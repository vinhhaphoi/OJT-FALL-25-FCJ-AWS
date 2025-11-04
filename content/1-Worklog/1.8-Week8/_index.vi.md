---
title: "Worklog Tuần 8"
date: "2025-10-27"
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* **Thành thạo AWS Chatbot cho Thông báo:**
  * Hiểu khái niệm AWS Chatbot và tích hợp
  * Cấu hình kênh Slack và Microsoft Teams
  * Thiết lập CloudWatch alarms và thông báo
  * Triển khai định tuyến và lọc sự kiện
  * Giám sát hoạt động và sử dụng chat

* **Học AWS AppConfig cho Configuration Management:**
  * Hiểu khái niệm AppConfig và triển khai
  * Cấu hình ứng dụng và môi trường
  * Triển khai feature flags và configuration profiles
  * Thiết lập chiến lược triển khai và validators
  * Giám sát triển khai cấu hình

* **Thành thạo AWS Systems Manager Session Manager:**
  * Hiểu khái niệm Session Manager và bảo mật
  * Cấu hình truy cập instance an toàn
  * Triển khai session logging và auditing
  * Thiết lập tùy chọn và cài đặt session
  * Giám sát hoạt động session

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ---- | ---------- | --------------- | ----------------- |
| 2   | - Học AWS Chatbot cho thông báo DevOps <br> - Thành thạo AWS AppConfig cho quản lý cấu hình <br> - Hiểu AWS Systems Manager Session Manager <br> - **Thực hành:** <br>&emsp; + **AWS Chatbot:** <br>&emsp;&emsp; - Cấu hình tích hợp Slack workspace <br>&emsp;&emsp; - Thiết lập tích hợp Microsoft Teams channel <br>&emsp;&emsp; - Cấu hình thông báo CloudWatch alarm <br>&emsp;&emsp; - Triển khai đăng ký SNS topic <br>&emsp;&emsp; - Thiết lập thông báo Security Hub findings <br>&emsp;&emsp; - Cấu hình định tuyến cảnh báo GuardDuty <br>&emsp;&emsp; - Triển khai lọc và tùy chỉnh thông báo <br>&emsp;&emsp; - Giám sát metrics phân phối chatbot <br>&emsp; + **AWS AppConfig:** <br>&emsp;&emsp; - Tạo ứng dụng và môi trường AppConfig <br>&emsp;&emsp; - Cấu hình configuration profiles và versions <br>&emsp;&emsp; - Triển khai feature flags cho rollout dần dần <br>&emsp;&emsp; - Thiết lập chiến lược triển khai (linear, exponential) <br>&emsp;&emsp; - Cấu hình validators cho validation cấu hình <br>&emsp;&emsp; - Triển khai cơ chế rollback <br>&emsp;&emsp; - Giám sát tiến trình và sức khỏe triển khai <br>&emsp; + **Systems Manager Session Manager:** <br>&emsp;&emsp; - Cấu hình điều kiện tiên quyết Session Manager <br>&emsp;&emsp; - Thiết lập truy cập instance an toàn không cần SSH keys <br>&emsp;&emsp; - Triển khai session logging tới S3 và CloudWatch <br>&emsp;&emsp; - Cấu hình tùy chọn session và timeout settings <br>&emsp;&emsp; - Thiết lập port forwarding cho ứng dụng <br>&emsp;&emsp; - Triển khai tùy chỉnh session document <br>&emsp;&emsp; - Giám sát và kiểm tra hoạt động session | 27/10/2025 | 27/10/2025 | [AWS Chatbot](https://000138.awsstudygroup.com/) <br> <br> [AWS AppConfig](https://000139.awsstudygroup.com/) <br> <br> [Systems Manager <br> Session Manager](https://000140.awsstudygroup.com/) |
| 3   | - Học Amazon Athena cho truy vấn SQL serverless <br> - Thành thạo AWS Data Pipeline cho điều phối data workflow <br> - Hiểu AWS Batch cho batch computing workloads <br> - **Thực hành:** <br>&emsp; + **Amazon Athena:** <br>&emsp;&emsp; - Cấu hình Athena workgroups và query settings <br>&emsp;&emsp; - Tạo databases và tables từ dữ liệu S3 <br>&emsp;&emsp; - Viết và tối ưu hóa SQL queries cho dữ liệu S3 <br>&emsp;&emsp; - Triển khai phân vùng cho hiệu suất query <br>&emsp;&emsp; - Thiết lập data catalogs với AWS Glue <br>&emsp;&emsp; - Cấu hình vị trí kết quả query và mã hóa <br>&emsp;&emsp; - Sử dụng prepared statements cho parameterized queries <br>&emsp;&emsp; - Giám sát thực thi query và chi phí <br>&emsp; + **AWS Data Pipeline:** <br>&emsp;&emsp; - Thiết kế và tạo định nghĩa data pipeline <br>&emsp;&emsp; - Cấu hình hoạt động và lịch trình pipeline <br>&emsp;&emsp; - Thiết lập data nodes cho nguồn và đích <br>&emsp;&emsp; - Triển khai preconditions và dependencies <br>&emsp;&emsp; - Cấu hình tài nguyên và compute pipeline <br>&emsp;&emsp; - Thiết lập xử lý lỗi và thử lại <br>&emsp;&emsp; - Giám sát thực thi và logs pipeline <br>&emsp;&emsp; - Triển khai workflows chuyển đổi dữ liệu <br>&emsp; + **AWS Batch:** <br>&emsp;&emsp; - Tạo batch compute environments <br>&emsp;&emsp; - Cấu hình job queues và priorities <br>&emsp;&emsp; - Định nghĩa job definitions với container images <br>&emsp;&emsp; - Submit và quản lý batch jobs <br>&emsp;&emsp; - Thiết lập job dependencies và scheduling <br>&emsp;&emsp; - Cấu hình yêu cầu và ràng buộc tài nguyên <br>&emsp;&emsp; - Triển khai giám sát và logging jobs <br>&emsp;&emsp; - Tối ưu chi phí xử lý batch | 28/10/2025 | 28/10/2025 | [Amazon Athena](https://000066.awsstudygroup.com/) <br> <br> [AWS Data Pipeline](https://000117.awsstudygroup.com/) <br> <br> [AWS Batch](https://000112.awsstudygroup.com/) |

### Kết quả đạt được tuần 8:

* **Thành thạo AWS Chatbot DevOps Notifications:**
  * Thành thạo khái niệm AWS Chatbot và tích hợp kênh
  * Thành công cấu hình Slack workspace và channels
  * Tích hợp Microsoft Teams cho thông báo DevOps
  * Thiết lập định tuyến CloudWatch alarm tới chat channels
  * Cấu hình đăng ký SNS topic cho thông báo sự kiện
  * Triển khai phân phối Security Hub findings tới teams
  * Định tuyến cảnh báo bảo mật GuardDuty tới chat channels
  * Áp dụng lọc thông báo cho cảnh báo phù hợp
  * Giám sát metrics phân phối và tương tác chatbot
  * Áp dụng best practices cho cộng tác DevOps

* **Thành thạo AWS AppConfig Configuration Management:**
  * Thành thạo khái niệm AppConfig cho cấu hình động
  * Thành công tạo ứng dụng và môi trường
  * Cấu hình configuration profiles với versioning
  * Triển khai feature flags cho rollout có kiểm soát
  * Thiết lập chiến lược triển khai (linear, canary, exponential)
  * Cấu hình validators cho validation cấu hình
  * Triển khai rollback tự động khi triển khai thất bại
  * Giám sát sức khỏe và tiến trình triển khai
  * Áp dụng best practices cho thay đổi cấu hình an toàn

* **Thành thạo Systems Manager Session Manager Security:**
  * Thành thạo khái niệm Session Manager cho truy cập an toàn
  * Thành công cấu hình truy cập instance không cần bastion
  * Loại bỏ nhu cầu SSH keys và mở cổng inbound
  * Triển khai session logging tới S3 và CloudWatch Logs
  * Cấu hình tùy chọn session và chính sách timeout
  * Thiết lập port forwarding cho truy cập ứng dụng an toàn
  * Tạo custom session documents cho vận hành
  * Giám sát và kiểm tra tất cả hoạt động session
  * Áp dụng best practices cho truy cập vận hành an toàn

* **Thành thạo Amazon Athena Serverless Query:**
  * Thành thạo khái niệm Athena cho phân tích SQL serverless
  * Thành công cấu hình Athena workgroups và query settings
  * Tạo databases và tables từ nguồn dữ liệu S3
  * Viết và tối ưu hóa SQL queries cho datasets lớn
  * Triển khai chiến lược phân vùng cho hiệu suất query
  * Tích hợp Athena với AWS Glue Data Catalog
  * Cấu hình vị trí kết quả query với mã hóa
  * Sử dụng prepared statements cho parameterized queries an toàn
  * Giám sát thời gian thực thi query và dữ liệu được quét
  * Áp dụng best practices cho tối ưu chi phí

* **Thành thạo AWS Data Pipeline Orchestration:**
  * Thành thạo khái niệm Data Pipeline cho tự động hóa workflow
  * Thành công thiết kế và tạo định nghĩa pipeline
  * Cấu hình hoạt động và lịch trình thực thi pipeline
  * Thiết lập data nodes cho nhiều nguồn và đích
  * Triển khai preconditions và dependencies hoạt động
  * Cấu hình tài nguyên và môi trường compute pipeline
  * Thiết lập xử lý lỗi và retry logic toàn diện
  * Giám sát trạng thái thực thi và logs pipeline
  * Triển khai workflows chuyển đổi dữ liệu phức tạp
  * Áp dụng best practices cho data pipelines đáng tin cậy

* **Thành thạo AWS Batch Computing:**
  * Thành thạo khái niệm AWS Batch cho batch workloads
  * Thành công tạo managed và unmanaged compute environments
  * Cấu hình job queues với priorities phù hợp
  * Định nghĩa job definitions với Docker container images
  * Submit và quản lý batch jobs theo chương trình
  * Thiết lập job dependencies và array jobs
  * Cấu hình yêu cầu tài nguyên (vCPU, memory, GPU)
  * Triển khai giám sát và logging jobs toàn diện
  * Tối ưu chi phí xử lý batch với Spot instances
  * Áp dụng best practices cho batch computing có thể mở rộng


