<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Python Moment</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: radial-gradient(circle, #1f1c2c, #928dab);
            font-family: Consolas, monospace;
            color: #ffffff;
        }

        .container {
            text-align: center;
            background: rgba(0, 0, 0, 0.4);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 0 25px rgba(0,0,0,0.6);
            animation: muncul 1.5s ease;
        }

        .text {
            font-size: 28px;
            font-weight: bold;
        }

        @keyframes muncul {
            from {
                opacity: 0;
                transform: scale(0.8);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="text">
        gilaa, pemograman pyton bjirr😱🙏
    </div>
</div>

</body>
</html>
