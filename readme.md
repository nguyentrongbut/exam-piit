1.Kích hoạt yêu cầu độ phức tạp của mật khẩu:

Mở Trình chỉnh sửa chính sách nhóm bằng cách nhập "gpedit.msc" trong hộp thoại Chạy (Win + R).
Điều hướng đến Cấu hình máy tính -> Cài đặt Windows -> Cài đặt bảo mật -> Chính sách tài khoản -> Chính sách mật khẩu.
Đặt "Mật khẩu phải đáp ứng các yêu cầu phức tạp" thành Đã bật.

2. Đặt quy tắc gửi đến và gửi đi trong tường lửa Windows:

Mở Tường lửa của Bộ bảo vệ Windows bằng cách tìm kiếm nó trong menu Bắt đầu.
Nhấp vào "Cài đặt nâng cao" ở khung bên trái.
Tạo quy tắc gửi đến hoặc gửi đi mới bằng cách nhấp chuột phải vào "Quy tắc gửi đến" hoặc "Quy tắc gửi đi" và chọn "Quy tắc mới".

3.Áp dụng bảo mật IP:

Sử dụng lệnh "secpol.msc" để mở Chính sách bảo mật cục bộ.
Điều hướng đến "Chính sách bảo mật IP trên máy tính cục bộ" và xác định các chính sách để liên lạc an toàn.

4.Áp dụng mã hóa:

Bật BitLocker để mã hóa ổ đĩa hoặc sử dụng EFS (Hệ thống tệp mã hóa) để mã hóa cấp độ tệp.

5.Áp dụng bảo mật trên một thư mục cho người dùng đơn giản:

Nhấp chuột phải vào thư mục, đi tới "Thuộc tính" và trong tab "Bảo mật", gán quyền thích hợp cho người dùng đơn giản.

6.Sử dụng lệnh Netstat:

Netstat hiển thị các kết nối mạng đang hoạt động và các cổng nghe.
Hai công tắc:
-a: Hiển thị tất cả các kết nối và cổng nghe.
-n: Hiển thị địa chỉ và số cổng ở dạng số.

7.Tìm thông tin về tên miền:

Sử dụng lệnh "nslookup" trong dấu nhắc lệnh.
Ví dụ:nslookup example.com

8.Sử dụng máy quét nâng cao:

Máy quét nâng cao cung cấp các tính năng nâng cao để xác định lỗ hổng, phần mềm độc hại và các mối đe dọa bảo mật khác trong mạng.

9.Tạo trang web HTTPS:

Nhận chứng chỉ SSL cho tên miền của bạn.
Định cấu hình máy chủ web của bạn (ví dụ: Apache, Nginx) để sử dụng chứng chỉ SSL.

10.Chức năng của Phân tích bảo mật cơ sở:

Phân tích bảo mật cơ bản thiết lập cấu hình bảo mật tiêu chuẩn, giúp xác định các sai lệch và lỗ hổng tiềm ẩn.

11.Các loại tin tặc và mục tiêu:

Các loại: Mũ trắng, Mũ đen, Mũ xám.
Mục tiêu: Thu lợi tài chính, đánh cắp thông tin, hoạt động, v.v.
Các giai đoạn: Trinh sát, Quét, Giành quyền truy cập, Duy trì quyền truy cập, Che dấu vết.

12.Sử dụng NSLookup:

NSLookup được sử dụng để truy vấn máy chủ DNS để lấy thông tin liên quan đến tên miền, chẳng hạn như địa chỉ IP và chi tiết máy chủ thư.

13.Chức năng của Wireshark:

Wireshark là một công cụ phân tích giao thức mạng có chức năng thu thập và kiểm tra các gói trên mạng để khắc phục sự cố và phân tích bảo mật.

14.Quét địa chỉ Mac:

Sử dụng các công cụ như Nmap để thực hiện quét địa chỉ MAC.
Ví dụ:nmap -sP 192.168.1.0/24

15.Chức năng của IPCONFIG:

IPCONFIG hiển thị cấu hình giao diện mạng trên hệ thống Windows.
Ví dụ:ipconfig /all

16.Giải thích Trình quản lý tác vụ:

Trình quản lý tác vụ cung cấp thông tin về các tiến trình đang chạy, hiệu suất hệ thống và cho phép chấm dứt tiến trình.

17.Chức năng của Microsoft Network Monitor:

Network Monitor là một công cụ phân tích gói có chức năng nắm bắt và phân tích lưu lượng mạng để khắc phục sự cố và phân tích.

18.Truy cập sổ đăng ký ở vị trí từ xa:

Sử dụng lệnh "regedit", nhấp vào "Tệp" và chọn "Kết nối sổ đăng ký mạng". Nhập tên máy tính từ xa hoặc IP.

19.Chặn CMD:

Vô hiệu hóa Dấu nhắc lệnh bằng cách đặt Chính sách nhóm. Điều hướng đến Cấu hình người dùng -> Mẫu quản trị -> Hệ thống và bật "Ngăn chặn quyền truy cập vào dấu nhắc lệnh."

20.Chặn kết nối mạng:

Sử dụng quy tắc tường lửa để chặn các ứng dụng hoặc cổng cụ thể cho kết nối mạng.