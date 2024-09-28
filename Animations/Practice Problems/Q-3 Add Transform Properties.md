# Add Transform Properties

## Problem Statement
In the Provided HTML and CSS code, add CSS Transform properties to achieve the desired output as shown in the “Expected Output” Section.

## Expected Output
https://ninjasfiles.s3.amazonaws.com/asset_0000000000003518_1717147096_unnamed%20(7).gif

**Note:**
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **.box class element**
   The .box class element should have the correct properties:
    - The "transition-property" property should be: **width, background-color, transform.**
    - The "transition-duration" property should be there to specify that the animation will take 2 seconds(**2s**) to complete.
    - The "transition-delay" property should be there to specify that the animation will start 1 second(**1s**) after the change happens.
    - The "transition-timing-function" should specify that the animation will start slowly, speed up in the middle, and then slow down again at the end (**ease-in-out**).

2. **Hover Effect on ".box" Class**
   When you hover over the ".box" class element(.box:hover), the following changes should happen:
    - The width should increase to a specific size.
    - The background color should change to a specific shade of green. (Hint: use #4caf50 for the green shade)
    - The box will rotate 360 degrees and scale up to 1.2 times its original size(Hint: use **transform** property with rotate and scale).


## HTML Code
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="styles.css" />
    <title>Transform Example</title>
  </head>
  <body>
    <div class="box"></div>
  </body>
</html>

```
## CSS
```
body {
  font-family: Arial, sans-serif;
  background-color: #f2f2f2;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

.box {
  width: 150px;
  height: 150px;
  background-color: #ff6347;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  /* Add transition properties here */
}

/* write code for changes occur over hovering the .box element below */

```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
