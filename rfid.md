## RFID – Phương thức giao dịch mới trong thế giới di động	
(Post 13/01/2006) 
Càng ngày các công nghệ mới càng hướng đến sự đơn giản, tiện lợi và một đặc trưng quan trọng nữa là khả năng không dây (wireless). Thiết bị không dây trong một thế giới di động làm cho con người được giải phóng, tự do và thoải mái hơn.
Một thiết bị chủ yếu trong hướng phát triển này là “Bộ định danh bằng tần số vô tuyến” – RFID (Radio Frequency Identifier), đây là thiết bị di động thụ động (Passive Mobile Device), được coi là một cuộc cách mạng trong các hệ thống nhúng và trong môi trường tương tác hiện nay.
Thực chất, thiết bị là một thẻ nhớ lưu trữ thông tin cá nhân và dữ liệu khác trong bảng mạch điện tử không cần năng lượng, hay nói chính xác hơn nó có một cơ chế thu nhận năng lượng từ các nguồn khác, do đó không cần pin hay nguồn nuôi trực tiếp nào. Điều này lý giải tại sao người ta gọi nó là thiết bị thụ động. Thiết bị bao gồm một ăng-ten và chip silicon (gồm cả bộ nhớ) được đóng gói chung. Thiết bị này thu nhận năng lượng từ các thiết bị chủ (hay còn gọi là thiết bị đọc-card reader). Các thiết bị đọc này luôn phát năng lượng bức xạ quanh nó, thẻ RFID hấp thụ năng lượng này và trao đổi thông tin với thiết bị đọc. Đặc biệt hơn, bộ đọc này còn có thể lưu thông tin lên chiếc thẻ kia. Đây là một cơ chế hết sức đặc biệt, nó đặt ra rất nhiều vấn đề về bảo mật đối với thẻ RFID.
Không chỉ khai thác thông tin, các thiết bị đọc còn có cơ chế ghi và theo dõi thông tin đã ghi trên thẻ - khả năng kiểm soát. Dựa trên đó ta có thể theo dõi được lộ trình của một chuyến hàng (xuất xứ hàng hóa, điểm xuất phát, qua các trạm hải quan nào, thời gian bắt đầu vận chuyển...).
Hãy tưởng tượng rằng trong cơ thể bạn được gắn thẻ RFID, bạn đi vào một sân bay có thiết bị đọc thẻ, mọi thông tin cá nhân, thậm chí là cả số ghế của chiếc vé mà bạn đã mua cũng được hiển thị trên màn hình máy tính, và cánh cửa check-in tự động mở, tất cả các thao tác này không làm bạn phải đứng chờ một giây nào bởi các thiết bị đã được kích hoạt khi bạn đi cách nó 5m!
Người ta đã mở rộng ứng dụng RFID bằng cách gắn thêm vào mỗi thẻ RFID một bộ cảm biến (sensor), một cơ chế bảo mật dữ liệu và một bộ nhớ điện tử. Tấm thẻ sẽ cung cấp năng lượng cho sensor, đồng thời làm nhiệm vụ lưu giữ thông tin mà sensor thu nhận được. Hãng lốp xe nổi tiếng Michelin đã ứng dụng thiết bị này để đo áp suất lốp xe và nhiệt độ khi xe di chuyển trên đường.
Do có các thao tác đọc ghi liên tục nên thiết bị này cần một giao thức để trao đổi dữ liệu với thiết bị đọc. Một thiết bị đọc có thể trao đổi dữ liệu với nhiều thẻ RFID cùng lúc do đó rất dễ xảy ra xung đột, vì vậy phải có một giao thức (hay giao tiếp) đặc biệt. Giải pháp đưa ra là sử dụng cửa sổ thời gian (time-window), mỗi thẻ RFID được phép truyền dữ liệu trong khoảng thời gian mà nó được cấp phát.

Mặt khác, để đảm bảo tính an toàn và riêng tư của mỗi thẻ RFID, người ta cũng đặt ra cơ chế kiểm soát như:
* Thông tin gì được lưu trong RFID?
* Ai có thể đọc được RFID của tôi?
* Ai có thể ghi vào bộ nhớ của tôi?
* Làm thế nào để tôi biết có người đọc dữ liệu của tôi?

Ưu và nhược điểm của RFID:
* Xử lý tự động
* Tiết kiệm năng lượng
* Chưa có chuẩn chung
* Chưa có giải pháp bảo mật hiệu quả.
* Tính riêng tư

Việc phổ biến RFID đối mặt với một số thách thức về mặt kỹ thuật và tài chính. Đó là:

Định hướng phát triển
Xử lý tín hiệu: Tín hiệu RFID dễ bị ngăn cản bởi các vật nhỏ bằng kim loại trong khoảng cách gần; với khoảng cách lớn hơn, các vật thể lớn hơn, thậm chí thân thể con người cũng làm méo tín hiệu. Hiện nay người ta đã cải tiến bằng cách thiết kế các loại ăng-ten mới và tăng cường độ nhạy của thiết bị đọc.
Quá nhiều chuẩn: Cần phải có chuẩn chung để mở rộng khả năng khai thác thẻ. Hiện có nhiều hãng cạnh tranh đưa ra các chuẩn khác nhau. Ví dụ, Nokia đã sử dụng chuẩn EPCGlobal và hệ thống siêu thị Wal-Mart sử dụng ISO 14443.
Quản lý tần số: Thông thường do Cục Tần Số Quốc Gia quản lý. Hiện tại, Mỹ đã thành lập một trung tâm Auto-ID kết hợp với Tổ Chức Tiêu Chuẩn Quốc Tế (ISO) để làm việc về vấn đề này.
Định dạng dữ liệu: Các dữ liệu chỉ đọc (không được phép sửa đổi) phải được định nghĩa sẵn trong chuẩn, nếu không được định nghĩa sẵn, thông tin cần ghi vào sẽ không có chuẩn thống nhất. Nếu được chuẩn hóa, chúng còn có thể chia sẻ với nhau về thông tin thu thập được. Người ta đã đề xuất sử dụng chuẩn XML để làm định dạng dữ liệu.
Khoảng cách cho phép từ thẻ đến máy đọc hiện nay mới chỉ được 1m. Mục tiêu đặt ra là phải đạt tối thiểu 3-4 m. Người ta đã xây dựng được một số hệ thống thiết bị đọc có thể đọc được thẻ cách xa 5m điều kiện đúng hướng và thẻ có nguồn điện riêng.
Chi phí thấp: Muốn áp dụng giải pháp này một cách rộng rãi thì chi phí sản xuất thẻ phải thật thấp.
Chúng ta sẽ có một phương thức giao dịch mới trong một thế giới di động mới: “M-bussiness + micropayment” dựa trên nền RFID. Hiện nay, một số hãng máy tính và thiết bị di động đã bắt đầu đưa ra thiết bị sử dụng công nghệ RFID. Đi đầu là Nokia với dòng Nokia 5140 tích hợp bộ đọc RFID. Theo dự đoán của các chuyên gia, đến năm 2010, các thiết bị như thế này sẽ phổ biến và được sử dụng rộng rãi trong tất cả các lĩnh vực của đời sống.

Binh Hoang Tieu
binhhoangtieu@yahoo.com
(theo PC World VN)
