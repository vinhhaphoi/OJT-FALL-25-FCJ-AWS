---
title: "Week 4 Worklog"
date: "2025-08-14"
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---



### Week 4 Objectives:


* Learn AWS Backup for centralized backup management across AWS services.
* Master AWS Storage Gateway for hybrid cloud storage integration.
* Understand Amazon S3 Glacier for long-term archival storage.
* Learn AWS DataSync for automated data transfer and synchronization.
* Master AWS Control Tower for multi-account AWS environment setup.
* Understand AWS Organizations for centralized account management.
* Learn AWS Service Catalog for standardized service provisioning.
* Master AWS Systems Manager for unified operations management.
* Understand AWS CloudFormation for infrastructure as code.


### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Learn AWS Backup for centralized backup management <br> - Master AWS Storage Gateway for hybrid cloud storage <br> - Understand Amazon S3 Glacier for archival storage <br> - Learn AWS DataSync for automated data transfer <br> - **Practice:** <br>&emsp; + **AWS Backup Service:** <br>&emsp;&emsp; - Understand AWS Backup architecture and features <br>&emsp;&emsp; - Configure backup plans and policies <br>&emsp;&emsp; - Set up backup vaults and access policies <br>&emsp;&emsp; - Implement automated backup schedules <br>&emsp;&emsp; - Perform backup restoration and recovery <br>&emsp;&emsp; - Configure cross-region and cross-account backup <br>&emsp; + **AWS Storage Gateway:** <br>&emsp;&emsp; - Understand Storage Gateway types (File, Volume, Tape) <br>&emsp;&emsp; - Deploy File Gateway for NFS/SMB file storage <br>&emsp;&emsp; - Configure Volume Gateway for iSCSI block storage <br>&emsp;&emsp; - Set up Tape Gateway for virtual tape library <br>&emsp;&emsp; - Implement caching and bandwidth optimization <br>&emsp;&emsp; - Configure on-premises to S3 integration <br>&emsp; + **Amazon S3 Glacier:** <br>&emsp;&emsp; - Understand Glacier storage classes and pricing <br>&emsp;&emsp; - Configure S3 Lifecycle policies for archival <br>&emsp;&emsp; - Implement Glacier retrieval options (Expedited, Standard, Bulk) <br>&emsp;&emsp; - Set up Glacier Vault Lock for compliance <br>&emsp;&emsp; - Configure S3 Intelligent-Tiering for cost optimization <br>&emsp; + **AWS DataSync:** <br>&emsp;&emsp; - Understand DataSync architecture and use cases <br>&emsp;&emsp; - Configure DataSync agents for on-premises transfers <br>&emsp;&emsp; - Set up DataSync tasks for automated transfers <br>&emsp;&emsp; - Implement data validation and verification <br>&emsp;&emsp; - Configure bandwidth throttling and scheduling <br>&emsp;&emsp; - Monitor DataSync task execution and performance | 09/29/2025 | 09/29/2025      | [AWS Backup Service](https://000102.awsstudygroup.com/) <br> <br> [AWS Storage Gateway](https://000032.awsstudygroup.com/) <br> <br> [Amazon S3 Glacier](https://000074.awsstudygroup.com/) <br> <br> [AWS DataSync](https://000075.awsstudygroup.com/) |
| 3   | - Master AWS Control Tower for multi-account environment setup <br> - Understand AWS Organizations for centralized account management <br> - Learn AWS Service Catalog for standardized provisioning <br> - **Practice:** <br>&emsp; + **AWS Control Tower:** <br>&emsp;&emsp; - Understand Control Tower architecture and landing zone <br>&emsp;&emsp; - Set up multi-account AWS environment with Control Tower <br>&emsp;&emsp; - Configure organizational units (OUs) and account structure <br>&emsp;&emsp; - Implement guardrails for preventive and detective controls <br>&emsp;&emsp; - Set up Account Factory for automated account provisioning <br>&emsp;&emsp; - Configure centralized logging and monitoring <br>&emsp;&emsp; - Implement baseline security configurations <br>&emsp; + **AWS Organizations:** <br>&emsp;&emsp; - Understand Organizations architecture and hierarchy <br>&emsp;&emsp; - Create and manage organizational structure <br>&emsp;&emsp; - Configure Service Control Policies (SCPs) <br>&emsp;&emsp; - Implement consolidated billing and cost allocation <br>&emsp;&emsp; - Set up cross-account resource sharing <br>&emsp;&emsp; - Configure centralized security and compliance policies <br>&emsp; + **AWS Service Catalog:** <br>&emsp;&emsp; - Understand Service Catalog architecture and benefits <br>&emsp;&emsp; - Create and manage product portfolios <br>&emsp;&emsp; - Configure provisioning artifacts and constraints <br>&emsp;&emsp; - Set up user access and permissions <br>&emsp;&emsp; - Implement TagOptions for resource tagging <br>&emsp;&emsp; - Configure launch constraints and templates <br>&emsp;&emsp; - Monitor provisioned products and compliance | 09/30/2025 | 09/30/2025      | [AWS Control Tower](https://000063.awsstudygroup.com/) <br> <br> [AWS Organizations](https://000064.awsstudygroup.com/) <br> <br> [AWS Service Catalog](https://000088.awsstudygroup.com/) |
| 4   | - Master AWS Systems Manager for unified operations management <br> - Understand AWS CloudFormation for infrastructure as code <br> - **Practice:** <br>&emsp; + **AWS Systems Manager:** <br>&emsp;&emsp; - Understand Systems Manager architecture and capabilities <br>&emsp;&emsp; - Configure Session Manager for secure instance access <br>&emsp;&emsp; - Set up Run Command for remote command execution <br>&emsp;&emsp; - Implement Patch Manager for automated patching <br>&emsp;&emsp; - Configure State Manager for configuration management <br>&emsp;&emsp; - Set up Parameter Store for configuration data <br>&emsp;&emsp; - Implement Inventory for metadata collection <br>&emsp;&emsp; - Configure Maintenance Windows for scheduled tasks <br>&emsp;&emsp; - Set up Automation for operational tasks <br>&emsp;&emsp; - Monitor compliance and configuration drift <br>&emsp; + **AWS CloudFormation:** <br>&emsp;&emsp; - Understand CloudFormation concepts and templates <br>&emsp;&emsp; - Create CloudFormation stacks with YAML/JSON templates <br>&emsp;&emsp; - Configure stack parameters and outputs <br>&emsp;&emsp; - Implement nested stacks for modular infrastructure <br>&emsp;&emsp; - Set up StackSets for multi-account/region deployment <br>&emsp;&emsp; - Configure drift detection and remediation <br>&emsp;&emsp; - Implement change sets for preview updates <br>&emsp;&emsp; - Set up rollback configuration and policies <br>&emsp;&emsp; - Monitor stack events and troubleshoot failures | 10/01/2025 | 10/01/2025      | [AWS Systems Manager](https://000089.awsstudygroup.com/) <br> <br> [AWS CloudFormation](https://000087.awsstudygroup.com/) |
| 5   | - Learn basic EC2: <br>&emsp; + Instance types <br>&emsp; + AMI <br>&emsp; + EBS <br>&emsp; + ... <br> - SSH connection methods to EC2 <br> - Learn about Elastic IP   <br>                            | 08/14/2025 | 08/15/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Practice:** <br>&emsp; + Launch an EC2 instance <br>&emsp; + Connect via SSH <br>&emsp; + Attach an EBS volume                                                                                     | 08/15/2025 | 08/15/2025      | <https://cloudjourney.awsstudygroup.com/> |


### Week 4 Achievements:

* **AWS Backup Service Mastery:**
  * Mastered AWS Backup concepts for centralized backup management
  * Understood AWS Backup architecture and supported AWS services
  * Successfully configured backup plans with retention policies
  * Set up backup vaults with encryption and access controls
  * Implemented automated backup schedules based on business requirements
  * Performed backup restoration and point-in-time recovery
  * Configured cross-region backup copy for disaster recovery
  * Set up cross-account backup sharing for organizational backup strategies
  * Implemented backup compliance monitoring and reporting
  * Mastered backup lifecycle management and cost optimization
  * Understood backup service integration with AWS Organizations
  * Applied best practices for backup strategy and data protection

* **AWS Storage Gateway Expertise:**
  * Understood AWS Storage Gateway concepts for hybrid cloud storage
  * Mastered three gateway types: File Gateway, Volume Gateway, and Tape Gateway
  * Successfully deployed File Gateway for NFS and SMB protocol support
  * Configured Volume Gateway for iSCSI block storage with cached and stored modes
  * Set up Tape Gateway as virtual tape library (VTL) for backup applications
  * Implemented local caching for low-latency access to frequently used data
  * Configured bandwidth throttling for network optimization
  * Set up Storage Gateway integration with Amazon S3 and Glacier
  * Mastered gateway monitoring using CloudWatch metrics
  * Implemented disaster recovery strategies with Storage Gateway
  * Understood cost optimization for hybrid storage architectures
  * Applied best practices for on-premises to cloud storage migration

* **Amazon S3 Glacier Storage Proficiency:**
  * Mastered Amazon S3 Glacier concepts for long-term archival storage
  * Understood Glacier storage classes: Glacier Instant Retrieval, Flexible Retrieval, Deep Archive
  * Successfully configured S3 Lifecycle policies for automatic archival
  * Implemented Glacier retrieval options with different speed and cost tiers
  * Set up Glacier Vault Lock for regulatory compliance and immutability
  * Configured S3 Intelligent-Tiering for automatic cost optimization
  * Mastered Glacier archive management and retrieval processes
  * Understood Glacier pricing model and cost calculation
  * Implemented data encryption for archived objects
  * Configured S3 Object Lock for write-once-read-many (WORM) compliance
  * Applied archival strategies for different data retention requirements
  * Understood use cases for long-term backup and regulatory compliance

* **AWS DataSync Transfer Mastery:**
  * Mastered AWS DataSync concepts for automated data transfer
  * Understood DataSync architecture with agents and cloud-native transfers
  * Successfully deployed DataSync agents on-premises or in EC2
  * Configured DataSync tasks for automated data synchronization
  * Implemented data transfer from on-premises NFS/SMB to Amazon S3
  * Set up DataSync for EFS-to-EFS and S3-to-S3 transfers
  * Configured data validation and integrity verification
  * Implemented bandwidth throttling to control network usage
  * Set up scheduled transfers for automated data migration
  * Monitored DataSync task execution and performance metrics
  * Understood DataSync vs Snow Family for large-scale data transfers
  * Applied best practices for data migration and synchronization strategies

* **AWS Control Tower Multi-Account Mastery:**
  * Mastered AWS Control Tower concepts for multi-account environment management
  * Understood Control Tower landing zone architecture and components
  * Successfully set up multi-account AWS environment with automated provisioning
  * Configured organizational units (OUs) with hierarchical account structure
  * Implemented preventive guardrails to enforce policies and compliance
  * Set up detective guardrails for monitoring and alerting
  * Mastered Account Factory for automated account creation and baseline configuration
  * Configured centralized logging with AWS CloudTrail and AWS Config
  * Implemented dashboard for compliance and security monitoring
  * Understood Control Tower integration with AWS Organizations and SSO
  * Applied best practices for enterprise-scale multi-account architecture
  * Mastered account lifecycle management and governance

* **AWS Organizations Governance Expertise:**
  * Understood AWS Organizations concepts for centralized account management
  * Mastered organizational hierarchy with root, OUs, and member accounts
  * Successfully created and structured organization with multiple accounts
  * Configured Service Control Policies (SCPs) for permission boundaries
  * Implemented preventive controls across organizational units
  * Set up consolidated billing for cost management and optimization
  * Configured cost allocation tags for detailed billing analysis
  * Implemented cross-account resource sharing with AWS RAM
  * Set up centralized security policies and compliance controls
  * Mastered invitation and account migration processes
  * Understood Organizations integration with Control Tower and SSO
  * Applied best practices for organizational account governance

* **AWS Service Catalog Provisioning Proficiency:**
  * Mastered AWS Service Catalog concepts for standardized provisioning
  * Understood Service Catalog architecture with portfolios and products
  * Successfully created product portfolios with versioned products
  * Configured provisioning artifacts using CloudFormation templates
  * Implemented launch constraints for resource governance
  * Set up template constraints for parameter validation
  * Configured user access and permissions for portfolio sharing
  * Implemented TagOptions for automated resource tagging
  * Set up notification constraints for provisioning events
  * Monitored provisioned products and stack resources
  * Understood Service Catalog integration with AWS Organizations
  * Applied best practices for self-service infrastructure provisioning

* **AWS Systems Manager Operations Mastery:**
  * Mastered AWS Systems Manager concepts for unified operations management
  * Understood Systems Manager architecture and component services
  * Successfully configured Session Manager for secure bastion-less access
  * Implemented Run Command for remote command execution across instances
  * Set up Patch Manager for automated OS and application patching
  * Configured State Manager for desired state configuration management
  * Mastered Parameter Store for secure configuration data storage
  * Implemented Inventory for automated metadata collection
  * Set up Maintenance Windows for scheduled operational tasks
  * Configured Automation for workflow-based operational procedures
  * Monitored compliance status and configuration drift detection
  * Understood Systems Manager integration with CloudWatch and Config
  * Applied best practices for fleet management and operations

* **AWS CloudFormation Infrastructure as Code Expertise:**
  * Mastered AWS CloudFormation concepts for infrastructure as code
  * Understood CloudFormation template structure with YAML and JSON
  * Successfully created CloudFormation stacks for resource provisioning
  * Configured stack parameters for flexible template reusability
  * Implemented stack outputs for cross-stack references
  * Set up nested stacks for modular infrastructure architecture
  * Mastered StackSets for multi-account and multi-region deployments
  * Configured drift detection to identify manual configuration changes
  * Implemented change sets for safe preview of stack updates
  * Set up rollback configuration and automatic rollback triggers
  * Monitored stack events and troubleshot provisioning failures
  * Understood CloudFormation integration with Service Catalog
  * Applied best practices for infrastructure as code and version control

