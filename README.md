<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rwanda Farm Market</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f7f2;
      color: #222;
    }

    header {
      background: #198754;
      color: white;
      padding: 25px 15px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 30px;
    }

    header p {
      margin-bottom: 0;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }

    .search {
      width: 100%;
      padding: 14px;
      border: 1px solid #ccc;
      border-radius: 8px;
      box-sizing: border-box;
      margin-bottom: 20px;
      font-size: 16px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 15px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .card h3 {
      color: #198754;
    }

    .price {
      font-weight: bold;
      font-size: 18px;
    }

    .contact {
      display: inline-block;
      background: #198754;
      color: white;
      padding: 10px 15px;
      text-decoration: none;
      border-radius: 6px;
      margin-top: 10px;
    }

    footer {
      text-align: center;
      padding: 25px;
      margin-top: 30px;
      background: #222;
      color: white;
    }
  </style>
</head>

<body>

<header>
  <h1>🇷🇼 Rwanda Farm Market</h1>
  <p>Buy and sell agricultural and livestock products in Rwanda</p>
</header>

<div class="container">

  <h2>Find Farm Products</h2>

  <input class="search" type="text"
    placeholder="Search for chickens, rabbits, ducks, vegetables...">

  <div class="products">

    <div class="card">
      <h3>🐔 Chickens</h3>
      <p>Healthy chickens available for sale.</p>
      <p class="price">Price: Contact seller</p>
      <a class="contact" href="tel:+250000000000">Contact Seller</a>
    </div>

    <div class="card">
      <h3>🐇 Rabbits</h3>
      <p>Rabbits for breeding and meat.</p>
      <p class="price">Price: Contact seller</p>
      <a class="contact" href="tel:+250000000000">Contact Seller</a>
    </div>

    <div class="card">
      <h3>🦆 Ducks</h3>
      <p>Quality ducks available from local farmers.</p>
      <p class="price">Price: Contact seller</p>
      <a class="contact" href="tel:+250000000000">Contact Seller</a>
    </div>

    <div class="card">
      <h3>🌱 Agricultural Products</h3>
      <p>Buy and sell crops and other farm products.</p>
      <p class="price">Price: Contact seller</p>
      <a class="contact" href="tel:+250000000000">Contact Seller</a>
    </div>

  </div>
</div>

<footer>
  <p>© 2026 Rwanda Farm Market</p>
  <p>Connecting farmers with buyers in Rwanda 🇷🇼</p>
</footer>

</body>
</html>
