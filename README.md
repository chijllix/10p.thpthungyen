<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thông tin lớp</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .profile-card {
            width: 100%;
            max-width: 350px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            padding: 20px;
            box-sizing: border-box;
            display: flex;
            align-items: center;
        }

        #avt {
            border-radius: 50%;
            border: 3px solid #333;
            width: 80px;
            height: 80px;
            margin-right: 20px;
        }

        .profile-details {
            flex-grow: 1;
        }

        .profile-details h1 {
            font-size: 1.5em;
            margin: 0;
            color: #333;
        }

        .profile-details h2 {
            font-size: 1.2em;
            margin: 5px 0;
            color: #666;
        }

        .profile-bio {
            margin-top: 10px;
        }

        .profile-bio p {
            margin: 0;
            font-size: 1em;
            color: #333;
        }

        .profile-info {
            display: none;
            margin-top: 10px;
            font-size: 0.9em;
            color: #666;
        }

        .profile-info p {
            margin: 5px 0;
        }

        .toggle-info {
            margin-top: 10px;
            cursor: pointer;
            color: #007bff;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <img id="avt" src="https://i.upanh.org/2024/08/29/10p477f7a09a3e43344.jpeg" alt="Avatar" />
        <div class="profile-details">
            <h1 id="name">10P</h1>
            <h2 id="nickname">Tóp Tóp</h2>
            <div class="profile-bio">
                <p id="bio">Thông tin lớp</p>
            </div>
            <div class="profile-info" id="profileInfo">
                <p>Số lượng thành viên: 30</p>
                <p>Giáo viên: Cô Nguyễn</p>
                <p>Môn dạy: Toán, Lý, Hóa</p>
            </div>
            <div class="toggle-info" id="toggleInfo">Xem thêm</div>
        </div>
    </div>
 <script>
        const toggleInfo = document.getElementById('toggleInfo');
        const profileInfo = document.getElementById('profileInfo');

        toggleInfo.addEventListener('click', () => {
            if (profileInfo.style.display === 'none' || profileInfo.style.display === '') {
                profileInfo.style.display = 'block';
                toggleInfo.textContent = 'Ẩn bớt';
            } else {/-strong/-heart:>:o:-((:-hprofileInfo.style.display = 'none';
                toggleInfo.textContent = 'Xem thêm';
            }
        });
    </script>
</body>
</html>
