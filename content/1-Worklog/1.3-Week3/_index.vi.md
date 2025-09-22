---
title: "Worklog Tuần 3"
date: "2025-08-13"
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Kết nối, làm quen với các thành viên trong First Cloud Journey.
* Học AWS WorkSpaces virtual desktop service cho modern cloud-based workstations.
* Thành thạo WordPress deployment trên AWS Cloud với scalability và high availability.
* Hiểu AWS Managed Directory Service cho enterprise Windows environments.
* Thành thạo AWS VM Import/Export cho on-premises to cloud migration.
* Học Database Schema Conversion và Migration sử dụng AWS DMS và SCT.
* Hiểu dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Học AWS WorkSpaces virtual desktop service và modern working adaptation <br> - Hiểu WorkSpaces infrastructure và deployment architecture <br> - Thành thạo WordPress deployment trên AWS Cloud với Auto Scaling và Load Balancing <br> - Học AWS Managed Directory Service cho enterprise Windows environments <br> - **Thực hành:** <br>&emsp; + **WorkSpaces Deployment:** <br>&emsp;&emsp; - Thiết lập WorkSpaces prerequisites và directory services <br>&emsp;&emsp; - Deploy Amazon WorkSpaces instances <br>&emsp;&emsp; - Truy cập WorkSpaces qua client applications và browsers <br>&emsp; + **WordPress trên AWS Cloud:** <br>&emsp;&emsp; - Cài đặt WordPress trên EC2 với RDS MySQL backend <br>&emsp;&emsp; - Triển khai Auto Scaling Groups cho application scalability <br>&emsp;&emsp; - Cấu hình Application Load Balancer cho high availability <br>&emsp;&emsp; - Thiết lập CloudFront CDN cho global content delivery <br>&emsp;&emsp; - Triển khai database backup và restore với Multi-AZ <br>&emsp; + **AWS Managed Directory Service:** <br>&emsp;&emsp; - Deploy AWS Managed Active Directory service <br>&emsp;&emsp; - Cấu hình Windows Server 2022 làm AD Manager <br>&emsp;&emsp; - Thiết lập Bastion Host cho secure remote access <br>&emsp;&emsp; - Triển khai domain joining và administrative tools | 22/09/2025   | 22/09/2025      | [AWS WorkSpaces Workshop](https://000093.awsstudygroup.com/) <br> <br> [WordPress on AWS Cloud](https://000101.awsstudygroup.com/) <br> <br> [AWS Managed Directory <br> Service](https://000095.awsstudygroup.com/) |
| 3   | - Thành thạo AWS VM Import/Export cho on-premises to cloud migration <br> - Học Database Schema Conversion và Migration với AWS DMS và SCT <br> - Hiểu hybrid cloud migration strategies <br> - **Thực hành:** <br>&emsp; + **VM Import/Export Workshop:** <br>&emsp;&emsp; - Thiết lập VMware Workstation với Ubuntu Desktop VM <br>&emsp;&emsp; - Cấu hình on-premises virtual machine environment <br>&emsp;&emsp; - Import virtual machine images từ on-premises đến Amazon EC2 <br>&emsp;&emsp; - Export EC2 instances trở lại on-premises environment <br>&emsp;&emsp; - Quản lý S3 storage cho VM image files <br>&emsp; + **Database Migration Workshop:** <br>&emsp;&emsp; - Hiểu AWS Schema Conversion Tool (SCT) concepts <br>&emsp;&emsp; - Học AWS Database Migration Service (DMS) architecture <br>&emsp;&emsp; - Select và configure DMS source databases <br>&emsp;&emsp; - Select và configure DMS target databases <br>&emsp;&emsp; - Triển khai serverless replication cho database migration <br>&emsp;&emsp; - Monitor DMS migrations và troubleshoot issues | 23/09/2025 | 23/09/2025 | [AWS VM Import/Export](https://000014.awsstudygroup.com/) <br> <br> [Database Schema <br> Conversion & Migration](https://000043.awsstudygroup.com/) |
| 4   | - Tạo AWS Free Tier account <br> - Tìm hiểu AWS Console & AWS CLI <br> - **Thực hành:** <br>&emsp; + Tạo AWS account <br>&emsp; + Cài AWS CLI & cấu hình <br> &emsp; + Cách sử dụng AWS CLI | 13/08/2025   | 13/08/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu EC2 cơ bản: <br>&emsp; + Instance types <br>&emsp; + AMI <br>&emsp; + EBS <br>&emsp; + ... <br> - Các cách remote SSH vào EC2 <br> - Tìm hiểu Elastic IP   <br>                  | 14/08/2025   | 15/08/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành:** <br>&emsp; + Tạo EC2 instance <br>&emsp; + Kết nối SSH <br>&emsp; + Gắn EBS volume                                                                                         | 15/08/2025   | 15/08/2025      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 3:

* **Thành thạo AWS WorkSpaces Virtual Desktop Service:**
  * Hiểu AWS WorkSpaces concepts và modern cloud-based workstation solutions
  * Thành công khám phá WorkSpaces infrastructure và deployment architecture
  * Thành thạo virtual desktop management capabilities cho enterprise environments
  * Thiết lập WorkSpaces prerequisites bao gồm directory services configuration
  * Thành công deploy Amazon WorkSpaces instances với proper bundles
  * Truy cập WorkSpaces qua multiple methods: client applications và web browsers
  * Cấu hình WorkSpaces bundles và triển khai user management practices
  * Quản lý WorkSpaces lifecycle bao gồm cleanup và resource optimization
  * Hiểu cost optimization strategies cho virtual desktop infrastructure

* **Chuyên môn WordPress Deployment trên AWS Cloud:**
  * Thành thạo scalable WordPress deployment architecture trên AWS Cloud
  * Thành công cài đặt WordPress trên EC2 instances với RDS MySQL backend
  * Triển khai Auto Scaling Groups cho dynamic application scaling dựa trên demand
  * Cấu hình Application Load Balancer cho high availability và traffic distribution
  * Deploy CloudFront CDN cho global content delivery và performance optimization
  * Thiết lập Multi-AZ RDS deployment cho database high availability
  * Triển khai database backup và restore strategies sử dụng RDS snapshots
  * Thành thạo Launch Templates cho standardized EC2 instance deployment
  * Hiểu Target Groups và load balancing configurations

* **Thành thạo AWS Managed Directory Service:**
  * Hiểu AWS Managed AD concepts và enterprise Windows environments
  * Thành công deploy AWS Managed Active Directory service với high availability
  * Cấu hình Windows Server 2022 làm Active Directory Manager với administrative tools
  * Thiết lập Bastion Host cho secure remote desktop gateway access
  * Triển khai domain joining automation sử dụng AWS IAM integration
  * Thành thạo delegated groups vs normal groups trong AWS Managed AD
  * Hiểu hybrid cloud directory integration capabilities
  * Cấu hình multi-subnet và multi-AZ deployment cho directory service resilience
  * Triển khai enterprise-level user và computer management qua AD tools

* **Chuyên môn AWS VM Import/Export Migration:**
  * Thành thạo VM Import/Export concepts cho hybrid cloud migration strategies
  * Thành công thiết lập VMware Workstation Pro với Ubuntu Desktop virtual machines
  * Cấu hình on-premises virtualization environment với proper networking
  * Triển khai VM image import từ on-premises environment đến Amazon EC2
  * Thành công export EC2 instances trở lại on-premises infrastructure
  * Quản lý Amazon S3 storage cho VM image files và migration artifacts
  * Hiểu migration use cases: application migration, backup, và disaster recovery
  * Thành thạo cost optimization strategies cho VM migration workflows
  * Áp dụng best practices cho VM preparation và post-migration configuration

* **Thành thạo Database Schema Conversion & Migration:**
  * Hiểu heterogeneous database migration concepts và challenges
  * Thành thạo AWS Schema Conversion Tool (SCT) cho schema transformation
  * Thành công học AWS Database Migration Service (DMS) architecture
  * Cấu hình DMS source databases từ various environments (on-premises, EC2, RDS)
  * Thiết lập DMS target databases bao gồm RDS, S3, Kinesis, DynamoDB, và DocumentDB
  * Triển khai serverless replication cho scalable database migration
  * Monitor DMS migration tasks và performance metrics
  * Troubleshoot migration issues và áp dụng remediation strategies
  * Hiểu minimal downtime migration techniques cho production databases

* Hiểu AWS là gì và nắm được các nhóm dịch vụ cơ bản: 
  * Compute
  * Storage
  * Networking 
  * Database
  * ...

* Đã tạo và cấu hình AWS Free Tier account thành công.

* Làm quen với AWS Management Console và biết cách tìm, truy cập, sử dụng dịch vụ từ giao diện web.

* Cài đặt và cấu hình AWS CLI trên máy tính bao gồm:
  * Access Key
  * Secret Key
  * Region mặc định
  * ...

* Sử dụng AWS CLI để thực hiện các thao tác cơ bản như:

  * Kiểm tra thông tin tài khoản & cấu hình
  * Lấy danh sách region
  * Xem dịch vụ EC2
  * Tạo và quản lý key pair
  * Kiểm tra thông tin dịch vụ đang chạy
  * ...

* Có khả năng kết nối giữa giao diện web và CLI để quản lý tài nguyên AWS song song.
* ...


