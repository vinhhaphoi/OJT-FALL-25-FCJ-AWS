---
title: "Week 9 Worklog"
date: "2025-09-09"
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives:

- Connect and get acquainted with members of First Cloud AI Journey.
- Understand basic AWS services, how to use the console & CLI.

### Tasks to be carried out this week:

| Day | Task                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Start Date | Completion Date | Reference Material                                                                                                                                                                                 |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2   | - Learn Introduction to Kubernetes and container orchestration <br> - Master Amazon EKS (Elastic Kubernetes Service) fundamentals <br> - Understand CI/CD pipelines with AWS CodePipeline for EKS <br> - **Practice:** <br>&emsp; + **Introduction to Kubernetes:** <br>&emsp;&emsp; - Understand Kubernetes architecture and components <br>&emsp;&emsp; - Learn about pods, deployments, and services <br>&emsp;&emsp; - Configure kubectl CLI tool <br>&emsp;&emsp; - Deploy sample applications to Kubernetes <br>&emsp;&emsp; - Manage Kubernetes resources and namespaces <br>&emsp;&emsp; - Understand ConfigMaps and Secrets <br>&emsp;&emsp; - Implement health checks and readiness probes <br>&emsp;&emsp; - Monitor Kubernetes cluster and workloads <br>&emsp; + **Amazon EKS CI/CD with CodePipeline:** <br>&emsp;&emsp; - Prepare EKS cluster prerequisites <br>&emsp;&emsp; - Create IAM roles for CodePipeline and CodeBuild <br>&emsp;&emsp; - Modify aws-auth ConfigMap for permissions <br>&emsp;&emsp; - Fork sample repository for deployment <br>&emsp;&emsp; - Generate GitHub access tokens <br>&emsp;&emsp; - Set up AWS CodePipeline for EKS deployments <br>&emsp;&emsp; - Configure CodeBuild for container image builds <br>&emsp;&emsp; - Trigger automated releases via GitHub commits <br>&emsp;&emsp; - Monitor pipeline executions and deployments <br>&emsp;&emsp; - Implement GitOps workflows for Kubernetes | 11/03/2025 | 11/03/2025      | [Introduction to Kubernetes <br> Container orchestration](https://000126.awsstudygroup.com/) <br> <br> [EKS CI/CD with CodePipeline <br> Automated deployments](https://000152.awsstudygroup.com/) |
| 3   | - Learn Introduction to Amazon EKS Blueprints <br> - Master infrastructure-as-code patterns for EKS <br> - Understand EKS cluster provisioning with Terraform and CDK <br> - **Practice:** <br>&emsp; + **Introduction to EKS Blueprints:** <br>&emsp;&emsp; - Understand EKS Blueprints architecture and concepts <br>&emsp;&emsp; - Learn about add-ons and team management <br>&emsp;&emsp; - Configure VPC for EKS clusters <br>&emsp;&emsp; - Set up Application Load Balancer (ALB) <br>&emsp;&emsp; - Deploy EC2 Kubernetes workers <br>&emsp;&emsp; - Understand EKS control plane and data plane <br>&emsp;&emsp; - Implement cluster autoscaling <br>&emsp;&emsp; - Configure storage classes and persistent volumes <br>&emsp;&emsp; - Set up monitoring and logging with CloudWatch <br>&emsp;&emsp; - Implement RBAC and IAM for EKS <br>&emsp;&emsp; - Deploy common EKS add-ons (metrics-server, cluster-autoscaler) <br>&emsp;&emsp; - Understand GitOps patterns with ArgoCD/Flux <br>&emsp;&emsp; - Implement multi-tenancy with namespaces <br>&emsp;&emsp; - Apply security best practices for EKS                                                                                                                                                                                                                                                                                                                             | 11/04/2025 | 11/04/2025      | [Introduction to EKS Blueprints <br> Infrastructure patterns](https://000065.awsstudygroup.com/)                                                                                                   |
| 4   | - Learn CI/CD on Amazon EKS with CodePipeline and GitHub <br> - Master AWS Lambda serverless computing <br> - Understand serverless application deployment patterns <br> - **Practice:** <br>&emsp; + **CI/CD on EKS with CodePipeline:** <br>&emsp;&emsp; - Set up prerequisites for EKS CI/CD <br>&emsp;&emsp; - Create CodePipeline for EKS deployments <br>&emsp;&emsp; - Integrate GitHub with CodePipeline <br>&emsp;&emsp; - Configure CodeBuild for container builds <br>&emsp;&emsp; - Implement automated testing in pipeline <br>&emsp;&emsp; - Deploy applications to EKS via pipeline <br>&emsp;&emsp; - Set up pipeline notifications and monitoring <br>&emsp;&emsp; - Implement rollback strategies <br>&emsp;&emsp; - Monitor deployment health and logs <br>&emsp; + **AWS Lambda Workshop:** <br>&emsp;&emsp; - Understand Lambda function fundamentals <br>&emsp;&emsp; - Create and deploy Lambda functions <br>&emsp;&emsp; - Configure triggers and event sources <br>&emsp;&emsp; - Implement Lambda with API Gateway <br>&emsp;&emsp; - Set up Lambda layers for dependencies <br>&emsp;&emsp; - Configure environment variables and secrets <br>&emsp;&emsp; - Implement error handling and retries <br>&emsp;&emsp; - Monitor Lambda with CloudWatch Logs <br>&emsp;&emsp; - Optimize Lambda performance and costs <br>&emsp;&emsp; - Apply serverless best practices                                                   | 11/05/2025 | 11/05/2025      | [CI/CD on EKS <br> CodePipeline and GitHub](https://000062.awsstudygroup.com/) <br> <br> [AWS Lambda Workshop <br> Serverless computing](https://000161.awsstudygroup.com/)                        |
| 5   | - Learn Red Hat OpenShift Service on AWS (ROSA) <br> - Master AWS Data Lake architecture and implementation <br> - Understand container orchestration with OpenShift <br> - **Practice:** <br>&emsp; + **Red Hat OpenShift Service on AWS:** <br>&emsp;&emsp; - Understand ROSA architecture and benefits <br>&emsp;&emsp; - Set up prerequisites for ROSA deployment <br>&emsp;&emsp; - Deploy ROSA cluster on AWS <br>&emsp;&emsp; - Configure cluster networking and security <br>&emsp;&emsp; - Deploy applications on OpenShift <br>&emsp;&emsp; - Implement OpenShift operators <br>&emsp;&emsp; - Configure persistent storage <br>&emsp;&emsp; - Set up monitoring and logging <br>&emsp;&emsp; - Manage cluster scaling and upgrades <br>&emsp; + **AWS Data Lake Implementation:** <br>&emsp;&emsp; - Understand Data Lake architecture and concepts <br>&emsp;&emsp; - Design S3-based Data Lake structure <br>&emsp;&emsp; - Implement S3 security best practices <br>&emsp;&emsp; - Configure S3 bucket policies and ACLs <br>&emsp;&emsp; - Set up data cataloging with AWS Glue <br>&emsp;&emsp; - Implement data partitioning strategies <br>&emsp;&emsp; - Configure Amazon Athena for querying <br>&emsp;&emsp; - Set up AWS Lake Formation for governance <br>&emsp;&emsp; - Implement data encryption and access control <br>&emsp;&emsp; - Monitor and optimize Data Lake performance                                         | 11/06/2025 | 11/06/2025      | [Red Hat OpenShift on AWS <br> ROSA deployment](https://000071.awsstudygroup.com/) <br> <br> [AWS Data Lake <br> S3 security practices](https://000035.awsstudygroup.com/)                         |
| 6   | - Learn building advanced Data Lakes with AWS <br> - Master Analytics on AWS with comprehensive data pipeline <br> - Understand end-to-end data analytics architecture <br> - **Practice:** <br>&emsp; + **Building Data Lake with Your Data:** <br>&emsp;&emsp; - Design scalable Data Lake architecture <br>&emsp;&emsp; - Implement data ingestion pipelines <br>&emsp;&emsp; - Configure S3 storage tiers and lifecycle policies <br>&emsp;&emsp; - Set up data cataloging and metadata management <br>&emsp;&emsp; - Implement data quality and validation <br>&emsp;&emsp; - Configure AWS Glue ETL jobs <br>&emsp;&emsp; - Apply data transformation workflows <br>&emsp;&emsp; - Implement data lineage tracking <br>&emsp;&emsp; - Set up data access patterns <br>&emsp; + **Analytics on AWS Workshop:** <br>&emsp;&emsp; - Build end-to-end analytics pipeline <br>&emsp;&emsp; - Configure Amazon RDS for transactional data <br>&emsp;&emsp; - Set up Amazon Redshift for data warehousing <br>&emsp;&emsp; - Implement Amazon EMR for big data processing <br>&emsp;&emsp; - Configure Amazon Kinesis for streaming analytics <br>&emsp;&emsp; - Set up Amazon QuickSight for visualization <br>&emsp;&emsp; - Implement real-time and batch analytics <br>&emsp;&emsp; - Configure data pipeline orchestration <br>&emsp;&emsp; - Optimize query performance <br>&emsp;&emsp; - Apply analytics best practices                     | 11/07/2025 | 11/07/2025      | [Building Data Lake <br> Advanced implementation](https://000070.awsstudygroup.com/) <br> <br> [Analytics on AWS <br> Comprehensive pipeline](https://000072.awsstudygroup.com/)                   |

### Week 9 Achievements:

- **Introduction to Kubernetes Mastery:**

  - Mastered Kubernetes architecture and core components
  - Successfully understood pods, deployments, and services
  - Configured and used kubectl CLI tool effectively
  - Deployed sample applications to Kubernetes clusters
  - Managed Kubernetes resources and namespaces
  - Implemented ConfigMaps and Secrets for configuration
  - Set up health checks and readiness probes
  - Monitored Kubernetes cluster and workload performance
  - Applied best practices for container orchestration

- **Amazon EKS CI/CD Pipeline Expertise:**

  - Mastered Amazon EKS cluster setup and configuration
  - Successfully created IAM roles for CodePipeline and CodeBuild
  - Modified aws-auth ConfigMap for proper RBAC permissions
  - Forked and configured GitHub repositories for deployments
  - Generated GitHub access tokens for pipeline integration
  - Set up AWS CodePipeline for automated EKS deployments
  - Configured CodeBuild for containerized application builds
  - Triggered automated releases via GitHub commits
  - Monitored pipeline executions and deployment status
  - Implemented GitOps workflows for Kubernetes deployments
  - Applied best practices for CI/CD on Kubernetes

- **Amazon EKS Blueprints Infrastructure Mastery:**

  - Mastered EKS Blueprints architecture and patterns
  - Successfully understood add-ons and team management concepts
  - Configured VPC networking for EKS clusters
  - Set up Application Load Balancer for ingress
  - Deployed and managed EC2 Kubernetes worker nodes
  - Understood EKS control plane and data plane separation
  - Implemented cluster autoscaling for dynamic workloads
  - Configured storage classes and persistent volumes
  - Set up monitoring and logging with CloudWatch integration
  - Implemented RBAC and IAM roles for secure access
  - Deployed essential EKS add-ons (metrics-server, cluster-autoscaler)
  - Understood GitOps deployment patterns
  - Implemented multi-tenancy using namespaces
  - Applied security best practices for production EKS clusters

- **CI/CD on Amazon EKS Expertise:**

  - Mastered CI/CD setup for EKS with CodePipeline
  - Successfully created automated deployment pipelines
  - Integrated GitHub with AWS CodePipeline
  - Configured CodeBuild for containerized builds
  - Implemented automated testing in CI/CD pipeline
  - Deployed applications to EKS via automated pipelines
  - Set up pipeline notifications and monitoring
  - Implemented rollback strategies for deployments
  - Monitored deployment health and logs
  - Applied best practices for EKS CI/CD

- **AWS Lambda Serverless Computing Mastery:**

  - Mastered Lambda function fundamentals and architecture
  - Successfully created and deployed Lambda functions
  - Configured event triggers and sources
  - Integrated Lambda with API Gateway
  - Implemented Lambda layers for shared dependencies
  - Configured environment variables and secrets management
  - Implemented error handling and retry mechanisms
  - Monitored Lambda functions with CloudWatch Logs
  - Optimized Lambda performance and cost efficiency
  - Applied serverless best practices

- **Red Hat OpenShift Service on AWS (ROSA) Expertise:**

  - Mastered ROSA architecture and benefits
  - Successfully set up ROSA deployment prerequisites
  - Deployed ROSA clusters on AWS infrastructure
  - Configured cluster networking and security
  - Deployed containerized applications on OpenShift
  - Implemented OpenShift operators for application management
  - Configured persistent storage for stateful applications
  - Set up monitoring and logging for OpenShift clusters
  - Managed cluster scaling and version upgrades
  - Applied best practices for enterprise Kubernetes

- **AWS Data Lake Implementation Mastery:**

  - Mastered Data Lake architecture and design patterns
  - Successfully designed S3-based Data Lake structures
  - Implemented S3 security best practices
  - Configured S3 bucket policies and access controls
  - Set up data cataloging with AWS Glue
  - Implemented data partitioning for query optimization
  - Configured Amazon Athena for SQL-based querying
  - Implemented AWS Lake Formation for data governance
  - Applied data encryption and access control mechanisms
  - Monitored and optimized Data Lake performance

- **Advanced Data Lake Building Expertise:**

  - Mastered scalable Data Lake architecture design
  - Successfully implemented data ingestion pipelines
  - Configured S3 storage tiers and lifecycle policies
  - Set up comprehensive data cataloging and metadata management
  - Implemented data quality and validation frameworks
  - Configured AWS Glue ETL jobs for transformation
  - Applied complex data transformation workflows
  - Implemented data lineage tracking
  - Set up efficient data access patterns
  - Applied performance optimization techniques

- **Analytics on AWS Comprehensive Mastery:**
  - Mastered end-to-end analytics pipeline architecture
  - Successfully configured Amazon RDS for transactional data
  - Set up Amazon Redshift for data warehousing
  - Implemented Amazon EMR for big data processing
  - Configured Amazon Kinesis for streaming analytics
  - Set up Amazon QuickSight for data visualization
  - Implemented both real-time and batch analytics
  - Configured data pipeline orchestration
  - Optimized query performance across analytics stack
  - Applied analytics best practices for production workloads
