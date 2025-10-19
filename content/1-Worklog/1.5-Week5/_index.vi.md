---
title: "Worklog Tuần 5"
date: "2025-09-09"
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* **Thành thạo AWS Lambda Serverless Computing:**
  * Hiểu các khái niệm Lambda và kiến trúc serverless
  * Tạo và triển khai các hàm Lambda với các runtime khác nhau
  * Cấu hình triggers và nguồn sự kiện
  * Quản lý phiên bản và bí danh hàm
  * Triển khai đồng thời và mở rộng quy mô hàm

* **Học Amazon API Gateway cho RESTful APIs:**
  * Hiểu khái niệm và tính năng API Gateway
  * Tạo và triển khai REST APIs
  * Cấu hình phương thức API và tích hợp
  * Triển khai bảo mật API và kiểm soát truy cập
  * Giám sát hiệu suất và sử dụng API

* **Học Amazon DynamoDB NoSQL Database:**
  * Hiểu khái niệm DynamoDB và mô hình dữ liệu
  * Tạo và quản lý bảng với phân vùng phù hợp
  * Triển khai các hoạt động CRUD với SDK
  * Cấu hình chế độ dung lượng đọc/ghi
  * Sử dụng DynamoDB Streams để nắm bắt thay đổi dữ liệu

* **Thành thạo Amazon SNS/SQS Messaging Services:**
  * Hiểu mô hình nhắn tin và trường hợp sử dụng
  * Tạo chủ đề và hàng đợi để gửi tin nhắn
  * Triển khai pub/sub với SNS
  * Cấu hình message queuing với SQS
  * Xử lý lọc tin nhắn và hàng đợi dead-letter

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ---- | ---------- | --------------- | ----------------- |
| 2   | - Học AWS Lambda serverless computing <br> - Thành thạo Amazon API Gateway cho REST APIs <br> - Hiểu Amazon DynamoDB NoSQL database <br> - Học AWS messaging với SNS/SQS <br> - **Thực hành:** <br>&emsp; + **AWS Lambda:** <br>&emsp;&emsp; - Tạo hàm Lambda với nhiều ngôn ngữ <br>&emsp;&emsp; - Cấu hình trigger và quyền hàm <br>&emsp;&emsp; - Triển khai xử lý lỗi và thử lại <br>&emsp;&emsp; - Thiết lập giám sát và ghi log hàm <br>&emsp;&emsp; - Sử dụng biến môi trường và layers <br>&emsp; + **Amazon API Gateway:** <br>&emsp;&emsp; - Tạo REST APIs với tài nguyên và phương thức <br>&emsp;&emsp; - Cấu hình tích hợp Lambda <br>&emsp;&emsp; - Triển khai xác thực API <br>&emsp;&emsp; - Thiết lập ánh xạ request/response <br>&emsp;&emsp; - Triển khai API tới các giai đoạn khác nhau <br>&emsp; + **Amazon DynamoDB:** <br>&emsp;&emsp; - Tạo bảng với schema khóa phù hợp <br>&emsp;&emsp; - Thực hiện các hoạt động CRUD qua SDK <br>&emsp;&emsp; - Triển khai chỉ mục phụ <br>&emsp;&emsp; - Cấu hình tự động mở rộng <br>&emsp;&emsp; - Sử dụng DynamoDB Streams <br>&emsp; + **SNS/SQS Messaging:** <br>&emsp;&emsp; - Tạo chủ đề SNS và đăng ký <br>&emsp;&emsp; - Thiết lập hàng đợi SQS với cấu hình phù hợp <br>&emsp;&emsp; - Triển khai lọc tin nhắn <br>&emsp;&emsp; - Xử lý xử lý tin nhắn <br>&emsp;&emsp; - Giám sát số liệu hàng đợi | 06/10/2025 | 06/10/2025 | [AWS Lambda](https://000096.awsstudygroup.com/) <br> <br> [Amazon API Gateway](https://000097.awsstudygroup.com/) <br> <br> [Amazon DynamoDB](https://000098.awsstudygroup.com/) <br> <br> [AWS SNS/SQS](https://000099.awsstudygroup.com/) |
| 3   | - Học AWS CloudWatch cho giám sát và quan sát <br> - Thành thạo AWS IAM Roles và Bảo mật <br> - Hiểu Amazon VPC networking <br> - **Thực hành:** <br>&emsp; + **AWS CloudWatch:** <br>&emsp;&emsp; - Thiết lập CloudWatch metrics và dashboards <br>&emsp;&emsp; - Cấu hình cảnh báo và thông báo <br>&emsp;&emsp; - Triển khai custom metrics và dimensions <br>&emsp;&emsp; - Sử dụng CloudWatch Logs cho tập hợp logs <br>&emsp;&emsp; - Tạo metric filters và insights <br>&emsp; + **AWS IAM Roles:** <br>&emsp;&emsp; - Tạo và cấu hình IAM roles <br>&emsp;&emsp; - Thiết lập service-linked roles <br>&emsp;&emsp; - Triển khai truy cập cross-account <br>&emsp;&emsp; - Cấu hình role trust relationships <br>&emsp;&emsp; - Sử dụng role assumption policies <br>&emsp; + **Amazon VPC:** <br>&emsp;&emsp; - Thiết kế kiến trúc VPC và subnets <br>&emsp;&emsp; - Cấu hình route tables và gateways <br>&emsp;&emsp; - Triển khai security groups và NACLs <br>&emsp;&emsp; - Thiết lập kết nối VPC peering <br>&emsp;&emsp; - Sử dụng VPC endpoints cho truy cập service | 07/10/2025 | 07/10/2025 | [AWS CloudWatch](https://000141.awsstudygroup.com/) <br> <br> [AWS IAM Roles](https://000069.awsstudygroup.com/) <br> <br> [Amazon VPC](https://000013.awsstudygroup.com/) |
| 4   | - Học Amazon EBS cho quản lý block storage <br> - Thành thạo Amazon EFS cho hệ thống tập tin có thể mở rộng <br> - Hiểu AWS KMS cho quản lý khóa mã hóa <br> - **Thực hành:** <br>&emsp; + **Amazon EBS Storage:** <br>&emsp;&emsp; - Tạo và gắn EBS volumes <br>&emsp;&emsp; - Cấu hình loại volume và IOPS <br>&emsp;&emsp; - Triển khai EBS snapshots và backups <br>&emsp;&emsp; - Thiết lập vòng đời snapshot tự động <br>&emsp;&emsp; - Giám sát metrics hiệu suất EBS <br>&emsp; + **Amazon EFS File System:** <br>&emsp;&emsp; - Tạo và cấu hình hệ thống tập tin EFS <br>&emsp;&emsp; - Thiết lập mount targets và security groups <br>&emsp;&emsp; - Triển khai EFS access points <br>&emsp;&emsp; - Cấu hình chế độ hiệu suất và throughput <br>&emsp;&emsp; - Sử dụng quản lý vòng đời EFS <br>&emsp; + **AWS KMS Security:** <br>&emsp;&emsp; - Tạo và quản lý khóa KMS <br>&emsp;&emsp; - Thiết lập chính sách và cấp quyền khóa <br>&emsp;&emsp; - Triển khai luân chuyển khóa <br>&emsp;&emsp; - Cấu hình truy cập khóa xuyên tài khoản <br>&emsp;&emsp; - Giám sát sử dụng API KMS | 08/10/2025 | 08/10/2025 | [Amazon EBS](https://000019.awsstudygroup.com/) <br> <br> [Amazon EFS](https://000020.awsstudygroup.com/) <br> <br> [AWS KMS](https://000077.awsstudygroup.com/) |

### Kết quả đạt được tuần 5:

* **Thành thạo AWS Lambda Serverless Computing:**
  * Thành thạo khái niệm AWS Lambda và nguyên tắc kiến trúc serverless
  * Thành công tạo và triển khai hàm Lambda bằng Python, Node.js
  * Cấu hình nguồn sự kiện bao gồm API Gateway, S3 và DynamoDB
  * Triển khai xử lý lỗi và cơ chế thử lại phù hợp
  * Thiết lập phiên bản và bí danh hàm để quản lý triển khai
  * Cấu hình đồng thời và đồng thời dành riêng cho hàm
  * Tối ưu hóa hiệu suất và phân bổ bộ nhớ hàm
  * Triển khai ghi log phù hợp với CloudWatch Logs
  * Sử dụng biến môi trường để quản lý cấu hình
  * Tạo và sử dụng các layer Lambda để tái sử dụng mã
  * Hiểu mô hình giá và tối ưu hóa chi phí Lambda
  * Áp dụng các thực tiễn tốt nhất để phát triển ứng dụng serverless

* **Chuyên môn Amazon API Gateway REST API:**
  * Thành thạo khái niệm API Gateway cho phát triển RESTful API
  * Thành công tạo và triển khai REST APIs với tài nguyên
  * Cấu hình phương thức HTTP và xử lý request/response
  * Triển khai tích hợp Lambda cho backend serverless
  * Thiết lập xác thực API với IAM và Cognito
  * Cấu hình xác thực request và ánh xạ response
  * Tạo các giai đoạn API cho môi trường khác nhau
  * Triển khai khóa API và kế hoạch sử dụng
  * Thiết lập tên miền tùy chỉnh với chứng chỉ ACM
  * Cấu hình CORS cho truy cập ứng dụng web
  * Giám sát số liệu API với CloudWatch
  * Áp dụng các thực tiễn tốt nhất cho bảo mật và hiệu suất API

* **Thành thạo Amazon DynamoDB NoSQL Database:**
  * Thành thạo khái niệm DynamoDB và mô hình hóa dữ liệu NoSQL
  * Thành công tạo bảng với khóa phân vùng tối ưu
  * Triển khai hoạt động CRUD hiệu quả sử dụng AWS SDK
  * Tạo và sử dụng chỉ mục phụ cho truy vấn linh hoạt
  * Cấu hình chế độ dung lượng theo yêu cầu và dự phòng
  * Triển khai xử lý lỗi phù hợp cho hoạt động DynamoDB
  * Thiết lập DynamoDB Streams để nắm bắt thay đổi dữ liệu
  * Cấu hình tự động mở rộng cho dung lượng đọc/ghi
  * Triển khai khóa lạc quan cho cập nhật đồng thời
  * Sử dụng hoạt động hàng loạt để xử lý dữ liệu hiệu quả
  * Giám sát hiệu suất bảng với CloudWatch
  * Áp dụng các thực tiễn tốt nhất để tối ưu hóa chi phí

* **Thành thạo AWS Messaging Services (SNS/SQS):**
  * Thành thạo khái niệm SNS/SQS cho kiến trúc phi kết nối
  * Thành công tạo chủ đề và đăng ký SNS
  * Cấu hình hàng đợi SQS với cài đặt phù hợp
  * Triển khai lọc tin nhắn với bộ lọc đăng ký
  * Thiết lập hàng đợi dead-letter cho tin nhắn thất bại
  * Cấu hình lưu giữ tin nhắn và thời gian chờ hiển thị
  * Triển khai xử lý tin nhắn phù hợp với xử lý hàng loạt
  * Tạo hàng đợi FIFO để xử lý tin nhắn theo thứ tự
  * Thiết lập gửi tin nhắn xuyên tài khoản
  * Giám sát số liệu và hiệu suất hàng đợi
  * Triển khai xử lý lỗi và thử lại phù hợp
  * Áp dụng các thực tiễn tốt nhất cho nhắn tin đáng tin cậy


