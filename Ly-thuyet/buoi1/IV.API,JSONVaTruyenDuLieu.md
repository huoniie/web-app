# IV. API , JSON và truyền dữ liệu

## 1.API

API (Application Programming Interface) là giao diện cho phép các phần mềm giao tiếp với nhau.

Nó quy định: bạn gửi yêu cầu theo dạng nào, và sẽ nhận lại dữ liệu theo dạng nào, mà không cần biết bên trong hệ thống xử lý ra sao.

## 2. Web API 

Web API là API hoạt động qua mạng bằng giao thức HTTP/HTTPS. Client gửi HTTP request tới một URL, server trả về HTTP response, dữ liệu thường ở dạng JSON (đôi khi XML).

Các kiểu phổ biến:

REST API: phổ biến nhất, dùng URL + HTTP method (GET, POST, PUT, DELETE).
GraphQL: client tự chọn chính xác dữ liệu cần lấy qua một endpoint.
gRPC, SOAP, WebSocket: dùng cho các nhu cầu đặc thù.

## 3. Endpoint

Endpoint là một địa chỉ (URL) cụ thể của API mà client gọi tới để thực hiện một chức năng. Mỗi endpoint thường kết hợp URL + HTTP method.

GET     https://api.example.com/posts       → lấy danh sách bài viết
GET     https://api.example.com/posts/5     → lấy bài viết số 5
POST    https://api.example.com/posts       → tạo bài viết
DELETE  https://api.example.com/posts/5     → xóa bài viết số 5

Cấu trúc thường gặp:

Base URL: https://api.example.com (phần chung)
Path: /posts/5 (phần riêng của endpoint)

Cùng một URL nhưng khác method (GET /posts và POST /posts) là hai endpoint khác nhau.

## 4. Path Parameter và Query Parameter

Cả hai đều là cách truyền thông tin trên URL, nhưng dùng cho mục đích khác nhau.

### Path Parameter (tham số đường dẫn)

Nằm trong đường dẫn, dùng để xác định chính xác một tài nguyên.

          GET /users/42
          GET /users/42/orders/1001
          
          42 là id người dùng,
          1001 là id đơn hàng. 
          Thường được viết trong tài liệu API là /users/{id}.

### Query Parameter (tham số truy vấn)

Nằm sau dấu ?, dạng khóa=giá_trị, nối nhau bằng &. Dùng để lọc, tìm kiếm, sắp xếp, phân trang.

GET /products?category=giay&sort=price&page=2&limit=20

<img width="664" height="178" alt="image" src="https://github.com/user-attachments/assets/ee9293d8-5bb2-4205-ae97-0a2c58f19635" />

Dùng kết hợp
GET /users/42/orders?status=paid&page=1

→ Lấy các đơn hàng đã thanh toán, trang 1, của người dùng 42.

Mẹo chọn: “đối tượng nào?” dùng path; “lọc/điều chỉnh kết quả thế nào?” dùng query.

## 5. FE gọi API thì luồng request - response diễn ra như thế nào?

Ví dụ: người dùng mở trang danh sách bài viết, FE (Frontend) cần lấy dữ liệu từ BE (Backend).

1. Người dùng thao tác (mở trang / bấm nút)
        ↓
2. FE chạy code gọi API (fetch / axios)
        ↓
3. Trình duyệt phân giải domain qua DNS → IP, mở kết nối (HTTPS)
        ↓
4. Gửi HTTP Request tới Backend
        ↓
5. Backend: kiểm tra token/quyền → validate dữ liệu
        → xử lý logic → truy vấn Database
        ↓
6. Database trả dữ liệu về Backend
        ↓
7. Backend đóng gói JSON, gửi HTTP Response (kèm status code)
        ↓
8. FE nhận response, kiểm tra status code
        ↓
9. FE cập nhật giao diện (hiển thị danh sách / báo lỗi)

### Tóm tắt

<img width="599" height="137" alt="image" src="https://github.com/user-attachments/assets/67d9d798-f1be-40e5-9780-26b755c0d443" />
