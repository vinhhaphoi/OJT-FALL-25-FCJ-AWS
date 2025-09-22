---
title: "Week 2 Worklog"
date: "2025-08-12"
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Week 2 Objectives:

* Understand AWS Identity and Access Management (IAM)
* Grant access to AWS services with an IAM role
* Understand AWS Cloud9 and its features
* Get started with AWS Cloud9
* Hosting static website with Amazon S3
* Master Amazon Relational Database Service (Amazon RDS)
* Learn container technology with Amazon Lightsail Container
* Deploy applications using Docker on Ubuntu
* Implement Auto Scaling Groups for scalable applications
* Configure Load Balancers for high availability
* Understand how to monitoring with CloudWatch
* Master AWS Command Line Interface (CLI) for infrastructure management
* Understand Amazon DynamoDB NoSQL database service
* Learn Amazon ElastiCache for Redis in-memory caching service
* Learn Python SDK (Boto3) for AWS service automation
* Master AWS Networking and VPC architecture fundamentals
* Understand advanced networking concepts: Transit Gateway, VPN, Direct Connect
* Learn Amazon CloudFront CDN for global content delivery
* Master advanced CloudFront features: Lambda@Edge, Origin Groups, and monitoring


### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Understand and implement IAM roles and policies <br> - Understand AWS Cloud9 can do and how to implement <br> - Explore Basic features in AWS Cloud 9 <br> - Using AWS CLI for list EC2 instances in account <br> - Starting services with Amazon S3 Services <br> - **Practice:** <br>&emsp; + Create IAM user and access key <br>&emsp; + Attach IAM policy to grant necessary permissions <br>&emsp; + AWS Cloud9: <br>&emsp;&emsp; - By using Command Line <br>&emsp;&emsp; - Working with text file <br>&emsp;&emsp; - Return to Dashboard <br>&emsp; + Using command: aws ec2 describe-instances for list EC2 instances in account in AWS CLI command <br>&emsp; + Amazon S3: <br>&emsp;&emsp; - Hosting static website with Amazon S3 <br>&emsp;&emsp; - Using CloudFront for hosting static website | 09/15/2025 | 09/15/2025 | [AWS Cloud9](https://000049.awsstudygroup.com/) <br> <br> [Grant permission for IAM <br> role](https://000048.awsstudygroup.com/) <br> <br> [Hosting static website <br> with Amazon S3](https://000057.awsstudygroup.com/)|
| 3   | - Explore Amazon Relational Database Service (Amazon RDS) and their benefits <br> - Amazon Lightsail Container: <br>&emsp; +  Understand Lightsail Container <br>&emsp; + Deploy container image to Amazon Lightsail Container by using Docker on Ubuntu <br> - Explore for deploy FCJ Management with Auto Scaling Group <br> - **Practice:** <br>&emsp; + Deploy Amazon RDS <br>&emsp; + Deploy Application with MySQL <br>&emsp; + Backup and Restore in Amazon RDS <br>&emsp; + Build container image and deploy <br>&emsp; + Deploy FCJ Management: <br>&emsp;&emsp; - Create Launch Template and Setup Load balance <br>&emsp;&emsp; - Create Auto Scaling Group | 09/16/2025 | 09/16/2025 | [Amazon RDS](https://000005.awsstudygroup.com/) <br> <br> [Amazon Lightsail](https://000046.awsstudygroup.com/) <br> <br> [Deploy an application <br> with Amazon EC2 Auto <br> Scaling](https://000006.awsstudygroup.com/)|
| 4   | - Learn and create CloudFormation with template file <br> - Using CloudWatch Metrics, CloudWatch Logs and CloudWatch dashboard <br> - Understand Hybrid DNS with Route 53 Resolver <br> - **Practice:** <br>&emsp; + CloudWatch: <br>&emsp;&emsp; - CloudWatch lets users choose and display metrics from their applications <br>&emsp;&emsp; - Filter data using advanced search expressions <br>&emsp;&emsp; - Apply math calculations for deeper insights like averages or rankings <br>&emsp;&emsp; - Add dynamic labels to improve chart readability and interpretation. <br>&emsp; + Route 53 Resolver: <br>&emsp;&emsp; - Initialize CloudFormation by template. <br>&emsp;&emsp; - Create and deploy Microsoft AD (AWS Managed Microsoft Active Directory) <br>&emsp;&emsp; - Setup DNS with In/Out Endpoint| 09/17/2025 | 09/17/2025      | [CloudWatch workshop](https://000008.awsstudygroup.com/) <br> <br> [Hybrid DNS with Route 53](https://000010.awsstudygroup.com/)|
| 5   | - Master AWS CLI fundamentals and EC2 management <br> - Learn EC2 instance types, AMI, EBS, and SSH connections <br> - Understand Amazon DynamoDB NoSQL database concepts <br> - Learn Amazon ElastiCache for Redis in-memory caching <br> - Learn Python SDK (Boto3) for AWS services <br> - **Practice:** <br>&emsp; + Configure AWS CLI with profiles and output formats <br>&emsp; + View resources: `aws ec2 describe-instances`, `aws s3 ls` <br>&emsp; + Create Key Pair and Security Groups <br>&emsp; + Launch EC2 with `aws ec2 run-instances` <br>&emsp; + Connect via SSH and terminate instances <br>&emsp; + Amazon DynamoDB Operations: <br>&emsp;&emsp; - Create tables and configure primary keys <br>&emsp;&emsp; - Perform CRUD operations (Create, Read, Update, Delete) <br>&emsp;&emsp; - Query and Scan data with Python Boto3 <br>&emsp;&emsp; - Load sample data and manage table operations <br>&emsp; + Amazon ElastiCache Redis Operations: <br>&emsp;&emsp; - Create ElastiCache clusters (mode disabled/enabled) <br>&emsp;&emsp; - Connect to Redis clusters with Python <br>&emsp;&emsp; - Set/Get strings and hash operations <br>&emsp;&emsp; - Implement Publish/Subscribe messaging <br>&emsp;&emsp; - Work with Redis streams for data processing | 09/18/2025   | 09/18/2025      | [Getting Started with AWS CLI](https://000011.awsstudygroup.com/) <br> <br> [Work with Amazon <br> DynamoDB](https://000060.awsstudygroup.com/) <br> <br> [Amazon ElastiCache <br> - Redis](https://000061.awsstudygroup.com/) |
| 6   | - Master AWS Networking fundamentals and VPC architecture <br> - Learn VPC components: Subnets, Route Tables, Internet Gateway, NAT Gateway <br> - Understand Security Groups and NACLs for network security <br> - Explore VPC Peering, Transit Gateway, and hybrid connectivity <br> - Learn Route 53 DNS services and Load Balancing concepts <br> - Master Amazon CloudFront CDN and content delivery <br> - **Practice:** <br>&emsp; + VPC Components Deep Dive: <br>&emsp;&emsp; - Create and configure VPC with multiple subnets <br>&emsp;&emsp; - Configure Route Tables and Internet/NAT Gateways <br>&emsp;&emsp; - Implement Security Groups and Network ACLs <br>&emsp; + Advanced Networking: <br>&emsp;&emsp; - Set up Transit Gateway and Site-to-Site VPNs <br>&emsp;&emsp; - Configure Route 53 DNS endpoints and hosted zones <br>&emsp;&emsp; - Implement VPC Endpoints for AWS services <br>&emsp;&emsp; - Create VPC Peering connections <br>&emsp;&emsp; - Deploy Network Load Balancer configurations <br>&emsp;    + CloudFront Content Delivery: <br>&emsp;&emsp; - Create S3 bucket for static website hosting <br>&emsp;&emsp; - Configure CloudFront distribution with S3 origin <br>&emsp;&emsp; - Implement Origin Access Identity (OAI) for security <br>&emsp;&emsp; - Test performance improvements and edge locations <br>&emsp;&emsp; - Configure custom domain names and SSL certificates <br>&emsp; + Advanced CloudFront Features: <br>&emsp;&emsp; - Configure distribution invalidations for cache management <br>&emsp;&emsp; - Set up custom error pages and Origin Groups for failover <br>&emsp;&emsp; - Implement response headers and cache behaviors <br>&emsp;&emsp; - Create and deploy Lambda@Edge functions <br>&emsp;&emsp; - Monitor performance with CloudFront metrics and logs | 09/19/2025 | 09/19/2025      | [AWS Networking and Content Delivery](https://000092.awsstudygroup.com/) <br> <br> [CloudFront with S3 <br> Bucket Origin](https://000094.awsstudygroup.com/) <br> <br> [Advanced CloudFront Workshop](https://000130.awsstudygroup.com/) |



### Week 2 Achievements:

* **AWS Identity and Access Management (IAM) Mastery:**
  * Comprehensive understanding of IAM concepts: Users, Groups, Roles, and Policies
  * Successfully created and managed IAM users with appropriate access keys
  * Configured and attached IAM policies to grant necessary permissions
  * Understood least privilege principle and IAM security best practices

* **AWS Cloud9 Development Environment Proficiency:**
  * Mastered AWS Cloud9 features and capabilities
  * Gained proficiency in using Cloud9 IDE for development tasks
  * Effectively worked with command line interface within Cloud9
  * Managed files and performed text editing in cloud-based environment
  * Navigated and utilized Cloud9 dashboard efficiently

* **Advanced AWS CLI Skills:**
  * Successfully utilized AWS CLI within Cloud9 environment
  * Executed `aws ec2 describe-instances` command to list and manage EC2 instances
  * Integrated AWS CLI commands into daily workflow
  * Understood how to combine GUI and CLI for efficient AWS resource management

* **Amazon S3 & Static Website Hosting:**
  * Understood basic concepts of Amazon S3 service
  * Grasped S3 bucket and object storage functionality
  * Successfully deployed static website hosting with Amazon S3
  * Configured S3 bucket to serve web content
  * Understood use cases and benefits of S3 in cloud architecture
  * Integrated CloudFront to enhance performance and distribution of static websites
  * Mastered best practices for web hosting on AWS cloud platform

* **Amazon RDS Database Management:**
  * Mastered concepts and benefits of Amazon Relational Database Service (RDS)
  * Successfully deployed and configured Amazon RDS instances
  * Developed and deployed applications integrated with MySQL database
  * Performed backup and restore operations in Amazon RDS
  * Understood best practices for database management on cloud
  * Gained proficiency in database security and performance optimization in RDS environment

* **Container Technology & Amazon Lightsail:**
  * Understood Amazon Lightsail Container service and its use cases
  * Gained proficiency in building and managing container images with Docker
  * Successfully deployed container applications to Amazon Lightsail Container
  * Worked effectively with Docker on Ubuntu environment
  * Mastered containerization concepts and best practices
  * Understood how to optimize container deployment for production workloads

* **Auto Scaling & Load Balancing:**
  * Mastered concepts and benefits of Amazon EC2 Auto Scaling
  * Successfully deployed FCJ Management application with Auto Scaling Group
  * Created and configured Launch Templates for scalable applications
  * Set up and managed Load Balancers for high availability
  * Understood scaling policies and monitoring for dynamic workloads
  * Gained proficiency in cost optimization strategies with auto scaling

* **Infrastructure as Code & CloudFormation:**
  * Mastered Infrastructure as Code (IaC) concepts and benefits
  * Gained proficiency in creating and managing CloudFormation templates
  * Successfully deployed and managed AWS resources using CloudFormation
  * Understood best practices for template design and stack management
  * Mastered version control and rollback strategies for infrastructure code
  * Automated resource deployment and configuration management

* **CloudWatch Monitoring & Observability:**
  * Mastered CloudWatch Metrics, Logs, and Dashboard functionalities
  * Successfully established comprehensive monitoring for AWS applications
  * Used advanced search expressions to filter and analyze log data
  * Applied mathematical calculations for deeper insights and analytics
  * Created dynamic labels to improve chart readability and interpretation
  * Set up alerting and notification systems for proactive monitoring
  * Understood performance optimization based on monitoring data

* **Hybrid DNS & Route 53 Resolver:**
  * Mastered Hybrid DNS architecture and use cases
  * Successfully deployed and configured Route 53 Resolver endpoints
  * Set up AWS Managed Microsoft Active Directory integration
  * Configured inbound and outbound DNS resolution
  * Understood DNS security and performance optimization
  * Managed cross-premises DNS connectivity and troubleshooting

* **AWS CLI & Command Line Infrastructure Management:**
  * Mastered AWS Command Line Interface (CLI) installation and configuration
  * Successfully configured AWS CLI profiles for multiple environments
  * Understood and implemented different output formats (JSON, YAML, text, table)
  * Gained proficiency in using CLI auto-prompt for interactive command creation
  * Mastered infrastructure viewing and management through command line
  * Successfully used `aws ec2 describe-instances` for EC2 resource inspection
  * Implemented S3 bucket management using `aws s3 ls` commands
  * Understood regional resource management and cross-region operations

* **EC2 Lifecycle Management via CLI:**
  * Mastered complete EC2 instance lifecycle management through AWS CLI
  * Successfully created and managed AWS Key Pairs for secure access
  * Configured Security Groups and ingress rules for SSH access
  * Gained proficiency in launching EC2 instances using `aws ec2 run-instances`
  * Mastered SSH connection methods and troubleshooting
  * Successfully monitored instance status using CLI commands
  * Implemented proper resource cleanup and instance termination procedures
  * Understood EC2 instance types, AMI selection, and EBS volume management

* **Amazon DynamoDB NoSQL Database Mastery:**
  * Understood fundamental concepts of Amazon DynamoDB NoSQL database service
  * Mastered DynamoDB core components: Tables, Items, Attributes, and Primary Keys
  * Gained proficiency in DynamoDB secondary indexes and query optimization
  * Understood read consistency models and capacity management
  * Successfully implemented DynamoDB naming rules and data type specifications
  * Mastered backup and restore capabilities for data protection
  * Understood encryption at rest and security best practices
  * Gained expertise in scaling strategies and performance optimization

* **Python SDK (Boto3) & AWS Service Automation:**
  * Mastered Python Boto3 SDK for AWS service automation and integration
  * Understood the difference between Boto3 Client and Resource interfaces
  * Successfully configured AWS SDK with proper authentication methods
  * Gained proficiency in DynamoDB table creation and schema design
  * Mastered CRUD operations: Create, Read, Update, and Delete data
  * Successfully implemented Query and Scan operations for data retrieval
  * Understood batch operations and efficient data loading techniques
  * Implemented proper error handling and resource management in Python code

* **Amazon ElastiCache Redis In-Memory Caching:**
  * Mastered Amazon ElastiCache for Redis concepts and architecture
  * Understood clusters, nodes, and shards configuration for high availability
  * Successfully created and managed ElastiCache clusters (mode disabled/enabled)
  * Gained proficiency in Redis data partitioning across up to 500 shards
  * Mastered automatic failure detection and recovery mechanisms
  * Successfully integrated ElastiCache with EC2, CloudWatch, and other AWS services
  * Understood backup management, patching, and security features
  * Implemented Redis operations: strings, hashes, Pub/Sub, and streams
  * Mastered performance optimization and cost-effective caching strategies

* **AWS Networking & VPC Architecture Mastery:**
  * Mastered Amazon Virtual Private Cloud (VPC) concepts and architecture
  * Understood AWS global infrastructure: Regions, Availability Zones, and Edge Locations
  * Successfully configured VPC components: Subnets, Route Tables, and CIDR blocks
  * Gained proficiency in Elastic Network Interfaces (ENI) and Elastic IP addresses
  * Mastered Internet Gateway and NAT Gateway configurations for internet connectivity
  * Implemented VPC Endpoints for secure AWS service connections without internet
  * Understood network security with Security Groups and Network ACLs (NACLs)
  * Mastered stateful vs stateless firewall concepts and rule configurations

* **Advanced Networking & Hybrid Connectivity:**
  * Mastered VPC Peering for inter-VPC communication and limitations
  * Gained expertise in Transit Gateway for centralized network hub architecture
  * Successfully configured VPN Site-to-Site for hybrid cloud connectivity
  * Understood AWS Direct Connect for dedicated private connections
  * Mastered Route 53 DNS services, endpoints, and internal hosted zones
  * Implemented Network Load Balancer (NLB) for high-performance Layer 4 load balancing
  * Understood Transit Gateway Network Manager for network visualization
  * Mastered complex routing scenarios and traffic flow optimization

* **Network Security & Performance Optimization:**
  * Implemented comprehensive network security using multiple layers of protection
  * Mastered Security Group rules and best practices for least privilege access
  * Successfully configured Network ACLs for subnet-level security controls
  * Understood VPC Flow Logs for network monitoring and troubleshooting
  * Implemented network segmentation strategies for different environments
  * Mastered DNS resolution and Route 53 advanced features
  * Optimized network performance through proper subnet and routing design
  * Understood cost optimization strategies for networking services

* **Amazon CloudFront Content Delivery Network:**
  * Mastered CDN concepts and global edge locations
  * Successfully created and configured CloudFront distributions with S3 origins
  * Implemented Origin Access Identity (OAI) for enhanced security
  * Understood performance benefits and edge caching strategies
  * Mastered custom domain configuration and SSL certificate management
  * Mastered global content delivery optimization techniques

* **Advanced CloudFront Features & Lambda@Edge:**
  * Expertly configured distribution invalidations for efficient cache management
  * Successfully implemented custom error pages for enhanced user experience
  * Mastered Origin Groups for automatic failover and high availability
  * Configured response headers for security and performance optimization
  * Created custom cache behaviors for different content types
  * Developed and deployed Lambda@Edge functions for request processing
  * Monitored CloudFront performance using comprehensive metrics and logs
  * Applied CloudFront best practices including compression and SSL/TLS encryption

* **Cloud Development Workflow:**
  * Established complete development environment on cloud
  * Developed skills in working with cloud-based tools and services
  * Understood how to integrate multiple AWS services in a workflow
  * Built foundation for advanced cloud development practices
  * Integrated database services into cloud application architecture
  * Mastered containerization and auto scaling in cloud architecture
  * Implemented Infrastructure as Code and comprehensive monitoring solutions
  * Designed secure and scalable network architectures for production workloads
