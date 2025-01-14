<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wtfgrotesque? Bio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: white;
            overflow: hidden;
            background: black;
        }

        .stars {
            position: absolute;
            width: 100%;
            height: 100%;
            background: radial-gradient(white, transparent 70%);
            animation: moveStars 50s linear infinite;
            background-size: 200% 200%;
        }

        @keyframes moveStars {
            0% { background-position: 0 0; }
            100% { background-position: -1000px -1000px; }
        }

        .bio-container {
            position: relative;
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.8);
            margin: 50px auto;
            border-radius: 10px;
            width: 90%;
            max-width: 600px;
        }

        .bio-container img.profile-pic {
            width: 100%;
            max-width: 600px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .bio-container h1 {
            margin: 10px 0;
            font-size: 2rem;
        }

        .bio-container p {
            margin: 5px 0;
        }

        .bio-container .highlight {
            color: lime;
        }

        .button-container {
            margin-top: 20px;
        }

        .button-container a {
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            background: white;
            color: black;
            font-size: 16px;
            padding: 10px 20px;
            border-radius: 5px;
            width: fit-content;
            margin: 0 auto;
        }

        .button-container a img {
            width: 20px;
            height: 20px;
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <div class="stars"></div>
    <div class="bio-container">
        <img class="profile-pic" src="https://i.imgur.com/OGcZD1Q.jpeg" alt="Profile Picture">
        <h1>Wtfgrotesque? Bio</h1>
        <p><strong>Имя:</strong> Артур</p>
        <p><strong>Возраст:</strong> 69 лет (15 ноября)</p>
        <p><strong>Устройство:</strong> iPhone 11</p>
        <p><strong>Язык:</strong> Русский, Английский</p>
        <p><strong>Хобби:</strong> Игры (Dota 2, MLBB)</p>
        <p><strong>Высший ранг в MLBB:</strong> Mythical Fame</p>
        <p><strong>Хост юзербота:</strong> <span class="highlight">TotHost💘</span></p>
        <div class="button-container">
            <a href="https://t.me/wtfgrotesque" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" alt="Telegram Logo">
                Написать
            </a>
        </div>
    </div>
</body>
</html>
