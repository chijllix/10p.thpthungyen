<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Card</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #f0f0f0;
        }

        .profile-card {
            width: 100%;
            max-width: 350px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
            padding: 20px;
            box-sizing: border-box;
        }

        #avt {
            border-radius: 50%;
            border: 5px solid black;
            width: 100px;
            height: 100px;
        }

        .profile-social-links {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 10px;
        }

        .profile-social-links li a {
            display: inline-block;
            text-decoration: none;
        }

        svg {
            width: 24px;
            height: 24px;
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <header>
            <a href="#">
                <img id="avt" src="https://i.upanh.org/2024/08/29/10p477f7a09a3e43344.jpeg" alt="Avatar" />
            </a>
            <h1 id="name">10P</h1>
            <h2 id="nickname">Tóp Tóp</h2>
        </header>
        <div class="profile-bio">
            <p id="bio">Ghi gì đó ở đây</p>
        </div>
        <ul class="profile-social-links">
            <li>
                <a id="linkFb" href="https://www.facebook.com/10P">
                    <svg viewBox="0 0 24 24">
                        <path fill="#3b5998" d="M17,2V2H17V6H15C14.31,6 14,6.81 14,7.5V10H14L17,10V14H14V22H10V14H7V10H10V6A4,4 0 0,1 14,2H17Z" />
                    </svg>
                </a>
            </li>
            <li>
                <a id="linkMes" href="//m.me/10P">
                    <svg viewBox="0 0 24 24">
                        <path fill="#0084ff" d="M12,2A10,10 0 0,0 2,12C2,16.84 5.64,20.65 10.5,21.74V15H7.5V12H10.5V9.5C10.5,7.29 11.97,6 14,6A5.5,5.5 0 0,1 16.5,6.14V9H14.5C13.4,9 13,9.75 13,10.5V12H16.5L16,15H13V21.74C17.86,20.65 21.5,16.84 21.5,12A10,10 0 0,0 12,2Z" />
                    </svg>
                </a>
            </li>
        </ul>
    </div>
</body>
