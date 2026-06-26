<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vidhi Pratap Singh | Portfolio</title>
  <style>
    /* Global Styles */
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0; padding: 0;
      background: #f5f7fa; color: #333;
    }
    header {
      background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
      color: #fff; padding: 60px 20px;
      text-align: center;
    }
    header h1 { margin: 0; font-size: 3em; }
    header p { font-size: 1.2em; margin-top: 10px; }

    nav {
      background: #333; padding: 15px;
      text-align: center;
    }
    nav a {
      color: #fff; margin: 0 15px;
      text-decoration: none; font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover { color: #2575fc; }

    section {
      padding: 60px 20px; max-width: 1100px;
      margin: auto;
    }
    h2 {
      color: #2575fc; font-size: 2em;
      border-bottom: 3px solid #eee;
      padding-bottom: 10px; margin-bottom: 20px;
    }

    /* Skills & Achievements */
    .skills li, .achievements li {
      background: #fff; padding: 12px;
      margin: 8px 0; border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    /* Projects Grid */
    .projects {
      display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .project-card {
      background: #fff; border-radius: 10px;
      padding: 20px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .project-card:hover { transform: translateY(-5px); }
    .project-card h3 { margin-top: 0; color: #6a11cb; }

    /* Contact */
    .contact a {
      color: #2575fc; text-decoration: none;
      font-weight: bold;
    }

    footer {
      background: #333; color: #fff;
      text-align: center; padding: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Vidhi Pratap Singh</h1>
  <p>B.Tech AI Student | Aspiring AI Engineer</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#skills">Skills</a>
  <a href="#projects">Projects</a>
  <a href="#achievements">Achievements</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Me</h2>
  <p>Adventurous, bold, confident, and kind. I respect boundaries, value people, and am always ready to learn. My goal is to become a skilled AI engineer within two years.</p>
</section>

<section id="skills">
  <h2>Skills</h2>
  <ul class="skills">
    <li>Programming: Python, Java, C, C++, HTML, CSS</li>
    <li>Frameworks & Tools: Django, NumPy, Pandas, Google Colab</li>
    <li>Cloud Computing: AWS Cloud Foundation (Coordinator)</li>
    <li>Soft Skills: Leadership, problem-solving, adaptability</li>
  </ul>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="projects">
    <div class="project-card">
      <h3>Machine Learning Projects</h3>
      <p>Classification, regression, and recommendation systems.</p>
    </div>
    <div class="project-card">
      <h3>CSS Projects</h3>
      <p>Creative web layouts and styling.</p>
    </div>
    <div class="project-card">
      <h3>Python Projects</h3>
      <p>Automation scripts and AI mini-projects.</p>
    </div>
  </div>
</section>

<section id="achievements">
  <h2>Achievements</h2>
  <ul class="achievements">
    <li>AWS Cloud Foundation Training Coordinator</li>
    <li>GCF Certified Student</li>
    <li>Daily DSA practice on CodeChef (Java)</li>
    <li>Hackathon participation</li>
  </ul>
</section>

<section id="contact">
  <h2>Contact</h2>

  <p>Email: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
  <p>LinkedIn: <a href="https://www.linkedin.com/in/vidhi-singh-a24b9b3b1">linkedin.com/in/vidhi-singh</a></p>
  <p>GitHub: <a href="https://github.com/veervidhivirat0031-bot">github.com/veervidhivirat0031-bot</a></p>
</section>

<footer>
  <p>© 2026 Vidhi Pratap Singh</p>
</footer>

</body>
</html>

