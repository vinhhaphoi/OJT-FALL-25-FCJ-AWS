---
title: "Worklog Tuần 4"
date: "2025-08-14"
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

- Học AWS Backup cho cen\* **Chuyên môn AWS CloudFormation Infrastructure as Code:**

  - Thành thạo AWS CloudFormation concepts cho infrastructure as code
  - Hiểu CloudFormation template structure với YAML và JSON
  - Thành công tạo CloudFormation stacks cho resource provisioning
  - Cấu hình stack parameters cho flexible template reusability
  - Triển khai stack outputs cho cross-stack references
  - Thiết lập nested stacks cho modular infrastructure architecture
  - Thành thạo StackSets cho multi-account và multi-region deployments
  - Cấu hình drift detection để identify manual configuration changes
  - Triển khai change sets cho safe preview of stack updates
  - Thiết lập rollback configuration và automatic rollback triggers
  - Monitor stack events và troubleshot provisioning failures
  - Hiểu CloudFormation integration với Service Catalog

- **Thành thạo Amazon EC2 Compute Fundamentals:**

  - Thành thạo Amazon EC2 concepts và compute services
  - Hiểu EC2 instance types, families, và use cases
  - Thành công launch và manage EC2 instances
  - Cấu hình Amazon Machine Images (AMI) cho custom images
  - Thiết lập SSH key pairs cho secure instance access
  - Triển khai security groups và network ACL rules
  - Cấu hình Elastic IP addresses cho static public IPs
  - Quản lý EBS volumes cho persistent block storage
  - Tạo và restore EBS snapshots cho backup
  - Thiết lập instance user data cho automated bootstrapping
  - Monitor EC2 instances với CloudWatch metrics
  - Hiểu EC2 placement groups và tenancy options

- **Thành thạo AWS IAM Security and Access Management:**

  - Thành thạo AWS IAM concepts cho identity and access management
  - Hiểu IAM authentication và authorization principles
  - Thành công tạo và quản lý IAM users và groups
  - Cấu hình IAM policies với JSON policy documents
  - Triển khai least privilege access với fine-grained permissions
  - Thiết lập IAM roles cho EC2, Lambda, và AWS services khác
  - Cấu hình multi-factor authentication (MFA) cho enhanced security
  - Triển khai password policies và access key rotation
  - Thiết lập cross-account access với IAM roles và trust policies
  - Cấu hình IAM identity federation với SAML và OIDC
  - Monitor IAM activity với CloudTrail và access advisor
  - Hiểu IAM best practices cho security và compliance
  - Áp dụng principle of least privilege across AWS resources

- **Chuyên môn Amazon RDS Managed Database:**

  - Thành thạo Amazon RDS concepts cho managed relational databases
  - Hiểu RDS database engines (MySQL, PostgreSQL, Oracle, SQL Server)
  - Thành công launch RDS instances với proper sizing
  - Cấu hình RDS parameter groups cho database optimization
  - Triển khai automated backups với retention policies
  - Thiết lập RDS snapshots cho manual backup và recovery
  - Cấu hình RDS read replicas cho read scaling
  - Triển khai Multi-AZ deployments cho high availability
  - Thiết lập RDS encryption at rest với KMS keys
  - Cấu hình RDS security groups và subnet groups
  - Monitor RDS performance với CloudWatch và Performance Insights
  - Hiểu RDS maintenance windows và version upgrades

- **Thành thạo Amazon Route 53 DNS Management:**
  - Thành thạo Amazon Route 53 concepts cho DNS và domain management
  - Hiểu DNS fundamentals và Route 53 features
  - Thành công register và manage domain names
  - Cấu hình hosted zones cho public và private DNS
  - Tạo record sets cho various DNS record types
  - Triển khai routing policies (simple, weighted, latency-based, failover)
  - Thiết lập health checks cho endpoint monitoring
  - Cấu hình DNS failover cho high availability
  - Triển khai alias records cho AWS resource integration
  - Thiết lập traffic flow cho complex routing configurations
  - Cấu hình Route 53 Resolver cho hybrid cloud DNS
  - Monitor DNS queries với CloudWatch Logs và metrics

management across AWS services.

- Thành thạo AWS Storage Gateway cho hybrid cloud storage integration.
- Hiểu Amazon S3 Glacier cho long-term archival storage.
- Học AWS DataSync cho automated data transfer và synchronization.
- Thành thạo AWS Control Tower cho multi-account AWS environment setup.
- Hiểu AWS Organizations cho centralized account management.
- Học AWS Service Catalog cho standardized service provisioning.
- Thành thạo AWS Systems Manager cho unified operations management.
- Hiểu AWS CloudFormation cho infrastructure as code.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Ngày bắt đầu | Ngày hoàn thành | Tài liệu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2   | - Học AWS Backup cho centralized backup management <br> - Thành thạo AWS Storage Gateway cho hybrid cloud storage <br> - Hiểu Amazon S3 Glacier cho archival storage <br> - Học AWS DataSync cho automated data transfer <br> - **Thực hành:** <br>&emsp; + **AWS Backup Service:** <br>&emsp;&emsp; - Hiểu AWS Backup architecture và features <br>&emsp;&emsp; - Cấu hình backup plans và policies <br>&emsp;&emsp; - Thiết lập backup vaults và access policies <br>&emsp;&emsp; - Triển khai automated backup schedules <br>&emsp;&emsp; - Thực hiện backup restoration và recovery <br>&emsp;&emsp; - Cấu hình cross-region và cross-account backup <br>&emsp; + **AWS Storage Gateway:** <br>&emsp;&emsp; - Hiểu Storage Gateway types (File, Volume, Tape) <br>&emsp;&emsp; - Deploy File Gateway cho NFS/SMB file storage <br>&emsp;&emsp; - Cấu hình Volume Gateway cho iSCSI block storage <br>&emsp;&emsp; - Thiết lập Tape Gateway cho virtual tape library <br>&emsp;&emsp; - Triển khai caching và bandwidth optimization <br>&emsp;&emsp; - Cấu hình on-premises to S3 integration <br>&emsp; + **Amazon S3 Glacier:** <br>&emsp;&emsp; - Hiểu Glacier storage classes và pricing <br>&emsp;&emsp; - Cấu hình S3 Lifecycle policies cho archival <br>&emsp;&emsp; - Triển khai Glacier retrieval options (Expedited, Standard, Bulk) <br>&emsp;&emsp; - Thiết lập Glacier Vault Lock cho compliance <br>&emsp;&emsp; - Cấu hình S3 Intelligent-Tiering cho cost optimization <br>&emsp; + **AWS DataSync:** <br>&emsp;&emsp; - Hiểu DataSync architecture và use cases <br>&emsp;&emsp; - Cấu hình DataSync agents cho on-premises transfers <br>&emsp;&emsp; - Thiết lập DataSync tasks cho automated transfers <br>&emsp;&emsp; - Triển khai data validation và verification <br>&emsp;&emsp; - Cấu hình bandwidth throttling và scheduling <br>&emsp;&emsp; - Monitor DataSync task execution và performance                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 29/09/2025   | 29/09/2025      | [AWS Backup Quản lý Tập trung <br> Tạo backup plans](https://000102.awsstudygroup.com/) <br> <br> [AWS Storage Gateway Hybrid Storage <br> Triển khai File](https://000032.awsstudygroup.com/) <br> <br> [Amazon S3 Glacier Lưu trữ Archive <br> Cấu hình lifecycle policies](https://000074.awsstudygroup.com/) <br> <br> [AWS DataSync Chuyển Tự động <br> Triển khai agents](https://000075.awsstudygroup.com/)     |
| 3   | - Thành thạo AWS Control Tower cho multi-account environment setup <br> - Hiểu AWS Organizations cho centralized account management <br> - Học AWS Service Catalog cho standardized provisioning <br> - **Thực hành:** <br>&emsp; + **AWS Control Tower:** <br>&emsp;&emsp; - Hiểu Control Tower architecture và landing zone <br>&emsp;&emsp; - Thiết lập multi-account AWS environment với Control Tower <br>&emsp;&emsp; - Cấu hình organizational units (OUs) và account structure <br>&emsp;&emsp; - Triển khai guardrails cho preventive và detective controls <br>&emsp;&emsp; - Thiết lập Account Factory cho automated account provisioning <br>&emsp;&emsp; - Cấu hình centralized logging và monitoring <br>&emsp;&emsp; - Triển khai baseline security configurations <br>&emsp; + **AWS Organizations:** <br>&emsp;&emsp; - Hiểu Organizations architecture và hierarchy <br>&emsp;&emsp; - Tạo và quản lý organizational structure <br>&emsp;&emsp; - Cấu hình Service Control Policies (SCPs) <br>&emsp;&emsp; - Triển khai consolidated billing và cost allocation <br>&emsp;&emsp; - Thiết lập cross-account resource sharing <br>&emsp;&emsp; - Cấu hình centralized security và compliance policies <br>&emsp; + **AWS Service Catalog:** <br>&emsp;&emsp; - Hiểu Service Catalog architecture và benefits <br>&emsp;&emsp; - Tạo và quản lý product portfolios <br>&emsp;&emsp; - Cấu hình provisioning artifacts và constraints <br>&emsp;&emsp; - Thiết lập user access và permissions <br>&emsp;&emsp; - Triển khai TagOptions cho resource tagging <br>&emsp;&emsp; - Cấu hình launch constraints và templates <br>&emsp;&emsp; - Monitor provisioned products và compliance                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 30/09/2025   | 30/09/2025      | [AWS Control Tower Thiết lập Multi-Account <br> Cấu hình landing zone](https://000063.awsstudygroup.com/) <br> <br> [AWS Organizations Quản lý Tập trung <br> Tạo OUs](https://000064.awsstudygroup.com/) <br> <br> [AWS Service Catalog Provisioning Chuẩn hóa <br> Tạo portfolios](https://000088.awsstudygroup.com/)                                                                                                                                                                     |
| 4   | - Thành thạo AWS Systems Manager cho unified operations management <br> - Hiểu AWS CloudFormation cho infrastructure as code <br> - **Thực hành:** <br>&emsp; + **AWS Systems Manager:** <br>&emsp;&emsp; - Hiểu Systems Manager architecture và capabilities <br>&emsp;&emsp; - Cấu hình Session Manager cho secure instance access <br>&emsp;&emsp; - Thiết lập Run Command cho remote command execution <br>&emsp;&emsp; - Triển khai Patch Manager cho automated patching <br>&emsp;&emsp; - Cấu hình State Manager cho configuration management <br>&emsp;&emsp; - Thiết lập Parameter Store cho configuration data <br>&emsp;&emsp; - Triển khai Inventory cho metadata collection <br>&emsp;&emsp; - Cấu hình Maintenance Windows cho scheduled tasks <br>&emsp;&emsp; - Thiết lập Automation cho operational tasks <br>&emsp;&emsp; - Monitor compliance và configuration drift <br>&emsp; + **AWS CloudFormation:** <br>&emsp;&emsp; - Hiểu CloudFormation concepts và templates <br>&emsp;&emsp; - Tạo CloudFormation stacks với YAML/JSON templates <br>&emsp;&emsp; - Cấu hình stack parameters và outputs <br>&emsp;&emsp; - Triển khai nested stacks cho modular infrastructure <br>&emsp;&emsp; - Thiết lập StackSets cho multi-account/region deployment <br>&emsp;&emsp; - Cấu hình drift detection và remediation <br>&emsp;&emsp; - Triển khai change sets cho preview updates <br>&emsp;&emsp; - Thiết lập rollback configuration và policies <br>&emsp;&emsp; - Monitor stack events và troubleshoot failures                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 01/10/2025   | 01/10/2025      | [AWS Systems Manager Vận hành Thống nhất <br> Cấu hình Session Manager](https://000089.awsstudygroup.com/) <br> <br> [AWS CloudFormation Infrastructure as Code <br> Tạo stacks](https://000087.awsstudygroup.com/)                                                                                                                                                                                                                                                                                                                                         |
| 5   | - Học Amazon EC2 fundamentals và compute services <br> - Thành thạo AWS IAM cho identity and access management <br> - Hiểu Amazon RDS cho managed databases <br> - Học Amazon Route 53 cho DNS management <br> - **Thực hành:** <br>&emsp; + **Amazon EC2 Fundamentals:** <br>&emsp;&emsp; - Hiểu EC2 instance types và families <br>&emsp;&emsp; - Cấu hình Amazon Machine Images (AMI) <br>&emsp;&emsp; - Launch và manage EC2 instances <br>&emsp;&emsp; - Thiết lập SSH key pairs cho secure access <br>&emsp;&emsp; - Cấu hình security groups và network ACLs <br>&emsp;&emsp; - Triển khai Elastic IP addresses <br>&emsp;&emsp; - Quản lý EBS volumes và snapshots <br>&emsp;&emsp; - Thiết lập instance user data và metadata <br>&emsp;&emsp; - Cấu hình EC2 instance lifecycle và states <br>&emsp;&emsp; - Monitor EC2 instances với CloudWatch <br>&emsp; + **AWS IAM Identity and Access Management:** <br>&emsp;&emsp; - Hiểu IAM concepts và components <br>&emsp;&emsp; - Tạo và quản lý IAM users và groups <br>&emsp;&emsp; - Cấu hình IAM policies và permissions <br>&emsp;&emsp; - Triển khai IAM roles cho AWS services <br>&emsp;&emsp; - Thiết lập multi-factor authentication (MFA) <br>&emsp;&emsp; - Cấu hình password policies và access keys <br>&emsp;&emsp; - Triển khai cross-account access với roles <br>&emsp;&emsp; - Thiết lập IAM identity federation <br>&emsp;&emsp; - Cấu hình service control policies (SCPs) <br>&emsp;&emsp; - Monitor IAM access với CloudTrail <br>&emsp; + **Amazon RDS Managed Databases:** <br>&emsp;&emsp; - Hiểu RDS database engines và features <br>&emsp;&emsp; - Launch RDS instances với MySQL/PostgreSQL <br>&emsp;&emsp; - Cấu hình RDS parameter groups và option groups <br>&emsp;&emsp; - Triển khai automated backups và snapshots <br>&emsp;&emsp; - Thiết lập RDS read replicas cho scaling <br>&emsp;&emsp; - Cấu hình Multi-AZ deployments cho high availability <br>&emsp;&emsp; - Triển khai RDS encryption at rest và in transit <br>&emsp;&emsp; - Thiết lập RDS security groups và subnet groups <br>&emsp;&emsp; - Monitor RDS performance với CloudWatch <br>&emsp;&emsp; - Cấu hình RDS maintenance windows và upgrades <br>&emsp; + **Amazon Route 53 DNS Service:** <br>&emsp;&emsp; - Hiểu Route 53 DNS concepts và features <br>&emsp;&emsp; - Register và manage domain names <br>&emsp;&emsp; - Cấu hình hosted zones và record sets <br>&emsp;&emsp; - Triển khai routing policies (simple, weighted, latency) <br>&emsp;&emsp; - Thiết lập health checks và DNS failover <br>&emsp;&emsp; - Cấu hình alias records cho AWS resources <br>&emsp;&emsp; - Triển khai traffic flow cho advanced routing <br>&emsp;&emsp; - Thiết lập Route 53 Resolver cho hybrid DNS <br>&emsp;&emsp; - Cấu hình DNSSEC cho domain security <br>&emsp;&emsp; - Monitor DNS queries với CloudWatch Logs                                                                                                                                                  | 02/10/2025   | 02/10/2025      | [Amazon EC2 Compute Cơ bản <br> Khởi chạy instances](https://000012.awsstudygroup.com/) <br> <br> [AWS IAM Quản lý Danh tính <br> Tạo users và roles](https://000030.awsstudygroup.com/) <br> <br> [Amazon RDS Databases Quản lý <br> Triển khai Multi-AZ instances](https://000044.awsstudygroup.com/) <br> <br> [Amazon Route 53 Quản lý DNS <br> Cấu hình hosted zones](https://000018.awsstudygroup.com/) |
| 6   | - Thành thạo AWS Auto Scaling cho automatic capacity management <br> - Hiểu Elastic Load Balancing cho traffic distribution <br> - Học Amazon CloudFront cho content delivery <br> - Thành thạo Amazon S3 cho object storage <br> - **Thực hành:** <br>&emsp; + **AWS Auto Scaling:** <br>&emsp;&emsp; - Hiểu Auto Scaling concepts và benefits <br>&emsp;&emsp; - Tạo và cấu hình Auto Scaling groups <br>&emsp;&emsp; - Thiết lập launch templates và configurations <br>&emsp;&emsp; - Triển khai scaling policies (target tracking, step, scheduled) <br>&emsp;&emsp; - Cấu hình health checks và instance replacement <br>&emsp;&emsp; - Thiết lập lifecycle hooks cho custom actions <br>&emsp;&emsp; - Triển khai instance warm-up và cooldown periods <br>&emsp;&emsp; - Cấu hình Auto Scaling với multiple instance types <br>&emsp;&emsp; - Thiết lập Auto Scaling notifications với SNS <br>&emsp;&emsp; - Monitor Auto Scaling activities với CloudWatch <br>&emsp; + **Elastic Load Balancing (ELB):** <br>&emsp;&emsp; - Hiểu ELB types (Application, Network, Gateway, Classic) <br>&emsp;&emsp; - Cấu hình Application Load Balancer (ALB) cho HTTP/HTTPS <br>&emsp;&emsp; - Thiết lập Network Load Balancer (NLB) cho TCP/UDP <br>&emsp;&emsp; - Triển khai target groups và health checks <br>&emsp;&emsp; - Cấu hình listener rules và routing <br>&emsp;&emsp; - Thiết lập SSL/TLS certificates với ACM <br>&emsp;&emsp; - Triển khai cross-zone load balancing <br>&emsp;&emsp; - Cấu hình sticky sessions và connection draining <br>&emsp;&emsp; - Thiết lập access logs cho load balancers <br>&emsp;&emsp; - Monitor ELB metrics với CloudWatch <br>&emsp; + **Amazon CloudFront CDN:** <br>&emsp;&emsp; - Hiểu CloudFront concepts và edge locations <br>&emsp;&emsp; - Tạo CloudFront distributions cho web content <br>&emsp;&emsp; - Cấu hình origin settings (S3, ALB, custom origins) <br>&emsp;&emsp; - Triển khai cache behaviors và TTL settings <br>&emsp;&emsp; - Thiết lập SSL/TLS certificates cho HTTPS <br>&emsp;&emsp; - Cấu hình geo-restriction và signed URLs <br>&emsp;&emsp; - Triển khai CloudFront Functions và Lambda@Edge <br>&emsp;&emsp; - Thiết lập origin failover cho high availability <br>&emsp;&emsp; - Cấu hình custom error pages và responses <br>&emsp;&emsp; - Monitor CloudFront với access logs và metrics <br>&emsp; + **Amazon S3 Object Storage:** <br>&emsp;&emsp; - Hiểu S3 concepts và storage classes <br>&emsp;&emsp; - Tạo và cấu hình S3 buckets <br>&emsp;&emsp; - Triển khai bucket policies và IAM permissions <br>&emsp;&emsp; - Cấu hình S3 versioning và lifecycle policies <br>&emsp;&emsp; - Thiết lập S3 encryption (SSE-S3, SSE-KMS, SSE-C) <br>&emsp;&emsp; - Triển khai S3 replication (CRR, SRR) <br>&emsp;&emsp; - Cấu hình S3 event notifications với Lambda <br>&emsp;&emsp; - Thiết lập S3 static website hosting <br>&emsp;&emsp; - Triển khai S3 access points và Object Lock <br>&emsp;&emsp; - Monitor S3 với CloudWatch metrics và logs | 03/10/2025   | 03/10/2025      | [AWS Auto Scaling Điều chỉnh Động <br> Tạo Auto Scaling groups](https://000111.awsstudygroup.com/) <br> <br> [Elastic Load Balancing Phân phối Traffic <br> Cấu hình ALB và NLB](https://000026.awsstudygroup.com/) <br> <br> [Amazon CloudFront CDN <br> Tạo distributions](https://000033.awsstudygroup.com/) <br> <br> [Amazon S3 Object Storage <br> Cấu hình buckets](https://000090.awsstudygroup.com/)                |

### Kết quả đạt được tuần 4:

- **Thành thạo AWS Backup Service:**

  - Thành thạo AWS Backup concepts cho centralized backup management
  - Hiểu AWS Backup architecture và supported AWS services
  - Thành công cấu hình backup plans với retention policies
  - Thiết lập backup vaults với encryption và access controls
  - Triển khai automated backup schedules dựa trên business requirements
  - Thực hiện backup restoration và point-in-time recovery
  - Cấu hình cross-region backup copy cho disaster recovery
  - Thiết lập cross-account backup sharing cho organizational backup strategies
  - Triển khai backup compliance monitoring và reporting
  - Thành thạo backup lifecycle management và cost optimization
  - Hiểu backup service integration với AWS Organizations

- **Chuyên môn AWS Storage Gateway:**

  - Hiểu AWS Storage Gateway concepts cho hybrid cloud storage
  - Thành thạo three gateway types: File Gateway, Volume Gateway, và Tape Gateway
  - Thành công deploy File Gateway cho NFS và SMB protocol support
  - Cấu hình Volume Gateway cho iSCSI block storage với cached và stored modes
  - Thiết lập Tape Gateway như virtual tape library (VTL) cho backup applications
  - Triển khai local caching cho low-latency access to frequently used data
  - Cấu hình bandwidth throttling cho network optimization
  - Thiết lập Storage Gateway integration với Amazon S3 và Glacier
  - Thành thạo gateway monitoring sử dụng CloudWatch metrics
  - Triển khai disaster recovery strategies với Storage Gateway
  - Hiểu cost optimization cho hybrid storage architectures

- **Thành thạo Amazon S3 Glacier Storage:**

  - Thành thạo Amazon S3 Glacier concepts cho long-term archival storage
  - Hiểu Glacier storage classes: Glacier Instant Retrieval, Flexible Retrieval, Deep Archive
  - Thành công cấu hình S3 Lifecycle policies cho automatic archival
  - Triển khai Glacier retrieval options với different speed và cost tiers
  - Thiết lập Glacier Vault Lock cho regulatory compliance và immutability
  - Cấu hình S3 Intelligent-Tiering cho automatic cost optimization
  - Thành thạo Glacier archive management và retrieval processes
  - Hiểu Glacier pricing model và cost calculation
  - Triển khai data encryption cho archived objects
  - Cấu hình S3 Object Lock cho write-once-read-many (WORM) compliance
  - Áp dụng archival strategies cho different data retention requirements
  - Hiểu use cases cho long-term backup và regulatory compliance

- **Thành thạo AWS DataSync Transfer:**

  - Thành thạo AWS DataSync concepts cho automated data transfer
  - Hiểu DataSync architecture với agents và cloud-native transfers
  - Thành công deploy DataSync agents on-premises hoặc trong EC2
  - Cấu hình DataSync tasks cho automated data synchronization
  - Triển khai data transfer từ on-premises NFS/SMB đến Amazon S3
  - Thiết lập DataSync cho EFS-to-EFS và S3-to-S3 transfers
  - Cấu hình data validation và integrity verification
  - Triển khai bandwidth throttling để control network usage
  - Thiết lập scheduled transfers cho automated data migration
  - Monitor DataSync task execution và performance metrics
  - Hiểu DataSync vs Snow Family cho large-scale data transfers

- **Thành thạo AWS Control Tower Multi-Account:**

  - Thành thạo AWS Control Tower concepts cho multi-account environment management
  - Hiểu Control Tower landing zone architecture và components
  - Thành công thiết lập multi-account AWS environment với automated provisioning
  - Cấu hình organizational units (OUs) với hierarchical account structure
  - Triển khai preventive guardrails để enforce policies và compliance
  - Thiết lập detective guardrails cho monitoring và alerting
  - Thành thạo Account Factory cho automated account creation và baseline configuration
  - Cấu hình centralized logging với AWS CloudTrail và AWS Config
  - Triển khai dashboard cho compliance và security monitoring
  - Hiểu Control Tower integration với AWS Organizations và SSO
  - Thành thạo account lifecycle management và governance

- **Chuyên môn AWS Organizations Governance:**

  - Hiểu AWS Organizations concepts cho centralized account management
  - Thành thạo organizational hierarchy với root, OUs, và member accounts
  - Thành công tạo và cấu trúc organization với multiple accounts
  - Cấu hình Service Control Policies (SCPs) cho permission boundaries
  - Triển khai preventive controls across organizational units
  - Thiết lập consolidated billing cho cost management và optimization
  - Cấu hình cost allocation tags cho detailed billing analysis
  - Triển khai cross-account resource sharing với AWS RAM
  - Thiết lập centralized security policies và compliance controls
  - Thành thạo invitation và account migration processes
  - Hiểu Organizations integration với Control Tower và SSO

- **Thành thạo AWS Service Catalog Provisioning:**

  - Thành thạo AWS Service Catalog concepts cho standardized provisioning
  - Hiểu Service Catalog architecture với portfolios và products
  - Thành công tạo product portfolios với versioned products
  - Cấu hình provisioning artifacts sử dụng CloudFormation templates
  - Triển khai launch constraints cho resource governance
  - Thiết lập template constraints cho parameter validation
  - Cấu hình user access và permissions cho portfolio sharing
  - Triển khai TagOptions cho automated resource tagging
  - Thiết lập notification constraints cho provisioning events
  - Monitor provisioned products và stack resources
  - Hiểu Service Catalog integration với AWS Organizations

- **Thành thạo AWS Systems Manager Operations:**

  - Thành thạo AWS Systems Manager concepts cho unified operations management
  - Hiểu Systems Manager architecture và component services
  - Thành công cấu hình Session Manager cho secure bastion-less access
  - Triển khai Run Command cho remote command execution across instances
  - Thiết lập Patch Manager cho automated OS và application patching
  - Cấu hình State Manager cho desired state configuration management
  - Thành thạo Parameter Store cho secure configuration data storage
  - Triển khai Inventory cho automated metadata collection
  - Thiết lập Maintenance Windows cho scheduled operational tasks
  - Cấu hình Automation cho workflow-based operational procedures
  - Monitor compliance status và configuration drift detection
  - Hiểu Systems Manager integration với CloudWatch và Config

- **Chuyên môn AWS CloudFormation Infrastructure as Code:**

  - Thành thạo AWS CloudFormation concepts cho infrastructure as code
  - Hiểu CloudFormation template structure với YAML và JSON
  - Thành công tạo CloudFormation stacks cho resource provisioning
  - Cấu hình stack parameters cho flexible template reusability
  - Triển khai stack outputs cho cross-stack references
  - Thiết lập nested stacks cho modular infrastructure architecture
  - Thành thạo StackSets cho multi-account và multi-region deployments
  - Cấu hình drift detection để identify manual configuration changes
  - Triển khai change sets cho safe preview of stack updates
  - Thiết lập rollback configuration và automatic rollback triggers
  - Monitor stack events và troubleshoot provisioning failures
  - Hiểu CloudFormation integration với Service Catalog

- **Thành thạo Amazon EC2 Compute Fundamentals:**

  - Thành thạo Amazon EC2 concepts và compute services
  - Hiểu EC2 instance types, families, và use cases
  - Thành công launch và manage EC2 instances
  - Cấu hình Amazon Machine Images (AMI) cho custom images
  - Thiết lập SSH key pairs cho secure instance access
  - Triển khai security groups và network ACL rules
  - Cấu hình Elastic IP addresses cho static public IPs
  - Quản lý EBS volumes cho persistent block storage
  - Tạo và restore EBS snapshots cho backup
  - Thiết lập instance user data cho automated bootstrapping
  - Monitor EC2 instances với CloudWatch metrics
  - Hiểu EC2 placement groups và tenancy options

- **Thành thạo AWS IAM Security and Access Management:**

  - Thành thạo AWS IAM concepts cho identity and access management
  - Hiểu IAM authentication và authorization principles
  - Thành công tạo và quản lý IAM users và groups
  - Cấu hình IAM policies với JSON policy documents
  - Triển khai least privilege access với fine-grained permissions
  - Thiết lập IAM roles cho EC2, Lambda, và AWS services khác
  - Cấu hình multi-factor authentication (MFA) cho enhanced security
  - Triển khai password policies và access key rotation
  - Thiết lập cross-account access với IAM roles và trust policies
  - Cấu hình IAM identity federation với SAML và OIDC
  - Monitor IAM activity với CloudTrail và access advisor
  - Hiểu IAM best practices cho security và compliance
  - Áp dụng principle of least privilege across AWS resources

- **Chuyên môn Amazon RDS Managed Database:**

  - Thành thạo Amazon RDS concepts cho managed relational databases
  - Hiểu RDS database engines (MySQL, PostgreSQL, Oracle, SQL Server)
  - Thành công launch RDS instances với proper sizing
  - Cấu hình RDS parameter groups cho database optimization
  - Triển khai automated backups với retention policies
  - Thiết lập RDS snapshots cho manual backup và recovery
  - Cấu hình RDS read replicas cho read scaling
  - Triển khai Multi-AZ deployments cho high availability
  - Thiết lập RDS encryption at rest với KMS keys
  - Cấu hình RDS security groups và subnet groups
  - Monitor RDS performance với CloudWatch và Performance Insights
  - Hiểu RDS maintenance windows và version upgrades

- **Thành thạo Amazon Route 53 DNS Management:**

  - Thành thạo Amazon Route 53 concepts cho DNS và domain management
  - Hiểu DNS fundamentals và Route 53 features
  - Thành công register và manage domain names
  - Cấu hình hosted zones cho public và private DNS
  - Tạo record sets cho various DNS record types
  - Triển khai routing policies (simple, weighted, latency-based, failover)
  - Thiết lập health checks cho endpoint monitoring
  - Cấu hình DNS failover cho high availability
  - Triển khai alias records cho AWS resource integration
  - Thiết lập traffic flow cho complex routing configurations
  - Cấu hình Route 53 Resolver cho hybrid cloud DNS
  - Monitor DNS queries với CloudWatch Logs và metrics

- **Chuyên môn AWS Auto Scaling Capacity Management:**

  - Thành thạo AWS Auto Scaling concepts cho automatic capacity management
  - Hiểu Auto Scaling benefits cho availability và cost optimization
  - Thành công tạo và cấu hình Auto Scaling groups
  - Thiết lập launch templates với instance configurations
  - Triển khai target tracking scaling policies cho dynamic scaling
  - Cấu hình step scaling policies cho gradual adjustments
  - Thiết lập scheduled scaling cho predictable load patterns
  - Triển khai health checks với EC2 và ELB health check types
  - Cấu hình lifecycle hooks cho custom instance preparation
  - Thiết lập instance warm-up periods và cooldown timers
  - Triển khai Auto Scaling với multiple instance types và purchase options
  - Cấu hình SNS notifications cho scaling events
  - Monitor Auto Scaling activities và metrics với CloudWatch

- **Thành thạo Elastic Load Balancing Traffic Distribution:**

  - Thành thạo Elastic Load Balancing concepts và load balancer types
  - Hiểu differences giữa ALB, NLB, GLB, và Classic Load Balancer
  - Thành công cấu hình Application Load Balancer cho HTTP/HTTPS traffic
  - Thiết lập Network Load Balancer cho high-performance TCP/UDP traffic
  - Triển khai target groups với instance, IP, và Lambda targets
  - Cấu hình advanced health checks với custom intervals và thresholds
  - Thiết lập listener rules cho path-based và host-based routing
  - Triển khai SSL/TLS termination với ACM certificates
  - Cấu hình cross-zone load balancing cho balanced distribution
  - Thiết lập sticky sessions cho session affinity
  - Triển khai connection draining cho graceful instance removal
  - Cấu hình access logs cho load balancer troubleshooting
  - Monitor ELB metrics và performance với CloudWatch

- **Thành thạo Amazon CloudFront Content Delivery Network:**

  - Thành thạo Amazon CloudFront concepts cho global content delivery
  - Hiểu CloudFront edge locations và regional edge caches
  - Thành công tạo CloudFront distributions cho web content delivery
  - Cấu hình multiple origin sources (S3, ALB, EC2, custom origins)
  - Triển khai cache behaviors cho different content types
  - Thiết lập TTL settings cho cache optimization
  - Cấu hình SSL/TLS certificates cho secure HTTPS delivery
  - Triển khai geo-restriction cho content access control
  - Thiết lập signed URLs và signed cookies cho private content
  - Cấu hình CloudFront Functions cho edge computing
  - Triển khai Lambda@Edge cho advanced request/response manipulation
  - Thiết lập origin failover cho high availability
  - Cấu hình custom error pages và HTTP response headers
  - Monitor CloudFront với access logs, real-time logs, và metrics

- **Chuyên môn Amazon S3 Object Storage:**
  - Thành thạo Amazon S3 concepts cho scalable object storage
  - Hiểu S3 storage classes (Standard, IA, One Zone-IA, Glacier, etc.)
  - Thành công tạo và cấu hình S3 buckets với proper naming
  - Triển khai bucket policies cho resource-based access control
  - Cấu hình IAM policies cho identity-based S3 permissions
  - Thiết lập S3 versioning cho object version management
  - Triển khai lifecycle policies cho automatic storage class transitions
  - Cấu hình S3 encryption at rest (SSE-S3, SSE-KMS, SSE-C)
  - Thiết lập S3 replication (Cross-Region và Same-Region Replication)
  - Triển khai S3 event notifications với Lambda, SNS, và SQS
  - Cấu hình S3 static website hosting với custom domains
  - Thiết lập S3 access points cho simplified bucket access
  - Triển khai S3 Object Lock cho WORM compliance
  - Cấu hình S3 Inventory và Analytics cho storage insights
  - Monitor S3 với CloudWatch metrics, access logs, và CloudTrail
