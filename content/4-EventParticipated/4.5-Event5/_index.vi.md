---
title: "Event 5"
date: "2025-11-29"
weight: 5
chapter: false
pre: " <b> 4.5. </b> "
---

# "AWS Cloud Mastery Series #3 - AWS Well-Architected Security Pillar"

### Thông Tin Sự Kiện

- **Tên sự kiện:** AWS Cloud Mastery Series #3
- **Chủ đề:** AWS Well-Architected Security Pillar
- **Thời gian:** 08:30 – 12:00, Thứ Bảy, ngày 29/11/2025
- **Địa điểm:** Tầng 26, tòa nhà Bitexco, số 02 đường Hải Triều, phường Sài Gòn, thành phố Hồ Chí Minh
- **Vai trò:** Người tham dự
- **Người tổ chức:** Kha Van

### Mục Đích Của Workshop

- Giới thiệu Security Pillar trong AWS Well-Architected Framework
- Hướng dẫn các nguyên tắc bảo mật cốt lõi: Least Privilege, Zero Trust, Defense in Depth
- Thực hành với các AWS Security Services
- Xây dựng Incident Response Playbook

### Lịch Trình Chi Tiết

| Thời gian     | Session                                     | Nội dung                                                                   |
| ------------- | ------------------------------------------- | -------------------------------------------------------------------------- |
| 08:30 - 08:50 | **Opening & Security Foundation**           | Security Pillar, core principles, Shared Responsibility Model, top threats |
| 08:50 - 09:30 |  Pillar 1: Identity & Access Management | Modern IAM Architecture, IAM Identity Center, SCPs                         |
| 09:30 - 09:55 |  Pillar 2: Detection                    | Detection & Continuous Monitoring, CloudTrail, GuardDuty, Security Hub     |
| 09:55 - 10:10 | **Coffee Break**                            | Nghỉ giải lao                                                              |
| 10:10 - 10:40 |  Pillar 3: Infrastructure Protection    | Network & Workload Security, VPC, WAF, Shield                              |
| 10:40 - 11:10 |  Pillar 4: Data Protection              | Encryption, Keys & Secrets, KMS, Secrets Manager                           |
| 11:10 - 11:40 |  Pillar 5: Incident Response            | IR Playbook & Automation                                                   |
| 11:40 - 12:00 | **Wrap-Up & Q&A**                           | Tổng kết, common pitfalls, certification roadmap                           |

### Nội Dung Nổi Bật - 5 Security Pillars

#### Foundation: Security Principles

- **Vai trò Security Pillar:** Trong AWS Well-Architected Framework
- **Nguyên tắc cốt lõi:**
  - **Least Privilege:** Chỉ cấp quyền tối thiểu cần thiết
  - **Zero Trust:** Không tin tưởng mặc định, luôn xác thực
  - **Defense in Depth:** Bảo vệ nhiều lớp
- **Shared Responsibility Model:** Phân chia trách nhiệm AWS vs Customer
- **Top threats:** Các mối đe dọa phổ biến trong môi trường cloud tại Việt Nam

---

#### Pillar 1: Identity & Access Management

- **IAM Best Practices:**

  - Users, Roles, Policies
  - Tránh long-term credentials
  - Temporary credentials với STS

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

  - Key policies và grants
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

- **IR Lifecycle theo AWS:**

  - Preparation
  - Detection & Analysis
  - Containment, Eradication, Recovery
  - Post-Incident Activity

- **Playbooks cho các scenarios phổ biến:**

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

### Những Gì Học Được

#### Security Mindset

- **Security as enabler:** Bảo mật không phải rào cản mà là enabler cho business
- **Shift-left security:** Tích hợp bảo mật từ giai đoạn thiết kế
- **Continuous security:** Bảo mật là process liên tục, không phải one-time

#### Technical Skills

- **IAM mastery:** Thiết kế IAM policies an toàn và hiệu quả
- **Detection engineering:** Xây dựng detection rules và alerts
- **Encryption everywhere:** Mã hóa data at-rest và in-transit
- **IR automation:** Tự động hóa incident response

#### Vietnamese Context

- **Local threats:** Hiểu các mối đe dọa phổ biến tại Việt Nam
- **Compliance:** Các yêu cầu compliance local
- **Common pitfalls:** Các lỗi phổ biến của doanh nghiệp Việt Nam

#### Certification Path

- **AWS Security Specialty:** Lộ trình chứng chỉ chuyên sâu
- **Solutions Architect Professional:** Kiến thức security cho SA Pro

### Ứng Dụng Vào Công Việc

- **Review IAM policies:** Audit và tối ưu IAM trong các dự án hiện tại
- **Enable MFA:** Bắt buộc MFA cho tất cả users
- **Setup GuardDuty:** Enable threat detection
- **Implement encryption:** Mã hóa data everywhere
- **Create IR playbooks:** Xây dựng playbook cho các scenarios phổ biến
- **Enable Security Hub:** Centralize security findings

### Trải Nghiệm Trong Sự Kiện

Workshop về Security Pillar là một trải nghiệm rất quan trọng và thực tiễn:

- **Comprehensive coverage:** Bao quát tất cả 5 security pillars
- **Vietnamese context:** Các threats và pitfalls specific cho Việt Nam
- **Practical playbooks:** IR playbooks có thể áp dụng ngay
- **Demo thực tế:** IAM policy validation và simulation
- **Career guidance:** Roadmap cho Security Specialty certification
- **Networking:** Kết nối với security professionals

#### Một số hình ảnh khi tham gia sự kiện

<div style="text-align: left;">
  <img src="/images/4-EventsParticipated/Series3.jpeg" alt="AWS Cloud Mastery Series #3 - Security Pillar" width="50%">
  <br><br>
  <video width="50%" controls>
    <source src="/images/4-EventsParticipated/Series3.mp4" type="video/mp4">
  </video>
</div>

> Tổng thể, workshop cung cấp nền tảng vững chắc về cloud security theo AWS Well-Architected Framework. Security Pillar là foundation quan trọng cho bất kỳ workload nào trên cloud, và việc hiểu rõ 5 pillars giúp xây dựng hệ thống an toàn và resilient.
