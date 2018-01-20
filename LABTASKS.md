# Lab Tasks
## Summary
Your task for this lab is to develop two different looks for a web page using different CSS without altering the HTML.
 - All of the formatting (including the positioning of elements in the page) must be done using CSS.
 - Do not alter the HTML.
    - The _one_ exception to this rule is if you want to load Google Fonts in your HTML so they'll be available in your CSS. (There are ways to do this entirely in CSS, but the "standard" approach typically involves modifying the HTML.)
 - Be intentional and sparing with your use of absolute sizes for things like font and location. Your style sheet should make the web page look nice for both a phone and a computer screen, and your choices should not interfere with accessibility in obvious ways.

## Technical Requirements
Please read carefully the list of technical requirements below and follow it precisely.

  - Your page must be viewable using the three different **external CSS files** included in your repository (one will be an example and you will alter the other two).
  - Your **CSS must validate** using a [CSS validator](https://jigsaw.w3.org/css-validator/), except perhaps warnings about features not supported in all browsers.
    > Pro tip: Some newer CSS features are not widely supported. If a CSS feature you use is not supported in some browsers, please clearly indicate which browsers support it and which ones don't.
  - Your CSS must make the page **look reasonable and be relatively easy to navigate.** We will take points off for features that lead to a problematic user experience. Take care that your design avoids common pitfalls.
    - Avoid links that are hard to see.
    - Avoid unpleasant color combinations.
    - Avoid fonts that are hard to read.
      > Pro tip: Fonts specified in CSS can be different in different browsers! Just because `font-family: "Comic Sans"` looks sweet in Internet Explorer 5 (which you better not be using) does not mean it will in Chrome or Firefox.
      >
      > You can use nifty fonts from places like
      [Google Fonts](https://fonts.google.com); this will require
      an (acceptable) change to the HTML file to load in the necessary
      font files. Tools like [FontJoy](http://fontjoy.com) can be useful for
      helping find font combinations that look good together.
    - Your page must look reasonable in all standard browsers (recent Chrome, Firefox, Safari, IE, Edge) and adapt the layout so that elements remain accessible and visible when the window is resized.
      > Pro tip: Making web pages that can resize across many different screen sizes and devices is referred to as _responsive web design_. This is very important since [more web views are happening
      on phones now than on computers](https://www.theguardian.com/technology/2016/nov/02/mobile-web-browsing-desktop-smartphones-tablets).
      By using fancy styling and other tools to adjust how a web page looks, developers can make a single page that will look good
      on multiple screen sizes rather than constructing multiple
      designs for each type of device. To see how your page would look on some phones or tablets:
      Open your page in Chrome > right-click the page > click "inspect element" > click the little phone symbol in the top-left corner. This will show roughly what your site would look like on the chosen device. In Firefox, click on the Developer button and choose Responsive Design mode. Or just resize your browser
      window so that it's really narrow and see how it behaves.
  - Your CSS can leverage the fact that the page has the following **elements of interest**; see [the links in the README](./README.md) for support in understanding how to use CSS to alter the look of the page. You should particularly care about these features that were included to make the CSS more fun:
    - A **navigation bar.** Actually, this is just a list that is presented as a navigation bar in `style1.css' It must behave reasonably when you resize the window. In your style files, it may be horizontal or vertical, but should differ
    in some meaningful way between your two CSS files.
    - Four images of the faculty members **each of which has a div with a unique id**
    - Course requirements with a variety of parts that have class attribute values
    - Four faculty members in a list with their names and office locations in div classes
    - Multiple divs that have unique ids **but have the same class attribute value**
    - Multiple lists, both ordered and unordered **so that you may handle lists in different ways** and show some cool css features

## How do you know you are "done"? How will you be graded?
  - Be sure to view the rubric for the assignment to see how the technical requirements from the list above will impact your grade
  - **Each** of your CSS files must include **5 CSS rules with comments** that describe the impact of the rule and how it differs from the other two style sheets.
    - a rule is a selector followed by settings for this selector
    - you may include more rules to make the page look really cool, but please comment on the 5 that you wish to have graded from each file
  - In addition to the minimum of 5 CSS rules with comments (in each of the CSS files), your CSS you must use and point out in comments somewhere in your edited style files each of the following: **grouping, nesting, a class, and an id**.
    > Pro tip: If you play with grouping and nesting after you've already written a bit of CSS, it'll be easier to understand why it's so cool. A good explanation of grouping and nesting can be found [here](http://lmgtfy.com/?q=grouping+and+nesting+css&l=1). Also, you can see some general info on CSS selectors [here](http://www.w3schools.com/cssref/css_selectors.asp).
