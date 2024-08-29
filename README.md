<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class Introduction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            animation: changeBgColor 10s infinite;
        }

        @keyframes changeBgColor {
            0% { background-color: #3498db; }
            25% { background-color: #2ecc71; }
            50% { background-color: #e74c3c; }
            75% { background-color: #f1c40f; }
            100% { background-color: #9b59b6; }
        }

        .container {
            padding: 20px;
        }

        .avatar {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            border: 5px solid black; /* Added black border */
        }

        .class-info h1 {
            margin-bottom: 10px;
            color: #f39c12; /* Orange */
        }

        .class-info h3 {
            margin-bottom: 10px;
            font-weight: normal;
            color: #ecf0f1; /* Light Gray */
        }

        .class-info p {
            color: #e74c3c; /* Red */
        }

        .class-info .class-details {
            margin-top: 10px;
            color: #ecf0f1; /* Light Gray */
            font-style: italic;
        }

        .teacher-info p {
            margin-top: 20px;
            font-size: 1.2em;
            color: #1abc9c; /* Turquoise */
        }

        .posts {
            margin-top: 30px;
            text-align: left;
            max-width: 800px;
            margin: 30px auto;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
        }

        .posts h2 {
            color: #9b59b6; /* Purple */
        }

        .post h4 {
            margin: 0;
            font-size: 1.5em;
            border-bottom: 1px solid white;
            padding-bottom: 5px;
            color: #3498db; /* Blue */
        }

        .post p {
            margin: 10px 0 0;
            color: #2ecc71; /* Green */
        }

        .contact-info {
            margin-top: 40px;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
        }

        .contact-info h2 {
            margin-bottom: 20px;
            color: #e67e22; /* Carrot Orange */
        }

        .contact-info p {
            color: #ffffff; /* White */
        }

        .contact-info a {
            color: #1abc9c; /* Turquoise */
            text-decoration: none;
            font-weight: bold;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

    </style>
</head>
<body>
    <div class="container">
        <img src="https://upanh.tv/image/NPVlqQ" alt="Class Avatar" class="avatar">
        <div class="class-info">
            <h1>Class : 10P </h1>
            <h3>Slogan: Cái Gì Bạn Cần Chúng Tôi Không Có, Nhưng Những Thứ Bạn Có Chúng Tôi Lại Cần.</h3>
            <p class="class-details">Thông Tin Lớp Học</p> <!-- Added class information -->
            <p>Số Lượng Thành Viên: 44</p>
        </div>

        <div class="teacher-info">
            <p>Giáo Viên Chủ Nhiệm: Thầy Đoàn Anh Phiến</p>
            <p>Môn Dạy: Địa Lí</p>
        </div>

        <div class="posts">
            <h2>Những Điều Vô Tri:</h2>
            <div class="post">
                <h4>Bài 1: Mục Tiêu</h4>
                <p>Trên Trung Bình Môn Thầy Chủ Nhiệm=)))</p>
            </div>
            <div class="post">
                <h4>Bài 2: +N Phiếu Bầu Lớp Trưởng </h4>
                <p>Admin Và 42 Bạn Còn Lại Ở 10P Bầu Cho Bạn Hiền Minh Làm Cán Bộ Lớp, Cụ Thể Là Lớp Trưởng</p>
            </div>
        </div>

        <div class="contact-info">
            <h2>Liên Hệ Với Chúng Tôi</h2>
            <p>Email: <a href="mailto:">10p.k65.thpthungyen@gmail.com</a></p>
            <p>Fanpage Facebook: <a href="" target="_blank">https://www.facebook.com/profile.php?id=61564576756287</a></p>
            <p>TikTok: Đang Update</p>
        </div>
    </div>
</body>
</html>
