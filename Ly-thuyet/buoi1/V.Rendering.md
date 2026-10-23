# V.Rendering 
## 1.HTML(Hyper Text Markup Language)
- **Khái niệm**

  HTML là ngôn ngữ **đánh dấu** tiêu chuẩn để tạo các trang 
    
    + mô tả cấu trúc của một trang web ( tiêu đề , liên kết , bảng , đoạn văn và nhiều yếu tố khác).
    
    + bao gồm một loạt các phần tử.

        Các phần tử cho trình duyệt biết cách hiển thị nội dung.

        Các phần tử HTML dùng để gắn nhãn cho các phần nội dung, ví dụ như "đây là tiêu đề","đây là đoạn văn", "đây là liên kết", v.v.
  


- **Phần tử HTML**

Một phần tử HTML được định nghĩa bởi thẻ mở, nội dung và thẻ đóng:

<img width="611" height="262" alt="image" src="https://github.com/user-attachments/assets/b5983997-402a-48a0-a1a9-837eb3bf9dfd" />


<img width="638" height="163" alt="image" src="https://github.com/user-attachments/assets/1a74df7d-dabf-47c0-ae68-5879a7a820ee" />

Note:Một số phần tử HTML không có nội dung (như phần tử <br>). Các phần tử này được gọi là phần tử rỗng. Phần tử rỗng không có thẻ đóng!


**Thuộc tính** 

các thẻ HTML cũng có các thuộc tính hay đặc trưng có thể cung cấp tác dụng hữu ích như định dạng, style,… Một thuộc tính (attribute) được sử dụng để xác định đặc trưng của phần tử HTML và được đặt bên trong phần tử đó.

<img width="665" height="354" alt="image" src="https://github.com/user-attachments/assets/278d0b51-f5c5-42b8-92fe-c8880a7221fb" />

Note: 

    + Có khoảng trắng giữa thuộc tính và phần tử.
    
    + Theo sau tên thuộc tính là dấu bằng, ví dụ: href=”itviec.com”.
    
    + Giá trị thuộc tính được đặt trong dấu ngoặc kép.
    
- **Trình duyệt web**

Mục đích của trình duyệt web (Chrome, Edge, Firefox, Safari) là đọc các tài liệu HTML và hiển thị chúng một cách chính xác.

Trình duyệt không hiển thị các thẻ HTML, mà sử dụng chúng để xác định cách hiển thị tài liệu:

<img width="628" height="351" alt="image" src="https://github.com/user-attachments/assets/bb22eb2b-f6bb-4250-9675-46b6f04c441b" />

- **Cấu trúc trang HTML**

  <img width="635" height="526" alt="image" src="https://github.com/user-attachments/assets/80ec4a73-8373-48df-bf0d-1272dd840e23" />

  Note: Nội dung bên trong phần <body> sẽ được hiển thị trong trình duyệt. Nội dung bên trong phần tử <title> sẽ được hiển thị trên thanh tiêu đề của trình duyệt hoặc trong tab của trang.




- **Ưu điểm và hạn chế**
    
    + **Ưu điểm**
      
          + HTML được hỗ trợ rộng rãi và hoạt động mượt mà trên trình duyệt web như Chrome, FireFox, Safari. Bên cạnh đó còn hỗ trợ các phiên bản mới của Internet Explorer và Edge.
      
          + Sử dụng bộ mã nguồn mở và miễn phí, không cần phải mua thêm bất kỳ phần mềm nào khác.
      
          + Linh hoạt, dễ tìm hiểu và sử dụng.
      
          + Dễ dàng tích hợp với các ngôn ngữ back-end như PHP, Ruby, Java,….
      
          + Markup sử dụng trong HTML ngắn gọn và có tính đồng nhất cao.
           
    + **Hạn chế**

           + Chức năng chính của HTML là lập trình cho các trang web tĩnh, do đó nếu bạn cần tạo các trang có tính năng động thì có thể kết hợp cùng JavaScript hoặc các ngôn ngữ backend khác. 

            + Người dùng phải tạo từng file HTML riêng lẻ, ngay cả khi cấu trúc phần tử giống nhau.

            + Cấu trúc phức tạp, bạn sẽ cần viết rất nhiều đoạn mã để có thể tạo nên một trang web đơn giản. 

            + Tính năng bảo mật còn bị hạn chế, dễ dẫn đến việc bị rò rỉ thông tin và bị  hack dữ liệu. 

            + Một số trình duyệt còn chậm cập nhật, chưa hỗ trợ các tính năng mới của HTML.
      
- **HTML tag**

HTML tags có hai loại chính là block-level tags (phần tử cấp khối) và inline tags (phần tử nội tuyến). Trong đó:

        + Block-level Tags được sử dụng cho toàn không gian của web và bắt đầu bằng
          dòng mới của trang.
          
        + Ngược lại, Inline Tags chỉ chiếm một phần nhỏ trên không gian web và không cần
          bắt đầu bằng dòng mới trên trang. 
## 2.CSS (Cascading Style Sheets)

### Khái niệm

Là ngôn ngữ style sheets, được sử dụng để mô tả cách trình bày các tài liệu được viết bằng ngôn ngữ đánh dấu (HTML, XML, SVG). CSS giúp kiểm soát cách trình bày của các yếu tố HTML 



### Một ví dụ đơn giản
  
  <img width="516" height="727" alt="image" src="https://github.com/user-attachments/assets/b737bae7-a4e8-49a1-bd3b-a81355138a98" />

Kết quả hiển thị

  <img width="480" height="214" alt="image" src="https://github.com/user-attachments/assets/e2477dcd-7aa7-4a39-86fc-a08e194ca415" />



### Cấu trúc

 - Bộ chọn (selector)
 
 - Khối khai báo (Declaration Blocks).

Bộ chọn giúp xác định phần tử HTML cần muốn định dạng. 

Khối khai báo giúp xác định thuộc tính (property) và giá trị (value) của thuộc tính đó để định dạng cho phần tử được chọn. Các khai báo thường được ngăn cách với nhau bởi dấu “;”. Khối bao gồm một hoặc nhiều khai báo được đặt trong ngoặc nhọn {}.

Các thuộc tính cơ bản của CSS

      + Màu sắc

      + Phông chữ

      + Bố cục

      + Hiệu ứng




  **Ưu điểm**

        Tách biệt nội dung và giao diện 
        Kiểm soát giao diện
        Responsive design
        Tăng tốc độ tải trang
        Tăng khả năng truy cập

**Hạn chế**

        Khó học
        Phụ thuộc vào trình duyệt
        Khó khăn trong việc debug
        Khả năng tương tác hạn chế
        
## 3.JavaScript

### Khái niệm

là một ngôn ngữ lập trình, chạy dưới dạng ngôn ngữ kịch bản phía máy khách trong môi trường hosting. Môi trường hosting phổ biến nhất là trình duyệt web, dùng ngôn ngữ này để tạo tính tương tác cho trang web. 

### Đặc điểm

          Là ngôn ngữ kịch bản (scripting language) hướng đối tượng.
          Là ngôn ngữ nhập động (dynamic typing) dựa trên prototype.
          Là ngôn ngữ lightweight (dễ học và viết code nhanh)
          Là ngôn ngữ đa mô hình (multi-paradigm) và đơn luồng (single threaded).






### Ưu điểm và hạn chế

**Ưu điểm**

Không cần bất kỳ thiết lập môi trường nào.
Chạy trên cả máy khách và máy chủ.
Chạy trên hầu hết các thiết bị.
Cho phép phát triển cả front-end và back-end
Có các phiên bản cập nhật thường xuyên.
Có mã nguồn mở.
Có nhiều framework & thư viện.


**Nhược điểm **

Rủi ro bảo mật: 

Hiệu suất: 

Độ phức tạp: 





##  4 Vai trò của HTML, CSS, JavaScript trong PE

**HTML tạo ra cái nút, CSS làm nó đẹp, JS làm nó phản ứng khi được bấm.**

Cách nhớ nhanh: HTML = cái gì, CSS = trông thế nào, JS = làm gì.

## 6.SSR (Server Side Rendering) & CSR (Client Side Rendering)

##SSR

### Cơ chế server-side rendering
phần lớn logic sẽ được xử lý ở server:

Vào web -(trình đuyệt)> server - > dọc dữ liệu từ database -> gửi về cho người dùng

<img width="806" height="547" alt="image" src="https://github.com/user-attachments/assets/7742a0d0-1369-4941-b39e-01fabd28c1bc" />

mọi thứ làm đều ở server

### Ưu điểm và hạn chế  

**Ưu điểm**

Trang web load nhanh 

thời điểm này không có khái niệm frontend và backend vì mọi thứ xử lý đều nằm trên đều nằm trên server còn client chỉ hiển thị
**Hạn chế**
vì mỗi lần đều phải gửi về server để xử lý -> chậm -> load nhiều lần 



## CSR

### Cơ chế server-side rendering

<img width="827" height="441" alt="image" src="https://github.com/user-attachments/assets/0c75c30e-194b-4fe5-9d34-12917739a605" />


mấy cái yêu cầu đơn giản sẽ được thực hiện trong client luôn còn mấy cái quá phức tạp vẫn cần chuyển về bên server để chạy


<img width="806" height="547" alt="image" src="https://github.com/user-attachments/assets/7742a0d0-1369-4941-b39e-01fabd28c1bc" />


### Ưu điểm và hạn chế  

**Ưu điểm**


không cần load lại nhiều nó hiện luôn như tin nhắn ấy

**Hạn chế**


Đòi hỏi project phải chia làm 2 phần riêng là back-end (REST api) và front-end nên khó code hơn

SEO không tốt bằng Server Side Rendering (Do bot crawl không đọc được dữ liệu). Để giải quyết, ta phải kết hợp thêm SSR (Bot mới của Google đọc được client-side rendering rồi).
Nếu client sử dụng mobile, device yếu thì khi load sẽ bị chậm





