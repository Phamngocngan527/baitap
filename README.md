# baitap
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

   <p style="color: #009432; font-weight: bold; font-size: 1.2em;"> Vận dụng 1: Tìm hiểu thêm các dạng pseudo-class khác, nêu ý nghĩa và tìm ví dụ ứng dụ thực tế cho các kiểu bộ chọn này</p>
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
