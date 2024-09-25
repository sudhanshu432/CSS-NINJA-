# Add Relative Units

## Problem Statement
In the context of the previous Velocity application, the company demands an enhancement in responsiveness by utilizing relative units in CSS. Your task is to modify the provided HTML and CSS code to achieve the desired output as depicted in the expected output section below.

## Expected Output
![Expected Output](https://github.com/user-attachments/assets/b2231f76-61a2-4cda-bf97-ed7335400243)

Note:
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **Meta Tag Verification**
   - The meta tag should have a `name` attribute set to `"viewport"`.
   - The meta tag should have a `content` attribute set to `"width=device-width, initial-scale=1.0"`.

2. **Header Styles**
   - The header should have a `padding` property set to `1rem`.
   - The header should have a `grid-template-columns` property set to `"1fr auto 1fr"`.

3. **Anchor Tags in Header**
   - Anchor tags should have a `margin` property set to `0 0.5rem`.
   - Anchor tags should have a `font-size` property set to `1rem`.

4. **Container Styles**
   - The container should have a `margin` property set to `6rem auto 0 auto`.
   - The container should have a `grid-template-columns` property set to `"repeat(auto-fit, minmax(30rem, 1fr))"`.
   - The container should have a `grid-auto-rows` property set to `minmax(25rem, auto)`.
   - The paragraph should have a `margin-top` property set to `2rem`.
   - The `h2` element should have a `margin-top` property set to `3rem`.

5. **Image Styles**
   - Image elements should have a `width` property set to `70%`.
   - Image elements should have a `height` property set to `70%`.

6. **Footer Styles**
   - The footer should have a `padding` property set to `1.5rem`.
   - The footer should have a `grid-template-rows` property set to `"repeat(2, auto)"`.

7. **Footer Image Styles**
   - Footer images should have a `width` property set to `7rem`.
   - Footer images should have a `height` property set to `3rem`.

## HTML Code
```
 <!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Add Meta tag attributes here  -->
    <meta charset="UTF-8" />
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
          class="footer-image"
          src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000003363_1715797923_de0d07ff99927b8ef47fe710cd091871-removebg-preview.png"
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
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}

header {
  background-color: #333;
  color: #fff4f4;
  padding: 5px;
  text-align: center;
  position: fixed;
  width: 100%;
  z-index: 1;
  top: 0;
  left: 0;
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  align-items: center;
  grid-template-areas: "title" "navs";
  justify-content: space-between;
}

header a {
  grid-area: navs;
  color: #fff;
  text-decoration: none;
  margin: 0 10px;
}

a:hover {
  text-decoration: underline;
}

h1 {
  grid-area: title;
  font-size: 30px;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}

.container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
  grid-auto-rows: minmax(400px, auto);
  padding: 10px;
  width: 90%;
  margin-left: auto;
  margin-right: auto;
  margin-top: 15%;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
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
  height: 305px;
  object-fit: cover;
}

p {
  margin-top: 40px;
  font-style: italic;
}

h2 {
  margin-top: 60px;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 15px;
  position: fixed;
  bottom: 0;
  width: 100%;
  display: grid;
  grid-template-rows: repeat(2, 30px);
  align-items: center;
  justify-items: center;
}

.footer-image {
  width: 100px;
  height: 70px;
  object-fit: cover;
  border-radius: 50%;
}

.footer-content {
  grid-row: 2;
}

```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
