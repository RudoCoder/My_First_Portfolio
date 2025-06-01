Introduction to HTML
What is HTML?
HTML stands for HyperText Markup Language. It is the standard language used to create and structure content on the web. HTML provides the basic building blocks for web pages, allowing developers to define elements such as headings, paragraphs, images, links, and more. It does not include styling or behavior—that's handled by CSS and JavaScript, respectively.

How to Create an HTML Page
Creating an HTML page is simple. You can use any text editor (like Notepad, VS Code, or Sublime Text). Save your file with a .html extension (e.g., index.html).

Here’s a basic example:

html
Copy
Edit
<!DOCTYPE html>
<html>
  <head>
    <title>My First Webpage</title>
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <p>This is my first webpage using HTML.</p>
  </body>
</html>
You can open the file in any web browser to see the result.

What is a Markup Language?
A markup language is a way of annotating a document so that it can be properly interpreted by a computer or browser. Unlike a programming language, it doesn’t include logic (like loops or conditions). Instead, it uses tags to define the structure and layout of content.

HTML is a markup language because it uses tags like <h1>, <p>, <img>, etc., to "mark up" content so browsers know how to display it.

What is the DOM?
The Document Object Model (DOM) is a programming interface for web documents. When a browser loads an HTML page, it parses the HTML and creates a tree-like structure called the DOM.

Each element in the HTML becomes a node in the DOM, allowing developers to use JavaScript to interact with and manipulate the page—such as changing content, styles, or responding to user actions (like clicks).

What is an Element / Tag?
An HTML element is the basic unit of an HTML page. It usually consists of:

An opening tag: e.g., <p>

Some content: e.g., This is a paragraph.

A closing tag: e.g., </p>

Example of a full element:

html
Copy
Edit
<p>This is a paragraph.</p>
Some elements are self-closing, like:

html
Copy
Edit
<img src="image.jpg" alt="A picture" />
What is an Attribute?
Attributes provide additional information about an HTML element. They are always specified in the opening tag and usually come in name="value" pairs.

Example:

html
Copy
Edit
<a href="https://example.com" target="_blank">Visit Example</a>
href tells the browser where the link should go

target="_blank" tells the browser to open the link in a new tab

How Does the Browser Load a Webpage?
User enters a URL or clicks a link

The browser sends a request to the server (e.g., via HTTP or HTTPS)

The server returns an HTML file

The browser parses the HTML and builds the DOM

The browser then loads any CSS for styling and JavaScript for interactivity

Once everything is processed, the browser renders the complete webpage for the user

How a Website Can Be Built with HTML, CSS, and JavaScript
HTML: Provides the structure (e.g., headers, paragraphs, forms)

CSS: Adds styling (e.g., colors, fonts, layout)

JavaScript: Adds behavior and interactivity (e.g., animations, form validation, dynamic content)

These three technologies are known as the core frontend web technologies. Every website on the internet is fundamentally built using them.

Example structure:

html
Copy
Edit
<!DOCTYPE html>
<html>
<head>
  <title>My Site</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>My Interactive Website</h1>
  <button onclick="sayHello()">Click Me</button>

  <script src="script.js"></script>
</body>
</html>

Note that:
style.css defines how the page looks

script.js defines how the page behaves
