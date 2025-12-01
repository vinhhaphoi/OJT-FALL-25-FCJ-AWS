---
title: "Blog 1"
date: "2025-12-01"
weight: 1
chapter: false
pre: " <b> 3.1. </b> "
---

{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

# Khai thác sức mạnh của Nested Materialized Views và khám phá tính năng Cascading Refresh

### Giới thiệu nested materialized views

Nested materialized views (View vật chất hóa lồng nhau) trong Amazon Redshift cho phép bạn tạo các materialized view dựa trên các materialized view khác. Khả năng này cho phép tạo ra một cấu trúc phân cấp của các kết quả được tính toán trước, nâng cao đáng kể hiệu suất truy vấn và hiệu quả xử lý dữ liệu. Với nested materialized views, bạn có thể xây dựng các lớp trừu tượng dữ liệu đa tầng, tạo ra các view ngày càng phức tạp và chuyên biệt phù hợp với các nhu cầu kinh doanh cụ thể. Cách tiếp cận phân lớp này mang lại một số lợi thế:

- **Cải thiện hiệu suất truy vấn**: Mỗi cấp độ của phân cấp nested materialized view đóng vai trò như một bộ nhớ đệm, cho phép các truy vấn truy cập nhanh vào dữ liệu đã tính toán trước mà không cần phải duyệt qua các bảng cơ sở bên dưới.
- **Giảm tải tính toán**: Bằng cách giảm tải công việc tính toán cho quy trình làm mới materialized view, bạn có thể giảm đáng kể thời gian chạy và sử dụng tài nguyên cho các truy vấn hàng ngày của mình.
- **Đơn giản hóa mô hình dữ liệu**: Nested materialized views cho phép bạn tạo một mô hình dữ liệu mô-đun và có thể mở rộng hơn, trong đó mỗi lớp đại diện cho một khái niệm kinh doanh hoặc trường hợp sử dụng cụ thể.
- **Làm mới gia tăng**: Redshift materialized views hỗ trợ làm mới gia tăng, cho phép bạn chỉ cập nhật dữ liệu đã thay đổi trong phân cấp lồng nhau, tối ưu hóa hơn nữa quy trình làm mới.
- **Cascading Materialized Views**: Redshift materialized views với tùy chọn CASCADE có thể giúp người dùng doanh nghiệp loại bỏ nhu cầu tạo và duy trì các đường ống dữ liệu của riêng họ.

Bạn có thể triển khai nested materialized views bằng câu lệnh [CREATE MATERIALIZED VIEW](https://docs.aws.amazon.com/redshift/latest/dg/materialized-view-create-sql-command.html), cho phép tham chiếu đến các materialized view khác trong định nghĩa. Các trường hợp sử dụng phổ biến bao gồm:

- Các đường ống chuyển đổi dữ liệu dạng mô-đun
- Tổng hợp phân cấp cho phân tích lũy tiến
- Các đường ống xác thực dữ liệu đa cấp
- Quản lý snapshot dữ liệu lịch sử
- Báo cáo BI tối ưu hóa với kết quả tính toán trước

### Architecture

Sơ đồ kiến trúc mô tả cấu trúc nested materialized view của Amazon Redshift: thể hiện nhiều bảng nguồn (màu cam) kết nối đến các materialized view (màu đỏ), với các liên kết đến một lớp view lồng nhau và bảng chia sẻ dữ liệu (màu xanh lá). Sơ đồ này còn hiển thị các điểm tích hợp cho người dùng và trực quan hóa với QuickSight.

1. **Bảng nguồn (Base Table)**: Đây là các bảng chứa dữ liệu thô trong kho dữ liệu, có thể là bảng cục bộ hoặc bảng chia sẻ dữ liệu.
2. **Materialized View cơ sở (Base Materialized View)**: Đây là các materialized view cấp 1 được tạo trực tiếp trên bảng nguồn, đóng vai trò tổng hợp, biến đổi dữ liệu phổ biến, vừa có thể làm nền tảng cho các view lồng nhau, vừa có thể được truy cập bởi người dùng cuối.
3. **Nested Materialized View**: Các materialized view cấp 2 (hoặc cao hơn) được xây dựng dựa trên các materialized view cơ sở. Các view lồng nhau này tiếp tục tổng hợp, lọc hoặc biến đổi dữ liệu từ cấp dưới.
4. **Ứng dụng/Người dùng/Báo cáo BI**: Các ứng dụng hoặc công cụ phân tích BI sẽ truy xuất vào lớp nested materialized view để tạo báo cáo, dashboard. Các view lồng nhau này cung cấp cấu trúc dữ liệu đã tiền xử lý tối ưu hóa cho truy vấn và báo cáo hiệu quả hơn.

### Tạo và sử dụng nested materialized views

Để minh họa cách hoạt động của nested materialized views trong Amazon Redshift, chúng ta sẽ sử dụng bộ dữ liệu TPC-DS. Chúng ta sẽ tạo ba truy vấn sử dụng các bảng STORE, STORE_SALES, CUSTOMER và CUSTOMER_ADDRESS để mô phỏng các báo cáo kho dữ liệu. Ví dụ này sẽ minh họa cách nhiều báo cáo có thể chia sẻ tập kết quả và cách materialized views có thể cải thiện cả hiệu quả tài nguyên và hiệu suất truy vấn.

Hãy xem xét các truy vấn sau đây như là các truy vấn dashboard:

```sql
SELECT cust.c_customer_id, cust.c_first_name, cust.c_last_name, sales.ss_item_sk, sales.ss_quantity, cust.c_current_addr_sk
FROM store_sales sales
INNER JOIN customer cust ON sales.ss_customer_sk = cust.c_customer_sk;

SELECT cust.c_customer_id, cust.c_first_name, cust.c_last_name, sales.ss_item_sk, sales.ss_quantity, cust.c_current_addr_sk, store.s_store_name
FROM store_sales sales
INNER JOIN customer cust ON sales.ss_customer_sk = cust.c_customer_sk
INNER JOIN store store ON sales.ss_store_sk = store.s_store_sk;

SELECT cust.c_customer_id, cust.c_first_name, cust.c_last_name, sales.ss_item_sk, sales.ss_quantity, addr.ca_state
FROM store_sales sales
INNER JOIN customer cust ON sales.ss_customer_sk = cust.c_customer_sk
INNER JOIN store store ON sales.ss_store_sk = store.s_store_sk
INNER JOIN customer_address addr ON cust.c_current_addr_sk = addr.ca_address_sk;
```

Lưu ý rằng phép nối giữa bảng STORE_SALES và CUSTOMER có mặt ở cả 3 truy vấn (dashboard).
Truy vấn thứ hai thêm một phép nối với bảng STORE và truy vấn thứ ba là truy vấn thứ hai với thêm một phép nối với bảng CUSTOMER_ADDRESS. Mô hình này phổ biến trong các kịch bản kinh doanh thông minh (BI). Như đã đề cập trước đó, việc sử dụng materialized view có thể tăng tốc truy vấn vì tập kết quả được lưu trữ và sẵn sàng để cung cấp cho người dùng, tránh việc xử lý lại cùng một dữ liệu. Trong những trường hợp như thế này, chúng ta có thể sử dụng nested materialized views để tái sử dụng dữ liệu đã xử lý.

Khi chuyển đổi các truy vấn của chúng ta thành một tập hợp các nested materialized views, kết quả sẽ như sau:

```sql
CREATE MATERIALIZED VIEW StoreSalesCust as
SELECT cust.c_customer_id, cust.c_first_name, cust.c_last_name, sales.ss_item_sk, sales.ss_store_sk, sales.ss_quantity, cust.c_current_addr_sk
FROM store_sales sales
INNER JOIN customer cust ON sales.ss_customer_sk = cust.c_customer_sk;

CREATE MATERIALIZED VIEW StoreSalesCustStore as
SELECT storesalescust.c_customer_id, storesalescust.c_first_name, storesalescust.c_last_name, storesalescust.ss_item_sk, storesalescust.ss_quantity, storesalescust.c_current_addr_sk, store.s_store_name
FROM StoreSalesCust storesalescust
INNER JOIN store store ON storesalescust.ss_store_sk = store.s_store_sk;

CREATE MATERIALIZED VIEW StoreSalesCustAddress as
SELECT storesalescuststore.c_customer_id, storesalescuststore.c_first_name, storesalescuststore.c_last_name, storesalescuststore.ss_item_sk, storesalescuststore.ss_quantity, addr.ca_state
FROM StoreSalesCustStore storesalescuststore
INNER JOIN customer_address addr ON storesalescuststore.c_current_addr_sk = addr.ca_address_sk;
```

Nested materialized views có thể cải thiện hiệu suất và hiệu quả tài nguyên bằng cách tái sử dụng kết quả view ban đầu, giảm thiểu các phép nối dư thừa và làm việc với các tập kết quả nhỏ hơn. Điều này tạo ra một cấu trúc phân cấp nơi các materialized view phụ thuộc lẫn nhau. Do các phụ thuộc này, bạn phải làm mới các view theo một thứ tự cụ thể.

Với tùy chọn mới “REFRESH MATERIALIZED VIEW mv_name CASCADE”, bạn sẽ có thể làm mới toàn bộ chuỗi phụ thuộc cho các materialized view mà bạn có. Lưu ý rằng trong ví dụ này, chúng ta đang sử dụng materialized view thứ ba, StoreSalesCustAddress, và điều này sẽ làm mới tất cả 3 materialized view vì chúng phụ thuộc lẫn nhau.

Nếu chúng ta sử dụng materialized view thứ hai với tùy chọn CASCADE, chúng ta sẽ chỉ làm mới materialized view thứ nhất và thứ hai, giữ nguyên view thứ ba. Điều này có thể hữu ích khi chúng ta cần giữ một số materialized view với dữ liệu ít cập nhật hơn những view khác.

System view [SVL_MV_REFRESH_STATUS](https://docs.aws.amazon.com/redshift/latest/dg/r_SVL_MV_REFRESH_STATUS.html) tiết lộ trình tự làm mới của các materialized view. Khi kích hoạt làm mới cascade trên StoreSalesCustAddress, hệ thống tuân theo chuỗi phụ thuộc mà chúng ta đã thiết lập: StoreSalesCust làm mới trước, tiếp theo là StoreSalesCustStore, và cuối cùng là StoreSalesCustAddress. Điều này chứng minh cách hoạt động làm mới tôn trọng cấu trúc phân cấp của các materialized view của chúng ta.

#### Lưu ý

Xem xét một chuỗi phụ thuộc nơi StoreSalesCust (A) → StoreSalesCustStore (B) → StoreSalesCustAddress (C).

- Hành vi làm mới CASCADE hoạt động như sau:
  - Khi làm mới C với CASCADE: A, B, và C đều sẽ được làm mới.
  - Khi làm mới B với CASCADE: Chỉ A và B sẽ được làm mới.
  - Khi làm mới A với CASCADE: Chỉ A sẽ được làm mới.
  - Nếu bạn đặc biệt cần làm mới A và C nhưng không phải B, bạn phải thực hiện các thao tác làm mới riêng biệt mà không sử dụng CASCADE—đầu tiên làm mới A, sau đó làm mới C trực tiếp.

### Thực hành tốt với materialized view

- **Cải thiện truy vấn nguồn**: Bắt đầu với một câu lệnh SELECT được tối ưu hóa tốt cho materialized view của bạn. Điều này đặc biệt quan trọng đối với các view cần xây dựng lại hoàn toàn trong mỗi lần làm mới.
- **Lập kế hoạch chiến lược làm mới**: Khi tạo các materialized view phụ thuộc vào các materialized view khác, bạn không thể sử dụng AUTO REFRESH YES. Thay vào đó, hãy triển khai các cơ chế làm mới được điều phối bằng cách sử dụng Redshift Data API với Amazon EventBridge để lập lịch và AWS Step Functions để quản lý quy trình làm việc.
- **Tận dụng distribution và sort keys**: Cấu hình đúng distribution và sort keys trên các materialized view dựa trên các mẫu truy vấn của chúng để tối ưu hóa hiệu suất. Các khóa được chọn tốt sẽ cải thiện tốc độ truy vấn và giảm các hoạt động I/O.

### Kết luận

Bài đăng này đã chỉ ra cách tạo nested Amazon Redshift materialized views và làm mới các materialized view con bằng cách sử dụng tùy chọn REFRESH CASCADE mới. Bạn có thể nhanh chóng xây dựng và duy trì các đường ống xử lý dữ liệu hiệu quả và mở rộng liền mạch các lợi ích thực thi truy vấn độ trễ thấp của materialized views sang phân tích dữ liệu.

Nếu bạn chưa quen với materialized views nhưng muốn tăng hiệu suất khối lượng công việc của mình, Amazon Redshift cung cấp tính năng Automated materialized view (auto-MV). Hệ thống thông minh này giám sát khối lượng công việc của bạn và tự động tạo các materialized view để nâng cao hiệu suất tổng thể. Để biết thêm thông tin chi tiết về tính năng này, vui lòng tham khảo [Automated materialized views](https://docs.aws.amazon.com/redshift/latest/dg/materialized-view-auto-mv.html).

### Thông tin tác giả

**Ritesh Kumar Sinha** là một Kiến trúc sư giải pháp chuyên về phân tích (Analytics Specialist Solutions Architect) làm việc tại San Francisco. Ông đã giúp khách hàng xây dựng các giải pháp kho dữ liệu và dữ liệu lớn có khả năng mở rộng trong hơn 16 năm. Ông yêu thích thiết kế và xây dựng các giải pháp đầu cuối hiệu quả trên AWS. Trong thời gian rảnh rỗi, ông thích đọc sách, đi bộ và tập yoga.

**Raza Hafeez** là một Quản lý sản phẩm cấp cao (Senior Product Manager) tại Amazon Redshift. Ông có hơn 13 năm kinh nghiệm chuyên môn trong việc xây dựng và tối ưu hóa các kho dữ liệu doanh nghiệp và rất đam mê việc giúp khách hàng nhận ra sức mạnh từ dữ liệu của họ. Ông chuyên về việc di chuyển các kho dữ liệu doanh nghiệp sang Kiến trúc dữ liệu hiện đại của AWS.

**Ricardo Serafim** là một Kiến trúc sư giải pháp chuyên về phân tích cấp cao (Senior Analytics Specialist Solutions Architect) tại AWS. Ông đã hỗ trợ các công ty với các giải pháp Kho dữ liệu từ năm 2007.
