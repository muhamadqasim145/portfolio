<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Muhammad Qasim | Portfolio</title>
  <link rel="stylesheet" href="my.css">
</head>
<body>
  <!-- buttons -->
  <header class="hero" id="home">
    <div class="overlay"></div>
    <nav class="navbar">
      <div class="logo">MQ</div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>

    <div class="hero-content">
      <h1>Hi, I'm <span>Muhammad Qasim</span></h1>
      <p>A Software Engineer passionate about creating modern, functional, and efficient digital experiences.</p>
      <div class="buttons">
        <a href="#projects" class="btn">View Projects</a>
        <a href="#contact" class="btn">Hire Me</a>
      </div>
    </div>
  </header>

 <!-- about section -->
  <section id="about" class="container about">
    <img src="photo1.jpg" alt="About Background" class="bg-photo">
    <div class="content">
      <h2>About Me</h2>
      <p>
        I'm Muhammad Qasim, a results-driven Software Engineer with a passion for building efficient web and Java-based systems.
        I focus on creating solutions that blend functionality, performance, and design.
      </p>
      <p>
        My core strengths include problem-solving, OOP programming, and modern UI design with HTML, CSS, and JavaScript.
      </p>
    </div>
  </section>

  <!-- ===== PROJECTS SECTION ===== -->
  <section id="projects" class="container projects">
    <img src="photo3.jpg" alt="Projects Background" class="bg-photo">
    <div class="content">
      <h2>My Projects</h2>
      <div class="project-grid">
        <div class="project">
          <h4>Food Delivery App</h4>
          <p>Full-stack mobile app connecting local restaurants with customers, featuring live tracking and secure payments.</p>
        </div>
        <div class="project">
          <h4>Armory Management System</h4>
          <p>Java OOP project that manages weapons, personnel, and maintenance records efficiently using GUI integration.</p>
        </div>
        <div class="project">
          <h4>Fourier Series Visualizer</h4>
          <p>Java MVC-based system visualizing mathematical waveforms in both 2D and 3D using Fourier transformations.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== SKILLS SECTION ===== -->
  <section id="skills" class="container skills">
    <img src="photo4.jpg" alt="Skills Background" class="bg-photo">
    <div class="content">
      <h2>My Skills</h2>
      <div class="tag-container">
        <div class="tag">Java</div>
        <div class="tag">HTML / CSS / JS</div>
        <div class="tag">Linux</div>
        <div class="tag">MySQL</div>
        <div class="tag">OOP Concepts</div>
        <div class="tag">MVC Architecture</div>
        <div class="tag">Git & GitHub</div>
        <div class="tag">Problem Solving</div>
      </div>
    </div>
  </section>

  <!-- ===== CONTACT SECTION ===== -->
  <section id="contact" class="container contact">
    <img src="photo2.jpg" alt="Contact Background" class="bg-photo">
    <div class="content">
      <h2>Contact Me</h2>
      <p>Interested in collaborating or have a project idea? I’d love to hear from you!</p>
      <form class="contact-form">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" required></textarea>
        <button type="submit" class="btn">Send Message</button>
      </form>
    </div>
  </section>

  <!-- ===== FOOTER ===== -->
  <footer>
    <div class="footer">
      <p>© 2025 Muhammad Qasim | All Rights Reserved</p>
      <div>
        <a href="#">LinkedIn</a> • <a href="https://github.com/muhamadqasim145">GitHub</a> • <a href="#">Portfolio</a>
      </div>
    </div>
  </footer>
</body>
</html>
