<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Poonam kalra - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>ABU SAID</h1>
        <nav>
            <ul>
                <li><a href="#about">ABOUT</a></li>
                <li><a href="#experience">EXPERIENCE</a></li>
                <li><a href="#skills">SKILLS</a></li>
                <li><a href="#education">EDUCATION</a></li>
                <li><a href="#blogs">BLOGS</a></li>
                <li><a href="#projects">PROJECTS</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="hero">
        <div class="text-content">
            <h2>Hello,</h2>
            <h1>This is <span class="highlight">Poonam kalra</span>, I'm a <br> Professional <span class="highlight">Software Developer.</span></h1>
            <div class="social-icons">
                <a href="#"><img src="github-icon.png" alt="GitHub"></a>
                <a href="#"><img src="linkedin-icon.png" alt="LinkedIn"></a>
                <a href="#"><img src="facebook-icon.png" alt="Facebook"></a>
                <a href="#"><img src="twitter-icon.png" alt="Twitter"></a>
            </div>
            <div class="buttons">
                <button class="contact">CONTACT ME</button>
                <button class="resume">GET RESUME</button>
            </div>
        </div>
        
        <div class="code-box">
            <pre>
                <code>
const coder = {
    name: 'Abu Said',
    skills: ['React', 'NextJS', 'Redux', 'Express', 'NestJS', 'MySql', 'MongoDB', 'Docker', 'AWS'],
    hardWorker: true,
    quickLearner: true,
    problemSolver: true,
    hireable: function() {
        return this.hardWorker && this.problemSolver && this.skills.length >= 5;
    }
};
                </code>
            </pre>
        </div>
    </section>
    
    <script src="script.js"></script>
</body>
</html>

/* styles.css */
body {
    font-family: Arial, sans-serif;
    background: linear-gradient(to right, #0f0c29, #302b63, #24243e);
    color: white;
    margin: 0;
    padding: 0;
    text-align: center;
}
.hero {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 100vh;
}
.highlight {
    color: #00ff99;
}
button {
    padding: 10px 20px;
    margin: 10px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}
.contact {
    background: transparent;
    color: white;
    border: 2px solid white;
}
.resume {
    background: purple;
    color: white;
}

/* script.js */
document.addEventListener("DOMContentLoaded", function() {
    document.querySelector(".contact").addEventListener("click", function() {
        alert("Contact button clicked!");
    });

    document.querySelector(".resume").addEventListener("click", function() {
        alert("Resume button clicked!");
    });
});
