# CSS Layout

## In this Article

[Key Concepts](#topic1)

[Screen Sizes](#topic2)

[Topic 3](#topic3)

---

<a name="topic1"></a>

## Key Concepts

**Boxes** are the fundamental building blocks when HTML is passed to our CSS. **Block Level** elements refer to elements that will be displayed as a new "block" by CSS.  **In-line** elements, on the other hand, are displayed in-line with the text of the web page.

Block elements can sit inside one another.  The outer, or parent, element is said to "contain" the inner block.  If a styling is applied to the outer element, it will also apply to it's contained elements.  This styling can be overridden however, with CSS specificity using class, ID's, or other CSS techniques.

**Positioning** can be changed using CSS as well.  When we talk about **normal flow** of the page, we are reffering to how the page would be displayed "normally" without CSS manipulation. **Absolute** positioning takes elements out of normal flow and positions them in relation to their containing element. **Floating** can be used to have text or content wrap around a certain element.  An example would be to float a photo left or right so that the text of the page can wrap around the photo and be read in a logical manner. 
<a name="topic2"></a>

## Screen Sizes

Screens sizes and resolution will be a topic of concern if you plan to develop web pages.  The web is now viewed on mobile devices, laptops, tablets, and desktop computers. Because of these varying screen sizes, web designers will try to create pages that are 960-1000 pixels wide. Most screens will be able to display this size, and it sets a standard. 

### Fixed Width Layouts

**Fixed Width** layouts are just that, *fixed*.  They do not change in size with different screens. An advantage is that as a developer, you know the size of your page and how things will look in relation to one another.  The disadvantage is that your page can have huge gaps of space around it's edges if the user views it on a large enough screen with enough resolution. 

### Fluid Layouts

**Fluid Layouts** change size with the browser.  As a user makes the window larger or smaller, so too goes your webpage.  Care needs to be taken by the developer, however, as the widths of sections can become too large and distort the page!

<a name="topic3"></a>

## Grid Layout

CSS **frameworks** are tools used to help us with our CSS.  THe 960 grid system framework helps by creating a "grid" for our HTML page.  The grid is used to place items where we want them.  It also allows us to easily adjust how wide box should be.  The system uses class names on our HTML elements to apply CSS rules to them.  For example, a class of "grid_3" is a class that stretches the element across three columns of the grid. 

Grids also make it easy to set consistent proportions and relative sizes in our page.  The main content might take up two-thirds of the width of the page, leaving the last third available for our aside.  This not only looks pleasing but is easy to organize and build with the grid system.

~ QP3

[Home](../README.md)

Information put into my own words came from *HTML & CSS* by J Duckett
