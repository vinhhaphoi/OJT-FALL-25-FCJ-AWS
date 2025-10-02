---
title: "Worklog Tuần 4"
date: "2025-08-14"
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Học AWS Backup cho centralized backup management across AWS services.
* Thành thạo AWS Storage Gateway cho hybrid cloud storage integration.
* Hiểu Amazon S3 Glacier cho long-term archival storage.
* Học AWS DataSync cho automated data transfer và synchronization.


### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Học AWS Backup cho centralized backup management <br> - Thành thạo AWS Storage Gateway cho hybrid cloud storage <br> - Hiểu Amazon S3 Glacier cho archival storage <br> - Học AWS DataSync cho automated data transfer <br> - **Thực hành:** <br>&emsp; + **AWS Backup Service:** <br>&emsp;&emsp; - Hiểu AWS Backup architecture và features <br>&emsp;&emsp; - Cấu hình backup plans và policies <br>&emsp;&emsp; - Thiết lập backup vaults và access policies <br>&emsp;&emsp; - Triển khai automated backup schedules <br>&emsp;&emsp; - Thực hiện backup restoration và recovery <br>&emsp;&emsp; - Cấu hình cross-region và cross-account backup <br>&emsp; + **AWS Storage Gateway:** <br>&emsp;&emsp; - Hiểu Storage Gateway types (File, Volume, Tape) <br>&emsp;&emsp; - Deploy File Gateway cho NFS/SMB file storage <br>&emsp;&emsp; - Cấu hình Volume Gateway cho iSCSI block storage <br>&emsp;&emsp; - Thiết lập Tape Gateway cho virtual tape library <br>&emsp;&emsp; - Triển khai caching và bandwidth optimization <br>&emsp;&emsp; - Cấu hình on-premises to S3 integration <br>&emsp; + **Amazon S3 Glacier:** <br>&emsp;&emsp; - Hiểu Glacier storage classes và pricing <br>&emsp;&emsp; - Cấu hình S3 Lifecycle policies cho archival <br>&emsp;&emsp; - Triển khai Glacier retrieval options (Expedited, Standard, Bulk) <br>&emsp;&emsp; - Thiết lập Glacier Vault Lock cho compliance <br>&emsp;&emsp; - Cấu hình S3 Intelligent-Tiering cho cost optimization <br>&emsp; + **AWS DataSync:** <br>&emsp;&emsp; - Hiểu DataSync architecture và use cases <br>&emsp;&emsp; - Cấu hình DataSync agents cho on-premises transfers <br>&emsp;&emsp; - Thiết lập DataSync tasks cho automated transfers <br>&emsp;&emsp; - Triển khai data validation và verification <br>&emsp;&emsp; - Cấu hình bandwidth throttling và scheduling <br>&emsp;&emsp; - Monitor DataSync task execution và performance | 29/09/2025 | 29/09/2025 | [AWS Backup Service](https://000102.awsstudygroup.com/) <br> <br> [AWS Storage Gateway](https://000032.awsstudygroup.com/) <br> <br> [Amazon S3 Glacier](https://000074.awsstudygroup.com/) <br> <br> [AWS DataSync](https://000075.awsstudygroup.com/) |
| 3   | - Tìm hiểu AWS và các loại dịch vụ <br>&emsp; + Compute <br>&emsp; + Storage <br>&emsp; + Networking <br>&emsp; + Database <br>&emsp; + ... <br>                                            | 12/08/2025   | 12/08/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tạo AWS Free Tier account <br> - Tìm hiểu AWS Console & AWS CLI <br> - **Thực hành:** <br>&emsp; + Tạo AWS account <br>&emsp; + Cài AWS CLI & cấu hình <br> &emsp; + Cách sử dụng AWS CLI | 13/08/2025   | 13/08/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu EC2 cơ bản: <br>&emsp; + Instance types <br>&emsp; + AMI <br>&emsp; + EBS <br>&emsp; + ... <br> - Các cách remote SSH vào EC2 <br> - Tìm hiểu Elastic IP   <br>                  | 14/08/2025   | 15/08/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành:** <br>&emsp; + Tạo EC2 instance <br>&emsp; + Kết nối SSH <br>&emsp; + Gắn EBS volume                                                                                         | 15/08/2025   | 15/08/2025      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 4:

* **Thành thạo AWS Backup Service:**
  * Thành thạo AWS Backup concepts cho centralized backup management
  * Hiểu AWS Backup architecture và supported AWS services
  * Thành công cấu hình backup plans với retention policies
  * Thiết lập backup vaults với encryption và access controls
  * Triển khai automated backup schedules dựa trên business requirements
  * Thực hiện backup restoration và point-in-time recovery
  * Cấu hình cross-region backup copy cho disaster recovery
  * Thiết lập cross-account backup sharing cho organizational backup strategies
  * Triển khai backup compliance monitoring và reporting
  * Thành thạo backup lifecycle management và cost optimization
  * Hiểu backup service integration với AWS Organizations
  * Áp dụng best practices cho backup strategy và data protection

* **Chuyên môn AWS Storage Gateway:**
  * Hiểu AWS Storage Gateway concepts cho hybrid cloud storage
  * Thành thạo three gateway types: File Gateway, Volume Gateway, và Tape Gateway
  * Thành công deploy File Gateway cho NFS và SMB protocol support
  * Cấu hình Volume Gateway cho iSCSI block storage với cached và stored modes
  * Thiết lập Tape Gateway như virtual tape library (VTL) cho backup applications
  * Triển khai local caching cho low-latency access to frequently used data
  * Cấu hình bandwidth throttling cho network optimization
  * Thiết lập Storage Gateway integration với Amazon S3 và Glacier
  * Thành thạo gateway monitoring sử dụng CloudWatch metrics
  * Triển khai disaster recovery strategies với Storage Gateway
  * Hiểu cost optimization cho hybrid storage architectures
  * Áp dụng best practices cho on-premises to cloud storage migration

* **Thành thạo Amazon S3 Glacier Storage:**
  * Thành thạo Amazon S3 Glacier concepts cho long-term archival storage
  * Hiểu Glacier storage classes: Glacier Instant Retrieval, Flexible Retrieval, Deep Archive
  * Thành công cấu hình S3 Lifecycle policies cho automatic archival
  * Triển khai Glacier retrieval options với different speed và cost tiers
  * Thiết lập Glacier Vault Lock cho regulatory compliance và immutability
  * Cấu hình S3 Intelligent-Tiering cho automatic cost optimization
  * Thành thạo Glacier archive management và retrieval processes
  * Hiểu Glacier pricing model và cost calculation
  * Triển khai data encryption cho archived objects
  * Cấu hình S3 Object Lock cho write-once-read-many (WORM) compliance
  * Áp dụng archival strategies cho different data retention requirements
  * Hiểu use cases cho long-term backup và regulatory compliance

* **Thành thạo AWS DataSync Transfer:**
  * Thành thạo AWS DataSync concepts cho automated data transfer
  * Hiểu DataSync architecture với agents và cloud-native transfers
  * Thành công deploy DataSync agents on-premises hoặc trong EC2
  * Cấu hình DataSync tasks cho automated data synchronization
  * Triển khai data transfer từ on-premises NFS/SMB đến Amazon S3
  * Thiết lập DataSync cho EFS-to-EFS và S3-to-S3 transfers
  * Cấu hình data validation và integrity verification
  * Triển khai bandwidth throttling để control network usage
  * Thiết lập scheduled transfers cho automated data migration
  * Monitor DataSync task execution và performance metrics
  * Hiểu DataSync vs Snow Family cho large-scale data transfers
  * Áp dụng best practices cho data migration và synchronization strategies

