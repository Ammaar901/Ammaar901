<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cracking Paradise - Ethical Web Design & Programming</title>
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body, html {
      height: 100%;
      font-family: 'Segoe UI', sans-serif;
      color: white;
    }
    .video-bg {
      position: fixed;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }
    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: rgba(0, 0, 0, 0.5);
    }
    h1 {
      font-size: 4rem;
      animation: fadeIn 2s ease-out;
    }
    p {
      font-size: 1.5rem;
      margin-top: 1rem;
      max-width: 600px;
    }
    section {
      padding: 4rem 2rem;
      background-color: rgba(0, 0, 0, 0.7); /* Transparent background */
      border-radius: 20px; /* Rounded corners */
      margin: 2rem 0;
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.5);
      backdrop-filter: blur(5px); /* Background blur effect */
    }
    .section-light {
      background-color: rgba(0, 0, 0, 0.7); /* Transparent background */
    }
    footer {
      background-color: #000;
      padding: 1rem;
      text-align: center;
      font-size: 0.9rem;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Navigation bar styles */
    nav {
      display: flex;
      justify-content: center;
      background-color: #333;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 1rem 2rem;
      font-size: 1.2rem;
    }
    nav a:hover {
      background-color: #444;
      border-radius: 5px;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#services">Our Services</a>
    <a href="#gaming">Gaming Deals</a> <!-- New Tab -->
    <a href="#contact">Contact Us</a>
  </nav>

  <!-- Background Video -->
  <video class="video-bg" autoplay muted loop>
    <source src="https://www.w3schools.com/howto/rain.mp4" type="video/mp4">
    Your browser does not support HTML5 video.
  </video>

  <!-- Hero Section -->
  <header>
    <h1>Welcome to Cracking Paradise</h1>
    <p>We *definitely do not* do account cracking. Everything here is legal, and we focus on using our skills to improve digital systems. Join us for fun, creativity, and innovation in tech!</p>
  </header>

  <!-- About Us Section -->
  <section id="about" data-aos="fade-up">
    <h2>About Us</h2>
    <p>We "definitely do not do" account cracking. Everything here is legal. Our mission is to help businesses and individuals improve their digital systems, while having fun with technology! We focus on security, creativity, and innovation.</p>
  </section>

  <!-- Our Services Section -->
  <section id="services" class="section-light" data-aos="fade-right">
    <h2>Our Services</h2>
    <ul>
      <li><strong>Web Design:</strong> We create stunning websites that are not only beautiful but also easy to navigate, ensuring an optimal user experience.</li>
      <li><strong>Programming:</strong> From custom applications to dynamic websites, our programming expertise spans across modern languages to meet your needs.</li>
      <li><strong>Computer Engineering:</strong> Our team is specialized in optimizing computer systems and software to make sure everything runs smoothly and securely.</li>
    </ul>
  </section>

  <!-- Free steam accounts  (New) -->
  <section id="accounts" data-aos="fade-up">
    <h2>Steam accounts and websites accounts</h2>
    <p>Check out the best free steam accoutns we provide on our discord server not only free but also 100% legit these accounts wont get you hacked but if you are insecure please do not disturb us just dont use them.</p>
    <ul>
      <li><strong>Steam accounts:</strong> Free accounts provided check out steam. <a href="https://store.steampowered.com/">Visit Steam</a></li>
      <li><strong>Epic Games Free Game of the Week are bad:</strong> Every week, new accounts provided. <a href="https://www.epicgames.com/store/en-US/">Visit Epic Games Store</a></li>
      <li><strong>Humble Bundle:</strong> Do not pay for anything. <a href="https://www.humblebundle.com/">Visit Humble Bundle</a></li>
    </ul>
  </section>

  <!-- Contact Us Section -->
  <section id="contact" data-aos="fade-left">
    <h2>Contact Us</h2>
    <p>Follow us on Instagram for updates, tech tips, and fun programming tutorials. Stay connected with our latest projects!</p>
  </section>

  <footer>
    &copy; 2025 Cracking Paradise. All rights reserved.
  </footer>

  <!-- AOS Library -->
  <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
  <script>
    AOS.init({ once: true });
  </script>
</body>
</html>


<!---
Ammaar901/Ammaar901 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
