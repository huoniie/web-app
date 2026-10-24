# III. HTTP và giao tiếp trên Web 
## 1.Khái niệm
### HTTP

HTTP (HyperText Transfer Protocol) là giao thức để client và server trao đổi dữ liệu. Mỗi lần trao đổi gồm một request (yêu cầu) và một response (phản hồi).

#### HTTP Request (client gửi lên server)(Không hiểu bản chất)

Request line: method + đường dẫn + phiên bản HTTP.

Headers: thông tin bổ sung (domain, loại trình duyệt, loại dữ liệu chấp nhận, cookie, token đăng nhập...).

Dòng trống ngăn cách.

Body (không bắt buộc): dữ liệu gửi kèm, thường có ở POST/PUT (ví dụ JSON, dữ liệu form).

### HTTP Response (server trả về client)(không hiểu bản chất)

Status line: phiên bản HTTP + mã trạng thái + mô tả.

Headers: thông tin về phản hồi (loại nội dung, độ dài, cookie, cache...).

Body: nội dung thật sự (HTML, JSON, ảnh, file...).

note:  HTTP là giao thức không lưu trạng thái (stateless), mỗi request độc lập, server không tự nhớ request trước. Vì vậy cần cookie, session, token để “nhớ” người dùng.

### HTTP Method

cho server biết client muốn làm hành động gì với tài nguyên.

<img width="790" height="296" alt="image" src="https://github.com/user-attachments/assets/bc7f623c-fcd7-4178-a519-59196f4b78ee" />


<img width="735" height="270" alt="image" src="https://github.com/user-attachments/assets/f140f1e5-5a05-47ef-91df-8b78d276e9a0" />


### HTTP Status Code

con số 3 chữ số server trả về trong response, cho biết kết quả xử lý request. Chữ số đầu tiên chia thành 5 nhóm:

<img width="458" height="231" alt="image" src="https://github.com/user-attachments/assets/37847f48-5ed6-4caa-8f72-199c6c79edf0" />

<img width="305" height="142" alt="image" src="https://github.com/user-attachments/assets/52795f58-9385-401f-9234-121af141f9cc" />



