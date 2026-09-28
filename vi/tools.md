<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/vi/tools; edits here are overwritten by the next export. -->

# Kho công cụ cho AI Agent — 60 công cụ dựng sẵn, API của bạn và MCP

> Trang bị công cụ cho AI agent: 60 công cụ dựng sẵn cho tìm kiếm, tri thức, dữ liệu, email, lịch và Drive; HTTP API và Python chạy trong sandbox của riêng bạn; mọi MCP server; và tích hợp Viettel Post, KiotViet, WordPress, ERPNext.

[2pm.space/vi/tools](https://2pm.space/vi/tools) · [English](../tools.md) · **Tiếng Việt** · [中文](../zh/tools.md) · [日本語](../ja/tools.md) · [한국어](../ko/tools.md) · [ไทย](../th/tools.md) · [Français](../fr/tools.md) · [ລາວ](../lo/tools.md)

*Công cụ · Dựng sẵn · HTTP · Code · MCP*

## Mọi công cụ agent cần, trong một kho

Chọn từ 60 công cụ dựng sẵn, bọc API hoặc hàm Python của riêng bạn, kết nối bất kỳ MCP server nào, hoặc giao cho agent một agent khác. Cấp từng công cụ cho đúng agent cần nó — và để những công cụ rủi ro phải chờ người duyệt.

[Bắt đầu miễn phí](https://2pm.space/signup)

## Trao công cụ cho agent trong ba bước

Chọn, kết nối, cấp quyền.

1. **Chọn loại** — Chọn từ kho dựng sẵn, hoặc tạo webhook, hàm Python, kết nối MCP hay agent làm công cụ.
2. **Kết nối** — Dán API key nhà cung cấp đưa cho bạn, hoặc URL và thông tin xác thực của dịch vụ riêng. Thông tin đăng nhập được lưu mã hóa.
3. **Cấp quyền** — Bật cho những agent nên dùng, hoặc để toàn cục cho mọi agent. Agent tự quyết khi nào gọi dựa trên mô tả của công cụ.

## Năm loại công cụ, một danh sách

Agent cần chạm tới thứ gì, đều có cách trao cho nó.

### Sáu mươi công cụ, dùng ngay

Tìm kiếm web, Wikipedia và ArXiv, trình duyệt headless, Gmail và Google Calendar, GitHub, Telegram, chuyển văn bản thành giọng nói, BI board và chính Drive của bạn — mỗi công cụ là một thẻ trong kho, nhiều cái chạy được ngay khi thêm vào.

### Mọi HTTP API

Mô tả endpoint — method, URL, header, xác thực và JSON agent cần gửi — là thành một công cụ. GET, POST, PUT, PATCH và DELETE, xác thực bằng bearer token hoặc API key.

### Python của riêng bạn

Viết một hàm, khai báo schema đầu vào, và nó chạy trong sandbox có timeout — không ra internet trừ khi bạn cho phép.

### Mọi MCP server

Trỏ tới URL của server, các công cụ nó cung cấp được tự phát hiện. Bật hoặc tắt từng cái, và bắt duyệt với những cái có ghi dữ liệu.

### Agent làm công cụ

Mở một agent cho agent khác dùng: người viết hỏi người nghiên cứu, agent bán hàng hỏi agent kiểm kho — mỗi agent vẫn giữ prompt, model và công cụ riêng.

### Bạn quyết ai nắm gì

Cấp công cụ theo từng agent hoặc để toàn cục, tắt mà không cần xóa, lưu cache kết quả, và bắt buộc có người duyệt trước khi chạy.

## 60 công cụ dựng sẵn

Kho của nút Tạo công cụ, đúng như hiện tại. Chọn một nhóm để thu gọn danh sách.

### Tìm kiếm

- Tavily Search — Cần API key
- DuckDuckGo Search
- Google Serper — Cần API key
- YouTube Search
- YouTube Video Info
- Google Places — Cần API key

### Tri thức

- Wikipedia
- ArXiv
- PubMed
- StackExchange
- Semantic Scholar
- OpenWeatherMap — Cần API key
- Google Scholar — Cần API key

### Tính toán

- Wolfram Alpha — Cần API key
- Python REPL
- Shell Command

### Dữ liệu

- SQL Database — Cần API key
- Pandas DataFrame
- Vector Store Search
- GraphQL — Cần API key
- BI Board

### AI & đa phương tiện

- DALL-E Image Generation — Cần API key
- ElevenLabs TTS — Cần API key
- Google Cloud TTS — Cần API key
- HuggingFace Hub — Cần API key

### Tài chính

- Yahoo Finance News
- Google Finance — Cần API key
- Google Trends — Cần API key

### Tiện ích

- Web Fetch
- Crawl URL
- Firecrawl Scrape — Cần API key
- Jina Reader
- HTTP Request (GET)
- JSON Navigator
- HTTP Requests Toolkit
- Playwright Browser
- Markdown to HTML

### Năng suất

- GitHub — Cần API key
- GitLab — Cần API key
- Office 365 — Cần API key
- Gmail — Cần API key
- Google Calendar — Cần API key
- Telegram Send Message — Cần API key
- Zalo
- Notify Operators (Push)

### MCP Server

- N8N — Cần API key
- WordPress (Royal MCP)
- GitHub — Cần API key
- Slack — Cần API key
- Google Drive — Cần API key
- Notion — Cần API key
- Custom MCP Server

### Drive

- Drive Docs
- Drive Mindmap
- Drive Script Storyboard
- Drive Tables

### Tích hợp

- WordPress
- Viettel Post
- KiotViet
- ERPNext / Frappe

- Thêm các bộ công cụ Composio, dùng key Composio của bạn
- Mọi HTTP API thành công cụ webhook
- Mọi MCP server qua URL

## Mỗi loại cần gì

Các trường, tùy chọn và giới hạn — trước khi bạn đăng ký.

### Các loại công cụ

- Dựng sẵn — chọn từ kho
- Webhook — mọi HTTP endpoint
- Code — một hàm Python trong sandbox
- MCP — mọi MCP server
- Agent làm công cụ — một agent khác trong workspace

### Công cụ webhook

- GET, POST, PUT, PATCH và DELETE
- Không xác thực, bearer token hoặc API key
- Header tùy chỉnh
- Schema JSON đầu vào để agent điền

### Công cụ code

- Python, sửa ngay trên trình duyệt
- Chạy trong sandbox có timeout
- Tắt internet trừ khi bạn cho phép
- Schema đầu vào như mọi công cụ khác

### MCP server

- Kết nối qua URL, bằng SSE hoặc Streamable HTTP
- Xác thực bearer token và header tùy chỉnh
- Liệt kê từng công cụ được phát hiện
- Bật hoặc tắt từng cái
- Duyệt theo từng công cụ, hoặc cho tất cả

### Tích hợp

- Viettel Post — cước phí, vận đơn, trạng thái và in nhãn
- KiotViet — sản phẩm, tồn kho, khách hàng, đơn hàng và hóa đơn
- WordPress — bài viết, trang, media, và sản phẩm WooCommerce
- ERPNext / Frappe — các chứng từ trên site của bạn
- Bộ công cụ Composio, dùng key Composio của bạn

### Quyền & an toàn

- Cấp theo từng agent, hoặc toàn cục cho tất cả
- Tắt mà không cần xóa
- Người duyệt trước khi công cụ được chọn chạy
- Cache kết quả, tự bỏ qua khi bật duyệt
- Mọi lời gọi đều nằm trong nhật ký chạy

## Tự nối công cụ bằng tay và dùng kho

Cùng một tích hợp, hai cách làm.

| Khi chưa có 2pm.space | Khi có 2pm.space |
| --- | --- |
| Mỗi API mới là thêm code, thêm một lần deploy, và một prompt giải thích nó. | Mô tả endpoint một lần; agent nào được cấp đều gọi được. |
| Công cụ có thể xóa dữ liệu chạy tự do như công cụ chỉ đọc. | Bắt duyệt với công cụ có ghi dữ liệu, và lượt chạy sẽ chờ người. |
| Mỗi MCP server mang theo mọi công cụ nó có, muốn hay không. | Bật hoặc tắt từng công cụ được phát hiện, từng cái một. |
| Không ai chắc agent nào chạm được tới hệ thống nào. | Trang của mỗi công cụ liệt kê các agent được cấp. |

## Câu hỏi về công cụ

Những điều mọi người hay hỏi trước khi kết nối hệ thống đầu tiên.

### Có bao nhiêu công cụ dựng sẵn?

Hiện có sáu mươi, chia thành tìm kiếm, tri thức, tính toán, dữ liệu, AI và đa phương tiện, tài chính, tiện ích, năng suất, MCP server, Drive và tích hợp — danh sách đầy đủ có ngay trên trang này. Ngoài ra, mọi HTTP API, hàm Python hay MCP server đều có thể thành công cụ.

### Có cần API key không?

Một số công cụ cần key của nhà cung cấp — Tavily, Serper, Gmail, GitHub và các công cụ có biểu tượng chìa khóa. Nhiều công cụ chạy không cần key, như DuckDuckGo, Wikipedia, ArXiv, Web Fetch, trình duyệt Playwright và các công cụ Drive.

### Công cụ có thể chờ duyệt trước khi chạy không?

Có. Bật Require human approval cho những công cụ cần người xác nhận — thường là công cụ gửi, ghi hoặc xóa — và lượt chạy của agent sẽ dừng cho đến khi có người duyệt lời gọi. Với MCP server hay tích hợp, việc duyệt được đặt theo từng công cụ được phát hiện.

### Tôi kết nối MCP server của riêng mình được không?

Được. Thêm một công cụ MCP với URL, transport và thông tin xác thực của server; các công cụ nó cung cấp sẽ được phát hiện và liệt kê, và bạn bật tắt từng cái. Kho đã có sẵn cấu hình cho N8N, Slack, Notion, GitHub, Google Drive và WordPress.

### Agent này dùng agent khác làm công cụ được không?

Được. Tạo một Agent as tool và chọn agent. Agent nào được cấp đều có thể giao việc cho nó và dùng câu trả lời, trong khi nó vẫn giữ prompt, model và công cụ riêng.

### Viettel Post và KiotViet nằm ở đâu?

Đó là các tích hợp dựng sẵn. Kết nối tài khoản một lần là agent có các thao tác của chúng dưới dạng công cụ — báo cước, tạo vận đơn, kiểm tra tồn kho, tra cứu đơn hàng.

## Trao cho agent đúng công cụ

Bắt đầu từ kho có sẵn. Thêm API của riêng bạn khi cần.

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
