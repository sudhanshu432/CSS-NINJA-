# Add Responsiveness I

## Problem Statement
In context to your previous Wildlife Photography Portfolio, there is a company's demand to add Responsiveness by adding Relative Units. Modify the given CSS code to achieve the desired output as shown in the Expected Output section.

## Expected Output
![Expected Output](https://github.com/user-attachments/assets/b2231f76-61a2-4cda-bf97-ed7335400243)

Note:
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **Header element**
   Verify that the header element has the correct CSS properties applied:
    - Ensure that the height property is set in vh.
    - Ensure that the padding property is set in rem.

2. **Anchor tags**
   Verify that the anchor tags within the header have the correct CSS properties applied:
    - Ensure that the font-size property is set in rem.
    - Ensure that the margin-left property is set in rem.

3. **main class**
   Ensure that the main class element should have a margin-top property set in rem.

4. **main class**
   Verify that the gallery-item class has the correct CSS properties applied:
    - Ensure that the margin-bottom property is set in rem.
    - Ensure that the width property is set in rem.
    - Ensure that the height property is set in rem.
    - Ensure that the border-radius property is set in rem.

5. **main class**
   Ensure the images within the gallery item class should have border-radius property set in rem.

6. **main class**
   Verify that the h3 headings within the gallery item class have the correct CSS properties applied:
    - Ensure that the font-size property is set in rem.
    - Ensure that the top property is set in rem.

## HTML Code
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Photography</title>
  </head>
  <body>
    <header>
      <div class="container">
        <div>
          <h1>Photography</h1>
        </div>
        <nav>
          <a href="#">Gallery</a>
          <a href="#">Blog</a>
          <a href="#">Classes</a>
          <a href="#">About me</a>
          <a href="#">Contact</a>
        </nav>
      </div>
    </header>

    <div class="heading">
      <h1>Wildlife Discovery</h1>
    </div>

    <main class="main">
      <div class="gallery-item">
        <h3>Elephant</h3>
        <img
          src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002829_1711277080_Elephant.jfif"
          alt="Elephant"
        />
      </div>
      <div class="gallery-item">
        <h3>Lion</h3>
        <img
          src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002830_1711277139_Lion.jfif"
          alt="Lion"
        />
      </div>
      <div class="gallery-item">
        <h3>Tiger</h3>
        <img
          src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002831_1711277431_tiger.jfif"
          alt="Tiger"
        />
      </div>
      <div class="gallery-item">
        <h3>Anaconda</h3>
        <img
          src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002832_1711277455_Anaconda.jfif"
          alt="Anaconda"
        />
      </div>
      <div class="gallery-item">
        <h3>Eagle</h3>
        <img
          src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002833_1711277471_Eagle.jfif"
          alt="Eagle"
        />
      </div>
      <div class="gallery-item">
        <h3>Swan</h3>
        <img
          src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002834_1711277488_Swan.jfif"
          alt="Swan"
        />
      </div>
      <div class="gallery-item">
        <h3>Deer</h3>
        <img
          src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002835_1711277519_Deer.jfif"
          alt="Deer"
        />
      </div>
      <div class="gallery-item">
        <h3>Giraffe</h3>
        <img
          src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002836_1711277533_Giraffe.jfif"
          alt="Giraffe"
        />
      </div>
      <div class="gallery-item">
        <h3>Gorilla</h3>
        <img
          src="https://ninjasfiles.s3.amazonaws.com/asset_0000000000002837_1711277549_gorilla.jfif"
          alt="Gorilla"
        />
      </div>
    </main>
  </body>
</html>


```
## CSS
```
body {
  background-color: #222;
  margin: 0;
  padding: 0;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
}

header {
  height: 15px; 
  background-color: #222;
  color: #fff;
  background-image: url("https://ninjasfiles.s3.amazonaws.com/asset_0000000000002828_1711271938_ken-cheung-KonWFWUaAuk-unsplash.jpg");
  background-size: cover;
  background-position: center;
  padding: 0.625px; 
  filter: brightness(90%);
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header a {
  color: #fff;
  text-decoration: none;
  font-size: 1.125px; 
  margin-left: 1.25px; 
  margin-top: 0;
}

header a:hover {
  text-decoration: underline;
}

h1 {
  text-align: center;
  color: white;
}

.main {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  margin-left: auto;
  margin-right: auto;
  margin-top: 3.125px; 
  width: 80%;
}

.gallery-item {
  text-align: center;
  margin-bottom: 1.875px; 
  padding: 0;
  width: 18.75px; 
  background-color: #f2f2f2;
  position: relative;
  height: 25px; 
  border-radius: 6.25px; 
}

.gallery-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  position: absolute;
  top: 0;
  left: 0;
  border-radius: 4.375px; 
  box-shadow: rgba(0, 0, 0, 0.25) 0px 3.375rem 3.4375rem,
  rgba(255, 255, 255, 0.12) 0px -0.75rem 1.875rem,
  rgba(255, 255, 255, 0.12) 0px 0.25rem 0.375rem,
  rgba(255, 255, 255, 0.17) 0px 0.75rem 0.8125rem,
  rgba(255, 255, 255, 0.09) 0px -0.1875rem 0.3125rem; 
}

.gallery-item h3 {
  top: 22px; 
  z-index: 2;
  position: relative;
  color: #fff;
  font-size: 1.375px; 
}

```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
