<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>给牧野的专属告白信 💌</title>
    <style>
        body {
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0;
            font-family: '楷体', cursive;
        }

        .love-box {
            background: rgba(255, 255, 255, 0.95);
            padding: 2rem;
            border-radius: 20px;
            box-shadow: 0 0 30px rgba(255, 105, 180, 0.4);
            text-align: center;
            animation: heartbeat 1.5s infinite;
            max-width: 90%; /* 手机屏幕适配 */
        }

        h1 {
            color: #ff1493;
            margin: 1rem 0;
            font-size: 2.2rem;
        }

        /* 新增图片样式 */
        .love-photo {
            width: 220px;         /* 调节图片大小 */
            border-radius: 15px;  /* 圆角程度 50%变圆形 */
            margin: 15px auto;
            border: 3px solid #ff69b4;
            box-shadow: 0 8px 20px rgba(255, 105, 180, 0.3);
            transition: transform 0.3s; /* 悬停动画 */
        }

        .love-photo:hover {
            transform: scale(1.05); /* 悬停放大效果 */
        }

        .signature {
            color: #666;
            margin-top: 1.5rem;
            font-style: italic;
            font-size: 1.1rem;
        }

        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.03); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="love-box">
        <!-- 在此处替换为你的图片文件名 -->
        <img src="muye-photo.jpg" 
             alt="牧野的照片" 
             class="love-photo">

        <h1>牧野，我喜欢你！❤️</h1>
        <h1>Muye, I Love You! 💖</h1>
        
        <p class="signature">
            —— 古吉的心意随风而至 🍃<br>
            (っ◔◡◔)っ ♥
        </p>
    </div>
</body>
</html>