<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Victory Chiemela | Web Developer</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }
    body {
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #0d6efd;
      color: #fff;
      text-align: center;
      padding: 2rem 1rem;
    }
    header h1 {
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
    }
    section {
      padding: 3rem 1.5rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #0d6efd;
      margin-bottom: 1rem;
    }
    .about p {
      line-height: 1.6;
      font-size: 1.1rem;
    }
    .skills ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }
    .skills li {
      background: #0d6efd;
      color: white;
      padding: 0.6rem 1.2rem;
      border-radius: 5px;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .project-card {
      background: #fff;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      padding: 1rem;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }
    .project-card:hover {
      transform: translateY(-5px);
    }
    .contact {
      text-align: center;
    }
    .contact a {
      text-decoration: none;
      color: #fff;
      background: #0d6efd;
      padding: 0.7rem 1.5rem;
      border-radius: 5px;
      display: inline-block;
      margin-top: 1rem;
    }
    footer {
      text-align: center;
      background: #0d6efd;
      color: white;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Victory Chiemela</h1>
    <p>Website Developer | Front-End Designer</p>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>
      Hi, I’m <strong>Victory Chiemela</strong> — a passionate website developer who loves building modern, responsive, and user-friendly websites. I focus on creating digital experiences that are both visually appealing and functional.
    </p>
  </section>

  <section class="skills">
    <h2>My Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>React</li>
      <li>Bootstrap</li>
      <li>Responsive Design</li>
    </ul>
  </section>

  <section class="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>Portfolio Website</h3>
      <p>A personal portfolio built to showcase my web development skills and creativity.</p>
    </div>
    <div class="project-card">
      <h3>Business Landing Page</h3>
      <p>A responsive landing page for a startup company using HTML, CSS, and JavaScript.</p>
    </div>
    <div class="project-card">
      <h3>Blog Website</h3>
      <p>A modern blog layout built with React and styled-components.</p>
    </div>
  </section>

  <section class="contact">
    <h2>Contact Me</h2>
    <p>Let’s collaborate or discuss your next project!</p>
    <a href="mailto:victorychiemela@gmail.com">Email Me</a>
  </section>

  <footer>
    <p>© 2025 Victory Chiemela | All Rights Reserved</p>
  </footer>
</body>
</html>
