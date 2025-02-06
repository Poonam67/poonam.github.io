<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0d0d0d;
            color: white;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #111;
            padding: 15px 0;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }
        .logo {
            font-size: 24px;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        .hero {
            margin: 50px 0;
        }
        .highlight {
            background: linear-gradient(90deg, #ff00ff, #ffcc00);
            padding: 5px 10px;
            border-radius: 5px;
        }
        .gradient-text {
            background: linear-gradient(90deg, #ff00ff, #00ffff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .blue {
            color: #008cff;
        }
        .experience {
            margin: 50px 0;
        }
        .experience-container {
            display: flex;
            justify-content: center;
            gap: 10px;
        }
        .experience-card {
            background: #222;
            padding: 15px;
            border-radius: 10px;
        }
        .projects {
            margin: 50px 0;
        }
        .project-card {
            background: #222;
            padding: 20px;
            border-radius: 10px;
            display: inline-block;
            text-align: left;
        }
        .project-card img {
            width: 100%;
            border-radius: 5px;
        }
        footer {
            margin-top: 50px;
            padding: 20px;
            background: #111;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">&#x2728;</div>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Lab</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h1>Hello! I am <span class="highlight">Ibrahim Memon</span></h1>
        <p>A Designer who <span class="gradient-text">Judges a book by its cover</span></p>
        <p>Currently, I'm a Software Engineer at <span class="blue">Facebook</span></p>
    </section>
    <section class="experience">
        <h2>Work Experience</h2>
        <div class="experience-container">
            <div class="experience-card">CIB on the Mobile</div>
            <div class="experience-card">CIB on the Mobile</div>
            <div class="experience-card">CIB on the Mobile</div>
            <div class="experience-card">CIB on the Mobile</div>
        </div>
    </section>
    <section class="projects">
        <h2>Featured Project</h2>
        <div class="project-card">
            <img src="project-image.png" alt="Project Screenshot">
            <p>A web app for visualizing personalized Spotify data...</p>
        </div>
    </section>
    <footer>
        <p>Contact: ibrahimmemon203@gmail.com</p>
    </footer>
</body>
</html>
