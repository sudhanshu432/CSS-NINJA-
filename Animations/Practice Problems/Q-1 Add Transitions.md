# Add Transitions

## Problem Statement
In the Provided HTML and CSS code, add CSS Transition properties to achieve the desired output as shown in the “Expected Output” Section.

## Expected Output
![Magic_Card](https://github.com/user-attachments/assets/bdc1b266-c33a-41a5-8dca-32ece6715519)

**Note:**
The desired output should adhere to the Test Cases mentioned below.

## Test Cases
Ensure that the modifications adhere to the following test cases:

1. **Verify the "card" class**
   Verify that the "card" class element has the correct CSS properties applied:
    - Ensure that the card element has an "overflow" property set to "hidden".
    - Ensure that the card element has a "transition" property set as: "height 0.3s ease, box-shadow 0.3s ease"

2. **card-header**
   Ensure that the "card-header" class element has a "transition" property set as: "background-color 0.3s ease"

3. **Verify the "card-content" class**
   Verify that the "card-content" class element has the correct CSS properties applied:
    - Ensure that the card content has an "opacity" property set to 0.
    - Ensure that the card content has a "transition" property set as: **"opacity 0.3s ease 0.3s".**

## HTML Code
```
 <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Expanding Information Card</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="card">
      <div class="card-header">Magic Card</div>
      <div class="card-content">
        <p>
          This is additional content that becomes visible when the card is
          hovered over. It provides more detailed information about the card.
        </p>
      </div>
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
  margin: 0;
  background-color: #f0f0f0;
  font-family: Arial, sans-serif;
}

.card {
  width: 300px;
  height: 200px;
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.card:hover {
  height: 280px;
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

.card-header {
  padding: 20px;
  background-color: #3498db;
  color: #fff;
  font-size: 1.5em;
}

.card:hover .card-header {
  background-color: #2980b9;
}

.card-content {
  padding: 20px;
}

.card:hover .card-content {
  opacity: 1;
}

```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
