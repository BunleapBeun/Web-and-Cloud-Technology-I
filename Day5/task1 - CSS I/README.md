## Task 1: CSS Basics

**Prompt:**

"Define CSS and explain its role in web development. Create a simple HTML document and include a basic CSS stylesheet
that changes the background color, text color, and font size of the page. Explain each part of the CSS code and its
effect on the HTML elements."

> ### ChatGPT

CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation of a document written in HTML or XML. It controls the layout, colors, fonts, and overall appearance of web pages, separating content from design. This separation makes it easier to maintain and update the visual style of a website without altering its underlying HTML structure.

**Role of CSS in Web Development:**

1. Styling: CSS allows developers to apply styles to HTML elements, including colors, fonts, spacing, and positioning.
2. Responsive Design: CSS supports media queries, enabling web pages to adapt to different screen sizes and devices.
3. Consistency: CSS helps maintain a consistent look across multiple pages of a website.
4. Improved Performance: By using external stylesheets, browsers can cache CSS files, improving load times.
5. Accessibility: Properly applied CSS can enhance the accessibility of web content, making it easier to navigate for users with disabilities.

**Simple HTML Document with CSS**

Here's a basic example of an HTML document that includes an internal CSS stylesheet:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Simple CSS Example</title>
    <style>
      body {
        background-color: #f0f0f0; /* Sets the background color of the page */
        color: #333333; /* Sets the text color */
        font-size: 16px; /* Sets the font size for the text */
        font-family: Arial, sans-serif; /* Sets the font family */
        margin: 0; /* Removes default margin around the body */
        padding: 20px; /* Adds padding inside the body */
      }

      h1 {
        color: #0056b3; /* Sets the color of <h1> headers */
        font-size: 2em; /* Increases the font size for <h1> headers */
      }

      p {
        line-height: 1.5; /* Increases line spacing for better readability */
      }
    </style>
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <p>This is a simple example of an HTML document styled with CSS.</p>
  </body>
</html>
```

**_Explanation of Each Part of the CSS Code_**

1. `body { ... }`: This rule applies styles to the entire body of the document.
   - `background-color: #f0f0f0;`: Sets the background color to a light gray.
   - `color: #333333;`: Sets the default text color to a dark gray.
   - `font-size`: 16px;: Sets the base font size for all text within the body.
   - `font-family`: Arial, sans-serif;: Specifies Arial as the primary font, with a fallback to sans-serif fonts.
   - `margin: 0;`: Removes any default margin around the body element.
   - `padding: 20px;`: Adds 20 pixels of padding inside the body, creating space between the content and the edges.
2. `h1 { ... }`: This rule styles the `<h1>` header element.
   - `color: #0056b3;`: Changes the text color of the header to a blue shade.
   - `font-size: 2em;`: Increases the font size of the header to 2 times the base font size.
3. `p { ... }`: This rule applies styles to paragraph elements.
   - `line-height: 1.5;`: Sets the line height to 1.5 times the font size, improving readability by providing more space between lines.

**Conclusion**

CSS is essential for creating visually appealing and user-friendly web pages. In this example, we've seen how to structure a simple HTML document and apply basic CSS styles to enhance its appearance. Understanding CSS is a fundamental skill for anyone involved in web development.

> ### Germini

CSS (Cascading Style Sheets) is a programming language used to style HTML elements. It controls the presentation of content on web pages, including layout, colors, fonts, and animations. By separating the content (HTML) from the presentation (CSS), CSS makes web development more efficient, maintainable, and reusable.

**Role of CSS in Web Development**

- Improving Readability: CSS enhances the visual appeal of web pages, making them easier to read and understand.
- Consistent Styling: It ensures a consistent look and feel across different web pages and devices.
- Responsiveness: CSS can be used to create responsive designs that adapt to different screen sizes.
- Accessibility: It helps to improve the accessibility of web content for users with disabilities.
- Maintenance: By separating content from presentation, CSS simplifies the process of updating and maintaining web pages.

**Creating a Simple HTML Document with CSS**

**HTML Document (index.html):**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First CSS Example</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is a paragraph of text.</p>
  </body>
</html>
```

**CSS Stylesheet (style.css):**

```css
body {
  background-color: lightblue;
}

h1 {
  color: red;
  font-size: 40px;
}

p {
  color: green;
  font-size: 18px;
}
```

**Explanation of CSS Code**

1. Selectors: The selectors (`body`, `h1`, `p`) specify the HTML elements that the styles will be applied to.
2. Properties: The properties (`background-color`, `color`, `font-size`) determine the style attributes of the elements.
3. Values: The values (`lightblue`, `red`, `green`, `40px`, `18px`) set the specific values for the corresponding properties.

**How the CSS affects the HTML elements:**

- The body selector styles the entire page, setting the background color to light blue.
- The `h1` selector styles the `<h1>` element, making the text red and increasing the font size to 40 pixels.
- The `p` selector styles the `<p>` element, making the text green and setting the font size to 18 pixels.

**_By combining the HTML and CSS, we create a web page with a visually appealing and customized appearance._**

## Task 2: Inline, Internal, and External CSS

**Prompt:**

"Explain the differences between inline, internal, and external CSS. Create an HTML page that demonstrates all three
methods. Include examples for each type, and explain the advantages and disadvantages of using each method."

## Task 3: CSS Selectors

**Prompt:**

"What are CSS selectors, and how do they work? Create an example HTML document that uses various selectors (element,
class, ID, attribute, and pseudo-classes). Provide CSS rules for each selector and explain how they target different
elements in the HTML."

## Task 4: How to Debug CSS

**Prompt:**

"Discuss common CSS issues and how to debug them. Provide a step-by-step guide on using browser developer tools to
inspect elements, identify CSS problems, and test changes live. Include a real example of a CSS issue and how you would
resolve it using debugging techniques."

## Task 5: Style on HTML

**Prompt:**

"Explain how to apply styles directly to HTML elements using the style attribute. Create an example HTML document where
specific styles are applied to elements via inline styles. Discuss the pros and cons of using inline styles compared to
external stylesheets."

## Task 6: Text and Font

**Prompt:**

"Describe how to style text and fonts in CSS. Create an example that demonstrates different text properties such as
font-family, font-size, font-weight, and text-align. Include a variety of text elements (headings, paragraphs, links) in
your HTML and style them accordingly."

## Task 7: Online Fonts and Favicon

**Prompt:**

"What are online fonts, and how can they be integrated into a website? Explain how to use Google Fonts in an HTML
document. Additionally, describe what a favicon is and how to add one to a web page. Provide examples of the HTML code
needed to implement both features."

## Task 8: Color and Background

**Prompt:**

"Explain how to apply colors and backgrounds in CSS. Create an example that demonstrates various ways to set colors (
hex, RGB, HSL) and background properties (solid color, gradient, image). Provide an HTML structure and the CSS styles
needed to achieve different effects."

## Task 9: Alignment and Display

**Prompt:**

"Discuss how to align elements in CSS and the different display properties available (block, inline, inline-block,
flex). Create an HTML document that showcases various alignment techniques, including text alignment, vertical
alignment, and the use of the display property. Explain each method used."

## Task 10: Box Model

**Prompt:**

"Define the CSS box model and its components (content, padding, border, margin). Create an example HTML layout and style
it using the box model. Provide visual examples showing how changing padding, margin, and border affects the layout and
spacing of elements."

## Task 11: Table and `<div>`

**Prompt:**

"Explain the use of tables and `<div>` elements for layout in CSS. Create an HTML document that uses both tables and
`<div>` elements to present content. Style them using CSS, and discuss when to use tables versus `<div>` elements for
layout."

## Task 12: Flexbox

**Prompt:**

"Describe the Flexbox layout model and how it simplifies responsive design. Create a responsive layout using Flexbox
that adjusts to different screen sizes. Include examples of properties like justify-content, align-items, and
flex-direction, and explain their effects on the layout."

## Task 13: Variables

**Prompt:**

"What are CSS variables (custom properties), and how do they work? Create an example that demonstrates how to define and
use CSS variables to maintain consistency in a stylesheet. Provide examples of changing the values of these variables
and explain how it affects the styles."
