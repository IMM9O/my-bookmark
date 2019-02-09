# How To master CSS

There are tons of tutorials out there for learnng CSS, but most of them are just scratch the surface, for beginner, out of date and not comprehensive.
So i built my own curriculum

This is a somewhat opinionated curriculum for learning CSS collecting it from many resourcess over the internet.

## 📆 Curriculum

Learn the basics and prerequisite first then learn those topics in order to master css.

1.  [CSS Selectors](#css-selectors)
2.  [CSS Values](#css-values)
3.  [Styling](#styling)
4.  [CSS Layout](#css-layout)
5.  [CSS Specificity](#css-specificity)
6.  [Responsive Web Design](#responsive-web-design)
7.  [CSS Animations and Drawing](#css-animations-and-drawing)
8.  [CSS Preprocessors](#css-preprocessors)
9.  [CSS Frameworks](#css-frameworks)
10. [CSS Architecture](#css-architecture)

---

### CSS Basics

#### 📖 Contents

- CSS can be written in three places
  - Inline style ( style attribute )
  - Internal style
  - External style

#### 📚 References, Resources & Guids

- [Introduction to HTML | Scrimba](https://scrimba.com/g/ghtml)
- [Introduction to CSS | Scrimba](https://scrimba.com/g/gintrotocss)
- [HTML Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=UB1O30fR-EE) - by Traversy Media on Youtube.
- [CSS Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=yfoY53QXEnI) - by Traversy Media on Youtube.

---

### CSS Selectors

In CSS, selectors are used to target the HTML elements on our web pages that we want to style.

#### 📖 Contents

- CSS Selectors Types
  - Simple Selectors
    - Element
    - Class
    - Id
    - Universal Selector ( _, ns|_, _|_, |\* )
  - Combinators & Multiple selectors
    - Group of selector [A, B].
    - Descendant selector [A B].
    - Child selector [A > B].
    - Adjacent sibling selector [A + B].
    - General sibling selector [A ~ B].
  - Attribute Selectors
  - Pseudo-class Selectors
  - Pseudo-element Selectors

#### 📚 References, Resources & Guids

- [CSS Selectors | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Selectors)
- [Simple Selectors | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Simple_selectors)
- [Combinators & Multiple selectors | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Combinators_and_multiple_selectors)
- [Attribute Selectors | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Attribute_selectors)
- [Pseudo-class and Pseudo-element Selectors | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Pseudo-classes_and_pseudo-elements)

---

### CSS Units & Values

#### 📖 Contents

- Thers is 4 types of values in css

  - Colors.
  - Length, sizes and numbers.
  - Pre-Defined Options.
  - Functions.

- How CSS values are processed.

  - [Initial value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/initial_value)
  - [Resolved value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/resolved_value)
  - [Specified value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/specified_value)
  - [Computed value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/computed_value)
  - [Used value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/used_value)
  - [Actual value | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/actual_value)

#### 📚 References, Resources & Guids

- CSS Colors and Gradients

  - [Color | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
  - [A Nerd’s Guide to Color on the Web | CSS Tricks](https://css-tricks.com/nerds-guide-color-web/)
  - [CSS Gradients Guides | CSS Tricks](https://css-tricks.com/guides/css-gradients/)

- CSS Variables

  - [Learn CSS Variables Course | Scrimba](https://scrimba.com/g/gcssvariables)
  - [Everything you need to know about CSS Variables | Freecodecamp](https://medium.freecodecamp.org/everything-you-need-to-know-about-css-variables-c74d922ea855)

---

### Styling Content

Once you have the ability to target html elements, styling target html element ( the content ) of your page is the next big core conecpt to master.
Styling Content involves manipulating how elements should look like, What `font-size` , `color`, `background`, `border` ...etc.

#### 📖 Contents

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
- Links
- Media ( Image, Video and Audio )
- Tables
- Forms
- Buttons
- CSS Box Model
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

#### 📚 References, Resources & Guids

- [A Complete Guide to the Table Element | CSS Tricks](https://css-tricks.com/complete-guide-table-element/)
- [Styling Links | MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links)

---

### CSS Layout

Once you have the ability to target html elements for styling, layout is the next core concept to master.
Layout involves manipulating how elements lay out on the page, How much space do they take?, Are they side by side or on top of each other?, ...etc.

#### 📖 Contents

- Normal flow
- The display property
  - Block
  - Inline
  - Inline-Block
  - Flexbox
  - Grid
  - Table
- Floats
- Positioning
  - Default ( no property specified or Static )
  - Relative
  - Absoulte
  - Fixed
  - Sticky
  - Stacking Content ( Z-Index property )
- Multiple-column layout

#### 📚 References, Resources & Guids

- [Learn CSS Layout](http://learnlayout.com/)
- [Building layouts with flexbox and CSS grids](https://www.youtube.com/watch?v=2GxAElWKaAo)
- [Centering in CSS: A Complete Guide | CSS Tricks](https://css-tricks.com/centering-css-complete-guide/)

- Flexbox

  - [CSS flexbox Course](https://flexbox.io/) - by WesBos
  - [Flexbox Complete Guide | CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [The Complete Illustrated Flexbox Tutorial | Freecodecamp](https://medium.freecodecamp.org/the-complete-illustrated-flexbox-tutorial-d35c085dbf35)
  - [The Ultimate Guide to Flexbox  | Freecodecamp](https://medium.freecodecamp.org/the-ultimate-guide-to-flexbox-learning-through-examples-8c90248d4676)
  - [Understanding Flexbox: Everything you need to know | Freecodecamp](https://medium.freecodecamp.org/understanding-flexbox-everything-you-need-to-know-b4013d4dc9af)

- Grid

  - [CSS Grid Course](https://cssgrid.io/) - by WesBos
  - [CSS Grid Complete Guide | CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
  - [CSS Grid — The Beginner’s Guide | Freecodecamp](https://medium.freecodecamp.org/css-grid-the-beginners-guide-45998e6f6b8)
  - [How to create an image gallery with CSS Grid | Freecodecamp](https://medium.freecodecamp.org/how-to-create-an-image-gallery-with-css-grid-e0f0fd666a5c)

- Floats

  - [All About Floats | CSS Tricks](https://css-tricks.com/all-about-floats/)
  - [CSS Floats Explained](https://www.youtube.com/watch?v=609adV3pTME) - by DevTips on Youtube.
  - [CSS Floats and Clears Explained](https://www.youtube.com/watch?v=xFGBNv2KeVU) - by DevTips on Youtube.

- Positioning

  - [CSS Positioning - part1](https://www.youtube.com/watch?v=kejG8G0dr5U) - by DevTips on Youtube.
  - [CSS Positioning - part2](https://www.youtube.com/watch?v=Rf6zAP4YnZA) - by DevTips on Youtube.

- Multiple-column layout

  - [When And How To Use CSS Multi-Column Layout | Smashing Magazine](https://www.smashingmagazine.com/2019/01/css-multiple-column-layout-multicol/)

---

### CSS Specificity

Once you've started to become comfortable with the basics of CSS - using it to change the layout and graphical features of your page, it is time to learn how to use it well. Once of the most important concepts to master as you start to dig into more advanced concepts is specificity - how the browser decides what styles to apply where. This will be key in understanding why and how different CSS naming systems and architectures are designed the way they are.

#### 📖 Contents

#### 📚 References, Resources & Guids

- [Cascading and Inheritance](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Cascade_and_inheritance)
- [inheritance](https://developer.mozilla.org/en-US/docs/Web/CSS/inheritance)
- [Debugging CSS Code](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Debugging_CSS)

---

### Responsive Web Design

Responsive design is the practice of designing a website so it looks and works properly on a range of different devices — particularly mobile phones and tablets as well as desktops and laptops.

#### 📖 Contents

- Media Queries
- Common Responsive Patterns
  - Mostly Fluid
  - Column Drop
  - Layout Shifter
  - Off Canvas
- Responsive Images
- Which Method Should You Use for Your Responsive Layout?
  - Mobile-First
  - Desktop-First

#### 📚 References, Resources & Guids

- [Responsive Web Design Fundamentals](https://udacity.com/course/responsive-web-design-fundamentals--ud893)
- [Responsive Images](https://udacity.com/course/responsive-images--ud882)

---

### CSS Animations and Drawing

#### 📖 Contents

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

- CSS Shapes

  - Introducing CSS Shapes
  - CSS Shapes: the inset() function
  - CSS Shapes: The circle() Function
  - CSS Shapes: The ellipse() Function
  - CSS Shapes: The polygon() function
  - CSS Shapes: Shapes from the Alpha Channel
  - CSS Shapes: Shapes from the Reference Box

#### 📚 References, Resources & Guids

- [CSS Animation Performance](https://www.html5rocks.com/en/tutorials/speed/high-performance-animations/)

---

### CSS Preprocessors

The use of CSS preprocessors has become so important especially when you start working on large project.
Learn about the most famous and common used preprocessor ( SASS ), Why i use it?, How to use it? and How to writing maintainable and scalable Sass.

#### 📖 Contents

- Common Preprocessors
  - SASS
  - LESS
  - Stylus
  - PostCSS

#### 📚 References, Resources & Guids

- [Learn Sass In 15 Minutes | Tutorialzine](https://tutorialzine.com/2016/01/learn-sass-in-15-minutes)
- [SASS Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iEwigam3gTjU_7IA3W2WZA) - by The Net Ninja on Youtube.
- [Sass Workflow & Dev Server From Scratch Using Gulp](https://www.youtube.com/watch?v=rmXVmfx3rNo) - by Traversy Media on Youtube.
- [Sass Guidelines](https://sass-guidelin.es/)
- [How to structure a Sass project](http://thesassway.com/beginner/how-to-structure-a-sass-project)
- [PostCSS – A Comprehensive Introduction | Smashing Magazine](https://www.smashingmagazine.com/2015/12/introduction-to-postcss/)

---

### CSS Architecture

If you're not careful, it is easy to write complex, confusing, and unmaintable CSS.

#### 📖 Contents

- Common naming conventions
  - [BEM](http://getbem.com/)
  - [OOCSS](http://oocss.org/)
  - [SMACSS](https://smacss.com/)
  - [SUITCSS](https://suitcss.github.io/)
  - [Atomic](https://acss.io/)

#### 📚 References, Resources & Guids

- [BEM For Beginners: Why You Need BEM | Smashing Magazine](https://www.smashingmagazine.com/2018/06/bem-for-beginners/)

---

### CSS Frameworks

In this area you can pick up any framework you want, but i will list here the most famous one.

#### 📖 Contents

- Bootstrap
- Bulma
- Tailwind CSS

#### 📚 References, Resources & Guids

- [Bootstrap](https://getbootstrap.com/)

  - [Learn Bootstrap 4 Course | Scrimba](https://scrimba.com/g/gbootstrap4)
  - [Bootstrap 4: Everything You Need to Know | Freecodecamp](https://medium.freecodecamp.org/bootstrap-4-everything-you-need-to-know-c750991f6784)
  - [Bootstrap Framework — Best Practices](https://hackernoon.com/bootstrap-framework-best-practises-b1d81c02d6cf)

- [Bulma](https://bulma.io/)

  - [learn Bulma Course | Scrimba](https://scrimba.com/g/gbulma)
  - [Bulma Crash Course](https://www.youtube.com/watch?v=IiPQYQT2-wg&index=23&list=PLillGF-RfqbZTASqIqdvm1R5mLrQq79CU) - by Traversy Media on Youtube.

- [Tailwind CSS](https://tailwindcss.com/docs/what-is-tailwind/)
  - [Vanilla CSS vs Bootstrap vs Tailwind CSS - Which one should you choose?](https://www.youtube.com/watch?v=vmXIGdP8KN8)
  - [Introduction to Tailwind CSS](https://www.youtube.com/playlist?list=PLylMDDjFIp1Dt5hWKHPIHtdF2GFAS8Ak9)
  - [Tailwind CSS](https://www.youtube.com/playlist?list=PLEhEHUEU3x5p8cxOJ27w20LffCknp935L)
