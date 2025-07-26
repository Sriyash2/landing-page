# landing-page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>lading page 
  </title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #f9ed67;
      color: #333;
    }

    header {
      background-color: #4CAF50;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: white;
    }

    header h1 {
      font-size: 28px;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: white;
      font-weight: 500;
    }

    .hero {
      background-image: url('https://source.unsplash.com/featured/?organic,food');
      background-size: cover;
      padding: 100px 40px;
      text-align: center;
      color: white;
    }

    .hero h2 {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 25px;
    }

    .hero button {
      padding: 12px 25px;
      background-color: #fff;
      color: #4CAF50;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: 600;
    }

    section.features, section.contact {
      padding: 60px 40px;
      text-align: center;
    }

    .features h3, .contact h3 {
      font-size: 28px;
      margin-bottom: 30px;
    }

    .feature-cards {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      gap: 20px;
    }

    .card {
      background-color: white;
      padding: 20px;
      width: 280px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      border-radius: 8px;
    }

    .card h4 {
      margin-bottom: 10px;
      font-size: 20px;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
    }

    form {
      max-width: 500px;
      margin: 0 auto;
    }

    input, textarea {
      width: 100%;
      margin-bottom: 15px;
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    button[type="submit"] {
      background-color: #4CAF50;
      color: white;
      padding: 10px 20px;
      border: none;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>FreshBite</h1>
    <nav>
      <a href="#features">Features</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Pure Organic Goodness</h2>
    <p>Healthy, fresh and chemical-free food straight from the farm to your plate.</p>
    <button>Explore Products</button>
  </section>

  <section id="features" class="features">
    <h3>Why Choose Us</h3>
    <div class="feature-cards">
      <div class="card">
        <h4>100% Organic</h4>
        <p>No chemicals or pesticides, just fresh and natural produce.</p>
      </div>
      <div class="card">
        <h4>Eco-Friendly</h4>
        <p>Sustainable farming practices that are good for the earth.</p>
      </div>
      <div class="card">
        <h4>Farm to Table</h4>
        <p>Fresh delivery directly from local farmers to your home.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h3>Contact Us</h3>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 FreshBite Organics | Made with ❤ by Yash Singh</p>
  </footer>
</body>
</html>
