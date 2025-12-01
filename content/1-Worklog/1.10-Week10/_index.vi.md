---
title: "Worklog Tuần 10"
date: "2025-11-10"
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

- Làm chủ trực quan hóa dữ liệu với Amazon QuickSight.
- Đi sâu vào Data Engineering trên AWS.
- Xây dựng serverless data lakes và pipelines xử lý dữ liệu thời gian thực.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Tài liệu                                                                                                                                                                                                |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2   | - Học Amazon QuickSight cho trực quan hóa dữ liệu <br> - Làm chủ Data Engineering trên AWS <br> - Hiểu kiến trúc serverless data lake <br> - **Thực hành:** <br>&emsp; + **Làm quen với QuickSight:** <br>&emsp;&emsp; - Hiểu các khái niệm QuickSight (Data source, Dataset, Analysis, Visual, Dashboard) <br>&emsp;&emsp; - Chuẩn bị dữ liệu cho phân tích <br>&emsp;&emsp; - Xây dựng interactive dashboards <br>&emsp;&emsp; - Cải thiện dashboard và thêm tính tương tác <br>&emsp; + **Data Engineering Immersion Day:** <br>&emsp;&emsp; - Triển khai phát hiện bất thường clickstream thời gian thực với Apache Flink <br>&emsp;&emsp; - Ingest dữ liệu sử dụng AWS DMS <br>&emsp;&emsp; - Chuyển đổi dữ liệu với AWS Glue <br>&emsp;&emsp; - Truy vấn và trực quan hóa với Athena và QuickSight <br>&emsp;&emsp; - Tự động hóa quy trình Data Lake <br>&emsp;&emsp; - Chuẩn bị dữ liệu với Glue DataBrew                                                                                           | 10/11/2025   | 10/11/2025      | [Làm quen với Quick Sight <br> Trực quan hóa dashboard](https://000073.awsstudygroup.com/) <br> <br> [Data Engineering Immersion Day <br> Serverless data lake](https://000105.awsstudygroup.com/)      |
| 3   | - Làm chủ Amazon Athena cho phân tích tương tác <br> - Đi sâu vào quản lý AWS RDS PostgreSQL <br> - Hiểu serverless SQL querying và tối ưu hóa database <br> - **Thực hành:** <br>&emsp; + **Amazon Athena Workshop:** <br>&emsp;&emsp; - Hiểu kiến trúc Athena và serverless analytics <br>&emsp;&emsp; - Chạy các truy vấn SQL tương tác trên dữ liệu S3 <br>&emsp;&emsp; - Triển khai Athena cho Apache Spark <br>&emsp;&emsp; - Cấu hình Athena Federation cho các nguồn dữ liệu bên ngoài <br>&emsp;&emsp; - Tối ưu hóa hiệu suất truy vấn và chi phí <br>&emsp; + **AWS RDS PostgreSQL Foundation:** <br>&emsp;&emsp; - Thực hiện nâng cấp và bảo trì cơ sở dữ liệu <br>&emsp;&emsp; - Triển khai giám sát và tối ưu hóa hiệu suất <br>&emsp;&emsp; - Cấu hình chiến lược sao lưu và phục hồi <br>&emsp;&emsp; - Triển khai khả năng mở rộng database và read replicas <br>&emsp;&emsp; - Quản lý parameter groups để tinh chỉnh <br>&emsp;&emsp; - Cấu hình High Availability (Multi-AZ) deployments | 11/11/2025   | 11/11/2025      | [Amazon Athena Workshop <br> Phân tích tương tác serverless](https://000106.awsstudygroup.com/) <br> <br> [AWS RDS PostgreSQL Foundation <br> Quản lý cơ sở dữ liệu](https://000115.awsstudygroup.com/) |
| 4   | - Học AWS RDS PostgreSQL cho phát triển ứng dụng <br> - Làm chủ Amazon SageMaker cho Machine Learning <br> - Hiểu quy trình ML từ Feature Engineering đến Deployment <br> - **Thực hành:** <br>&emsp; + **AWS RDS PostgreSQL cho Developers:** <br>&emsp;&emsp; - Kết nối đến RDS PostgreSQL từ ứng dụng <br>&emsp;&emsp; - Triển khai code kết nối cơ sở dữ liệu (Python/Node.js) <br>&emsp;&emsp; - Deploy ứng dụng Node.js với RDS backend <br>&emsp;&emsp; - Quản lý thông tin đăng nhập và bảo mật database <br>&emsp; + **SageMaker Immersion Day:** <br>&emsp;&emsp; - Hiểu kiến trúc và khả năng của SageMaker <br>&emsp;&emsp; - Thực hiện Feature Engineering trên datasets <br>&emsp;&emsp; - Train, Tune, và Deploy mô hình XGBoost <br>&emsp;&emsp; - Triển khai Lift-and-Shift cho ML workloads <br>&emsp;&emsp; - Giám sát và debug mô hình ML                                                                                                                                               | 12/11/2025   | 12/11/2025      | [AWS RDS PostgreSQL cho Developers <br> Tích hợp ứng dụng](https://000116.awsstudygroup.com/) <br> <br> [SageMaker Immersion Day <br> Quy trình Machine Learning](https://000200.awsstudygroup.com/)    |

### Kết quả đạt được tuần 10:

- **Thành thạo Trực quan hóa Amazon QuickSight:**

  - Thành thạo các khái niệm cốt lõi và kiến trúc QuickSight
  - Thành công kết nối với nhiều nguồn dữ liệu khác nhau
  - Tạo và quản lý datasets cho phân tích
  - Xây dựng dashboards tương tác và trực quan
  - Triển khai các loại biểu đồ và tính tương tác cho dashboard
  - Áp dụng best practices cho trực quan hóa dữ liệu

- **Thành thạo Phân tích Amazon Athena:**

  - Thành thạo phân tích tương tác serverless với Athena
  - Thành công chạy các truy vấn SQL phức tạp trên S3 data lakes
  - Triển khai Athena cho khối lượng công việc Apache Spark
  - Cấu hình Athena Federation để truy vấn các nguồn dữ liệu bên ngoài
  - Tối ưu hóa hiệu suất truy vấn và quản lý chi phí hiệu quả
  - Áp dụng best practices cho phân tích dữ liệu serverless

- **Thành thạo Phát triển RDS PostgreSQL:**

  - Thành thạo phát triển ứng dụng với RDS PostgreSQL
  - Thành công kết nối ứng dụng với managed databases
  - Deploy ứng dụng Node.js có khả năng mở rộng với RDS
  - Triển khai các mẫu kết nối cơ sở dữ liệu an toàn

- **Chuyên gia Amazon SageMaker ML:**
  - Thành thạo quy trình ML end-to-end trên SageMaker
  - Thành công thực hiện Feature Engineering
  - Train, tune, và deploy các mô hình XGBoost
  - Áp dụng best practices cho triển khai mô hình
