<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/vi/security; edits here are overwritten by the next export. -->

# Bảo mật & quản trị cho AI agent

> Phân quyền theo từng tài nguyên, vai trò tùy chỉnh, quyền truy cập theo nhóm và theo kênh, mã hoá thông tin xác thực, guardrail cho đầu ra của agent, nhật ký audit từng lượt chạy và sao lưu theo lịch.

[2pm.space/vi/security](https://2pm.space/vi/security) · [English](../security.md) · **Tiếng Việt** · [中文](../zh/security.md) · [日本語](../ja/security.md) · [한국어](../ko/security.md) · [ไทย](../th/security.md) · [Français](../fr/security.md) · [ລາວ](../lo/security.md)

*Vai trò · Chia sẻ · Audit · Sao lưu*

## Cấp cho mỗi người đúng quyền họ cần

Phân quyền theo từng tài nguyên, quyền truy cập kênh theo từng nhóm, thông tin xác thực được mã hoá, guardrail cho những gì agent được nói, và nhật ký cho mọi lượt chạy — để việc đưa AI ra tiếp khách là quyết định bạn có thể bảo vệ.

[Bắt đầu miễn phí](https://2pm.space/signup)

## Quản trị vẫn vững khi có thêm đội thứ hai

Những lớp kiểm soát quyết định AI có đáng tin để tiếp một cuộc trò chuyện thật với khách hay không.

### Vai trò đúng với công việc

Có sẵn Chủ sở hữu, Quản trị viên và Thành viên, cùng vai trò tùy chỉnh khi những vai trò đó chưa phù hợp. Quyền được cấp theo từng tài nguyên và từng thao tác, nên “trực hộp thư nhưng không bao giờ thấy phần thanh toán” là một vai trò chứ không phải một quy tắc ai đó phải nhớ.

### Chia sẻ theo từng tài nguyên

Một agent, tài liệu, thư mục, công cụ hay board có danh sách truy cập riêng bên trên vai trò — xem, dùng, chỉnh sửa hoặc quản trị (với tài liệu: xem, bình luận hoặc chỉnh sửa), cấp cho một thành viên, một nhóm hoặc tất cả mọi người.

### Tách biệt theo kênh

Kênh mặc định là đóng. Giao một Page, một tài khoản Zalo hay một widget cho một thành viên, một vai trò hoặc một nhóm ở mức Xem, Trả lời, Cấu hình hoặc Toàn quyền, và hộp thư họ mở chỉ chứa những hội thoại đó — đúng thứ một agency cần, và đúng thứ một đội hỗ trợ phụ trách một sản phẩm cần.

### Bí mật luôn được giữ kín

Thông tin xác thực cơ sở dữ liệu, token kênh và auth header của endpoint được mã hoá khi lưu trữ và không bao giờ gửi về trình duyệt. Biểu mẫu chỉ báo rằng bí mật đã được cấu hình; không hiển thị lại giá trị.

### Guardrail cho những gì agent được nói

Chính sách áp lên những gì đi vào và đi ra khỏi agent, kèm audit cho biết guard nào đã kích hoạt, nó đã làm gì và vì sao — để một câu trả lời bị chặn là một bản ghi, không phải một bí ẩn.

### Nhật ký cho mọi loại lượt chạy

Lượt thực thi agent kèm lượt gọi công cụ và chi phí, lượt chạy tác vụ theo lịch, lượt gửi webhook, tin chăm sóc đã gửi, lỗi nền tảng và mọi thay đổi quyền truy cập — mỗi loại có danh sách riêng thay vì dồn chung một luồng.

## Những gì bạn kiểm soát được

Quyền truy cập, xử lý dữ liệu, khả năng quan sát và tính liên tục.

### Danh tính và quyền truy cập

- Vai trò hệ thống Chủ sở hữu, Quản trị viên và Thành viên
- Vai trò tùy chỉnh, cấp quyền theo từng tài nguyên, từng thao tác
- Nhóm, có trưởng nhóm và thành viên
- 55 loại tài nguyên, 201 quyền
- Lời mời, và thu hồi quyền truy cập từ một màn hình

### Chia sẻ cấp tài nguyên

- Xem, dùng, chỉnh sửa, quản trị — với tài liệu: xem, bình luận, chỉnh sửa
- Cấp cho một thành viên, một nhóm hoặc cả workspace
- Áp dụng cho agent, tài liệu, thư mục và công cụ
- Áp dụng cho kho tri thức, kênh, nguồn dữ liệu và board
- Tài liệu chia sẻ qua link, với cấp quyền bạn chọn

### Xử lý dữ liệu

- Cô lập workspace trên mọi yêu cầu
- Thông tin xác thực mã hoá khi lưu trữ
- Bí mật không bao giờ gửi về trình duyệt
- Kết nối cơ sở dữ liệu chỉ đọc khi bạn muốn
- Dữ liệu khách hàng bên ngoài được truy xuất, không lặng lẽ sao chép

### Khả năng quan sát

- Nhật ký thực thi từng lượt chạy, kèm token và chi phí
- Audit guardrail — guard nào đã kích hoạt, và nó đã làm gì
- Lịch sử lượt chạy theo lịch
- Nhật ký gửi webhook
- Nhật ký lỗi nền tảng, và nhật ký quyền truy cập cho mọi thay đổi vai trò và chia sẻ

### Sao lưu và liên tục

- Sao lưu theo yêu cầu và theo lịch
- Khôi phục trở lại workspace
- Xuất dữ liệu workspace
- Dung lượng lưu trữ hiển thị theo từng workspace

### Truy cập bằng lập trình

- API key giới hạn theo quyền của người tạo
- Cùng key đó xác thực MCP endpoint
- Thu hồi được từng key
- Nhật ký từng lượt gọi, phân bổ chi phí

## Điều gì thay đổi khi phân quyền chi tiết

Những cách chữa cháy không còn cần đến.

| Khi chưa có 2pm.space | Khi có 2pm.space |
| --- | --- |
| Ai đăng nhập được cũng thấy mọi thứ, vì quyền truy cập kiểu được tất cả hoặc không gì cả | Phân quyền theo từng tài nguyên, từng thao tác, cộng với danh sách truy cập cho từng tài nguyên |
| Giao cho cộng tác viên một Page đồng nghĩa với giao cả workspace | Quyền truy cập kênh cấp cho một thành viên, một vai trò hoặc một nhóm |
| API token dán vào file cấu hình rồi chuyền tay khắp đội | Thông tin xác thực mã hoá khi lưu trữ, không bao giờ hiển thị lại sau khi lưu |
| Một câu trả lời AI bị sai, và không cách nào xem nó đã làm gì hay tốn bao nhiêu | Nhật ký từng lượt chạy với mọi lượt gọi công cụ, mọi kết quả guardrail và chi phí từng bước |
| Bản sao lưu chỉ tồn tại nếu có ai đó nhớ chạy | Sao lưu theo lịch, có khôi phục vào workspace |

## Câu hỏi về bảo mật và quản trị

Những điều quản trị viên kiểm tra trước khi mời đội thứ hai vào.

### Phân quyền chi tiết đến mức nào?

Quyền được cấp theo từng loại tài nguyên và từng thao tác — xem agent, tạo công cụ, khôi phục bản sao lưu, bắt đầu lượt huấn luyện: 55 loại tài nguyên với 201 quyền, mỗi quyền cấp riêng. Có sẵn ba vai trò (Chủ sở hữu, Quản trị viên, Thành viên) và bạn có thể tự định nghĩa vai trò riêng, bắt đầu trống hoặc sao chép từ một vai trò có sẵn, nên “trả lời được hộp thư nhưng không được đụng vào thanh toán” là một vai trò chứ không phải một ngoại lệ ai đó phải nhớ.

### Tôi có thể chia sẻ một agent hay một tài liệu mà không chia sẻ cả workspace không?

Có. Bên trên quyền theo vai trò, từng tài nguyên — agent, tài liệu, thư mục, công cụ, kho tri thức, kênh, nguồn dữ liệu và board — đều có danh sách truy cập riêng. Bạn cấp cho một thành viên, một nhóm hoặc cả workspace một mức trên đúng thứ đó: xem, dùng, chỉnh sửa hoặc quản trị với agent, công cụ hay board; xem, bình luận hoặc chỉnh sửa với tài liệu hay thư mục.

### Agency có thể cho đội của khách hàng chỉ truy cập kênh của chính họ không?

Đó chính là mục đích của quyền truy cập kênh. Kênh mặc định là đóng: một Page, một tài khoản Zalo hay một widget được giao cho một thành viên, một vai trò hoặc một nhóm ở mức Xem, Trả lời, Cấu hình hoặc Toàn quyền, và hộp thư họ mở chỉ chứa hội thoại từ những gì họ được giao. Chủ sở hữu và quản trị viên thấy mọi kênh. Để trả lời khách, một người cần đủ hai nửa — quyền Trả lời trên vai trò và mức Trả lời trên kênh đó.

### Thông tin xác thực và API token được lưu ở đâu?

Được mã hoá khi lưu trữ, và không bao giờ gửi ngược về trình duyệt. Biểu mẫu cài đặt của một tích hợp đã kết nối chỉ báo rằng bí mật đã được cấu hình; không hiển thị lại giá trị. Điều này áp dụng như nhau cho kết nối cơ sở dữ liệu, token kênh và auth header của các endpoint bổ sung dữ liệu.

### Tôi xem được gì về những việc AI thực sự đã làm?

Mọi lượt chạy đều được ghi nhật ký từ đầu đến cuối: tin nhắn, các công cụ đã gọi và kết quả trả về, token và chi phí mỗi bước, guardrail nào đã kích hoạt và nó đã xử lý thế nào. Có nhật ký riêng cho lượt chạy theo lịch, lượt gửi webhook, tin chăm sóc đã gửi và lỗi nền tảng.

### Tôi có lấy dữ liệu ra được không, và có xoá được không?

Có thể sao lưu theo yêu cầu hoặc theo lịch và khôi phục vào workspace. Xoá dữ liệu là thao tác có sẵn chứ không phải gửi yêu cầu hỗ trợ: thành viên có thể tự xoá tài khoản của mình ngay trên website, và dữ liệu workspace bị xoá cùng workspace.

## Thiết lập đúng theo cách đội bạn vận hành

Vai trò, nhóm và quyền truy cập theo từng tài nguyên có sẵn ngay từ workspace đầu tiên. Bắt đầu miễn phí, không cần thẻ tín dụng.

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
