# Responsive Flipkart Clone

## Objective
In reference to the previous Flipkart Home Page Clone, the company has requested the addition of responsiveness by incorporating relative units and media queries. Modify the CSS code provided in the starter kit to achieve the expected output as shown in the Expected Output section.

## Note:
Use the provided starter kit to write your code and then upload the zip file.

## Expected Output:
![image](https://github.com/user-attachments/assets/a0b6c959-1666-4ff0-9694-7fe0a165d07d)


**Requirements**

**1. Relative Units:**
- Utilize relative units such as rem, em, %, and vw/vh for dimensions, padding, and margins. This ensures the layout scales appropriately across different screen sizes and resolutions.

**2. Mobile-First Approach:**
- Start by designing the layout for mobile devices with a screen width of 480px or less. Use a @media query with max-width: 480px to apply these styles.
- Adjust the layout for mobile screens, such as stacking elements vertically, resizing images and buttons, and ensuring text remains legible.

**3. Tablet and Desktop View:**
- Expand the design to support tablet and desktop views with a screen width of 768px or more. Use a @media query with min-width: 768px to apply these styles.
- Modify the layout for larger screens, such as arranging elements in a grid, adjusting image sizes, and expanding the width of containers.

**4. Orientation:**
- Implement a @media query for orientation: portrait to customize the layout when the device is held in portrait mode.
- Adjust the layout, ensuring elements like banners and footers are correctly positioned and sized for portrait orientation.

**5. Aspect Ratio:**
- Use a @media query with aspect-ratio: 16/9 to apply specific styles for screens with a 16:9 aspect ratio.
- Enhance the layout for this aspect ratio by adjusting widths, heights, and grid configurations to make the most of the available space.

**6. Additional Styling:**
- Implement hover effects, button styles, and font settings to enhance the visual appeal and user interaction.
- Ensure that the layout remains visually consistent and accessible across all supported screen sizes and orientations.

**Evaluation parameters**
**Media Queries for Mobile-First Approach**  **Max score: 40**
- Ensure that media queries are correctly applied for screens 480px or less, resulting in a single-column layout where elements such as the header, item list, banners, and footer are resized and repositioned for optimal viewing on small screens.

**Responsive Design for Tablet and Desktop View** **Max score: 40**
- Confirm that media queries adapt the layout for screens 768px and above, transitioning to a multi-column grid where larger images, text, and other elements are properly aligned and scaled for usability on larger displays.

**Use of Relative Units**   **Max score: 40**
- Check that relative units like rem, em, %, and vw are used instead of fixed units, ensuring the layout remains flexible and scales proportionally across various screen sizes without breaking the design. 

**Orientation-Based Adjustments** **Max score: 40**
- Verify that the layout adjusts based on screen orientation changes, effectively switching between single-column and multi-column formats while maintaining proper image and text scaling, ensuring usability in both portrait and landscape modes.

**Aspect Ratio Considerations**   **Max score: 40**
- Assess the design's adaptability to different aspect ratios, particularly 16:9 screens, ensuring that elements like the header, item list, and banners adjust their maximum width to fit the screen without causing horizontal scrolling or leaving excessive empty space.


```
## Modifications
Make necessary adjustments to the HTML and CSS code to ensure responsiveness and achieve the expected output.
