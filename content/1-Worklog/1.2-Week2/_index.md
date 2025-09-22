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


### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Understand and implement IAM roles and policies <br> - Understand AWS Cloud9 can do and how to implement <br> - Explore Basic features in AWS Cloud 9 <br> - Using AWS CLI for list EC2 instances in account <br> - Starting services with Amazon S3 Services <br> - **Practice:** <br>&emsp; + Create IAM user and access key <br>&emsp; + Attach IAM policy to grant necessary permissions <br>&emsp; + AWS Cloud9: <br>&emsp;&emsp; - By using Command Line <br>&emsp;&emsp; - Working with text file <br>&emsp;&emsp; - Return to Dashboard <br>&emsp; + Using command: aws ec2 describe-instances for list EC2 instances in account in AWS CLI command <br>&emsp; + Amazon S3: <br>&emsp;&emsp; - Hosting static website with Amazon S3 <br>&emsp;&emsp; - Using CloudFront for hosting static website | 09/15/2025 | 09/15/2025 | [AWS Cloud9](https://000049.awsstudygroup.com/) <br> <br> [Grant permission for IAM <br> role](https://000048.awsstudygroup.com/) <br> <br> [Hosting static website <br> with Amazon S3](https://000057.awsstudygroup.com/)|
| 3   | - Explore Amazon Relational Database Service (Amazon RDS) and their benefits <br> - Amazon Lightsail Container: <br>&emsp; +  Understand Lightsail Container <br>&emsp; + Deploy container image to Amazon Lightsail Container by using Docker on Ubuntu <br> - Explore for deploy FCJ Management with Auto Scaling Group <br> - **Practice:** <br>&emsp; + Deploy Amazon RDS <br>&emsp; + Deploy Application with MySQL <br>&emsp; + Backup and Restore in Amazon RDS <br>&emsp; + Build container image and deploy <br>&emsp; + Deploy FCJ Management: <br>&emsp;&emsp; - Create Launch Template and Setup Load balance <br>&emsp;&emsp; - Create Auto Scaling Group | 09/16/2025 | 09/16/2025 | [Amazon RDS](https://000005.awsstudygroup.com/) <br> <br> [Amazon Lightsail](https://000046.awsstudygroup.com/) <br> <br> [Deploy an application <br> with Amazon EC2 Auto <br> Scaling](https://000006.awsstudygroup.com/)|
| 4   | - Learn and create CloudFormation with template file <br> - Using CloudWatch Metrics, CloudWatch Logs and CloudWatch dashboard <br> - Understand Hybrid DNS with Route 53 Resolver <br> - **Practice:** <br>&emsp; + CloudWatch: <br>&emsp;&emsp; - CloudWatch lets users choose and display metrics from their applications <br>&emsp;&emsp; - Filter data using advanced search expressions <br>&emsp;&emsp; - Apply math calculations for deeper insights like averages or rankings <br>&emsp;&emsp; - Add dynamic labels to improve chart readability and interpretation. <br>&emsp; + Route 53 Resolver: <br>&emsp;&emsp; - Initialize CloudFormation by template. <br>&emsp;&emsp; - Create and deploy Microsoft AD (AWS Managed Microsoft Active Directory) <br>&emsp;&emsp; - Setup DNS with In/out Endpoint| 09/17/2025 | 09/17/2025      | [CloudWatch workshop](https://000008.awsstudygroup.com/) <br> <br> [Hybrid DNS with Route 53](https://000010.awsstudygroup.com/)|
| 5   | - Learn basic EC2: <br>&emsp; + Instance types <br>&emsp; + AMI <br>&emsp; + EBS <br>&emsp; + ... <br> - SSH connection methods to EC2 <br> - Learn about Elastic IP   <br>                            | 08/14/2025 | 08/15/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Practice:** <br>&emsp; + Launch an EC2 instance <br>&emsp; + Connect via SSH <br>&emsp; + Attach an EBS volume                                                                                     | 08/15/2025 | 08/15/2025      | <https://cloudjourney.awsstudygroup.com/> |


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

* **Cloud Development Workflow:**
  * Established complete development environment on cloud
  * Developed skills in working with cloud-based tools and services
  * Understood how to integrate multiple AWS services in a workflow
  * Built foundation for advanced cloud development practices
  * Integrated database services into cloud application architecture
  * Mastered containerization and auto scaling in cloud architecture
  * Implemented Infrastructure as Code and comprehensive monitoring solutions
