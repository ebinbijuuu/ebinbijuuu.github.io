<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ebin Biju | Software Engineer Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background-color: #121212;
      color: #e0e0e0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 2rem;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      margin-top: 4rem;
      opacity: 0;
      animation: fadeInUp 1.5s ease forwards;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #bbbbbb;
    }

    section {
      max-width: 800px;
      width: 100%;
      margin: 4rem auto;
      opacity: 0;
      animation: fadeInUp 1.5s ease forwards;
      animation-delay: 0.5s;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #90caf9;
    }

    ul {
      list-style: none;
    }

    li {
      background: #1e1e1e;
      padding: 1rem;
      margin-bottom: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
      transition: transform 0.3s;
    }

    li:hover {
      transform: translateY(-5px);
    }

    footer {
      margin: 4rem 0;
      text-align: center;
      font-size: 0.9rem;
      opacity: 0;
      animation: fadeInUp 1.5s ease forwards;
      animation-delay: 1s;
    }

    a {
      color: #90caf9;
      text-decoration: none;
    }

    .socials a {
      margin: 0 1rem;
      font-size: 1.5rem;
      transition: color 0.3s;
    }

    .socials a:hover {
      color: #ffffff;
    }

    @keyframes fadeInUp {
      from {
        transform: translateY(30px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }
  </style>
</head>

<body>
  <header>
    <h1>Ebin Biju</h1>
    <p>An aspiring Software Engineer looking to specialise in Cybersecurity and AI</p>
  </header>

  <section>
    <h2>Projects</h2>
    <ul>
      <li><strong>Secure Web App</strong> – Coming soon</li>
      <li><strong>AI-powered CV Scanner</strong> – Coming soon</li>
      <li><strong>Containerized Vulnerability Scanner</strong> – Coming soon</li>
      <li><strong>AI Chatbot Helpdesk</strong> – Coming soon</li>
      <li><strong>CTF Tool/Challenge</strong> – Coming soon</li>
    </ul>
  </section>

  <footer>
    <p>Contact: <a href="mailto:ebinbijuuu@gmail.com">ebinbijuuu@gmail.com</a></p>
    <div class="socials">
      <a href="https://github.com/ebinbijuuu" target="_blank"><i class="fab fa-github"></i></a>
      <a href="https://www.linkedin.com/in/ebin-biju-a93854344" target="_blank"><i class="fab fa-linkedin"></i></a>
    </div>
    <p>&copy; 2025 Ebin Biju</p>
  </footer>
</body>

</html>
