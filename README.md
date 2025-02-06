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
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background: #111;
        }
        .logo {
            font-size: 24px;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: #fff;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
        }
        .highlight {
            background: linear-gradient(90deg, #ff00ff, #ffcc00);
            padding: 5px 10px;
            border-radius: 5px;
        }
        .gradient-text {
            color: cyan;
        }
        .blue {
            color: #3498db;
        }
        .experience {
            text-align: center;
            padding: 50px 20px;
        }
        .experience-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .experience-card {
            background: #222;
            padding: 15px 20px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .projects {
            text-align: center;
            padding: 50px 20px;
        }
        .project-card {
            background: #222;
            padding: 20px;
            border-radius: 8px;
            display: inline-block;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #111;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">✨ Portfolio</div>
        <nav>
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
            <div class="experience-card">CIB on the Mobile - UI/UX Designer</div>
            <div class="experience-card">CIB on the Mobile - Frontend Developer</div>
            <div class="experience-card">CIB on the Mobile - Product Designer</div>
            <div class="experience-card">CIB on the Mobile - Software Engineer</div>
        </div>
    </section>
    <section class="projects">
        <h2>Featured Project</h2>
        <div class="project-card">
            <img src="project-image.png" alt="Project Screenshot" width="300">
            <p>A web app for visualizing personalized Spotify data...</p>
        </div>
    </section>
    <footer>
        <p>Contact: ibrahimmemon203@gmail.com</p>
    </footer>
</body>
</html>
