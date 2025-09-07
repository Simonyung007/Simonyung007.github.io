<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simon Yung | Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      line-height: 1.6;
      background: #fff;
    }
    header {
      background: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    header p {
      margin: 5px 0 10px;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
    }
    h2 {
      color: #333;
      margin-bottom: 20px;
    }
    .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .project {
      flex: 1 1 calc(33% - 20px);
      background: #f4f4f4;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
    }
    .project img {
      max-width: 100%;
      border-radius: 8px;
    }
    .skills ul {
      columns: 2;
      list-style: none;
      padding: 0;
    }
    .skills li {
      margin-bottom: 10px;
    }
    .social-icons {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }
    .social-icons img {
      width: 50px;
      border-radius: 50%;
      background: #ddd;
      padding: 5px;
      transition: transform 0.3s;
    }
    .social-icons img:hover {
      transform: scale(1.1);
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Simon Yung</h1>
    <p>Aspiring Gameplay Programmer | Game Developer</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  
  <!-- About -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I am a passionate gameplay programmer currently studying Game Development. 
       I enjoy creating fun and engaging experiences across PC, mobile, and console. 
       This website showcases my projects, skills, and journey in game development.</p>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h2>🎮 My Games</h2>
    <div class="projects">

      <div class="project">
        <h3>Meteor Pong</h3>
        <p><strong>Engine:</strong> Stencyl<br><strong>Role:</strong> Gameplay Programmer</p>
        <a href="meteor-pong.html">
          <img src="https://i.postimg.cc/764s2v5h/Meteor-Pong-Main-Title-Screen.png" alt="Meteor Pong Screenshot">
        </a>
        <p><a href="https://your-game-link.com" target="_blank">🎮 Play on itch.io (coming soon)</a></p>
      </div>

      <div class="project">
        <h3>Virus Exterminator</h3>
        <p><strong>Engine:</strong> Stencyl<br><strong>Role:</strong> Gameplay Programmer</p>
        <a href="virus-exterminator.html">
          <img src="https://i.postimg.cc/8km8w4Gx/Virus-Exterminator-Main-Title-Screen.png" alt="Virus Exterminator Screenshot">
        </a>
        <p><a href="https://your-game-link.com" target="_blank">🎮 Play on itch.io (coming soon)</a></p>
      </div>

      <div class="project">
        <h3>Bomb Guy</h3>
        <p><strong>Engine:</strong> Stencyl<br><strong>Role:</strong> Gameplay Programmer</p>
        <a href="bomb-guy.html">
          <img src="https://i.postimg.cc/dQrQFGY9/Bomb-Guy-Main-Title-Screen.png" alt="Bomb Guy Screenshot">
        </a>
        <p><a href="https://your-game-link.com" target="_blank">🎮 Play on itch.io (coming soon)</a></p>
      </div>

    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="skills">
    <h2>Skills</h2>
    <ul>
      <li>Stencyl</li>
      <li>Unity (placeholder)</li>
      <li>C# / Java (placeholder)</li>
      <li>Unreal (placeholder)</li>
      <li>Photoshop / Aseprite (placeholder)</li>
      <li>Git & GitHub</li>
    </ul>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>📫 Contact</h2>
    <div class="social-icons">
      <!-- LinkedIn -->
      <a href="https://www.linkedin.com/in/simon-yung-1061351a4/" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111499.png" alt="LinkedIn">
      </a>
      <!-- GitHub -->
      <a href="https://github.com/Simonyung007" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111432.png" alt="GitHub">
      </a>
      <!-- Email -->
      <a href="mailto:simonyung007@gmail.com">
        <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email">
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Simon Yung. All rights reserved.</p>
  </footer>

</body>
</html>
