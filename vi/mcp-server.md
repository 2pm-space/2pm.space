<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/vi/mcp-server; edits here are overwritten by the next export. -->

# MCP Server — Kết nối Claude Code và Cursor với workspace của bạn

> MCP server từ xa cho workspace 2pm.space. Kết nối Claude Code, Cursor hay bất kỳ MCP client nào bằng một API key, rồi xây agent, sửa tài liệu và sơ đồ tư duy trên Drive, truy vấn cơ sở dữ liệu và quản lý board ngay từ trình soạn thảo — hơn 300 công cụ, giới hạn đúng trong quyền của key.

[2pm.space/vi/mcp-server](https://2pm.space/vi/mcp-server) · [English](../mcp-server.md) · **Tiếng Việt** · [中文](../zh/mcp-server.md) · [日本語](../ja/mcp-server.md) · [한국어](../ko/mcp-server.md) · [ไทย](../th/mcp-server.md) · [Français](../fr/mcp-server.md) · [ລາວ](../lo/mcp-server.md)

*MCP Server · Claude Code · Cursor*

## Workspace của bạn, ngay trong AI client

Kết nối Claude Code, Cursor hay bất kỳ MCP client nào với 2pm.space bằng một API key. Nhờ nó xây agent, sửa quy trình, điền bảng Drive hay đặt biểu đồ lên board — client làm việc qua đúng những thao tác app đang dùng, và chỉ những thao tác key của bạn cho phép.

[Bắt đầu miễn phí](https://2pm.space/signup)

## Kết nối trong ba bước

Một key, một đoạn cấu hình, một yêu cầu.

1. **Tạo API key** — Vào Cài đặt › API Keys & MCP, tạo key và chọn những gì nó được làm. Key không bao giờ có nhiều quyền hơn người tạo ra nó.
2. **Dán đoạn cấu hình** — Chép khối server cho Claude Code hoặc Cursor — endpoint, và key của bạn trong header X-API-Key — vào file cấu hình của client.
3. **Nhờ làm việc** — Nói với client điều bạn muốn. Nó liệt kê công cụ của workspace, đọc playbook cho việc đó, rồi gọi từng bước một.

## Cả workspace, dưới dạng công cụ

Không phải một cửa sổ chỉ đọc — mà đúng những thao tác app thực hiện.

### Mọi MCP client

Server từ xa qua Streamable HTTP, nên chạy với Claude Code, Cursor và mọi client nói được MCP. Trang thiết lập trong app có sẵn đoạn cấu hình cho từng client.

### Hơn 300 công cụ

Agent và canvas của chúng, công cụ, kỹ năng, tri thức, guardrail và bộ nhớ, tài liệu, bảng, sơ đồ tư duy và storyboard trên Drive, nguồn dữ liệu và board, thương hiệu, content calendar và kênh.

### Gói gọn trong quyền của key

Server chỉ liệt kê những công cụ mà quyền của key cho phép, và key hành động như thành viên đã tạo ra nó. Chỉ cấp quyền đọc, và key không thay đổi được gì.

### Playbook cho việc dài hơi

Mười chín hướng dẫn dựng sẵn — xây agent, thiết lập RAG, chuẩn hóa nguồn dữ liệu, lên content calendar — để client đọc trước khi bắt tay vào làm.

### Drive của bạn, ngay từ trình soạn thảo

Tạo và sửa tài liệu, điền bảng Drive, thêm node vào sơ đồ tư duy hay shot vào storyboard — và thay đổi có ngay trong app cho cả đội.

### Dữ liệu và board

Truy vấn cơ sở dữ liệu đã kết nối qua mô hình ngữ nghĩa, dựng board và thêm biểu đồ, hoặc tinh chỉnh chỉ số và quan hệ của mô hình.

## Server mở ra những gì

Kết nối, key, và những phần của workspace mà client làm việc được.

### Kết nối

- MCP server từ xa qua Streamable HTTP
- Một endpoint, hiện trên trang thiết lập
- Đoạn cấu hình cho Claude Code và Cursor
- Khám phá được tại /.well-known/ai-catalog.json

### Key & quyền

- API key của workspace trong header X-API-Key
- Key hành động như thành viên đã tạo nó
- Quyền không rộng hơn quyền của người tạo
- Ngày hết hạn tùy chọn
- Chỉ liệt kê công cụ được phép

### Agent

- Tạo, cấu hình và xóa agent
- Sửa canvas quy trình từng node
- Gán công cụ, kỹ năng và tri thức
- Lưu và khôi phục phiên bản canvas
- Chạy thử và đọc trace

### Drive & nội dung

- Tài liệu, thư mục và bảng Drive
- Sơ đồ tư duy — node, hình và bảng
- Storyboard — cảnh, shot và khung hình
- Thương hiệu, sản phẩm và hình ảnh của chúng
- Các slot của content calendar

### Dữ liệu

- Nguồn dữ liệu, bảng và phạm vi
- Mô hình ngữ nghĩa: cube, chỉ số, quan hệ nối
- Truy vấn bằng CubeQL hoặc SQL
- BI board, tab, biểu đồ và bộ lọc

### Kênh & hộp thư

- Kênh và thiết lập của kênh
- Hội thoại và tin nhắn
- Care agent và trigger
- Guardrail và bộ nhớ

## Sao chép qua lại giữa các tab so với MCP

Cùng một thay đổi, hai cách làm.

| Khi chưa có 2pm.space | Khi có 2pm.space |
| --- | --- |
| Mô tả app cho AI, rồi tự tay chép câu trả lời ngược vào app. | Client tự thực hiện thay đổi, qua chính những thao tác của workspace. |
| Dán một token toàn quyền vào khung chat. | Một key giới hạn trong những gì người tạo được làm — và danh sách công cụ dừng ở đó. |
| Client đoán cách một thiết lập nhiều bước vận hành. | Nó đọc playbook của việc đó trước. |
| Dựng lại cùng một agent bằng tay ở mọi workspace. | Yêu cầu một lần, client dựng từng node. |

## Câu hỏi về MCP

Những điều mọi người hay hỏi trước khi kết nối một client.

### Những client nào dùng được?

Mọi client hỗ trợ MCP server từ xa qua Streamable HTTP. Trang thiết lập có sẵn đoạn cấu hình cho Claude Code và Cursor.

### Client làm được gì trong workspace của tôi?

Những gì key cho phép: xây và chạy thử agent; sửa tài liệu, bảng, sơ đồ tư duy và storyboard trên Drive; truy vấn cơ sở dữ liệu đã kết nối; quản lý board, thương hiệu, content calendar và thiết lập kênh. Danh sách công cụ client thấy đã được lọc sẵn theo những quyền đó.

### Đưa key cho một AI client có an toàn không?

Key hành động như thành viên đã tạo ra nó và không thể có quyền mà người đó không có. Qua MCP không có bước hỏi duyệt, nên quyền của key chính là cửa chặn: chỉ cấp quyền đọc cho client chỉ cần đọc, và đặt ngày hết hạn cho key cần ngừng hoạt động.

### Có tốn credit không?

Phần lớn công cụ chỉ là đọc và ghi thông thường. Những công cụ tạo ra thứ gì đó — một dàn ý calendar, một bức ảnh, một lượt chạy thử agent — tốn credit của workspace y như khi dùng trong app.

## Làm việc trong workspace mà không rời trình soạn thảo

Tạo key, dán đoạn cấu hình, rồi hỏi.

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
