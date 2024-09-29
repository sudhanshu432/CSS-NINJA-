# Add Animations II

## Problem Statement
In the Provided HTML and CSS code, add CSS Animation properties to achieve the desired output as shown in the “Expected Output” Section.

## Expected Output
https://ninjasfiles.s3.amazonaws.com/asset_0000000000003522_1717151537_Untitled%20design%20(24).gif

**Note:**
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **.circle**
   Ensure that the ".circle" class has the correct animation properties applied:
        - Ensure that the element has an "animation-name" property set to bounce.
        - Ensure that the element has an "animation-duration" property set to 1s
        - Ensure that the element has an "animation-iteration-count" property set to infinite
        - Ensure that the element has an "animation-direction" property set to alternate
        - Ensure that the element has an "animation-timing-function" property set to ease-in-out
        - Ensure that the element has an "animation-fill-mode" property set to both.
2. **.wave**
    Ensure that the hover state on the ".circle" class element has the correct property:
        - Ensure that the ".circle:hover" selector is defined in the CSS.
        - Ensure that the "animation-play-state" property is set to paused.
3. **.wave-1**
   Ensure the second circle element has an "animation-delay" property set to 0.2s

4. **.wave-2**
   Ensure the third circle element has an 'animation-delay' property set to 0.4s.

5. **.wave-3**
   Ensure that the fourth circle element has an "animation-delay" property set to 0.6s

6. **keyframes**
   Ensure that the fifth circle element has an "animation-delay" property set to 0.8s

7. **keyframes**
Ensure that the keyframes for the bounce animation are defined correctly:
        - Ensure that the @keyframes bounce rule is defined in the CSS.
        - Ensure that the from keyframe has a "transform" property set to translateY(0).
        - Ensure that the to keyframe has a "transform" property set to translateY(-100px).
## HTML Code
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bounce Effect</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="container">
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
    </div>
  </body>
</html>

```

## CSS
```
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #333;
}

.container {
  display: flex;
  justify-content: space-between;
  width: 400px;
}

.circle {
  border-radius: 50%; 
  /* Add animation properties here */
}

/* give effect by hovering over cicle class element below: */

.circle:nth-child(1) {
  width: 30px;
  height: 30px;
  background-color: #ff6347; 
}

.circle:nth-child(2) {
  width: 40px;
  height: 40px;
  background-color: #ffd700; 
  /* Add animation property here */
}

.circle:nth-child(3) {
  width: 50px;
  height: 50px;
  background-color: #00ff7f; 
  /* Add animation property here */
}

.circle:nth-child(4) {
  width: 40px;
  height: 40px;
  background-color: #87ceeb; 
  /* Add animation property here */
}

.circle:nth-child(5) {
  width: 30px;
  height: 30px;
  background-color: #da70d6; 
  /* Add animation property here */
}

/* give @keyframes rule for animation name 'bounce' below: */
```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
