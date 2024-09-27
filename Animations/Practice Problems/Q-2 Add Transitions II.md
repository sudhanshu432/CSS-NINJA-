# Add Transitions II

## Problem Statement
In the Provided HTML and CSS code, add CSS Transition properties to achieve the desired output as shown in the “Expected Output” Section.

## Expected Output
https://ninjasfiles.s3.amazonaws.com/asset_0000000000003517_1717145782_Untitled%20design%20(21).gif

**Note:**
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **Transition Effect on ".box" Class**
   Transition Effect on ".box" Class:
        - Make sure the ".box" class smoothly transitions any transformation over 0.5 seconds, using an ease-in-out effect.
(Hint: use **transition** property with transform and ease-in-out).

2. **card-header**
   Hover Effect on ".box" Class(.box:hover):
        - On hovering over the ".box" element, it should smoothly rotate a full circle (360 degrees) and scale to 1.2 times its original size.
(Hint: use **transform** property with rotate and scale).


## HTML Code
```
 <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Transition Example</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="container">
      <div class="box"></div>
    </div>
  </body>
</html>

```
## CSS
```
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.box {
  width: 200px;
  height: 200px;
  background-color: #4285f4;
  /* Add transition here */
}

/* Add transform effect over hover below */


```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
