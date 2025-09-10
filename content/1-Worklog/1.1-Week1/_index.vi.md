---
title: "Worklog Tuần 1"
date: "2025-08-11"
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Mục tiêu tuần 1:

* Kết nối, làm quen với các thành viên trong First Cloud Journey.
* Hiểu dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:
| Ngày | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 1   | - Gặp mặt, kết nối với team cố vấn và những người khác trong AWS_OJT_FALL_25 <br> - Ghi chú về các chính sách và quy định của chương trình thực tập <br> - Cách thực hiện nhiệm vụ và hoàn thành tất cả bài tập| 09/06/2025 | 09/06/2025      |
| 2   | - Tìm hiểu về các dịch vụ AWS và hỗ trợ cho OJT <br>&emsp; + Cách tạo tài khoản mới và nhận credit free tier <br>&emsp; + Tạo ngân sách hàng tháng cho hóa đơn, một bước quan trọng trong việc quản lý chi phí dịch vụ AWS <br>&emsp; + **Module 1 - 1:** <br>&emsp;&emsp; - Cloud Computing: định nghĩa, lợi ích và cách bắt đầu <br>&emsp;&emsp; - Tìm hiểu về hạ tầng AWS: Data center, Availability Zone, Region, Edge Locations <br>&emsp;&emsp; - Công cụ quản lý dịch vụ AWS: AWS Management Console, AWS CLI (Command Line Interface), AWS SDK (Software Development Kit) | 09/08/2025 | 09/08/2025      | https://000007.awsstudygroup.com/0-createtemplate/ |
| 3   | - **Dịch vụ AWS:** <br>&emsp; + **Module 1 - 1:** <br>&emsp;&emsp; - Tối ưu hóa chi phí sử dụng trên AWS: tránh chi phí không cần thiết <br>&emsp;&emsp; - Làm việc với AWS Support và các loại gói hỗ trợ <br> &emsp;&emsp;&emsp; + Basic <br> &emsp;&emsp;&emsp; + Developer <br> &emsp;&emsp;&emsp; + Business <br> &emsp;&emsp;&emsp; + Enterprise <br> -   **Nhiệm vụ thực hành:** <br>&emsp;&emsp; - Tài khoản AWS <br>&emsp;&emsp; - Cài đặt MFA cho tài khoản root & IAM <br>&emsp;&emsp; - Tổng quan quản lý ngân sách <br>&emsp;&emsp; - Tạo ngân sách theo mẫu <br>&emsp;&emsp; - Tạo ngân sách sử dụng <br>&emsp;&emsp; - Tạo ngân sách Reservation Instance (RI) <br>&emsp;&emsp; - Tạo ngân sách Savings Plans <br>&emsp;&emsp; - Quản lý gói hỗ trợ AWS & Yêu cầu <br>&emsp; + **Nghiên cứu bổ sung:** <br>&emsp;&emsp; - AWS Well-Architected Framework <br> &emsp;&emsp;&emsp; + Tự học và trả lời <br> &emsp;&emsp;&emsp;&emsp; - Các khái niệm, nguyên tắc thiết kế và thực tiễn tốt nhất để thiết kế và vận hành hệ thống trong môi trường điện toán đám mây. <br> &emsp;&emsp;&emsp;&emsp; - Bạn sử dụng Framework bằng cách trả lời các câu hỏi, giúp hiểu sự phù hợp giữa kiến trúc của bạn và các thực tiễn tốt nhất được khuyến nghị. <br> &emsp;&emsp;&emsp;&emsp; - Khi sử dụng AWS Well-Architected Framework trong AWS Management Console, bạn sẽ nhận được hướng dẫn để cải thiện kiến trúc hiện tại.| 09/09/2025 | 09/09/2025| [AWS Calculator](https://calculator.aws/#/) <br> <br> [AWS Well Architected <br> Framework](https://docs.aws.amazon.com/wellarchitected/) |
| 4   | - Tìm hiểu về AWS Virtual Private Cloud (VPC) <br> - Tìm hiểu về bảo mật VPC & tính năng Multi-VPC <br> - VPN - DirectConnect - LoadBalancer - ExtraResources <br> - **Nhiệm vụ thực hành:** <br>&emsp;&emsp; + Bắt đầu với Amazon VPC và AWS VPN Site-to-Site <br>&emsp;&emsp; + Subnets <br>&emsp;&emsp; + Routes <br>&emsp;&emsp; + Internet Gateway (IGW) <br>&emsp;&emsp; + NAT Gateway (NGW) <br>&emsp;&emsp; + Security Group| 09/10/2025 | 09/10/2025 | [AWS Virtual Private <br> Cloud](https://youtu.be/O9Ac_vGHquM?si=VnvwkOE2_eUi2-XP) <br> <br> [VPC Security & <br> Multi-VPC feature](https://youtu.be/BPuD1l2hEQ4?si=Hdqaxk8S2Dtpx83X) <br> <br> [VPN - DirectConnect - <br> LoadBalancer - <br> ExtraResources](https://youtu.be/CXU8D3kyxIc?si=xagv4Aexd94cxUJQ)|


### Kết quả đạt được tuần 1:

* Hiểu AWS là gì và nắm được các nhóm dịch vụ cơ bản: 
  * Compute
  * Storage
  * Networking 
  * Database
  * ...

* Đã tạo và cấu hình AWS Free Tier account thành công.

* Làm quen với AWS Management Console và biết cách tìm, truy cập, sử dụng dịch vụ từ giao diện web.

* Cài đặt và cấu hình AWS CLI trên máy tính bao gồm:
  * Access Key
  * Secret Key
  * Region mặc định
  * ...

* Sử dụng AWS CLI để thực hiện các thao tác cơ bản như:

  * Kiểm tra thông tin tài khoản & cấu hình
  * Lấy danh sách region
  * Xem dịch vụ EC2
  * Tạo và quản lý key pair
  * Kiểm tra thông tin dịch vụ đang chạy
  * ...

* Có khả năng kết nối giữa giao diện web và CLI để quản lý tài nguyên AWS song song.
* ...
