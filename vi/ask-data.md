<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/vi/ask-data; edits here are overwritten by the next export. -->

# Chat với cơ sở dữ liệu — phân tích bằng AI & BI Board

> Kết nối PostgreSQL, MySQL, Redshift, ClickHouse, Snowflake hoặc BigQuery, định nghĩa chỉ số một lần, rồi để đội của bạn đặt câu hỏi bằng ngôn ngữ đời thường — mỗi câu trả lời đều kèm câu SQL và biểu đồ.

[2pm.space/vi/ask-data](https://2pm.space/vi/ask-data) · [English](../ask-data.md) · **Tiếng Việt** · [中文](../zh/ask-data.md) · [日本語](../ja/ask-data.md) · [한국어](../ko/ask-data.md) · [ไทย](../th/ask-data.md) · [Français](../fr/ask-data.md) · [ລາວ](../lo/ask-data.md)

*6 loại cơ sở dữ liệu và kho dữ liệu*

## Hỏi cơ sở dữ liệu một câu, nhận câu trả lời kiểm chứng được

Kết nối Postgres, BigQuery, Snowflake hoặc ClickHouse, định nghĩa chỉ số một lần, rồi để bất kỳ ai trong đội hỏi bằng ngôn ngữ đời thường. Mỗi câu trả lời đều kèm biểu đồ, bảng và câu SQL đã chạy.

[Bắt đầu miễn phí](https://2pm.space/signup)

## Kết nối với cơ sở dữ liệu bạn đang dùng

Sáu engine, từ Postgres trên máy chủ của bạn đến một project BigQuery. Chọn loại, dán thông tin đăng nhập, chọn bảng — kết nối được kiểm tra trước khi lưu.

- **PostgreSQL** — Host, cổng 5432, chế độ SSL
- **MySQL** — Host, cổng 3306, chế độ SSL
- **ClickHouse** — Host, cổng HTTP 8123
- **Snowflake** — Account, warehouse và schema
- **BigQuery** — Khoá service account và location
- **Redshift** — Endpoint cluster, cổng 5439

- Thông tin đăng nhập được mã hoá khi lưu, không bao giờ gửi lại trình duyệt
- Chế độ chỉ đọc: chỉ câu lệnh SELECT được chạy
- Chỉ mô hình hoá những bảng bạn chọn

## Từ chuỗi kết nối đến board

Phần mô hình hoá là bản nháp đầu tiên để bạn chỉnh sửa, không phải một dự án phải lên lịch.

1. **Kết nối cơ sở dữ liệu** — Trỏ tới PostgreSQL, MySQL, Redshift, ClickHouse, Snowflake hoặc BigQuery. Thông tin xác thực được mã hoá khi lưu trữ, và kết nối có thể đặt chế độ chỉ đọc để không gì ngoài SELECT chạm tới được.
2. **Tinh chỉnh mô hình** — Schema được tự động đọc và tạo sẵn bản đầu tiên gồm cube, phép join và chỉ số. Ẩn những gì không ai nên truy vấn, đổi tên những gì chỉ người đặt mới hiểu, và thêm các chỉ số doanh nghiệp bạn thực sự báo cáo.
3. **Hỏi, rồi ghim lại** — Đặt câu hỏi bằng ngôn ngữ đời thường, kiểm tra câu SQL đằng sau câu trả lời, và ghim những câu đáng giữ lên một board mà đội bạn mở mỗi sáng.

## Tự phân tích dữ liệu mà không bịa số

Một lớp ngữ nghĩa nằm dưới các câu hỏi, để các câu trả lời luôn khớp với nhau.

### Hỏi bằng ngôn ngữ đời thường

Gõ câu hỏi như cách bạn hỏi đồng nghiệp. Câu trả lời trả về dưới dạng bảng và biểu đồ hợp với hình dạng của kết quả — kèm câu truy vấn đã chạy, để ai cũng kiểm tra được cách tính.

### Mô hình ngữ nghĩa, không phải đoán mò

Chỉ số, chiều dữ liệu và phép join được định nghĩa một lần rồi biên dịch vào mọi truy vấn. “Doanh thu” mang cùng một nghĩa trong mọi câu trả lời, và câu hỏi mà mô hình không diễn đạt được sẽ không lặng lẽ biến thành một phép join bịa ra.

### Câu hỏi đã kiểm chứng luôn đúng

Lưu một câu trả lời bạn đã kiểm tra làm ví dụ đã xác minh. Câu hỏi và câu SQL của nó được thêm vào các ví dụ mà mô hình đọc trước khi viết truy vấn, nên câu hỏi tương tự lần sau sẽ theo đúng cách bạn đã duyệt.

### Board dựng từ câu trả lời

Ghim bất kỳ câu trả lời nào lên board. Board có nhiều tab, bộ lọc dùng chung và khoảng ngày luôn tương đối — board lưu là “7 ngày qua” thì tháng sau vẫn là 7 ngày qua.

### SQL Lab cho phần còn lại

Có những câu hỏi gõ ra nhanh hơn giải thích. Tự viết SQL trên cùng mô hình ngữ nghĩa, lưu các truy vấn hay dùng, vẽ biểu đồ cho kết quả và ghim nó vào bảng.

### Chia sẻ số liệu, không chia sẻ mật khẩu

Board được chia sẻ chỉ hiện số liệu, không giao ra cơ sở dữ liệu phía sau. Quyền truy cập được cấp theo từng nguồn dữ liệu, và người xem nhận được một board chứ không phải một cửa sổ truy vấn.

## Kết nối với gì, bạn nhận được gì

Mọi thứ lớp mô hình hoá, board và cửa sổ SQL thực sự hỗ trợ.

### Cơ sở dữ liệu và kho dữ liệu

- PostgreSQL và MySQL
- Redshift và ClickHouse
- Snowflake và BigQuery
- Chọn bảng khi kết nối — mô hình chỉ đọc những bảng đó

### Lớp ngữ nghĩa

- Cube tạo từ schema của bạn, rồi tinh chỉnh
- Chỉ số và chiều tính toán do bạn định nghĩa
- Phép join được gợi ý từ khoá, do bạn xác nhận
- Cube dẫn xuất cho những dạng dữ liệu mà SQL thuần viết rất rối
- Ngữ cảnh kinh doanh và thuật ngữ mà mô hình đọc được

### Board và biểu đồ

- Nhiều tab trong một board
- Khoảng ngày tương đối luôn giữ tương đối
- Bộ lọc cấp board áp lên mọi ô
- Biểu đồ được chọn theo hình dạng của kết quả
- Chia sẻ qua link, ẩn nguồn dữ liệu

### Dành cho người viết SQL

- SQL Lab chạy trên cùng kết nối
- Các cặp câu hỏi và SQL đã kiểm chứng
- Phạm vi bảng — những gì mô hình được và không được thấy
- Giới hạn số dòng áp cho mọi truy vấn
- Làm mới schema khi kho dữ liệu thay đổi

### Sẵn sàng cho agent của bạn

- Agent có thể truy vấn cùng mô hình ngữ nghĩa
- Câu trả lời xuất hiện trong chat, hộp thư hoặc báo cáo định kỳ
- MCP endpoint cho client bên ngoài
- Ghi nhật ký từng lượt chạy: câu hỏi, truy vấn và chi phí

### Kiểm soát

- Quyền truy cập cấp theo từng nguồn dữ liệu
- Kết nối chỉ đọc
- Thông tin xác thực mã hoá khi lưu trữ, không bao giờ gửi về trình duyệt
- Chia sẻ board không kèm theo kết nối

## Vì sao các đội thôi chụp màn hình dashboard

Điều gì thay đổi khi số liệu tự trả lời.

| Khi chưa có 2pm.space | Khi có 2pm.space |
| --- | --- |
| Mọi câu hỏi về số liệu đều xếp hàng chờ chuyên viên phân tích, tuần sau mới có | Ai cũng hỏi được bằng ngôn ngữ đời thường và nhận câu trả lời, kèm câu SQL |
| Một LLM trỏ thẳng vào bảng thô, tự tin join nhầm hai cột | Truy vấn biên dịch từ mô hình ngữ nghĩa do bạn định nghĩa và kiểm tra được |
| “Doanh thu” trong file của kế toán mang một nghĩa, trong dashboard vận hành lại mang nghĩa khác | Mỗi chỉ số một định nghĩa, dùng chung cho mọi câu trả lời và mọi board |
| Dashboard lưu là “7 ngày qua” nhưng lặng lẽ mãi mãi chỉ là một tuần trong tháng Ba | Khoảng ngày tương đối luôn giữ tương đối |
| Chia sẻ một con số đồng nghĩa với chia sẻ mật khẩu cơ sở dữ liệu | Board được chia sẻ mà không kèm kết nối phía sau |

## Câu hỏi về hỏi đáp dữ liệu

Những điều đội dữ liệu kiểm tra trước khi trỏ vào môi trường production.

### Tôi có thể kết nối những cơ sở dữ liệu và kho dữ liệu nào?

PostgreSQL, MySQL, Redshift, ClickHouse, Snowflake và BigQuery. Kết nối có thể đặt chế độ chỉ đọc để không gì ngoài SELECT chạm tới được, và thông tin xác thực được mã hoá khi lưu trữ, không bao giờ gửi ngược về trình duyệt.

### Khác gì so với để LLM tự viết SQL thô?

Một model đoán tên bảng thô sẽ vô tư join nhầm hai cột rồi đưa bạn một con số sai với vẻ rất tự tin. Ở đây, câu hỏi chạy trên mô hình ngữ nghĩa: bạn định nghĩa chỉ số, chiều dữ liệu và phép join một lần, và mọi câu trả lời được biên dịch từ những định nghĩa đó. “Doanh thu” mang cùng một nghĩa trong mọi biểu đồ, và câu hỏi mà mô hình không diễn đạt được sẽ không lặng lẽ biến thành một truy vấn bịa ra.

### Tôi có phải mô hình hoá mọi thứ trước khi nhận được câu trả lời không?

Không. Schema được tự động đọc khi kết nối và bản đầu tiên gồm cube, phép join và chỉ số được tạo sẵn cho bạn. Sau đó bạn tinh chỉnh — ẩn những bảng không ai nên truy vấn, đổi tên những cột mà chỉ người tạo ra mới hiểu, và thêm các chỉ số doanh nghiệp bạn thực sự báo cáo.

### Tôi vẫn viết SQL được khi cần chứ?

Được. SQL Lab chạy SQL bạn tự viết trên cùng kết nối và mô hình ngữ nghĩa — lưu các truy vấn hay dùng, vẽ biểu đồ cho kết quả rồi ghim vào bảng, hoặc biến một truy vấn thành derived cube. Ví dụ đã xác minh đến từ chính ChatQL: lưu một câu trả lời bạn tin tưởng, và câu hỏi cùng câu SQL của nó sẽ định hướng các truy vấn cho những câu hỏi tương tự sau này.

### Tôi có thể biến câu trả lời thành dashboard không?

Mỗi câu trả lời đều trả về kèm bảng và biểu đồ do nền tảng chọn theo hình dạng của kết quả, và câu nào cũng ghim lên board được. Board chứa nhiều tab, có bộ lọc và khoảng ngày riêng, và có thể chia sẻ cho những người cần xem số liệu mà không phải cấp quyền vào cơ sở dữ liệu phía sau.

### Ai được xem dữ liệu nào?

Quyền truy cập được cấp theo từng nguồn dữ liệu, và board được chia sẻ không mang theo kết nối — người xem thấy board, không phải cửa sổ truy vấn. Kết nối chỉ đọc, giới hạn số dòng cho mọi truy vấn, và nhật ký từng lượt chạy ghi lại đã hỏi gì và tốn bao nhiêu được áp dụng xuyên suốt.

## Kết nối cơ sở dữ liệu và hỏi thử một câu

Bắt đầu miễn phí, không cần thẻ tín dụng, và kết nối chỉ đọc nên câu hỏi đầu tiên không thể làm hỏng gì.

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
