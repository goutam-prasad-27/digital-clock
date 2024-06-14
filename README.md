## Digital Clock

This is a simple digital clock web application built with HTML, CSS, and JavaScript.

**Features:**

- Displays the current time in hours, minutes, and seconds.
- Customizable background image and font.
- Adjustable blur effect and drop shadow on the clock box.

**Files:**

- `index.html`: Main HTML file for the application structure.
- `style.css`: Stylesheet for styling the clock's appearance.
- `script.js`: JavaScript file containing the logic to update the clock display.

**Customization:**

- **Background Image:** Change the path in the `background-image` property within `.wrapper .background` to your desired image.
- **Font:** Replace the font family in `* { font-family: ... }` with your preferred font.
- **Blur effect:** Adjust the `backdrop-filter: blur(5px);` property in `.wrapper .blur` to control the blur intensity.
- **Drop shadow:** Modify the properties within `box-shadow` in `.wrapper .blur` to customize the drop shadow.
- **Clock font size:** Change the `font-size` property in `.clock span` to adjust the clock text size.

**How to Use:**

1. Save the code snippets (HTML, CSS, and JavaScript) as separate files: `index.html`, `style.css`, and `script.js`.
2. Ensure they are in the same directory.
3. Open `index.html` in your web browser to view the digital clock.

**Note:**

- The provided code snippet for `script.js` uses `defer` to prevent the JavaScript from blocking the initial rendering of the HTML. This ensures the clock appears quickly, and then the script updates the time dynamically.

**Additional Considerations:**

- You can explore adding features like a 12-hour format option, date display, and alarm functionality.
