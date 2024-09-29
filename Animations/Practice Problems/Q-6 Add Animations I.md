# Add Animations I

## Problem Statement
In the Provided HTML and CSS code, add CSS Animation properties to achieve the desired output as shown in the “Expected Output” Section.

## Expected Output
https://ninjasfiles.s3.amazonaws.com/asset_0000000000003521_1717150647_Untitled%20design%20(23).gif

**Note:**
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **.circle**
   Ensure that the **".circle"** class element has a "transform" property set as: **translate(-50%, -50%)**

2. **.wave**
    Ensure that the **".wave"** class element has the correct animation properties applied:
        - Ensure that the element has a "transform" property set to **translate(-50%, -50%).**
        - Ensure that the element has an "animation-name" property set to **wave.**
        - Ensure that the element has an "animation-duration" property set to **3s.**
        - Ensure that the element has an "animation-timing-function" property set to **linear.**
        - Ensure that the element has an "animation-iteration-count" property set to **infinite.**

3. **.wave-1**
   Ensure that the **".wave-1"** class element has an "animation-delay" property set to **0s**

4. **.wave-2**
   Ensure that the **".wave-2"** class has the correct animation properties applied:
        - Ensure that the element has an "animation-delay" property set to **1s.**
        - Ensure that the element has an "animation-duration" property set to **4s.**

5. **.wave-3**
   Ensure that the **".wave-3"** class has the correct animation properties applied:
        - Ensure that the element has an "animation-delay" property set to **2s.**
        - Ensure that the element has an "animation-duration" property set to **5s.**

6. **keyframes**
   Ensure that the **keyframes** for the wave animation are defined correctly:
        - Ensure that the **@keyframes wave** rule is defined in the CSS.
        - Ensure that the from keyframe has a "transform" property set to **"translate(-50%, -50%) scale(1)"** and an "opacity" property set to **1.**
        - Ensure that the **to** keyframe has a "transform" property set to **"translate(-50%, -50%) scale(2.5)"** and an "opacity" property set to **0.**

## HTML Code
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Wave Animation</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="container">
      <div class="circle"></div>
      <div class="wave wave-1"></div>
      <div class="wave wave-2"></div>
      <div class="wave wave-3"></div>
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
  min-height: 100vh;
  background-color: #222;
}

.container {
  position: relative;
  width: 400px;
  height: 400px;
}

.circle {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background-color: #fff;
  z-index: 2;
  /* Add transform Property here */
}

.wave {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 200px;
  height: 200px;
  border-radius: 50%;
  background-color: transparent;
  border: 2px solid #fff;
  /* Add transform and animation properties here  */
}

/* give animation properties for 'wave-1', 'wave-2', and wave-3 classes below: */

/* give @keyframes rule for animation name 'wave' below: */
```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
