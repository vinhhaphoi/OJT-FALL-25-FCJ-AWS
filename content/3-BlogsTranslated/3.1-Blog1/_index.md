---
title: "Blog 1"
date: "2025-12-01"
weight: 1
chapter: false
pre: " <b> 3.1. </b> "
---

# Harnessing the Power of Nested Materialized Views and exploring Cascading Refresh

### Introduction to Nested Materialized Views

Nested materialized views in Amazon Redshift allow you to create materialized views based on other materialized views. This capability enables a hierarchical structure of precomputed results, significantly enhancing query performance and data processing efficiency. With nested materialized views, you can build multi-layered data abstractions, creating increasingly complex and specialized views tailored to specific business needs. This layered approach offers several advantages:

- **Improved Query Performance**: Each level of the nested materialized view hierarchy serves as a cache, allowing queries to quickly access pre-computed data without the need to traverse the underlying base tables.
- **Reduced Computational Load**: By offloading the computational work to the materialized view refresh process, you can significantly reduce the runtime and resource utilization of your day-to-day queries.
- **Simplified Data Modeling**: Nested materialized views enable you to create a more modular and extensible data model, where each layer represents a specific business concept or use case.
- **Incremental Refreshes**: The Redshift materialized views support incremental refreshes, allowing you to update only the changed data within the nested hierarchy, further optimizing the refresh process.
- **Cascading Materialized Views**: The Redshift materialized views with CASCADE can help business users to eliminate the need of creating and maintaining their own data pipelines.

You can implement nested materialized views using the [CREATE MATERIALIZED VIEW](https://docs.aws.amazon.com/redshift/latest/dg/materialized-view-create-sql-command.html) statement, which allows referencing other materialized views in the definition. Common use cases include:

- Modular data transformation pipelines
- Hierarchical aggregations for progressive analysis
- Multi-level data validation pipelines
- Historical data snapshot management
- Optimized BI reporting with precomputed results

### Architecture

Architectural diagram depicting Amazon Redshift’s nested materialized view structure. Shows multiple base tables (orange) connecting to materialized views (red), with connections to a nested view layer and data sharing table (green). Includes integration points for users and QuickSight visualization.

1. **Base Table(s)**: These are the underlying base tables that contain the raw data for your data warehouse. It can be local tables or data sharing tables.
2. **Base Materialized View(s)**: These are the first-level materialized views that are created directly on top of the base tables. These views encapsulate common data transformations and aggregations. This can serve as the base for the nested materialized view and also be accessed by users directly.
3. **Nested Materialized View(s)**: These are the second level (or higher) materialized views that are created based on the base materialized views. The nested materialized view can further aggregate, filter, or transform the data from the base materialized views.
4. **Application/Users/BI Reporting**: The application or business intelligence (BI) tools interact with the nested materialized views to generate reports and dashboards. The nested views provide a more optimized and precomputed data structure for efficient querying and reporting.

### Creating and using nested materialized views

To demonstrate how nested materialized views work in Amazon Redshift, we’ll use the TPC-DS dataset. We’ll create three queries using the STORE, STORE_SALES, CUSTOMER, and CUSTOMER_ADDRESS tables to simulate data warehouse reports. This example will illustrate how multiple reports can share result sets and how materialized views can improve both resource efficiency and query performance.

Let’s consider the following queries as dashboard queries:

```sql
SELECT cust.c_customer_id, cust.c_first_name, cust.c_last_name, sales.ss_item_sk, sales.ss_quantity, cust.c_current_addr_sk
FROM store_sales sales
INNER JOIN customer cust ON sales.ss_customer_sk = cust.c_customer_sk;

SELECT cust.c_customer_id, cust.c_first_name, cust.c_last_name, sales.ss_item_sk, sales.ss_quantity, cust.c_current_addr_sk, store.s_store_name
FROM store_sales sales
INNER JOIN customer cust ON sales.ss_customer_sk = cust.c_customer_sk
INNER JOIN store store ON sales.ss_store_sk = store.s_store_sk;

SELECT cust.c_customer_id, cust.c_first_name, cust.c_last_name, sales.ss_item_sk, sales.ss_quantity, addr.ca_state
FROM store_sales sales
INNER JOIN customer cust ON sales.ss_customer_sk = cust.c_customer_sk
INNER JOIN store store ON sales.ss_store_sk = store.s_store_sk
INNER JOIN customer_address addr ON cust.c_current_addr_sk = addr.ca_address_sk;
```

Notice that the join between STORE_SALES and CUSTOMER tables is present at all 3 queries (dashboards).
The second query adds a join with STORE table and the third query is the second one with an extra join with CUSTOMER_ADDRESS table. This pattern is common in business intelligence scenarios. As mentioned earlier, using a materialized view can speed up queries because the result set is stored and ready to be delivered to the user, avoiding reprocessing of the same data. In cases like this, we can use nested materialized views to reuse already processed data.

When transforming our queries into a set of nested materialized views, the result would be as below:

```sql
CREATE MATERIALIZED VIEW StoreSalesCust as
SELECT cust.c_customer_id, cust.c_first_name, cust.c_last_name, sales.ss_item_sk, sales.ss_store_sk, sales.ss_quantity, cust.c_current_addr_sk
FROM store_sales sales
INNER JOIN customer cust ON sales.ss_customer_sk = cust.c_customer_sk;

CREATE MATERIALIZED VIEW StoreSalesCustStore as
SELECT storesalescust.c_customer_id, storesalescust.c_first_name, storesalescust.c_last_name, storesalescust.ss_item_sk, storesalescust.ss_quantity, storesalescust.c_current_addr_sk, store.s_store_name
FROM StoreSalesCust storesalescust
INNER JOIN store store ON storesalescust.ss_store_sk = store.s_store_sk;

CREATE MATERIALIZED VIEW StoreSalesCustAddress as
SELECT storesalescuststore.c_customer_id, storesalescuststore.c_first_name, storesalescuststore.c_last_name, storesalescuststore.ss_item_sk, storesalescuststore.ss_quantity, addr.ca_state
FROM StoreSalesCustStore storesalescuststore
INNER JOIN customer_address addr ON storesalescuststore.c_current_addr_sk = addr.ca_address_sk;
```

Nested materialized views can improve performance and resource efficiency by reusing initial view results, minimizing redundant joins, and working with smaller result sets. This creates a hierarchical structure where materialized views depend on one another. Due to these dependencies, you must refresh the views in a specific order.

With the new option “REFRESH MATERIALIZED VIEW mv_name CASCADE” you will be able to refresh the entire chain of dependencies for the materialized views you have. Note that in this example we are using the third materialized view, StoreSalesCustAddress, and this will refresh all 3 materialized views because they are dependent on each other.

If we use the second materialized view with the CASCADE option, we will refresh only the first and second materialized views, leaving the third unchanged. This may be useful when we need to keep some materialized views with less current data than others.

The [SVL_MV_REFRESH_STATUS](https://docs.aws.amazon.com/redshift/latest/dg/r_SVL_MV_REFRESH_STATUS.html) system view reveals the refresh sequence of materialized views. When triggering a cascade refresh on StoreSalesCustAddress, the system follows the dependency chain we established: StoreSalesCust refreshes first, followed by StoreSalesCustStore, and finally StoreSalesCustAddress. This demonstrates how the refresh operation respects the hierarchical structure of our materialized views.

#### Considerations

Consider a dependency chain where StoreSalesCust (A) → StoreSalesCustStore (B) → StoreSalesCustAddress (C).

- The CASCADE refresh behavior works as follows:
  - When refreshing C with CASCADE: A, B, and C will all be refreshed.
  - When refreshing B with CASCADE: Only A and B will be refreshed.
  - When refreshing A with CASCADE: Only A will be refreshed.
  - If you specifically need to refresh A and C but not B, you must perform separate refresh operations without using CASCADE—first refresh A, then refresh C directly.

### Best Practices for Materialized View

- **Improve the source query**: Start with a well-optimized SELECT statement for your materialized view. This is especially important for views that need full rebuilds during each refresh.
- **Plan refresh strategies**: When creating materialized views that depend on other materialized views, you cannot use AUTO REFRESH YES. Instead, implement orchestrated refresh mechanisms using Redshift Data API with Amazon EventBridge for scheduling and AWS Step Functions for workflow management.
- **Leverage distribution and sort keys**: Properly configure distribution and sort keys on materialized views based on their query patterns to optimize performance. Well-chosen keys improve query speed and reduce I/O operations.

### Clean up

Complete the following steps to clean up your resources:

- Delete the Redshift provisioned replica cluster or the Redshift serverless endpoints created for this exercise
  or
- Drop only the Materialized view which you have created for testing

### Conclusion

This post showed how to create nested Amazon Redshift materialized views and refresh the child materialized views using the new REFRESH CASCADE option. You can quickly build and maintain efficient data processing pipelines and seamlessly extend the low latency query execution benefits of materialized views to data analysis.

If you’re unfamiliar with materialized views but want to boost your workload performance, Amazon Redshift offers an Automated materialized view (auto-MV) feature. This intelligent system monitors your workload and automatically creates materialized views to enhance overall performance. For more detailed information on this feature, please refer to [Automated materialized views](https://docs.aws.amazon.com/redshift/latest/dg/materialized-view-auto-mv.html).

### About the authors

**Ritesh Kumar Sinha** is an Analytics Specialist Solutions Architect based out of San Francisco. He has helped customers build scalable data warehousing and big data solutions for over 16 years. He loves to design and build efficient end-to-end solutions on AWS. In his spare time, he loves reading, walking, and doing yoga.

**Raza Hafeez** is a Senior Product Manager at Amazon Redshift. He has over 13 years of professional experience building and optimizing enterprise data warehouses and is passionate about enabling customers to realize the power of their data. He specializes in migrating enterprise data warehouses to AWS Modern Data Architecture.

**Ricardo Serafim** is a Senior Analytics Specialist Solutions Architect at AWS. He has been helping companies with Data Warehouse solutions since 2007.
