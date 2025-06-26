# physique-pack-site
Website for Physique Pack fitness kits
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Physique Pack</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #121212;
      color: #ffffff;
    }
    header {
      background-color: #b30000;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #800000;
      padding: 10px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    .kits {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .kit {
      background-color: #1e1e1e;
      padding: 20px;
      border-radius: 10px;
      border: 1px solid #333;
    }
    .kit h3 {
      color: #ff4d4d;
    }
    .kit p {
      font-size: 0.95rem;
    }
    footer {
      background-color: #222;
      padding: 20px;
      text-align: center;
      font-size: 0.9rem;
      color: #aaa;
    }
    .button {
      background-color: #ff3333;
      border: none;
      padding: 10px 20px;
      color: white;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Physique Pack</h1>
    <p>Your Physique. Our Pack.</p>
  </header>
  <nav>
    <a href="#kits">Shop Kits</a>
    <a href="#learn">Learn</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="kits">
    <h2>Choose Your Transformation Kit</h2>
    <div class="kits">
      <div class="kit">
        <h3>Shred Pack</h3>
        <p>Burn fat and reveal lean muscle. Includes whey, fat burner, and HIIT plan.</p>
        <button class="button">Buy Now - ₹1,999</button>
      </div>
      <div class="kit">
        <h3>Bulk Beast</h3>
        <p>Build size and strength. Includes mass gainer, creatine, and muscle diet plan.</p>
        <button class="button">Buy Now - ₹2,999</button>
      </div>
      <div class="kit">
        <h3>Home Hero</h3>
        <p>Train at home. Includes resistance band, whey, and bodyweight program.</p>
        <button class="button">Buy Now - ₹1,499</button>
      </div>
      <div class="kit">
        <h3>Veg Pro</h3>
        <p>Muscle building for vegetarians. Includes plant protein, B12, and custom veg plan.</p>
        <button class="button">Buy Now - ₹2,499</button>
      </div>
    </div>
  </section>
  <section id="learn">
    <h2>Learn More</h2>
    <p>Get diet tips, workout guidance, and transformation stories from real users.</p>
    <button class="button">Read Articles</button>
  </section>
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Have questions or want to collaborate? Reach us via WhatsApp or Instagram.</p>
    <button class="button">Message Now</button>
  </section>
  <footer>
    <p>&copy; 2025 Physique Pack. All rights reserved.</p>
  </footer>
</body>
</html>
