1.Html and HTML5
A: -the standard markup language used for creating the structure of web pages. It consists of a series of elements      (tags) that tell the browser how to display the content, such as text, images, links, tables, and other multimedia components.eg: video,audio,footer,header,nav bar,<article>, <nav>, <aside>, and <figure>

    HTML5 is a advanced version of HTML4, new features added like nav, header, footer

2. explain head, title, body?
A:      ### 1. **`<head>`:**
            - Contains meta-information about the document (e.g., character set, page description).
            - Includes elements like `<title>`, `<meta>`, `<link>`, and `<style>`.
            - It is not visible in the browser's main content area but affects the page's behavior and SEO.

        ### 2. **`<title>`:**
            - Sets the title of the web page, displayed in the browser tab.
            - Appears in search engine results as the clickable link.
            - Placed inside the `<head>` section.

        ### 3. **`<body>`:**
            - Contains the main content of the web page, including text, images, videos, and other elements.
            - Everything inside the `<body>` tag is rendered on the browser window for users to see.
            - Represents the visible structure of the web page.

3. Elements and tags
    -element: <tag>content</tag>
    -tag: no need content

4. Attributes: provide additional information like src,id,class,href,alt,height,width,type...
    Rules:
    -Attribute values are enclosed in quotes.
    -Multiple attributes can be added to a single element, separated by spaces.

5. <b> vs <strong>
        <b> (Bold): and <i>(italic)
        - Used to display text in bold style.
        - Does not convey any semantic meaning (purely presentational).
        - Example: <p>This is <b>bold</b> text.</p>
        
        <strong> (Strong Importance): <em>
        -Indicates that the text has strong emphasis or importance.
        -Conveys semantic meaning, making it more meaningful for screen readers and search engines.
        -Usually displayed in bold style, but its primary function is to highlight importance.
        -Example: <p>This is <strong>strongly emphasized</strong> text.</p>
        Key Difference:
        For accessibility and SEO, prefer <strong> over <b>.

6. Different form of colour:
        - Hex: #FF5733 (orange)
        - RGB: rgb(255, 0, 0) (red)
        - RGBA: rgba(255, 0, 0, 0.5) (semi-transparent red)
        - HSL: hsl(240, 100%, 50%) (blue)
        - HSLA: hsla(240, 100%, 50%, 0.5) (semi-transparent blue)
        - Color Name: coral

7. Link:
    -General--> <a href="url">link text</a>
    -Email--> <a href="mailto:someone@example.com">Send email</a>
    -Button--> <button onclick="document.location='https://eloquentjavascript.net/00_intro.html'" target="">HTML Tutorial</button>

    The "target" attribute specifies where to open the linked document.
    The "target" attribute can have one of the following values:

    - _self - Default. Opens the document in the same window/tab as it was clicked
    - _blank - Opens the document in a new window or tab
    - _parent - Opens the document in the parent frame
    - _top - Opens the document in the full body of the window
            
8.<link> tag
        - used to link external resources
        - rel: Specifies the relationship between the current document and the linked resource. For stylesheets, it should be stylesheet.
        - href: Specifies the URL of the linked resource (in this case, the CSS file)

9. Lists:
    - ordered list(ol)
    - unordered list(ul)
    - defination list(dl,dt,dd)

10. block and inline element
     - Block elements take up the full width available (stretches to the left and right) and start on a new line.
      eg. div,p,h1..h6,
    - inline elements take up only as much width as necessary 
     eg. a,img,span, em,i,strong

11. <div> vs <span>

12. class and id: id is unique, but class name would be same.

13. Tags used in head.
    <title>,<meta>,<link>,<style>,<script>

14. HTML Layout:
     - header, navigation, main content, sidebar, and footer.

15. semantic and non-semantic
        - Semantic: elements which have meaning and Better for search engine optimization eg. nav,header, footer, article, img
        - Non-Semantic: don't have meaning. eg. span,div,b,i

16. HTML Entity:displaying reserved characters, special symbols, and characters from different languages
    eg. &amp;,&copy; , &lt;, 

17. Void /self closing tags: <br>,<hr>,<img/>,<link>,<input>,<area>

18. CSS apply : 3 ways-->inline (like attribute eg. style=""),internal(<style> tag),external(<link rel="" href="">)

19. JS inject: 3 ways--> inline, internal(script tag), external(src),in body.

20. lang attribute: use for language purpose, date format, screen reader,right to left,font size vary according to lang, alert prompt based on lang.

21. Validation tool: W3C Validator

22. Importance of UTF-8(Unicode Transformation Format - 8-bit) in HTML
        Global Language Support: UTF-8 can represent characters from virtually every language and script, enabling seamless multilingual content.

        Compatibility: It is widely supported by modern browsers and programming languages, ensuring consistent text rendering across platforms.

        SEO Benefits: Using UTF-8 helps search engines properly index all characters, enhancing visibility in search results.

        Accessibility: It improves text interpretation for screen readers and assistive technologies, making content more accessible.

        HTML Declaration: Specifying UTF-8 in the <meta charset="UTF-8"> tag prevents character corruption and ensures correct display.

        Ease of Use: UTF-8 eliminates the need for multiple encodings, simplifying development and maintenance.

23. Graphics:
    1. SVG:SVG graphics are scalable, and do not lose any quality if they are zoomed or resized:
        Reason for use: SVG is a powerful tool for creating graphics on the web, offering scalability, small file sizes, interactivity, and high-quality rendering. Its versatility and ease of use make it a popular choice for modern web design and development.
     eg. <svg width="100" height="100">
             <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
             <rect x="10" y="10" width="200" height="100" stroke="red" stroke-width="6" fill="blue" />
        </svg>

    2. Canvas: HTML Canvas is a powerful tool for creating dynamic and interactive graphics on the web. Its flexibility and performance make it a popular choice for games, animations, and data visualizations.
        eg.  <canvas id="myCanvas" width="400" height="200" style="border:1px solid #000000;"></canvas>
        getContext(): Retrieves the drawing context for the canvas, such as 2d or webgl.
        fillRect(x, y, width, height): Draws a filled rectangle.
        strokeRect(x, y, width, height): Draws a rectangle outline.
        arc(x, y, radius, startAngle, endAngle, anticlockwise): Draws a circle or arc.
        drawImage(): Draws an image onto the canvas.

24. using a existing css file into another file using @import
    eg. @import url("header.css");

25. 
