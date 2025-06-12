<!DOCTYPE html>
<html>
<head>
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Shamjith Ram</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <section id="about">
    <h2>About Me</h2>
    <p>Brief introduction about myself.</p>
  </section>
  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>Project 1</li>
      <li>Project 2</li>
    </ul>
  </section>
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: shamjithram90@gmail.com</p>
  </section>
  <footer>
    <p>&copy; 2025 Shamjith Ram</p>
  </footer>
</body>
</html>
body {
  font-family: sans-serif;
  margin: 0;
  padding: 0;
}
header, footer {
  background: #333;
  color: white;
  padding: 15px;
  text-align: center;
}
nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}
section {
  padding: 20px;
}
