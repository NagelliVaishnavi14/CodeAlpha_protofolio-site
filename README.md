<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Your Name - Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Navigation -->
  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#resume">Resume</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- About Section -->
  <section id="about">
    <h1>Hello, I'm Nagelli Vaishanvi</h1>
    <p>A brief intro about yourself, your skills and passions.</p>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project-list">
      <div class="project-item">
        <h3>Project One</h3>
        <p>Short description of project one.</p>
        <a href="https://github.com/yourusername/project-one" target="_blank">View on GitHub</a>
      </div>
      <div class="project-item">
        <h3>Project Two</h3>
        <p>Short description of project two.</p>
        <a href="https://github.com/yourusername/project-two" target="_blank">View on GitHub</a>
      </div>
    </div>
  </section>

  <!-- Resume Section -->
  <section id="resume">
    <h2>Resume</h2>
    <p>You can embed your resume here or provide a link:</p>
    <a href="resume.pdf" target="_blank">Download my Resume (PDF)</a>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <form id="contact-form">
      <label for="name">Name:</label><br/>
      <input type="text" id="name" name="name" required /><br/>

      <label for="email">Email:</label><br/>
      <input type="email" id="email" name="email" required /><br/>

      <label for="message">Message:</label><br/>
      <textarea id="message" name="message" rows="4" required></textarea><br/>

      <button type="submit">Send</button>
    </form>
  </section>

  <script src="script.js"></script>
</body>
</html>
