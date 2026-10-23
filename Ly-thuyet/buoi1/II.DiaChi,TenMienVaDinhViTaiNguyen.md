# II.Địa chỉ , tên miền và định vị tài nguyên


  ## Địa chỉ IP (Internet Protocol Address)

  ### Khái niệm 

  là một dãy số hoặc ký tự được gán cho mỗi thiết bị khi tham gia vào mạng máy tính sử dụng giao thức Internet (IP). Địa chỉ IP cho phép các thiết bị như máy tính, điện thoại thông minh, máy chủ và router giao tiếp với nhau trên internet và các mạng cục bộ (LAN).

  ### Phân loại 

  **IPv4 (Internet Protocol version 4)**
  
IPv4  Nó sử dụng 32 bit  Địa chỉ IPv4 được biểu diễn dưới dạng **bốn nhóm số thập phân**,**mỗi nhóm từ 0 đến 255**, cách nhau bởi **dấu chấm** (ví dụ: 192.168.1.1).

**Pv6 (Internet Protocol version 6)**

IPv6 là phiên bản địa chỉ IP mới hơn, được phát triển để giải quyết vấn đề cạn kiệt địa chỉ IPv4. Nó sử dụng 128 bit,

Địa chỉ IPv6 được biểu diễn dưới dạng **tám nhóm số hexa**, **mỗi nhóm 16 bit**, cách nhau bởi **dấu hai chấm**). 

**IP công cộng (Public IP)**

IP công cộng là địa chỉ IP được gán cho thiết bị của bạn bởi nhà cung cấp dịch vụ internet (ISP)

**IP riêng (Private IP)**

IP riêng là địa chỉ IP được sử dụng trong mạng cục bộ (LAN), chẳng hạn như mạng gia đình hoặc mạng văn phòng.  một mạng LAN.


### Ưu điểm và hạn chế

**Ưu điểm**

 IP Address giúp định tuyến dữ liệu trên internet, 

**Nhược điểm**

Với IPv4, số lượng địa chỉ IP có hạn,
## Domain
  Domain (tên miền) là địa chỉ dễ nhớ của một website trên Internet, ví dụ google.com, vnexpress.net, claude.ai. Nó là “tên” thay cho dãy số IP khó nhớ (như 142.250.190.14).

Dùng để 
Truy cập website-> rất nhiều cái từ đây


Cấu trúc tên miền

Ví dụ: blog.example.com.vn

vn: tên miền cấp cao nhất (TLD, ở đây là quốc gia Việt Nam)
com.vn: tên miền cấp 2
example: phần tên chính do bạn đặt
blog: tên miền phụ (subdomain)
  
  ## Định vị tài nguyên
  
   ### Port
   Port (cổng) là một con số dùng để xác định dịch vụ/ứng dụng cụ thể trên một máy tính hoặc máy chủ khi nhận dữ liệu qua mạng.

          Phân biệt dịch vụ
          Cho phép nhiều kết nối đồng thời
          Kiểm soát bảo mật


Là số nguyên từ 0 đến 65535.


Phân loại port
            
            0 - 1023: well-known ports, dành cho dịch vụ chuẩn.
            
            
            1024 - 49151: registered ports, dành cho ứng dụng đã đăng ký.
            
            49152 - 65535: dynamic/private ports, hệ thống cấp tạm thời cho kết nối đi ra.
            Một số port thông dụng
            
Port	Dịch vụ
- 20, 21	FTP (truyền file)
- 22	SSH (điều khiển từ xa an toàn)
- 25	SMTP (gửi email)
- 53	DNS
- 80	HTTP (web thường)
- 110	POP3 (nhận email)
- 143	IMAP (nhận email)
- 443	HTTPS (web bảo mật)
- 3306	MySQL
- 3389	Remote Desktop (Windows)
- 5432	PostgreSQL
   
   ### URL
  URL (Uniform Resource Locator) là địa chỉ đầy đủ của một tài nguyên trên Internet (trang web, hình ảnh, video, file...). Nó cho trình duyệt biết tìm ở đâu và lấy bằng cách nào.

Truy cập tài nguyên: gõ vào thanh địa chỉ để mở trang web, tải file, xem ảnh.
Chia sẻ liên kết: gửi cho người khác đúng trang cần xem.
Tạo liên kết (hyperlink) giữa các trang.

   
   ### URI

   URI (Uniform Resource Identifier) là chuỗi ký tự dùng để định danh một tài nguyên, theo một quy tắc chuẩn chung. Nó là khái niệm rộng hơn URL.

### URN

(định danh bằng tên, không chỉ vị trí)

URI = cách để gọi tên/định danh một tài nguyên.

URL = URI có thêm thông tin chỉ đường để tìm thấy tài nguyên đó.

URN = URI chỉ đặt tên, không chỉ đường.

   - URI
        +  URL  (định danh + vị trí, cách truy cập)
        +  URN  (định danh bằng tên, không chỉ vị trí)
