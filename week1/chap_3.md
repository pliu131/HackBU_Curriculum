Big Concepts

The Multitude of Devices
  - bradfrostweb.com images
  - Before 2007 (aka, introduction of the iPhone), web pages were typically 960px because there weren't many variations on screen sizes
  - Now, you go on web pages on anything connected to the internet (tablets and mobile devices)
  - Designing for these devices also means designing for context (where is the user, what are they doing at the moment, what information do they need, how fast is their connection)
  - Most people are online on their mobile devices now
  - Not to mention not everyone is using the same browser
  - Key point: what you see when you're designing a web site isn't what someone else might be seeing, keep that in mind

  - Additional reading
    - The Coming Zombie Apocalypse
    - Mobile First
    - Future Friend.ly

Web Standards
  How do we deal with multitude of devices?
  Stick to the standard for HTML, CSS, and JavaScript set by the W3C (World Wide Web Consortium) to make sure it is consistent as possible over standards-complaint web browsers (99% of them are)
  (Also nice thing to tell people)

  - Additional Read
    - Designing with Web Standards


Progressive Enhancement
  - No browser has implemented all standards and some users set their own preferences (like turning off JavaScript)
  - Not all browsers have the same capabilities (CSS3 and HTML5 are still being written and not all browsers can utilize these technologies)

  - Because not all browsers are capable, progressive enhancement advocates creating a baseline experience that will function on even the most basic browsers.
  - Then when you're down with that, you can add all the nice to have features like animations and gradient. It's a lot like buying a car.

  Strategies with:
  - HTML - Make sure the elements on a page are marked up in a meaningful way
  - CSS - There are ways to make a background of an element red but there are also ways to add a gradient effect for browsers that support that or add it only on browsers that support it. Basically, you have fallback options if something fails because browsers will just ignore anything they don't understand.
  - JavaScript - Makes pages dynamic and interactive. Browsers handle JS differently (sometimes breaks things), and some people turn it off, so again, make the baseline experience work without JS


Responsive Web Design
  - When you go to a website on a mobile device, sometimes they fit the entire page into the screen and you have to zoom in and out to be able to read the text. Obviously, text to small to read and links are too hard to click

  - Responsive web design adjusts the layout of a webpage depending on the screen size of the device you're using
    - Show an example on mediaqueri.es and talk about how things are split up into columns and links larger and smaller

  - Doesn't solve all problems; some websites have mobile apps that provide a much better experience and take advantage of all the capabilities of a device (for web apps)

  - Some websites make a separate mobile site


Accessibility
- Design to create as few barriers as possible to access information, regardless of ability and device used
- Also benefit users with images/JS disabled, mobile devices, and older browsers over slow internet connection
- Also more effectively indexed by search engines

Four Broad Categories
- Vision Impairment - may use screen reader, Braille display, screen magnifier; may also zoom to make text large enough
- Mobility Impairment - Limited use of hands: modified mice and keyboards, foot pedals, or joysticks to navigate web
- Auditory Impairment - provide transcripts for audio tracks and captions for video (think about educational videos)
- Cognitive Impairment - memory, reading comprehension, problem solving, and attention limitations: design websites simply and clearly (don't add too much visual noise and distractions)

Web Accessibility Initiative - address this need
- Also, if you ever design a website for the government, you must comply

Site Performance
- It's frustrating to wait for a website to load
- If a website takes more than 2 seconds to load, users get frustrated and 1/3 of them will leave, and probably won't come back (bad people...)
- Amazon increased revenue by 1% by shaving 100ms on loading times

What You Can Do
- Optimize/compress images
- Minimize HTML/CSS by removing whitespace and line breaks
- Keep JS to a minimum
- Add scripts so they load in parallell with other page assets and don't block rendering
- Don't load unnecessary assets
- Reduce number of times browser has to make requests to the server (HTTP requests)

- Things make a surprising amount of server requests. Chrome inspector to look.

More Readings (compile this list)

QUESTIONS
- List unknown factors to consider when designing a website
- Progressive enhancement, server-side detection, responsive design, wai-aria, site performance optimization
- Name the categories of disabilities
- When to use a waterfall chart
- Responsive web design - good and where it falls short

