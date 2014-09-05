Chapter 7 - Adding Images
======
Images on the web work two ways:
  - Background image
  - Image element

Image formats - not all are supported! Only GIF, PNG, and JPEG (and also SVGs can be sourced)

For others like TIFF, BMP, EPS, can link to the file on the folder for access to it, but web browsers wouldn't know how to display it. Like when you download PDFs in Chrome. 

Image Tag
<img src="" alt=""> - inline element
Show example in a paragraph and is also by default, aligned with the baseline.

Whenever you load an image, you make a request to the server for the file. Sometimes when you have a slow connection, the image loads slowly. In general, want to prevent loading too many images on a page. 

Things to note
- Empty element - no text content like a line break or a horizontal rule
- Replaced Element - replaced by an external file when page is displayed, like a video


Two attributes are required
- src - where to find the file
- alt - describe the photo; serve as a replacement for the content that describes the photo (use the if you're happy and you know it example)
  - you can leave this attribute empty, but don't leave it out altogether; do this when the image you add doesn't add any value to the surrounding text
  - This is important for screen readers
  - Alt text on different browsers

Image Accessibility and figures/figcaptions with descriptions for big images that need it

Attributes - width and height - good because the web page is waiting for the page to restructure itself if you don't; if you do, it automatically saves the space for the item. Think about when you show up late for something

- Match with actual size (in pixels) because you don't want to request a large image when you don't need (exception with responsive design)


Window in a window 
- Iframe

Exercises
- The one with images and the test questions

