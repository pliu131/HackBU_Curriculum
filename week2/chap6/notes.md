Chapter 6 - Adding Links
======
Topics
- Making links to external pages
- Making relative links (to documents on your own server)
- Linking to a specific point in a page
- Adding "mailto" and "tel" links
- Targeting new windows


The href attributes
- Absolute URLs - Points to a webpage on the web; includes full URL (uniform resource locator), pathname to the file, and the (http://) protocol
  href="http://hackbu.org/"

- Relative URLs - Describes the path to a file *relative* to the current page
  href="blog/post.html" (doesn't need the URL or the pathname; similar to how pages are organized on your computer)


Creating your first link
<a href="http://hackbu.org">HackBU</a>

List of Links
<ul>
  <li><a href="http://instagram.com/">Instagram</a></li>
  <li><a href="http://facebook.com/">Facebook</a></li>
  <li><a href="http://twitter.com/">Twitter</a></li>
</ul>

- Linking Within Your Own Site
  - show a diagram of a basic sitemap
  - Home
    - Images
      - logo.jpg
      - header.jpg
    - about.html
    - Index.html
    - Blog
      - programming.html
      - design.html
      - Microposts
        - today.html
        - yesterday.html


- Site Root Relative Pathnames
<a href="/blog/programming.html">Programming</a>
- Goes to the root of the website and then goes down from there

Linking/Sourcing Images
<img src="images/logo.jpg" alt="">
Adding image in lower pages (design.html)
<img src="../../images/logo.jpg" alt="">
<img src="/images/logo.jpg" alt=""> (This could work)

Linking to a specific point on a page
- Give the section an ID (where do you want to go to?)
<h1 id="aardvark">aardvark</h1>

- Linking to the destination
<a href="#aardvark">A</a>

Linking to a specific point on another
<a href="dictionary.html#aardvark">See the definition of 'aardvark'</a>


Targetting a New Browser Window
- When you want someone to open a link, e.g., an ad or something, in a new window

<a href="http://somespammyadsite.com/" target="_blank">Ad</a>
(New Window/Tab?)
<a href="http://somespammyadsite.com/" target="display">Ad</a>
(New Window/Popup)

Mail Links
<a href="mailto:pliu7@binghamton.edu">Peter Liu</a>

Telephone Links
<a href="tel:+13473500849">Call Peter Liu at (347) 350-0849!</a>
(allows you to click a link on your phone and it will open up your phones dialer)

Best Practices
- Full international dialing number
- Include phone number in link in case broken
- Sometimes other numbers are mistaken for phone numbers
Add
  <meta name="format-detection" content="telephone=no">
  <meta http-equiv="x-rim-auto-match" content="none">

Exercises
- Give a site map and ask them to link within it and also source images






