<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohammed Jamal's Bio</title>
  <style>
    /* Basic reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      background-color: #121212;
      color: #fff;
      padding: 20px;
    }

    /* Typewriter effect */
    .typewriter {
      font-size: 1.5em;
      font-weight: bold;
      color: #4CAF50;
      overflow: hidden; /* Ensures text is hidden until revealed */
      border-right: .15em solid #4CAF50; /* Cursor effect */
      white-space: nowrap;
      margin: 0 auto;
      animation: typing 3.5s steps(30) 1s 1 normal both, blinkCaret 0.75s step-end infinite;
    }

    @keyframes typing {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }

    @keyframes blinkCaret {
      50% {
        border-color: transparent;
      }
    }

    .container {
      text-align: center;
      padding-top: 50px;
    }

    .bio-text {
      margin-top: 20px;
    }

    .tech-stack, .connect-links {
      margin-top: 30px;
    }

    .tech-stack ul, .connect-links ul {
      list-style-type: none;
      padding-left: 0;
    }

    .tech-stack li, .connect-links li {
      margin: 10px 0;
    }

    .tech-stack li span, .connect-links li a {
      color: #4CAF50;
      text-decoration: none;
    }

    .tech-stack li span:hover, .connect-links li a:hover {
      text-decoration: underline;
    }

    .fun-fact {
      margin-top: 20px;
      font-size: 1.2em;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="typewriter">Hi, I'm Mohammed Jamal</div>

    <div class="bio-text">
      <p>🚀 <strong>Full-Stack Developer | JavaScript Enthusiast | Problem Solver</strong></p>
      <p>"I don’t write bugs, I create unexpected features."</p>
    </div>

    <div class="tech-stack">
      <h3>🛠 My Tech Stack</h3>
      <ul>
        <li><span>🟡 JavaScript</span> – Because who needs semicolons anyway?</li>
        <li><span>🟥 Laravel</span> – PHP, but with more style.</li>
        <li><span>🔵 React</span> – Managing state, one problem at a time.</li>
        <li><span>🐍 Node.js</span> – Running JavaScript on everything.</li>
        <li><span>🐬 MySQL</span> – It's where I store my data (and occasional bad decisions).</li>
        <li><span>🟢 MongoDB</span> – Flexible schemas for flexible minds.</li>
      </ul>
    </div>

    <div class="connect-links">
      <h3>🤙 Let's Connect</h3>
      <ul>
        <li><a href="https://www.linkedin.com/in/YOUR-LINKEDIN">LinkedIn</a></li>
        <li><a href="mailto:YOUR-EMAIL">Email</a></li>
        <li><a href="YOUR-PORTFOLIO-URL">Portfolio</a></li>
      </ul>
    </div>

    <div class="fun-fact">
      ⚡ **Fun Fact:** 90% of my time coding is spent googling errors, the other 10% is just trying to figure out why everything broke.
    </div>
  </div>
</body>
</html>
