<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Product Showcase</title>
  <style>
    /* Reset & Base Styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: "Segoe UI", sans-serif;
      color: #111;
    }

    header {
      background-color: #0a0a0a;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.2rem;
      margin-bottom: 10px;
    }

    .container {
      max-width: 1200px;
      margin: 40px auto;
      padding: 0 20px;
      display: flex;
      flex-wrap: wrap;
      gap: 40px;
    }

    .gallery {
      flex: 1 1 500px;
    }

    .main-image {
      position: relative;
      width: 100%;
      height: 500px;
      border: 1px solid #ccc;
      margin-bottom: 15px;
      overflow: hidden;
      background-color: #ddd; /* fallback if image fails */
    }

    /* This img will fill its parent container */
    .main-image img {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .thumbnail-row {
      display: flex;
      gap: 10px;
    }

    .thumbnail {
      flex: 1;
      height: 80px;
      background-color: #eee;
      border: 1px solid #bbb;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.9rem;
      color: #555;
    }

    .product-info {
      flex: 1 1 500px;
    }

    .product-info h2 {
      font-size: 1.8rem;
      margin-bottom: 10px;
    }

    .price {
      font-size: 1.3rem;
      color: #00b386;
      margin-bottom: 25px;
    }

    .buy-button {
      background-color: #00b386;
      color: white;
      font-size: 1rem;
      padding: 12px 28px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .buy-button:hover {
      background-color: #009973;
    }

    .tabs {
      margin-top: 50px;
      padding: 0 20px;
      max-width: 1200px;
      margin-left: auto;
      margin-right: auto;
    }

    .tab-header {
      display: flex;
      border-bottom: 2px solid #ccc;
    }

    .tab-header div {
      padding: 12px 20px;
      cursor: pointer;
      font-weight: bold;
      color: #333;
    }

    .tab-header div:hover {
      background-color: #eee;
    }

    .tab-content {
      padding: 20px 0;
    }

    footer {
      margin-top: 60px;
      background-color: #111;
      color: #ccc;
      text-align: center;
      padding: 30px 10px;
      font-size: 0.9rem;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
        gap: 20px;
      }

      .main-image {
        height: 300px;
      }

      .thumbnail {
        height: 60px;
      }

      .product-info h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>ProSIM GT1 Cockpit</h1>
    <p>DIY Simulation Rig Blueprint</p>
  </header>

  <div class="container">
    <div class="gallery">
      <!-- Main Product Image using the provided Imgur link -->
      <div class="main-image">
        <img src="https://i.imgur.com/5KjaPtN.jpeg" alt="ProSIM GT1 Cockpit">
      </div>

      <div class="thumbnail-row">
        <div class="thumbnail">Image 1</div>
        <div class="thumbnail">Image 2</div>
        <div class="thumbnail">Image 3</div>
        <div class="thumbnail">Image 4</div>
      </div>
    </div>

    <div class="product-info">
      <h2>ProSIM GT1 DIY Blueprint</h2>
      <div class="price">$19.95</div>
      <p>This step-by-step instruction file will guide you through building your own racing cockpit. Designed for a cost-effective and ergonomic setup inspired by touring car driver positions.</p>
      <br />
      <button class="buy-button">Buy Now</button>

      <!-- Inserted image under the Buy Now button -->
      <div style="margin-top: 20px;">
        <img src="https://github.com/dkmasicampo/dkmasicampo.github.io/blob/main/trusted%20payment%20types.png?raw=true" alt="Trusted Payment Logos" style="max-width: 25%; height: auto;">
      </div>
    </div>
  </div>

  <div class="tabs">
    <div class="tab-header">
      <div>Details</div>
      <div>Specifications</div>
      <div>Downloads</div>
    </div>
    <div class="tab-content">
      <p>Placeholder content for the selected tab. Add full product information, measurements, downloadable files, or customer support links here.</p>
    </div>
  </div>

  <footer>
    &copy; 2025 ProSIM. All rights reserved. | <a href="#" style="color:#55ff99;">Contact</a>
  </footer>

</body>
</html>
