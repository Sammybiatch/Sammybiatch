<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samoya's Blog</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Press Start 2P', cursive, sans-serif;
            background: linear-gradient(135deg, #ffd1dc, #ffe7a9, #bde0fe, #ffb3ba);
            color: #333;
            min-height: 100vh;
            padding: 20px;
        }

        h1, h2, h3, p {
            margin-bottom: 1rem;
        }

        /* Header */
        header {
            text-align: center;
            margin-bottom: 40px;
        }

        header h1 {
            font-size: 2.5rem;
            color: #ffffff;
            text-shadow: 3px 3px 0px #ff6f91, 6px 6px 0px #ffc75f;
        }

        /* Blog Layout */
        .blog-container {
            max-width: 900px;
            margin: 0 auto;
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
            overflow: hidden;
        }

        .blog-header {
            background: linear-gradient(135deg, #ff9aa2, #ffb7b2);
            padding: 20px;
            text-align: center;
        }

        .blog-header h2 {
            font-size: 1.8rem;
            color: #fff;
        }

        .blog-content {
            padding: 20px;
        }

        .post {
            margin-bottom: 20px;
        }

        .post-title {
            font-size: 1.5rem;
            color: #ff6f91;
            margin-bottom: 10px;
        }

        .post-content {
            font-size: 1rem;
            line-height: 1.5;
            color: #333;
        }

        .post-content a {
            color: #ff6f91;
            text-decoration: none;
            font-weight: bold;
        }

        /* Footer */
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.8rem;
            color: #666;
        }

        /* Doodle Style */
        .doodle {
            position: absolute;
            z-index: -1;
            width: 100px;
            height: 100px;
            background-size: cover;
        }

        .doodle1 {
            top: 20px;
            left: 20px;
            background-image: url('https://via.placeholder.com/100x100.png?text=Doodle+1');
        }

        .doodle2 {
            bottom: 20px;
            right: 20px;
            background-image: url('https://via.placeholder.com/100x100.png?text=Doodle+2');
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
</head>
<body>
    <div class="doodle doodle1"></div>
    <div class="doodle doodle2"></div>

    <header>
        <h1>Samoya's Cute Blog</h1>
    </header>

    <div class="blog-container">
        <div class="blog-header">
            <h2>Welcome to My World of Cute Things</h2>
        </div>
        <div class="blog-content">
            <div class="post">
                <h3 class="post-title">🌸 My First Post</h3>
                <p class="post-content">Welcome to my blog! This is where I’ll share adorable ideas, doodles, and all the cute things I love. Stay tuned! 🌼</p>
            </div>
            <div class="post">
                <h3 class="post-title">🎨 Latest Doodle</h3>
                <p class="post-content">Check out my latest doodle project <a href="#">here</a>. Let me know what you think! 💕</p>
            </div>
        </div>
    </div>

    <footer>
        &copy; 2024 Samoya. Designed with pastel vibes and retro love.
    </footer>
</body>
</html>
