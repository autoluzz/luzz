<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Auto.Luzz | Premium Car Dealership</title>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Outfit', sans-serif; }
    body { background-color: #f9f9f9; color: #333; line-height: 1.6; }
    header { background: #111; color: #fff; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; }
    header h1 { color: #00bcd4; }
    nav a { margin-left: 1.5rem; color: #fff; text-decoration: none; font-weight: bold; }
    nav a:hover { color: #00bcd4; }
    section { padding: 3rem 2rem; max-width: 1200px; margin: auto; }
    .hero { background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70') center/cover no-repeat; color: white; text-align: center; padding: 6rem 2rem; }
    .hero h2 { font-size: 3rem; margin-bottom: 1rem; }
    .hero p { font-size: 1.25rem; }
    .inventory { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 2rem; }
    .car { background: white; padding: 1rem; border-radius: 8px; box-shadow: 0 0 15px rgba(0,0,0,0.1); }
    .car img { width: 100%; border-radius: 6px; }
    .car h3 { margin-top: 0.5rem; color: #00bcd4; }
    form { display: flex; flex-direction: column; gap: 1rem; max-width: 500px; margin: auto; }
    form input, form textarea { padding: 0.75rem; border: 1px solid #ccc; border-radius: 6px; }
    form button { padding: 0.75rem; background: #00bcd4; color: white; border: none; border-radius: 6px; cursor: pointer; font-weight: bold; }
    form button:hover { background: #0097a7; }
    footer { text-align: center; background: #111; color: #ccc; padding: 2rem; margin-top: 4rem; }
  </style>
</head>
<body>
  <header>
    <h1>Auto.Luzz</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#inventory">Inventory</a>
      <a href="#financing">Financing</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Welcome to Auto.Luzz</h2>
    <p>Find your dream car with us — Premium Quality, Trusted Service.</p>
  </section>

  <section id="inventory">
    <h2>Available Cars</h2>
    <div class="inventory">
      <div class="car">
        <img src="https://source.unsplash.com/featured/?bmw" alt="BMW">
        <h3>BMW 5 Series</h3>
        <p>2021 · Automatic · Diesel · 45,000 km</p>
      </div>
      <div class="car">
        <img src="https://source.unsplash.com/featured/?audi" alt="Audi">
        <h3>Audi A6</h3>
        <p>2020 · Automatic · Petrol · 38,000 km</p>
      </div>
      <div class="car">
        <img src="https://source.unsplash.com/featured/?mercedes" alt="Mercedes">
        <h3>Mercedes C-Class</h3>
        <p>2019 · Manual · Diesel · 52,000 km</p>
      </div>
    </div>
  </section>

  <section id="financing">
    <h2>Financing Options</h2>
    <p>We offer competitive financing through trusted partners. Apply today and drive away tomorrow!</p>
  </section>

  <section id="about">
    <h2>About Auto.Luzz</h2>
    <p>Auto.Luzz is a trusted car dealership offering premium used vehicles with transparency, affordability, and support. We help you choose the right car for your lifestyle and budget.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <input type="tel" placeholder="Phone Number">
      <textarea rows="4" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Auto.Luzz. All rights reserved.</p>
    <p>Follow us on Instagram: <a href="https://instagram.com/auto.luzz" style="color:#00bcd4">@auto.luzz</a></p>
  </footer>
</body>
</html>
