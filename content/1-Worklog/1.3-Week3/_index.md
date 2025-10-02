---
title: "Week 3 Worklog"
date: "2025-08-13"
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---



### Week 3 Objectives:

* Connect and get acquainted with members of First Cloud Journey.
* Learn AWS WorkSpaces virtual desktop service for modern cloud-based workstations.
* Master WordPress deployment on AWS Cloud with scalability and high availability.
* Understand AWS Managed Directory Service for enterprise Windows environments.
* Master AWS VM Import/Export for on-premises to cloud migration.
* Learn Database Schema Conversion and Migration using AWS DMS and SCT.
* Master AWS VPC networking concepts and advanced network architecture.
* Understand AWS Site-to-Site VPN for secure hybrid cloud connectivity.
* Learn AWS FSx for Windows File Server enterprise storage solutions.
* Master AWS Direct Connect for dedicated private network connections.
* Understand AWS Client VPN for secure remote user access.
* Learn AWS Transit Gateway for centralized network hub architecture.
* Master AWS PrivateLink for private service connectivity.
* Learn AWS Lambda for serverless computing and event-driven architecture.
* Master Amazon ECS for container orchestration and management.
* Understand Amazon EKS for managed Kubernetes deployments.
* Learn AWS App Runner for simplified containerized application deployment.
* Understand basic AWS services, how to use the console & CLI.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Learn AWS WorkSpaces virtual desktop service and modern working adaptation <br> - Understand WorkSpaces infrastructure and deployment architecture <br> - Master WordPress deployment on AWS Cloud with Auto Scaling and Load Balancing <br> - Learn AWS Managed Directory Service for enterprise Windows environments <br> - **Practice:** <br>&emsp; + **WorkSpaces Deployment:** <br>&emsp;&emsp; - Set up WorkSpaces prerequisites and directory services <br>&emsp;&emsp; - Deploy Amazon WorkSpaces instances <br>&emsp;&emsp; - Access WorkSpaces via client applications and browsers <br>&emsp; + **WordPress on AWS Cloud:** <br>&emsp;&emsp; - Install WordPress on EC2 with RDS MySQL backend <br>&emsp;&emsp; - Implement Auto Scaling Groups for application scalability <br>&emsp;&emsp; - Configure Application Load Balancer for high availability <br>&emsp;&emsp; - Set up CloudFront CDN for global content delivery <br>&emsp;&emsp; - Implement database backup and restore with Multi-AZ <br>&emsp; + **AWS Managed Directory Service:** <br>&emsp;&emsp; - Deploy AWS Managed Active Directory service <br>&emsp;&emsp; - Configure Windows Server 2022 as AD Manager <br>&emsp;&emsp; - Set up Bastion Host for secure remote access <br>&emsp;&emsp; - Implement domain joining and administrative tools | 09/22/2025 | 09/22/2025      | [AWS WorkSpaces Workshop](https://000093.awsstudygroup.com/) <br> <br> [WordPress on AWS Cloud](https://000101.awsstudygroup.com/) <br> <br> [AWS Managed Directory <br> Service](https://000095.awsstudygroup.com/) |
| 3   | - Master AWS VM Import/Export for on-premises to cloud migration <br> - Learn Database Schema Conversion and Migration with AWS DMS and SCT <br> - Understand hybrid cloud migration strategies <br> - **Practice:** <br>&emsp; + **VM Import/Export Workshop:** <br>&emsp;&emsp; - Set up VMware Workstation with Ubuntu Desktop VM <br>&emsp;&emsp; - Configure on-premises virtual machine environment <br>&emsp;&emsp; - Import virtual machine images from on-premises to Amazon EC2 <br>&emsp;&emsp; - Export EC2 instances back to on-premises environment <br>&emsp;&emsp; - Manage S3 storage for VM image files <br>&emsp; + **Database Migration Workshop:** <br>&emsp;&emsp; - Understand AWS Schema Conversion Tool (SCT) concepts <br>&emsp;&emsp; - Learn AWS Database Migration Service (DMS) architecture <br>&emsp;&emsp; - Select and configure DMS source databases <br>&emsp;&emsp; - Select and configure DMS target databases <br>&emsp;&emsp; - Implement serverless replication for database migration <br>&emsp;&emsp; - Monitor DMS migrations and troubleshoot issues | 09/23/2025 | 09/23/2025      | [AWS VM Import/Export](https://000014.awsstudygroup.com/) <br> <br> [Database Schema <br> Conversion & Migration](https://000043.awsstudygroup.com/) |
| 4   | - Learn AWS VPC and advanced networking concepts <br> - Master AWS VPN for secure hybrid cloud connectivity <br> - Understand AWS FSx for Windows File Server enterprise storage <br> - **Practice:** <br>&emsp; + **AWS VPC Networking:** <br>&emsp;&emsp; - Create and configure VPC with custom CIDR blocks <br>&emsp;&emsp; - Set up public and private subnets across multiple AZs <br>&emsp;&emsp; - Configure Internet Gateway for public subnet connectivity <br>&emsp;&emsp; - Implement NAT Gateway for private subnet internet access <br>&emsp;&emsp; - Configure route tables and network ACLs <br>&emsp;&emsp; - Set up security groups for instance-level security <br>&emsp; + **AWS Site-to-Site VPN:** <br>&emsp;&emsp; - Understand VPN architecture and components <br>&emsp;&emsp; - Configure Virtual Private Gateway and Customer Gateway <br>&emsp;&emsp; - Establish VPN connections between on-premises and AWS <br>&emsp;&emsp; - Configure static and dynamic routing with BGP <br>&emsp;&emsp; - Test and verify VPN connectivity <br>&emsp; + **AWS FSx for Windows File Server:** <br>&emsp;&emsp; - Deploy FSx file system with Multi-AZ configuration <br>&emsp;&emsp; - Configure Active Directory integration <br>&emsp;&emsp; - Set up EC2 instances for file server access <br>&emsp;&emsp; - Implement file sharing and permissions <br>&emsp;&emsp; - Configure backup and restore strategies | 09/24/2025 | 09/24/2025      | [AWS VPC Networking](https://000100.awsstudygroup.com/) <br> <br> [AWS Site-to-Site VPN](https://000022.awsstudygroup.com/) <br> <br> [AWS FSx for Windows <br> File Server](https://000029.awsstudygroup.com/) |
| 5   | - Learn AWS Direct Connect for dedicated network connections <br> - Master AWS Client VPN for secure remote access <br> - Understand AWS Transit Gateway for network consolidation <br> - Learn AWS PrivateLink for private connectivity <br> - **Practice:** <br>&emsp; + **AWS Direct Connect:** <br>&emsp;&emsp; - Understand Direct Connect architecture and benefits <br>&emsp;&emsp; - Learn Direct Connect Gateway configuration <br>&emsp;&emsp; - Configure Virtual Private Gateway connections <br>&emsp;&emsp; - Set up routing and BGP configurations <br>&emsp;&emsp; - Understand LAG (Link Aggregation Groups) for bandwidth <br>&emsp; + **AWS Client VPN:** <br>&emsp;&emsp; - Deploy Client VPN endpoint configuration <br>&emsp;&emsp; - Configure mutual authentication with certificates <br>&emsp;&emsp; - Set up client VPN connections and routing <br>&emsp;&emsp; - Implement split-tunnel and full-tunnel configurations <br>&emsp;&emsp; - Configure authorization rules and security groups <br>&emsp; + **AWS Transit Gateway:** <br>&emsp;&emsp; - Understand Transit Gateway architecture and use cases <br>&emsp;&emsp; - Configure Transit Gateway attachments to VPCs <br>&emsp;&emsp; - Set up Transit Gateway route tables <br>&emsp;&emsp; - Implement VPC-to-VPC connectivity via Transit Gateway <br>&emsp;&emsp; - Configure VPN attachments to Transit Gateway <br>&emsp; + **AWS PrivateLink:** <br>&emsp;&emsp; - Understand VPC Endpoint Services and Interface Endpoints <br>&emsp;&emsp; - Configure PrivateLink for AWS services <br>&emsp;&emsp; - Set up custom PrivateLink endpoints <br>&emsp;&emsp; - Implement private connectivity patterns <br>&emsp;&emsp; - Configure endpoint policies and security | 09/25/2025 | 09/25/2025      | [AWS Direct Connect](https://000036.awsstudygroup.com/) <br> <br> [AWS Client VPN](https://000027.awsstudygroup.com/) <br> <br> [AWS Transit Gateway](https://000028.awsstudygroup.com/) <br> <br> [AWS PrivateLink](https://000031.awsstudygroup.com/) |
| 6   | - Learn AWS Lambda serverless computing platform <br> - Master Amazon ECS container orchestration service <br> - Understand Amazon EKS Kubernetes service <br> - Learn AWS App Runner for containerized web applications <br> - **Practice:** <br>&emsp; + **AWS Lambda Serverless:** <br>&emsp;&emsp; - Understand Lambda architecture and execution model <br>&emsp;&emsp; - Create and deploy Lambda functions with various runtimes <br>&emsp;&emsp; - Configure Lambda triggers from multiple event sources <br>&emsp;&emsp; - Implement Lambda function versioning and aliases <br>&emsp;&emsp; - Set up Lambda layers for shared code and dependencies <br>&emsp;&emsp; - Configure environment variables and execution role <br>&emsp;&emsp; - Monitor Lambda performance with CloudWatch <br>&emsp; + **Amazon ECS Container Service:** <br>&emsp;&emsp; - Understand ECS architecture with clusters and services <br>&emsp;&emsp; - Configure ECS task definitions and container specifications <br>&emsp;&emsp; - Deploy ECS services with Fargate and EC2 launch types <br>&emsp;&emsp; - Set up Application Load Balancer integration <br>&emsp;&emsp; - Implement auto-scaling for ECS services <br>&emsp;&emsp; - Configure service discovery and networking <br>&emsp; + **Amazon EKS Kubernetes Service:** <br>&emsp;&emsp; - Understand EKS architecture and Kubernetes concepts <br>&emsp;&emsp; - Create EKS cluster with managed node groups <br>&emsp;&emsp; - Deploy applications using Kubernetes manifests <br>&emsp;&emsp; - Configure kubectl for EKS cluster management <br>&emsp;&emsp; - Implement Kubernetes deployments and services <br>&emsp;&emsp; - Set up ingress controllers and load balancing <br>&emsp; + **AWS App Runner:** <br>&emsp;&emsp; - Understand App Runner architecture and use cases <br>&emsp;&emsp; - Deploy containerized applications from source code <br>&emsp;&emsp; - Configure automatic deployments and scaling <br>&emsp;&emsp; - Set up custom domains and HTTPS <br>&emsp;&emsp; - Implement health checks and monitoring | 09/26/2025 | 09/26/2025      | [AWS Lambda Serverless](https://000058.awsstudygroup.com/) <br> <br> [Amazon ECS Container Service](https://000037.awsstudygroup.com/) <br> <br> [Amazon EKS Kubernetes](https://000038.awsstudygroup.com/) <br> <br> [AWS App Runner](https://000076.awsstudygroup.com/) |


### Week 3 Achievements:

* **AWS WorkSpaces Virtual Desktop Service Mastery:**
  * Understood AWS WorkSpaces concepts and modern cloud-based workstation solutions
  * Successfully explored WorkSpaces infrastructure and deployment architecture
  * Mastered virtual desktop management capabilities for enterprise environments
  * Set up WorkSpaces prerequisites including directory services configuration
  * Successfully deployed Amazon WorkSpaces instances with proper bundles
  * Accessed WorkSpaces via multiple methods: client applications and web browsers
  * Configured WorkSpaces bundles and implemented user management practices
  * Managed WorkSpaces lifecycle including cleanup and resource optimization
  * Understood cost optimization strategies for virtual desktop infrastructure

* **WordPress on AWS Cloud Deployment Expertise:**
  * Mastered scalable WordPress deployment architecture on AWS Cloud
  * Successfully installed WordPress on EC2 instances with RDS MySQL backend
  * Implemented Auto Scaling Groups for dynamic application scaling based on demand
  * Configured Application Load Balancer for high availability and traffic distribution
  * Deployed CloudFront CDN for global content delivery and performance optimization
  * Set up Multi-AZ RDS deployment for database high availability
  * Implemented database backup and restore strategies using RDS snapshots
  * Mastered Launch Templates for standardized EC2 instance deployment
  * Understood Target Groups and load balancing configurations

* **AWS Managed Directory Service Proficiency:**
  * Understood AWS Managed AD concepts and enterprise Windows environments
  * Successfully deployed AWS Managed Active Directory service with high availability
  * Configured Windows Server 2022 as Active Directory Manager with administrative tools
  * Set up Bastion Host for secure remote desktop gateway access
  * Implemented domain joining automation using AWS IAM integration
  * Mastered delegated groups vs normal groups in AWS Managed AD
  * Understood hybrid cloud directory integration capabilities
  * Configured multi-subnet and multi-AZ deployment for directory service resilience
  * Implemented enterprise-level user and computer management through AD tools

* **AWS VM Import/Export Migration Expertise:**
  * Mastered VM Import/Export concepts for hybrid cloud migration strategies
  * Successfully set up VMware Workstation Pro with Ubuntu Desktop virtual machines
  * Configured on-premises virtualization environment with proper networking
  * Implemented VM image import from on-premises environment to Amazon EC2
  * Successfully exported EC2 instances back to on-premises infrastructure
  * Managed Amazon S3 storage for VM image files and migration artifacts
  * Understood migration use cases: application migration, backup, and disaster recovery
  * Mastered cost optimization strategies for VM migration workflows
  * Applied best practices for VM preparation and post-migration configuration

* **Database Schema Conversion & Migration Mastery:**
  * Understood heterogeneous database migration concepts and challenges
  * Mastered AWS Schema Conversion Tool (SCT) for schema transformation
  * Successfully learned AWS Database Migration Service (DMS) architecture
  * Configured DMS source databases from various environments (on-premises, EC2, RDS)
  * Set up DMS target databases including RDS, S3, Kinesis, DynamoDB, and DocumentDB
  * Implemented serverless replication for scalable database migration
  * Monitored DMS migration tasks and performance metrics
  * Troubleshot migration issues and applied remediation strategies
  * Understood minimal downtime migration techniques for production databases

* **AWS VPC Networking Expertise:**
  * Mastered AWS Virtual Private Cloud (VPC) concepts and architecture
  * Successfully created VPC with custom IPv4 CIDR blocks
  * Configured public and private subnets across multiple Availability Zones
  * Implemented Internet Gateway for public subnet internet connectivity
  * Deployed NAT Gateway to enable internet access for private subnets
  * Configured route tables for traffic routing between subnets
  * Implemented Network ACLs for subnet-level security controls
  * Mastered Security Groups for instance-level firewall rules
  * Understood VPC peering and transit gateway concepts
  * Applied best practices for network segmentation and security

* **AWS Site-to-Site VPN Proficiency:**
  * Understood hybrid cloud connectivity using AWS VPN
  * Mastered VPN architecture with Virtual Private Gateway and Customer Gateway
  * Successfully configured Site-to-Site VPN connections
  * Implemented static routing for VPN traffic management
  * Configured dynamic routing using Border Gateway Protocol (BGP)
  * Set up redundant VPN tunnels for high availability
  * Tested and verified VPN connectivity between on-premises and AWS
  * Monitored VPN connection status and troubleshot connectivity issues
  * Understood IPsec encryption and VPN security protocols
  * Applied cost optimization strategies for VPN deployments

* **AWS FSx for Windows File Server Mastery:**
  * Understood AWS FSx concepts for enterprise Windows file storage
  * Successfully deployed FSx file system with Multi-AZ configuration
  * Integrated FSx with AWS Managed Active Directory
  * Configured Windows EC2 instances for FSx file server access
  * Implemented file sharing and NTFS permissions management
  * Set up automated backup and restore strategies
  * Understood deduplication and data compression features
  * Mastered FSx performance optimization and scaling capabilities
  * Configured shadow copies for point-in-time file recovery
  * Implemented monitoring and maintenance best practices
  * Understood cost considerations for FSx deployment

* **AWS Direct Connect Expertise:**
  * Mastered AWS Direct Connect concepts for dedicated private connectivity
  * Understood Direct Connect architecture and connection types (dedicated vs hosted)
  * Learned Direct Connect Gateway for multi-region and multi-VPC connectivity
  * Configured Virtual Private Gateway integration with Direct Connect
  * Understood routing configurations and BGP protocol implementation
  * Mastered Link Aggregation Groups (LAG) for increased bandwidth
  * Learned Direct Connect resiliency and high availability patterns
  * Understood cost optimization strategies for Direct Connect deployments
  * Applied best practices for hybrid cloud network architecture
  * Compared Direct Connect vs VPN for enterprise connectivity scenarios

* **AWS Client VPN Proficiency:**
  * Understood AWS Client VPN concepts for secure remote access
  * Successfully learned Client VPN endpoint architecture and configuration
  * Mastered mutual authentication using client certificates and server certificates
  * Configured Active Directory and SAML-based authentication methods
  * Implemented split-tunnel VPN for optimized traffic routing
  * Set up full-tunnel VPN for complete traffic encryption
  * Configured authorization rules for user access control
  * Implemented security group rules for Client VPN endpoints
  * Understood connection logging and monitoring capabilities
  * Applied cost considerations and scaling strategies for Client VPN

* **AWS Transit Gateway Mastery:**
  * Mastered AWS Transit Gateway concepts for centralized network hub
  * Understood Transit Gateway architecture and scalability benefits
  * Successfully learned Transit Gateway attachment types (VPC, VPN, Direct Connect)
  * Configured Transit Gateway route tables for traffic management
  * Implemented inter-VPC connectivity through Transit Gateway
  * Set up VPN connections to Transit Gateway for hybrid cloud
  * Configured Direct Connect Gateway integration with Transit Gateway
  * Understood Transit Gateway peering for inter-region connectivity
  * Mastered route propagation and static routing configurations
  * Applied network segmentation and security best practices
  * Understood cost optimization for large-scale network architectures

* **AWS PrivateLink Expertise:**
  * Understood AWS PrivateLink concepts for private service connectivity
  * Mastered VPC Endpoint Services and Interface Endpoints architecture
  * Successfully configured PrivateLink for AWS managed services
  * Learned Gateway Endpoints for S3 and DynamoDB private access
  * Implemented custom PrivateLink endpoints for third-party services
  * Configured endpoint policies for fine-grained access control
  * Understood PrivateLink DNS resolution and naming
  * Mastered cross-account PrivateLink service sharing
  * Implemented private connectivity patterns for microservices
  * Applied security best practices for private service exposure
  * Understood cost considerations and scaling for PrivateLink deployments

* **AWS Lambda Serverless Computing Mastery:**
  * Mastered AWS Lambda concepts for serverless event-driven architecture
  * Understood Lambda execution model and compute resource allocation
  * Successfully created Lambda functions with multiple runtime environments (Python, Node.js, Java)
  * Configured Lambda triggers from various event sources (S3, DynamoDB, API Gateway, EventBridge)
  * Implemented Lambda function versioning for code management
  * Set up Lambda aliases for environment-specific deployments
  * Mastered Lambda layers for shared code libraries and dependencies
  * Configured environment variables and execution roles with IAM
  * Implemented error handling and retry logic for Lambda functions
  * Monitored Lambda performance metrics using CloudWatch
  * Understood Lambda pricing model and cost optimization strategies
  * Applied best practices for serverless application architecture

* **Amazon ECS Container Orchestration Expertise:**
  * Mastered Amazon ECS concepts for container orchestration
  * Understood ECS architecture with clusters, services, and tasks
  * Successfully created ECS task definitions with container specifications
  * Configured ECS services with Fargate serverless launch type
  * Deployed ECS services using EC2 launch type for custom configurations
  * Integrated Application Load Balancer for traffic distribution
  * Implemented auto-scaling policies for ECS services based on metrics
  * Configured service discovery using AWS Cloud Map
  * Set up VPC networking and security groups for ECS tasks
  * Mastered ECS task placement strategies and constraints
  * Implemented logging and monitoring with CloudWatch Container Insights
  * Understood cost optimization for Fargate vs EC2 launch types

* **Amazon EKS Kubernetes Service Proficiency:**
  * Understood Amazon EKS concepts for managed Kubernetes clusters
  * Mastered Kubernetes architecture including control plane and worker nodes
  * Successfully created EKS cluster with managed node groups
  * Configured kubectl command-line tool for EKS cluster management
  * Deployed containerized applications using Kubernetes manifests (YAML)
  * Implemented Kubernetes Deployments for application lifecycle management
  * Configured Kubernetes Services for service discovery and load balancing
  * Set up Ingress controllers for external traffic routing
  * Mastered Kubernetes ConfigMaps and Secrets for configuration management
  * Implemented horizontal pod autoscaling based on resource metrics
  * Understood EKS integration with AWS services (IAM, CloudWatch, EBS)
  * Applied Kubernetes best practices for production workloads

* **AWS App Runner Deployment Expertise:**
  * Understood AWS App Runner concepts for simplified container deployment
  * Mastered App Runner architecture and automatic scaling capabilities
  * Successfully deployed containerized web applications from source code repositories
  * Configured App Runner services from Docker container images
  * Implemented automatic deployments triggered by code commits
  * Set up custom domains with HTTPS certificates for App Runner services
  * Configured environment variables and secrets management
  * Implemented health checks for application availability monitoring
  * Mastered App Runner auto-scaling based on concurrent requests
  * Monitored application performance using App Runner metrics
  * Understood cost-effective deployment strategies for web applications
  * Applied best practices for containerized application architecture

* Understood what AWS is and mastered the basic service groups: 
  * Compute
  * Storage
  * Networking 
  * Database
  * ...

* Successfully created and configured an AWS Free Tier account.

* Became familiar with the AWS Management Console and learned how to find, access, and use services via the web interface.

* Installed and configured AWS CLI on the computer, including:
  * Access Key
  * Secret Key
  * Default Region
  * ...

* Used AWS CLI to perform basic operations such as:

  * Check account & configuration information
  * Retrieve the list of regions
  * View EC2 service
  * Create and manage key pairs
  * Check information about running services
  * ...

* Acquired the ability to connect between the web interface and CLI to manage AWS resources in parallel.
* ...
