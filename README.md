<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WinSub - Social Media Marketing</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: url('https://anhdepfree.com/wp-content/uploads/2021/12/background-den-cong-nghe_552489-768x432.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
        }

        .top-bar {
            display: flex;
            justify-content: flex-end;
            padding: 10px 20px;
        }

        .top-bar button {
            margin: 0 5px;
            padding: 10px 20px;
            background: rgba(0, 0, 0, 0.7);
            border: 2px solid white;
            color: white;
            cursor: pointer;
            border-radius: 5px;
            font-size: 14px;
	    font-weight: bold;  /* Thêm dòng này để làm chữ đậm */
        }

        .top-bar button:hover {
            background: white;
            color: black;
        }

        .container {
            text-align: center;
            padding: 100px 20px;
        }

        .container h1 {
            margin: 20px 0;
            font-size: 37px;
            font-weight: bold;
        }

        .container p {
            font-size: 25px;
            color: gray;
        }

        .button-group {
            margin: 20px 0;
        }

        .button-group button {
            margin: 0 10px;
            padding: 10px 20px;
            background: rgba(0, 0, 0, 0.7);    					 
            border: 2px solid white;
            color: white;
            cursor: pointer;
            border-radius: 5px;
            font-size: 16px;
	    font-weight: bold;  /* Thêm dòng này để làm chữ đậm */
        }

        .button-group button:hover {
            background: white;
            color: black;
        }

        .features, .category {
            margin: 50px auto;
            width: 90%;
            max-width: 1200px;
            background: rgba(0, 0, 0, 0.7);
            padding: 30px;
            border-radius: 10px;
        }

        .features h2 {
            font-size: 30px;
            margin-bottom: 20px;
        }

        .features .feature-title {
            font-size: 24px;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
            color: white;
        }

        .footer-columns {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            color: gray;
            font-size: 14px;
        }

        .footer-columns div h3 {
            font-size: 16px;
            font-weight: bold;
            color: white;
        }

        .footer-columns div a {
            color: gray;
            text-decoration: none;
            margin: 5px 0;
            display: block;
        }

        .footer-columns div a:hover {
            color: white;
        }

     	.popup {
    	   position: fixed;
 	   top: 50%;
      	   left: 50%;
    	   transform: translate(-50%, -50%);
    	   background: black;
    	   color: red;
    	   padding: 20px;
    	   border-radius: 10px;
    	   text-align: center;
     	   z-index: 1000;
    	   display: none;
    	   font-weight: bold;  /* Thêm dòng này để làm chữ đậm */
        }

        .popup a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: white;
            color: black;
            text-decoration: none;
            border-radius: 5px;
        }

        .popup a:hover {
            background: black;
            color: white;
        }

        .popup .close-btn {
            position: absolute;
            top: 10px;
            right: 10px;
            font-size: 20px;
            font-weight: bold;
            background: transparent;
            color: white;
            border: none;
            cursor: pointer;
        }

        .popup .close-btn:hover {
            color: white;
        }
    </style>
</head>
<body>
    <!-- Top Bar -->
    <div class="top-bar">
        <button onclick="goHome()">Trang Chủ</button>
    </div>

    <!-- Main Content -->
    <div class="container">
        <h1>CHÀO MỪNG BẠN ĐÃ ĐẾN VỚI <span style="color: #FF69B4;">WINSUB</span> HỆ THỐNG DỊCH VỤ MẠNG XÃ HỘI</h1>
        <h1>SOCIAL MEDIA MARKETING 2024</h1>
        <p>Nền Tảng Tăng Tương Tác Uy Tín Và Tin Cậy Nhất Cho Các Dịch Vụ Truyền Thông Mạng Xã Hội.</p>
        <div class="button-group">
            <button onclick="showPopup()">Đăng Nhập</button>
            <button onclick="showPopup()">Đăng Ký</button>
        </div>
    </div>

    <!-- Features Section -->
    <div class="features">
        <h2>Đặc Trưng ⭐️⭐️⭐️⭐️⭐️</h2>
        <p class="feature-title">   Gia tăng lợi nhuận📊</p>
        <p>Tạo ra lợi nhuận cho khách hàng là sứ mệnh của chúng tôi.</p>
        <p class="feature-title">   Quản lý bảo mật🔒</p>
        <p>Cam kết bảo mật thông tin khách hàng tuyệt đối.</p>
        <p class="feature-title">   Quản lý và hỗ trợ📲</p>
        <p>Đồng hành cùng sự phát triển của bạn.</p>
    </div>
    <div class="category">
        <div>
            <h2>Nền Tảng Tăng Tương Tác Uy Tín Và Tin Cậy Nhất</h2>
            <p>Những Gì Bạn Cần Tăng - Chúng Tôi Có Cung Cấp.</p>
            <ul>
                <li>✔ Dịch vụ Facebook 🥑</li>
                <li>✔ Dịch vụ TikTok 🍒</li>
                <li>✔ Dịch vụ Instagram 🍍</li>
                <li>✔ Dịch vụ Telegram 🍇</li>
                <li>✔ Dịch vụ YouTube 🍅</li>
		<li>✔ Dịch vụ Threads 💐</li>
                <li>✔ Dịch vụ X - Twitter 🎃</li>
                <li>✔ Nhiều dịch vụ khác</li>
            </ul>
        </div>
    </div>
    <!-- Footer -->
    <footer>

        <p>© 2024 WINSUB. Quản lý vận hành bởi : 
  <a href="https://www.facebook.com/WinSub1/" target="_blank" 
   style="color: #00FFCC; font-weight: bold; font-size: 20px; text-decoration: none; transition: all 0.3s ease;"
   onmouseover="this.style.textShadow = '0 0 5px #FF00FF, 0 0 10px #FF00FF, 0 0 15px #FF00FF, 0 0 20px #FF6347, 0 0 30px #FF6347, 0 0 40px #FF6347, 0 0 50px #FF6347'; this.style.color = '#FF6347';"
   onmouseout="this.style.textShadow = ''; this.style.color = '#00FFCC';">Lê Văn Trọng</a>

</p>
        <div class="footer-columns">
            <div>
                <h3>Sản phẩm</h3>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Trang chủ</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Đặc trưng</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Tài liệu</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Giới thiệu</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Định giá</a>
            </div>
            <div>
                <h3>Danh sách</h3>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Tài liệu</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Thiết kế</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Chủ đề</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Minh họa</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">UI kit</a>
            </div>
            <div>
                <h3>Nhiều hơn</h3>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Liên hệ</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Điều kiện</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Chính sách bảo mật</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Giấy phép</a>
                <a href="https://www.facebook.com/WinSub1/" target="_blank">Hỗ trợ</a>
            </div>
        </div>
    </footer>

    <!-- Popup -->
    <div class="popup" id="popup">
        <button class="close-btn" onclick="closePopup()">x</button>
        <p> ⚠️ Web Đang Bị Delay - Liên Hệ Admin Để Hỗ Trợ </p>
        <a href="https://www.facebook.com/WinSub1/" target="_blank">Liên Hệ Admin</a>
    </div>

    <script>
        function showPopup() {
            document.getElementById('popup').style.display = 'block';
        }

        function closePopup() {
            document.getElementById('popup').style.display = 'none';
        }

        function goHome() {
            alert("⚠️ Web Đang Bị Delay - Liên Hệ Admin Để Hỗ Trợ ");
        }
    </script>
</body>
</html>
