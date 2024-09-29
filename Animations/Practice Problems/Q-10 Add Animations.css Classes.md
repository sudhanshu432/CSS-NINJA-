# Add Animations.css Classes

## Problem Statement
In the Provided HTML and CSS code, add CSS Animate.css classes to achieve the desired output as shown in the “Expected Output” Section.

## Expected Output
https://ninjasfiles.s3.amazonaws.com/asset_0000000000003526_1717158643_screen-capture%20(50)%20(online-video-cutter.com).gif

**Note:**
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **HTML file**
    Add the classes given below in the HTML file within the appropriate elements.

2. **Header element**
    Ensure that the header element has the classes: **animate__animated and animate__fadeInDown.**
(For example: class="animate__animated animate__fadeInDown")

3. **Hero**
    Ensure that the section with the class "hero" also has these classes: **animate__animated and animate__fadeIn**

4. **h1**
    Ensure that the h1 inside the .hero section has the classes: animate__animated and animate__bounce

4. **h1**
    Ensure that the h1 inside the .hero section has the classes: animate__animated and animate__bounce

5. **p**
    Ensure that the p inside the .hero section has the classes: **animate__fadeInUp, and animate__delay-1s.**

6. **.hero**
    Ensure that the button link inside the **.hero** section has the classes: **animate__pulse, animate__infinite, and animate__delay-2s.**

7. **features**
    Ensure that the section with the class **"features"** also has these classes: **animate__animated, animate__fadeInUp, and animate__delay-3s.**

8. **first div**
    Ensure that the **first div** with the class **"feature"** also has the classes: **animate__zoomIn, and animate__delay-4s.**

9. **second div**
    Ensure that the **second div** with the class "feature" also has the class: **animate__delay-5s**

10. **third div**
   Ensure that the **third div** with the class **"feature"** also has the class: **animate__delay-6s**

11. **footer**
   Ensure that the **footer** element has the classes: **animate__fadeInUp, and animate__delay-7s.**

## HTML Code
```
  <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Animate.css Example</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
    />
  </head>
  <body>
    <header>
      <nav>
        <h3>ANIMATE</h3>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div class="container">
          <h1>Welcome to Our Website</h1>
          <p class="animate__animated">Discover our innovative solutions for your business.</p>
          <a href="#" class="btn animate__animated">Learn More</a>
        </div>
      </section>

      <section class="features">
        <div class="container">
          <h2>Our Features</h2>
          <div class="feature-grid">
            <div class="feature animate__animated">
              <i class="fas fa-rocket"></i>
              <h3>Fast Performance</h3>
              <p>Our products are designed for lightning-fast performance.</p>
            </div>
            <div class="feature animate__animated animate__zoomIn">
              <i class="fas fa-lock"></i>
              <h3>Secure and Reliable</h3>
              <p>
                We prioritize security and reliability in all our solutions.
              </p>
            </div>
            <div class="feature animate__animated animate__zoomIn">
              <i class="fas fa-user-friends"></i>
              <h3>Customer Support</h3>
              <p>
                Our dedicated support team is here to assist you every step of
                the way.
              </p>
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer class="animate__animated">
      <p>&copy; 2023 Your Company. All rights reserved.</p>
    </footer>
  </body>
</html>

```
## CSS
```
 /* Reset and basic styles */
 body,
 h1,
 h2,
 h3,
 p,
 ul {
   margin: 0;
   padding: 0;
 }

 body {
   font-family: "Roboto", sans-serif;
   line-height: 1.6;
   color: #333;
 }

 .container {
   max-width: 1200px;
   margin: 0 auto;
   padding: 0 20px;
 }

 /* Header */
 header {
   background-color: #fff;
   box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
   position: sticky;
   top: 0;
   z-index: 1000;
 }

 nav {
   display: flex;
   justify-content: space-between;
   align-items: center;
   padding: 20px;
 }

 nav ul {
   list-style-type: none;
   display: flex;
 }

 nav ul li {
   margin-left: 20px;
 }

 nav ul li a {
   text-decoration: none;
   color: #333;
   transition: color 0.3s ease;
 }

 nav ul li a:hover {
   color: #0077b6;
 }

 /* Hero section */
 .hero {
   background: linear-gradient(to right, #0077b6, #0096c7);
   color: #fff;
   padding: 80px 0;
   text-align: center;
 }

 .hero h1 {
   font-size: 48px;
   margin-bottom: 20px;
 }

 .hero p {
   font-size: 20px;
   margin-bottom: 40px;
 }

 .btn {
   display: inline-block;
   background-color: #fff;
   color: #0077b6;
   text-decoration: none;
   padding: 12px 24px;
   border-radius: 4px;
   transition: background-color 0.3s ease;
 }

 .btn:hover {
   background-color: #e6e6e6;
 }

 /* Features section */
 .features {
   padding: 80px 0;
 }

 .features h2 {
   font-size: 36px;
   text-align: center;
   margin-bottom: 40px;
 }

 .feature-grid {
   display: grid;
   grid-template-columns: repeat(3, 1fr);
   grid-gap: 40px;
 }

 .feature {
   text-align: center;
 }

 .feature i {
   font-size: 48px;
   color: #0077b6;
   margin-bottom: 20px;
 }

 .feature h3 {
   font-size: 24px;
   margin-bottom: 10px;
 }

 /* Footer */
 footer {
   background-color: #333;
   color: #fff;
   padding: 20px;
   text-align: center;
 }
```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
