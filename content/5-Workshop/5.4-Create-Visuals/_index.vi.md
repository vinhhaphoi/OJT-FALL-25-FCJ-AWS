---
title: "Tạo Trực quan hóa"
date: "2025-12-02"
weight: 4
chapter: false
pre: " <b> 5.4. </b> "
---

#### Bước 1: Tạo Phân tích

1.  Nếu bạn chưa ở trong chế độ xem phân tích, hãy vào **Datasets**, chọn tập dữ liệu của bạn và chọn **Create analysis** (Tạo phân tích).
2.  Bạn sẽ thấy một không gian làm việc trống được gọi là "Sheet".

#### Bước 2: Trực quan hóa 1 - Doanh số theo Sản phẩm (Biểu đồ Donut)

1.  Trong ngăn **Visual types** (Loại trực quan hóa) ở dưới cùng bên trái, chọn biểu tượng **Donut chart**.
2.  Từ **Fields list** (Danh sách trường) bên trái, kéo `Product` vào ô **Group/Color**.
3.  Kéo `Sales` vào ô **Value**.
4.  Bạn sẽ thấy biểu đồ donut hiển thị phân bổ doanh số theo sản phẩm.

#### Bước 3: Trực quan hóa 2 - Xu hướng Doanh số theo Thời gian (Biểu đồ Đường)

1.  Chọn **Add** > **Add visual** từ thanh menu trên cùng.
2.  Chọn biểu tượng **Line chart** (Biểu đồ đường).
3.  Kéo `Date` vào ô **X axis**.
4.  Kéo `Sales` vào ô **Value**.
5.  Bạn sẽ thấy biểu đồ đường hiển thị doanh số theo thời gian.

#### Bước 4: Trực quan hóa 3 - Doanh số theo Khu vực (Biểu đồ Cột)

1.  Chọn **Add** > **Add visual**.
2.  Chọn biểu tượng **Vertical bar chart** (Biểu đồ cột dọc).
3.  Kéo `Region` vào ô **X axis**.
4.  Kéo `Sales` vào ô **Value**.
5.  Bây giờ bạn có thể thấy khu vực nào hoạt động tốt nhất.
