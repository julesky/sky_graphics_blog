<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SKY_GRAPHICS Blog</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f4f8;
      color: #333;
      scroll-behavior: smooth;
    }
    header {
      background-color: #222831;
      color: white;
      padding: 1em 2em;
      text-align: center;
      animation: fadeIn 2s ease-in-out;
    }
    nav {
      background-color: #393e46;
      padding: 0.5em;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1em;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #00adb5;
    }
    main {
      max-width: 800px;
      margin: 2em auto;
      padding: 1em;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      animation: fadeIn 1.5s ease-in-out;
    }
    section {
      margin-bottom: 3em;
    }
    article {
      margin-bottom: 2em;
    }
    h1, h2 {
      color: #222831;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 10px;
    }
    .gallery img {
      width: 100%;
      border-radius: 8px;
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    .portfolio-item {
      background: #f9f9f9;
      padding: 1em;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin-bottom: 1em;
    }
    footer {
      text-align: center;
      padding: 1em;
      background-color: #222831;
      color: white;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 0.5em 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>SKY_GRAPHICS</h1>
    <p>Your Creative Design and Inspiration Hub</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#blog">Blog</a>
    <a href="#gallery">Gallery</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <section id="about">
      <h2>About SKY_GRAPHICS</h2>
      <p>Welcome to SKY_GRAPHICS, your hub for creativity and visual inspiration. We provide tutorials, design tips, and highlight amazing projects to help you grow as a designer. Whether you're a beginner or a pro, you'll find something valuable here!</p>
    </section>

    <section id="blog">
      <h2>Latest Blog Posts</h2>
      <article>
        <h3>Welcome to SKY_GRAPHICS</h3>
        <p><em>Posted on July 26, 2025</em></p>
        <p>This is your first blog post! Here you can share design inspiration, tutorials, tips, and updates about SKY_GRAPHICS projects.</p>
      </article>

      <article>
        <h3>Getting Started with Graphic Design</h3>
        <p><em>Posted on July 24, 2025</em></p>
        <p>Learn the basics of graphic design, the tools you need, and how to start building your creative portfolio today.</p>
      </article>
    </section>

    <section id="gallery">
      <h2>Gallery</h2>
      <div class="gallery">
        <img src="https://via.placeholder.com/150" alt="Sample Work 1">
        <img src="https://via.placeholder.com/150" alt="Sample Work 2">
        <img src="https://via.placeholder.com/150" alt="Sample Work 3">
        <img src="https://via.placeholder.com/150" alt="Sample Work 4">
      </div>
    </section>

    <section id="portfolio">
      <h2>Portfolio</h2>
      <div class="portfolio-item">
        <h3>Brand Identity Project</h3>
        <p>Created a visual identity including logo, color palette, and brand guidelines for a modern startup.</p>
      </div>
      <div class="portfolio-item">
        <h3>Web Design Concept</h3>
        <p>Designed a responsive, user-friendly interface for a portfolio website using HTML, CSS, and basic animations.</p>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>We'd love to hear from you! Reach out to us at:</p>
      <ul>
        <li>Email: skygraphics@example.com</li>
        <li>Instagram: @sky.graphics</li>
        <li>Twitter: @SkyGraphicsHQ</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 SKY_GRAPHICS. All rights reserved.</p>
  </footer>
</body>
</html>
