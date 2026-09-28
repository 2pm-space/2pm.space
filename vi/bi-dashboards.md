<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/vi/bi-dashboards; edits here are overwritten by the next export. -->

# BI Dashboard dựng từ những câu hỏi bằng lời thường

> Ghim biểu đồ từ Ask Data hoặc SQL Lab lên các BI board dùng chung: nhiều tab, chín loại biểu đồ, bộ lọc cho cả board theo mô hình dữ liệu, so sánh kỳ và định dạng số — trên PostgreSQL, MySQL, BigQuery, Snowflake, Redshift hoặc ClickHouse.

[2pm.space/vi/bi-dashboards](https://2pm.space/vi/bi-dashboards) · [English](../bi-dashboards.md) · **Tiếng Việt** · [中文](../zh/bi-dashboards.md) · [日本語](../ja/bi-dashboards.md) · [한국어](../ko/bi-dashboards.md) · [ไทย](../th/bi-dashboards.md) · [Français](../fr/bi-dashboards.md) · [ລາວ](../lo/bi-dashboards.md)

*BI Dashboard · Board · SQL Lab*

## Dashboard bắt đầu từ một câu hỏi

Hỏi cơ sở dữ liệu bằng lời thường, ghim biểu đồ, và nó vào một board cả đội luôn mở — với các tab, bộ lọc chạm tới mọi ô, và so sánh với kỳ trước chỉ cách một cú bấm.

[Bắt đầu miễn phí](https://2pm.space/signup)

## Từ câu hỏi đến board trong ba bước

Hỏi, ghim, chia sẻ.

1. **Hỏi, hoặc tự viết SQL** — Ask Data trả lời bằng lời thường kèm biểu đồ. SQL Lab cho bạn tự viết truy vấn, hoặc để AI soạn từ một mô tả.
2. **Ghim lên board** — Ghim biểu đồ vào một board và một tab — mới hoặc có sẵn. Ô giữ lại truy vấn, không chỉ bức ảnh.
3. **Chia sẻ** — Chia sẻ board cho người cần xem. Bộ lọc nằm trong URL, nên đường link mở đúng góc nhìn bạn đang xem.

## Một board luôn trung thực

Mỗi ô là một truy vấn trên mô hình dữ liệu của bạn, không phải ảnh chụp của nó.

### Một định nghĩa doanh thu

Các ô truy vấn cùng mô hình ngữ nghĩa mà Ask Data dùng, nên một chỉ số định nghĩa một lần sẽ mang cùng ý nghĩa trên mọi biểu đồ và mọi board.

### Bộ lọc chạm tới mọi ô

Thêm bộ lọc board trên bất kỳ chiều nào mô hình đánh dấu lọc được — văn bản, chọn, chọn nhiều, ngày hoặc khoảng ngày — và mọi ô dùng chiều đó chạy lại. Ô nào không áp được thì nói rõ.

### Kỳ này so với kỳ trước

So sánh với kỳ trước, cùng kỳ năm trước hoặc một khoảng bạn chọn, và gom lại thời gian theo ngày, tuần, tháng, quý hoặc năm.

### Chín cách vẽ

Cột, thanh ngang, chồng, chồng 100%, đường, vùng, tròn, phân tán và thẻ một con số — với thiết lập trục, chú giải, nhãn dữ liệu và màu chuỗi cho từng ô.

### SQL Lab cho người cần chính xác

Viết CubeQL trên mô hình, xem SQL gốc mà nó biên dịch ra, lưu truy vấn, và biến truy vấn tốt thành một derived cube dùng lại được.

### Agent cũng dựng được board

Công cụ BI Board cho agent tạo board, thêm biểu đồ và đọc dữ liệu của một ô — và các thao tác đó cũng có trên MCP server của chúng tôi cho Claude Code hoặc Cursor.

## Board hỗ trợ những gì

Biểu đồ, định dạng, bộ lọc và thời gian — danh sách đầy đủ.

### Loại biểu đồ

- Cột và thanh ngang
- Chồng và chồng 100%
- Đường và vùng
- Tròn
- Phân tán
- Thẻ số

### Định dạng

- Số, tiền tệ, phần trăm hoặc byte
- Số thập phân, rút gọn K / M / B và dấu phân cách
- Tiền tố và hậu tố
- Tiêu đề trục, min, max và thang log
- Chú giải, nhãn dữ liệu và màu chuỗi
- Ghi đè định dạng của mô hình theo từng trường

### Bộ lọc

- Trên mọi chiều lọc được của mô hình
- Văn bản, chọn, chọn nhiều, ngày và khoảng ngày
- là, không là, chứa, bắt đầu bằng, kết thúc bằng
- Lưu trong URL để chia sẻ đúng góc nhìn
- Tìm trong các hạng mục của một ô

### Thời gian

- So sánh với kỳ trước
- Hoặc cùng kỳ năm trước
- Hoặc một khoảng tùy chọn
- Gom theo ngày, tuần, tháng, quý hoặc năm
- Khoảng ngày tương đối luôn giữ tương đối

### SQL Lab

- CubeQL trên mô hình ngữ nghĩa
- SQL gốc mà nó biên dịch ra
- AI soạn truy vấn từ một mô tả
- Truy vấn đã lưu
- Lưu truy vấn thành derived cube

### Board & chia sẻ

- Nhiều tab mỗi board, đổi tên và sắp xếp lại
- Bố cục kéo thả, đổi kích thước
- Làm mới một ô khi cần
- Chia sẻ với đồng đội
- Agent và MCP client dựng được board

## Báo cáo bảng tính so với board sống

Cùng những con số sáng thứ Hai, hai cách làm.

| Khi chưa có 2pm.space | Khi có 2pm.space |
| --- | --- |
| Thứ Hai nào cũng có người xuất, dán và vẽ lại biểu đồ. | Ô giữ lại truy vấn — làm mới là có số hiện tại. |
| Hai báo cáo, hai định nghĩa doanh thu. | Mọi ô đọc cùng một chỉ số từ mô hình. |
| "Làm giúp cho tháng trước được không?" nghĩa là thêm một báo cáo. | Đổi bộ lọc board, hoặc bật so sánh. |
| Yêu cầu một biểu đồ phải chờ người biết SQL. | Hỏi bằng lời thường và ghim câu trả lời. |

## Câu hỏi về BI Dashboard

Những điều mọi người hay hỏi trước khi dựng board đầu tiên.

### Board dùng được những cơ sở dữ liệu nào?

Mọi kết nối Ask Data hỗ trợ: PostgreSQL, MySQL, Redshift, ClickHouse, Snowflake và BigQuery. Board truy vấn chúng qua mô hình ngữ nghĩa của bạn.

### Biểu đồ lên board bằng cách nào?

Từ Ask Data hoặc SQL Lab: khi biểu đồ đã ưng ý, chọn Pin to board rồi chọn board và tab. Ô giữ lại truy vấn, không chỉ bức ảnh.

### Bộ lọc có áp lên mọi ô không?

Bộ lọc board áp lên mọi ô có truy vấn dùng chiều đó, và chạy lại ô. Ô nào không lọc được theo chiều đó sẽ ghi rõ ở tiêu đề, thay vì lặng lẽ hiện số chưa lọc.

### Có so sánh với tháng trước hay năm trước được không?

Được. Bật so sánh và chọn kỳ trước, cùng kỳ năm trước hoặc một khoảng tùy chọn; các ô có khoảng ngày sẽ hiện cả hai kỳ.

### Agent có dùng được board không?

Có. Công cụ BI Board cho agent tạo board, thêm biểu đồ và đọc dữ liệu của một ô, và các thao tác đó cũng có cho Claude Code hoặc Cursor qua MCP server.

## Đặt con số của bạn ở nơi ai cũng thấy

Kết nối cơ sở dữ liệu, đặt một câu hỏi, ghim câu trả lời.

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
