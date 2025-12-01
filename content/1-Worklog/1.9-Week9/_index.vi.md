---
title: "Worklog Tuần 9"
date: "2025-08-19"
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---le: "Worklog Tuần 9"
date: "2025-09-09"
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---

{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 9:

- Kết nối, làm quen với các thành viên trong First Cloud Journey.
- Hiểu dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | ------------ | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 2   | - Học Introduction to Kubernetes và điều phối container <br> - Làm chủ Amazon EKS (Elastic Kubernetes Service) cơ bản <br> - Hiểu CI/CD pipelines với AWS CodePipeline cho EKS <br> - **Thực hành:** <br>&emsp; + **Giới thiệu Kubernetes:** <br>&emsp;&emsp; - Hiểu kiến trúc Kubernetes và các thành phần <br>&emsp;&emsp; - Tìm hiểu về pods, deployments, và services <br>&emsp;&emsp; - Cấu hình công cụ kubectl CLI <br>&emsp;&emsp; - Triển khai ứng dụng mẫu lên Kubernetes <br>&emsp;&emsp; - Quản lý tài nguyên và namespaces Kubernetes <br>&emsp;&emsp; - Hiểu ConfigMaps và Secrets <br>&emsp;&emsp; - Triển khai health checks và readiness probes <br>&emsp;&emsp; - Giám sát Kubernetes cluster và workloads <br>&emsp; + **Amazon EKS CI/CD với CodePipeline:** <br>&emsp;&emsp; - Chuẩn bị điều kiện tiên quyết EKS cluster <br>&emsp;&emsp; - Tạo IAM roles cho CodePipeline và CodeBuild <br>&emsp;&emsp; - Chỉnh sửa aws-auth ConfigMap cho quyền <br>&emsp;&emsp; - Fork sample repository cho deployment <br>&emsp;&emsp; - Tạo GitHub access tokens <br>&emsp;&emsp; - Thiết lập AWS CodePipeline cho EKS deployments <br>&emsp;&emsp; - Cấu hình CodeBuild cho container image builds <br>&emsp;&emsp; - Kích hoạt automated releases qua GitHub commits <br>&emsp;&emsp; - Giám sát pipeline executions và deployments <br>&emsp;&emsp; - Triển khai GitOps workflows cho Kubernetes                                    | 03/11/2025   | 03/11/2025      | [Introduction to Kubernetes <br> Điều phối container](https://000126.awsstudygroup.com/) <br> <br> [EKS CI/CD với CodePipeline <br> Triển khai tự động](https://000152.awsstudygroup.com/) |
| 3   | - Học Introduction to Amazon EKS Blueprints <br> - Làm chủ các mẫu infrastructure-as-code cho EKS <br> - Hiểu provisioning EKS cluster với Terraform và CDK <br> - **Thực hành:** <br>&emsp; + **Giới thiệu EKS Blueprints:** <br>&emsp;&emsp; - Hiểu kiến trúc và khái niệm EKS Blueprints <br>&emsp;&emsp; - Tìm hiểu về add-ons và team management <br>&emsp;&emsp; - Cấu hình VPC cho EKS clusters <br>&emsp;&emsp; - Thiết lập Application Load Balancer (ALB) <br>&emsp;&emsp; - Triển khai EC2 Kubernetes workers <br>&emsp;&emsp; - Hiểu EKS control plane và data plane <br>&emsp;&emsp; - Triển khai cluster autoscaling <br>&emsp;&emsp; - Cấu hình storage classes và persistent volumes <br>&emsp;&emsp; - Thiết lập monitoring và logging với CloudWatch <br>&emsp;&emsp; - Triển khai RBAC và IAM cho EKS <br>&emsp;&emsp; - Deploy các EKS add-ons phổ biến (metrics-server, cluster-autoscaler) <br>&emsp;&emsp; - Hiểu GitOps patterns với ArgoCD/Flux <br>&emsp;&emsp; - Triển khai multi-tenancy với namespaces <br>&emsp;&emsp; - Áp dụng security best practices cho EKS                                                                                                                                                                                                                                                                                                                                                    | 04/11/2025   | 04/11/2025      | [Introduction to EKS Blueprints <br> Các mẫu infrastructure](https://000065.awsstudygroup.com/)                                                                                            |
| 4   | - Học CI/CD trên Amazon EKS với CodePipeline và GitHub <br> - Làm chủ AWS Lambda serverless computing <br> - Hiểu các mẫu triển khai serverless application <br> - **Thực hành:** <br>&emsp; + **CI/CD trên EKS với CodePipeline:** <br>&emsp;&emsp; - Thiết lập điều kiện tiên quyết cho EKS CI/CD <br>&emsp;&emsp; - Tạo CodePipeline cho EKS deployments <br>&emsp;&emsp; - Tích hợp GitHub với CodePipeline <br>&emsp;&emsp; - Cấu hình CodeBuild cho container builds <br>&emsp;&emsp; - Triển khai automated testing trong pipeline <br>&emsp;&emsp; - Deploy ứng dụng lên EKS qua pipeline <br>&emsp;&emsp; - Thiết lập pipeline notifications và monitoring <br>&emsp;&emsp; - Triển khai rollback strategies <br>&emsp;&emsp; - Giám sát deployment health và logs <br>&emsp; + **AWS Lambda Workshop:** <br>&emsp;&emsp; - Hiểu Lambda function fundamentals <br>&emsp;&emsp; - Tạo và deploy Lambda functions <br>&emsp;&emsp; - Cấu hình triggers và event sources <br>&emsp;&emsp; - Triển khai Lambda với API Gateway <br>&emsp;&emsp; - Thiết lập Lambda layers cho dependencies <br>&emsp;&emsp; - Cấu hình environment variables và secrets <br>&emsp;&emsp; - Triển khai error handling và retries <br>&emsp;&emsp; - Giám sát Lambda với CloudWatch Logs <br>&emsp;&emsp; - Tối ưu Lambda performance và costs <br>&emsp;&emsp; - Áp dụng serverless best practices                                                            | 05/11/2025   | 05/11/2025      | [CI/CD trên EKS <br> CodePipeline và GitHub](https://000062.awsstudygroup.com/) <br> <br> [AWS Lambda Workshop <br> Serverless computing](https://000161.awsstudygroup.com/)               |
| 5   | - Học Red Hat OpenShift Service trên AWS (ROSA) <br> - Làm chủ kiến trúc và triển khai AWS Data Lake <br> - Hiểu điều phối container với OpenShift <br> - **Thực hành:** <br>&emsp; + **Red Hat OpenShift Service trên AWS:** <br>&emsp;&emsp; - Hiểu kiến trúc ROSA và lợi ích <br>&emsp;&emsp; - Thiết lập điều kiện tiên quyết cho ROSA deployment <br>&emsp;&emsp; - Deploy ROSA cluster trên AWS <br>&emsp;&emsp; - Cấu hình cluster networking và security <br>&emsp;&emsp; - Deploy ứng dụng trên OpenShift <br>&emsp;&emsp; - Triển khai OpenShift operators <br>&emsp;&emsp; - Cấu hình persistent storage <br>&emsp;&emsp; - Thiết lập monitoring và logging <br>&emsp;&emsp; - Quản lý cluster scaling và upgrades <br>&emsp; + **Triển khai AWS Data Lake:** <br>&emsp;&emsp; - Hiểu kiến trúc và khái niệm Data Lake <br>&emsp;&emsp; - Thiết kế cấu trúc Data Lake dựa trên S3 <br>&emsp;&emsp; - Triển khai S3 security best practices <br>&emsp;&emsp; - Cấu hình S3 bucket policies và ACLs <br>&emsp;&emsp; - Thiết lập data cataloging với AWS Glue <br>&emsp;&emsp; - Triển khai data partitioning strategies <br>&emsp;&emsp; - Cấu hình Amazon Athena cho querying <br>&emsp;&emsp; - Thiết lập AWS Lake Formation cho governance <br>&emsp;&emsp; - Triển khai data encryption và access control <br>&emsp;&emsp; - Giám sát và tối ưu Data Lake performance                                                               | 06/11/2025   | 06/11/2025      | [RedHat OpenShift trên AWS <br> Triển khai ROSA](https://000071.awsstudygroup.com/) <br> <br> [AWS Data Lake <br> S3 security practices](https://000035.awsstudygroup.com/)                |
| 6   | - Học xây dựng Data Lakes nâng cao với AWS <br> - Làm chủ Analytics trên AWS với comprehensive data pipeline <br> - Hiểu kiến trúc end-to-end data analytics <br> - **Thực hành:** <br>&emsp; + **Xây dựng Data Lake với dữ liệu của bạn:** <br>&emsp;&emsp; - Thiết kế kiến trúc Data Lake có khả năng mở rộng <br>&emsp;&emsp; - Triển khai data ingestion pipelines <br>&emsp;&emsp; - Cấu hình S3 storage tiers và lifecycle policies <br>&emsp;&emsp; - Thiết lập data cataloging và metadata management <br>&emsp;&emsp; - Triển khai data quality và validation <br>&emsp;&emsp; - Cấu hình AWS Glue ETL jobs <br>&emsp;&emsp; - Áp dụng data transformation workflows <br>&emsp;&emsp; - Triển khai data lineage tracking <br>&emsp;&emsp; - Thiết lập data access patterns <br>&emsp; + **Analytics on AWS Workshop:** <br>&emsp;&emsp; - Xây dựng end-to-end analytics pipeline <br>&emsp;&emsp; - Cấu hình Amazon RDS cho transactional data <br>&emsp;&emsp; - Thiết lập Amazon Redshift cho data warehousing <br>&emsp;&emsp; - Triển khai Amazon EMR cho big data processing <br>&emsp;&emsp; - Cấu hình Amazon Kinesis cho streaming analytics <br>&emsp;&emsp; - Thiết lập Amazon QuickSight cho visualization <br>&emsp;&emsp; - Triển khai real-time và batch analytics <br>&emsp;&emsp; - Cấu hình data pipeline orchestration <br>&emsp;&emsp; - Tối ưu query performance <br>&emsp;&emsp; - Áp dụng analytics best practices | 07/11/2025   | 07/11/2025      | [Xây dựng Data Lake <br> Triển khai nâng cao](https://000070.awsstudygroup.com/) <br> <br> [Analytics trên AWS <br> Pipeline toàn diện](https://000072.awsstudygroup.com/)                 |

### Kết quả đạt được tuần 9:

- **Thành thạo Introduction to Kubernetes:**

  - Thành thạo kiến trúc Kubernetes và các thành phần cốt lõi
  - Thành công hiểu về pods, deployments, và services
  - Cấu hình và sử dụng công cụ kubectl CLI hiệu quả
  - Triển khai ứng dụng mẫu lên Kubernetes clusters
  - Quản lý tài nguyên và namespaces Kubernetes
  - Triển khai ConfigMaps và Secrets cho cấu hình
  - Thiết lập health checks và readiness probes
  - Giám sát Kubernetes cluster và hiệu suất workload
  - Áp dụng best practices cho điều phối container

- **Chuyên gia Amazon EKS CI/CD Pipeline:**

  - Thành thạo thiết lập và cấu hình Amazon EKS cluster
  - Thành công tạo IAM roles cho CodePipeline và CodeBuild
  - Chỉnh sửa aws-auth ConfigMap cho quyền RBAC phù hợp
  - Fork và cấu hình GitHub repositories cho deployments
  - Tạo GitHub access tokens cho tích hợp pipeline
  - Thiết lập AWS CodePipeline cho automated EKS deployments
  - Cấu hình CodeBuild cho containerized application builds
  - Kích hoạt automated releases qua GitHub commits
  - Giám sát pipeline executions và deployment status
  - Triển khai GitOps workflows cho Kubernetes deployments
  - Áp dụng best practices cho CI/CD trên Kubernetes

- **Thành thạo Amazon EKS Blueprints Infrastructure:**

  - Thành thạo kiến trúc và patterns của EKS Blueprints
  - Thành công hiểu về add-ons và team management concepts
  - Cấu hình VPC networking cho EKS clusters
  - Thiết lập Application Load Balancer cho ingress
  - Triển khai và quản lý EC2 Kubernetes worker nodes
  - Hiểu sự tách biệt EKS control plane và data plane
  - Triển khai cluster autoscaling cho dynamic workloads
  - Cấu hình storage classes và persistent volumes
  - Thiết lập monitoring và logging với CloudWatch integration
  - Triển khai RBAC và IAM roles cho secure access
  - Deploy các EKS add-ons thiết yếu (metrics-server, cluster-autoscaler)
  - Hiểu GitOps deployment patterns
  - Triển khai multi-tenancy sử dụng namespaces
  - Áp dụng security best practices cho production EKS clusters

- **Chuyên gia CI/CD trên Amazon EKS:**

  - Thành thạo thiết lập CI/CD cho EKS với CodePipeline
  - Thành công tạo automated deployment pipelines
  - Tích hợp GitHub với AWS CodePipeline
  - Cấu hình CodeBuild cho containerized builds
  - Triển khai automated testing trong CI/CD pipeline
  - Deploy ứng dụng lên EKS qua automated pipelines
  - Thiết lập pipeline notifications và monitoring
  - Triển khai rollback strategies cho deployments
  - Giám sát deployment health và logs
  - Áp dụng best practices cho EKS CI/CD

- **Thành thạo AWS Lambda Serverless Computing:**

  - Thành thạo Lambda function fundamentals và architecture
  - Thành công tạo và deploy Lambda functions
  - Cấu hình event triggers và sources
  - Tích hợp Lambda với API Gateway
  - Triển khai Lambda layers cho shared dependencies
  - Cấu hình environment variables và secrets management
  - Triển khai error handling và retry mechanisms
  - Giám sát Lambda functions với CloudWatch Logs
  - Tối ưu Lambda performance và cost efficiency
  - Áp dụng serverless best practices

- **Chuyên gia Red Hat OpenShift Service trên AWS (ROSA):**

  - Thành thạo kiến trúc ROSA và lợi ích
  - Thành công thiết lập điều kiện tiên quyết ROSA deployment
  - Deploy ROSA clusters trên AWS infrastructure
  - Cấu hình cluster networking và security
  - Deploy ứng dụng container hóa trên OpenShift
  - Triển khai OpenShift operators cho application management
  - Cấu hình persistent storage cho stateful applications
  - Thiết lập monitoring và logging cho OpenShift clusters
  - Quản lý cluster scaling và version upgrades
  - Áp dụng best practices cho enterprise Kubernetes

- **Thành thạo Triển khai AWS Data Lake:**

  - Thành thạo kiến trúc và design patterns Data Lake
  - Thành công thiết kế cấu trúc Data Lake dựa trên S3
  - Triển khai S3 security best practices
  - Cấu hình S3 bucket policies và access controls
  - Thiết lập data cataloging với AWS Glue
  - Triển khai data partitioning cho query optimization
  - Cấu hình Amazon Athena cho SQL-based querying
  - Triển khai AWS Lake Formation cho data governance
  - Áp dụng data encryption và access control mechanisms
  - Giám sát và tối ưu Data Lake performance

- **Chuyên gia Xây dựng Data Lake Nâng cao:**
- Thành thạo thiết kế kiến trúc Data Lake có khả năng mở rộng
- Thành công triển khai data ingestion pipelines
- Cấu hình S3 storage tiers và lifecycle policies
- Thiết lập comprehensive data cataloging và metadata management
- Triển khai data quality và validation frameworks
- Cấu hình AWS Glue ETL jobs cho transformation
- Áp dụng complex data transformation workflows
- Triển khai data lineage tracking
- Thiết lập efficient data access patterns
- Áp dụng performance optimization techniques

- **Thành thạo Toàn diện Analytics trên AWS:**
  - Thành thạo kiến trúc end-to-end analytics pipeline
  - Thành công cấu hình Amazon RDS cho transactional data
  - Thiết lập Amazon Redshift cho data warehousing
  - Triển khai Amazon EMR cho big data processing
  - Cấu hình Amazon Kinesis cho streaming analytics
  - Thiết lập Amazon QuickSight cho data visualization
  - Triển khai cả real-time và batch analytics
  - Cấu hình data pipeline orchestration
  - Tối ưu query performance across analytics stack
  - Áp dụng analytics best practices cho production workloads
