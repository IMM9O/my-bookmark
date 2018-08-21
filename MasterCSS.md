## CSS Basics

Learn the basics and prerequisite first then learn those topics in order to master css not to just learn it

1.  [CSS Selectors](#css-selectors)
2.  [CSS Values](#css-values)
3.  [CSS Specificity](#css-specificity)
4.  [Styling](#styling) (text, boxes, tables and forms )
5.  [CSS Layout](#css-layout)
6.  [Responsive Web Design](#responsive-web-design) ( RWD )
7.  [CSS Animations and Drawing](#css-animations-and-drawing)
8.  [CSS Preprocessors](#css-preprocessors)
9.  [CSS Architecture](#css-architecture)
10. [CSS Frameworks](#css-frameworks) ( optional )

- Three Types of Style Sheet

  - Inline style ( style attribute )
  - Internal style
  - External style

- [Introduction to HTML](https://scrimba.com/g/ghtml)
- [Introduction to CSS](https://scrimba.com/g/gintrotocss)

- [HTML Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=UB1O30fR-EE) - by Traversy Media on Youtube.
- [CSS Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=yfoY53QXEnI) - by Traversy Media on Youtube.

---

## CSS Selectors

> In CSS, selectors are used to target the HTML elements on our web pages that we want to style.

- [CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Selectors)

  - [Simple Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Simple_selectors)
    - Element
    - Class
    - Id
    - Universal Selector ( _, ns|_, _|_, |\* )
  - [Combinators & Multiple selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Combinators_and_multiple_selectors)
    - Group of selector [A, B].
    - Descendant selector [A B].
    - Child selector [A > B].
    - Adjacent sibling selector [A + B].
    - General sibling selector [A ~ B].
  - [Attribute Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Attribute_selectors)
  - [Pseudo-class and Pseudo-element Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Pseudo-classes_and_pseudo-elements)

---

## CSS Values

> Thers is 4 types of values in css

1.  Pre-Defined Options
2.  Colors.
3.  Length, sizes and numbers.
4.  Functions.

> How CSS values are processed.

- [Initial value](https://developer.mozilla.org/en-US/docs/Web/CSS/initial_value)
- [Resolved value](https://developer.mozilla.org/en-US/docs/Web/CSS/resolved_value)
- [Specified value](https://developer.mozilla.org/en-US/docs/Web/CSS/specified_value)
- [Computed value](https://developer.mozilla.org/en-US/docs/Web/CSS/computed_value)
- [Used value](https://developer.mozilla.org/en-US/docs/Web/CSS/used_value)
- [Actual value](https://developer.mozilla.org/en-US/docs/Web/CSS/actual_value)

- CSS Variables

  - [Learn CSS Variables for free](https://scrimba.com/g/gcssvariables)
  - [CSS Variables Tutorial (CSS Custom Properties)](https://www.youtube.com/watch?v=sQUB039MG0I) - by Traversy Media on Youtube.

---

## CSS Specificity

> CSS is an acronym for Cascading Style Sheets, which indicates that the notion of the cascade is important. At its most basic level it indicates that the order of CSS rules matter, but it's more complex than that. What selectors win out in the cascade depends on three factors (these are listed in order of weight — earlier ones will overrule later ones):

- [Cascading and Inheritance](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Cascade_and_inheritance)

1.  Importance
2.  Specificity
    - [How is specificity calculated?](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)
    - [Specificity Calculator](https://specificity.keegan.st/)
3.  Source order

> CSS inheritance is the last piece we need to investigate to get all the information and understand what style is applied to an element. and it has lowest priority even after ( user agent / browser ) styles.

- [inheritance](https://developer.mozilla.org/en-US/docs/Web/CSS/inheritance)
- [Debugging CSS Code](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Debugging_CSS)

---

## Styling Content

- Text ( Typography )

  - Use HTML Tags for text
  - font-size
  - font-family
  - font-weight
  - font-style
  - line-height
  - color
  - text-align
  - text-transform
  - text-decoration
  - [Styling Lists](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_lists)
  - [Styling Links](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links)

- Media ( Image, Video and Audio )

- Tables

- Forms

- CSS Box Model ( Any Bloc element is a box model)

  - Content ( images, text .... etc )
  - Padding ( Transparent area around the content, inside of the box )
  - Borders ( goes around the padding and content )
  - Margins ( Space around elements, outside of any defined borders. )
  - Fill Area ( area the contain border, padding and content, and filling with backround and bacground-image )
  - Box Sizing
    - content-box: Width and height only apply to the content of the element
    - border-box: Include padding and border in the element's total width and height
  - Background
    - background
    - background-color
    - background-image
      - Multiple Background Images.
      - Linear Gradients.
      - Radial Gradients.
    - background-size
    - background-position
    - background-repeat
    - background-attachment
    - background-origin
    - background-clip
    - background-blend-mode
  - clip-path

---

## CSS Layout

- The Display Property

  - Display block ( flex, list-item and table )
  - Display inline
  - Display inline-block

- Floats

  - [CSS Floats Explained - DevTips](https://www.youtube.com/watch?v=609adV3pTME)
  - [CSS Floats and Clears Explained - DevTips](https://www.youtube.com/watch?v=xFGBNv2KeVU)

- Positioning Techniques

  - [CSS POSITIONING (PART1) - DevTips](https://www.youtube.com/watch?v=kejG8G0dr5U)
  - [CSS POSITIONING (PART2) - DevTips](https://www.youtube.com/watch?v=Rf6zAP4YnZA)

  * Normal Flow

    - Default ( no property specified )
    - Relative Positioning

    * Absolute Positioning
      - Absoulte ( Absoulte to the nearst relative box )
      - Fixed ( absoulte for the html )
      - Sticky

    * Stacking Content
      - Z-Index property

- Flexbox

  - [Flexbox Complete Guide - CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [CSS Flexbox Course - freeCodeCamp](https://www.youtube.com/watch?v=-Wlt8NRtOpo)
  - [CSS flexbox Course - WesBos](https://flexbox.io/)
  - [20 minutes Flexbox Crash Course](https://youtu.be/JJSoEo8JSnc) - by Traversy Media on Youtube.

- Grids

  - [CSS Grid Complete Guide - CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
  - [CSS Grid Course - freeCodeCamp](https://www.youtube.com/watch?v=t6CBKf8K_Ac)
  - [CSS Grid Course - WesBos](https://cssgrid.io/)
  - [CSS Grid Crash Course](https://youtu.be/jV8B24rSN5o) by Traversy Media on Youtube.
  - [CSS Grid Introduction - Udemy Tech](https://www.youtube.com/watch?v=oz0fbFviLIU)

---

## Responsive Web Design

- [Responsive Web Design Fundamentals](https://udacity.com/course/responsive-web-design-fundamentals--ud893)
- [Build An HTML5 Website With A Responsive Layout](https://www.youtube.com/watch?v=Wm6CUkswsNw) - by Traversy Media on Youtube.

* Common Responsive Patterns

  - Mostly Fluid
  - Column Drop
  - Layout Shifter
  - Off Canvas

* Media Queries
* Responsive Images

  - [Responsive Images](https://udacity.com/course/responsive-images--ud882)

* Which Method Should You Use for Your Responsive Layout? ( Mobile-First vs Desktop-First )

---

## CSS Animations and Drawing

- CSS Transforming

  - Transform: translate()
  - Transform: rotate() and Transform-Origin
  - Transform: scale()
  - Transform: skew()
  - Transform Shorthand

- CSS Transitions

  - Transition Duration
  - Transition Property
  - Transition Timing Function
  - Transition Delay
  - Transition Shorthand

- CSS Animation

  - CSS Animation Keyframes
  - CSS Animation Duration
  - CSS Animation Fil Mode
  - CSS Animation Iteration Count
  - CSS Animation Delay
  - CSS Animation Direction
  - CSS Animation Timing Function
  - CSS Animation Properties
  - CSS Animation Shorthand
  - [CSS Animation Performance](https://www.html5rocks.com/en/tutorials/speed/high-performance-animations/)

- CSS Shapes

  - Introducing CSS Shapes
  - CSS Shapes: the inset() function
  - CSS Shapes: The circle() Function
  - CSS Shapes: The ellipse() Function
  - CSS Shapes: The polygon() function
  - CSS Shapes: Shapes from the Alpha Channel
  - CSS Shapes: Shapes from the Reference Box

---

## CSS Preprocessors

- [SASS](https://sass-lang.com/)
  - [SASS Tutorial](https://www.youtube.com/watch?v=wz3kElLbEHE)
  - [Sass Workflow & Dev Server From Scratch Using Gulp](https://www.youtube.com/watch?v=rmXVmfx3rNo)
- [PostCSS](http://postcss.org/)

---

## CSS Architecture

- [BEM](http://getbem.com/)
- [OOCSS](http://oocss.org/)
- [SMACSS](https://smacss.com/)
- [SUITCSS](https://suitcss.github.io/)
- [Atomic](https://acss.io/)

---

## CSS Frameworks

- [Bootstrap](https://getbootstrap.com/)
- [Tailwind CSS](https://tailwindcss.com/)
