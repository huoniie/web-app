# V.Rendering 
## 1.HTML(Hyper Text Markup Language)
- **Khái niệm**

  HTML là ngôn ngữ **đánh dấu** tiêu chuẩn để tạo các trang 
    
    + ngôn ngữ đánh dấu tiêu chuẩn để tạo các trang web.
    
    + mô tả cấu trúc của một trang web( tiêu đề , liên kết , bảng , đoạn văn và nhiều yếu tố khác).
    
    + bao gồm một loạt các phần tử.

        Các phần tử cho trình duyệt biết cách hiển thị nội dung.

        Các phần tử HTML dùng để gắn nhãn cho các phần nội dung, ví dụ như "đây là tiêu đề",            "đây là đoạn văn", "đây là liên kết", v.v.
  
 -  **Một tài liệu HTML đơn giản**

<img width="362" height="288" alt="image" src="https://github.com/user-attachments/assets/d5f1a2de-15d5-4fd9-b5c6-27c2581642ef" />

        + Phần <!DOCTYPE html>khai báo xác định rằng tài liệu này là tài liệu HTML5.
        
        + Phần <html>tử <element> là phần tử gốc của một trang HTML.
        
        + Phần tử này <head>chứa thông tin meta về trang HTML.
        
        + Phần tử này <title>chỉ định tiêu đề cho trang HTML (tiêu đề này sẽ được hiển thị             trên thanh tiêu đề của trình duyệt hoặc trong tab của trang).
        
        + Phần tử này <body>xác định phần thân của tài liệu và là vùng chứa cho tất cả nội             dung hiển thị, chẳng hạn như tiêu đề, đoạn văn, hình ảnh, siêu liên kết, bảng,               danh sách, v.v.
        
        + Phần tử này <h1>định nghĩa một tiêu đề lớn.
        
        + Phần tử này <p>định nghĩa một đoạn văn.

- **Phần tử HTML**

Một phần tử HTML được định nghĩa bởi thẻ mở, nội dung và thẻ đóng:

<img width="611" height="262" alt="image" src="https://github.com/user-attachments/assets/b5983997-402a-48a0-a1a9-837eb3bf9dfd" />



//<h1> Tiêu đề đầu tiên của tôi </h1>

//<p> Đoạn văn đầu tiên của tôi. </p>

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


- **Cơ chế**

  <img width="677" height="341" alt="image" src="https://github.com/user-attachments/assets/c0b7398b-d260-461b-a518-087ce485d42e" />

  -Một tập tin <- các phần tử HTML <(bao bọc)- 1 cặp thẻ

  <img width="710" height="528" alt="image" src="https://github.com/user-attachments/assets/741e5a9d-42bb-480e-83b3-31cf6062175f" />

- **Ưu điểm và hạn chế**
    
    + **Ưu điểm**
      
          + HTML được hỗ trợ rộng rãi và hoạt động mượt mà trên trình duyệt web như                      Chrome, FireFox, Safari. Bên cạnh đó còn hỗ trợ các phiên bản mới của Internet               Explorer và Edge.
      
          + Sử dụng bộ mã nguồn mở và miễn phí, không cần phải mua thêm bất kỳ phần mềm nào              khác.
      
          + Linh hoạt, dễ tìm hiểu và sử dụng.
      
          + Dễ dàng tích hợp với các ngôn ngữ back-end như PHP, Ruby, Java,….
      
          + Markup sử dụng trong HTML ngắn gọn và có tính đồng nhất cao.
           
    + **Hạn chế**

           + Chức năng chính của HTML là lập trình cho các trang web tĩnh, do đó nếu bạn cần              tạo các trang có tính năng động thì có thể kết hợp cùng JavaScript hoặc các                   ngôn ngữ backend khác. 

            + Người dùng phải tạo từng file HTML riêng lẻ, ngay cả khi cấu trúc phần tử                     giống nhau.

            + Cấu trúc phức tạp, bạn sẽ cần viết rất nhiều đoạn mã để có thể tạo nên một                   trang web đơn giản. 

            + Tính năng bảo mật còn bị hạn chế, dễ dẫn đến việc bị rò rỉ thông tin và bị                   hack dữ liệu. 
            + Một số trình duyệt còn chậm cập nhật, chưa hỗ trợ các tính năng mới của HTML.
- **HTML tag**
HTML tags có hai loại chính là block-level tags (phần tử cấp khối) và inline tags (phần tử nội tuyến). Trong đó:

        Block-level Tags được sử dụng cho toàn không gian của web và bắt đầu bằng dòng mới của trang. Một số thẻ block-level tags trong HTML như <html>, <div>, <p>, <table> và <body>.  
        Ngược lại, Inline Tags chỉ chiếm một phần nhỏ trên không gian web và không cần bắt đầu bằng dòng mới trên trang. Thường được sử dụng để tạo bố cục và định dạng cho phần nội dung của Block-Level Tags. Một số thẻ Inline phổ biến như <a>, <span>, <b>, <i>,…



## 4.Mối liên hệ giữa HTML, CSS và JavaScript

HTML được xem là một nền tảng cơ bản trong quá trình triển khai một website, nhưng một mình HTML vẫn chưa đủ để tạo nên một website hoàn chỉnh và chuyên nghiệp. Chính vì vậy, các lập trình viên thường kết hợp HTML với hai ngôn ngữ front-end khác là CSS và JavaScript để tạo nên một website hoàn chỉnh.

Khi kết hợp giữa HTML, CSS và JavaScript sẽ giúp website tăng trải nghiệm người dùng hiệu quả với một số chức năng cơ bản như:

          + Bên cạnh HTML tạo các thành phần của một trang web thì CSS sẽ đóng vai trò thiết lập màu sắc, background, hiệu ứng,.. phù hợp với ý tưởng của website.
          + Còn JavaScript sẽ có vai trò biến các cấu trúc thành phần thành thứ người dùng có thể tương tác, cụ thể là tạo ra các tính năng động như slider, pop-up,…
          + Bạn có thể hiểu đơn giản, HTML cung cấp phần xương của trang web, CSS phụ trách phần da và JavaScript sẽ là đầu não quan trọng.

**Ví dụ**

 bạn muốn tạo một trang web cho người dùng điền biểu mẫu tham gia một cuộc thi, thì:

          + HTML: Tạo các thông tin về cuộc thi, biểu mẫu (họ tên, tuổi, địa chỉ,…) dưới dạng những đoạn mã văn bản. 
          
          + CSS: Chỉnh sửa các đoạn văn bản theo bố cục hợp lý như định dạng bảng, màu sắc, kiểu dáng,.. Đồng thời giúp bạn tạo nên các ô điền câu trả lời cho người dùng. 
          
          + JavaScript: Cho phép bạn lập trình một popup hiển thị “Cảm ơn bạn đã tham gia” khi bạn đã điền đầy đủ thông tin và bấm gửi. 
