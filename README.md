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
            align-items: center;
            justify-content: center;
            height: 50vh;
            text-align: left;
            padding: 20px;
        }
        .hero img {
            width: 200px;
            height: auto;
            border-radius: 50%;
            margin-right: 20px;
        }
        .hero-content {
            max-width: 600px;
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
        <img src="media/logo.png" alt="Profile Picture" height="200" width="200">
        <div class="hero-content">
            <h2>Hello! I am Poonam kalra.</h2>
            <p>A passionate Flutter developer with 5 years of experience in cross-platform apps, REST APIs, UI/UX, widgets, and state management solutions.I specialize in creating beautiful, user-friendly, and scalable apps using Flutter and Dart. Let's build something amazing together!. Contributed to 50-plus open source projects within the organization including AI Agents and CI/CD pipelines using Fastlane Match</p>
            <p>Currently, I'm a Senior Associate Engineer at <span class="blue">Successive Digital</span></p>
        </div>
    </section>
    <section class="experience">
        <h2>Work Experience</h2>
        <div class="experience-container">
            <div class="experience-card">
                <h3>Sr. Associate Engineer at Successive Digital</h3>
                <p>Developing scalable mobile applications for multiple projects.</p>
                <p><strong>Duration:</strong> 2022 - Present</p>
            </div>
            <div class="experience-card">
                <h3>Mobile Developer at Abc Info Soft Pvt. Ltd.</h3>
                <p>Worked on real estate construction as a pre and post sales.</p>
                <p><strong>Duration:</strong> 2020 - 2021</p>
            </div>
            <div class="experience-card">
                <h3>Android App developer at Appkul Technologies Pvt. Ltd.</h3>
                <p>I work here with two live projects i.e e-commerce and home workout</p>
                <p><strong>Duration:</strong> 2019 - 2020</p>
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