# portfolio.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mahan SM - Portfolio</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: "Poppins", sans-serif;
      background: #0a0a0a;
      color: #f5f5f5;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
      padding: 60px 20px;
      text-align: center;
      animation: fadeIn 2s ease-in-out;
    }

    header h1 {
      font-size: 3rem;
      color: #00ffcc;
      animation: slideDown 1.5s ease;
    }

    header p {
      font-size: 1.3rem;
      color: #ccc;
      margin-top: 10px;
    }

    nav {
      background: #1c1c1c;
      text-align: center;
      padding: 15px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav a {
      margin: 0 20px;
      color: #00ffcc;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #fff;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
      animation: fadeIn 1.5s ease;
    }

    h2 {
      color: #00ffcc;
      margin-bottom: 20px;
      position: relative;
      display: inline-block;
    }

    h2::after {
      content: "";
      width: 50px;
      height: 3px;
      background: #00ffcc;
      display: block;
      margin-top: 5px;
    }

    .skills li, .projects li {
      margin: 12px 0;
      padding: 10px;
      background: #1a1a1a;
      border-left: 4px solid #00ffcc;
      transition: transform 0.3s;
      list-style: none;
    }

    .skills li:hover, .projects li:hover {
      transform: translateX(10px);
      background: #111;
    }

    .contact a {
      color: #00ffcc;
      text-decoration: none;
      transition: color 0.3s;
    }

    .contact a:hover {
      color: #fff;
    }

    footer {
      background: #111;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      color: #888;
    }

    /* Animations */
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    @keyframes slideDown {
      from {transform: translateY(-50px); opacity: 0;}
      to {transform: translateY(0); opacity: 1;}
    }
  </style>
</head>
<body>
  <header>
    <h1>Mahan SM</h1>
    <p>BCA Student | Programmer | Tech Enthusiast</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I am <b>Mahan SM</b>, currently pursuing a <b>Bachelor of Computer Applications (BCA)</b>. 
       I am passionate about coding, problem-solving, and learning new technologies. 
       I aim to build a successful career in software development.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul class="skills">
      <li>⚡ C</li>
      <li>⚡ Java</li>
      <li>⚡ Python</li>
      <li>⚡ HTML & CSS</li>
      <li>⚡ DBMS</li>
      <li>⚡ MS Excel</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul class="projects">
      <li>📌 <b>Student Management System</b> (Mini Project in Java)</li>
      <li>📌 <b>Personal Portfolio Website</b> (This project!)</li>
      <li>📌 <b>Basic Calculator in Python</b></li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>📧 Email: <a href="mailto:mahangowda15@gmail.com">mahangowda15@gmail.com</a></p>
    <p>📱 Phone: <a href="tel:7619123515">7619123515</a></p>
  </section>

  <footer>
    <p>© 2025 Mahan SM | All Rights Reserved</p>
  </footer>
</body>
</html>
