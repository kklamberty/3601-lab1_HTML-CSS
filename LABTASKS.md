# Lab Tasks
## Summary
Your task for this lab is to develop two different looks for a web page using different CSS without altering the HTML.
 - All of the formatting (including the positioning of elements in the page) must be done using CSS. 
 - Do not alter the HTML. 
 - Do not use absolute settings for sizes, make them relative to your page size and your default font.  

## Technical Requirements
Please read carefully the list of technical requirements below and follow it precisely.

  - Your page must be viewable using the three different**external CSS files**included in your repository (one will be an example and you will alter the other two). 
  - Your**CSS must validate**using a[CSS validator,](https://jigsaw.w3.org/css-validator/)except perhaps warnings about features not supported in all browsers.
    > Protip: Some newer CSS features are not widely supported. If a CSS feature you use is not supported in some browsers, please clearly indicate which browsers support it and which ones don't. 
  - Your CSS must make the page**look reasonable and be relatively easy to navigate.** We will take points off for features that lead to a problematic user experience. Take care that your design avoids common pitfals. 
    - Avoid links that are hard to see.
    - Avoid unpleasant color combinations.
    - Avoid fonts that are hard to read.
      > Protip: Fonts specified in CSS can be different in different browsers! Just because ``font-family: "Comic Sans"`` looks sweet in Internet Explorer 5 (which you better not be using) doesn't mean it will in Chrome or Firefox.
    - Your page must look reasonable in all standard browsers (recent Chrome, Firefox, Safari, IE, Edge) and preserve its setup when the window is resized.
      > Protip: Making web pages that can resize across many different screen sizes and devices is referred to as _responsive web design_. This is a big thing right now. By using fancy styling, among other tools, to adjust how a web page looks, developers can make a single page rather than multiple for each type of device. To see how your page would look on some phones or tablets: open your page in Chrome > right-click the page > click "inspect element" > click the little phone symbol in the top-left corner. This will show roughly what your site would look like on the chosen device. 
  - Your CSS must leverage the fact that the page has the **following elements implemented as div elements;** use CSS positioning, see[the links in the README](./README.md)for support in understanding how to use CSS to alter:
    - A **navigation bar.** It must behave reasonably when you resize the window. It may be horizontal or vertical, but should differ between your two CSS files.
    - A **footer** with the company's address, contact information, etc.
  - At least **three images**. Since we don't have a real business to develop the page for, just use any images as a mock-up. Make sure you abide by relevant copyrights; it's probably simplest if you search for images that have appropriate Creative Commons licenses. The quality of the images is not a part of the grade.

> Protip: If you're having trouble finding decent images for your site, remember that you can take pictures with your phone and use them. As long as no people or company logos are featured prominently, images should be safe to use.

  - You must use at least **12 elements** in your page. List items of the same list count as one element for this purpose.
  - You must use at least **10 CSS rules** in your CSS file (a rule is a selector followed by settings for this selector).
  - In your CSS you must use each of the following: **grouping, nesting, a class, and an id**.
  
> Protip: If you play with grouping and nesting after you've already written a bit of CSS, it'll be easier to understand why it's so cool. A good explanation of grouping and nesting can be found [here](http://lmgtfy.com/?q=grouping+and+nesting+css&l=1). Also, you can see some general info on CSS selectors [here](http://www.w3schools.com/cssref/css_selectors.asp).
