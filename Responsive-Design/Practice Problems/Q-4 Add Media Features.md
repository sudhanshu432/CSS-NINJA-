# Add Media Features

## Problem Statement
In the Velocity application add the necessary Media Queries Features to achieve the desired output as shown in the Expected Output section.

## Expected Output
https://ninjasfiles.s3.amazonaws.com/asset_0000000000003437_1716541531_Untitled%20design%20(17).gif

**Note:**
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **Media Query for Tablet View**
   Media query for orientation landscape is applied correctly:
    - The media query should be defined as: @media screen and (orientation: landscape).
    - The "container" class inside this query should have a margin-top property set to 7 rem.
    - The footer element should have a padding property set to 0.5 rem.

2. **Media Query for mobile view**
   Media query for min-width 1024px and orientation landscape is applied correctly:
    - The media query should be defined as: @media screen and (min-width: 1024px) and (orientation: landscape).
    - The header element inside this query should have a padding property set to 0.5rem.

## HTML Code
```
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

/* Mobile view */
@media screen and (max-width: 767px) {
  header {
    grid-template-columns: 1fr;
    grid-template-areas:
      "title"
      "navs";
    padding: 0.5rem;
  }

  header nav {
    display: flex;
    justify-content: center;
  }

  h1 {
    font-size: 1.5rem;
  }

  .container {
    grid-template-columns: 1fr;
    margin-top: 6rem;
    width: 100%;
    padding: 0;
  }

  .grid-item {
    width: 100%;
    padding: 0.5rem;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .image-card {
    width: 90%;
    height: auto;
  }

  .content-card {
    width: 100%;
    height: auto;
    padding: 1rem;
    box-sizing: border-box;
  }

  img {
    width: 100%;
    height: auto;
    border-radius: 10%;
    object-fit: cover;
  }

  footer {
    padding: 0.5rem;
    position: static;
  }
}

/* Tablet View  */
@media screen and (min-width: 768px) and (max-width: 1024px) {
  header {
    grid-template-columns: 1fr;
    grid-template-areas: "title navs";
    padding: 1rem;
  }

  h1 {
    font-size: 1.8rem;
  }

  .container {
    grid-template-columns: repeat(auto-fit, minmax(24rem, 1fr));
  }

  .image-card,
  .content-card {
    padding: 1rem;
  }

  img {
    border-radius: 20%;
  }
}

/* Give Media query for orientation landscape below */

/* Give Media query for min-width 1024px and orientation landscape below */

```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
