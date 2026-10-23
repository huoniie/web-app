# I.Internet, Web và mô hình hoạt động

  ## 1.Khái niệm cơ bản
  ### Internet
  - **Khái niệm**
    
    là một hệ thống mạng toàn cầu kết nối hàng tỷ thiết bị như máy tính, điện thoại,
  máy chủ và nhiều thiết bị thông minh khác thông qua giao thức truyền dữ liệu chung.


### Web

Web là một dịch vụ chạy trên Internet, gồm các trang tài liệu (văn bản, hình ảnh, video) liên kết với nhau bằng siêu liên kết (hyperlink), mỗi trang có một URL riêng. Bạn truy cập chúng bằng trình duyệt qua giao thức HTTP/HTTPS.

### Website

Website là một tập hợp các trang web (web page) thuộc về cùng một tên miền, do một cá nhân hoặc tổ chức quản lý.

### Web Application

Web Application (ứng dụng web): ứng dụng chạy trên trình duyệt, cho phép người dùng tương tác, thao tác, xử lý dữ liệu, thường có đăng nhập và nội dung cá nhân hóa.

## 2.So sánh các khái niệm
<img width="674" height="202" alt="image" src="https://github.com/user-attachments/assets/3bc151a2-f78b-41ad-8cf2-41a773436526" />

<img width="661" height="204" alt="image" src="https://github.com/user-attachments/assets/8fe3d5b7-60bd-4dfc-96c0-e0567ee168bf" />



## 3.Mô hình client - Server và Frontend - Backend - Database 

### Client - Server

Client (máy khách): thiết bị gửi yêu cầu (request). Ví dụ: trình duyệt trên điện thoại, laptop của bạn.
Server (máy chủ): máy tính mạnh, hoạt động liên tục, nhận yêu cầu và trả về phản hồi (response).

### Frontend - Backend - Database 

**Frontend (giao diện)**

Phần người dùng nhìn thấy và tương tác, chạy trên trình duyệt.
Công nghệ: HTML, CSS, JavaScript, framework như React, Vue, Angular.
Nhiệm vụ: hiển thị giao diện, nhận thao tác (bấm nút, nhập form), gửi yêu cầu tới backend.

**Backend (xử lý nghiệp vụ)**

Chạy trên server, người dùng không thấy trực tiếp.
Công nghệ: Node.js, Python (Django, FastAPI), Java (Spring), PHP (Laravel), C#...
Nhiệm vụ: xử lý logic, kiểm tra đăng nhập/quyền, thực hiện nghiệp vụ, giao tiếp với database, trả dữ liệu cho frontend (thường qua API, định dạng JSON).

**Database (cơ sở dữ liệu)**

Nơi lưu trữ dữ liệu lâu dài: tài khoản, đơn hàng, bài viết...
Công nghệ: MySQL, PostgreSQL, SQL Server (quan hệ), MongoDB, Redis (NoSQL).
