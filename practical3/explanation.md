# Practical No. 3: Create and Link an External CSS Stylesheet

## Aim
To create an HTML webpage and link an external CSS stylesheet to apply styles to the webpage.

## Software Requirements
- Visual Studio Code
- Web browser
- HTML
- CSS

## Theory
External CSS is a method of applying styles to an HTML document using a separate file with the `.css` extension.

It allows us to maintain the design and layout of a webpage separately from its HTML structure.

The external CSS file is connected to the HTML document using the `<link>` tag inside the `<head>` section.

### Syntax

```html
<link rel="stylesheet" href="style.css">
```

- `link`: Connects an external resource to the HTML document.
- `rel="stylesheet"`: Specifies that the linked file is a stylesheet.
- `href="style.css"`: Specifies the path of the CSS file.

## Procedure
1. Open Visual Studio Code.
2. Create a folder named `Practical_03_External_CSS`.
3. Create three files: `index.html`, `style.css`, and `explanation.md`.
4. Write the HTML structure in `index.html`.
5. Write the styling rules in `style.css`.
6. Link the CSS file using the `<link>` tag inside the HTML `<head>` section.
7. Save all the files.
8. Open `index.html` in a web browser to view the webpage.

## Implementation
The HTML file contains the webpage structure, including a header, main content, button, and footer.

The external CSS file defines the font, colors, spacing, alignment, borders, and button hover effect.

## Result
Successfully created an HTML webpage and linked an external CSS stylesheet to apply styles to the webpage.

## Advantages of External CSS
1. Separates HTML structure from presentation.
2. Makes code easier to read and maintain.
3. Allows one CSS file to style multiple HTML pages.
4. Reduces repeated styling code.
5. Makes it easier to update the website design.
