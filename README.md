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
    <h2>Choose Your Transformation Kit</h2
