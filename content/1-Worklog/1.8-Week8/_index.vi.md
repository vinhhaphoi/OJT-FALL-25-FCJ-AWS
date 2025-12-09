---
title: "Worklog Tuần 8"
date: "2025-10-27"
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

- **Thành thạo AWS Chatbot cho Thông báo:**

  - Hiểu khái niệm AWS Chatbot và tích hợp
  - Cấu hình kênh Slack và Microsoft Teams
  - Thiết lập CloudWatch alarms và thông báo
  - Triển khai định tuyến và lọc sự kiện
  - Giám sát hoạt động và sử dụng chat

- **Tìm hiểu về Configuration Management:**

  - Hiểu khái niệm AppConfig và triển khai
  - Cấu hình ứng dụng và môi trường
  - Triển khai feature flags và configuration profiles
  - Thiết lập chiến lược triển khai và validators
  - Giám sát triển khai cấu hình

- **Thành thạo AWS Systems Manager Session Manager:**
  - Hiểu khái niệm Session Manager và bảo mật
  - Cấu hình truy cập instance an toàn
  - Triển khai session logging và auditing
  - Thiết lập tùy chọn và cài đặt session
  - Giám sát hoạt động session

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Ngày bắt đầu | Ngày hoàn thành | Tài liệu                                                                                                                                                                                                                                                                                                                                                                     |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2   | - Tìm hiểu về AWS Chatbot cho thông báo DevOps <br> - Thành thạo AWS AppConfig cho quản lý cấu hình <br> - Hiểu AWS Systems Manager Session Manager <br> - **Thực hành:** <br>&emsp; + **AWS Chatbot:** <br>&emsp;&emsp; - Cấu hình tích hợp Slack workspace <br>&emsp;&emsp; - Thiết lập tích hợp Microsoft Teams channel <br>&emsp;&emsp; - Cấu hình thông báo CloudWatch alarm <br>&emsp;&emsp; - Triển khai đăng ký SNS topic <br>&emsp;&emsp; - Thiết lập thông báo Security Hub findings <br>&emsp;&emsp; - Cấu hình định tuyến cảnh báo GuardDuty <br>&emsp;&emsp; - Triển khai lọc và tùy chỉnh thông báo <br>&emsp;&emsp; - Giám sát metrics phân phối chatbot <br>&emsp; + **AWS AppConfig:** <br>&emsp;&emsp; - Tạo ứng dụng và môi trường AppConfig <br>&emsp;&emsp; - Cấu hình configuration profiles và versions <br>&emsp;&emsp; - Triển khai feature flags cho rollout dần dần <br>&emsp;&emsp; - Thiết lập chiến lược triển khai (linear, exponential) <br>&emsp;&emsp; - Cấu hình validators cho validation cấu hình <br>&emsp;&emsp; - Triển khai cơ chế rollback <br>&emsp;&emsp; - Giám sát tiến trình và sức khỏe triển khai <br>&emsp; + **Systems Manager Session Manager:** <br>&emsp;&emsp; - Cấu hình điều kiện tiên quyết Session Manager <br>&emsp;&emsp; - Thiết lập truy cập instance an toàn không cần SSH keys <br>&emsp;&emsp; - Triển khai session logging tới S3 và CloudWatch <br>&emsp;&emsp; - Cấu hình tùy chọn session và timeout settings <br>&emsp;&emsp; - Thiết lập port forwarding cho ứng dụng <br>&emsp;&emsp; - Triển khai tùy chỉnh session document <br>&emsp;&emsp; - Giám sát và kiểm tra hoạt động session                                                                              | 27/10/2025   | 27/10/2025      | [AWS Chatbot Thông báo DevOps <br> Cấu hình tích hợp Slack và Teams](https://000138.awsstudygroup.com/) <br> <br> [AWS AppConfig Quản lý Cấu hình <br> Tạo ứng dụng và môi trường](https://000139.awsstudygroup.com/) <br> <br> [Systems Manager Session Manager Truy cập An toàn <br> Cấu hình truy cập instance an toàn không SSH keys](https://000140.awsstudygroup.com/) |
| 3   | - Tìm hiểu về Amazon Athena cho truy vấn SQL serverless <br> - Thành thạo AWS Data Pipeline cho điều phối data workflow <br> - Hiểu AWS Batch cho batch computing workloads <br> - **Thực hành:** <br>&emsp; + **Amazon Athena:** <br>&emsp;&emsp; - Cấu hình Athena workgroups và query settings <br>&emsp;&emsp; - Tạo databases và tables từ dữ liệu S3 <br>&emsp;&emsp; - Viết và tối ưu hóa SQL queries cho dữ liệu S3 <br>&emsp;&emsp; - Triển khai phân vùng cho hiệu suất query <br>&emsp;&emsp; - Thiết lập data catalogs với AWS Glue <br>&emsp;&emsp; - Cấu hình vị trí kết quả query và mã hóa <br>&emsp;&emsp; - Sử dụng prepared statements cho parameterized queries <br>&emsp;&emsp; - Giám sát thực thi query và chi phí <br>&emsp; + **AWS Data Pipeline:** <br>&emsp;&emsp; - Thiết kế và tạo định nghĩa data pipeline <br>&emsp;&emsp; - Cấu hình hoạt động và lịch trình pipeline <br>&emsp;&emsp; - Thiết lập data nodes cho nguồn và đích <br>&emsp;&emsp; - Triển khai preconditions và dependencies <br>&emsp;&emsp; - Cấu hình tài nguyên và compute pipeline <br>&emsp;&emsp; - Thiết lập xử lý lỗi và thử lại <br>&emsp;&emsp; - Giám sát thực thi và logs pipeline <br>&emsp;&emsp; - Triển khai workflows chuyển đổi dữ liệu <br>&emsp; + **AWS Batch:** <br>&emsp;&emsp; - Tạo batch compute environments <br>&emsp;&emsp; - Cấu hình job queues và priorities <br>&emsp;&emsp; - Định nghĩa job definitions với container images <br>&emsp;&emsp; - Submit và quản lý batch jobs <br>&emsp;&emsp; - Thiết lập job dependencies và scheduling <br>&emsp;&emsp; - Cấu hình yêu cầu và ràng buộc tài nguyên <br>&emsp;&emsp; - Triển khai giám sát và logging jobs <br>&emsp;&emsp; - Tối ưu chi phí xử lý batch | 28/10/2025   | 28/10/2025      | [Amazon Athena Truy vấn SQL Serverless <br> Cấu hình workgroups](https://000066.awsstudygroup.com/) <br> <br> [AWS Data Pipeline Điều phối Workflow <br> Thiết kế pipeline definitions](https://000117.awsstudygroup.com/) <br> <br> [AWS Batch Workloads Tính toán <br> Tạo compute environments](https://000112.awsstudygroup.com/)                                        |
| 4   | - Tìm hiểu về AWS Step Functions cho điều phối workflow <br> - Chuyên sâu Amazon Rekognition cho phân tích hình ảnh và video <br> - Hiểu Amazon Transcribe cho chuyển đổi giọng nói sang văn bản <br> - **Thực hành:** <br>&emsp; + **AWS Step Functions:** <br>&emsp;&emsp; - Tạo state machines với định nghĩa JSON <br>&emsp;&emsp; - Cấu hình task states và tích hợp Lambda <br>&emsp;&emsp; - Triển khai parallel và choice states <br>&emsp;&emsp; - Thiết lập xử lý lỗi và retry logic <br>&emsp;&emsp; - Cấu hình wait states và timeouts <br>&emsp;&emsp; - Triển khai callback patterns <br>&emsp;&emsp; - Giám sát executions và state transitions <br>&emsp;&emsp; - Sử dụng Express và Standard workflows <br>&emsp; + **Amazon Rekognition:** <br>&emsp;&emsp; - Phát hiện labels và objects trong hình ảnh <br>&emsp;&emsp; - Thực hiện phân tích khuôn mặt và nhận diện <br>&emsp;&emsp; - Phát hiện text trong hình ảnh (OCR) <br>&emsp;&emsp; - Phân tích nội dung video và hoạt động <br>&emsp;&emsp; - Tạo face collections và tìm kiếm <br>&emsp;&emsp; - Phát hiện nội dung không an toàn <br>&emsp;&emsp; - Triển khai nhận diện người nổi tiếng <br>&emsp;&emsp; - Giám sát API usage và chi phí <br>&emsp; + **Amazon Transcribe:** <br>&emsp;&emsp; - Chuyển đổi file âm thanh sang văn bản <br>&emsp;&emsp; - Cấu hình real-time streaming transcription <br>&emsp;&emsp; - Triển khai custom vocabularies <br>&emsp;&emsp; - Thiết lập speaker identification <br>&emsp;&emsp; - Cấu hình language identification <br>&emsp;&emsp; - Triển khai redaction cho dữ liệu nhạy cảm <br>&emsp;&emsp; - Sử dụng custom language models <br>&emsp;&emsp; - Giám sát transcription jobs                                  | 10/29/2025   | 10/29/2025      | [AWS Step Functions Điều phối Workflow <br> Tạo state machines](https://000113.awsstudygroup.com/) <br> <br> [Amazon Rekognition Phân tích Hình ảnh và Video <br> Phát hiện labels và objects](https://000021.awsstudygroup.com/) <br> <br> [Amazon Transcribe Chuyển đổi Speech-to-Text <br> Transcribe audio](https://000091.awsstudygroup.com/)                           |
| 5   | - Tìm hiểu về Amazon Lightsail Containers để triển khai container đơn giản <br> - Chuyên sâu các nguyên tắc cơ bản của Docker containerization <br> - Hiểu kiến trúc monolithic sang microservices với ECS và AWS Fargate <br> - **Thực hành:** <br>&emsp; + **Amazon Lightsail Containers:** <br>&emsp;&emsp; - Hiểu các khái niệm và lợi ích của Lightsail Containers <br>&emsp;&emsp; - Tạo Lightsail container services <br>&emsp;&emsp; - Triển khai Docker images công khai từ DockerHub <br>&emsp;&emsp; - Xây dựng và triển khai Docker images tùy chỉnh <br>&emsp;&emsp; - Cấu hình dung lượng và scaling cho container service <br>&emsp;&emsp; - Thiết lập custom domains và HTTPS <br>&emsp;&emsp; - Giám sát triển khai container và logs <br>&emsp;&emsp; - Quản lý phiên bản container và rollback <br>&emsp; + **Chuyển đổi Monolithic sang Microservices với Docker và ECS:** <br>&emsp;&emsp; - Hiểu Docker containers và containerization <br>&emsp;&emsp; - Tìm hiểu về kiến trúc ECS (Elastic Container Service) <br>&emsp;&emsp; - Chuyên sâu AWS Fargate cho serverless containers <br>&emsp;&emsp; - Chuyển đổi ứng dụng monolithic sang microservices <br>&emsp;&emsp; - Tạo ECS clusters và task definitions <br>&emsp;&emsp; - Triển khai ứng dụng container hóa trên Fargate <br>&emsp;&emsp; - Cấu hình service discovery và load balancing <br>&emsp;&emsp; - Triển khai CI/CD pipelines cho containers <br>&emsp;&emsp; - Giám sát ứng dụng container hóa với CloudWatch <br>&emsp;&emsp; - Thực hành hiệu quả về kiến trúc microservices                                                                                                                                                                      | 10/30/2025   | 10/30/2025      | [Amazon Lightsail Container <br> Chạy ứng dụng trên Lightsail](https://000046.awsstudygroup.com/) <br> <br> [Chuyển đổi Monolithic sang Microservices <br> Docker, ECS và Fargate](https://000067.awsstudygroup.com/)                                                                                                                                                        |
| 6   | - Tìm hiểu về AWS CDK (Cloud Development Kit) cho infrastructure as code <br> - Chuyên sâu triển khai ứng dụng Spring Boot trên ECS Fargate <br> - Hiểu AWS CDK TypeScript cho provisioning infrastructure <br> - **Thực hành:** <br>&emsp; + **Thiết lập AWS CDK Infrastructure:** <br>&emsp;&emsp; - Hiểu các khái niệm và lợi ích của AWS CDK <br>&emsp;&emsp; - Cài đặt và cấu hình AWS CDK CLI <br>&emsp;&emsp; - Khởi tạo ứng dụng CDK với TypeScript <br>&emsp;&emsp; - Định nghĩa CDK stacks và constructs <br>&emsp;&emsp; - Cấu hình VPC và networking với CDK <br>&emsp;&emsp; - Thiết lập security groups và IAM roles <br>&emsp;&emsp; - Triển khai infrastructure sử dụng CDK deploy <br>&emsp;&emsp; - Quản lý vòng đời ứng dụng CDK <br>&emsp; + **Spring Boot trên ECS Fargate với CDK:** <br>&emsp;&emsp; - Xây dựng Spring Boot application Docker images <br>&emsp;&emsp; - Push images tới Amazon ECR (Elastic Container Registry) <br>&emsp;&emsp; - Tạo ECS Fargate cluster với CDK <br>&emsp;&emsp; - Định nghĩa ECS task definitions và services <br>&emsp;&emsp; - Cấu hình Application Load Balancer <br>&emsp;&emsp; - Thiết lập auto-scaling policies <br>&emsp;&emsp; - Triển khai health checks và monitoring <br>&emsp;&emsp; - Cấu hình CloudWatch logs cho containers <br>&emsp;&emsp; - Triển khai và test Spring Boot services <br>&emsp;&emsp; - Thực hành hiệu quả về production deployments                                                                                                                                                                                                                                                                                                            | 10/31/2025   | 10/31/2025      | [Spring Boot trên ECS Fargate <br> Triển khai sử dụng AWS CDK](https://000118.awsstudygroup.com/)                                                                                                                                                                                                                                                                            |

### Kết quả đạt được tuần 8:

- **Thành thạo AWS Chatbot DevOps Notifications:**

  - Thành thạo khái niệm AWS Chatbot và tích hợp kênh
  - Thành công cấu hình Slack workspace và channels
  - Tích hợp Microsoft Teams cho thông báo DevOps
  - Thiết lập định tuyến CloudWatch alarm tới chat channels
  - Cấu hình đăng ký SNS topic cho thông báo sự kiện
  - Triển khai phân phối Security Hub findings tới teams
  - Định tuyến cảnh báo bảo mật GuardDuty tới chat channels
  - Áp dụng lọc thông báo cho cảnh báo phù hợp
  - Giám sát metrics phân phối và tương tác chatbot
  - Thực hành hiệu quả về cộng tác DevOps

- **Thành thạo AWS AppConfig Configuration Management:**

  - Thành thạo khái niệm AppConfig cho cấu hình động
  - Thành công tạo ứng dụng và môi trường
  - Cấu hình configuration profiles với versioning
  - Triển khai feature flags cho rollout có kiểm soát
  - Thiết lập chiến lược triển khai (linear, canary, exponential)
  - Cấu hình validators cho validation cấu hình
  - Triển khai rollback tự động khi triển khai thất bại
  - Giám sát sức khỏe và tiến trình triển khai
  - Thực hành hiệu quả về thay đổi cấu hình an toàn

- **Thành thạo Systems Manager Session Manager Security:**

  - Thành thạo khái niệm Session Manager cho truy cập an toàn
  - Thành công cấu hình truy cập instance không cần bastion
  - Loại bỏ nhu cầu SSH keys và mở cổng inbound
  - Triển khai session logging tới S3 và CloudWatch Logs
  - Cấu hình tùy chọn session và chính sách timeout
  - Thiết lập port forwarding cho truy cập ứng dụng an toàn
  - Tạo custom session documents cho vận hành
  - Giám sát và kiểm tra tất cả hoạt động session
  - Thực hành hiệu quả về truy cập vận hành an toàn

- **Thành thạo Amazon Athena Serverless Query:**

  - Thành thạo khái niệm Athena cho phân tích SQL serverless
  - Thành công cấu hình Athena workgroups và query settings
  - Tạo databases và tables từ nguồn dữ liệu S3
  - Viết và tối ưu hóa SQL queries cho datasets lớn
  - Triển khai chiến lược phân vùng cho hiệu suất query
  - Tích hợp Athena với AWS Glue Data Catalog
  - Cấu hình vị trí kết quả query với mã hóa
  - Sử dụng prepared statements cho parameterized queries an toàn
  - Giám sát thời gian thực thi query và dữ liệu được quét
  - Thực hành hiệu quả về tối ưu chi phí

- **Thành thạo AWS Data Pipeline Orchestration:**

  - Thành thạo khái niệm Data Pipeline cho tự động hóa workflow
  - Thành công thiết kế và tạo định nghĩa pipeline
  - Cấu hình hoạt động và lịch trình thực thi pipeline
  - Thiết lập data nodes cho nhiều nguồn và đích
  - Triển khai preconditions và dependencies hoạt động
  - Cấu hình tài nguyên và môi trường compute pipeline
  - Thiết lập xử lý lỗi và retry logic toàn diện
  - Giám sát trạng thái thực thi và logs pipeline
  - Triển khai workflows chuyển đổi dữ liệu phức tạp
  - Thực hành hiệu quả về data pipelines đáng tin cậy

- **Thành thạo AWS Batch Computing:**

  - Thành thạo khái niệm AWS Batch cho batch workloads
  - Thành công tạo managed và unmanaged compute environments
  - Cấu hình job queues với priorities phù hợp
  - Định nghĩa job definitions với Docker container images
  - Submit và quản lý batch jobs theo chương trình
  - Thiết lập job dependencies và array jobs
  - Cấu hình yêu cầu tài nguyên (vCPU, memory, GPU)
  - Triển khai giám sát và logging jobs toàn diện
  - Tối ưu chi phí xử lý batch với Spot instances
  - Thực hành hiệu quả về batch computing có thể mở rộng

- **Thành thạo AWS Step Functions Workflow Orchestration:**

  - Thành thạo khái niệm Step Functions cho serverless workflows
  - Thành công tạo state machines với định nghĩa JSON
  - Cấu hình task states với Lambda và AWS service integrations
  - Triển khai parallel states cho concurrent execution
  - Thiết lập choice states cho conditional branching
  - Cấu hình xử lý lỗi với Catch và Retry
  - Triển khai wait states và timeouts cho delays
  - Sử dụng callback patterns cho external processes
  - Giám sát workflow executions và state transitions
  - Thực hành hiệu quả về thiết kế workflow

- **Thành thạo Amazon Rekognition Computer Vision:**

  - Thành thạo khái niệm Rekognition cho phân tích image và video
  - Thành công phát hiện labels và objects trong images
  - Thực hiện phân tích facial bao gồm age và emotion detection
  - Triển khai facial recognition với face collections
  - Phát hiện và trích xuất text từ images (OCR)
  - Phân tích nội dung video cho activities và objects
  - Cấu hình content moderation cho unsafe content
  - Triển khai tính năng celebrity recognition
  - Giám sát API usage và chiến lược optimization
  - Thực hành hiệu quả về ML-powered vision

- **Thành thạo Amazon Transcribe Speech-to-Text:**

  - Thành thạo khái niệm Transcribe cho audio transcription
  - Thành công transcribe audio files thành text
  - Cấu hình real-time streaming transcription
  - Triển khai custom vocabularies cho accuracy
  - Thiết lập speaker identification (diarization)
  - Cấu hình automatic language identification
  - Triển khai content redaction cho PII
  - Sử dụng custom language models cho domain-specific terms
  - Giám sát transcription job performance
  - Thực hành hiệu quả về speech recognition

- **Thành thạo Triển khai Amazon Lightsail Containers:**

  - Thành thạo các khái niệm Lightsail Containers cho triển khai đơn giản hóa
  - Thành công tạo Lightsail container services
  - Triển khai Docker images công khai từ DockerHub registry
  - Xây dựng và triển khai ứng dụng container hóa tùy chỉnh
  - Cấu hình dung lượng container và horizontal scaling
  - Thiết lập custom domain names với HTTPS certificates
  - Giám sát sức khỏe container và application logs
  - Quản lý phiên bản triển khai và rollback strategies
  - Thực hành hiệu quả về container workloads đơn giản

- **Chuyên gia Kiến trúc Microservices với Docker và ECS:**

  - Thành thạo nguyên tắc cơ bản Docker containerization
  - Thành công chuyển đổi ứng dụng monolithic sang microservices
  - Cấu hình Amazon ECS clusters và services
  - Triển khai ứng dụng container hóa trên AWS Fargate
  - Triển khai service discovery với AWS Cloud Map
  - Thiết lập Application Load Balancer cho microservices
  - Cấu hình CI/CD pipelines cho automated deployments
  - Giám sát container metrics với CloudWatch
  - Thực hành hiệu quả về kiến trúc cloud-native

- **Thành thạo AWS CDK Infrastructure as Code:**

  - Thành thạo các khái niệm AWS CDK và phát triển TypeScript
  - Thành công cài đặt và cấu hình AWS CDK CLI
  - Khởi tạo và cấu trúc các ứng dụng CDK
  - Định nghĩa CDK stacks và constructs có thể tái sử dụng
  - Cấu hình VPC, networking và security với CDK
  - Thiết lập IAM roles và security groups theo lập trình
  - Triển khai infrastructure sử dụng CDK deploy và diff
  - Quản lý vòng đời và cập nhật ứng dụng CDK
  - Thực hành hiệu quả về infrastructure as code

- **Chuyên gia Triển khai Spring Boot trên ECS Fargate:**
  - Thành thạo xây dựng Spring Boot Docker images
  - Thành công push images tới Amazon ECR
  - Tạo ECS Fargate clusters với AWS CDK
  - Định nghĩa ECS task definitions và service configurations
  - Cấu hình Application Load Balancer cho services
  - Triển khai auto-scaling policies cho containers
  - Thiết lập health checks và CloudWatch monitoring
  - Cấu hình structured logging cho containerized apps
  - Triển khai và kiểm thử Spring Boot services production-grade
  - Thực hành hiệu quả về Java microservices trên AWS
