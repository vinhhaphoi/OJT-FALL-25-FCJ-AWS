---
title: "Event 5"
date: "2025-11-29"
weight: 5
chapter: false
pre: " <b> 4.5. </b> "
---

# "AWS Cloud Mastery Series #3 - AWS Well-Architected Security Pillar"

### Event Information

- **Event Name:** AWS Cloud Mastery Series #3
- **Topic:** AWS Well-Architected Security Pillar
- **Time:** 08:30 – 12:00, Saturday, November 29, 2025
- **Location:** 26th Floor, Bitexco Tower, 02 Hai Trieu Street, Saigon Ward, Ho Chi Minh City
- **Role:** Attendee
- **Organizer:** Kha Van

### Workshop Objectives

- Introduction to Security Pillar in AWS Well-Architected Framework
- Guide to core security principles: Least Privilege, Zero Trust, Defense in Depth
- Hands-on with AWS Security Services
- Building Incident Response Playbooks

### Detailed Schedule

| Time          | Session                                     | Content                                                                    |
| ------------- | ------------------------------------------- | -------------------------------------------------------------------------- |
| 08:30 - 08:50 | **Opening & Security Foundation**           | Security Pillar, core principles, Shared Responsibility Model, top threats |
| 08:50 - 09:30 |  Pillar 1: Identity & Access Management | Modern IAM Architecture, IAM Identity Center, SCPs                         |
| 09:30 - 09:55 |  Pillar 2: Detection                    | Detection & Continuous Monitoring, CloudTrail, GuardDuty, Security Hub     |
| 09:55 - 10:10 | **Coffee Break**                            | Break                                                                      |
| 10:10 - 10:40 |  Pillar 3: Infrastructure Protection    | Network & Workload Security, VPC, WAF, Shield                              |
| 10:40 - 11:10 |  Pillar 4: Data Protection              | Encryption, Keys & Secrets, KMS, Secrets Manager                           |
| 11:10 - 11:40 |  Pillar 5: Incident Response            | IR Playbook & Automation                                                   |
| 11:40 - 12:00 | **Wrap-Up & Q&A**                           | Summary, common pitfalls, certification roadmap                            |

### Key Highlights - 5 Security Pillars

#### Foundation: Security Principles

- **Security Pillar role:** In AWS Well-Architected Framework
- **Core principles:**
  - **Least Privilege:** Grant only minimum necessary permissions
  - **Zero Trust:** Never trust by default, always verify
  - **Defense in Depth:** Multi-layer protection
- **Shared Responsibility Model:** Division of responsibilities between AWS and Customer
- **Top threats:** Common threats in cloud environment in Vietnam

---

#### Pillar 1: Identity & Access Management

- **IAM Best Practices:**

  - Users, Roles, Policies
  - Avoid long-term credentials
  - Temporary credentials with STS

- **IAM Identity Center:**

  - Single Sign-On (SSO)
  - Permission sets
  - Centralized access management

- **Multi-Account Security:**

  - Service Control Policies (SCPs)
  - Permission boundaries
  - AWS Organizations

- **Authentication:**

  - MFA enforcement
  - Credential rotation
  - IAM Access Analyzer

- **Mini Demo:** Validate IAM Policy + simulate access

---

#### Pillar 2: Detection & Continuous Monitoring

- **Logging & Audit:**

  - CloudTrail (org-level)
  - VPC Flow Logs
  - ALB/S3 access logs

- **Threat Detection:**

  - Amazon GuardDuty
  - AWS Security Hub
  - Finding aggregation

- **Alerting & Automation:**

  - EventBridge rules
  - SNS notifications
  - Auto-remediation

- **Detection-as-Code:**
  - Infrastructure rules
  - Custom detection rules

---

#### Pillar 3: Infrastructure Protection

- **Network Security:**

  - VPC segmentation
  - Private vs public subnet placement
  - Security Groups vs NACLs

- **Perimeter Protection:**

  - AWS WAF (Web Application Firewall)
  - AWS Shield (DDoS protection)
  - AWS Network Firewall

- **Workload Protection:**
  - EC2 security basics
  - ECS/EKS security
  - Instance hardening

---

#### Pillar 4: Data Protection

- **AWS KMS (Key Management Service):**

  - Key policies and grants
  - Key rotation
  - Customer Managed Keys (CMK)

- **Encryption:**

  - At-rest: S3, EBS, RDS, DynamoDB
  - In-transit: TLS/SSL
  - Client-side vs Server-side encryption

- **Secrets Management:**

  - AWS Secrets Manager
  - SSM Parameter Store
  - Secret rotation patterns

- **Data Classification:**
  - Data lifecycle
  - Access guardrails
  - Compliance requirements

---

#### Pillar 5: Incident Response

- **IR Lifecycle per AWS:**

  - Preparation
  - Detection & Analysis
  - Containment, Eradication, Recovery
  - Post-Incident Activity

- **Playbooks for common scenarios:**

  - Compromised IAM key
  - S3 public exposure
  - EC2 malware detection

- **Evidence Collection:**

  - Snapshot creation
  - Instance isolation
  - Log preservation

- **Automation:**
  - Lambda-based response
  - Step Functions orchestration
  - Auto-remediation patterns

### Key Takeaways

#### Security Mindset

- **Security as enabler:** Security is not a barrier but an enabler for business
- **Shift-left security:** Integrate security from design phase
- **Continuous security:** Security is a continuous process, not one-time

#### Technical Skills

- **IAM mastery:** Design secure and effective IAM policies
- **Detection engineering:** Build detection rules and alerts
- **Encryption everywhere:** Encrypt data at-rest and in-transit
- **IR automation:** Automate incident response

#### Vietnamese Context

- **Local threats:** Understanding common threats in Vietnam
- **Compliance:** Local compliance requirements
- **Common pitfalls:** Common mistakes by Vietnamese enterprises

#### Certification Path

- **AWS Security Specialty:** Advanced certification roadmap
- **Solutions Architect Professional:** Security knowledge for SA Pro

### Application to Work

- **Review IAM policies:** Audit and optimize IAM in current projects
- **Enable MFA:** Require MFA for all users
- **Setup GuardDuty:** Enable threat detection
- **Implement encryption:** Encrypt data everywhere
- **Create IR playbooks:** Build playbooks for common scenarios
- **Enable Security Hub:** Centralize security findings

### Event Experience

The Security Pillar workshop was a very important and practical experience:

- **Comprehensive coverage:** Covering all 5 security pillars
- **Vietnamese context:** Threats and pitfalls specific to Vietnam
- **Practical playbooks:** IR playbooks that can be applied immediately
- **Real demo:** IAM policy validation and simulation
- **Career guidance:** Roadmap for Security Specialty certification
- **Networking:** Connecting with security professionals

#### Photos/ videos from the Event

<div style="text-align: left;">
  <img src="/images/4-EventsParticipated/Series3.jpeg" alt="AWS Cloud Mastery Series #3 - Security Pillar" width="50%">
  <br><br>
  <video width="50%" controls>
    <source src="/images/4-EventsParticipated/Series3.mp4" type="video/mp4">
  </video>
</div>

> Overall, the workshop provided a solid foundation for cloud security according to AWS Well-Architected Framework. Security Pillar is an important foundation for any workload on cloud, and understanding the 5 pillars helps build secure and resilient systems.
