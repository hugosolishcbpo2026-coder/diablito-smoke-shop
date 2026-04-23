<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Diablito Smoke Shop</title>
  <style>
    body {
      margin:0;
      font-family:"Segoe UI",sans-serif;
      background:#111;
      color:#eee;
    }
    header {
      background:#d00000;
      padding:20px;
      text-align:center;
    }
    header h1 {
      margin:0;
      font-size:2.5rem;
      color:#fff;
      text-shadow:0 0 10px #ff4444;
    }
    nav {
      margin-top:10px;
    }
    nav a {
      color:#fff;
      margin:0 15px;
      text-decoration:none;
      font-weight:bold;
    }
    .hero {
      text-align:center;
      padding:60px 20px;
      background:linear-gradient(135deg,#d00000,#ff6600);
    }
    .hero h2 {
      font-size:2rem;
      margin-bottom:20px;
    }
    .hero button {
      background:#000;
      color:#fff;
      border:none;
      padding:15px 30px;
      font-size:1em;
      cursor:pointer;
    }
    .products {
      display:flex;
      flex-wrap:wrap;
      gap:20px;
      justify-content:center;
      padding:40px 20px;
    }
    .product-card {
      background:#222;
      border-radius:10px;
      padding:20px;
      width:250px;
      text-align:center;
    }
    .product-card img {
      width:100%;
      border-radius:8px;
      margin-bottom:10px;
    }
    .product-card h3 {
      margin:10px 0;
      color:#ff6600;
    }
    .product-card button {
      background:#d00000;
      color:#fff;
      border:none;
      padding:10px 20px;
      cursor:pointer;
    }
    footer {
      background:#000;
      color:#999;
      text-align:center;
      padding:20px;
      margin-top:40px;
    }
  </style>
</head>
<body>

<header>
  <h1>Diablito Smoke Shop</h1>
  <nav>
    <a href="#products">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h2>Premium Smoke & Accessories</h2>
  <p>Discover unique products and exclusive deals at Diablito.</p>
  <button>Shop Now</button>
</section>

<section id="products" class="products">
  <div class="product-card">
    <img src="product1.jpg" alt="Glass Pipe">
    <h3>Glass Pipe</h3>
    <p>$25.00</p>
    <button>Add to Cart</button>
  </div>
  <div class="product-card">
    <img src="product2.jpg" alt="Rolling Papers">
    <h3>Rolling Papers</h3>
    <p>$5.00</p>
    <button>Add to Cart</button>
  </div>
  <div class="product-card">
    <img src="product3.jpg" alt="Hookah">
    <h3>Hookah</h3>
    <p>$75.00</p>
    <button>Add to Cart</button>
  </div>
</section>

<section id="about" style="padding:40px 20px;text-align:center;">
  <h2>About Diablito</h2>
  <p>We are a Tijuana‑based smoke shop offering premium products, accessories, and a unique shopping experience.</p>
</section>

<section id="contact" style="padding:40px 20px;text-align:center;">
  <h2>Contact Us</h2>
  <p>Email: info@diablito.com | Phone: (123) 456‑7890</p>
</section>

<footer>
  <p>&copy; 2026 Diablito Smoke Shop. All rights reserved.</p>
</footer>

</body>
</html>
