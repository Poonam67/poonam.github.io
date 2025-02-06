<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-color: #0d0d0d;
            color: #fff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #111;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
        }
        ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        li a {
            color: #fff;
            text-decoration: none;
            font-size: 18px;
        }
        .hero {
            text-align: center;
            padding: 100px 20px;
        }
        .highlight {
            background: linear-gradient(90deg, #ff00ff, #ffcc00);
            padding: 5px 10px;
            border-radius: 5px;
            color: #000;
            font-weight: bold;
        }
        .gradient-text {
            background: linear-gradient(90deg, #ff00ff, #00ffff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: bold;
        }
        .work-experience, .projects {
            padding: 50px 20px;
            text-align: center;
        }
        .cards {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        .card {
            background: #222;
            padding: 20px;
            border-radius: 10px;
            font-weight: bold;
            width: 200px;
            text-align: center;
            transition: 0.3s;
        }
        .card:hover {
            background: #333;
            transform: scale(1.05);
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #111;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">&#x292;</div>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Lab</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h1>Hello! I am <span class="highlight">Ibrahim Memon</span></h1>
        <h2>A Designer who <span class="gradient-text">Judges a book by its cover</span></h2>
        <p>Currently, I'm a Software Engineer at <a href="#">Facebook</a></p>
    </section>
    <section class="work-experience">
        <h2>Work Experience</h2>
        <div class="cards">
            <div class="card">CIB on the Mobile</div>
            <div class="card">CIB on the Mobile</div>
            <div class="card">CIB on the Mobile</div>
            <div class="card">CIB on the Mobile</div>
        </div>
    </section>
    <section class="projects">
        <h2>Example Project</h2>
        <p>A web app for visualizing personalized Spotify data.</p>
    </section>
    <footer>
        <p>Contact me at ibrahimmemon203@gmail.com</p>
    </footer>
</body>
</html>
