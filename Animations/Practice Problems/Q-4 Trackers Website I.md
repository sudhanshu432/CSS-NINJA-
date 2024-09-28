# Trackers Website I

## Problem Statement
Suppose you are a web developer at Trackers, a shoe store for all ages, and your job is to create a new, attractive website.

Use transitions and transformations to enhance the design and improve the shopping experience.

## Expected Output
https://ninjasfiles.s3.amazonaws.com/asset_0000000000003519_1717147900_screen-capture%20(44)%20(online-video-cutter.com).mp4

**Note:**
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **each anchor element inside the nav unordered list**
   Ensure that each anchor element inside the nav unordered list has a "transition" property set as: **background-color 0.3s ease-in-out**

2. **element inside the **".family-card"** class**
   Ensure that each img element inside the **".family-card"** class element has a "transition" property set as: **transform 0.3s ease.**

3. **hover effect on family card images**
   Verify that the hover effect on family card images contains the correct properties:
    - Ensure that the **".family-card img:hover"** selector is defined in the CSS.
    - The image should rotate 30 degrees around the vertical axis (Y-axis) and scale up to 1.05 times its original size(Hint: use "transform" with **rotateY and scale).**

4. **family-card img:hover::before**
   Verify that the hover effect on family card images **::before** pseudo-element contains the correct transition properties:
    - Ensure that the **".family-card img:hover::before"** selector is defined in the CSS.
    - Ensure that the "transition" property is set as: **opacity 0.3s ease.**

5. **product-card**
   Ensure that each **".product-card"** class element has a "transition" property set as: **transform 0.3s ease.**

6. **product-card**
   Verify that the hover effect on the **"product-card"** class elements contains the correct transition properties:
    - Ensure that the **".product-card:hover"** selector is defined in the CSS.
    - Ensure that the "transform" property is set as: **translateY(-5px)**, for shifting upwards by 5 pixels.

7. **product-card::before**
   Verify that the **.product-card::before** contains transition properties:
    - Ensure that the **".product-card::before"** selector is defined in the CSS.
    - Ensure that the "transition" property set as: **opacity 0.3s ease.**

8. **Hover Effect on ".box" Class**
   Ensure that each **".cta-button"** class element has a "transition" property as: **bottom 0.3s ease.**

9. **Hover Effect on ".box" Class**
   Ensure that each anchor element inside the **".footer-column"** unordered list has a "transition" property set as: **color 0.3s ease-in-out.**

10. **Hover Effect on ".box" Class**
   Verify that the hover effect on footer links contains the correct transition properties:
    - Ensure that the **".footer-column ul li a::before"** selector is defined in the CSS.
    - Ensure that the "transition" property set as: **width 0.3s ease-in-out.**

11. **Hover Effect on ".box" Class**
   Ensure that each anchor element inside the ".social-icons" list items has a "transition" property set as: **color 0.3s ease-in-out, transform 0.3s ease-in-out.**

12. **Hover Effect on ".box" Class**
   Verify that the hover effect on social media icons contains the correct transition properties:
    - Ensure that the **".social-icons li a:hover"** selector is defined in the CSS.
    - Ensure that the anchor icons on hover should scale up to 1.2 times their original size(Hint: use "transform" with **scale**).

## HTML Code
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Shoe Store</title>
    <link rel="stylesheet" href="styles.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
    />
  </head>
  <body>
    <header>
      <nav>
        <div class="logo">
          <a href="#"><i class="fas fa-shoe-prints"></i> Trackers</a>
        </div>
        <ul>
          <li><a href="#">Men</a></li>
          <li><a href="#">Women</a></li>
          <li><a href="#">Kids</a></li>
          <li><a href="#">Sale</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section
        class="hero"
        style="
          background-size: cover;
          background-image: url(https://ninjasfiles.s3.amazonaws.com/asset_0000000000003459_1717090194_jordan.jpg);
        "
      >
        <h1>Step Into Style</h1>
        <p>Discover the perfect pair for every occasion.</p>
      </section>

      <section class="product-showcase">
        <h2>Featured Products</h2>
        <div class="product-container">
          <div class="product-card">
            <img
              src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003460_1717090205_jordan-stay-loyal-3-shoes-GNHN2X.jpg"
              alt="Shoe 1"
            />
            <h3>Jordan Stay Loyal 3</h3>
            <p>MRP : ₹ 10 295.00</p>
            <div class="cta-button">
              <a href="#">Buy Now</a>
            </div>
          </div>
          <div class="product-card">
            <img
              src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003461_1717090229_tatum-2-sidewalk-chalk-pf-basketball-shoes-SjC3nc.jpg"
              alt="Shoe 1"
            />
            <h3>Tatum Sidewalk</h3>
            <p>MRP : ₹ 15 698.00</p>
            <div class="cta-button">
              <a href="#">Buy Now</a>
            </div>
          </div>
          <div class="product-card">
            <img
              src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003462_1717090245_jumpman-mvp-shoes-JV1HCs.png"
              alt="Shoe 1"
            />
            <h3>Jumpman Mvp</h3>
            <p>MRP : ₹ 25 698.00</p>
            <div class="cta-button">
              <a href="#">Buy Now</a>
            </div>
          </div>
          <div class="product-card">
            <img
              src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003463_1717090265_air-jordan-1-low-shoes-ZHhKk2.png"
              alt="Shoe 1"
            />
            <h3>Air Jordan 1 Low</h3>
            <p>MRP : ₹ 8 995.00</p>
            <div class="cta-button">
              <a href="#">Buy Now</a>
            </div>
          </div>
          <div class="product-card">
            <img
              src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003464_1717090275_jordan-one-take-5-quai-54-pf-basketball-shoes-FqsGlx.jpg"
              alt="Shoe 1"
            />
            <h3>Jordan One Take</h3>
            <p>MRP : ₹ 38 995.00</p>
            <div class="cta-button">
              <a href="#">Buy Now</a>
            </div>
          </div>
          <div class="product-card">
            <img
              src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003465_1717090292_jordan-stay-loyal-3-shoes-GNHN2X (1).jpg"
              alt="Shoe 1"
            />
            <h3>Jordan Stay Loyal 2</h3>
            <p>MRP : ₹ 9 995.00</p>
            <div class="cta-button">
              <a href="#">Buy Now</a>
            </div>
          </div>
          <div class="product-card">
            <img
              src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003466_1717090304_air-jordan-1-low-shoes-zTWr01.png"
              alt="Shoe 1"
            />
            <h3>Air Jordan 1 Low</h3>
            <p>MRP : ₹ 8 995.00</p>
            <div class="cta-button">
              <a href="#">Buy Now</a>
            </div>
          </div>
          <div class="product-card">
            <img
              src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003467_1717090319_tatum-2-vortex-pf-basketball-shoes-WWbXXK.jpg"
              alt="Shoe 1"
            />
            <h3>Tatum 2 'Vortex' PF</h3>
            <p>MRP : ₹ 11 495.00</p>
            <div class="cta-button">
              <a href="#">Buy Now</a>
            </div>
          </div>
        </div>
      </section>
    </main>

    <section class="family-section">
      <h2>JORDAN GEAR FOR THE ENTIRE FAM</h2>
      <div class="family-card">
        <div>
          <h3>Jordan Men</h3>
          <img
            src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003468_1717090331_jordan (1).jpg"
            alt=""
          />
        </div>
        <div>
          <h3>Jordan Women</h3>
          <img
            src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003470_1717090353_jordan (2).jpg"
            alt=""
          />
        </div>
        <div>
          <h3>Jordan Kids</h3>
          <img
            src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003472_1717090372_jordan (3).jpg"
            alt=""
          />
        </div>
      </div>
    </section>

    <footer>
      <div class="footer-content">
        <div class="footer-column">
          <h4>Customer Service</h4>
          <ul>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">Shipping & Returns</a></li>
            <li><a href="#">FAQ</a></li>
          </ul>
        </div>
        <div class="footer-column">
          <h4>Company</h4>
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Careers</a></li>
            <li><a href="#">Sustainability</a></li>
          </ul>
        </div>
        <div class="footer-column">
          <h4>Follow Us</h4>
          <ul class="social-icons">
            <li>
              <a href="#"><i class="fab fa-facebook-f"></i></a>
            </li>
            <li>
              <a href="#"><i class="fab fa-twitter"></i></a>
            </li>
            <li>
              <a href="#"><i class="fab fa-instagram"></i></a>
            </li>
          </ul>
        </div>
      </div>
      <p>&copy; 2023 Trackers. All rights reserved.</p>
    </footer>
  </body>
</html>

```
## CSS
```
  /* General Styles */
 body {
  font-family: "Helvetica Neue", Arial, sans-serif;
  margin: 0;
  padding: 0;
}

/* Header Styles */
header {
  background-color: #111;
  color: #fff;
  padding: 20px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
  position: sticky;
  top: 0;
  z-index: 100;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
}

.logo a {
  color: #fff;
  text-decoration: none;
  font-size: 24px;
  font-weight: bold;
  text-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
}

nav ul {
  list-style: none;
  display: flex;
  align-items: center;
}

nav ul li {
  margin-left: 20px;
  position: relative;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  padding: 10px;
  border-radius: 5px;
  /* Add Transition Property here */
}

nav ul li a:hover {
  background-color: rgba(255, 255, 255, 0.2);
}

nav ul li:last-child a {
  background-color: #f44336;
}

nav ul li:last-child a:hover {
  background-color: #e53935;
}

/* Family Section Styles with 3D Transformation */
.family-section {
  text-align: center;
}

.family-card {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.family-card > div {
  flex: 1;
  max-width: 300px;
}

.family-card h3 {
  margin-top: 10px;
}

.family-card img {
  width: 100%;
  height: auto;
  border-radius: 10px;
  /* Add Transition Property here */
}

/* Add effects by hovering over family-card images below */

.family-card img:hover::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.3);
  border-radius: 10px;
  opacity: 1;
  /* Add Transition Property here */
}

/* Hero Section Styles */
.hero {
  background-size: cover;
  background-position: center;
  height: 500px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: #fff;
  text-align: center;
}

.hero h1 {
  font-size: 48px;
  text-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  opacity: 100;
}

.hero p {
  font-size: 24px;
  text-shadow: 0 0 5px rgba(0, 0, 0, 0.5);
  opacity: 100;
}

/* Product Showcase Styles */
.product-showcase {
  text-align: center;
  margin-bottom: 50px;
}

.product-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.product-card {
  width: 250px;
  background-color: #f9f9f9;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  position: relative;
  /* Add Transition Property here */
}

/* Add effects by hovering over product-card below */


.product-card::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.2);
  opacity: 0;
  border-radius: 10px;
   /* Add Transition Property here */
}

.product-card:hover::before {
  opacity: 1;
}

.product-card img {
  width: 100%;
  height: auto;
}

.product-card h3,
.product-card p {
  margin: 10px;
}

.cta-button {
  text-align: center;
  position: absolute;
  bottom: -40px;
  left: 0;
  width: 100%;
   /* Add Transition Property here */
}

.product-card:hover .cta-button {
  bottom: 80px;
}

.cta-button a {
  display: inline-block;
  background-color: #333;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
}

.cta-button a:hover {
  background-color: #333;
}

.product-card:hover .popup {
  display: block;
}

/* Footer Styles */
footer {
  background-color: #111;
  color: #fff;
  padding: 40px;
}

.footer-content {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.footer-column {
  flex: 1;
  min-width: 200px;
  margin-bottom: 20px;
}

.footer-column h4 {
  margin-bottom: 10px;
}

.footer-column ul {
  list-style: none;
  padding: 0;
}

.footer-column ul li {
  margin-bottom: 5px;
}

.footer-column ul li a {
  color: #fff;
  text-decoration: none;
  position: relative;
   /* Add Transition Property here */
}

.footer-column ul li a::before {
  content: "";
  position: absolute;
  width: 0;
  height: 2px;
  bottom: -2px;
  left: 0;
  background-color: #fff;
   /* Add Transition Property here */
}

.footer-column ul li a:hover::before {
  width: 100%;
}

.footer-column ul li a:hover {
  color: #c6c6c6;
}

.social-icons {
  display: flex;
}

.social-icons li {
  margin-right: 10px;
}

.social-icons li a {
  color: #fff;
  font-size: 20px;
  /* Add Transition Property here */
}

.social-icons li a:hover {
  color: #c6c6c6;
   /* Add Transform Property here */
}

footer p {
  text-align: center;
  margin-top: 20px;
}

```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
