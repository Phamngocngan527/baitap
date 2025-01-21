<html lang="en">
<style>
      h1{color: #d63031;
      background:  #ff7675;
      border: 70px solid #ff7675;
	}
</style>
<body>
    <h1>Bài 16: Định dạng khung </h1>
    <p style="color: red; font-weight: bold;">Luyện tập 1: Phần tử html có thể ẩn đi trên trang web được không? Nếu có thì dùng lệnh CSS gì?</p>
    <p> Có, phần tử HTML có thể được ẩn đi trên trang web bằng cách sử dụng lệnh CSS display: none;. </p> 
    <p style="color: red; font-weight: bold;">Luyện tập 2:Hãy giải thích ý nghĩa định dạng sau:</p>
    <p style="color: red;">.test .test_more {background-clor:red;}</p>
    <p>-test.test_more: Đây là một bộ chọn đồng thời (class selector) áp dụng cho các phần tử có cả hai lớp tên là "test" và "test_more". Điều này có nghĩa là chỉ các phần tử có cả hai lớp tên này sẽ được áp dụng định dạng. </p>
    <p>- background-color: red;: Đây là thuộc tính CSS được sử dụng để đặt màu nền (background-color) của các phần tử được chọn. Trong trường hợp này, màu nền của các phần tử có lớp tên "test" và "test_more" sẽ được đặt là đỏ (red).</p>
   <p style="color: red; font-weight: bold;">Vận dụng 1: Giả sử nội dung trang web của em có rất nhiều thẻ p, trong đó có ba đoạn mà em thấy quan trọng nhất, kí hiệu các đoạn này là P1, P2, P3. Có cách nào thiết lập định dạng CSS để có thể định dạng P1 khác biệt, P2 và P3 có cùng kiểu và cũng khác biệt không? Tất cả các đoạn còn lại có định dạng giống nhau. Hãy nêu cách giải quyết vấn đề của em </p>
    <p>Có.
Cách giải quyết: </p> 
	  <p>- Gắn một lớp tên riêng cho P1, ví dụ: <p class="important">Đoạn P1</p>. Đây là lớp tên dùng để định dạng đoạn P1. </p> 
		  <p>- Gắn cùng một lớp tên cho P2 và P3, ví dụ: <p class="normal">Đoạn P2</p> và <p class="normal">Đoạn P3</p>. Đây là lớp tên dùng để định dạng đoạn P2 và P3.</p> 
	  <p>- Sử dụng CSS để áp dụng các định dạng khác biệt cho các lớp tên tương ứng</p> 

    <p style="color: red; font-weight: bold;">Vận dụng 2: Có thể thiết lập định dạng cho các khung với thông số khung, viền trên, dưới, trái, phải khác nhau được không? Em hãy tìm hiểu và trình bày cách thiết lập định dạng CSS cho các khung, viền như vậy.
Có, bạn có thể thiết lập định dạng khác nhau cho các khung và viền trên, dưới, trái, phải bằng cách sử dụng thuộc tính CSS border và các thuộc tính liên quan.</p>
<p>Có, bạn có thể thiết lập định dạng khác nhau cho các khung và viền trên, dưới, trái, phải bằng cách sử dụng thuộc tính CSS border và các thuộc tính liên quan.
Cách thiết lập định dạng CSS cho các khung và viền như vậy như sau:</p>
    <p>- Sử dụng thuộc tính border để định dạng viền của khung. </p>
    <p>-Để thiết lập viền khác nhau cho các cạnh, bạn có thể sử dụng các thuộc tính border-top, border-bottom, border-left và border-right để chỉ định viền cho từng cạnh riêng biệt.</p>
	
	<a href="NHOM1-12L.html"> Quay lại trang chủ</a>
</body>
</html>
<html lang="en">
<style>
      h1{color: white;
      background:  #6ab04c;
      border: 70px solid #6ab04c;
	}
</style>

  <body>
 
 <h1>Bài 17: CÁC MỨC ƯU TIÊN CỦA BỘ</h1>
    <p style="color: #C4E538; font-weight: bold; font-size: 1.2em;">Luyện tập 1: Giải thích sự khác nhau giữa hai định dạng sau:</p>
     <p> #p123 + p {color: red;} </p> 

     <p> h2#p123 + p {color: red;}</p>  
   <p>• #p123 + p {color: red;} : áp dụng cho phần tử p với điều kiện phần tử p nằm ngay sau phần tử bất kì có mã định danh #p123</p>

  <p>•h2#p123 + p {color: red;}: áp dụng cho phần tử p với điều kiện phần tử p nằm ngay sau phần tử h2 có mã định danh #p123</p>

    <p style="color: #A3CB38; font-weight: bold; font-size: 1.2em;">Luyện tập 2:Trong phần Thực hành, các tên riêng (tên người, tên tổ chức) cần được bổ sung định dạng đóng khung và in nghiêng. Em sẽ thực hiện các yêu cầu này như thế nào?</p>
   <p>• Đưa các tên riêng vào thẻ < em>... < / em > </p>

   <p>• Tạo mẫu định dạng CSS cho phần tử < em >: em {font-style: italic; border: 1px solid blue;}</p>

   <p style="color: #009432; font-weight: bold; font-size: 1.2em;"> Vận dụng 1: Tìm hiểu thêm các dạng pseudo-class khác, nêu ý nghĩa và tìm ví dụ ứng dụ thực tế cho các kiểu bộ chọn này</p>
     <p>Các trạng thái của phần tử input:</p>

     <p>•checked: được chọn (type=checkbox)</p>

     <p>•focus: được chọn (type=text</p>

     <p>•enabled: sẵn sàng nhập dữ liệu</p>

     <p>•disabled: vô hiệu hóa phần tử input</p>

     <p>•valid: có hiệu lực</p>

     <p>•invalid: không có hiệu lực</p>

 <img src="124.png" width="831" height="227" alt="Ảnh minh họa">

<code><style></code>
<code>input:checked {height: 50px; width: 50px;}</code>

<code>input: valid {background-color: yellow;}</code>

<code>input: invalid {background-color: magenta;}</code>

<code>input[type=text]: enabled {background: cyan;}</code>

<code>input[type=text]: disabled {background: silver;}</code>

<code></style></code>
<img src="125.png" width="713" height="425" alt="Ảnh minh họa">
<p><html>

<head>

<style>

input:checked (height: 50px; width: 50px;}

input: valid {background-color: #6ab04c;}

input: invalid (background-color: magenta;}

input[type=text]: enabled {background: cyan;}

input[type=text]: disabled {background: silver;}

</style>

</head>

<body>

<form action="">

First name: <input type="text" name="firstname"><br><br>

Last name: <input type="text" name="lastname"><br><br>

Email: <input type="email"><br><br>

Country: <input type="text" disabled="disabled" value="Viet Nam"><br><br>

<input type="checkbox" value="Bike"> I have a bike<br>

<input type="checkbox" value="Car"> I have a car<br>

</form>

</body>

</html></p>
<p style="color: #006266; font-weight: bold; font-size: 1.2em;"> Vận dụng 2: Tìm hiểu thêm các dạng pseuso-element khác, nêu ý nghĩa và tìm ví dụ ứng dụng thực tế cho các kiểu bộ chọn này.</p>
 <p>Các phần tử giả:</p>

 <p>•before: thành phần phía trước</p>

 <p>•after: thành phần phía sau</p>

 <p>•marker: thành phần đánh dấu</p>

<p><style></p>
<p>h1::before {content: url(smiley.gif);}</p>

<p>h1::after {content: url(smiley.gif);}</p>

<p>::marke {color: red; font-size: 23px;}</p>

<p></style></p>
<img src="126.png" width="447" height="467" alt="Ảnh minh họa">
 <p><style>
<p><html>

<head>

<style>

h1::before {content: url(smiley.gif);}

h1::after {content: url(smiley.gif);}

::marker {color: #6ab04c; font-size: 23px;}

</style>

</head>

<body>

<h1 style="background-color: #6ab04c;">This is a heading</h1>

<ul>

<li>Coffee</li>

<li>Tea</li>

<li>Milk</li>

</ul>

<ol>

<li>First</li>

<li>Second</li>

<li>Third</li>

</ol>
	 <a style="color: #44bd32"; href="NHOM1-12L.html"> Quay lại trang chủ</a>

</body>

</html></p>





 
</body>
</html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Đăng Ký Câu Lạc Bộ</title>
    <link rel="stylesheet" href="styles.css"> <!-- Liên kết file CSS -->
</head>
<style>
      h1{color: #d63031;
      background:  #ff7675;
      border: 70px solid #ff7675;
    	}
      h2{color: blue;
      font-weight: bold; 
      font-size: 1.2em;
        }
</style>
<body>
    <h1> Bài 18:Thực hành tổng hợp thiết kế trang web</h1>
    <h2> Luyện tập 1: Tạo trang dangki.html chứa biểu mẫu đăng kí câu lạc bộ và bổ sung liên kết tới trang dangki trong phần cuối trang của tất cả các trang </h2>
    <header>
        <h3>Đăng Ký Tham Gia Câu Lạc Bộ</h3>
    </header>
    <main>
        <form action="submit_form.php" method="POST">
            <label for="fullname">Họ và Tên:</label>
            <input type="text" id="fullname" name="fullname" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="phone">Số Điện Thoại:</label>
            <input type="tel" id="phone" name="phone" required>
            
            <label for="club">Chọn Câu Lạc Bộ:</label>
            <select id="club" name="club" required>
                <option value="bong_da">Bóng Đá</option>
                <option value="am_nhac">Âm Nhạc</option>
                <option value="nhiếp_anh">Nhiếp Ảnh</option>
                <option value="sach">Câu Lạc Bộ Sách</option>
            </select>
            <label for="message">Lời Nhắn:</label>
            <textarea id="message" name="message" rows="4"></textarea>
            <button type="submit">Đăng Ký</button>
        </form>
    </main>
  <footer>
     <p>&copy; 2025 Câu Lạc Bộ Trường Học</p>
  </footer>
  <h2> Luyện tập 2 trang 105 Tin học 12: Thay đổi định dạng và màu sắc của phông chữ trong các vùng khi di chuyển chuột qua.</h2>
  <p> Để thay đổi định dạng và màu sắc của phông chữ trong các vùng khi di chuyển chuột qua, em có thể sử dụng hiệu ứng hover trong CSS.</p>
  <p>  vung {</p>
<p>font-family: Arial, sans-serif;</p>
<p>font-size: 14px;</p>
<p>color: #333;</p>
         <p>}</p>
<p>.vung:hover {</p>
<p>font-size: 16px;</p>
<p>color: red;</p>
<p>font-weight: bold; </p>
            }
  <h2>Vận dụng : Để áp dụng thiết kế mới cho trang web đã tạo trong phần Thực hành, em cần thực hiện các bước sau:</h2>
  <p>- Tạo một tệp CSS mới và đặt tên là "style.css" (hoặc tên tùy chọn khác).</p>
  <p>- Trong tệp CSS, thêm mã CSS để định dạng các phần tử theo thiết kế mới.</p>
  <em>Ví dụ:</em>
  <em style=" font-weight: bold; font-size: 1.2em;>/* Định dạng phần banner */</em>
  <p>.banner {</p>
<p>background: url("../assets/img/bg-masthead.jpg") no-repeat center center;</p>
  <p>background-size: cover;</p>
  <p>padding-top: 12rem;</p>
  <p>padding-bottom: 12rem;</p>
  <p>text-align: center;</p>
  <p>color: darkred;</p>
  <p>}</p>
  <p>.banner h2 {</p>
  <p>font-size: 36px;</p>
  <p>font-weight: bold;</p>
  <p>}</p>
  <a href="NHOM1-12L.html"> Quay lại trang chủ</a>  
  <em style="font-weight: bold; font-size: 1.2em;>/* Định dạng phần slogan */</em>
  <p>.slogan {</p>
  <p>background-color: rgb(248, 249, 250);</p>
  <p>text-align: center;</p>
  <p>padding-right: 0.5rem;</p>
  <p>padding-left: 3rem;</p>
  <p>padding-top: 7rem;</p>
  <p>padding-bottom: 7rem;</p>
  <p>}</p>
  <p>.row {</p>
  <p>display: flex;</p>
  <p>flex-wrap: wrap;</p>
  <p>margin-top: -1;</p>
  <p>max-width: 100%;</p>
  <p>padding-right: 3rem;</p>
  <p>padding-left: 3rem;</p>
  <p>}</p>
  <p>.block_3 {</p>
  <p>flex: 0 0 33.33333333%;</p>
  <p>}</p>
  <p>.block_3 h3 {</p>
  <p>font-size: 24px;</p>
  <p>font-weight: bold;</p>
  <p>}</p>
  <p>.text-content {</p>
  <p>font-size: 16px;</p>
  <p>color: #333;</p>
  <p>}</p>               
 </body>
</html>
