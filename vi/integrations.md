<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/vi/integrations; edits here are overwritten by the next export. -->

# Tích hợp — kênh, API, cơ sở dữ liệu & MCP

> Kết nối kênh nhắn tin, HTTP API, 6 loại cơ sở dữ liệu, MCP server và code trong sandbox với AI agent của bạn — chỉ cần mô tả chứ không cần viết code, kèm API và MCP endpoint riêng.

[2pm.space/vi/integrations](https://2pm.space/vi/integrations) · [English](../integrations.md) · **Tiếng Việt** · [中文](../zh/integrations.md) · [日本語](../ja/integrations.md) · [한국어](../ko/integrations.md) · [ไทย](../th/integrations.md) · [Français](../fr/integrations.md) · [ລາວ](../lo/integrations.md)

*Kênh · Công cụ · MCP · API*

## Kết nối với mọi hệ thống bạn đang dùng

Kênh nhắn tin, HTTP API, cơ sở dữ liệu, MCP server và code trong sandbox — chỉ cần mô tả chứ không cần viết code, để agent chạm tới được hệ thống đang giữ câu trả lời thay vì xin lỗi vì không biết.

[Bắt đầu miễn phí](https://2pm.space/signup)

## Sáu cách chạm tới phần còn lại của hệ thống

Dù là hệ thống nào, một trong số này cũng đã đáp ứng được.

### Mọi API, chỉ cần mô tả

Cho công cụ một URL, một phương thức, một auth header và JSON Schema cho tham số, rồi cấp nó cho những agent cần gọi. Không phải triển khai gì ngoài endpoint bạn đã có.

### Viết code khi mô tả khó hơn

Python trong sandbox, gọi được như một công cụ: tham số đến qua ARGS, kết quả là những gì hàm in ra. Dành cho những phép định dạng lại, phân tích và tính toán viết ra nhanh hơn giải thích cho model.

### MCP, cả hai chiều

Trỏ một công cụ vào bất kỳ MCP server nào, khám phá các công cụ của nó bằng một cú bấm rồi bật, tắt hoặc bắt duyệt từng cái — và điều khiển workspace này từ một MCP client bên ngoài, kể cả coding agent dựng agent giúp bạn.

### Agent làm công cụ

Cho agent này dùng agent kia. Agent điều phối giao việc cho agent chuyên môn và nhận lại câu trả lời có cấu trúc, thay vì nhồi thêm một bản sao của agent chuyên môn vào prompt của chính nó.

### Kênh cũng là tích hợp

Messenger, Zalo cá nhân, Telegram, Pancake và widget website kết nối như kênh chính thức, đầy đủ tính năng. Mọi thứ khác đi qua kênh API tùy chỉnh — một webhook vào, một webhook ra.

### Sự kiện đẩy về cho bạn

Sự kiện trong hộp thư được gửi tới các endpoint của bạn, nên một tin nhắn mới có thể kích hoạt việc gì đó trong hệ thống của bạn. Việc gửi được ghi nhật ký, nên bên nhận từng bị sập sẽ hiện rõ chứ không bị mất dấu.

## Danh mục tích hợp

Những gì đã kết nối được hôm nay, theo từng loại.

### Kênh nhắn tin

- Facebook Messenger, và bình luận kèm trả lời bằng tin nhắn riêng
- Zalo cá nhân; Zalo Official Account sắp ra mắt
- Bot Telegram
- Tài khoản Pancake
- Widget chat trên website
- API tùy chỉnh — webhook vào, webhook ra

### Loại công cụ

- Công cụ có sẵn, gồm Viettel Post, KiotViet và WordPress
- Công cụ webhook — mọi HTTP API, xác thực bằng bearer hoặc key
- Hàm Python trong sandbox, không có mạng trừ khi bạn cho phép
- Người duyệt và lưu đệm kết quả, cho từng công cụ
- MCP server — khám phá công cụ, bật hoặc tắt từng cái
- Agent giao việc cho agent khác dưới dạng công cụ

### Kết nối dữ liệu

- PostgreSQL và MySQL
- Redshift và ClickHouse
- Snowflake và BigQuery
- Chọn bảng khi kết nối — mô hình chỉ đọc những bảng đó

### Đăng bài và dịch vụ

- Đăng lên Facebook Page và WordPress
- Nơi đăng là webhook tùy chỉnh
- Kết nối tài khoản ứng dụng cho dịch vụ bên thứ ba
- Giao hàng qua Viettel Post, có thu hộ (COD)

### Truy cập bằng lập trình

- API key của workspace, giới hạn theo quyền của người tạo
- MCP endpoint xác thực bằng cùng key đó
- Webhook gửi đi theo sự kiện trong hộp thư
- Nhật ký từng lượt gọi kèm chi phí

### Sẵn sàng để cài

- Marketplace mẫu agent
- Mẫu được sao chép vào workspace của bạn rồi chỉnh sửa
- Kỹ năng và công cụ dùng chung cho mọi agent
- Ứng dụng xây trên nền tảng, cài vào workspace

## Những gì không còn là một dự án kỹ thuật

Những tích hợp mà lẽ ra bạn phải tự viết và bảo trì.

| Khi chưa có 2pm.space | Khi có 2pm.space |
| --- | --- |
| Yêu cầu connector nằm trong backlog của ai đó, chờ nhà cung cấp làm | Tự mô tả endpoint và agent gọi được ngay trong buổi chiều |
| Code kết nối phải triển khai và bảo trì cho từng dịch vụ nội bộ mà agent chạm tới | Công cụ webhook, cộng Python trong sandbox cho những phần cần đến |
| Agent chỉ biết nói, vì không chạm tới được thứ gì nó cần | Kênh, API, cơ sở dữ liệu và MCP server đều gọi được từ cùng một vòng lặp |
| Chép prompt của một agent chuyên môn vào mọi agent khác cần đến nó | Một agent được mở ra làm công cụ để các agent khác giao việc |
| Dán một token vào file cấu hình dùng chung để một script chạm tới được nền tảng | API key của workspace giới hạn theo quyền của người tạo, thu hồi được từng key |

## Câu hỏi về tích hợp

Những điều kỹ sư hay hỏi trước khi nối nền tảng vào hệ thống nội bộ.

### Làm sao kết nối một dịch vụ không có trong danh sách?

Bằng một công cụ webhook. Bạn điền URL, phương thức, auth header và JSON Schema cho các tham số, rồi cấp nó cho những agent cần dùng — hoặc đặt Toàn cục để mọi agent đều dùng được. Không phải triển khai code gì ở phía chúng tôi, và phía bạn cũng không cần gì ngoài endpoint bạn đã có.

### Agent có chạy được code không?

Có — Python, trong sandbox, như một công cụ agent có thể gọi. Đây là lựa chọn đúng cho những phép biến đổi viết ra dễ hơn mô tả: định dạng lại payload, làm những phép tính không nên giao cho model, phân tích một thứ gì đó khó nhằn. Truy cập internet luôn tắt trừ khi bạn bật lên.

### Có hỗ trợ MCP không?

Theo cả hai chiều. Một công cụ MCP trỏ vào bất kỳ server nào: khám phá các công cụ của nó bằng một cú bấm, rồi chọn cái nào agent được dùng và cái nào cần người duyệt. Nền tảng cũng mở MCP server riêng để một client bên ngoài — kể cả coding agent — điều khiển workspace của bạn: tạo agent, sửa tài liệu, truy vấn board, quản lý kỹ năng và công cụ.

### Một agent có gọi được agent khác không?

Có. Một agent có thể được mở ra làm công cụ, để agent điều phối giao việc cho agent chuyên môn và nhận lại câu trả lời có cấu trúc, thay vì làm lại những gì agent chuyên môn vốn đã làm.

### Webhook theo chiều ngược lại hoạt động thế nào?

Sự kiện trong hộp thư có thể được đẩy tới các endpoint của bạn, nên một tin nhắn mới hay một hội thoại đã xử lý xong có thể kích hoạt việc gì đó trong hệ thống của riêng bạn. Việc gửi được ghi nhật ký, nên bên nhận từng bị sập sẽ hiện rõ, chứ không phải một tin nhắn bạn không bao giờ biết tới.

### Có API không?

Có. API key được cấp theo từng workspace và mang quyền của thành viên đã tạo ra nó, nên một key không thể làm nhiều hơn người đứng sau nó. Cùng key đó cũng dùng để xác thực MCP endpoint.

## Nối vào hệ thống đang có câu trả lời

Mô tả một endpoint, kết nối một cơ sở dữ liệu, hoặc trỏ tới một MCP server. Bắt đầu miễn phí, không cần thẻ tín dụng.

[Bắt đầu miễn phí](https://2pm.space/signup) · [Liên hệ tư vấn](contact.md)

---

**Sản phẩm**

- [AI Inbox](ai-inbox.md) — Messenger, Telegram, chat website và Zalo cá nhân trong một hàng đợi
- [Live Chat](live-chat.md) — Widget chat AI ngay trên website của bạn
- [Customer 360](customer-360.md) — Một hồ sơ khách hàng xuyên suốt mọi kênh
- [Ask Data](ask-data.md) — Hỏi cơ sở dữ liệu bằng ngôn ngữ đời thường
- [BI Dashboard](bi-dashboards.md) — Board ghim từ những câu hỏi bằng lời thường
- [Content Calendar](content-calendar.md) — Lên kế hoạch, viết bài, minh họa và đăng bài
- [Brand Kit](brand-kit.md) — Giọng văn, thiết kế và tri thức cho mọi người viết
- [Magic Studio](magic-studio.md) — Ảnh AI đúng chất thương hiệu, trên một canvas nhiều bước
- [Storyboard](storyboard.md) — Từ kịch bản, phân cảnh đến clip hoàn chỉnh
- [Mind Map](mind-map.md) — Vẽ sơ đồ tư duy thời gian thực, miễn phí, không giới hạn
- [Ứng dụng di động](mobile-app.md)

**Nền tảng**

- [Agent Builder](agent-builder.md) — Agent theo quy trình: tra cứu, hành động và tự kiểm tra
- [Kho công cụ](tools.md) — 60 công cụ dựng sẵn, API của bạn và MCP
- [Lịch trình](scheduler.md) — Agent tự chạy theo lịch
- [Tích hợp](integrations.md) — Kênh, API, cơ sở dữ liệu và MCP
- [MCP Server](mcp-server.md) — Làm việc trong workspace từ Claude Code hoặc Cursor
- [Fine-Tuning](fine-tuning.md) — Huấn luyện model từ chính các cuộc hội thoại của bạn
- [Bảo mật](security.md) — Vai trò, chia sẻ, nhật ký audit và sao lưu
- [Bảng giá](pricing.md)

**Công ty**

- [Liên hệ](contact.md)
- [Chính sách quyền riêng tư](https://2pm.space/privacy-policy)
- [Xoá tài khoản của bạn](https://2pm.space/delete-account)
