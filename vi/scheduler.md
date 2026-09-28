<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/vi/scheduler; edits here are overwritten by the next export. -->

# Lịch trình cho AI Agent — Chạy agent tự động theo lịch

> Lên lịch để AI agent tự chạy: một lần, hằng ngày, hằng tuần, hằng tháng hoặc cron, theo múi giờ của bạn. Chế độ Batch API rẻ khoảng một nửa, giới hạn số lượt và ngày hết hạn, cùng lịch sử mọi câu trả lời kèm token và chi phí.

[2pm.space/vi/scheduler](https://2pm.space/vi/scheduler) · [English](../scheduler.md) · **Tiếng Việt** · [中文](../zh/scheduler.md) · [日本語](../ja/scheduler.md) · [한국어](../ko/scheduler.md) · [ไทย](../th/scheduler.md) · [Français](../fr/scheduler.md) · [ລາວ](../lo/scheduler.md)

*Lịch trình · Agent chạy định kỳ*

## Agent có mặt đúng giờ, mọi lần

Nói cho agent làm gì và khi nào — báo cáo doanh số lúc 8:00, bản tổng hợp nội dung mỗi thứ Hai, rà soát chăm sóc khách mỗi tối. Agent tự chạy theo múi giờ của bạn, và lưu mọi câu trả lời ở nơi bạn đọc được.

[Bắt đầu miễn phí](https://2pm.space/signup)

## Đặt agent vào lịch

Chọn agent, đặt giờ, đọc kết quả.

1. **Chọn agent và việc cần làm** — Chọn agent và viết điều cần hỏi, mỗi dòng một tin nhắn — mỗi dòng được gửi và trả lời thành một mục riêng.
2. **Đặt thời điểm chạy** — Một lần, hằng ngày, hằng tuần vào những ngày bạn tích, hằng tháng vào một ngày, hoặc biểu thức cron — theo múi giờ bạn chọn.
3. **Xem agent đã làm gì** — Mỗi lượt chạy đều vào lịch sử của tác vụ với từng câu trả lời, token và chi phí. Chạy ngay, tạm dừng hoặc hủy ngay từ danh sách.

## Một lịch chạy biết mình đang chạy agent

Không phải cron job gọi webhook — mà là một lượt chạy có hội thoại, công cụ và nhật ký.

### Năm kiểu lịch

Một lần vào một ngày, hằng ngày vào một giờ, hằng tuần vào những ngày chọn, hằng tháng vào một ngày trong tháng, hoặc bất kỳ biểu thức cron nào. Mọi lịch đều theo múi giờ bạn đặt, không phải múi giờ của server.

### Kết quả đến đúng nơi cần

Agent chạy cùng công cụ của nó, nên báo cáo có thể gửi đi ngay khi viết xong: một tin Telegram vào nhóm bán hàng, một email, một thông báo đẩy cho đội vận hành, một dòng trong bảng Drive.

### Rẻ một nửa, khi việc chờ được

Chuyển agent đơn giản sang Batch API và các lượt chạy đi qua hàng đợi batch của nhà cung cấp — rẻ khoảng 50%, xong trong vòng 24 giờ. Dành cho model Anthropic và OpenAI.

### Nhớ qua các lượt, nếu bạn muốn

Mỗi lượt mở hội thoại mới, tiếp tục hội thoại gần nhất để agent nhớ lần trước, hoặc gửi vào một hội thoại cụ thể.

### Dừng khi bạn muốn

Đặt ngày hết hạn hoặc số lượt chạy tối đa, và chọn bao nhiêu tin nhắn chạy song song — từ một đến mười.

### Lượt nào cũng có hồ sơ

Mỗi lượt giữ trạng thái, giờ bắt đầu và kết thúc, cùng câu trả lời hoặc lỗi của từng tin nhắn kèm token và chi phí — cũng được gom trong Cài đặt › Nhật ký.

## Mọi tùy chọn lên lịch

Những gì hộp thoại Tạo tác vụ có, từng trường một.

### Lịch

- Một lần, vào một ngày giờ
- Hằng ngày vào một giờ
- Hằng tuần, vào những ngày bạn tích
- Hằng tháng, vào một ngày trong tháng
- Biểu thức cron tùy chỉnh
- Mọi múi giờ

### Thực thi

- Chạy ngay, 1–10 tin nhắn cùng lúc
- Batch API, rẻ khoảng 50%, trong vòng 24 giờ
- Batch cho agent đơn giản dùng model Anthropic hoặc OpenAI
- Agent có bước Human Review không lên lịch được

### Đầu vào & hội thoại

- Mỗi dòng một tin nhắn, mỗi tin một mục
- Hội thoại mới mỗi lượt
- Hoặc tiếp tục hội thoại gần nhất
- Hoặc một hội thoại cụ thể theo ID

### Giới hạn

- Ngày giờ hết hạn
- Số lượt chạy tối đa
- Đếm lượt ngay trong danh sách, ví dụ 6/12

### Điều khiển

- Chạy ngay
- Tạm dừng và tiếp tục
- Hủy
- Sửa hoặc xóa
- Tìm kiếm, lọc theo trạng thái hoặc chế độ

### Lịch sử & nhật ký

- Trạng thái của từng lượt và từng tin nhắn
- Toàn văn mỗi câu trả lời hoặc lỗi
- Token và chi phí theo tin nhắn và theo lượt
- Tab Scheduler Runs trong nhật ký workspace

## Cron và script so với Lịch trình

Cùng một báo cáo buổi sáng, hai cách làm.

| Khi chưa có 2pm.space | Khi có 2pm.space |
| --- | --- |
| Một cron job, một script và một server phải giữ sống — chỉ để hỏi một câu. | Chọn agent, viết câu hỏi, đặt giờ. |
| Một lượt chạy lỗi lúc 3 giờ sáng và một tuần sau bạn mới biết. | Trạng thái và lỗi của từng lượt nằm ngay trong lịch sử tác vụ. |
| Báo cáo nào cũng bắt đầu từ con số không. | Tiếp tục hội thoại gần nhất, và agent nhớ lần trước. |
| Trả giá đầy đủ cho việc mà đến mai mới cần. | Lượt chạy Batch API tốn khoảng một nửa. |

## Câu hỏi về Lịch trình

Những điều mọi người hay hỏi trước khi tự động hóa báo cáo đầu tiên.

### Tôi lên lịch được những gì?

Bất kỳ agent nào đang bật trong workspace. Bạn viết các tin nhắn agent sẽ nhận, mỗi dòng một tin, và mỗi lượt chạy sẽ gửi chúng rồi ghi lại câu trả lời.

### Kết quả đến tay tôi bằng cách nào?

Qua chính công cụ của agent. Gắn cho nó Telegram Send Message, Gmail hoặc Notify Operators và ghi trong tin nhắn nơi cần gửi kết quả. Mọi câu trả lời cũng được giữ trong lịch sử chạy của tác vụ.

### Chế độ Batch API là gì?

Chế độ này gửi các tin nhắn của một lượt qua hàng đợi batch của nhà cung cấp model thay vì trả lời ngay. Chi phí khoảng một nửa và xong trong vòng 24 giờ. Chế độ này dùng cho agent đơn giản với model Anthropic hoặc OpenAI; quy trình agentic cần thực thi nhiều lượt, nên luôn chạy ngay.

### Lịch dùng múi giờ nào?

Múi giờ bạn chọn trên tác vụ — mặc định là múi giờ trình duyệt. Giờ chạy hằng ngày, hằng tuần và hằng tháng đều tính theo múi giờ đó.

### Tôi có lên lịch cho agent có bước Human Review được không?

Không. Lượt chạy theo lịch không có ai để duyệt, nên hộp thoại sẽ không lên lịch cho agent có node Human Review trong quy trình.

### Tác vụ có tự dừng sau một số lượt không?

Có. Đặt số lượt chạy tối đa, ngày hết hạn, hoặc cả hai. Bạn cũng có thể tạm dừng, tiếp tục hoặc hủy tác vụ bất cứ lúc nào.

## Để agent tự giữ lịch

Xây một lần, đặt vào lịch, và đọc kết quả bên ly cà phê.

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
