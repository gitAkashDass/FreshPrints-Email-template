# FreshPrints-Email-template
Email Template for FreshPrints
entire code Below 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Email Template</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 5px;
      padding: 10px;
      background-color: rgb(216, 140, 216);
    }
    .container {
      margin: 20px auto;
      background: whitesmoke;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      max-width: 700px;
    }
    .header {
      background-color: whitesmoke;
      text-align: center;
      padding: 20px;
    }
    .welcome {
      text-align: center;
      font-size: 25px;
    }
    .p1 {
      padding: 20px;
      font-weight: 500;
    }
    .Buttons {
      background-color: #ff5a5f;
      color: #fff;
      text-decoration: none;
      padding: 12px 24px;
      border-radius: 6px;
      font-weight: bold;
      font-size: 16px;
    }
    .h2 {
      color: #2c74da;
      text-align: center;
      font-size: medium;
    }
    .Explore {
      color: #212529;
      text-align: center;
      font-weight: bold;
    }
    .footer {
      background-color: #212529;
      color: white;
      text-align: center;
      padding: 10px;
      font-size: 0.9em;
    }
    .footer a {
      color: #42fc42;
      text-decoration: none;
    }

    /* Image styles */
    .product-table {
      width: 100%;
      border-collapse: collapse;
      table-layout: fixed;
    }
    .product-table td {
      padding: 5px;
      text-align: center;
      vertical-align: top;
    }
    .product-image {
      width: 100%;
      max-width: 150px;
      border-radius: 6px;
      margin: auto;
      display: block;
    }
    .gotit{
      text-align: center;
      font-size: medium;
      font-weight: bold;
    }

    /* Responsive stacking */
    @media only screen and (max-width: 600px) {
      .product-table tr {
        display: block;
      }
      .product-table td {
        display: block;
        width: 100% !important;
        padding: 10px 0;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <img
        src="https://ik.imagekit.io/4vnt36ko3/myIcon.png?updatedAt=1744524525574"
        alt="Logo FreshPrints"
        style="max-height: 30px"
      />
      <h2 class="h2">What Your Merch Says About Your Brand</h2>
    </div>

    <h1 class="welcome">Welcome to Fresh Prints 👕</h1>

    <p class="p1">
      Hi Akash, <br><br>

      We're thrilled to welcome you to the Fresh Prints family! Whether you're gearing up to represent your team, club, business, or something uniquely yours, we're here to make sure you look good doing it.<br><br>

      From ultra-soft tees and standout hoodies to custom bags and mugs, we offer fast turnaround times, dedicated design support, and high-quality gear that speaks volumes about your brand.
</p>

      
    </p>

    <div style="text-align: center; padding: 10px">
      <a class="Buttons" href="https://www.freshprints.com/start-design">
        Start Your Design
      </a>
      <p class="p1">
        Not sure where to begin? Check out some of our most popular categories below and get inspired. If you have questions, our team is always happy to help.
      </p>
    </div>

    <hr />

    <h1 class="Explore">Explore our Designs/Categories</h1>

    <table role="presentation" class="product-table">
      <tr>
        <td>
          <a href="https://fp.freshprints.com/products">
          <img
            class="product-image"
            src="https://ik.imagekit.io/4vnt36ko3/bhG6tVExBp8PF4P2ETZx1G9s4.jpg?updatedAt=1744534214182"
            alt="Jacket image"
          />
        </a>
        </td>
        <td>
          <a href="https://fp.freshprints.com/products?mainFilterTag=productType&subFilter=Sweaters">
          <img
            class="product-image"
            src="https://ik.imagekit.io/4vnt36ko3/WC55mVOTs4JhuelWJ6LVWyZF7dw.jpg?updatedAt=1744534207403"
            alt="Hoodie Image"
          />
        </a>
        </td>
        <td>
          <a href="https://fp.freshprints.com/products?mainFilterTag=productType&subFilter=Polos">
          <img
            class="product-image"
            src="https://ik.imagekit.io/4vnt36ko3/f7k0nB4oRZlBcmSpCM2bLVcjiGw.jpeg?updatedAt=1744541012915"
            alt="Collar Tshirt image"
          />
        </a>
        </td>
      </tr>
      <tr>
        <td>
          <a href="https://fp.freshprints.com/products?mainFilterTag=productType&subFilter=Accessories">
          <img
            class="product-image"
            src="https://ik.imagekit.io/4vnt36ko3/QfRqC0Ba01igo9NZglIDxT3ZEs.png?updatedAt=1744534194744"
            alt="Bag Headphones image"
          />
        </a>
        </td>
        <td>
          <a href="https://fp.freshprints.com/product?styleCode=101941&hex=%2523f9f1da">
          <img
            class="product-image"
            src="https://ik.imagekit.io/4vnt36ko3/3jXNTKbuxQWyXWvbdySsd0aQPY.png?updatedAt=1744541663833"
            alt="Steel Coffee mug"
          />
        </a>
        </td>
        <td>
          <a href="https://fp.freshprints.com/product?styleCode=91023&hex=%2523000000">
          <img
            class="product-image"
            src="https://ik.imagekit.io/4vnt36ko3/JqRHhZ8rJFrPzrPG8DHHcVKYOQ.jpg?updatedAt=1744541386554"
            alt="Bag image"
          />
        </a>
        </td>
      </tr>
    </table>
    <p class="gotit">You Name it we’ve got it </p>
    <div class="footer">
      <p>Need help? <a href="mailto:support@freshprints.com">Contact our support team</a></p>
      <p>
        Follow us on 
        <a href="https://www.instagram.com/shirtjustgotcrazy/">Instagram</a> | 
        <a href="https://www.facebook.com/FreshPrintsShop">Facebook</a> 
      </p>
      <p>&copy; 2025 Fresh Prints. All rights reserved.</p>
      <p>
        <a href="https://www.freshprints.com/privacy-policy">Privacy Policy</a> | 
        <a href="https://www.freshprints.com/terms">Terms of Service</a>
      </p>
    </div>

</body>
</html>
