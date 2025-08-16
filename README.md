# business-landing-page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Business Landing Page</title>
  <style>
    * {margin:0; padding:0; box-sizing:border-box; font-family: Arial, sans-serif;}
    body {background:#f9f9f9; color:#333;}
    header {background:#007bff; color:white; padding:20px; text-align:center;}
    nav a {color:white; margin:0 15px; text-decoration:none; font-weight:bold;}
    .hero {text-align:center; padding:80px 20px; background:#eef4ff;}
    .hero h1 {font-size:2.5rem; margin-bottom:15px;}
    .hero p {font-size:1.2rem; margin-bottom:20px;}
    .hero button {padding:12px 25px; background:#007bff; border:none; color:white; font-size:1rem; border-radius:5px; cursor:pointer;}
    .hero button:hover {background:#0056b3;}
    .services {display:grid; grid-template-columns:repeat(auto-fit, minmax(250px, 1fr)); gap:20px; padding:50px 20px;}
    .card {background:white; padding:20px; border-radius:10px; box-shadow:0 4px 6px rgba(0,0,0,0.1); text-align:center;}
    .card h3 {margin-bottom:10px; color:#007bff;}
    .contact {background:#007bff; color:white; padding:40px 20px; text-align:center;}
    .contact a {color:yellow; font-weight:bold;}
    footer {background:#222; color:white; text-align:center; padding:15px;}
  </style>
</head>
<body>
  <header>
    <h2>My Business</h2>
    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h1>Welcome to Our Company</h1>
    <p>We provide modern solutions for your business growth.</p>
    <button>Get Started</button>
  </section>

  <section class="services" id="services">
    <div class="card">
      <h3>Web Design</h3>
      <p>We create responsive and attractive websites for your brand.</p>
    </div>
    <div class="card">
      <h3>SEO Optimization</h3>
      <p>Boost your online presence with smart SEO strategies.</p>
    </div>
    <div class="card">
      <h3>Marketing</h3>
      <p>Grow your business with our digital marketing solutions.</p>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:yourmail@example.com">yourmail@example.com</a></p>
    <p>Phone: +91 98765 43210</p>
  </section>

  <footer>
    <p>© 2025 My Business. All Rights Reserved.</p>
  </footer>
</body>
</html>
