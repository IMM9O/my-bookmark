## CSS Basics

Learn the basics and prerequisite first then learn those topics in order to master css not to just learn it

1.  [CSS Selectors](#css-selectors)
2.  [CSS Values](#css-values)
3.  [CSS Specificity](#css-specificity)
4.  [Styling](#styling)
5.  [CSS Layout](#css-layout)
6.  [Responsive Web Design](#responsive-web-design)
7.  [CSS Animations and Drawing](#css-animations-and-drawing)
8.  [CSS Preprocessors](#css-preprocessors)
9.  [CSS Frameworks](#css-frameworks)
10. [CSS Architecture](#css-architecture)

- Three Types of Style Sheet

  - Inline style ( style attribute )
  - Internal style
  - External style

- [Introduction to HTML](https://scrimba.com/g/ghtml) - scrimba
- [Introduction to CSS](https://scrimba.com/g/gintrotocss) - scrimba

- [HTML Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=UB1O30fR-EE) - by Traversy Media on Youtube.
- [CSS Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=yfoY53QXEnI) - by Traversy Media on Youtube.

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

  - [Everything you need to know about CSS Variables](https://medium.freecodecamp.org/everything-you-need-to-know-about-css-variables-c74d922ea855)
  - [Learn CSS Variables Course](https://scrimba.com/g/gcssvariables) - scrimba

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

## Styling Content

- Typography

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

- Lists

  - [Styling Lists](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_lists)

- Links

  - [Styling Links](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links)

- Media ( Image, Video and Audio )

- Tables

  - [A Complete Guide to the Table Element](https://css-tricks.com/complete-guide-table-element/)

- Forms

- Buttons

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

## CSS Layout

- **[Learn CSS Layout](http://learnlayout.com/)**

- The Display Property

  - Display block ( flex, list-item and table )
  - Display inline
  - Display inline-block

- Floats

  - [All About Floats](https://css-tricks.com/all-about-floats/)
  - [CSS Floats Explained](https://www.youtube.com/watch?v=609adV3pTME) - DevTips
  - [CSS Floats and Clears Explained](https://www.youtube.com/watch?v=xFGBNv2KeVU) - DevTips

- Flexbox

  - [CSS flexbox Course](https://flexbox.io/) - by WesBos
  - [Flexbox Complete Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - CSS Tricks
  - [The Complete Illustrated Flexbox Tutorial](https://medium.freecodecamp.org/the-complete-illustrated-flexbox-tutorial-d35c085dbf35)
  - [The Ultimate Guide to Flexbox ](https://medium.freecodecamp.org/the-ultimate-guide-to-flexbox-learning-through-examples-8c90248d4676)
  - [Understanding Flexbox: Everything you need to know](https://medium.freecodecamp.org/understanding-flexbox-everything-you-need-to-know-b4013d4dc9af)

- Grids

  - [CSS Grid Course](https://cssgrid.io/) - by WesBos
  - [CSS Grid Complete Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - CSS Tricks
  - [CSS Grid — The Beginner’s Guide](https://medium.freecodecamp.org/css-grid-the-beginners-guide-45998e6f6b8)
  - [How to create an image gallery with CSS Grid](https://medium.freecodecamp.org/how-to-create-an-image-gallery-with-css-grid-e0f0fd666a5c)

## CSS Positioning

- [CSS POSITIONING (PART1)](https://www.youtube.com/watch?v=kejG8G0dr5U) - DevTips
- [CSS POSITIONING (PART2)](https://www.youtube.com/watch?v=Rf6zAP4YnZA) - DevTips

- Normal Flow

  - Default ( no property specified )
  - Relative
  - Absoulte
  - Fixed
  - Sticky
  - Stacking Content ( Z-Index property )

## Responsive Web Design

- Common Responsive Patterns

  - Mostly Fluid
  - Column Drop
  - Layout Shifter
  - Off Canvas

- Media Queries
- Responsive Images
- Which Method Should You Use for Your Responsive Layout? ( Mobile-First vs Desktop-First )

* [Responsive Web Design Fundamentals](https://udacity.com/course/responsive-web-design-fundamentals--ud893)
* [Responsive Images](https://udacity.com/course/responsive-images--ud882)

## CSS Animations and Drawing

- CSS Animations: Transforms

  - Transform: translate()
  - Transform: rotate() and Transform-Origin
  - Transform: scale()
  - Transform: skew()
  - Transform Shorthand

- CSS Animations: Transitions

  - Transition Duration
  - Transition Property
  - Transition Timing Function
  - Transition Delay
  - Transition Shorthand

- CSS Animations: Keyframes

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

## CSS Preprocessors

- [SASS](https://sass-lang.com/)
  - [SASS Tutorial](https://www.youtube.com/watch?v=wz3kElLbEHE)
  - [Sass Workflow & Dev Server From Scratch Using Gulp](https://www.youtube.com/watch?v=rmXVmfx3rNo)
- [PostCSS](http://postcss.org/)

## CSS Frameworks

- [Bootstrap](https://getbootstrap.com/)

  - [Learn Bootstrap 4 Course](https://scrimba.com/g/gbootstrap4) - scrimba
  - [Bootstrap 4: Everything You Need to Know](https://medium.freecodecamp.org/bootstrap-4-everything-you-need-to-know-c750991f6784)
  - [Bootstrap Framework — Best Practices](https://hackernoon.com/bootstrap-framework-best-practises-b1d81c02d6cf)

- [Bulma](https://bulma.io/)

  - [Bulma Crash Course](https://www.youtube.com/watch?v=IiPQYQT2-wg&index=23&list=PLillGF-RfqbZTASqIqdvm1R5mLrQq79CU) - by Traversy Media on Youtube.
  - [learn Bulma Course](https://scrimba.com/g/gbulma) - scrimba

## CSS Architecture

- [BEM](http://getbem.com/)
- [OOCSS](http://oocss.org/)
- [SMACSS](https://smacss.com/)
- [SUITCSS](https://suitcss.github.io/)
- [Atomic](https://acss.io/)
