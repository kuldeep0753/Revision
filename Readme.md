# HTML and HTML5 Concepts

## 1. HTML and HTML5
HTML is the standard markup language used for creating the structure of web pages. It consists of elements (tags) that tell the browser how to display content such as text, images, links, and multimedia components (e.g., video, audio, footer, header, navbar, `<article>`, `<nav>`, `<aside>`, and `<figure>`).

HTML5 is an advanced version of HTML4, with new features like `<nav>`, `<header>`, and `<footer>`.

## 2. Head, Title, Body Tags
### 1. **`<head>`**:
   - Contains meta-information about the document (e.g., character set, page description).
   - Includes elements like `<title>`, `<meta>`, `<link>`, and `<style>`.
   - Affects page behavior and SEO but is not visible in the main content.

### 2. **`<title>`**:
   - Sets the title displayed in the browser tab and appears in search results.
   - Placed inside the `<head>` section.

### 3. **`<body>`**:
   - Contains the main content of the web page (text, images, videos, etc.).
   - Everything inside the `<body>` is rendered for users to see.

## 3. Elements and Tags
- **Element**: `<tag>content</tag>`
- **Tag**: May or may not require content.

## 4. Attributes
Attributes provide additional information like `src`, `id`, `class`, `href`, `alt`, `height`, `width`, `type`, etc.
- Attribute values are enclosed in quotes.
- Multiple attributes can be added to an element, separated by spaces.

## 5. `<b>` vs `<strong>`
- **`<b>`** (Bold): Used to display text in bold style. No semantic meaning (purely presentational).
- **`<strong>`** (Strong Importance): Indicates strong emphasis or importance and conveys semantic meaning. For accessibility and SEO, prefer `<strong>` over `<b>`.

## 6. Different Forms of Color
- **Hex**: `#FF5733` (orange)
- **RGB**: `rgb(255, 0, 0)` (red)
- **RGBA**: `rgba(255, 0, 0, 0.5)` (semi-transparent red)
- **HSL**: `hsl(240, 100%, 50%)` (blue)
- **HSLA**: `hsla(240, 100%, 50%, 0.5)` (semi-transparent blue)
- **Color Name**: `coral`

## 7. Links
- **General**: `<a href="url">link text</a>`
- **Email**: `<a href="mailto:someone@example.com">Send email</a>`
- **Button**: `<button onclick="document.location='url'">HTML Tutorial</button>`

Target attribute options:
- `_self`: Default, opens the link in the same window.
- `_blank`: Opens the link in a new tab/window.
- `_parent`: Opens the link in the parent frame.
- `_top`: Opens the link in the full window.

## 8. `<link>` Tag
- Used to link external resources.
- **`rel`**: Specifies the relationship (e.g., `stylesheet`).
- **`href`**: Specifies the URL of the linked resource.

## 9. Lists
- **Ordered List**: `<ol>`
- **Unordered List**: `<ul>`
- **Definition List**: `<dl>`, `<dt>`, `<dd>`

## 10. Block vs Inline Elements
- **Block Elements**: Take up full width and start on a new line (e.g., `<div>`, `<p>`, `<h1>` to `<h6>`).
- **Inline Elements**: Take up only necessary width (e.g., `<a>`, `<img>`, `<span>`, `<em>`, `<i>`, `<strong>`).

## 11. `<div>` vs `<span>`
- **`<div>`**: Block-level element used for layout and structure.
- **`<span>`**: Inline element used for styling parts of content.

## 12. Class vs ID
- **ID**: Unique to a page.
- **Class**: Can be used multiple times across elements.

## 13. Tags in `<head>`
- `<title>`, `<meta>`, `<link>`, `<style>`, `<script>`

## 14. HTML Layout
- **Header**, **Navigation**, **Main Content**, **Sidebar**, and **Footer**.

## 15. Semantic vs Non-Semantic Elements
- **Semantic**: Meaningful elements (e.g., `<nav>`, `<header>`, `<footer>`, `<article>`).
- **Non-Semantic**: Elements that don't carry meaning (e.g., `<div>`, `<span>`, `<b>`, `<i>`).

## 16. HTML Entities
Display reserved characters, symbols, and characters from other languages (e.g., `&amp;`, `&copy;`, `&lt;`).

## 17. Void/Self-Closing Tags
- Tags that don’t require closing (e.g., `<br>`, `<hr>`, `<img>`, `<link>`, `<input>`).

## 18. Applying CSS
- **Inline**: Using the `style` attribute.
- **Internal**: Inside `<style>` tag.
- **External**: Using `<link>` to an external CSS file.

## 19. Injecting JavaScript
- **Inline**, **Internal** (within `<script>`), and **External** (via `src` attribute).

## 20. `lang` Attribute
Used to specify the language of the page, which can affect date format, screen reader behavior, and right-to-left language support.

## 21. Validation Tool
- **W3C Validator**: Used for checking the validity of HTML code.

## 22. Importance of UTF-8
- UTF-8 supports all characters from various languages, ensures compatibility, improves SEO, and enhances accessibility. Declared in `<meta charset="UTF-8">`.

## 23. Graphics
### 1. **SVG** (Scalable Vector Graphics)
- Scalable, interactive, and high-quality rendering.
- Example:
  ```html
  <svg width="100" height="100">
      <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
  </svg>
### 2. **Canvas** 
Used for dynamic and interactive graphics, such as games and animations.
```html
Canvas: HTML Canvas is a powerful tool for creating dynamic and interactive graphics on the web. Its flexibility and performance make it a popular choice for games, animations, and data visualizations.
        eg.  <canvas id="myCanvas" width="400" height="200" style="border:1px solid #000000;"></canvas>
        getContext(): Retrieves the drawing context for the canvas, such as 2d or webgl.
        fillRect(x, y, width, height): Draws a filled rectangle.
        strokeRect(x, y, width, height): Draws a rectangle outline.
        arc(x, y, radius, startAngle, endAngle, anticlockwise): Draws a circle or arc.
        drawImage(): Draws an image onto the canvas.
```
Example
<canvas id="myCanvas" width="400" height="200" style="border:1px solid #000000;"></canvas>

24. Importing CSS Files
`@import url("header.css");`

## 25. Void/Self-Closing Tags
Examples include `<br>`, `<img />`, and `<input />`.

