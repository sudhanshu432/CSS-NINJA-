# Add Transitions and Transform Properties

## Problem Statement
In the Provided HTML and CSS code, add CSS Transition & Transform properties to achieve the desired output as shown in the “Expected Output” Section.

## Expected Output
https://ninjasfiles.s3.amazonaws.com/asset_0000000000003520_1717149616_Untitled%20design%20(22).gif

**Note:**
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **label element**
   Ensure that the label element has a "transition" property set as: **all 0.4s ease-out.**

2. **label:after**
    Ensure that the "label:after" pseudo-element has a "transition" property set as: **all 0.4s ease-out.**

3. **checkbox**
   Ensure that when the input type 'checkbox' is checked, the adjacent label element has a "background-color" property set to "#96e7ef".
(Hint: create selector like this: **input:checked + label** and then give property inside it)

4. **checked state**
   Ensure that the **checked state** transition property on the **label:after** pseudo-element is applied correctly:
        - Ensure that the **"input:checked + label:after"** selector is defined in the CSS.
        - Ensure that the "transform" property is set as: **translate3d(50px, 0, 0).**

## HTML Code
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Toggle Button Task</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <input type="checkbox" id="toggle-slider" />
    <label for="toggle-slider">On/Off</label>
  </body>
</html>

```

## CSS
```
 body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

input[type="checkbox"] {
  display: none;
}

label {
  cursor: pointer;
  text-indent: -9999px;
  width: 100px;
  height: 50px;
  background-color: #dff7fa;
  border-radius: 25px;
  position: relative;
}

label::after {
  content: "";
  position: absolute;
  top: 5px;
  left: 5px;
  width: 40px;
  height: 40px;
  background-color: #a5cace;
  border-radius: 50%;
  /* Add Transition Property here */
}

/* Create the styling for the checked states */


input:checked + label::after {
  background-color: #1d6269;
  /* Add Transform Property here */
} 
```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
