# Add Media Queries II

## Problem Statement
In the Velocity application add the necessary Media Queries for Mobile and Tablet View to achieve the desired output as shown in the Expected Output section.

## Expected Output
![Expected Output](https://github.com/user-attachments/assets/b2231f76-61a2-4cda-bf97-ed7335400243)

Note:
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **Media Query for Tablet View**
   - The media queries for Tablet View implemented in the previous coding question should also be included here.

2. **Media Query for mobile view**
   Media queries for mobile view should be applied correctly:
    - The media query should be defined like this: "@media screen and (max-width: 767px)".

3. **Header element for mobile view**
   The header element for mobile view should have the following properties:
    - Ensure that the grid-template-columns property is set to 1fr.
    - Ensure that the grid-template-areas property is set to: "title" "navs";
    - Ensure that the padding property is set to 0.5rem.

4. **Navbar inside the header for mobile view**
   The navbar inside the header for mobile view should have the following properties:
    - Ensure that the display property is set to flex.
    - Ensure that the justify-content property is set to center.

5. **H1 element for mobile view**
   The h1 element for mobile view should have the following properties:
    - Ensure that the font-size property is set to 1.5rem.

6. **Container class for mobile view**
   The "container" class for mobile view should have the following properties:
    - Ensure that the grid-template-columns property is set to 1fr.
    - Ensure that the margin-top property is set to 6rem.
    - Ensure that the width property is set to 100%.
    - Ensure that the padding property is set to 0

7. **grid-item class for the mobile view**
   The "grid-item" class for the mobile view should have the following properties:
    - Ensure that the width property is set to 100%.
    - Ensure that the padding property is set to 0.5rem.
    - Ensure that the box-sizing property is set to border-box.
    - Ensure that the display property is set to flex.
    - Ensure that the flex-direction property is set to column.
    - Ensure that the align-items property is set to center.

8. **image-card class for the mobile view**
   The "image-card" class for the mobile view should have the following properties:
    - Ensure that the width property is set to 90%.
    - Ensure that the height property is set to auto.

9. **content-card class for the mobile view**
   view should have the following properties:
    - Ensure that the width property is set to 100%.
    - Ensure that the height property is set to auto.
    - Ensure that the padding property is set to 1rem.
    - Ensure that the box-sizing property is set to border-box.

10. **image element(img) for mobile view**
   The image element(img) for mobile view should have the following properties:
    - Ensure that the width property is set to 100%.
    - Ensure that the height property is set to auto.
    - Ensure that the border-radius property is set to 10%.
    - Ensure that the object-fit property is set to cover.

11. **footer element for mobile view**
   The footer element for mobile view should have the following properties:
    - Ensure that the padding property is set to 0.5rem.
    - Ensure that the position property is set to static.

## HTML Code
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Grid Layout</title>
  </head>
  <body>
    <header>
      <div></div>
      <h1>Sports Cars</h1>
      <nav>
        <a href="#">Home</a>
        <a href="#">FAQ</a>
        <a href="#">Contact</a>
      </nav>
    </header>
    <div class="container">
      <div class="grid-item">
        <div class="image-card">
          <img
            src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002840_1711383478_gian-gomez-SU6MbWxLozY-unsplash.jpg"
            alt="Image 1"
          />
        </div>
      </div>
      <div class="grid-item">
        <div class="content-card">
          <h2>CHEVROLET CORVETTE</h2>
          <p>
            The Chevrolet Corvette is a line of American two-door, two-seater
            sports cars, manufactured and marketed by GM, under the Chevrolet
            marque, since 1953.The Corvette has become widely known as
            "America's Sports Car."Automotive News wrote that after being
            featured in the early 1960s television show Route 66, "the Corvette
            became synonymous with freedom.
          </p>
        </div>
      </div>

      <div class="grid-item">
        <div class="content-card">
          <h2>LAMBORGHINI'S AVENTADOR</h2>
          <p>
            The Lamborghini Aventador is a mid-engine sports car that was
            produced by the Italian automotive manufacturer Lamborghini from
            2011 until 2022. The Aventador's namesake is a Spanish fighting bull
            that fought in Zaragoza, Aragón, in 1993.The Aventador was the
            successor to the Murciélago and was produced in Sant'Agata
            Bolognese, Italy.
          </p>
        </div>
      </div>

      <div class="grid-item">
        <div class="image-card">
          <img
            src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002839_1711383194_max-brinton-kU2MOjKobNg-unsplash.jpg"
            alt="Image 2"
          />
        </div>
      </div>

      <div class="grid-item">
        <div class="image-card">
          <img
            src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002841_1711384281_egor-vikhrev-K63ks3iwaj0-unsplash.jpg"
            alt="Image 3"
          />
        </div>
      </div>

      <div class="grid-item">
        <div class="content-card">
          <h2>FORD MUSTANG</h2>
          <p>
            The Ford Mustang is a series of American automobiles manufactured by
            Ford. In continuous production since 1964, the Mustang is currently
            the longest-produced Ford car nameplate. Currently in its seventh
            generation, it is the fifth-best selling Ford car nameplate. The
            namesake of the "pony car" automobile segment, the Mustang was
            developed as a highly styled line of sporty coupes and convertibles
            derived from existing model lines, initially distinguished by "long
            hood, short deck" proportions.
          </p>
        </div>
      </div>

      <div class="grid-item">
        <div class="content-card">
          <h2>LOTUS EMIRA</h2>
          <p>
            The Lotus Emira is a sports car manufactured by the British company
            Lotus Cars. It is intended to be the Geely-owned firm's final
            vehicle powered by an internal combustion engine. The Emira was
            launched at Hethel, England on 6 July 2021 and then presented at the
            Goodwood Festival of Speed on 8 July 2021. It replaces the Evora,
            Exige and Elise.
          </p>
        </div>
      </div>

      <div class="grid-item">
        <div class="image-card">
          <img
            src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002842_1711384735_lotuaemira.jpeg"
            alt="Image 4"
          />
        </div>
      </div>
    </div>
    <footer>
      <div>
        <img
          class="footer-image" src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003363_1715797923_de0d07ff99927b8ef47fe710cd091871-removebg-preview.png"
          alt="Car Icon"
        />
      </div>
      <div class="footer-content">
        &copy; 2023 Sports Cars. All rights reserved.
      </div>
    </footer>
  </body>
</html>


```
## CSS
```
body {
  background-color: #e8f9fd;
  margin: 0;
  padding: 0;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS",
    sans-serif;
}

header {
  background-color: #333;
  color: #fff4f4;
  padding: 1rem;
  text-align: center;
  position: fixed;
  width: 100%;
  z-index: 1;
  top: 0;
  left: 0;
  display: grid;
  grid-template-columns: 1fr auto 1fr;
  align-items: center;
  grid-template-areas: "title navs";
  justify-content: space-between;
}

header a {
  color: #fff;
  text-decoration: none;
  margin: 0 0.5rem;
  font-size: 1rem;
}

a:hover {
  text-decoration: underline;
}

h1 {
  grid-area: title;
  font-size: 2.2rem;
  margin: 0;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}

.container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
  grid-auto-rows: minmax(25rem, auto);
  padding: 1rem;
  width: 90%;
  margin: 6rem auto 0px auto;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS",
    sans-serif;
}

.grid-item {
  padding: 0;
  text-align: center;
}

.image-card,
.content-card {
  width: 100%;
  height: 100%;
}

img {
  border-radius: 50%;
  width: 70%;
  height: 70%;
  object-fit: cover;
}

p {
  margin-top: 2rem;
  font-style: italic;
}

h2 {
  margin-top: 3rem;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 1.5rem;
  position: fixed;
  bottom: 0;
  width: 100%;
  display: grid;
  grid-template-rows: repeat(2, auto);
  align-items: center;
  justify-items: center;
}

.footer-image {
  width: 7rem;
  height: 3rem;
  object-fit: cover;
  border-radius: 50%;
}

.footer-content {
  grid-row: 2;
}

/* Give tablet view media queries for screen widths between 768px and 1024px below */
```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
