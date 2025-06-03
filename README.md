# dkmasicampo.github.io

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Project Simulation</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: "Segoe UI", sans-serif;
      background-color: #ffffff;
      color: #333;
    }

    header {
      background-color: #0a0a0a;
      color: #fff;
      padding: 60px 20px 30px;
      text-align: center;
    }

    header h1 {
      font-size: 2.2rem;
      margin: 0;
    }

    header p {
      margin-top: 10px;
      font-size: 1.1rem;
      color: #ccc;
    }

    nav {
      background-color: #1a1a1a;
      text-align: center;
      padding: 15px 0;
    }

    nav a {
      color: #eee;
      text-decoration: none;
      margin: 0 20px;
      font-weight: 500;
      text-transform: uppercase;
      font-size: 0.95rem;
      display: inline-block;
    }

    nav a:hover {
      color: #55ff99;
    }

    main {
      display: flex;
      flex-wrap: wrap;
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
      gap: 40px;
    }

    .product-image {
      flex: 1 1 400px;
      text-align: center;
    }

    .product-image img {
      width: 100%;
      max-width: 400px;
      aspect-ratio: 9 / 16;
      object-fit: cover;
      border: 1px solid #ddd;
    }

    .below-image {
      text-align: center;
      margin-top: 10px;
      font-weight: 600;
      font-size: 1rem;
    }

    .product-info {
      flex: 1 1 500px;
    }

    .product-info h2 {
      font-size: 1.4rem;
      font-weight: bold;
      margin-bottom: 15px;
    }

    .product-info p {
      line-height: 1.7;
      margin-bottom: 12px;
    }

    .paypal-button {
      margin-top: 25px;
    }

    .paypal-button input[type="submit"] {
      background-color: #00b386;
      color: #fff;
      font-size: 1rem;
      padding: 12px 24px;
      border: none;
      cursor: pointer;
      border-radius: 4px;
      transition: background 0.3s ease;
    }

    .paypal-button input[type="submit"]:hover {
      background-color: #009973;
    }

    footer {
      background-color: #111;
      color: #ccc;
      text-align: center;
      padding: 25px 10px;
      margin-top: 60px;
    }

    footer a {
      color: #55ff99;
      margin: 0 12px;
      text-decoration: none;
      font-size: 0.95rem;
    }

    footer a:hover {
      text-decoration: underline;
    }

    /* 📱 Mobile Optimization */
    @media (max-width: 768px) {
      header h1 {
        font-size: 1.8rem;
      }

      nav {
        padding: 10px;
      }

      nav a {
        display: block;
        margin: 10px 0;
      }

      main {
        flex-direction: column;
        padding: 0 15px;
        gap: 20px;
      }

      .product-info {
        padding-bottom: 20px;
      }

      .paypal-button input[type="submit"] {
        width: 100%;
        max-width: 300px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Project Simulation</h1>
    <p>DIY Driving Simulation Blueprint Plans</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">F1 Cockpit</a>
    <a href="#">DIY Service</a>
  </nav>

  <main>
    <div class="product-image">
      <img src="https://via.placeholder.com/400x711?text=ProSIM+GT1+Cockpit" alt="ProSIM GT1 Cockpit">
      <div class="below-image">ProSIM GT1 Cockpit</div>
    </div>

    <div class="product-info">
      <h2>ProSIM GT1 Cockpit DIY Blueprint</h2>
      <p>This step-by-step instruction file will guide you into building your very own racing cockpit. The ProSIM GT1 Cockpit is designed to simulate the most common touring car driving position.</p>
      <p>The main goal of this blueprint is to provide you with the most cost-effective building method. The estimated cost of the building materials will be under $100–150 USD. Building tools are not included in this estimate.</p>

      <div class="paypal-button">
        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
          <input type="hidden" name="cmd" value="_xclick">
          <input type="hidden" name="business" value="youremail@example.com">
          <input type="hidden" name="item_name" value="ProSIM GT1 Cockpit DIY Blueprint">
          <input type="hidden" name="amount" value="19.95">
          <input type="hidden" name="currency_code" value="USD">
          <input type="submit" value="Buy Now – $19.95">
        </form>
      </div>
    </div>
  </main>

  <footer>
    <a href="#">Contact Us</a> |
    <a href="#">About Us</a> |
    <a href="#">YouTube</a> |
    <a href="#">Forum</a>
  </footer>

</body>
</html>
