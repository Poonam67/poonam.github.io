<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abu Said - Portfolio</title>
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
    </style>
</head>
<body>
    <div class="container">
        <div class="text-section">
            <h1>Hello, <br> This is <span class="highlight">Poonam</span>,<br> I'm a Professional <span class="highlight-green">Software Developer.</span></h1>
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