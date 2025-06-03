# dkmasicampo.github.io

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ProSIM GT1 Cockpit</title>
  <style>
    /* Reset & Base Styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: "Helvetica Neue", Arial, sans-serif;
      background-color: #fff;
      color: #111;
      line-height: 1.5;
    }
    a {
      text-decoration: none;
      color: inherit;
    }
    ul {
      list-style: none;
    }

    /* Container */
    .product-page {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    /* Header (simplified) */
    .site-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 20px 0;
    }
    .site-logo {
      font-size: 1.5rem;
      font-weight: bold;
    }
    .site-nav a {
      margin-left: 30px;
      font-size: 0.9rem;
      color: #555;
      transition: color 0.2s;
    }
    .site-nav a:hover {
      color: #000;
    }

    /* Main Product Section */
    .product-main {
      display: flex;
      flex-wrap: wrap;
      gap: 40px;
      margin-top: 40px;
    }

    /* Gallery */
    .product-gallery {
      flex: 1 1 50%;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .product-main-image {
      width: 100%;
      padding-top: 66.666%; /* 3:2 aspect ratio placeholder */
      background-color: #f0f0f0;
      position: relative;
      border: 1px solid #e0e0e0;
    }
    .product-main-image span {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: #888;
      font-size: 0.9rem;
    }
    .thumbnail-row {
      display: flex;
      gap: 10px;
    }
    .thumbnail {
      flex: 1;
      padding-top: 66.666%; /* same 3:2 aspect ratio */
      background-color: #f8f8f8;
      border: 1px solid #e0e0e0;
      position: relative;
    }
    .thumbnail span {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: #aaa;
      font-size: 0.8rem;
    }

    /* Details */
    .product-details {
      flex: 1 1 50%;
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .product-title {
      font-size: 2rem;
      font-weight: bold;
      color: #111;
    }
    .product-price {
      font-size: 1.5rem;
      color: #009e60; /* green accent */
      font-weight: bold;
    }
    .product-description {
      font-size: 0.95rem;
      color: #333;
    }
    .quantity-label {
      font-size: 0.9rem;
      margin-bottom: 5px;
      color: #555;
    }
    .quantity-input {
      width: 60px;
      padding: 8px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
      margin-bottom: 20px;
    }
    .buy-button {
      background-color: #009e60;
      color: #fff;
      padding: 12px 30px;
      border: none;
      border-radius: 4px;
      font-size: 1rem;
      cursor: pointer;
      text-transform: uppercase;
      transition: background-color 0.2s;
      align-self: flex-start;
    }
    .buy-button:hover {
      background-color: #007d4e;
    }

    /* Tabs */
    .tabs {
      margin-top: 50px;
    }
    .tab-header {
      display: flex;
      border-bottom: 2px solid #e0e0e0;
    }
    .tab-header div {
      padding: 15px 25px;
      cursor: pointer;
      font-size: 0.95rem;
      color: #555;
      transition: background-color 0.2s, color 0.2s;
    }
    .tab-header div:hover {
      background-color: #f5f5f5;
      color: #000;
    }
    .tab-header .active {
      border-bottom: 3px solid #009e60;
      color: #000;
      font-weight: bold;
    }
    .tab-content {
      padding: 20px 0;
      font-size: 0.92rem;
      color: #444;
    }

    /* Footer */
    .site-footer {
      margin-top: 60px;
      padding: 30px 0;
      text-align: center;
      border-top: 1px solid #e0e0e0;
      font-size: 0.9rem;
      color: #777;
    }
    .site-footer a {
      margin: 0 15px;
      color: #009e60;
      transition: color 0.2s;
    }
    .site-footer a:hover {
      color: #007d4e;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .product-main {
        flex-direction: column;
      }
      .product-main-image,
      .thumbnail {
        padding-top: 100%; /* 1:1 square on mobile */
      }
      .thumbnail-row {
        overflow-x: auto;
      }
      .thumbnail {
        flex: 0 0 30%;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <div class="site-header">
    <div class="site-logo">ProSIM</div>
    <div class="site-nav">
      <a href="#">Home</a>
      <a href="#">Products</a>
      <a href="#">Support</a>
      <a href="#">Forum</a>
    </div>
  </div>

  <!-- Product Page Container -->
  <div class="product-page">

    <!-- Main Product Section -->
    <div class="product-main">

      <!-- Image Gallery -->
      <div class="product-gallery">
        <div class="product-main-image">
          <span>Main Image Placeholder</span>
        </div>
        <div class="thumbnail-row">
          <div class="thumbnail"><span>Thumb 1</span></div>
          <div class="thumbnail"><span>Thumb 2</span></div>
          <div class="thumbnail"><span>Thumb 3</span></div>
          <div class="thumbnail"><span>Thumb 4</span></div>
        </div>
      </div>

      <!-- Product Details -->
      <div class="product-details">
        <div class="product-title">ProSIM GT1 Cockpit DIY Blueprint</div>
        <div class="product-price">$19.95</div>
        <div class="product-description">
          This step-by-step instruction file will guide you through building your own racing cockpit. Designed to simulate the most common touring car driving position, with cost-effective materials under $150 USD. Tools not included.
        </div>
        <label class="quantity-label" for="quantity">Quantity:</label>
        <input type="number" id="quantity" class="quantity-input" value="1" min="1" />

        <button class="buy-button">Add to Cart</button>
      </div>

    </div>

    <!-- Tabs Section -->
    <div class="tabs">
      <div class="tab-header">
        <div class="active">Details</div>
        <div>Specifications</div>
        <div>Downloads</div>
      </div>
      <div class="tab-content">
        <p>Placeholder content for the Details tab. Add full product information, assembly instructions, and any other relevant text here.</p>
      </div>
    </div>

  </div>

  <!-- Footer -->
  <div class="site-footer">
    &copy; 2025 ProSIM • <a href="#">Contact Us</a> • <a href="#">About Us</a> • <a href="#">YouTube</a> • <a href="#">Forum</a>
  </div>

</body>
</html>

