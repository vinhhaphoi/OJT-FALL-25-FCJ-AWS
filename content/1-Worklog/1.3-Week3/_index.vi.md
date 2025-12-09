---
title: "Worklog Tuần 3"
date: "2025-08-13"
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

- Tìm hiểu về AWS WorkSpaces virtual desktop service cho modern cloud-based workstations.
- Thành thạo WordPress deployment trên AWS Cloud với scalability và high availability.
- Hiểu AWS Managed Directory Service cho enterprise Windows environments.
- Thành thạo AWS VM Import/Export cho on-premises to cloud migration.
- Tìm hiểu về Database Schema Conversion và Migration sử dụng AWS DMS và SCT.
- Thành thạo AWS VPC networking concepts và advanced network architecture.
- Hiểu AWS Site-to-Site VPN cho secure hybrid cloud connectivity.
- Tìm hiểu về AWS FSx for Windows File Server enterprise storage solutions.
- Thành thạo AWS Direct Connect cho dedicated private network connections.
- Hiểu AWS Client VPN cho secure remote user access.
- Tìm hiểu về AWS Transit Gateway cho centralized network hub architecture.
- Thành thạo AWS PrivateLink cho private service connectivity.
- Tìm hiểu về AWS Lambda cho serverless computing và event-driven architecture.
- Thành thạo Amazon ECS cho container orchestration và management.
- Hiểu Amazon EKS cho managed Kubernetes deployments.
- Tìm hiểu về AWS App Runner cho simplified containerized application deployment.
- Hiểu dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Ngày bắt đầu | Ngày hoàn thành | Tài liệu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2   | - Tìm hiểu về AWS WorkSpaces virtual desktop service và modern working adaptation <br> - Hiểu WorkSpaces infrastructure và deployment architecture <br> - Thành thạo WordPress deployment trên AWS Cloud với Auto Scaling và Load Balancing <br> - Tìm hiểu về AWS Managed Directory Service cho enterprise Windows environments <br> - **Thực hành:** <br>&emsp; + **WorkSpaces Deployment:** <br>&emsp;&emsp; - Thiết lập WorkSpaces prerequisites và directory services <br>&emsp;&emsp; - Deploy Amazon WorkSpaces instances <br>&emsp;&emsp; - Truy cập WorkSpaces qua client applications và browsers <br>&emsp; + **WordPress trên AWS Cloud:** <br>&emsp;&emsp; - Cài đặt WordPress trên EC2 với RDS MySQL backend <br>&emsp;&emsp; - Triển khai Auto Scaling Groups cho application scalability <br>&emsp;&emsp; - Cấu hình Application Load Balancer cho high availability <br>&emsp;&emsp; - Thiết lập CloudFront CDN cho global content delivery <br>&emsp;&emsp; - Triển khai database backup và restore với Multi-AZ <br>&emsp; + **AWS Managed Directory Service:** <br>&emsp;&emsp; - Deploy AWS Managed Active Directory service <br>&emsp;&emsp; - Cấu hình Windows Server 2022 làm AD Manager <br>&emsp;&emsp; - Thiết lập Bastion Host cho secure remote access <br>&emsp;&emsp; - Triển khai domain joining và administrative tools                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 22/09/2025   | 22/09/2025      | [AWS WorkSpaces Desktop Ảo <br> Triển khai WorkSpaces instances](https://000093.awsstudygroup.com/) <br> <br> [WordPress trên AWS Cloud <br> Cài đặt WordPress với RDS](https://000101.awsstudygroup.com/) <br> <br> [Dịch vụ AWS Managed Directory <br> Triển khai Managed AD](https://000095.awsstudygroup.com/)                                                                                                                                                                                                                                                                                                  |
| 3   | - Thành thạo AWS VM Import/Export cho on-premises to cloud migration <br> - Tìm hiểu về Database Schema Conversion và Migration với AWS DMS và SCT <br> - Hiểu hybrid cloud migration strategies <br> - **Thực hành:** <br>&emsp; + **VM Import/Export Workshop:** <br>&emsp;&emsp; - Thiết lập VMware Workstation với Ubuntu Desktop VM <br>&emsp;&emsp; - Cấu hình on-premises virtual machine environment <br>&emsp;&emsp; - Import virtual machine images từ on-premises đến Amazon EC2 <br>&emsp;&emsp; - Export EC2 instances trở lại on-premises environment <br>&emsp;&emsp; - Quản lý S3 storage cho VM image files <br>&emsp; + **Database Migration Workshop:** <br>&emsp;&emsp; - Hiểu AWS Schema Conversion Tool (SCT) concepts <br>&emsp;&emsp; - Tìm hiểu về AWS Database Migration Service (DMS) architecture <br>&emsp;&emsp; - Chọn và cấu hình DMS source databases <br>&emsp;&emsp; - Chọn và cấu hình DMS target databases <br>&emsp;&emsp; - Triển khai serverless replication cho database migration <br>&emsp;&emsp; - Monitor DMS migrations và troubleshoot issues                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 23/09/2025   | 23/09/2025      | [VM Import/Export Migration <br> Import VMs on-premises lên EC2 và export ngược lại sử dụng S3 storage](https://000014.awsstudygroup.com/) <br> <br> [Chuyển đổi và Di chuyển Schema Database <br> Sử dụng AWS SCT cho schema conversion và DMS cho data migration với minimal downtime](https://000043.awsstudygroup.com/)                                                                                                                                                                                                                                                                                         |
| 4   | - Tìm hiểu về AWS VPC và advanced networking concepts <br> - Thành thạo AWS VPN cho secure hybrid cloud connectivity <br> - Hiểu AWS FSx for Windows File Server enterprise storage <br> - **Thực hành:** <br>&emsp; + **AWS VPC Networking:** <br>&emsp;&emsp; - Tạo và cấu hình VPC với custom CIDR blocks <br>&emsp;&emsp; - Thiết lập public và private subnets qua multiple AZs <br>&emsp;&emsp; - Cấu hình Internet Gateway cho public subnet connectivity <br>&emsp;&emsp; - Triển khai NAT Gateway cho private subnet internet access <br>&emsp;&emsp; - Cấu hình route tables và network ACLs <br>&emsp;&emsp; - Thiết lập security groups cho instance-level security <br>&emsp; + **AWS Site-to-Site VPN:** <br>&emsp;&emsp; - Hiểu VPN architecture và components <br>&emsp;&emsp; - Cấu hình Virtual Private Gateway và Customer Gateway <br>&emsp;&emsp; - Thiết lập VPN connections giữa on-premises và AWS <br>&emsp;&emsp; - Cấu hình static và dynamic routing với BGP <br>&emsp;&emsp; - Test và verify VPN connectivity <br>&emsp; + **AWS FSx for Windows File Server:** <br>&emsp;&emsp; - Deploy FSx file system với Multi-AZ configuration <br>&emsp;&emsp; - Cấu hình Active Directory integration <br>&emsp;&emsp; - Thiết lập EC2 instances cho file server access <br>&emsp;&emsp; - Triển khai file sharing và permissions <br>&emsp;&emsp; - Cấu hình backup và restore strategies                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 24/09/2025   | 24/09/2025      | [AWS Elastic Disaster Recovery <br> Replicate workloads on-premises lên AWS cho disaster recovery nhanh chóng với minimal downtime](https://000100.awsstudygroup.com/) <br> <br> [Tối ưu Chi phí Lambda <br> Tự động hóa start/stop EC2 với Lambda functions sử dụng resource tags để tiết kiệm chi phí](https://000022.awsstudygroup.com/) <br> <br> [Grafana Monitoring Cơ bản <br> Cài đặt Grafana trên EC2 và giám sát AWS resources với visualization và analytics](https://000029.awsstudygroup.com/)                                                                                                         |
| 5   | - Tìm hiểu về AWS Direct Connect cho dedicated network connections <br> - Thành thạo AWS Client VPN cho secure remote access <br> - Hiểu AWS Transit Gateway cho network consolidation <br> - Tìm hiểu về AWS PrivateLink cho private connectivity <br> - **Thực hành:** <br>&emsp; + **AWS Direct Connect:** <br>&emsp;&emsp; - Hiểu Direct Connect architecture và benefits <br>&emsp;&emsp; - Tìm hiểu về Direct Connect Gateway configuration <br>&emsp;&emsp; - Cấu hình Virtual Private Gateway connections <br>&emsp;&emsp; - Thiết lập routing và BGP configurations <br>&emsp;&emsp; - Hiểu LAG (Link Aggregation Groups) cho bandwidth <br>&emsp; + **AWS Client VPN:** <br>&emsp;&emsp; - Deploy Client VPN endpoint configuration <br>&emsp;&emsp; - Cấu hình mutual authentication với certificates <br>&emsp;&emsp; - Thiết lập client VPN connections và routing <br>&emsp;&emsp; - Triển khai split-tunnel và full-tunnel configurations <br>&emsp;&emsp; - Cấu hình authorization rules và security groups <br>&emsp; + **AWS Transit Gateway:** <br>&emsp;&emsp; - Hiểu Transit Gateway architecture và use cases <br>&emsp;&emsp; - Cấu hình Transit Gateway attachments to VPCs <br>&emsp;&emsp; - Thiết lập Transit Gateway route tables <br>&emsp;&emsp; - Triển khai VPC-to-VPC connectivity via Transit Gateway <br>&emsp;&emsp; - Cấu hình VPN attachments to Transit Gateway <br>&emsp; + **AWS PrivateLink:** <br>&emsp;&emsp; - Hiểu VPC Endpoint Services và Interface Endpoints <br>&emsp;&emsp; - Cấu hình PrivateLink cho AWS services <br>&emsp;&emsp; - Thiết lập custom PrivateLink endpoints <br>&emsp;&emsp; - Triển khai private connectivity patterns <br>&emsp;&emsp; - Cấu hình endpoint policies và security                                                                                                                                                                                                                                                                                                            | 25/09/2025   | 25/09/2025      | [AWS CloudWatch Workshop <br> Cấu hình metrics](https://000036.awsstudygroup.com/) <br> <br> [Quản lý Resources với Tags <br> Tổ chức AWS resources sử dụng tags và tạo resource groups cho batch management](https://000027.awsstudygroup.com/) <br> <br> [Kiểm soát Truy cập IAM dựa trên Tags <br> Quản lý quyền truy cập EC2 sử dụng resource tags với conditional IAM policies cho least privilege](https://000028.awsstudygroup.com/) <br> <br> [AWS Systems Manager <br> Tập trung vận hành với Patch Manager cho automated patching và Run Command cho remote execution](https://000031.awsstudygroup.com/) |
| 6   | - Tìm hiểu về AWS Lambda serverless computing platform <br> - Thành thạo Amazon ECS container orchestration service <br> - Hiểu Amazon EKS Kubernetes service <br> - Tìm hiểu về AWS App Runner cho containerized web applications <br> - **Thực hành:** <br>&emsp; + **AWS Lambda Serverless:** <br>&emsp;&emsp; - Hiểu Lambda architecture và execution model <br>&emsp;&emsp; - Tạo và deploy Lambda functions với various runtimes <br>&emsp;&emsp; - Cấu hình Lambda triggers từ multiple event sources <br>&emsp;&emsp; - Triển khai Lambda function versioning và aliases <br>&emsp;&emsp; - Thiết lập Lambda layers cho shared code và dependencies <br>&emsp;&emsp; - Cấu hình environment variables và execution role <br>&emsp;&emsp; - Monitor Lambda performance với CloudWatch <br>&emsp; + **Amazon ECS Container Service:** <br>&emsp;&emsp; - Hiểu ECS architecture với clusters và services <br>&emsp;&emsp; - Thiết đặt các các task trong ECS và các thông số của container <br>&emsp;&emsp; - Deploy ECS services với Fargate và EC2 launch types <br>&emsp;&emsp; - Thiết lập Application Load Balancer integration <br>&emsp;&emsp; - Triển khai auto-scaling cho ECS services <br>&emsp;&emsp; - Cấu hình service discovery và networking <br>&emsp; + **Amazon EKS Kubernetes Service:** <br>&emsp;&emsp; - Hiểu EKS architecture và Kubernetes concepts <br>&emsp;&emsp; - Tạo EKS cluster với managed node groups <br>&emsp;&emsp; - Deploy applications sử dụng Kubernetes manifests <br>&emsp;&emsp; - Cấu hình kubectl cho EKS cluster management <br>&emsp;&emsp; - Triển khai Kubernetes deployments và services <br>&emsp;&emsp; - Thiết lập ingress controllers và load balancing <br>&emsp; + **AWS App Runner:** <br>&emsp;&emsp; - Hiểu App Runner architecture và use cases <br>&emsp;&emsp; - Deploy containerized applications từ source code <br>&emsp;&emsp; - Cấu hình automatic deployments và scaling <br>&emsp;&emsp; - Thiết lập custom domains và HTTPS <br>&emsp;&emsp; - Triển khai health checks và monitoring | 26/09/2025   | 26/09/2025      | [Systems Manager Session Manager <br> Truy cập shell bảo mật tới EC2 instances với session logging và port forwarding](https://000058.awsstudygroup.com/) <br> <br> [AWS CloudFormation IaC <br> Định nghĩa và triển khai infrastructure as code sử dụng JSON/YAML templates với Cloud9 IDE](https://000037.awsstudygroup.com/) <br> <br> [AWS CDK Cơ bản <br> Triển khai infrastructure sử dụng TypeScript](https://000038.awsstudygroup.com/) <br> <br> [AWS CDK Nâng cao <br> Xây dựng kiến trúc ứng dụng với API Gateway](https://000076.awsstudygroup.com/)                                                    |

### Kết quả đạt được tuần 3:

- **Thành thạo AWS WorkSpaces Virtual Desktop Service:**

  - Hiểu AWS WorkSpaces concepts và modern cloud-based workstation solutions
  - Tìm hiểu sâu về WorkSpaces infrastructure và deployment architecture
  - Thành thạo virtual desktop management capabilities cho enterprise environments
  - Cấu hình điều kiện tiên quyết cho WorkSpaces, bao gồm cấu hình dịch vụ trực tiếp (directory services configuration)
  - Thành công deploy Amazon WorkSpaces instances với proper bundles
  - Truy cập WorkSpaces qua multiple methods: client applications và web browsers
  - Cấu hình WorkSpaces bundles và triển khai user management practices
  - Quản lý WorkSpaces lifecycle bao gồm cleanup và resource optimization
  - Hiểu cost optimization strategies cho virtual desktop infrastructure

- **Chuyên môn WordPress Deployment trên AWS Cloud:**

  - Thành thạo scalable WordPress deployment architecture trên AWS Cloud
  - Thành công cài đặt WordPress trên EC2 instances với RDS MySQL backend
  - Triển khai Auto Scaling Groups cho dynamic application scaling dựa trên demand
  - Cấu hình Application Load Balancer cho high availability và traffic distribution
  - Deploy CloudFront CDN cho global content delivery và performance optimization
  - Thiết lập Multi-AZ RDS deployment cho database high availability
  - Triển khai database backup và restore strategies sử dụng RDS snapshots
  - Thành thạo Launch Templates cho standardized EC2 instance deployment
  - Hiểu Target Groups và load balancing configurations

- **Thành thạo AWS Managed Directory Service:**

  - Hiểu AWS Managed AD concepts và enterprise Windows environments
  - Thành công deploy AWS Managed Active Directory service với high availability
  - Cấu hình Windows Server 2022 làm Active Directory Manager với administrative tools
  - Thiết lập Bastion Host cho secure remote desktop gateway access
  - Triển khai domain joining automation sử dụng AWS IAM integration
  - Thành thạo delegated groups vs normal groups trong AWS Managed AD
  - Hiểu hybrid cloud directory integration capabilities
  - Cấu hình multi-subnet và multi-AZ deployment cho directory service resilience
  - Triển khai enterprise-level user và computer management qua AD tools

- **Chuyên môn AWS VM Import/Export Migration:**

  - Thành thạo VM Import/Export concepts cho hybrid cloud migration strategies
  - Thành công thiết lập VMware Workstation Pro với Ubuntu Desktop virtual machines
  - Cấu hình on-premises virtualization environment với proper networking
  - Triển khai VM image import từ on-premises environment đến Amazon EC2
  - Thành công export EC2 instances trở lại on-premises infrastructure
  - Quản lý Amazon S3 storage cho VM image files và migration artifacts
  - Hiểu migration use cases: application migration, backup, và disaster recovery
  - Thành thạo cost optimization strategies cho VM migration workflows

- **Thành thạo Database Schema Conversion & Migration:**

  - Hiểu heterogeneous database migration concepts và challenges
  - Thành thạo AWS Schema Conversion Tool (SCT) cho schema transformation
  - Thành công học AWS Database Migration Service (DMS) architecture
  - Cấu hình DMS source databases từ various environments (on-premises, EC2, RDS)
  - Thiết lập DMS target databases bao gồm RDS, S3, Kinesis, DynamoDB, và DocumentDB
  - Triển khai serverless replication cho scalable database migration
  - Monitor DMS migration tasks và performance metrics
  - Troubleshoot migration issues và áp dụng remediation strategies
  - Hiểu minimal downtime migration techniques cho production databases

- **Chuyên môn AWS VPC Networking:**

  - Thành thạo AWS Virtual Private Cloud (VPC) concepts và architecture
  - Thành công tạo VPC với custom IPv4 CIDR blocks
  - Cấu hình public và private subnets qua multiple Availability Zones
  - Triển khai Internet Gateway cho public subnet internet connectivity
  - Deploy NAT Gateway để enable internet access cho private subnets
  - Cấu hình route tables cho traffic routing giữa subnets
  - Triển khai Network ACLs cho subnet-level security controls
  - Thành thạo Security Groups cho instance-level firewall rules
  - Hiểu VPC peering và transit gateway concepts

- **Thành thạo AWS Site-to-Site VPN:**

  - Hiểu hybrid cloud connectivity sử dụng AWS VPN
  - Thành thạo VPN architecture với Virtual Private Gateway và Customer Gateway
  - Thành công cấu hình Site-to-Site VPN connections
  - Triển khai static routing cho VPN traffic management
  - Cấu hình dynamic routing sử dụng Border Gateway Protocol (BGP)
  - Thiết lập redundant VPN tunnels cho high availability
  - Test và verify VPN connectivity giữa on-premises và AWS
  - Monitor VPN connection status và troubleshoot connectivity issues
  - Hiểu IPsec encryption và VPN security protocols
  - Áp dụng cost optimization strategies cho VPN deployments

- **Thành thạo AWS FSx for Windows File Server:**

  - Hiểu AWS FSx concepts cho enterprise Windows file storage
  - Thành công deploy FSx file system với Multi-AZ configuration
  - Tích hợp FSx với AWS Managed Active Directory
  - Cấu hình Windows EC2 instances cho FSx file server access
  - Triển khai file sharing và NTFS permissions management
  - Thiết lập automated backup và restore strategies
  - Hiểu deduplication và data compression features
  - Thành thạo FSx performance optimization và scaling capabilities
  - Cấu hình shadow copies cho point-in-time file recovery
  - Triển khai monitoring và maintenance best practices
  - Hiểu cost considerations cho FSx deployment

- **Chuyên môn AWS Direct Connect:**

  - Thành thạo AWS Direct Connect concepts cho dedicated private connectivity
  - Hiểu Direct Connect architecture và connection types (dedicated vs hosted)
  - Tìm hiểu về Direct Connect Gateway cho multi-region và multi-VPC connectivity
  - Cấu hình Virtual Private Gateway integration với Direct Connect
  - Hiểu routing configurations và BGP protocol implementation
  - Thành thạo Link Aggregation Groups (LAG) cho increased bandwidth
  - Tìm hiểu về Direct Connect resiliency và high availability patterns
  - Hiểu cost optimization strategies cho Direct Connect deployments
  - Thực hành hiệu quả về hybrid cloud network architecture
  - So sánh Direct Connect vs VPN cho enterprise connectivity scenarios

- **Thành thạo AWS Client VPN:**

  - Hiểu AWS Client VPN concepts cho secure remote access
  - Thành công học Client VPN endpoint architecture và configuration
  - Thành thạo mutual authentication sử dụng client certificates và server certificates
  - Cấu hình Active Directory và SAML-based authentication methods
  - Triển khai split-tunnel VPN cho optimized traffic routing
  - Thiết lập full-tunnel VPN cho complete traffic encryption
  - Cấu hình authorization rules cho user access control
  - Triển khai security group rules cho Client VPN endpoints
  - Hiểu connection logging và monitoring capabilities
  - Áp dụng cost considerations và scaling strategies cho Client VPN

- **Thành thạo AWS Transit Gateway:**

  - Thành thạo AWS Transit Gateway concepts cho centralized network hub
  - Hiểu Transit Gateway architecture và scalability benefits
  - Thành công học Transit Gateway attachment types (VPC, VPN, Direct Connect)
  - Cấu hình Transit Gateway route tables cho traffic management
  - Triển khai inter-VPC connectivity through Transit Gateway
  - Thiết lập VPN connections to Transit Gateway cho hybrid cloud
  - Cấu hình Direct Connect Gateway integration với Transit Gateway
  - Hiểu Transit Gateway peering cho inter-region connectivity
  - Thành thạo route propagation và static routing configurations
  - Áp dụng network segmentation và security best practices
  - Hiểu cost optimization cho large-scale network architectures

- **Chuyên môn AWS PrivateLink:**

  - Hiểu AWS PrivateLink concepts cho private service connectivity
  - Thành thạo VPC Endpoint Services và Interface Endpoints architecture
  - Thành công cấu hình PrivateLink cho AWS managed services
  - Tìm hiểu về Gateway Endpoints cho S3 và DynamoDB private access
  - Triển khai custom PrivateLink endpoints cho third-party services
  - Cấu hình endpoint policies cho fine-grained access control
  - Hiểu PrivateLink DNS resolution và naming
  - Thành thạo cross-account PrivateLink service sharing
  - Triển khai private connectivity patterns cho microservices
  - Áp dụng security best practices cho private service exposure
  - Hiểu cost considerations và scaling cho PrivateLink deployments

- **Thành thạo AWS Lambda Serverless Computing:**

  - Thành thạo AWS Lambda concepts cho serverless event-driven architecture
  - Hiểu Lambda execution model và compute resource allocation
  - Thành công tạo Lambda functions với multiple runtime environments (Python, Node.js, Java)
  - Cấu hình Lambda triggers từ various event sources (S3, DynamoDB, API Gateway, EventBridge)
  - Triển khai Lambda function versioning cho code management
  - Thiết lập Lambda aliases cho environment-specific deployments
  - Thành thạo Lambda layers cho shared code libraries và dependencies
  - Cấu hình environment variables và execution roles với IAM
  - Triển khai error handling và retry logic cho Lambda functions
  - Monitor Lambda performance metrics sử dụng CloudWatch
  - Hiểu Lambda pricing model và cost optimization strategies

- **Chuyên môn Amazon ECS Container Orchestration:**

  - Thành thạo Amazon ECS concepts cho container orchestration
  - Hiểu ECS architecture với clusters, services, và tasks
  - Thành công tạo ECS task definitions với container specifications
  - Cấu hình ECS services với Fargate serverless launch type
  - Deploy ECS services sử dụng EC2 launch type cho custom configurations
  - Tích hợp Application Load Balancer cho traffic distribution
  - Triển khai auto-scaling policies cho ECS services dựa trên metrics
  - Cấu hình service discovery sử dụng AWS Cloud Map
  - Thiết lập VPC networking và security groups cho ECS tasks
  - Thành thạo ECS task placement strategies và constraints
  - Triển khai logging và monitoring với CloudWatch Container Insights
  - Hiểu cost optimization cho Fargate vs EC2 launch types

- **Thành thạo Amazon EKS Kubernetes Service:**

  - Hiểu Amazon EKS concepts cho managed Kubernetes clusters
  - Thành thạo Kubernetes architecture bao gồm control plane và worker nodes
  - Thành công tạo EKS cluster với managed node groups
  - Cấu hình kubectl command-line tool cho EKS cluster management
  - Deploy containerized applications sử dụng Kubernetes manifests (YAML)
  - Triển khai Kubernetes Deployments cho application lifecycle management
  - Cấu hình Kubernetes Services cho service discovery và load balancing
  - Thiết lập Ingress controllers cho external traffic routing
  - Thành thạo Kubernetes ConfigMaps và Secrets cho configuration management
  - Triển khai horizontal pod autoscaling dựa trên resource metrics
  - Hiểu EKS integration với AWS services (IAM, CloudWatch, EBS)

- **Chuyên môn AWS App Runner Deployment:**
  - Hiểu AWS App Runner concepts cho simplified container deployment
  - Thành thạo App Runner architecture và automatic scaling capabilities
  - Thành công deploy containerized web applications từ source code repositories
  - Cấu hình App Runner services từ Docker container images
  - Triển khai automatic deployments triggered by code commits
  - Thiết lập custom domains với HTTPS certificates cho App Runner services
  - Cấu hình environment variables và secrets management
  - Triển khai health checks cho application availability monitoring
  - Thành thạo App Runner auto-scaling dựa trên concurrent requests
  - Monitor application performance sử dụng App Runner metrics
  - Hiểu cost-effective deployment strategies cho web applications
