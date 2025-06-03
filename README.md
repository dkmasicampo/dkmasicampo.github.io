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
      background-color: #f8f9fa;
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

    /* Style for trusted payment badges container */
    .trusted-payment-badges {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 20px;
      padding-left: 0;
    }
    .trusted-payment-badge {
      display: inline-flex;
      align-items: center;
      justify-content: center;
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
      <!-- Main Product Image -->
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

      <!-- Trusted Payment Badges -->
      <ul class="list-unstyled trusted-payment-badges flex flex-wrap">
        <li class="trusted-payment-badge">
          <svg xmlns="http://www.w3.org/2000/svg" role="img" aria-labelledby="pi-american_express" viewBox="0 0 38 24" width="38" height="24"><title id="pi-american_express">American Express</title><path fill="#000" d="M35 0H3C1.3 0 0 1.3 0 3v18c0 1.7 1.4 3 3 3h32c1.7 0 3-1.3 3-3V3c0-1.7-1.4-3-3-3Z" opacity=".07"></path><path fill="#006FCF" d="M35 1c1.1 0 2 .9 2 2v18c0 1.1-.9 2-2 2H3c-1.1 0-2-.9-2-2V3c0-1.1.9-2 2-2h32Z"></path><path fill="#FFF" d="M22.012 19.936v-8.421L37 11.528v2.326l-1.732 1.852L37 17.573v2.375h-2.766l-1.47-1.622-1.46 1.628-9.292-.02Z"></path><path fill="#006FCF" d="M23.013 19.012v-6.57h5.572v1.513h-3.768v1.028h3.678v1.488h-3.678v1.01h3.768v1.531h-5.572Z"></path><path fill="#006FCF" d="m28.557 19.012 3.083-3.289-3.083-3.282h2.386l1.884 2.083 1.89-2.082H37v.051l-3.017 3.23L37 18.92v.093h-2.307l-1.917-2.103-1.898 2.104h-2.321Z"></path><path fill="#FFF" d="M22.71 4.04h3.614l1.269 2.881V4.04h4.46l.77 2.159.771-2.159H37v8.421H19l3.71-8.421Z"></path><path fill="#006FCF" d="m23.395 4.955-2.916 6.566h2l.55-1.315h2.98l.55 1.315h2.05l-2.904-6.566h-2.31Zm.25 3.777.875-2.09.873 2.09h-1.748Z"></path><path fill="#006FCF" d="M28.581 11.52V4.953l2.811.01L32.84 9l1.456-4.046H37v6.565l-1.74.016v-4.51l-1.644 4.494h-1.59L30.35 7.01v4.51h-1.768Z"></path></svg>
        </li>
        <li class="trusted-payment-badge">
          <svg version="1.1" xmlns="http://www.w3.org/2000/svg" role="img" x="0" y="0" width="38" height="24" viewBox="0 0 165.521 105.965" xml:space="preserve" aria-labelledby="pi-apple_pay"><title id="pi-apple_pay">Apple Pay</title><path fill="#000" d="M150.698 0H14.823c-.566 0-1.133 0-1.698.003-.477.004-.953.009-1.43.022-1.039.028-2.087.09-3.113.274a10.51 10.51 0 0 0-2.958.975 9.932 9.932 0 0 0-4.35 4.35 10.463 10.463 0 0 0-.975 2.96C.113 9.611.052 10.658.024 11.696a70.22 70.22 0 0 0-.022 1.43C0 13.69 0 14.256 0 14.823v76.318c0 .567 0 1.132.002 1.699.003.476.009.953.022 1.43.028 1.036.09 2.084.275 3.11a10.46 10.46 0 0 0 .974 2.96 9.897 9.897 0 0 0 1.83 2.52 9.874 9.874 0 0 0 2.52 1.83c.947.483 1.917.79 2.96.977 1.025.183 2.073.245 3.112.273.477.011.953.017 1.43.02.565.004 1.132.004 1.698.004h135.875c.565 0 1.132 0 1.697-.004.476-.002.952-.009 1.431-.02 1.037-.028 2.085-.09 3.113-.273a10.478 10.478 0 0 0 2.958-.977 9.955 9.955 0 0 0 4.35-4.35c.483-.947.789-1.917.974-2.96.186-1.026.246-2.074.274-3.11.013-.477.02-.954.022-1.43.004-.567.004-1.132.004-1.699V14.824c0-.567 0-1.133-.004-1.699a63.067 63.067 0 0 0-.022-1.429c-.028-1.038-.088-2.085-.274-3.112a10.4 10.4 0 0 0-.974-2.96 9.94 9.94 0 0 0-4.35-4.35A10.52 10.52 0 0 0 156.939.3c-1.028-.185-2.076-.246-3.113-.274a71.417 71.417
