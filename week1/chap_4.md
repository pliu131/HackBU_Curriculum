This is the interactive part.
Things to Go Through
Process
1. Start with the content - raw text
2. Give the document structure - with HTML (learn element syntax and elements that structure the website)
3. Identify text elements - describe content using the proper HTML elements and learn how to properly use HTML elements
4. Add an image - also learn about attributes and empty elements
5. Change the page appearance with a stylesheet

Launching a text editor (default ones on Windows and Mac (Notepad and TextEdit))
- Settings for each, I'll just check in the book

1. Start with Content
Paste the content and save the document after creating a folder for the project. Save the file as index.html
(Open up the document in a web browser by navigating to the folder that contains it)

What We learn from viewing this
- The browser ignore line breaks (+ whitespace, wrong markup, and comments)
- Naming the file an html file isn't enough; we need to define the structure of the website)

2. Give the document structure
Include picture of what opening tags and closing tags look like
<elementname>Content Here</elementname>
Elements are ID'd with tags. 
Tags around content is called markup.
Some elements are empty (like img) because they don't contain any content

Basic Document Structure

<!DOCTYPE html>
<!-- doctype declaration - identifies this as an HTML5 document -->
<html lang="en">
<!-- Encloses all of the HTML, which has two elements: the head and the body -->
<head>
<!-- This provides information about the web page and is not shown in the browser window -->
  <meta charset="UTF-8">
  <!-- This defintes the character encoding -->
  <title>Document</title>
  <!-- This is required: shown in top of browser -->
</head>
<body>
The content goes here. This is what is shown in the browser.  
</body>
</html>

Interactive: add basic structure (and wrap content in body tag)


3. Identify text elements
- Semantic Markup - HTML is meant to add structure and meaning to the content; not meant for presentation 
  - The reason the elements do look different is because every browser has a stylesheet that presents each element differently
  - job is to choose the HTML markup that provides the most meaningful description of the content (SEMANTIC)
  - Gives the document structure - way that elements follow each other or nest within each other creates relationships between the elements (DOM - gives browsers cue on how to handle content - also foundation which we add presentation instructure with CSS and behaviors with JS)

  Elements to show off: h1, h2, p, em
  Then explain block and inline elements
  Add a border and a background to highlight elements

  The way they look is because of the way the browser renders it (a stylesheet)

4. Add an image
Empty Elements <elementname>, img and br
Attributes - instructions that clarify or modify an element 
img src is required and specify where to find the image file
attributename="value", can also do attributename='value'
Go in open tag or empty tag

Alt attribute - 

<elementname attribute="value">
<elementname attribute="value">Content</elementname>
<elementname attribute1="value" attribute2="value">Content</elementname>

Not all attributes take values (checked)
Values could be number word, text, URL

<h1><img src="hackbulogo.png" alt="HackBU logo"><br>Content</h1>

5. Change the look with a stylesheet

body {
  background-color: #fafa2e4;
  margin: 0 15%;
  font-family: sans-serif;
}

h1 {
  text-align: center;
  h1 {
  font-family: serif;
  font-weight: normal;
  text-transform: uppercase;
  border-bottom: 1px solid #000;
  margin-top: 30px;
}

h2 {
  color: red;
  font-size: 1em;
}

Validating Documents
Very easy to make mistakes 
Forgetting slash in closing tag
Forgetting quotes in attributes

Test Questions
ALL


