---
title: "Điều kiện tiên quyết & Dữ liệu"
date: "2025-12-02"
weight: 2
chapter: false
pre: " <b> 5.2. </b> "
---

#### Bước 1: Đăng ký Amazon QuickSight

1.  Đăng nhập vào AWS Management Console.
2.  Tìm kiếm **QuickSight**.
3.  Nếu bạn chưa đăng ký, bạn sẽ được nhắc thực hiện việc này.
4.  Chọn **Sign up for QuickSight** (Đăng ký QuickSight).
5.  Chọn phiên bản **Enterprise** (có bản dùng thử miễn phí).
6.  Làm theo hướng dẫn trên màn hình:
    - **Authentication method** (Phương thức xác thực): Sử dụng IAM federated identity & QuickSight-managed users (mặc định).
    - **Region** (Khu vực): Chọn **US East (N. Virginia)**.
    - **QuickSight account name** (Tên tài khoản QuickSight): Nhập một tên duy nhất.
    - **Notification email** (Email thông báo): Nhập email của bạn.
    - **Allow access** (Cho phép truy cập): Bạn có thể để mặc định. Đối với workshop này, chúng ta không nhất thiết cần quyền truy cập S3, nhưng tốt nhất là nên chọn S3 nếu bạn định sử dụng sau này.
7.  Nhấp **Finish** (Hoàn tất).

#### Bước 2: Chuẩn bị Dữ liệu Mẫu

Chúng ta sẽ sử dụng một tệp CSV đơn giản cho workshop này.

1.  Sao chép dữ liệu sau và lưu thành tệp có tên `sales_data.csv` trên máy tính của bạn.

```csv
Date,Region,Product,Sales,Quantity
2023-01-01,North,Laptop,1200,2
2023-01-02,South,Phone,800,5
2023-01-03,East,Tablet,400,3
2023-01-04,West,Laptop,1200,1
2023-01-05,North,Phone,800,2
2023-01-06,South,Tablet,400,4
2023-01-07,East,Laptop,1200,3
2023-01-08,West,Phone,800,6
2023-01-09,North,Tablet,400,2
2023-01-10,South,Laptop,1200,4
```

Ngoài ra, bạn có thể sử dụng bất kỳ tệp CSV nào bạn có, nhưng hướng dẫn sẽ tuân theo cấu trúc này.
