<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Welcome to my first website! I'm learning HTML and CSS to create beautiful and functional websites.">
  <link rel="icon" type="image/x-icon" href="favicon.ico">
  <link rel="stylesheet" href="style.css">
  <title>My First Website</title>
</head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>Hello! My name is [Your Name], and this is my first website. I'm learning HTML and CSS to create beautiful and functional websites.</p>
    </section>

    <section id="services">
      <h2>Services</h2>
      <ul>
        <li>Web Design</li>
        <li>Frontend Development</li>
        <li>Responsive Layouts</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <form action="submit_form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        <button type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My First Website. All rights reserved.</p>
    <div class="social-links">
      <a href="https://twitter.com/yourprofile" target="_blank">Twitter</a>
      <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
      <a href="https://github.com/yourprofile" target="_blank">GitHub</a>
    </div>
  </footer>
</body>
</html>
