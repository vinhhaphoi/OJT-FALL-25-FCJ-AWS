---
title: "Worklog Tuần 2"
date: "2025-08-12"
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---


### Mục tiêu tuần 2:

* Hiểu AWS Identity and Access Management (IAM)
* Cấp quyền truy cập cho các dịch vụ AWS với IAM role
* Hiểu AWS Cloud9 và các tính năng của nó
* Bắt đầu làm việc với AWS Cloud9
* Hosting website tĩnh với Amazon S3
* Thành thạo Amazon Relational Database Service (Amazon RDS)
* Học công nghệ container với Amazon Lightsail Container
* Deploy ứng dụng sử dụng Docker trên Ubuntu
* Triển khai Auto Scaling Groups cho các ứng dụng có thể mở rộng
* Cấu hình Load Balancers cho tính khả dụng cao
* Hiểu cách monitoring với CloudWatch

### Các công việc cần triển khai trong tuần này:
| Ngày | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Hiểu và triển khai IAM roles và policies <br> - Hiểu AWS Cloud9 có thể làm gì và cách triển khai <br> - Khám phá các tính năng cơ bản trong AWS Cloud 9 <br> - Sử dụng AWS CLI để liệt kê EC2 instances trong tài khoản <br> - Bắt đầu các dịch vụ với Amazon S3 Services <br> - **Thực hành:** <br>&emsp; + Tạo IAM user và access key <br>&emsp; + Gắn IAM policy để cấp các quyền cần thiết <br>&emsp; - AWS Cloud9: <br>&emsp;&emsp; - Sử dụng Command Line <br>&emsp;&emsp; - Làm việc với text file <br>&emsp;&emsp; - Quay lại Dashboard <br>&emsp; + Sử dụng lệnh: aws ec2 describe-instances để liệt kê EC2 instances trong tài khoản bằng AWS CLI command <br>&emsp; - Amazon S3: <br>&emsp;&emsp; + Hosting website tĩnh với Amazon S3 <br>&emsp;&emsp; + Sử dụng CloudFront để hosting website tĩnh | 09/15/2025 | 09/15/2025 | [AWS Cloud9](https://000049.awsstudygroup.com/) <br> <br> [Cấp quyền cho IAM <br> role](https://000048.awsstudygroup.com/) <br> <br> [Hosting website tĩnh <br> với Amazon S3](https://000057.awsstudygroup.com/)|
| 3   | - Khám phá Amazon Relational Database Service (Amazon RDS) và các lợi ích của nó <br> - Amazon Lightsail Container: <br>&emsp; + Hiểu về Lightsail Container <br>&emsp; + Deploy container image lên Amazon Lightsail Container bằng Docker trên Ubuntu <br> - Khám phá deploy FCJ Management với Auto Scaling Group <br> - **Thực hành:** <br>&emsp; + Triển khai Amazon RDS <br>&emsp; + Triển khai Application với MySQL <br>&emsp; + Backup và Restore trong Amazon RDS <br>&emsp; + Build container image và deploy <br>&emsp; + Deploy FCJ Management: <br>&emsp;&emsp; - Tạo Launch Template và Setup Load balance <br>&emsp;&emsp; - Tạo Auto Scaling Group | 09/16/2025 | 09/16/2025 | [Amazon RDS](https://000005.awsstudygroup.com/) <br> <br> [Amazon Lightsail](https://000046.awsstudygroup.com/) <br> <br> [Deploy ứng dụng với <br> Amazon EC2 Auto Scaling](https://000006.awsstudygroup.com/)|
| 4   | - Học và tạo CloudFormation với template file <br> - Sử dụng CloudWatch Metrics, CloudWatch Logs và CloudWatch dashboard <br> - Hiểu Hybrid DNS với Route 53 Resolver <br> - **Thực hành:** <br>&emsp; + CloudWatch: <br>&emsp;&emsp; - CloudWatch cho phép người dùng chọn và hiển thị metrics từ các ứng dụng của họ <br>&emsp;&emsp; - Lọc dữ liệu sử dụng advanced search expressions <br>&emsp;&emsp; - Áp dụng tính toán toán học để có insight sâu hơn như averages hoặc rankings <br>&emsp;&emsp; - Thêm dynamic labels để cải thiện khả năng đọc và diễn giải biểu đồ. <br>&emsp; + Route 53 Resolver: <br>&emsp;&emsp; - Khởi tạo CloudFormation bằng template. <br>&emsp;&emsp; - Tạo và deploy Microsoft AD (AWS Managed Microsoft Active Directory) <br>&emsp;&emsp; - Setup DNS với In/out Endpoint| 09/17/2025 | 09/17/2025      | [CloudWatch workshop](https://000008.awsstudygroup.com/) <br> <br> [Hybrid DNS với Route 53](https://000010.awsstudygroup.com/)|
| 5   | - Tìm hiểu EC2 cơ bản: <br>&emsp; + Instance types <br>&emsp; + AMI <br>&emsp; + EBS <br>&emsp; + ... <br> - Các cách remote SSH vào EC2 <br> - Tìm hiểu Elastic IP   <br>                  | 08/14/2025   | 08/15/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành:** <br>&emsp; + Tạo EC2 instance <br>&emsp; + Kết nối SSH <br>&emsp; + Gắn EBS volume                                                                                         | 08/15/2025   | 08/15/2025      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 2:

* **Thành thạo AWS Identity and Access Management (IAM):**
  * Hiểu rõ các khái niệm IAM: Users, Groups, Roles, và Policies
  * Tạo và quản lý IAM users với access keys phù hợp
  * Cấu hình và gắn IAM policies để cấp quyền truy cập cần thiết
  * Hiểu nguyên tắc least privilege và best practices cho IAM security

* **Làm chủ AWS Cloud9 Development Environment:**
  * Nắm vững các tính năng và khả năng của AWS Cloud9
  * Thành thạo sử dụng Cloud9 IDE cho development tasks
  * Làm việc hiệu quả với command line interface trong Cloud9
  * Quản lý files và text editing trong cloud-based environment
  * Điều hướng và sử dụng Cloud9 dashboard một cách thành thạo

* **Kỹ năng AWS CLI nâng cao:**
  * Sử dụng thành công AWS CLI trong môi trường Cloud9
  * Thực hiện lệnh `aws ec2 describe-instances` để liệt kê và quản lý EC2 instances
  * Tích hợp AWS CLI commands vào workflow hàng ngày
  * Hiểu cách kết hợp GUI và CLI để quản lý tài nguyên AWS hiệu quả

* **Amazon S3 & Static Website Hosting:**
  * Hiểu các khái niệm cơ bản của Amazon S3 service
  * Nắm vững cách thức hoạt động của S3 bucket và object storage
  * Thành công triển khai static website hosting với Amazon S3
  * Cấu hình S3 bucket để phục vụ web content
  * Hiểu use cases và benefits của S3 trong cloud architecture
  * Tích hợp CloudFront để cải thiện performance và distribution của static websites
  * Nắm vững best practices cho web hosting trên AWS cloud platform

* **Amazon RDS Database Management:**
  * Nắm vững các khái niệm và lợi ích của Amazon Relational Database Service (RDS)
  * Thành công triển khai và cấu hình Amazon RDS instances
  * Phát triển và triển khai applications tích hợp với MySQL database
  * Thực hiện backup và restore operations trong Amazon RDS
  * Hiểu các best practices cho database management trên cloud
  * Nắm vững database security và performance optimization trong RDS environment

* **Container Technology & Amazon Lightsail:**
  * Hiểu rõ về Amazon Lightsail Container service và các use cases
  * Thành thạo việc build và manage container images với Docker
  * Thành công deploy container applications lên Amazon Lightsail Container
  * Làm việc hiệu quả với Docker trên Ubuntu environment
  * Nắm vững containerization concepts và best practices
  * Hiểu cách tối ưu hóa container deployment cho production workloads

* **Auto Scaling & Load Balancing:**
  * Nắm vững các khái niệm và lợi ích của Amazon EC2 Auto Scaling
  * Thành công deploy FCJ Management application với Auto Scaling Group
  * Tạo và cấu hình Launch Templates cho scalable applications
  * Thiết lập và quản lý Load Balancers cho high availability
  * Hiểu scaling policies và monitoring cho dynamic workloads
  * Nắm vững cost optimization strategies với auto scaling

* **Infrastructure as Code & CloudFormation:**
  * Nắm vững các khái niệm Infrastructure as Code (IaC) và lợi ích của nó
  * Thành thạo tạo và quản lý CloudFormation templates
  * Thành công deploy và quản lý AWS resources bằng CloudFormation
  * Hiểu best practices cho template design và stack management
  * Nắm vững version control và rollback strategies cho infrastructure code
  * Tự động hóa resource deployment và configuration management

* **CloudWatch Monitoring & Observability:**
  * Thành thạo CloudWatch Metrics, Logs, và Dashboard functionalities
  * Thành công thiết lập comprehensive monitoring cho AWS applications
  * Sử dụng advanced search expressions để filter và analyze log data
  * Áp dụng mathematical calculations cho deeper insights và analytics
  * Tạo dynamic labels để cải thiện chart readability và interpretation
  * Thiết lập alerting và notification systems cho proactive monitoring
  * Hiểu performance optimization dựa trên monitoring data

* **Hybrid DNS & Route 53 Resolver:**
  * Nắm vững Hybrid DNS architecture và use cases
  * Thành công deploy và cấu hình Route 53 Resolver endpoints
  * Thiết lập AWS Managed Microsoft Active Directory integration
  * Cấu hình inbound và outbound DNS resolution
  * Hiểu DNS security và performance optimization
  * Quản lý cross-premises DNS connectivity và troubleshooting

* **Cloud Development Workflow:**
  * Thiết lập môi trường development hoàn chỉnh trên cloud
  * Phát triển kỹ năng làm việc với cloud-based tools và services
  * Hiểu cách tích hợp multiple AWS services trong một workflow
  * Xây dựng foundation cho advanced cloud development practices
  * Tích hợp database services vào cloud application architecture
  * Thành thạo containerization và auto scaling trong cloud architecture
  * Triển khai Infrastructure as Code và comprehensive monitoring solutions


