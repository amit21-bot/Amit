<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Amit Pariyar | Social Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background: linear-gradient(to right, #e0f7fa, #fce4ec);
      color: #333;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
    }
    header img {
      border-radius: 50%;
      width: 140px;
      height: 140px;
      object-fit: cover;
      margin-top: 1rem;
      border: 4px solid #ec407a;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      margin: 0 15px;
      color: #ffca28;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #fff;
    }
    section {
      padding: 2rem;
      max-width: 1000px;
      margin: 1rem auto;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .social-icons {
      margin-top: 1rem;
    }
    .social-icons a {
      margin: 0 10px;
      display: inline-block;
      font-weight: bold;
      color: #2196f3;
      text-decoration: none;
      font-size: 1.1rem;
    }
    .social-icons a:hover {
      text-decoration: underline;
    }
    iframe {
      width: 100%;
      border: none;
      margin-top: 1rem;
      border-radius: 10px;
    }
    .embed {
      margin-bottom: 2rem;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    .gallery img {
      width: 32%;
      border-radius: 10px;
      object-fit: cover;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    footer {
      background: #2c3e50;
      color: #fff;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }

    /* Mobile responsiveness */
    @media (max-width: 768px) {
      .gallery img {
        width: 48%;
      }
    }

    @media (max-width: 480px) {
      nav {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 10px;
      }
      nav a {
        margin: 5px;
        font-size: 0.9rem;
      }
      .gallery img {
        width: 100%;
      }
    }

    .cta-facebook {
      display: inline-block;
      margin-top: 1rem;
      background: #1877f2;
      color: #fff;
      padding: 10px 20px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
    .cta-facebook:hover {
      background: #0f66d0;
    }
  </style>
</head>
<body>

  <header>
    <h1>Amit Pariyar</h1>
    <p>Content Creator | Social Media Influencer</p>
    <img src="https://via.placeholder.com/140" alt="Amit Profile Picture">
    <nav>
      <a href="#about">About</a>
      <a href="#social">Social Media</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi! I'm Amit Pariyar, a content creator who shares videos, lifestyle moments, and creativity across TikTok, Instagram, Facebook, and YouTube. Welcome to my official website!</p>
    <a href="https://www.facebook.com/share/1BVaGS6MBF/" class="cta-facebook" target="_blank">Find Me on Facebook</a>
  </section>

  <section id="social">
    <h2>Follow Me</h2>
    <div class="social-icons">
      <a href="https://www.facebook.com/share/1BVaGS6MBF/" target="_blank">Facebook</a>
      <a href="https://www.tiktok.com/@amitpariyar108?_t=ZS-8wSGKjPEv6l&_r=1" target="_blank">TikTok</a>
      <a href="https://youtube.com/@amitpariyar245?si=Kwg0qvURu1GiK3jj" target="_blank">YouTube</a>
      <a href="https://www.instagram.com/amitsunam5?igsh=MTZsZ3IxY2Y2dmhrbQ==" target="_blank">Instagram</a>
    </div>

    <div class="embed">
      <h3>Instagram Post</h3>
      <iframe src="https://www.instagram.com/p/C5TGQgJPy5T/embed" height="500"></iframe>
    </div>

    <div class="embed">
      <h3>YouTube Video</h3>
      <iframe height="315" src="https://www.youtube.com/embed/x07N3CXXG_4" allowfullscreen></iframe>
    </div>

    <div class="embed">
      <h3>Facebook Post</h3>
      <iframe src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Fshare%2F1BVaGS6MBF%2F&width=500" height="500"></iframe>
    </div>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300" alt="Gallery 1">
      <img src="https://th.bing.com/th/id/OIP.0l1Sdvk9HV-hysgtIH1ArQHaFY?w=1200&h=872&rs=1&pid=ImgDetMain" alt="Gallery 2">
      <img src="https://i.ibb.co/SX1vZ9Lh/IMG-20250326-WA0011.jpg" alt="Gallery 3">
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:amitsunam71@gmail.com">amitsunam71@gmail.com</a></p>
    <p>Phone: <a href="tel:+9779818151153">9818151153</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Amit Pariyar. All rights reserved.</p>
  </footer>

</body>
</html>
