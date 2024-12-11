<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MayPhenol Linktree</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffe6e6;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            background-color: #ffc8c8;
            border-radius: 20px;
            padding: 20px;
            max-width: 350px;
            text-align: center;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }

        .profile-pic {
            border-radius: 50%;
            width: 100px;
            height: 100px;
            margin: 0 auto;
            display: block;
        }

        .name {
            font-size: 1.5em;
            font-weight: bold;
            margin: 10px 0;
        }

        .description {
            font-size: 1em;
            color: #555;
            margin-bottom: 20px;
        }

        .social-icons {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-bottom: 20px;
        }

        .social-icons a {
            display: inline-block;
            width: 40px;
            height: 40px;
            background-color: #fff;
            border-radius: 50%;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            display: flex;
            justify-content: center;
            align-items: center;
            transition: box-shadow 0.2s ease;
            animation: wave 2s infinite ease-in-out;
            /* 应用波浪动画 */
        }

        .social-icons a:nth-child(1) {
            animation-delay: 0s;
            /* 第一个图标立即开始 */
        }

        .social-icons a:nth-child(2) {
            animation-delay: 0.2s;
            /* 第二个图标延迟 0.2s */
        }

        .social-icons a:nth-child(3) {
            animation-delay: 0.4s;
            /* 第三个图标延迟 0.4s */
        }

        /* 鼠标悬停时停止当前按钮动画 */
        .social-icons a:hover {
            animation-play-state: paused;
            /* 暂停动画 */
            transform: translateY(-3px);
            /* 上升，增强悬停效果 */
            box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.3);
            /* 悬停阴影效果 */
        }

        @keyframes wave {

            0%,
            100% {
                transform: translateY(0);
            }

            50% {
                transform: translateY(-5px);
                /* 向上移动 5px */
            }
        }


        .social-icons img {
            width: 20px;
            height: 20px;
        }

        @keyframes float {

            0%,
            100% {
                transform: translateY(0);
            }

            50% {
                transform: translateY(-2px);
                /* 向上移动 2px */
            }
        }

        .links a {
            display: block;
            background-color: #ff9e9e;
            color: #000;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 10px;
            padding: 10px 15px;
            margin: 10px 0;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            animation: float 2s infinite ease-in-out;
            /* 添加动画 */
            transition: box-shadow 0.2s ease;
            /* 让悬浮阴影效果依然生效 */
        }

        .links a:hover {
            animation-play-state: paused;
            /* 暂停动画 */
            transform: translateY(-3px);
            /* 上升，增强悬停效果 */
            box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.3);
            /* 悬停阴影效果 */
        }

        .links a:active {
            transform: translateY(2px);
            box-shadow: 1px 1px 5px rgba(0, 0, 0, 0.2);
        }


        .footer {
            margin-top: 20px;
            font-size: 0.8em;
            color: #777;
        }
    </style>
</head>

<body>
    <div class="container">
        <img src="avatar.jpg" alt="Profile Picture" class="profile-pic">
        <div class="name">MayPhenol</div>
        <div class="description">✨Creative mind | Sharing inspiration & good vibes ✨ Let's connect!</div>
        <div class="social-icons">
            <a href="https://www.youtube.com/@MayPhenol" target="_blank"><img src="youtube-icon.png" alt="YouTube"></a>
            <a href="https://x.com/MayPhenol" target="_blank"><img src="x-icon.png" alt="X"></a>
            <a href="https://github.com/mayphenol" target="_blank"><img src="github-icon.png" alt="GitHub"></a>
        </div>
        <div class="links">
            <a href="https://mayphenol.usells.com/" target="_blank">→甜品店</a>
            <a href="https://perohub.com/users/659ec37175ac153c2e3136b0" target="_blank">→Store (PayPal available)</a>
            <a href="https://afdian.com/a/mayphenol" target="_blank">→爱发电</a>
            <a href="https://t.co/7t9rv6eIDw" target="_blank">→哔哩哔哩Bilibili</a>
            <a href="https://v.douyin.com/iDT36PA2" target="_blank">→抖音Tiktok</a>
        </div>
        <div class="footer">MayPhenol</div>
    </div>
</body>

</html>
