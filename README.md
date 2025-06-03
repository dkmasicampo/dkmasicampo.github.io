# dkmasicampo.github.io

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Project Simulation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
    }

    header p {
      margin-top: 8px;
      font-size: 1.1em;
      color: #ccc;
    }

    nav {
      background-color: #444;
      text-align: center;
      padding: 10px 0;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      display: flex;
      flex-wrap: wrap;
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .image-slot {
      flex: 1 1 40%;
      text-align: center;
    }

    .image-slot img {
      width: 100%;
      aspect-ratio: 9 / 16;
      object-fit: cover;
      border: 1px solid #ccc;
      max-width: 300px;
    }

    .description {
      flex: 1 1 60%;
      padding-left: 30px;
    }

    .description h2 {
      font-size: 1.3em;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .description p {
      line-height: 1.6;
      margin-bottom: 10px;
    }

    .paypal-button {
      margin-top: 20px;
    }

    .below-image {
      text-align: center;
      margin-top: 10px;
      font-weight: bold;
    }

    footer {
      background-color: #222;
      color: #ccc;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
    }

    footer a {
      color: #88c0ff;
      margin: 0 10px;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>Project Simulation</h1>
    <p>DIY Driving Simulation blueprint plans</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">F1 Cockpit</a>
    <a href="#">DIY Service</a>
  </nav>

  <main>
    <div class="image-slot">
      <img src="https://via.placeholder.com/300x533?text=9:16+Photo" alt="ProSIM GT1 Cockpit">
      <div class="below-image">ProSIM GT1 Cockpit</div>
    </div>

    <div class="description">
      <h2>ProSIM GT1 Cockpit DIY Blueprint</h2>
      <p>This step-by-step instruction file will guide you into building your very own racing cockpit. The ProSIM GT1 Cockpit is designed to simulate the most common touring car driving position.</p>
      <p>The main goal of this blueprint is to be able to provide you plans for the most cost-effective building method. The estimated cost of the building materials will be under 100–150 USD. Building tools are not included in this estimate.</p>

      <div class="paypal-button">
        <!-- PayPal Button -->
        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
          <input type="hidden" name="cmd" value="_xclick">
          <input type="hidden" name="business" value="youremail@example.com">
          <input type="hidden" name="item_name" value="ProSIM GT1 Cockpit DIY Blueprint">
          <input type="hidden" name="amount" value="19.95">
          <input type="hidden" name="currency_code" value="USD">
          <input type="submit" value="Buy Now for $19.95" style="padding: 10px 20px; font-size: 16px; cursor: pointer;">
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
