<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/vi/agent-builder; edits here are overwritten by the next export. -->

# Công cụ xây dựng AI Agent với canvas quy trình trực quan

> Xây AI agent từ một prompt hoặc thành cả một quy trình: 16 loại node cho tra cứu, công cụ, vòng đánh giá, duyệt bởi người và rẽ nhánh. Chạy thử có nhật ký từng bước, phiên bản canvas, và triển khai lên hộp thư, theo lịch hoặc qua MCP client.

[2pm.space/vi/agent-builder](https://2pm.space/vi/agent-builder) · [English](../agent-builder.md) · **Tiếng Việt** · [中文](../zh/agent-builder.md) · [日本語](../ja/agent-builder.md) · [한국어](../ko/agent-builder.md) · [ไทย](../th/agent-builder.md) · [Français](../fr/agent-builder.md) · [ລາວ](../lo/agent-builder.md)

*Agent Builder · Canvas quy trình · Chạy thử*

## Agent làm được việc, không chỉ trả lời một prompt

Bắt đầu bằng một prompt, hoặc vẽ công việc thành quy trình: tìm đúng tài liệu, suy luận và gọi công cụ, kiểm tra câu trả lời, hỏi người khi cần, rồi trả lời. Mỗi lượt chạy cho thấy từng bước đã làm gì, tốn bao nhiêu và vì sao.

[Bắt đầu miễn phí](https://2pm.space/signup)

## Từ ý tưởng đến agent chạy được trong ba bước

Vẽ ra, trang bị, đưa vào đúng chỗ làm việc.

1. **Vẽ công việc** — Chọn Simple cho một prompt, hoặc Agentic để bày công việc thành các node trên canvas — tra cứu, suy luận, kiểm tra, rẽ nhánh — nối từ trái sang phải.
2. **Trang bị cho agent** — Gắn công cụ, kỹ năng, tri thức và bộ nhớ cho agent hoặc cho riêng một node, và đặt guardrail mà mọi tin nhắn đều phải đi qua.
3. **Đưa vào làm việc** — Chạy thử ngay trên canvas, rồi nối agent vào một kênh hộp thư, một lịch chạy, dùng làm công cụ cho agent khác, hoặc cho một MCP client.

## Hơn cả một prompt có gắn công cụ

Một canvas cho những việc mà một prompt tự mình không làm nổi.

### Simple hoặc Agentic

Agent đơn giản là một lần gọi model với system prompt của bạn — hợp cho hỏi đáp, dịch và tóm tắt. Agent agentic là một đồ thị các node, cho những việc cần nhiều bước và một quyết định giữa các bước.

### Mười sáu loại bước

Agent, Crew, Run Agent, Code, Knowledge và Skill Retrieval, Drive Action, Condition, Parallel, Loop, Evaluation, Human Review, Message, Send — mỗi loại là một thẻ bạn kéo lên canvas và nối với bước kế tiếp.

### Tự kiểm tra việc mình làm

Node Evaluation chấm câu trả lời bằng luật hoặc bằng LLM rồi chuyển hướng: Pass thì đi tiếp, Retry thì trả về agent làm lại, tối đa số lần bạn cho phép.

### Có người ở chỗ quan trọng

Node Human Review dừng lượt chạy cho đến khi có người duyệt hoặc từ chối, còn node Message có thể hỏi khách thêm thông tin qua form hoặc nút bấm trước khi quy trình đi tiếp.

### Công cụ, kỹ năng và tri thức

Sáu mươi công cụ dựng sẵn, HTTP API và Python của riêng bạn, MCP server, và cả agent khác làm công cụ. Kỹ năng có thể nạp vào mọi prompt hoặc chỉ khi câu hỏi khớp — để một thư viện lớn không tốn token ở mọi lượt gọi.

### Chạy thử, lần vết, quay lại

Chạy quy trình ngay trên canvas và xem đầu ra, token, chi phí của từng node. Lưu phiên bản canvas, và khôi phục khi một thay đổi không ổn.

## Trên canvas có gì

Mọi loại node, danh mục model và mọi nơi agent có thể chạy.

### Suy luận & hành động

- Agent — model, prompt và công cụ riêng, trong vòng lặp suy luận và hành động
- Crew — một crew CrewAI gồm nhiều agent và nhiệm vụ
- Run Agent — gọi một agent bạn đã xây
- Code — Python hoặc Bash trong sandbox, không tốn LLM

### Điều khiển luồng

- Start — nơi tin nhắn đi vào
- Condition — rẽ nhánh theo luật, không tốn LLM
- Parallel — chạy mọi nhánh ra cùng lúc
- Loop và Exit Loop — lặp qua danh sách hoặc N lần

### Kiểm tra & con người

- Evaluation — luật hoặc LLM chấm, rồi Pass hoặc Retry
- Human Review — dừng chờ duyệt hoặc từ chối
- Message — một tin nhắn, form hoặc nút bấm
- Send — nhắn cho khách rồi đi tiếp

### Tri thức & dữ liệu

- Knowledge Retrieval — tìm theo ngữ nghĩa, từ khóa hoặc kết hợp
- Skill Retrieval — khớp kỹ năng không cần bước LLM
- Drive Action — tạo, đọc hoặc cập nhật tài liệu, bảng, sơ đồ tư duy và storyboard
- Bộ nhớ giữ lại giữa các cuộc hội thoại, và bộ nhớ workspace dùng chung cho mọi agent

### Model

- Anthropic, OpenAI, Google và DeepSeek
- Alibaba Qwen, Z.AI GLM, xAI và MiniMax
- Mỗi node Agent một model, không phải cả quy trình một model
- Trừ vào credit của workspace — không phải tự quản key nhà cung cấp

### Chạy ở đâu

- Kênh hộp thư: Messenger, Telegram, Zalo cá nhân, chat website
- Lịch trình, chạy định kỳ
- Một agent khác, dưới dạng công cụ
- MCP client như Claude Code và Cursor
- Playground, trước khi khách hàng nào nhìn thấy

## Ô nhập prompt và một agent builder

Cùng một việc, hai cách dựng.

| Khi chưa có 2pm.space | Khi có 2pm.space |
| --- | --- |
| Một prompt vừa tra cứu, suy luận, kiểm tra vừa trả lời — và không biết phần nào hỏng. | Mỗi việc là một node, và nhật ký chạy cho thấy từng node nhận gì, trả gì, tốn bao nhiêu. |
| Câu trả lời sai đi thẳng đến khách hàng. | Node Evaluation chặn lại và trả về làm lại trước khi ai kịp thấy. |
| Một thao tác rủi ro cần lập trình viên dựng bước phê duyệt. | Đặt node Human Review ngay trước nó, và lượt chạy sẽ chờ một cái gật đầu. |
| Một thay đổi làm hỏng agent là phải dựng lại theo trí nhớ. | Khôi phục phiên bản canvas từ trước lúc thay đổi. |

## Câu hỏi về Agent Builder

Những điều mọi người hay hỏi trước khi dựng quy trình đầu tiên.

### Có cần biết lập trình để xây agent không?

Không. Agent đơn giản là một biểu mẫu: model, prompt, công cụ. Agent agentic được vẽ trên canvas bằng cách kéo node và nối chúng lại. Code là tùy chọn — node Code chạy Python hoặc Bash khi bạn muốn một bước được làm mà không cần model.

### Agent đơn giản và agent agentic khác nhau thế nào?

Agent đơn giản gọi model một lần với system prompt cùng công cụ và tri thức bạn gắn vào. Agent agentic chạy một đồ thị: mỗi node làm một việc — tra cứu, suy luận, kiểm tra, rẽ nhánh, lặp, hỏi người — và các cạnh quyết định bước tiếp theo.

### Agent dùng được những model nào?

Danh mục gồm Anthropic, OpenAI, Google, DeepSeek, Alibaba (Qwen), Z.AI (GLM), xAI và MiniMax, và trên canvas agentic mỗi node Agent tự chọn model riêng. Chi phí trừ vào credit của workspace, nên không phải quản lý key của nhà cung cấp.

### Làm sao chạy thử agent trước khi khách hàng thấy?

Chạy ngay trên canvas hoặc trong Playground. Mỗi lượt chạy đều được ghi lại với đầu vào, đầu ra, token, chi phí và lời gọi công cụ của từng bước, nên bạn thấy câu trả lời sai ở đâu và sửa đúng node đó thay vì sửa cả prompt.

### Nhiều người có cùng chỉnh một agent được không?

Được. Canvas đồng bộ thời gian thực và hiện ai đang cùng mở, còn phiên bản canvas giúp lưu một trạng thái chạy tốt và khôi phục về sau.

### Xây xong, agent chạy ở đâu?

Trên một kênh hộp thư — Messenger, Telegram, Zalo cá nhân hoặc chat website — theo lịch, làm công cụ cho agent khác gọi, hoặc từ một MCP client như Claude Code hay Cursor.

## Xây agent đúng với việc bạn cần

Bắt đầu bằng một prompt. Nâng thành quy trình khi công việc đòi hỏi.

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
