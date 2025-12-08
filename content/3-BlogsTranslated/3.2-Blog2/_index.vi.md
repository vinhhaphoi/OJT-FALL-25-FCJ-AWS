---
title: "Blog 2"
date: "2025-12-01"
weight: 1
chapter: false
pre: " <b> 3.2. </b> "
---

# Amazon Nova Lite cho phép Bito cung cấp tùy chọn miễn phí cho đánh giá mã nguồn bằng AI

### Lựa chọn mô hình chi phí hiệu quả cho gói miễn phí

Để cung cấp tùy chọn gói miễn phí cho AI Code Review Agent, Bito cần một mô hình nền tảng (FM) có thể cung cấp mức hiệu suất và kết quả phù hợp với chi phí hợp lý. Tất nhiên, việc cung cấp đánh giá mã miễn phí cho khách hàng tiềm năng sẽ không miễn phí đối với Bito, vì họ sẽ phải trả chi phí suy luận (inference costs). Để xác định một mô hình cho Gói miễn phí của mình, Bito đã thực hiện quy trình đánh giá kéo dài 2 tuần trên nhiều mô hình, bao gồm các FM hiệu suất cao trên [Amazon Bedrock](https://aws.amazon.com/bedrock/), cũng như OpenAI GPT-4o mini. Các mô hình Amazon Nova—các mô hình nhanh, tiết kiệm chi phí mới được giới thiệu trên Amazon Bedrock—đặc biệt thu hút sự quan tâm của nhóm.

Vào cuối quá trình đánh giá, Bito xác định rằng Amazon Nova Lite mang lại sự kết hợp phù hợp giữa hiệu suất và hiệu quả chi phí cho các trường hợp sử dụng của họ. Tốc độ của nó cung cấp khả năng tạo nhanh các bản tóm tắt đánh giá mã. Tuy nhiên, chi phí—một cân nhắc chính cho Gói miễn phí của Bito—đã chứng minh là yếu tố quyết định. Cuối cùng, Amazon Nova Lite đã đáp ứng các tiêu chí của Bito về tốc độ, chi phí và chất lượng. Sự kết hợp giữa Amazon Nova Lite và Amazon Bedrock cũng giúp Bito có thể cung cấp độ tin cậy và bảo mật mà khách hàng của họ cần khi giao phó mã của họ cho Bito. Rốt cuộc, kiểm soát cẩn thận mã là một trong những lời hứa cốt lõi của Bito với khách hàng. Nó không lưu trữ mã hoặc sử dụng nó để đào tạo mô hình. Và các sản phẩm của nó được chứng nhận SOC 2 Type 2 để cung cấp bảo mật dữ liệu, tính toàn vẹn của quá trình xử lý, quyền riêng tư và bảo mật.

### Áp dụng mô hình phù hợp cho từng gói

Bito hiện đã áp dụng Amazon Bedrock làm nền tảng tiêu chuẩn hóa để khám phá, thêm và chạy các mô hình. Bito sử dụng Amazon Nova Lite làm mô hình chính cho Gói miễn phí của mình và Claude 3.7 Sonnet của Anthropic cung cấp sức mạnh cho Gói Teams trả phí, tất cả đều được truy cập và tích hợp thông qua API và các biện pháp kiểm soát thống nhất của Amazon Bedrock. Amazon Bedrock cung cấp khả năng chuyển đổi liền mạch từ Amazon Nova Lite sang Sonnet của Anthropic khi khách hàng nâng cấp, với những thay đổi mã tối thiểu. Các nhà lãnh đạo của Bito nhanh chóng chỉ ra rằng Amazon Nova Lite không chỉ cung cấp sức mạnh cho Gói miễn phí của họ—nó đã truyền cảm hứng cho nó. Nếu không có chi phí rất thấp của Amazon Nova Lite, họ sẽ không thể cung cấp một tầng miễn phí của AI Code Review Agent, điều mà họ coi là một bước đi chiến lược cho phép mở rộng cơ sở khách hàng doanh nghiệp của mình. Chiến lược này nhanh chóng tạo ra kết quả, thu hút lượng khách hàng tiềm năng đến với Gói miễn phí nhiều gấp ba lần so với dự kiến. Vào cuối thời gian dùng thử 14 ngày, một số lượng đáng kể người dùng chuyển đổi sang AI Code Review Agent đầy đủ để truy cập toàn bộ các khả năng của nó.

Được khích lệ bởi thành công với AI Code Review Agent, Bito hiện đang sử dụng Amazon Nova Lite để cung cấp khả năng trò chuyện cho [Bito Wingman](https://bito.ai/product/wingman/), công nghệ tác nhân AI mới nhất của họ—một trợ lý nhà phát triển đầy đủ tính năng trong môi trường phát triển tích hợp (IDE) kết hợp tạo mã, xử lý lỗi, tư vấn kiến trúc và hơn thế nữa. Một lần nữa, sự kết hợp giữa chất lượng và chi phí thấp của Amazon Nova Lite đã khiến nó trở thành lựa chọn đúng đắn cho Bito.

### Kết luận

Trong bài đăng này, chúng tôi đã chia sẻ cách Bito—một công ty khởi nghiệp sáng tạo cung cấp danh mục ngày càng tăng các tác nhân nhà phát triển được hỗ trợ bởi AI—đã chọn Amazon Nova Lite để cung cấp sức mạnh cho gói miễn phí của AI Code Review Agent, sản phẩm chủ lực của họ. Các tác nhân được hỗ trợ bởi AI của họ được thiết kế đặc biệt để giúp cuộc sống của các nhà phát triển dễ dàng hơn và công việc của họ hiệu quả hơn:

- **Amazon Nova Lite cho phép Bito đáp ứng một trong những thách thức kinh doanh cốt lõi của mình**—thu hút khách hàng doanh nghiệp. Bằng cách giới thiệu gói miễn phí, Bito đã thu hút lượng khách hàng mới tiềm năng nhiều gấp ba lần đến với sản phẩm chủ lực dựa trên AI tạo sinh của mình—AI Code Review Agent.
- **Amazon Nova Lite vượt trội hơn các mô hình khác trong quá trình thử nghiệm nội bộ nghiêm ngặt**, cung cấp mức hiệu suất phù hợp với chi phí rất thấp mà Bito cần để ra mắt gói miễn phí của AI Code Review Agent.
- **Amazon Bedrock trao quyền cho Bito chuyển đổi liền mạch giữa các mô hình khi cần thiết** cho từng tầng của AI Code Review Agent—Amazon Nova Lite cho Gói miễn phí và Claude 3.7 Sonnet của Anthropic cho Gói Teams trả phí. Amazon Bedrock cũng cung cấp bảo mật và quyền riêng tư, những cân nhắc quan trọng đối với khách hàng của Bito.
- **Bito cho thấy cách các tổ chức sáng tạo có thể sử dụng sự kết hợp giữa chất lượng, hiệu quả chi phí và tốc độ** trong Amazon Nova Lite để mang lại giá trị cho khách hàng của họ—và cho doanh nghiệp của họ.

“Thách thức của chúng tôi là thúc đẩy khả năng của AI để mang lại giá trị mới cho các nhà phát triển, nhưng với chi phí hợp lý,” Amar Goel, đồng sáng lập và CEO của Bito chia sẻ. “Amazon Nova Lite cung cấp cho chúng tôi mô hình rất nhanh, chi phí thấp mà chúng tôi cần để cung cấp sức mạnh cho gói miễn phí của AI Code Review Agent—và thu hút khách hàng mới.”

Bắt đầu với Amazon Nova trên [Amazon Bedrock console](https://console.aws.com/bedrock/). Tìm hiểu thêm về Amazon Nova Lite tại [trang sản phẩm Amazon Nova](https://aws.amazon.com/nova/).

### Thông tin về tác giả

**Eshan Bhatnagar** là Giám đốc Quản lý Sản phẩm cho Amazon AGI tại Amazon Web Services.

**Amar Goel** là Đồng sáng lập và CEO của Bito. Là một doanh nhân hàng loạt, Amar trước đây đã thành lập PubMatic (lên sàn chứng khoán năm 2020), và từng làm việc tại Microsoft, McKinsey, và là kỹ sư phần mềm tại Netscape, công ty trình duyệt ban đầu. Amar đã theo học tại Đại học Harvard. Ông rất hào hứng với việc sử dụng GenAI để thúc đẩy thế hệ tiếp theo của cách phần mềm được xây dựng!
