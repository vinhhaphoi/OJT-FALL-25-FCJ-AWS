---
title: "Week 8 Worklog"
date: "2025-10-27"
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Week 8 Objectives:

* **Master AWS Chatbot for Notifications:**
  * Understand AWS Chatbot concepts and integrations
  * Configure Slack and Microsoft Teams channels
  * Set up CloudWatch alarms and notifications
  * Implement event routing and filtering
  * Monitor chat operations and usage

* **Learn AWS AppConfig for Configuration Management:**
  * Understand AppConfig concepts and deployment
  * Configure applications and environments
  * Implement feature flags and configuration profiles
  * Set up deployment strategies and validators
  * Monitor configuration deployments

* **Master AWS Systems Manager Session Manager:**
  * Understand Session Manager concepts and security
  * Configure secure instance access
  * Implement session logging and auditing
  * Set up session preferences and settings
  * Monitor session activities

* **Learn Amazon Athena for Serverless SQL Queries:**
  * Understand Athena concepts and serverless architecture
  * Configure Athena workgroups and query settings
  * Create databases and tables from S3 data
  * Write and optimize SQL queries for S3 data
  * Implement partitioning for query performance
  * Set up data catalogs with AWS Glue
  * Configure query result locations and encryption
  * Use prepared statements for parameterized queries
  * Monitor query execution and costs

* **Master AWS Data Pipeline for Data Workflow Orchestration:**
  * Understand Data Pipeline concepts and components
  * Design and create data pipeline definitions
  * Configure pipeline activities and schedules
  * Set up data nodes for sources and destinations
  * Implement preconditions and dependencies
  * Configure pipeline resources and compute
  * Set up error handling and retries
  * Monitor pipeline execution and logs
  * Implement data transformation workflows

* **Understand AWS Batch for Batch Computing Workloads:**
  * Learn AWS Batch concepts and architecture
  * Create batch compute environments
  * Configure job queues and priorities
  * Define job definitions with container images
  * Submit and manage batch jobs
  * Set up job dependencies and scheduling
  * Configure resource requirements and constraints
  * Implement job monitoring and logging
  * Optimize batch processing costs

* **Master AWS Step Functions for Workflow Orchestration:**
  * Understand Step Functions concepts and state machines
  * Configure task states and integrations
  * Implement parallel and choice states
  * Set up error handling and retry logic
  * Configure wait states and timeouts
  * Implement callback patterns
  * Monitor executions and state transitions
  * Use Express and Standard workflows

* **Learn Amazon Rekognition for Image and Video Analysis:**
  * Understand Rekognition concepts and features
  * Detect labels and objects in images
  * Perform facial analysis and recognition
  * Detect text in images (OCR)
  * Analyze video content and activities
  * Create face collections and search
  * Detect unsafe content moderation
  * Implement celebrity recognition
  * Monitor API usage and costs

* **Understand Amazon Transcribe for Speech-to-Text Conversion:**
  * Learn Transcribe concepts and capabilities
  * Transcribe audio files to text
  * Configure real-time streaming transcription
  * Implement custom vocabularies
  * Set up speaker identification
  * Configure language identification
  * Implement redaction for sensitive data
  * Use custom language models
  * Monitor transcription jobs

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ----------------- |
| 2   | - Learn AWS Chatbot for DevOps notifications <br> - Master AWS AppConfig for configuration management <br> - Understand AWS Systems Manager Session Manager <br> - **Practice:** <br>&emsp; + **AWS Chatbot:** <br>&emsp;&emsp; - Configure Slack workspace integration <br>&emsp;&emsp; - Set up Microsoft Teams channel integration <br>&emsp;&emsp; - Configure CloudWatch alarm notifications <br>&emsp;&emsp; - Implement SNS topic subscriptions <br>&emsp;&emsp; - Set up Security Hub findings notifications <br>&emsp;&emsp; - Configure GuardDuty alert routing <br>&emsp;&emsp; - Implement notification filtering and customization <br>&emsp;&emsp; - Monitor chatbot delivery metrics <br>&emsp; + **AWS AppConfig:** <br>&emsp;&emsp; - Create AppConfig application and environments <br>&emsp;&emsp; - Configure configuration profiles and versions <br>&emsp;&emsp; - Implement feature flags for gradual rollouts <br>&emsp;&emsp; - Set up deployment strategies (linear, exponential) <br>&emsp;&emsp; - Configure validators for configuration validation <br>&emsp;&emsp; - Implement rollback mechanisms <br>&emsp;&emsp; - Monitor deployment progress and health <br>&emsp; + **Systems Manager Session Manager:** <br>&emsp;&emsp; - Configure Session Manager prerequisites <br>&emsp;&emsp; - Set up secure instance access without SSH keys <br>&emsp;&emsp; - Implement session logging to S3 and CloudWatch <br>&emsp;&emsp; - Configure session preferences and timeout settings <br>&emsp;&emsp; - Set up port forwarding for applications <br>&emsp;&emsp; - Implement session document customization <br>&emsp;&emsp; - Monitor and audit session activities | 10/27/2025 | 10/27/2025 | [AWS Chatbot](https://000138.awsstudygroup.com/) <br> <br> [AWS AppConfig](https://000139.awsstudygroup.com/) <br> <br> [Systems Manager <br> Session Manager](https://000140.awsstudygroup.com/) |
| 3   | - Learn Amazon Athena for serverless SQL queries <br> - Master AWS Data Pipeline for data workflow orchestration <br> - Understand AWS Batch for batch computing workloads <br> - **Practice:** <br>&emsp; + **Amazon Athena:** <br>&emsp;&emsp; - Configure Athena workgroups and query settings <br>&emsp;&emsp; - Create databases and tables from S3 data <br>&emsp;&emsp; - Write and optimize SQL queries for S3 data <br>&emsp;&emsp; - Implement partitioning for query performance <br>&emsp;&emsp; - Set up data catalogs with AWS Glue <br>&emsp;&emsp; - Configure query result locations and encryption <br>&emsp;&emsp; - Use prepared statements for parameterized queries <br>&emsp;&emsp; - Monitor query execution and costs <br>&emsp; + **AWS Data Pipeline:** <br>&emsp;&emsp; - Design and create data pipeline definitions <br>&emsp;&emsp; - Configure pipeline activities and schedules <br>&emsp;&emsp; - Set up data nodes for sources and destinations <br>&emsp;&emsp; - Implement preconditions and dependencies <br>&emsp;&emsp; - Configure pipeline resources and compute <br>&emsp;&emsp; - Set up error handling and retries <br>&emsp;&emsp; - Monitor pipeline execution and logs <br>&emsp;&emsp; - Implement data transformation workflows <br>&emsp; + **AWS Batch:** <br>&emsp;&emsp; - Create batch compute environments <br>&emsp;&emsp; - Configure job queues and priorities <br>&emsp;&emsp; - Define job definitions with container images <br>&emsp;&emsp; - Submit and manage batch jobs <br>&emsp;&emsp; - Set up job dependencies and scheduling <br>&emsp;&emsp; - Configure resource requirements and constraints <br>&emsp;&emsp; - Implement job monitoring and logging <br>&emsp;&emsp; - Optimize batch processing costs | 10/28/2025 | 10/28/2025 | [Amazon Athena](https://000066.awsstudygroup.com/) <br> <br> [AWS Data Pipeline](https://000117.awsstudygroup.com/) <br> <br> [AWS Batch](https://000112.awsstudygroup.com/) |
| 4   | - Learn AWS Step Functions for workflow orchestration <br> - Master Amazon Rekognition for image and video analysis <br> - Understand Amazon Transcribe for speech-to-text conversion <br> - **Practice:** <br>&emsp; + **AWS Step Functions:** <br>&emsp;&emsp; - Create state machines with JSON definitions <br>&emsp;&emsp; - Configure task states and Lambda integrations <br>&emsp;&emsp; - Implement parallel and choice states <br>&emsp;&emsp; - Set up error handling and retry logic <br>&emsp;&emsp; - Configure wait states and timeouts <br>&emsp;&emsp; - Implement callback patterns <br>&emsp;&emsp; - Monitor executions and state transitions <br>&emsp;&emsp; - Use Express and Standard workflows <br>&emsp; + **Amazon Rekognition:** <br>&emsp;&emsp; - Detect labels and objects in images <br>&emsp;&emsp; - Perform facial analysis and recognition <br>&emsp;&emsp; - Detect text in images (OCR) <br>&emsp;&emsp; - Analyze video content and activities <br>&emsp;&emsp; - Create face collections and search <br>&emsp;&emsp; - Detect unsafe content moderation <br>&emsp;&emsp; - Implement celebrity recognition <br>&emsp;&emsp; - Monitor API usage and costs <br>&emsp; + **Amazon Transcribe:** <br>&emsp;&emsp; - Transcribe audio files to text <br>&emsp;&emsp; - Configure real-time streaming transcription <br>&emsp;&emsp; - Implement custom vocabularies <br>&emsp;&emsp; - Set up speaker identification <br>&emsp;&emsp; - Configure language identification <br>&emsp;&emsp; - Implement redaction for sensitive data <br>&emsp;&emsp; - Use custom language models <br>&emsp;&emsp; - Monitor transcription jobs | 10/29/2025 | 10/29/2025 | [AWS Step Functions](https://000113.awsstudygroup.com/) <br> <br> [Amazon Rekognition](https://000021.awsstudygroup.com/) <br> <br> [Amazon Transcribe](https://000091.awsstudygroup.com/) |

### Week 8 Achievements:

* **AWS Chatbot DevOps Notifications Mastery:**
  * Mastered AWS Chatbot concepts and channel integrations
  * Successfully configured Slack workspace and channels
  * Integrated Microsoft Teams for DevOps notifications
  * Set up CloudWatch alarm routing to chat channels
  * Configured SNS topic subscriptions for event notifications
  * Implemented Security Hub findings delivery to teams
  * Routed GuardDuty security alerts to chat channels
  * Applied notification filtering for relevant alerts
  * Monitored chatbot delivery and engagement metrics
  * Applied best practices for DevOps collaboration

* **AWS AppConfig Configuration Management Expertise:**
  * Mastered AppConfig concepts for dynamic configuration
  * Successfully created applications and environments
  * Configured configuration profiles with versioning
  * Implemented feature flags for controlled rollouts
  * Set up deployment strategies (linear, canary, exponential)
  * Configured validators for configuration validation
  * Implemented automatic rollback on deployment failures
  * Monitored deployment health and progress
  * Applied best practices for safe configuration changes

* **Systems Manager Session Manager Security Proficiency:**
  * Mastered Session Manager concepts for secure access
  * Successfully configured bastion-less instance access
  * Eliminated need for SSH keys and open inbound ports
  * Implemented session logging to S3 and CloudWatch Logs
  * Configured session preferences and timeout policies
  * Set up port forwarding for secure application access
  * Created custom session documents for operations
  * Monitored and audited all session activities
  * Applied best practices for secure operational access

* **Amazon Athena Serverless Query Mastery:**
  * Mastered Athena concepts for serverless SQL analytics
  * Successfully configured Athena workgroups and query settings
  * Created databases and tables from S3 data sources
  * Wrote and optimized SQL queries for large datasets
  * Implemented partitioning strategies for query performance
  * Integrated Athena with AWS Glue Data Catalog
  * Configured query result locations with encryption
  * Used prepared statements for secure parameterized queries
  * Monitored query execution times and data scanned
  * Applied best practices for cost optimization

* **AWS Data Pipeline Orchestration Expertise:**
  * Mastered Data Pipeline concepts for workflow automation
  * Successfully designed and created pipeline definitions
  * Configured pipeline activities and execution schedules
  * Set up data nodes for multiple sources and destinations
  * Implemented preconditions and activity dependencies
  * Configured pipeline resources and compute environments
  * Set up comprehensive error handling and retry logic
  * Monitored pipeline execution status and logs
  * Implemented complex data transformation workflows
  * Applied best practices for reliable data pipelines

* **AWS Batch Computing Proficiency:**
  * Mastered AWS Batch concepts for batch workloads
  * Successfully created managed and unmanaged compute environments
  * Configured job queues with proper priorities
  * Defined job definitions with Docker container images
  * Submitted and managed batch jobs programmatically
  * Set up job dependencies and array jobs
  * Configured resource requirements (vCPU, memory, GPU)
  * Implemented comprehensive job monitoring and logging
  * Optimized batch processing costs with Spot instances
  * Applied best practices for scalable batch computing

* **AWS Step Functions Workflow Orchestration Mastery:**
  * Mastered Step Functions concepts for serverless workflows
  * Successfully created state machines with JSON definitions
  * Configured task states with Lambda and AWS service integrations
  * Implemented parallel states for concurrent execution
  * Set up choice states for conditional branching
  * Configured error handling with Catch and Retry
  * Implemented wait states and timeouts for delays
  * Used callback patterns for external processes
  * Monitored workflow executions and state transitions
  * Applied best practices for workflow design

* **Amazon Rekognition Computer Vision Expertise:**
  * Mastered Rekognition concepts for image and video analysis
  * Successfully detected labels and objects in images
  * Performed facial analysis including age and emotion detection
  * Implemented facial recognition with face collections
  * Detected and extracted text from images (OCR)
  * Analyzed video content for activities and objects
  * Configured content moderation for unsafe content
  * Implemented celebrity recognition features
  * Monitored API usage and optimization strategies
  * Applied best practices for ML-powered vision

* **Amazon Transcribe Speech-to-Text Proficiency:**
  * Mastered Transcribe concepts for audio transcription
  * Successfully transcribed audio files to text
  * Configured real-time streaming transcription
  * Implemented custom vocabularies for accuracy
  * Set up speaker identification (diarization)
  * Configured automatic language identification
  * Implemented content redaction for PII
  * Used custom language models for domain-specific terms
  * Monitored transcription job performance
  * Applied best practices for speech recognition
