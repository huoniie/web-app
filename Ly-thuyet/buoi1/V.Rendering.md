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

        + Block-level Tags được sử dụng cho toàn không gian của web và bắt đầu bằng
          dòng mới của trang. Một số thẻ block-level tags trong HTML như <html>, <div>, <p>,           <table> và <body>.  
        + Ngược lại, Inline Tags chỉ chiếm một phần nhỏ trên không gian web và không cần
          bắt đầu bằng dòng mới trên trang. Thường được sử dụng để tạo bố cục và định dạng
          cho phần nội dung của Block-Level Tags. Một số thẻ Inline phổ biến như <a>, <span>, <b>, <i>,…

## 2.CSS (Cascading Style Sheets)
### Khái niệm
à ngôn ngữ style sheets, được sử dụng để mô tả cách trình bày các tài liệu được viết bằng ngôn ngữ đánh dấu (HTML, XML, SVG). CSS giúp kiểm soát cách trình bày của các yếu tố HTML gồm:
Màu sắc: Màu nền, màu chữ, màu viền,…
Phông chữ: Kiểu chữ, kích thước chữ, độ dày chữ,…
Bố cục: Vị trí các yếu tố, kích thước, căn chỉnh,…
Hiệu ứng: Hiệu ứng chuyển tiếp, hiệu ứng di chuột,…

mô tả cách các phần tử HTML được hiển thị trên màn hình, giấy hoặc các phương tiện khác.
giúp tiết kiệm rất nhiều công sức. Nó có thể điều khiển bố cục của nhiều trang web cùng một lúc.
Các bảng định kiểu bên ngoài được lưu trữ trong các tệp CSS.

### Một ví dụ đơn giản
  
  <img width="516" height="727" alt="image" src="https://github.com/user-attachments/assets/b737bae7-a4e8-49a1-bd3b-a81355138a98" />

Kết quả hiển thị

  <img width="480" height="214" alt="image" src="https://github.com/user-attachments/assets/e2477dcd-7aa7-4a39-86fc-a08e194ca415" />


### Cơ chế hoạt động

<img width="929" height="518" alt="image" src="https://github.com/user-attachments/assets/c27bebfe-ab6c-4208-80ba-203aa8abaefc" />

### Vai trò 

Có 3 cách thêm CSS vào trang web HTML là Inline CSS (CSS nội tuyến), Internal CSS (CSS nội bộ) và External CSS (CSS bên ngoài). 

      + Định dạng và tạo kiểu cho website

      + Tách biệt nội dung và định dạng

      + Tăng khả năng truy cập

      + Tối ưu hóa hiệu suất website

      + Tăng khả năng bảo trì

### Cấu trúc

Toàn bộ cấu trúc của CSS được gọi là một bộ quy tắc với 2 phần chính gồm: Bộ chọn (selector), Khối khai báo (Declaration Blocks).

Bộ chọn giúp xác định phần tử HTML cần muốn định dạng. Có nhiều loại bộ chọn khác nhau gồm: Bộ chọn theo thẻ (element selector), Bộ chọn theo class (class selector), Bộ chọn theo ID (id selector), Bộ chọn con cháu (descendant selector), Bộ chọn anh em (sibling selector).

Khai báo giúp xác định thuộc tính (property) và giá trị (value) của thuộc tính đó để định dạng cho phần tử được chọn. Các khai báo thường được ngăn cách với nhau bởi dấu “;”. Khối bao gồm một hoặc nhiều khai báo được đặt trong ngoặc nhọn {}.

Các thuộc tính cơ bản của CSS

      + Màu sắc

      + Phông chữ

      + Bố cục

      + Hiệu ứng


### Các thao tác thiết kế giao diện cơ bản

**Thay đổi màu sắc**

        Sử dụng thuộc tính color để thay đổi màu sắc của text.
        Sử dụng thuộc tính background-color để thay đổi màu nền của phần tử HTML.
        Sử dụng thuộc tính gradient để tạo hiệu ứng chuyển màu cho nền của phần tử HTML.
        Sử dụng thuộc tính filter để thêm các hiệu ứng filter cho phần tử HTML.

**Định dạng bố cục**
        
        Sử dụng thuộc tính margin để tạo khoảng cách giữa body và các phần tử khác.
        Sử dụng thuộc tính padding để tạo khoảng cách giữa nội dung body và đường viền.
        Sử dụng thuộc tính text-align để căn lề text sang trái, phải, giữa hoặc hai đầu.
        Sử dụng display: flex để kích hoạt flexbox cho body.
        Sử dụng các thuộc tính flexbox như justify-content và align-items để căn chỉnh các phần tử theo chiều ngang và chiều dọc.


**Định dạng văn bản**

        Sử dụng thuộc tính font-family: để chọn font chữ cho phần tử HTML.
        Sử dụng thuộc tính font-size: để định cỡ font chữ.
        Sử dụng thuộc tính font-weight: để định độ dày mỏng của font chữ.
        Sử dụng thuộc tính font-style: để định kiểu chữ như normal, italic, oblique,…
        Sử dụng thuộc tính text-transform: để chuyển đổi kiểu chữ như uppercase, lowercase, capitalize,…
        Sử dụng thuộc tính letter-spacing: để điều chỉnh khoảng cách giữa các ký tự.
        Sử dụng thuộc tính word-spacing: để điều chỉnh khoảng cách giữa các từ.
        Sử dụng thuộc tính text-shadow: để thêm bóng đổ cho text.


**Căn chỉnh hình ảnh**
        
        Sử dụng thuộc tính margin: để tạo khoảng cách giữa hình ảnh và các phần tử khác.
        Sử dụng thuộc tính float: để di chuyển hình ảnh sang trái hoặc phải.
        Sử dụng thuộc tính text-align: để căn chỉnh hình ảnh trong một phần tử block.
        Sử dụng display: flex để kích hoạt flexbox cho phần tử chứa hình ảnh.
        Sử dụng các thuộc tính flexbox như justify-content và align-items để căn chỉnh hình ảnh theo chiều ngang và chiều dọc.
        Sử dụng display: grid để kích hoạt grid layout cho phần tử chứa hình ảnh.
        Sử dụng các thuộc tính grid layout như grid-template-columns và grid-template-rows để xác định kích thước của các cột và hàng.
        Sử dụng các thuộc tính grid layout như justify-content và align-items để căn chỉnh hình ảnh trong grid.

- **Ưu điểm và hạn chế**

  **Ưu điểm**

        Tách biệt nội dung và giao diện: CSS nội bộ và CSS bên ngoài có thể tách biệt nội dung (HTML) và giao diện (CSS) của website, giúp cho việc quản lý và cập nhật website dễ dàng hơn.
        Kiểm soát giao diện: CSS cho phép bạn kiểm soát hoàn toàn giao diện của website, bao gồm màu sắc, font chữ, bố cục, v.v.
        Responsive design: CSS giúp bạn tạo ra website có thể tự động thích ứng với kích thước màn hình của mọi thiết bị.
        Tăng tốc độ tải trang: CSS bên ngoài giúp giảm kích thước của trang web bằng cách tách biệt nội dung và giao diện.
        Tăng khả năng truy cập: CSS giúp website dễ sử dụng hơn cho người dùng có khiếm khuyết.

**Hạn chế**

        Khó học: CSS có thể khó học đối với người mới bắt đầu.
        Phụ thuộc vào trình duyệt: Các trình duyệt khác nhau có thể hiển thị một số thành phần CSS khác nhau.
        Khó khăn trong việc debug: Việc tìm kiếm lỗi CSS có thể khó khăn. Tuy nhiên, bạn có thể nhờ tới sự hỗ trợ của Chrome DevTools hoặc Firefox Developer Edition.
        Khả năng tương tác hạn chế: CSS không thể tạo ra các hiệu ứng tương tác phức tạp.

## 3.JavaScript

### Khái niệm

là một ngôn ngữ lập trình, chạy dưới dạng ngôn ngữ kịch bản phía máy khách trong môi trường hosting. Môi trường hosting phổ biến nhất là trình duyệt web, dùng ngôn ngữ này để tạo tính tương tác cho trang web. 

### Đặc điểm


          Là ngôn ngữ kịch bản (scripting language) hướng đối tượng.
          Là ngôn ngữ nhập động (dynamic typing) dựa trên prototype.
          Là ngôn ngữ lightweight (dễ học và viết code nhanh)
          Là ngôn ngữ đa mô hình (multi-paradigm) và đơn luồng (single threaded).

### Cơ chế


### JS làm được
**Sẽ ra sao nếu không có js**
Nếu không có JavaScript, trang web sẽ chỉ có HTML và CSS. Khi đó, 90% website sẽ ở dạng tĩnh như một cuốn sách.

Ngôn ngữ lập trình này được tạo ra để web developer có thể nhúng mã thực thi vào trang web, cho phép trình duyệt web phản hồi tương tác của người dùng và thay đổi bố cục, nội dung trên trang web như:

        Nút có thể nhấp vào, menu thả xuống 
        Nội dung bổ sung khi làm mới trang
        Màu sắc của các phần tử thay đổi linh hoạt trên trang.

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
JavaScript có thể được sử dụng để tải dữ liệu bằng AJAX hoặc bằng cách thao tác với các thẻ tải dữ liệu như <img>, <object>, <script>. Các cuộc tấn công này được gọi là tấn công tập lệnh chéo trang.

Hiệu suất: 
JavaScript có hiệu suất hạn chế hơn các ngôn ngữ truyền thống. Một chương trình phức tạp nếu viết bằng ngôn ngữ này sẽ chạy tương đối chậm. Dù vậy, nó thường được dùng để thực hiện các tác vụ đơn giản trong trình duyệt, do đó hiệu suất không được coi là một hạn chế quá lớn.

Độ phức tạp: 
Để có thể viết các tập lệnh nâng cao bằng JavaScript, developer cần có kiến ​​thức sâu về tất cả các khái niệm lập trình, các đối tượng ngôn ngữ cốt lõi, các đối tượng phía máy khách và máy chủ.














Note: JavaScript vừa là ngôn ngữ biên dịch và thông dịch. 



## 4.Mối liên hệ giữa HTML, CSS và JavaScript

HTML được xem là một nền tảng cơ bản trong quá trình triển khai một website, nhưng một mình HTML vẫn chưa đủ để tạo nên một website hoàn chỉnh và chuyên nghiệp. Chính vì vậy, các lập trình viên thường kết hợp HTML với hai ngôn ngữ front-end khác là CSS và JavaScript để tạo nên một website hoàn chỉnh.

Khi kết hợp giữa HTML, CSS và JavaScript sẽ giúp website tăng trải nghiệm người dùng hiệu quả với một số chức năng cơ bản như:

          + Bên cạnh HTML tạo các thành phần của một trang web thì CSS sẽ đóng vai trò thiết lập màu sắc, background, hiệu ứng,.. phù hợp với ý tưởng của website.
          + Còn JavaScript sẽ có vai trò biến các cấu trúc thành phần thành thứ người dùng có thể tương tác, cụ thể là tạo ra các tính năng động như slider, pop-up,…
          + Bạn có thể hiểu đơn giản, HTML cung cấp phần xương của trang web, CSS phụ trách phần da và JavaScript sẽ là đầu não quan trọng.


          HTML xác định cấu trúc và nội dung của trang web.
          CSS đặt cách trình bày và thiết kế giao diện trang web.
          JavaScript bổ sung tính tương tác cho trang web, tạo ra các ứng dụng web phong phú hơn.

          <img width="485" height="268" alt="image" src="https://github.com/user-attachments/assets/6ed18f91-9fde-4172-9a99-f253793c24aa" />


**Ví dụ**

 bạn muốn tạo một trang web cho người dùng điền biểu mẫu tham gia một cuộc thi, thì:

          + HTML: Tạo các thông tin về cuộc thi, biểu mẫu (họ tên, tuổi, địa chỉ,…) dưới dạng những đoạn mã văn bản. 
          
          + CSS: Chỉnh sửa các đoạn văn bản theo bố cục hợp lý như định dạng bảng, màu sắc, kiểu dáng,.. Đồng thời giúp bạn tạo nên các ô điền câu trả lời cho người dùng. 
          
          + JavaScript: Cho phép bạn lập trình một popup hiển thị “Cảm ơn bạn đã tham gia” khi bạn đã điền đầy đủ thông tin và bấm gửi. 
