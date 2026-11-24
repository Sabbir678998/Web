# Web
#HTML
#
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f0f4ff;
            color: #222;
        }

        header {
            background: #222b55;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #39477c;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 10px;
        }

        .hero {
            text-align: center;
            padding: 80px 20px;
            background: #dce5ff;
        }

        .hero h1 {
            font-size: 35px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 17px;
            margin-bottom: 25px;
        }

        button {
            background: #39477c;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
        }

        section {
            padding: 40px 20px;
            text-align: center;
        }

        .card {
            background: white;
            padding: 25px;
            margin: 15px auto;
            max-width: 400px;
            border-radius: 12px;
            box-shadow: 0 3px 12px #0001;
        }

        footer {
            background: #222b55;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h2>My Website</h2>
        <p>Welcome to my first website!</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero" id="home">
        <h1>Hello, World! 👋</h1>
        <p>Welcome to my personal website.</p>
        <button onclick="alert('Thank you for visiting!')">
            Click Me
        </button>
    </div>

    <section id="about">
        <h2>About Me</h2>
        <div class="card">
            <p>Hello! I am a beginner web developer.</p>
            <p>I am learning HTML and CSS.</p>
        </div>
    </section>

    <section id="skills">
        <h2>My Skills</h2>
        <div class="card">
            <p>🌐 HTML</p>
            <p>🎨 CSS</p>
            <p>💻 JavaScript (Learning)</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <div class="card">
            <p>Thanks for visiting my website!</p>
            <p>See you again. ❤️</p>
        </div>
    </section>

    <footer>
        <p>© 2026 My Website</p>
    </footer>

</body>
</html>
