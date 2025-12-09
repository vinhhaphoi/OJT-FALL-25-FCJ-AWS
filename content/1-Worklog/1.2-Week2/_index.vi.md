---
title: "Worklog Tuần 2"
date: "2025-08-12"
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

- Hiểu AWS Identity and Access Management (IAM)
- Cấp quyền truy cập cho các dịch vụ AWS với IAM role
- Hiểu AWS Cloud9 và các tính năng của nó
- Bắt đầu làm việc với AWS Cloud9
- Hosting website tĩnh với Amazon S3
- Thành thạo Amazon Relational Database Service (Amazon RDS)
- Tìm hiểu về công nghệ container với Amazon Lightsail Container
- Deploy ứng dụng sử dụng Docker trên Ubuntu
- Triển khai Auto Scaling Groups cho các ứng dụng có thể mở rộng
- Cấu hình Load Balancers cho tính khả dụng cao
- Hiểu cách monitoring với CloudWatch
- Thành thạo AWS Command Line Interface (CLI) để Quản lý hạ tầng
- Hiểu Amazon DynamoDB NoSQL database service
- Tìm hiểu về Amazon ElastiCache for Redis in-memory caching service
- Tìm hiểu về Python SDK (Boto3) cho AWS service automation
- Thành thạo AWS Networking và VPC architecture fundamentals
- Hiểu advanced networking concepts: Transit Gateway, VPN, Direct Connect
- Thành thạo Amazon CloudFront CDN cho global content delivery
- Thành thạo chuyên sâu về CloudFront features: Lambda@Edge, Origin Groups, và monitoring

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Ngày bắt đầu | Ngày hoàn thành | Tài liệu                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2    | - Hiểu và triển khai IAM roles và policies <br> - Hiểu AWS Cloud9 có thể làm gì và cách triển khai <br> - Khám phá các tính năng cơ bản trong AWS Cloud 9 <br> - Sử dụng AWS CLI để liệt kê EC2 instances trong tài khoản <br> - Bắt đầu các dịch vụ với Amazon S3 Services <br> - **Thực hành:** <br>&emsp; + Tạo IAM user và access key <br>&emsp; + Gắn IAM policy để cấp các quyền cần thiết <br>&emsp; - AWS Cloud9: <br>&emsp;&emsp; - Sử dụng Command Line <br>&emsp;&emsp; - Làm việc với text file <br>&emsp;&emsp; - Quay lại Dashboard <br>&emsp; + Sử dụng lệnh: aws ec2 describe-instances để liệt kê EC2 instances trong tài khoản bằng AWS CLI command <br>&emsp; - Amazon S3: <br>&emsp;&emsp; + Hosting website tĩnh với Amazon S3 <br>&emsp;&emsp; + Sử dụng CloudFront để hosting website tĩnh                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 09/15/2025   | 09/15/2025      | [AWS Cloud9 IDE - Tạo Cloud9 instance, sử dụng command line, chỉnh sửa files và tích hợp AWS CLI](https://000049.awsstudygroup.com/) <br> <br> [Quản lý IAM Roles và Quyền truy cập - Tạo IAM users, access keys và gắn IAM roles cho EC2](https://000048.awsstudygroup.com/) <br> <br> [S3 Hosting Website Tĩnh - Cấu hình S3 buckets, bật static hosting, tích hợp CloudFront, versioning và multi-region replication](https://000057.awsstudygroup.com/)                        |
| 3    | - Khám phá Amazon Relational Database Service (Amazon RDS) và các tính năng đi kèm <br> - Amazon Lightsail Container: <br>&emsp; + Hiểu về Lightsail Container <br>&emsp; + Deploy container image lên Amazon Lightsail Container bằng Docker trên Ubuntu <br> - Khám phá deploy FCAJ Management với Auto Scaling Group <br> - **Thực hành:** <br>&emsp; + Triển khai Amazon RDS <br>&emsp; + Triển khai Application với MySQL <br>&emsp; + Backup và Restore trong Amazon RDS <br>&emsp; + Build container image và deploy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 09/16/2025   | 09/16/2025      | [Amazon RDS Database - Triển khai RDS instances, tích hợp ứng dụng MySQL và thực hiện backup và restore](https://000005.awsstudygroup.com/) <br> <br> [Dịch vụ Lightsail Container - Build và deploy Docker container images sử dụng Ubuntu và AWS CLI](https://000046.awsstudygroup.com/) <br> <br> [Triển khai EC2 Auto Scaling - Tạo launch templates, cấu hình load balancers và kiểm thử manual, scheduled, dynamic và predictive scaling](https://000006.awsstudygroup.com/) |
| 4    | - Tìm hiểu về và tạo CloudFormation với template file <br> - Sử dụng CloudWatch Metrics, CloudWatch Logs và CloudWatch dashboard <br> - Hiểu Hybrid DNS với Route 53 Resolver <br> - **Thực hành:** <br>&emsp; + CloudWatch: <br>&emsp;&emsp; - CloudWatch cho phép người dùng chọn và hiển thị metrics từ các ứng dụng của họ <br>&emsp;&emsp; - Lọc dữ liệu sử dụng advanced search expressions <br>&emsp;&emsp; - Áp dụng tính toán toán học để có insights sâu hơn như averages hoặc rankings <br>&emsp;&emsp; - Thêm dynamic labels để cải thiện khả năng đọc và diễn giải biểu đồ. <br>&emsp; + Route 53 Resolver: <br>&emsp;&emsp; - Khởi tạo CloudFormation bằng template. <br>&emsp;&emsp; - Tạo và deploy Microsoft AD (AWS Managed Microsoft Active Directory) <br>&emsp;&emsp; - Setup DNS với In/Out Endpoint                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | 09/17/2025   | 09/17/2025      | [CloudWatch Monitoring - Cấu hình metrics, logs, insights, alarms và dashboards với search và math expressions](https://000008.awsstudygroup.com/) <br> <br> [Route 53 Hybrid DNS - Triển khai Microsoft AD, cấu hình inbound và outbound endpoints với CloudFormation](https://000010.awsstudygroup.com/)                                                                                                                                                                         |
| 5    | - Thành thạo AWS CLI cơ bản và quản lý EC2 <br> - Tìm hiểu EC2 instance types, AMI, EBS, và kết nối SSH <br> - Hiểu Amazon DynamoDB NoSQL database concepts <br> - Tìm hiểu về Amazon ElastiCache for Redis in-memory caching <br> - Tìm hiểu về Python SDK (Boto3) cho các dịch vụ AWS <br> - **Thực hành:** <br>&emsp; + Cấu hình AWS CLI với profiles và output formats <br>&emsp; + Xem tài nguyên: `aws ec2 describe-instances`, `aws s3 ls` <br>&emsp; + Tạo Key Pairs và Security Groups <br>&emsp; + Tạo EC2 với `aws ec2 run-instances` <br>&emsp; + Kết nối SSH và terminate instances <br>&emsp; + Amazon DynamoDB Operations: <br>&emsp;&emsp; - Tạo tables và cấu hình primary keys <br>&emsp;&emsp; - Thực hiện CRUD operations (Create, Read, Update, Delete) <br>&emsp;&emsp; - Query và Scan data với Python Boto3 <br>&emsp;&emsp; - Load sample data và quản lý table operations <br>&emsp; + Amazon ElastiCache Redis Operations: <br>&emsp;&emsp; - Tạo ElastiCache clusters (mode disabled/enabled) <br>&emsp;&emsp; - Kết nối Redis clusters với Python <br>&emsp;&emsp; - Set/Get strings và hash operations <br>&emsp;&emsp; - Triển khai Publish/Subscribe messaging <br>&emsp;&emsp; - Làm việc với Redis streams cho data processing                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 09/18/2025   | 09/18/2025      | [AWS CLI Cơ bản - Cài đặt CLI, quản lý EC2, S3, SNS, IAM, VPC và tạo resources qua command line](https://000011.awsstudygroup.com/) <br> <br> [Amazon DynamoDB với Python - Thực hành CRUD operations, queries và scans sử dụng Boto3 SDK](https://000060.awsstudygroup.com/) <br> <br> [ElastiCache cho Redis - Tạo clusters, thực hiện string và hash operations, Pub/Sub messaging và streams với Python SDK](https://000061.awsstudygroup.com/)                                |
| 6    | - Thành thạo AWS Networking cơ bản và kiến trúc VPC <br> - Tìm hiểu về các thành phần VPC: Subnets, Route Tables, Internet Gateway, NAT Gateway <br> - Hiểu Security Groups và NACLs cho network security <br> - Khám phá VPC Peering, Transit Gateway, và hybrid connectivity <br> - Tìm hiểu về Route 53 DNS services và Load Balancing concepts <br> - Thành thạo Amazon CloudFront CDN và content delivery <br> - **Thực hành:** <br>&emsp; + VPC Components Deep Dive: <br>&emsp;&emsp; - Tạo và cấu hình VPC với multiple subnets <br>&emsp;&emsp; - Cấu hình Route Tables và Internet/NAT Gateways <br>&emsp;&emsp; - Triển khai Security Groups và Network ACLs <br>&emsp; + Advanced Networking: <br>&emsp;&emsp; - Thiết lập Transit Gateway và Site-to-Site VPNs <br>&emsp;&emsp; - Cấu hình Route 53 DNS endpoints và hosted zones <br>&emsp;&emsp; - Triển khai VPC Endpoints cho AWS services <br>&emsp;&emsp; - Tạo VPC Peering connections <br>&emsp;&emsp; - Deploy Network Load Balancer configurations <br>&emsp; + CloudFront Content Delivery: <br>&emsp;&emsp; - Tạo S3 bucket cho static website hosting <br>&emsp;&emsp; - Cấu hình CloudFront distribution với S3 origin <br>&emsp;&emsp; - Triển khai Origin Access Identity (OAI) cho security <br>&emsp;&emsp; - Test performance improvements và edge locations <br>&emsp;&emsp; - Cấu hình custom domain names và SSL certificates <br>&emsp; + Advanced CloudFront Configure: <br>&emsp;&emsp; - Cấu hình distribution invalidations cho cache management <br>&emsp;&emsp; - Thiết lập custom error pages và Origin Groups cho failover <br>&emsp;&emsp; - Triển khai response headers và cache behaviors <br>&emsp;&emsp; - Tạo và deploy Lambda@Edge functions <br>&emsp;&emsp; - Monitor performance với CloudFront metrics và logs | 09/19/2025   | 09/19/2025      | [AWS Networking Cơ bản - Kiến trúc VPC, subnets, security groups, Transit Gateway, VPN và Route 53](https://000092.awsstudygroup.com/) <br> <br> [CloudFront với S3 Origin - Tạo S3 bucket, upload nội dung và cấu hình CloudFront distribution](https://000094.awsstudygroup.com/) <br> <br> [Tính năng CloudFront Nâng cao - Distribution invalidations, custom error pages, Origin Groups, Lambda@Edge functions và monitoring](https://000130.awsstudygroup.com/)              |

### Kết quả đạt được tuần 2:

- **Thành thạo AWS Identity and Access Management (IAM):**

  - Hiểu rõ các khái niệm IAM: Users, Groups, Roles, và Policies
  - Tạo và quản lý IAM users với access keys phù hợp
  - Cấu hình và gắn IAM policies để cấp quyền truy cập cần thiết
  - Hiểu nguyên tắc least privilege và best practices cho IAM security

- **Tìm hiểu chuyên sâu AWS Cloud9 Development Environment:**

  - Nắm vững các tính năng và khả năng của AWS Cloud9
  - Thành thạo sử dụng Cloud9 IDE cho development tasks
  - Làm việc hiệu quả với command line interface trong Cloud9
  - Quản lý files và text editing trong cloud-based environment
  - Điều hướng và sử dụng Cloud9 dashboard một cách thành thạo

- **Kỹ năng AWS CLI nâng cao:**

  - Sử dụng thành công AWS CLI trong môi trường Cloud9
  - Thực hiện lệnh `aws ec2 describe-instances` để liệt kê và quản lý EC2 instances
  - Tích hợp AWS CLI commands vào workflow hàng ngày
  - Hiểu cách kết hợp GUI và CLI để quản lý tài nguyên AWS hiệu quả

- **Amazon S3 & Static Website Hosting:**

  - Hiểu các khái niệm cơ bản của Amazon S3 service
  - Nắm vững cách thức hoạt động của S3 bucket và object storage
  - Thành công triển khai static website hosting với Amazon S3
  - Cấu hình S3 bucket để phục vụ web content
  - Hiểu use cases và benefits của S3 trong cloud architecture
  - Tích hợp CloudFront để cải thiện performance và distribution của static websites
  - Nắm vững best practices cho web hosting trên AWS cloud platform

- **Amazon RDS Database Management:**

  - Nắm vững các khái niệm và lợi ích của Amazon Relational Database Service (RDS)
  - Thành công triển khai và cấu hình Amazon RDS instances
  - Phát triển và triển khai applications tích hợp với MySQL database
  - Thực hiện backup và restore operations trong Amazon RDS
  - Hiểu các best practices cho database management trên cloud
  - Nắm vững database security và performance optimization trong RDS environment

- **Container Technology & Amazon Lightsail:**

  - Hiểu rõ về Amazon Lightsail Container service và các use cases
  - Thành thạo việc build và manage container images với Docker
  - Thành công deploy container applications lên Amazon Lightsail Container
  - Làm việc hiệu quả với Docker trên Ubuntu environment
  - Nắm vững containerization concepts và best practices
  - Hiểu cách tối ưu hóa container deployment cho production workloads

- **Auto Scaling & Load Balancing:**

  - Nắm vững các khái niệm và lợi ích của Amazon EC2 Auto Scaling
  - Thành công deploy FCAJ Management application với Auto Scaling Group
  - Tạo và cấu hình Launch Templates cho scalable applications
  - Thiết lập và quản lý Load Balancers cho high availability
  - Hiểu scaling policies và monitoring cho dynamic workloads
  - Nắm vững cost optimization strategies với auto scaling

- **Infrastructure as Code & CloudFormation:**

  - Nắm vững các khái niệm Infrastructure as Code (IaC) và lợi ích của nó
  - Thành thạo tạo và quản lý CloudFormation templates
  - Thành công deploy và quản lý AWS resources bằng CloudFormation
  - Hiểu best practices cho template design và stack management
  - Nắm vững version control và rollback strategies cho infrastructure code
  - Tự động hóa resource deployment và configuration management

- **CloudWatch Monitoring & Observability:**

  - Thành thạo CloudWatch Metrics, Logs, và Dashboard functionalities
  - Thành công thiết lập comprehensive monitoring cho AWS applications
  - Sử dụng advanced search expressions để filter và analyze log data
  - Áp dụng mathematical calculations cho deeper insights và analytics
  - Tạo dynamic labels để cải thiện chart readability và interpretation
  - Thiết lập alerting và notification systems cho proactive monitoring
  - Hiểu performance optimization dựa trên monitoring data

- **Hybrid DNS & Route 53 Resolver:**

  - Nắm vững Hybrid DNS architecture và use cases
  - Thành công deploy và cấu hình Route 53 Resolver endpoints
  - Thiết lập AWS Managed Microsoft Active Directory integration
  - Cấu hình inbound và outbound DNS resolution
  - Hiểu DNS security và performance optimization
  - Quản lý cross-premises DNS connectivity và troubleshooting

- **AWS CLI & Quản lý hạ tầng qua Command Line:**

  - Thành thạo cài đặt và cấu hình AWS Command Line Interface (CLI)
  - Cấu hình thành công AWS CLI profiles cho nhiều môi trường
  - Hiểu và áp dụng các output formats khác nhau (JSON, YAML, text, table)
  - Thành thạo sử dụng CLI auto-prompt để tạo lệnh tương tác
  - Nắm vững việc xem và Quản lý hạ tầng qua command line
  - Sử dụng thành công `aws ec2 describe-instances` để kiểm tra tài nguyên EC2
  - Quản lý S3 buckets bằng lệnh `aws s3 ls`
  - Hiểu quản lý tài nguyên theo region và cross-region operations

- **Quản lý EC2 Lifecycle qua CLI:**

  - Thành thạo quản lý toàn bộ vòng đời EC2 instance qua AWS CLI
  - Tạo và quản lý thành công AWS Key Pairs cho secure access
  - Cấu hình Security Groups và ingress rules cho SSH access
  - Thành thạo tạo EC2 instances bằng `aws ec2 run-instances`
  - Nắm vững các phương pháp kết nối SSH và troubleshooting
  - Theo dõi thành công trạng thái instance bằng CLI commands
  - Thực hiện resource cleanup và terminate instances đúng cách
  - Hiểu EC2 instance types, AMI selection, và EBS volume management

- **Thành thạo Amazon DynamoDB NoSQL Database:**

  - Hiểu các khái niệm cơ bản của Amazon DynamoDB NoSQL database service
  - Nắm vững DynamoDB core components: Tables, Items, Attributes, và Primary Keys
  - Thành thạo DynamoDB secondary indexes và query optimization
  - Hiểu read consistency models và capacity management
  - Thành công triển khai DynamoDB naming rules và data type specifications
  - Nắm vững backup và restore capabilities cho data protection
  - Hiểu encryption at rest và security best practices
  - Có chuyên môn trong scaling strategies và performance optimization

- **Python SDK (Boto3) & AWS Service Automation:**

  - Thành thạo Python Boto3 SDK cho AWS service automation và integration
  - Hiểu sự khác biệt giữa Boto3 Client và Resource interfaces
  - Cấu hình thành công AWS SDK với proper authentication methods
  - Thành thạo DynamoDB table creation và schema design
  - Nắm vững CRUD operations: Create, Read, Update, và Delete data
  - Thành công triển khai Query và Scan operations cho data retrieval
  - Hiểu batch operations và efficient data loading techniques
  - Triển khai proper error handling và resource management trong Python code

- **Amazon ElastiCache Redis In-Memory Caching:**

  - Thành thạo Amazon ElastiCache for Redis concepts và architecture
  - Hiểu clusters, nodes, và shards configuration cho high availability
  - Tạo và quản lý thành công ElastiCache clusters (mode disabled/enabled)
  - Thành thạo Redis data partitioning trên tới 500 shards
  - Nắm vững automatic failure detection và recovery mechanisms
  - Tích hợp thành công ElastiCache với EC2, CloudWatch, và AWS services khác
  - Hiểu backup management, patching, và security features
  - Triển khai Redis operations: strings, hashes, Pub/Sub, và streams
  - Thành thạo performance optimization và cost-effective caching strategies

- **Thành thạo AWS Networking & Kiến trúc VPC:**

  - Nắm vững Amazon Virtual Private Cloud (VPC) concepts và architecture
  - Hiểu AWS global infrastructure: Regions, Availability Zones, và Edge Locations
  - Cấu hình thành công VPC components: Subnets, Route Tables, và CIDR blocks
  - Thành thạo Elastic Network Interfaces (ENI) và Elastic IP addresses
  - Nắm vững Internet Gateway và NAT Gateway configurations cho internet connectivity
  - Triển khai VPC Endpoints cho secure AWS service connections không cần internet
  - Hiểu network security với Security Groups và Network ACLs (NACLs)
  - Thành thạo stateful vs stateless firewall concepts và rule configurations

- **Advanced Networking & Hybrid Connectivity:**

  - Nắm vững VPC Peering cho inter-VPC communication và limitations
  - Có chuyên môn trong Transit Gateway cho centralized network hub architecture
  - Cấu hình thành công VPN Site-to-Site cho hybrid cloud connectivity
  - Hiểu AWS Direct Connect cho dedicated private connections
  - Thành thạo Route 53 DNS services, endpoints, và internal hosted zones
  - Triển khai Network Load Balancer (NLB) cho high-performance Layer 4 load balancing
  - Hiểu Transit Gateway Network Manager cho network visualization
  - Thành thạo complex routing scenarios và traffic flow optimization

- **Network Security & Performance Optimization:**

  - Triển khai comprehensive network security sử dụng multiple layers of protection
  - Thành thạo Security Group rules và best practices cho least privilege access
  - Cấu hình thành công Network ACLs cho subnet-level security controls
  - Hiểu VPC Flow Logs cho network monitoring và troubleshooting
  - Triển khai network segmentation strategies cho different environments
  - Thành thạo DNS resolution và Route 53 advanced features
  - Tối ưu hóa network performance qua proper subnet và routing design
  - Hiểu cost optimization strategies cho networking services

- **Amazon CloudFront Content Delivery Network:**

  - Thành thạo CDN concepts và global edge locations
  - Thành công tạo và cấu hình CloudFront distributions với S3 origins
  - Triển khai Origin Access Identity (OAI) cho enhanced security
  - Hiểu performance benefits và edge caching strategies
  - Nắm vững custom domain configuration và SSL certificate management
  - Thành thạo global content delivery optimization techniques
  - Hiểu caching behaviors và cache invalidation strategies
  - Tối ưu hóa website performance qua CloudFront edge locations

- **Advanced CloudFront Configure & Lambda@Edge:**

  - Expertly cấu hình distribution invalidations cho efficient cache management
  - Thành công triển khai custom error pages cho enhanced user experience
  - Thành thạo Origin Groups cho automatic failover và high availability
  - Cấu hình response headers cho security và performance optimization
  - Tạo custom cache behaviors cho different content types
  - Phát triển và deploy Lambda@Edge functions cho request processing
  - Monitor CloudFront performance sử dụng comprehensive metrics và logs
  - Áp dụng CloudFront best practices bao gồm compression và SSL/TLS encryption

- **Cloud Development Workflow:**
  - Thiết lập môi trường development hoàn chỉnh trên cloud
  - Phát triển kỹ năng làm việc với cloud-based tools và services
  - Hiểu cách tích hợp multiple AWS services trong một workflow
  - Xây dựng foundation cho advanced cloud development practices
  - Tích hợp database services vào cloud application architecture
  - Thành thạo containerization và auto scaling trong cloud architecture
  - Triển khai Infrastructure as Code và comprehensive monitoring solutions
  - Thiết kế secure và scalable network architectures cho production workloads
