---
title: "Worklog Tuần 5"
date: "2025-09-09"
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

- **Thành thạo AWS Lambda Serverless Computing:**

  - Hiểu các khái niệm Lambda và kiến trúc serverless
  - Tạo và triển khai các hàm Lambda với các runtime khác nhau
  - Cấu hình triggers và nguồn sự kiện
  - Quản lý phiên bản và bí danh hàm
  - Triển khai đồng thời và mở rộng quy mô hàm

- **Học Amazon API Gateway cho RESTful APIs:**

  - Hiểu khái niệm và tính năng API Gateway
  - Tạo và triển khai REST APIs
  - Cấu hình phương thức API và tích hợp
  - Triển khai bảo mật API và kiểm soát truy cập
  - Giám sát hiệu suất và sử dụng API

- **Học Amazon DynamoDB NoSQL Database:**

  - Hiểu khái niệm DynamoDB và mô hình dữ liệu
  - Tạo và quản lý bảng với phân vùng phù hợp
  - Triển khai các hoạt động CRUD với SDK
  - Cấu hình chế độ dung lượng đọc/ghi
  - Sử dụng DynamoDB Streams để nắm bắt thay đổi dữ liệu

- **Thành thạo Amazon SNS/SQS Messaging Services:**

  - Hiểu mô hình nhắn tin và trường hợp sử dụng
  - Tạo chủ đề và hàng đợi để gửi tin nhắn
  - Triển khai pub/sub với SNS
  - Cấu hình message queuing với SQS
  - Xử lý lọc tin nhắn và hàng đợi dead-letter

- **Học AWS Config cho Resource Management:**

  - Hiểu AWS Config rules và evaluations
  - Giám sát thay đổi cấu hình tài nguyên
  - Triển khai kiểm tra tuân thủ
  - Cấu hình khắc phục tự động
  - Theo dõi mối quan hệ tài nguyên

- **Thành thạo AWS WAF cho Web Application Security:**

  - Hiểu khái niệm WAF và web ACLs
  - Triển khai rules và conditions bảo mật
  - Cấu hình rate-based rules
  - Bảo vệ ứng dụng khỏi các lỗi phổ biến
  - Giám sát sự kiện bảo mật

- **Học Application Load Balancer:**
  - Hiểu khái niệm và tính năng ALB
  - Cấu hình listener rules và target groups
  - Triển khai path-based routing
  - Thiết lập SSL/TLS termination
  - Giám sát metrics load balancer

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Ngày bắt đầu | Ngày hoàn thành | Tài liệu                                                                                                                                                                                                                                                                                                                                                                                 |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2   | - Học AWS Lambda serverless computing <br> - Thành thạo Amazon API Gateway cho REST APIs <br> - Hiểu Amazon DynamoDB NoSQL database <br> - Học AWS messaging với SNS/SQS <br> - **Thực hành:** <br>&emsp; + **AWS Lambda:** <br>&emsp;&emsp; - Tạo hàm Lambda với nhiều ngôn ngữ <br>&emsp;&emsp; - Cấu hình trigger và quyền hàm <br>&emsp;&emsp; - Triển khai xử lý lỗi và thử lại <br>&emsp;&emsp; - Thiết lập giám sát và ghi log hàm <br>&emsp;&emsp; - Sử dụng biến môi trường và layers <br>&emsp; + **Amazon API Gateway:** <br>&emsp;&emsp; - Tạo REST APIs với tài nguyên và phương thức <br>&emsp;&emsp; - Cấu hình tích hợp Lambda <br>&emsp;&emsp; - Triển khai xác thực API <br>&emsp;&emsp; - Thiết lập ánh xạ request/response <br>&emsp;&emsp; - Triển khai API tới các giai đoạn khác nhau <br>&emsp; + **Amazon DynamoDB:** <br>&emsp;&emsp; - Tạo bảng với schema khóa phù hợp <br>&emsp;&emsp; - Thực hiện các hoạt động CRUD qua SDK <br>&emsp;&emsp; - Triển khai chỉ mục phụ <br>&emsp;&emsp; - Cấu hình tự động mở rộng <br>&emsp;&emsp; - Sử dụng DynamoDB Streams <br>&emsp; + **SNS/SQS Messaging:** <br>&emsp;&emsp; - Tạo chủ đề SNS và đăng ký <br>&emsp;&emsp; - Thiết lập hàng đợi SQS với cấu hình phù hợp <br>&emsp;&emsp; - Triển khai lọc tin nhắn <br>&emsp;&emsp; - Xử lý xử lý tin nhắn <br>&emsp;&emsp; - Giám sát số liệu hàng đợi | 06/10/2025   | 06/10/2025      | [AWS Lambda Hàm Serverless <br> Tạo hàm đa ngôn ngữ](https://000096.awsstudygroup.com/) <br> <br> [Amazon API Gateway REST APIs <br> Xây dựng APIs](https://000097.awsstudygroup.com/) <br> <br> [Amazon DynamoDB NoSQL Database <br> Tạo bảng](https://000098.awsstudygroup.com/) <br> <br> [AWS SNS/SQS Dịch vụ Nhắn tin <br> Tạo topics và queues](https://000099.awsstudygroup.com/) |
| 3   | - Học AWS CloudWatch cho giám sát và quan sát <br> - Thành thạo AWS IAM Roles và Bảo mật <br> - Hiểu Amazon VPC networking <br> - **Thực hành:** <br>&emsp; + **AWS CloudWatch:** <br>&emsp;&emsp; - Thiết lập CloudWatch metrics và dashboards <br>&emsp;&emsp; - Cấu hình cảnh báo và thông báo <br>&emsp;&emsp; - Triển khai custom metrics và dimensions <br>&emsp;&emsp; - Sử dụng CloudWatch Logs cho tập hợp logs <br>&emsp;&emsp; - Tạo metric filters và insights <br>&emsp; + **AWS IAM Roles:** <br>&emsp;&emsp; - Tạo và cấu hình IAM roles <br>&emsp;&emsp; - Thiết lập service-linked roles <br>&emsp;&emsp; - Triển khai truy cập cross-account <br>&emsp;&emsp; - Cấu hình role trust relationships <br>&emsp;&emsp; - Sử dụng role assumption policies <br>&emsp; + **Amazon VPC:** <br>&emsp;&emsp; - Thiết kế kiến trúc VPC và subnets <br>&emsp;&emsp; - Cấu hình route tables và gateways <br>&emsp;&emsp; - Triển khai security groups và NACLs <br>&emsp;&emsp; - Thiết lập kết nối VPC peering <br>&emsp;&emsp; - Sử dụng VPC endpoints cho truy cập service                                                                                                                                                                                                                                                                                         | 07/10/2025   | 07/10/2025      | [AWS CloudWatch Nền tảng Giám sát <br> Cấu hình metrics và dashboards](https://000141.awsstudygroup.com/) <br> <br> [AWS IAM Roles Bảo mật <br> Tạo roles](https://000069.awsstudygroup.com/) <br> <br> [Amazon VPC Kiến trúc Mạng <br> Thiết kế subnets](https://000013.awsstudygroup.com/)                                                                                             |
| 4   | - Học Amazon EBS cho quản lý block storage <br> - Thành thạo Amazon EFS cho hệ thống tập tin có thể mở rộng <br> - Hiểu AWS KMS cho quản lý khóa mã hóa <br> - **Thực hành:** <br>&emsp; + **Amazon EBS Storage:** <br>&emsp;&emsp; - Tạo và gắn EBS volumes <br>&emsp;&emsp; - Cấu hình loại volume và IOPS <br>&emsp;&emsp; - Triển khai EBS snapshots và backups <br>&emsp;&emsp; - Thiết lập vòng đời snapshot tự động <br>&emsp;&emsp; - Giám sát metrics hiệu suất EBS <br>&emsp; + **Amazon EFS File System:** <br>&emsp;&emsp; - Tạo và cấu hình hệ thống tập tin EFS <br>&emsp;&emsp; - Thiết lập mount targets và security groups <br>&emsp;&emsp; - Triển khai EFS access points <br>&emsp;&emsp; - Cấu hình chế độ hiệu suất và throughput <br>&emsp;&emsp; - Sử dụng quản lý vòng đời EFS <br>&emsp; + **AWS KMS Security:** <br>&emsp;&emsp; - Tạo và quản lý khóa KMS <br>&emsp;&emsp; - Thiết lập chính sách và cấp quyền khóa <br>&emsp;&emsp; - Triển khai luân chuyển khóa <br>&emsp;&emsp; - Cấu hình truy cập khóa xuyên tài khoản <br>&emsp;&emsp; - Giám sát sử dụng API KMS                                                                                                                                                                                                                                                                          | 08/10/2025   | 08/10/2025      | [Amazon EBS Block Storage <br> Tạo và gắn volumes](https://000019.awsstudygroup.com/) <br> <br> [Amazon EFS Hệ thống File Elastic <br> Tạo file systems](https://000020.awsstudygroup.com/) <br> <br> [AWS KMS Quản lý Khóa <br> Tạo và quản lý keys](https://000077.awsstudygroup.com/)                                                                                                 |
| 5   | - Học Amazon S3 object storage cơ bản <br> - Thành thạo S3 security và access control <br> - Hiểu S3 performance optimization <br> - **Thực hành:** <br>&emsp; + **Amazon S3 Storage:** <br>&emsp;&emsp; - Tạo và cấu hình S3 buckets <br>&emsp;&emsp; - Thiết lập bucket policies và IAM permissions <br>&emsp;&emsp; - Triển khai versioning và lifecycle rules <br>&emsp;&emsp; - Cấu hình S3 encryption options <br>&emsp;&emsp; - Giám sát S3 access và usage <br>&emsp; + **S3 Security Management:** <br>&emsp;&emsp; - Cấu hình bucket và object ACLs <br>&emsp;&emsp; - Triển khai CORS và bucket policies <br>&emsp;&emsp; - Thiết lập S3 Block Public Access <br>&emsp;&emsp; - Sử dụng presigned URLs và cookies <br>&emsp;&emsp; - Giám sát S3 security settings <br>&emsp; + **S3 Performance:** <br>&emsp;&emsp; - Tối ưu S3 performance với prefixes <br>&emsp;&emsp; - Triển khai S3 Transfer Acceleration <br>&emsp;&emsp; - Cấu hình multipart uploads <br>&emsp;&emsp; - Sử dụng S3 Select cho query optimization <br>&emsp;&emsp; - Giám sát performance metrics                                                                                                                                                                                                                                                                                        | 09/10/2025   | 09/10/2025      | [Amazon S3 Object Storage Cơ bản <br> Tạo buckets](https://100000.awsstudygroup.com/) <br> <br> [S3 Bảo mật và Kiểm soát Truy cập <br> Cấu hình bucket policies và ACLs](https://100001.awsstudygroup.com/) <br> <br> [S3 Tối ưu Hiệu suất <br> Tối ưu với prefixes](https://100002.awsstudygroup.com/)                                                                                  |
| 6   | - Học AWS Config cho quản lý tài nguyên <br> - Thành thạo AWS WAF cho bảo mật ứng dụng web <br> - Hiểu Application Load Balancer <br> - **Thực hành:** <br>&emsp; + **AWS Config:** <br>&emsp;&emsp; - Thiết lập AWS Config và recorders <br>&emsp;&emsp; - Cấu hình rules và evaluations <br>&emsp;&emsp; - Triển khai giám sát tuân thủ <br>&emsp;&emsp; - Thiết lập khắc phục tự động <br>&emsp;&emsp; - Giám sát thay đổi cấu hình <br>&emsp; + **AWS WAF:** <br>&emsp;&emsp; - Tạo và cấu hình web ACLs <br>&emsp;&emsp; - Triển khai security rules <br>&emsp;&emsp; - Thiết lập giới hạn tốc độ <br>&emsp;&emsp; - Cấu hình chặn IP <br>&emsp;&emsp; - Giám sát sự kiện bảo mật <br>&emsp; + **Application Load Balancer:** <br>&emsp;&emsp; - Tạo và cấu hình ALB <br>&emsp;&emsp; - Thiết lập listener rules <br>&emsp;&emsp; - Triển khai target groups <br>&emsp;&emsp; - Cấu hình path routing <br>&emsp;&emsp; - Giám sát ALB metrics                                                                                                                                                                                                                                                                                                                                                                                                                           | 10/10/2025   | 10/10/2025      | [AWS Config Quản lý Tài nguyên <br> Cấu hình recorders và rules](https://100003.awsstudygroup.com/) <br> <br> [AWS WAF Web Application Firewall <br> Tạo web ACLs](https://100004.awsstudygroup.com/) <br> <br> [Application Load Balancer HTTP/HTTPS <br> Cấu hình listener rules và target groups](https://000015.awsstudygroup.com/)                                                  |

### Kết quả đạt được tuần 5:

- **Thành thạo AWS Lambda Serverless Computing:**

  - Thành thạo khái niệm AWS Lambda và nguyên tắc kiến trúc serverless
  - Thành công tạo và triển khai hàm Lambda bằng Python, Node.js
  - Cấu hình nguồn sự kiện bao gồm API Gateway, S3 và DynamoDB
  - Triển khai xử lý lỗi và cơ chế thử lại phù hợp
  - Thiết lập phiên bản và bí danh hàm để quản lý triển khai
  - Cấu hình đồng thời và đồng thời dành riêng cho hàm
  - Tối ưu hóa hiệu suất và phân bổ bộ nhớ hàm
  - Triển khai ghi log phù hợp với CloudWatch Logs
  - Sử dụng biến môi trường để quản lý cấu hình
  - Tạo và sử dụng các layer Lambda để tái sử dụng mã
  - Hiểu mô hình giá và tối ưu hóa chi phí Lambda
  - Áp dụng các thực tiễn tốt nhất để phát triển ứng dụng serverless

- **Chuyên môn Amazon API Gateway REST API:**

  - Thành thạo khái niệm API Gateway cho phát triển RESTful API
  - Thành công tạo và triển khai REST APIs với tài nguyên
  - Cấu hình phương thức HTTP và xử lý request/response
  - Triển khai tích hợp Lambda cho backend serverless
  - Thiết lập xác thực API với IAM và Cognito
  - Cấu hình xác thực request và ánh xạ response
  - Tạo các giai đoạn API cho môi trường khác nhau
  - Triển khai khóa API và kế hoạch sử dụng
  - Thiết lập tên miền tùy chỉnh với chứng chỉ ACM
  - Cấu hình CORS cho truy cập ứng dụng web
  - Giám sát số liệu API với CloudWatch
  - Áp dụng các thực tiễn tốt nhất cho bảo mật và hiệu suất API

- **Thành thạo Amazon DynamoDB NoSQL Database:**

  - Thành thạo khái niệm DynamoDB và mô hình hóa dữ liệu NoSQL
  - Thành công tạo bảng với khóa phân vùng tối ưu
  - Triển khai hoạt động CRUD hiệu quả sử dụng AWS SDK
  - Tạo và sử dụng chỉ mục phụ cho truy vấn linh hoạt
  - Cấu hình chế độ dung lượng theo yêu cầu và dự phòng
  - Triển khai xử lý lỗi phù hợp cho hoạt động DynamoDB
  - Thiết lập DynamoDB Streams để nắm bắt thay đổi dữ liệu
  - Cấu hình tự động mở rộng cho dung lượng đọc/ghi
  - Triển khai khóa lạc quan cho cập nhật đồng thời
  - Sử dụng hoạt động hàng loạt để xử lý dữ liệu hiệu quả
  - Giám sát hiệu suất bảng với CloudWatch
  - Áp dụng các thực tiễn tốt nhất để tối ưu hóa chi phí

- **Thành thạo AWS Messaging Services (SNS/SQS):**

  - Thành thạo khái niệm SNS/SQS cho kiến trúc phi kết nối
  - Thành công tạo chủ đề và đăng ký SNS
  - Cấu hình hàng đợi SQS với cài đặt phù hợp
  - Triển khai lọc tin nhắn với bộ lọc đăng ký
  - Thiết lập hàng đợi dead-letter cho tin nhắn thất bại
  - Cấu hình lưu giữ tin nhắn và thời gian chờ hiển thị
  - Triển khai xử lý tin nhắn phù hợp với xử lý hàng loạt
  - Tạo hàng đợi FIFO để xử lý tin nhắn theo thứ tự
  - Thiết lập gửi tin nhắn xuyên tài khoản
  - Giám sát số liệu và hiệu suất hàng đợi
  - Triển khai xử lý lỗi và thử lại phù hợp
  - Áp dụng các thực tiễn tốt nhất cho nhắn tin đáng tin cậy

- **Thành thạo AWS Config Resource Management:**

  - Thành thạo khái niệm AWS Config và quản lý cấu hình
  - Thành công thiết lập Config recorders và aggregators
  - Triển khai custom và managed Config rules
  - Cấu hình hành động khắc phục tự động
  - Thiết lập giám sát thay đổi cấu hình
  - Triển khai báo cáo và kiểm tra tuân thủ
  - Tạo theo dõi mối quan hệ tài nguyên
  - Thực hành hiệu quả về quản trị tài nguyên

- **Thành thạo AWS WAF Security:**

  - Thành thạo khái niệm AWS WAF và bảo mật web
  - Thành công tạo và cấu hình web ACLs
  - Triển khai rules chặn và cho phép dựa trên IP
  - Thiết lập rate-based rules cho bảo vệ DDoS
  - Cấu hình phòng chống SQL injection và XSS
  - Triển khai điều kiện geo-matching
  - Giám sát và phân tích sự kiện bảo mật
  - Thực hành hiệu quả về bảo mật ứng dụng web

- **Thành thạo Application Load Balancer:**
  - Thành thạo khái niệm và tính năng ALB
  - Thành công tạo và cấu hình ALB
  - Triển khai listener rules và conditions
  - Thiết lập target groups và health checks
  - Cấu hình path-based routing
  - Triển khai SSL/TLS termination
  - Giám sát metrics hiệu suất ALB
  - Thực hành hiệu quả về load balancing
