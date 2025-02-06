<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: white;
            text-align: center;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #1e1e1e;
        }
        .nav-menu {
            list-style: none;
            display: flex;
            gap: 50px;
            margin: 0;
            padding: 0;
        }
        .nav-menu li {
            display: inline;
        }
        .nav-menu a {
            text-decoration: none;
            color: white;
            font-size: 18px;
        }
        nav {
            margin-left: auto;
        }
        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 50vh;
        }
        .experience-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 20px;
        }
        .experience-card {
            background-color: #232323;
            padding: 20px;
            border-radius: 10px;
            width: 60%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            margin-bottom: 20px;
            text-align: left;
            position: relative;
        }
        .experience-card::before {
            content: "";
            position: absolute;
            left: -10px;
            top: 10px;
            width: 5px;
            height: 90%;
            background-color: #ff9800;
            border-radius: 5px;
        }
        .experience-card h3 {
            margin: 10px 0;
            color: #ff9800;
        }
        .experience-card p {
            margin: 5px 0;
        }
        .projects {
            margin: 40px 0;
            text-align: center;
        }
        .project-card {
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #232323;
            padding: 20px;
            border-radius: 10px;
            width: 60%;
            margin: 0 auto;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .project-card img {
            width: 150px;
            height: auto;
            border-radius: 10px;
            margin-right: 20px;
        }
        .project-card div {
            text-align: left;
        }
        .project-card h3 {
            margin: 0 0 10px;
            color: #ff9800;
        }
        h1:first-of-type {
            display: none;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">&#x2728;Portfolio</div>
        <nav>
            <ul class="nav-menu">
                <li><a href="#">About</a></li>
                <li><a href="#">Experience</a></li>
                <li><a href="#">Skills</a></li>
                <li><a href="#">Project</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <img src="media/logo.jpg" alt="Profile Picture">
        <div class="hero-content">
            <h1>Hello! I am <span class="highlight">Poonam kalra</span></h1>
            <p>A Designer who <span class="gradient-text">Judges a book by its cover</span></p>
            <p>Currently, I'm a Software Engineer at <span class="blue">Facebook</span></p>
        </div>
    </section>
    <section class="experience">
        <h2>Work Experience</h2>
        <div class="experience-container">
            <div class="experience-card">
                <h3>Software Engineer at Facebook</h3>
                <p>Developing scalable web applications and leading frontend development for multiple projects.</p>
                <p><strong>Duration:</strong> 2022 - Present</p>
            </div>
            <div class="experience-card">
                <h3>Frontend Developer at Google</h3>
                <p>Worked on UI/UX for Google's internal tools, enhancing performance and usability.</p>
                <p><strong>Duration:</strong> 2019 - 2022</p>
            </div>
            <div class="experience-card">
                <h3>Intern at Microsoft</h3>
                <p>Contributed to open-source projects and assisted in developing a real-time dashboard.</p>
                <p><strong>Duration:</strong> 2018 - 2019</p>
            </div>
        </div>
    </section>
    <section class="projects">
        <h2>Featured Project</h2>
        <div class="project-card">
            <img src="project-image.png" alt="Project Screenshot">
            <div>
                <h3>Spotify Data Visualizer</h3>
                <p>A web app for visualizing personalized Spotify data using React and D3.js.</p>
                <p><strong>Technologies:</strong> React, D3.js, Spotify API</p>
            </div>
        </div>
    </section>
    <footer>
        <p>Contact: poonamkalra67@gmail.com</p>
    </footer>
</body>
</html>