# Layout

**Building Blocks**

CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level
box or an inline box.
Examples include:
< h1 > < p > < ul > < li >

Inline elements: Examples include:
< img > < b > < i >

**Containing Elements**

If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.

### Normal Flow

- **position:static** : In normal flow, each block-level 
element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow

![f](https://cdn.educba.com/academy/wp-content/uploads/2019/12/CSS-Position.jpg)

 - **position:absolute** :When the position property 
is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.)

![v](https://pbs.twimg.com/media/DSpo9RJU0AARkEw.jpg)

- **position:fixed** :Fixed positioning is a type 
of absolute positioning that requires the position property to have a value of fixed.It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect.

### Floating Elements

***float*** : The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.Anything else that sits inside the containing element will flow around the element that is floated.

![v](https://miro.medium.com/max/840/1*CFwJ6lMQMOi4Oy7L8Mn17g.png)

**Clearing Floats**

The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box.

**Page Sizes**

Because screen sizes and display resolutions vary so much, web 
designers often try to create pages of around 960-1000 pixels wide 
(since most users will be able to see designs this wide on their screens).



### Fixed Width Layouts
Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. measurements tendto be given in pixels.
![v](sizze.PNG)