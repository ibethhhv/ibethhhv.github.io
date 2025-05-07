<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ibeth Vazquez | Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #fffafc;
      color: #333;
    }
    nav {
      background: #ffe3f1;
      padding: 10px;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: #333;
      background-color: #d4f1f4;
      margin: 0 5px;
      padding: 10px 20px;
      border-radius: 8px;
      text-decoration: none;
      text-transform: uppercase;
      font-weight: bold;
      transition: background 0.3s;
    }
    nav a:hover {
      background-color: #bde0fe;
    }
    .section {
      display: none;
      padding: 20px;
    }
    .active {
      display: block;
    }
    header {
      text-align: center;
      background: #cce5ff;
      padding: 40px 20px;
    }
    header img {
      border-radius: 50%;
      width: 120px;
      height: 120px;
      object-fit: cover;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #e0f7ec;
      font-size: 0.9em;
    }
    .project-link, .social-link {
      color: #0077b6;
      text-decoration: none;
    }
    .marketing-image {
      width: 200px;
      border-radius: 10px;
      margin: 10px;
    }
  </style>
</head>
<body>

<header>
  <img src="your-photo.jpg" alt="Ibeth Vazquez">
  <h1>Ibeth Vazquez</h1>
  <p>Marketing-Minded. Tech-Savvy. Globally Inspired.</p>
</header>

<nav>
  <a href="#" onclick="showSection('about')">About Me</a>
  <a href="#" onclick="showSection('marketing')">Marketing</a>
  <a href="#" onclick="showSection('tech')">Technical</a>
  <a href="#" onclick="showSection('contact')">Contact</a>
</nav>

<div id="about" class="section active">
  <h2>About Me</h2>
  <p>Hi! I’m Ibeth, an international business major driven by my passion for international communication, creativity, and technology. As a first-generation Latina, I’m proud to merge cultural roots with global ambitions. Whether it’s creating engaging campaigns or building web tools, I’m here to make impact through connection and strategy.</p>
</div>

<div id="marketing" class="section">
  <h2>Marketing Experience</h2>
  <ul>
    <li>
      <strong>Good Molecules Brand Ambassador</strong>
      <p>Created campus presentations and giveaways. Worked with student orgs to spread awareness through campaigns and surveys.</p>
      <img src="gm-promo.jpg" class="marketing-image" alt="GM Presentation">
    </li>
    <li>
      <strong>Target + TikTok Mini Campaign</strong>
      <p>Recorded and edited a 45-sec video showing Good Molecules restock and shopping experience for campus contest.</p>
      <img src="tiktok-video.jpg" class="marketing-image" alt="TikTok Screenshot">
    </li>
  </ul>
</div>

<div id="tech" class="section">
  <h2>Technical Projects</h2>
  <ul>
    <li>
      <strong>Capital One Tech Intern</strong> – <a href="https://github.com/yourusername/project1" class="project-link">Python automation repo</a>
    </li>
    <li>
      <strong>HTML Portfolio Site</strong> – <a href="https://github.com/yourusername/portfolio-site" class="project-link">Check the source</a>
    </li>
    <li>
      <strong>Apple Financial Analysis</strong> – <a href="https://github.com/yourusername/apple-financial-report" class="project-link">See full analysis</a>
    </li>
  </ul>
</div>

<div id="contact" class="section">
  <h2>Contact Me</h2>
  <p>Email: <a href="mailto:ibethvazquez@email.com" class="social-link">ibethvazquez@email.com</a></p>
  <p>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile" class="social-link" target="_blank">Connect with me</a></p>
  <p>GitHub: <a href="https://github.com/yourusername" class="social-link" target="_blank">View my code</a></p>
  <p>Location: Texas, USA — open to relocation 🌎</p>
</div>

<footer>
  <p>© 2025 Ibeth Vazquez</p>
</footer>

<script>
  function showSection(id) {
    const sections = document.querySelectorAll('.section');
    sections.forEach(sec => sec.classList.remove('active'));
    document.getElementById(id).classList.add('active');
  }
</script>

</body>
</html>
