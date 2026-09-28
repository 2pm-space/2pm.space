<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/vi/fine-tuning; edits here are overwritten by the next export. -->

# Fine-tune model AI trên chính hội thoại của bạn

> Đánh giá câu trả lời của AI agent ngay trong hộp thư, sửa những câu chưa ổn, tinh chỉnh một model open-weight trên các cặp đó bằng LoRA, rồi cho agent dùng kết quả — trừ vào cùng số dư credit như mọi thứ khác.

[2pm.space/vi/fine-tuning](https://2pm.space/vi/fine-tuning) · [English](../fine-tuning.md) · **Tiếng Việt** · [中文](../zh/fine-tuning.md) · [日本語](../ja/fine-tuning.md) · [한국어](../ko/fine-tuning.md) · [ไทย](../th/fine-tuning.md) · [Français](../fr/fine-tuning.md) · [ລາວ](../lo/fine-tuning.md)

*LoRA trên model open-weight*

## Fine-tune model trên chính hội thoại của bạn

Đánh giá câu trả lời của agent trong hộp thư và sửa những câu chưa ổn, tinh chỉnh một model open-weight trên các cặp đó, rồi cho agent dùng kết quả — để giọng điệu bạn cứ phải giải thích đi giải thích lại trong prompt nằm luôn trong trọng số của model.

[Bắt đầu miễn phí](https://2pm.space/signup)

## Dataset, huấn luyện, agent

Ba bước, tất cả diễn ra ngay trong workspace mà model sẽ làm việc.

1. **Dựng dataset** — Chọn dataset huấn luyện trong một cuộc hội thoại ở hộp thư, rồi 👍 những câu trả lời của AI đáng giữ và cải thiện những câu chưa ổn. Mỗi cặp đều chờ bạn Đưa vào hoặc Loại bỏ trước khi có gì được gửi đi huấn luyện.
2. **Chọn model gốc và huấn luyện** — Chọn một model gốc open-weight, xem chi phí ước tính khi dataset đã được xuất, giữ siêu tham số mặc định hoặc chỉnh lại, rồi bắt đầu lượt chạy.
3. **Cho agent dùng** — Adapter huấn luyện xong xuất hiện trong ô Mô hình của agent, mục My Adapters. Cho một agent dùng nó, chạy lại tin nhắn thật của khách với agent đó bằng “Run with…” trong hộp thư, và giữ lại lựa chọn trả lời tốt hơn.

## Fine-tuning mà không cần hạ tầng riêng

Không console của nhà cung cấp, không đặt trước tài nguyên, không hợp đồng — dùng chung số dư credit như mọi thứ khác.

### Huấn luyện trên những câu trả lời bạn đã duyệt

Các cặp huấn luyện đến từ hộp thư của bạn: câu trả lời của AI bạn đã 👍, bản chỉnh bạn viết khi một câu trả lời chưa ổn, các episode điểm cao từ bộ nhớ của agent, và các cặp hỏi–đáp bạn tự thêm — thay vì những ví dụ bịa ra cho model bắt chước.

### Model nhỏ hơn mà vẫn đúng ý

Khi giọng điệu và từ vựng đã nằm trong trọng số, chúng thôi tốn token prompt ở mỗi lượt gọi — thường nghĩa là một model nhỏ hơn, nhanh hơn làm được việc trước đây cần model lớn.

### Có ước tính trước khi bắt đầu

Khi dataset đã được xuất, hộp thoại huấn luyện hiện chi phí ước tính và số token huấn luyện trước khi chạy. Lượt chạy được tính phí khi hoàn tất, trừ vào cùng số dư credit như mọi thứ khác — không hợp đồng riêng, không đặt trước tài nguyên.

### Chỉ là một lựa chọn, không phải một cuộc chuyển đổi

Adapter hoàn thành xuất hiện như một model mà agent có thể chọn, bên cạnh các nhà cung cấp hosted. Cho một agent dùng nó, so sánh, và giữ lại cái trả lời tốt hơn.

### Tác vụ theo dõi được

Dataset, lượt huấn luyện và adapter hoàn thành đều có danh sách riêng, hiện rõ trạng thái, model gốc và chi phí của từng lượt chạy thay vì bị chôn trong console của nhà cung cấp.

### Phân quyền riêng

Dữ liệu huấn luyện được tạo từ hội thoại thật của khách hàng, nên toàn bộ phần này có quyền truy cập riêng — kể cả danh sách hội thoại ứng viên — tách biệt với phần còn lại của workspace.

## Quy trình hỗ trợ những gì

Từ những cuộc hội thoại được đưa vào đến adapter mà agent của bạn gọi.

### Dataset

- Dựng từ các câu trả lời của AI được đánh giá và sửa trong hộp thư
- Mọi cặp đề xuất đều chờ Đưa vào hoặc Loại bỏ trước khi xuất
- Trang chi tiết dataset cho thấy dữ liệu sẽ được huấn luyện
- Dùng lại được cho nhiều lượt huấn luyện

### Model gốc

- Các họ open-weight: Llama, Qwen, Mistral và Mixtral
- Các bản distill DeepSeek R1 và gpt-oss
- Hiện số tham số của từng model
- Chi phí ước tính hiện khi dataset đã được xuất
- Danh sách chọn lọc các model gốc mà nhà cung cấp huấn luyện hỗ trợ tinh chỉnh

### Lượt huấn luyện

- Adapter LoRA, với giá trị mặc định hợp lý cho mọi siêu tham số
- Trạng thái và lịch sử tác vụ cho từng lượt
- Chi phí được ghi nhận theo từng lượt chạy
- Lỗi được báo rõ, không âm thầm thử lại mãi

### Triển khai

- Adapter xuất hiện như một nhà cung cấp model trong ô chọn model của agent
- Tính theo giá suy luận của model gốc, nhân với hệ số premium của adapter
- Agent nào trong workspace cũng dùng được
- Đổi được theo từng agent, từng node

### Kiểm soát

- Khoá phân quyền riêng, huấn luyện là một thao tác tách biệt
- Hội thoại ứng viên được bảo vệ bằng cùng khoá đó
- Số điện thoại và email được xoá trước khi file JSONL được tải lên nhà cung cấp huấn luyện Together AI
- Không gộp chung, cũng không dùng để huấn luyện bất cứ thứ gì khác

### Chi phí

- Cùng số dư credit với phần còn lại của nền tảng
- Không thuê bao, không tính phí theo đầu người
- Ước tính trước khi chạy, tính phí theo chi phí thực sau khi xong

## Model đã tinh chỉnh thay đổi điều gì

Chi phí và sự thiếu nhất quán thực ra đi đâu.

| Khi chưa có 2pm.space | Khi có 2pm.space |
| --- | --- |
| System prompt 2.000 token giải thích lại giọng điệu của bạn ở từng lượt gọi | Giọng điệu và từ vựng nằm trong trọng số, chỉ trả tiền một lần |
| Phải dùng model lớn nhất vì model nhỏ không giữ được đúng chất thương hiệu | Một model nhỏ đã tinh chỉnh và đúng ý, với chi phí mỗi lượt gọi chỉ bằng một phần nhỏ |
| Tự viết ví dụ huấn luyện giả lập cho một lĩnh vực mà bạn vốn đã có sẵn bản ghi hội thoại | Dataset dựng từ những câu trả lời của AI bạn đã đánh giá và sửa |
| Huấn luyện trong console của nhà cung cấp, tách rời khỏi nơi model được dùng | Dataset, lượt huấn luyện và adapter đang chạy nằm cùng workspace với agent |

## Câu hỏi về fine-tuning

Những điều các đội kiểm tra trước khi huấn luyện trên hội thoại của khách hàng.

### Fine-tuning mang lại gì mà một prompt tốt không làm được?

Prompt bảo model phải làm gì; fine-tune dạy nó cách bạn làm. Khi giọng điệu, từ vựng sản phẩm và hình mẫu của một câu trả lời tốt đã nằm trong trọng số, bạn thôi phải trả tiền cho chúng ở mỗi prompt — thường nghĩa là một model nhỏ hơn, rẻ hơn, nhanh hơn làm được việc trước đây cần model lớn.

### Dữ liệu huấn luyện lấy từ đâu?

Từ hộp thư của bạn. Chọn dataset huấn luyện trong phần cài đặt của một cuộc hội thoại, rồi đánh giá các câu trả lời của agent — câu nào được 👍 sẽ thành ứng viên — và dùng Cải thiện để viết lại câu trả lời lẽ ra phải như thế nào; bản chỉnh đó cũng thành một cặp huấn luyện. Các episode được bộ nhớ của agent chấm từ 8/10 trở lên có thể tự động đưa vào, và bạn có thể tự thêm các cặp hỏi–đáp. Câu trả lời do đội của bạn tự viết không được thu thập. Mỗi cặp đều chờ bạn Đưa vào trước khi được xuất, và vì đó là tin nhắn thật của khách, toàn bộ phần này có quyền truy cập riêng, tách khỏi phần còn lại của workspace.

### Tôi có thể huấn luyện những model gốc nào?

Chỉ model open-weight, vì model host sẵn như Claude hay GPT không thể tinh chỉnh bằng LoRA. Danh sách là tập chọn lọc các model mà nhà cung cấp huấn luyện hỗ trợ — Llama, Qwen, Mistral, Mixtral, các bản distill DeepSeek R1 và gpt-oss, từ 1B đến 120B tham số — mỗi model hiện kèm số tham số.

### Chi phí thế nào?

Huấn luyện tính theo mỗi triệu token với đơn giá của model gốc, kèm mức tối thiểu cho mỗi lượt của nhà cung cấp, và hộp thoại huấn luyện hiện chi phí ước tính khi dataset đã được xuất. Lượt chạy được tính phí khi hoàn tất, trừ vào cùng số dư credit như mọi thứ khác. Sau khi huấn luyện, adapter được tính theo giá suy luận của model gốc nhân với hệ số premium của adapter. Không có thuê bao và không tính phí theo đầu người — xem trang bảng giá để biết cách tính phí theo mức sử dụng.

### Dùng model đã huấn luyện như thế nào?

Nó xuất hiện trong ô Mô hình của agent, mục My Adapters, cạnh các nhà cung cấp host sẵn. Cho một agent dùng nó, chạy lại tin nhắn thật của khách bằng “Run with…” trong hộp thư, và giữ lại lựa chọn trả lời tốt hơn — đổi model chỉ là một lựa chọn trong danh sách, không phải một cuộc di chuyển.

### Dữ liệu huấn luyện của tôi có bị dùng để huấn luyện thứ gì khác không?

Không. Dataset dựng trong workspace của bạn huấn luyện một adapter thuộc về workspace của bạn, và nền tảng không gộp chung hay chia sẻ nó với workspace khác. Để huấn luyện, file JSONL đã xuất — đã xoá số điện thoại và email — được tải lên nhà cung cấp huấn luyện Together AI, nơi chạy lượt tinh chỉnh và phục vụ adapter mà agent của bạn gọi tới.

## Huấn luyện một model nói chuyện giống hệt bạn

Dựng dataset từ những câu trả lời agent của bạn đã đưa ra. Bắt đầu miễn phí — lượt huấn luyện được trừ vào số dư credit khi hoàn tất.

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
