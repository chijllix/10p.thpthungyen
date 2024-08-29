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
            color: white;
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
        }

        .class-info {
            margin-top: 20px;
        }

        .class-info h1 {
            margin-bottom: 10px;
        }

        .class-info h3 {
            margin-bottom: 20px;
            font-weight: normal;
        }

        .teacher-info {
            margin-top: 20px;
            font-size: 1.2em;
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

        .post {
            margin-bottom: 20px;
        }

        .post h4 {
            margin: 0;
            font-size: 1.5em;
            border-bottom: 1px solid white;
            padding-bottom: 5px;
        }

        .post p {
            margin: 10px 0 0;
        }

        .contact-info {
            margin-top: 40px;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
        }

        .contact-info h2 {
            margin-bottom: 20px;
        }

        .contact-info a {
            color: #1abc9c;
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
        <img src="link_to_class_avatar.jpg" alt="Class Avatar" class="avatar">
        <div class="class-info">
            <h1>Tên lớp: Lớp 12A1</h1>
            <h3>Slogan: "Học hết mình, chơi hết sức"</h3>
            <p>Số lượng thành viên: 35</p>
        </div>

        <div class="teacher-info">
            <p>Giáo viên chủ nhiệm: Thầy Nguyễn Văn A</p>
            <p>Môn dạy: Toán học</p>
        </div>

        <div class="posts">
            <h2>Bài viết lớp học:</h2>
            <div class="post">
                <h4>Bài viết 1: Hoạt động ngoại khóa</h4>
                <p>Nội dung bài viết 1...</p>
            </div>
            <div class="post">
                <h4>Bài viết 2: Cuộc thi học sinh giỏi</h4>
                <p>Nội dung bài viết 2...</p>
            </div>
        </div>

        <div class="contact-info">
            <h2>Liên hệ với chúng tôi</h2>
            <p>Email: <a href="mailto:yourclass@gmail.com">yourclass@gmail.com</a></p>
            <p>Fanpage Facebook: <a href="https://facebook.com/yourclass" target="_blank">facebook.com/yourclass</a></p>
            <p>TikTok: <a href="https://tiktok.com/@yourclass" target="_blank">@yourclass</a></p>
        </div>
    </div>
</body>
</html>
