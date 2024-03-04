# portfolio.html
all about html coding
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Navigation Menu</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
    </ul>
  </nav>

  <section id="home">
    <h2>Home</h2>
    <p>Welcome to our website! This is the home section.</p>
  </section>

  <section id="about">
    <h2>About</h2>
    <p>Learn more about us in this section.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <p>Check out some of our projects below:</p>
    <ul>
      <li><a href="#">Project 1</a></li>
      <li><a href="#">Project 2</a></li>
      <li><a href="#">Project 3</a></li>
    </ul>
  </section>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 20px;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
}

nav ul li a:hover {
  color: #007bff;
}

section {
  margin: 20px 0;
}

h2 {
  font-size: 24px;
  color: #333;
}

p {
  font-size: 16px;
  color: #666;
}
