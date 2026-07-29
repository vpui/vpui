<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>vpui - Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: linear-gradient(135deg, #1e1e2e 0%, #2d2d44 100%);
      color: #e0e0e0;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
      line-height: 1.6;
      min-height: 100vh;
      padding: 40px 20px;
    }

    .container {
      max-width: 700px;
      margin: 0 auto;
    }

    .hero {
      text-align: center;
      margin-bottom: 60px;
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-bottom: 20px;
      border: 3px solid #6366f1;
      object-fit: cover;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      color: #fff;
      font-weight: 700;
    }

    .hero p {
      font-size: 1.1rem;
      color: #a0a0b0;
    }

    .socials {
      display: flex;
      gap: 12px;
      justify-content: center;
      margin: 25px 0;
      flex-wrap: wrap;
    }

    .socials a {
      transition: transform 0.2s ease, opacity 0.2s ease;
      display: inline-flex;
    }

    .socials a:hover {
      transform: translateY(-3px);
      opacity: 0.8;
    }

    .socials img {
      height: 35px;
      border-radius: 4px;
    }

    .profile-views {
      text-align: center;
      margin-bottom: 50px;
    }

    .profile-views img {
      height: 20px;
    }

    .section {
      margin-bottom: 50px;
    }

    .section h2 {
      font-size: 1.5rem;
      margin-bottom: 20px;
      color: #fff;
      font-weight: 600;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .about-text {
      font-size: 1rem;
      color: #b0b0c0;
      margin-bottom: 15px;
    }

    .about-text strong {
      color: #6366f1;
    }

    ul {
      list-style: none;
      margin-left: 0;
    }

    ul li {
      padding: 8px 0;
      padding-left: 25px;
      position: relative;
      color: #a0a0b0;
      font-size: 0.95rem;
    }

    ul li:before {
      content: "→";
      position: absolute;
      left: 0;
      color: #6366f1;
      font-weight: bold;
    }

    .stats {
      text-align: center;
      margin-top: 40px;
    }

    .stats img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      border: 1px solid #3d3d52;
    }

    .divider {
      height: 1px;
      background: rgba(99, 102, 241, 0.2);
      margin: 40px 0;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Hero Section -->
    <div class="hero">
      <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" alt="Welcome" class="avatar" />
      <h1>Hey there 👋</h1>
      <p>I'm vpui from Poland</p>
    </div>

    <!-- Social Links -->
    <div class="profile-views">
      <img src="https://visitor-badge.laobi.icu/badge?page_id=vpui.vpui" alt="Profile views" />
    </div>

    <div class="socials">
      <a href="https://youtube.com/your-channel" target="_blank" rel="noopener noreferrer" title="YouTube">
        <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" alt="YouTube" />
      </a>
      <a href="https://twitter.com/your-handle" target="_blank" rel="noopener noreferrer" title="Twitter">
        <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" alt="Twitter" />
      </a>
    </div>

    <div class="divider"></div>

    <!-- About Section -->
    <div class="section">
      <h2>👩‍💻 About Me</h2>
      <p class="about-text">
        Passionate developer focused on creating secure and efficient solutions. 
        Currently expanding my expertise in <strong>Cybersecurity</strong>.
      </p>
      <ul>
        <li>📚 Currently learning Cybersecurity</li>
        <li>⚡ Passionate about new technologies and continuous improvement</li>
        <li>🔒 Interested in secure code practices and system architecture</li>
      </ul>
    </div>

    <!-- Stats Section -->
    <div class="stats">
      <img src="https://i.pinimg.com/1200x/81/20/14/8120143659a8de4c7c4a9813937dbada.jpg" alt="GitHub streak graph" />
    </div>
  </div>
</body>
</html>
