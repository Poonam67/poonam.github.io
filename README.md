<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Poonam kalra - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            background: #0f111a;
            color: white;
            text-align: center;
        }
        .container {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 100vh;
        }
        .text-section {
            text-align: left;
        }
        h1 {
            font-size: 2.5rem;
        }
        .highlight {
            color: #ff007f;
            font-weight: bold;
        }
        .highlight-green {
            color: #00ff99;
            font-weight: bold;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            background: linear-gradient(45deg, #ff007f, #ae49ff);
            border: none;
            padding: 10px 20px;
            color: white;
            border-radius: 25px;
            font-size: 1rem;
            cursor: pointer;
            margin: 10px;
        }
        .code-box {
            background: #1e1e2e;
            padding: 20px;
            border-radius: 10px;
            text-align: left;
            font-family: monospace;
        }
        .code-box code {
            color: #ffbf00;
            white-space: pre-line;
            display: block;
        }
        header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 50px;
        background: linear-gradient(to right, #0f0c29, #302b63, #24243e);
        color: #00ff99;
        font-family: 'Poppins', sans-serif;
        }
        header h1 {
            font-size: 24px;
            font-weight: bold;
            color: #00ff99;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 16px;
            font-weight: bold;
            transition: color 0.3s ease-in-out;
        }
        nav ul li a:hover {
            color: #00ff99;
        }
    </style>
</head>
<body>
    <header>
        <h1>Poonam Kalra</h1>
        <nav>
            <ul>
                <li><a href="#experience">ABOUT</a></li>
                <li><a href="#skills">EXPERIENCE</a></li>
                <li><a href="#blogs">SKILLS</a></li>
                <li><a href="#projects">PROJECTS</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <div class="text-section">
            <h1>Hello, <br> This is <span class="highlight">AB Kalra</span>,<br> I'm a Professional <span class="highlight-green">Software Developer.</span></h1>
            <div class="buttons">
                <button>Contact Me</button>
                <button>Get Resume</button>
            </div>
        </div>
        <div class="code-box">
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
        </div>
    </div>
</body>
</html>
