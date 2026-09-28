<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/vi/customer-360; edits here are overwritten by the next export. -->

# Customer 360 — một hồ sơ khách hàng xuyên suốt mọi kênh

> Customer 360 ngay trong Hộp thư: mở một hội thoại là đã thấy tin nhắn của cùng người đó từ các kênh khác — khớp theo số điện thoại hoặc email — cạnh số điện thoại nhận diện được, khách hàng đã liên kết và dữ liệu trực tiếp từ hệ thống của bạn.

[2pm.space/vi/customer-360](https://2pm.space/vi/customer-360) · [English](../customer-360.md) · **Tiếng Việt** · [中文](../zh/customer-360.md) · [日本語](../ja/customer-360.md) · [한국어](../ko/customer-360.md) · [ไทย](../th/customer-360.md) · [Français](../fr/customer-360.md) · [ລາວ](../lo/customer-360.md)

*Mọi kênh, một hồ sơ*

## Customer 360, tự tổng hợp từ những gì đã diễn ra

Hội thoại từ mọi kênh, số điện thoại bắt được giữa cuộc chat và dữ liệu trực tiếp từ hệ thống của bạn gộp lại thành một góc nhìn khách hàng duy nhất — đội của bạn đọc nó, và agent của bạn trả lời dựa trên nó.

[Bắt đầu miễn phí](https://2pm.space/signup)

## Hồ sơ tự hình thành như thế nào

Không cần một dự án nhập liệu. Hồ sơ được suy ra từ những cuộc hội thoại bạn vẫn đang có.

1. **Kết nối các kênh** — Mỗi cuộc hội thoại đi qua hộp thư đều góp phần dựng hồ sơ: ai nhắn, từ đâu, về chuyện gì. Không phải điền thêm gì — hồ sơ có mặt vì các cuộc hội thoại có mặt.
2. **Thêm dữ liệu của riêng bạn** — Gắn một endpoint bổ sung dữ liệu, nhập từ bảng tính, hoặc đồng bộ từ một API nội bộ. Sau đó chọn một lần cho cả workspace: lịch sử hiện ngay trong hội thoại, trong tab Customer 360, hay không hiện.
3. **Làm việc với bức tranh toàn cảnh** — Đội của bạn trả lời với lịch sử ngay trước mắt, và agent của bạn trả lời với cùng ngữ cảnh đó — kể cả những phần nằm trong hệ thống của bạn chứ không phải của chúng tôi.

## Hồ sơ luôn cập nhật vì nó được suy ra

Không phải một biểu mẫu mà ai đó phải nhớ cập nhật.

### Một người, mọi kênh

Mở một hội thoại Messenger là đã thấy tin nhắn chat website và Zalo của cùng người đó, nối với nhau qua số điện thoại hoặc email chung. Không có gì được nối chỉ vì tên na ná — không có định danh chung thì hai hội thoại vẫn tách riêng, không bị đoán gộp.

### Thông tin liên hệ bạn không cần gõ

Số điện thoại khách viết giữa cuộc trò chuyện được nhận diện, loại trùng với những số bạn đã có, và gắn vào hội thoại — số của nhân viên và số trong tin trích dẫn được lọc ra chứ không bị tính vào.

### Hệ thống của bạn, ngay trong panel

Trỏ tới một endpoint do bạn quản lý. Chúng tôi gửi các định danh đang có; hệ thống của bạn trả về các mục dòng thời gian — đơn hàng, cuộc gọi, lượt xem web — hiển thị ngay trong hội thoại hoặc trong tab Customer 360, và không được sao chép vào cơ sở dữ liệu của chúng tôi trừ khi bạn bật lưu đệm.

### Ngữ cảnh agent dùng được

Bật lưu đệm cho một nguồn và bật ngữ cảnh bên ngoài, agent trả lời sẽ đọc từ bản lưu đệm đó — nên có thể trả lời về đơn hàng mà API nội bộ của bạn không phải nằm trên đường xử lý của từng tin nhắn.

### Mang theo khách hàng bạn đang có

Nhập từ bảng tính với cách ghép cột được ghi nhớ, hoặc đồng bộ từ một nguồn HTTP theo con trỏ để mỗi lần chạy tiếp tục từ chỗ lần trước dừng. Mỗi dòng được khớp theo mã khách hàng của chính bạn, nên lần nhập sau cập nhật chứ không tạo bản trùng.

### Chặn ở tầng cơ sở dữ liệu, không chỉ ở API

Hồ sơ khách hàng tuân theo hệ thống phân quyền của workspace và được áp ở tầng cơ sở dữ liệu, nên thành viên không có quyền sẽ không thể chạm tới dữ liệu bằng bất kỳ đường nào — kể cả truy vấn trực tiếp.

## Customer 360 gồm những gì

Những gì tự có, những gì bạn mang vào, và ai được phép xem.

### Bên cạnh mỗi hội thoại

- Tin nhắn của cùng người đó từ các kênh khác
- Số điện thoại nhận diện được, đã lọc sạch
- Khách hàng đã liên kết, kèm các đơn hàng gần đây
- Nhãn, ghi chú nội bộ và thuộc tính tùy chỉnh
- Bản tóm tắt hội thoại có cấu trúc

### Bổ sung dữ liệu từ hệ thống của bạn

- Một HTTP endpoint do bạn quản lý, GET hoặc POST
- Định danh được gửi: hội thoại, kênh, external id, số điện thoại, email, tên, thuộc tính
- Một lựa chọn hiển thị cho cả workspace: trong dòng, panel hoặc ẩn
- Giới hạn một nguồn cho hội thoại riêng hoặc hội thoại nhóm
- Auth header được mã hoá khi lưu trữ, không bao giờ gửi về trình duyệt

### Đưa khách hàng vào

- Nhập từ bảng tính, ghi nhớ cách ghép cột
- Nguồn HTTP ở chế độ kết nối hoặc đồng bộ
- Đồng bộ theo con trỏ, tiếp tục từ chỗ đã dừng
- Lịch sử đồng bộ kèm số lượng và lỗi
- Upsert theo external id của bạn, nên nhập lại là cập nhật

### Dành cho agent

- Bật ngữ cảnh bên ngoài cho từng nguồn
- Phục vụ từ cache, không nằm trên đường trả lời
- Bộ nhớ agent lưu về khách hàng
- Công cụ có thể thao tác trên hồ sơ

### Dành cho đội của bạn

- Danh sách khách hàng có tìm kiếm và bộ lọc
- Trang chi tiết cho từng khách hàng
- Liên kết hội thoại với một khách hàng, hoặc tạo mới, ngay từ panel liên hệ
- Các kênh khác của cùng người đó, ngay trong hội thoại bạn đang mở

### Kiểm soát

- Phân quyền, áp ở tầng cơ sở dữ liệu
- Quyền theo kênh vẫn áp dụng: lịch sử từ kênh mà nhân viên không mở được sẽ không hiện trong hội thoại của họ
- Dữ liệu bên ngoài được truy xuất, không lặng lẽ sao chép
- Tắt nguồn bổ sung dữ liệu mà không cần xoá

## Những gì đội của bạn không phải chắp vá nữa

Việc ghép nối thủ công biến mất khi hồ sơ tự tổng hợp.

| Khi chưa có 2pm.space | Khi có 2pm.space |
| --- | --- |
| Một khách nhắn trên ba kênh là ba người lạ với đội của bạn | Tin nhắn từ các kênh khác đã có sẵn trong hội thoại bạn mở |
| Số điện thoại được chép tay từ hội thoại sang bảng tính | Số điện thoại được tự động nhận diện, loại trùng và gắn vào hồ sơ |
| Lịch sử đơn hàng trong ERP, hội thoại trong hộp thư, và một agent không biết cả hai | Dữ liệu từ hệ thống của bạn hiện ngay trong hội thoại, và agent đọc được khi đã lưu đệm |
| Nhập CRM tạo ra một danh sách song song không ai đối chiếu | Dữ liệu nhập được khớp theo mã khách hàng của chính bạn, nên nhập lại là cập nhật chứ không nhân bản |
| Ai có tài khoản cũng đọc được mọi khách hàng | Hồ sơ có phân quyền, áp ở cả tầng cơ sở dữ liệu lẫn API |

## Câu hỏi về Customer 360

Những điều các đội hay hỏi trước khi kết nối hệ thống nội bộ.

### Điều gì khiến nó là góc nhìn 360 chứ không phải một danh sách liên hệ?

Nó được ghép lại chứ không phải gõ tay, và nằm ngay nơi bạn làm việc: mở một hội thoại là tin nhắn của cùng người đó từ các kênh khác — khớp qua số điện thoại hoặc email chung — đã có sẵn trong hội thoại, cạnh những số điện thoại nhận diện được, khách hàng đã liên kết cùng các đơn hàng gần đây, và những gì hệ thống của bạn báo về. Nó luôn mới vì được suy ra, chứ không phải vì ai đó nhớ cập nhật.

### Có hiển thị được dữ liệu từ CRM hay hệ thống đơn hàng của chúng tôi không?

Có. Bạn trỏ nó tới một HTTP endpoint do bạn quản lý. Chúng tôi gửi các định danh đang có — hội thoại, kênh, external id, số điện thoại, email, tên, thuộc tính tùy chỉnh — và endpoint của bạn trả về các mục dòng thời gian mà nó nhận ra: đơn hàng, cuộc gọi, lượt xem web. Mặc định không có gì được sao chép vào cơ sở dữ liệu của chúng tôi; dữ liệu chỉ được truy xuất và hiển thị. Một nguồn khách hàng ở chế độ kết nối còn có thể hiện tên, số điện thoại và email của người đó, đọc trực tiếp khi mở hội thoại.

### AI agent có dùng được dữ liệu bên ngoài đó khi trả lời không?

Chỉ khi bạn bật cho nguồn đó và giữ một bản lưu đệm của nó. Agent đọc ngữ cảnh bên ngoài từ bản lưu đệm thay vì bắt endpoint của bạn trả lời ở mỗi tin nhắn — nên một API nội bộ chậm hoặc bị giới hạn tần suất không bao giờ làm chậm câu trả lời cho khách.

### Tôi có nhập được khách hàng hiện có không?

Có — từ bảng tính với cách ghép cột bạn thiết lập một lần và được ghi nhớ, hoặc từ một nguồn HTTP đồng bộ theo con trỏ để mỗi lần chạy tiếp tục từ chỗ lần trước dừng. Mỗi dòng được khớp theo mã khách hàng của chính bạn, nên nhập lại sẽ cập nhật đúng những khách hàng đó thay vì thêm bản thứ hai.

### Ai được xem hồ sơ khách hàng?

Dữ liệu khách hàng được kiểm soát bởi hệ thống phân quyền của workspace, và việc chặn được áp ở cả tầng cơ sở dữ liệu lẫn API — thành viên không có quyền không thể đọc dữ liệu bằng bất kỳ đường nào. Quyền theo kênh được áp thêm bên trên: lịch sử từ kênh mà một nhân viên không mở được sẽ không bao giờ hiện trong hội thoại của họ.

### Chuyện gì xảy ra khi cùng một người nhắn từ hai kênh?

Tin nhắn ở kênh kia hiện ngay trong hội thoại bạn đang mở, khớp qua số điện thoại hoặc email chung, trong khi hai hội thoại vẫn tách riêng. Không có gì được đoán từ một cái tên na ná — không có định danh chung thì chúng vẫn tách biệt. Khi bạn liên kết hội thoại với một khách hàng, việc khớp sẽ theo liên kết đó thay vì theo số điện thoại. Nếu hai kênh hóa ra là cùng một tài khoản, có thể gộp cả kênh vào kênh kia.

## Nhìn khách hàng như một con người

Kết nối một kênh và hồ sơ tự bắt đầu hình thành. Bắt đầu miễn phí, không cần thẻ tín dụng.

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
