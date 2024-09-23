# CS100 Basic Web Development 1 - Lab Sheet 1

## Creating a Basic Web Page Layout Using CSS

### Objective
This lab teaches students how to create a simple web page layout using HTML and CSS. Students will apply floats and basic styling to divide a web page into sections based on a given design.

### Files Needed
- [`index.html`](index.html) (provided)
- `layout.css` (to be created)

---

## Instructions

### Step 1: Understanding the HTML Structure
- Open the provided `index.html` file in a code editor.
- Review the HTML structure:

```html
<html>
<head>
    <title>Web Layout Exercise</title>
</head>
<body>
    <header>Header</header>
    <nav>Nav</nav>
    <article>Article <span>text1</span> <span>text2</span></article>
    <div>Ads</div>
    <footer>Footer</footer>
</body>
</html>
```

This file contains the structure we will style using CSS.

---

### Step 2: Setting Up the CSS File
- In your code editor, create a new file and name it `layout.css`.
- In the `<head>` section of `index.html`, link the CSS file:
```html
<link rel="stylesheet" href="layout.css">
```

- Write a CSS rule in `layout.css` to perform the following:
   - Set all the margins and padding for all HTML elements to be zero to ensure consistent rendering across different browsers.
   - Use the CSS selector that can apply the style to all elements.
   - Set the `box-sizing` property so that padding and border are included in the width and height.
```css
```

---
### Step 3: Styling the Page Body
- Add the following styles to your CSS file under the previous code:
    - Set font family to Arial for better readability.
```css
```

---
### Step 4: Styling the Header, Nav, Article, Ads, and Footer
- Add the following CSS rules to style the page sections:
    - Allow space 10px around the content.
    - Use yellow background to match the design.
    - Add borders as gray color solid lines to separate each section.
    - Center the text in each section.
```css
```

---
### Step 5: Positioning the Layout Using Floats
- Add the following CSS code to position the layout:
    - Assign width percentages to header and footer to 100%.
    - Position the nav, article, and div elements side by side using float.
    - Assign width percentages to each remaining section: 20% for nav and div, and 60% for article. Set a height of these elements to 200px for visualization purposes.
    - Ensures the footer appears below the nav, article, and div sections.
```css
```

---
### Step 6: Testing the Layout
- Open the index.html file in a web browser.
- Verify that the layout appears as follows:
    - The header spans the full width of the page.
    - The nav, article, and div sections are side by side.
    - The footer spans the full width at the bottom of the page.

---
### Extension Task (Optional 10-15 minutes): Customize the Layout
- As an additional task, students can experiment with the following:
    - Change the colors of the sections.
    - Adjust the widths of the nav, article, and div.
    - Add more content to each section.
