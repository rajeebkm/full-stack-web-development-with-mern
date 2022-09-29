# full-stack-web-development-with-mern

## Interoduction

What is Internet ?

TCP : Transmission Control Protocol
IP: Internet Protocol

HTML, CSS, JavaScript

Code editor: Atom, VS code, Notepad etc.

Installation (Atom): https://atom.io/

### Links

HTML File:

https://github.com/OakAcademy/HTML-For-Everyone-Real-World-Coding-in-HTML

HTML, CSS and Web Design file:

https://github.com/OakAcademy/HTML-CSS-Code-and-Design-Websites-With-HTML-and-CSS

JavaScript file:

https://github.com/OakAcademy/JavaScript-Beginner

React JS project files:

https://github.com/OakAcademy/react-router/tree/master/react-router

https://github.com/OakAcademy/blog-posts

https://github.com/OakAcademy/hemisphere

https://github.com/OakAcademy/first-app

https://github.com/OakAcademy/image-list

https://github.com/OakAcademy/contextapi

https://github.com/OakAcademy/hooks-project

https://github.com/OakAcademy/Full-Stack-React-Js-with-Redux-Node.Js-Express.Js-MongoDB/tree/main

NodeJS Project files:

https://github.com/OakAcademy/Node-JS

MongoDB Project Files:

https://github.com/OakAcademy/MongoDB

Graphql Project Files:

https://github.com/OakAcademy/graphql

Mern stack project file:

https://github.com/OakAcademy/Mern-Stack-Project

### HTML


HTML File:

https://github.com/OakAcademy/HTML-For-Everyone-Real-World-Coding-in-HTML

#### HTML Basic Tags

HTML element: (<openingTag>Content<closingTag>)
<tagName>content</tagName>

Examples:

<html> </html>, <head>, <title>, <body>, <h1> to <h6>, <br>, <p>, <strong> <b>, <em> <i>, <u>

HTML Headings:
-------------
```<h1>Project</h1>```

HTML Images:
-----------
Image website: https://www.freepik.com/
```<img src="images/1.jpg" alt="horse" title="Horse Racing" height="50%" width="50%">```

HTML Lists:
-----------
* Unordered Lists   
* Ordered Lists
* Description Lists

### CSS

#### CSS Basics

There are 3 types of CSS so there are 3 ways to include CSS in the document –

-- Inline CSS
-- Internal or Embedded CSS
-- External CSS

Out of these, the best way to include CSS is through External CSS but depending upon the requirement, you can also use Inline CSS and Internal CSS

Inline CSS
-----------

Syntax of Inline CSS:

```<elementName style=attr1:val1;attr2:val2;…..;attr-n:val-n>Details</elementName>
```

``` <tag style={property: value; }> Contents </tag>```

``` <h1 style={color: red;}>This is Heading</h1> ```

``` <p style="background-color:SlateBlue;padding:10px">This paragraph uses Inline CSS</p> ```


Internal or Embedded CSS
------------------------
```
<head>
<style>
  elementA {
    attra1:vala1;
    attra2:vala2;
    ..;
    attr-an:val-an
}
  ..
  elementN {
    attrn1:valn1;
    attrn2:valn2;
    ..;
    attr-nn:val-nn
}

```
.h4class {
  background-color:#ffa500;
}
.square {
  list-style-type: square;
} 
```
</style>
```

External CSS
-------------
```
Selector {
    property: value;
}

Selector {
    property: value;
    Another property: value;
    .
    .
    .
    Another property: value;
}
```

Example:

STEP 1- Create an External CSS file with .CSS extention. For example - Suppose, we have an external CSS file with any valid name like style.css whose content is as below -

```
h1  {
  background-color:#ff6347;
  color: blue;
}

h5 {
  color: Tomato;
}

p  {
text-align: center;
}
```

```
.h4class {
  background-color:#ffa500;
}
.square {
  list-style-type: square;
} 
```

STEP 2- Then, you can place this file either at the same location in which your HTML file is present or you can place this inside some other folder like 'CSS' folder.

In Case, you place your CSS file in the same location where you kept your HTML file then the syntax to include the CSS file is -
```
<ink rel="styesheet" type="text/css" href="style.css">
```
You should include this CSS file under the <head> section as below -

```
<head>
<link rel="stylesheet" type="text/css" href="style.css">
</head>
```
Correct way to include External CSS
Suppose, your CSS file name extstyle.css and it is present inside a folder, say cssext, then you should provide the path of your CSS file like below -
```
<head>
<link rel="stylesheet" type="text/css" href="cssext/extstyle.css">
</head>
```

Which has higher priority - Inline CSS or Internal CSS
If both Inline CSS and Internal CSS are specifies for an element, then Inline CSS takes higher priority and it will override the style of Internal CSS.

So, Inline CSS has higher priority than Internal CSS.

#### CSS Colors

https://www.w3schools.com/css/css_colors.asp
https://www.w3schools.com/colors/colors_names.asp
https://www.w3schools.com/colors/colors_picker.asp

Base (primary) colors: Red(255-0-0), Green(0-255-0) and Blue(0-0-255)
Intermediate (secondary) colors: By mixing primary colors. (Yellow (R-G), Cyan(G-B), Magenta(B-R)), white (combination of R-G-B)

Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.
All modern browsers support the following 140 color names.

Decimal: (0,1,2..............9..........99)
Hexadecimal: (0,1,2..........9,A,B,C,D,E,F...........FF)

Red: #FF0000
Green: #00FF00
Blue: #0000FF
White: #FFFFFF

Hexadecimal: #FF0000 (Red), #FFFFFF-White, #000000-Black
RGB model: rgb(255,0,0) (Red), rgb(255,255,255)-White, rgb(0,0,0)-Black
HSL model: hsl(0,100%,50%), hsl(360,100%,50%)-(Red), hsl(0, 0%, 0%)-(Black), hsl(0, 100%, 100%)-(White)

#### CSS Background and Border

```
h1{
  background: rgb(255,80,80);
  /* border-color:blue;
  border-width: 5px;
  border-style: solid; */

  /* border:5px solid blue; */

  border:2px dashed blue;
}

body{
  background: green;
}

body{
  background: url(https://img.freepik.com/free-vector/underwater-background-water-surface-ocean-sea_33099-1755.jpg?size=626&ext=jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
```

#### CSS Selector

The id and class are two selectors in CSS that allows applying styling to the HTML elements. The main difference between id and class in CSS is that id is used to apply styling to one unique element while class is used to apply styling to multiple elements.

.html
-----
```
  <body>
    <ul>
      <li id="select">The Great Barier Reef</li>
      <li class="underline"> Pyramids of Giza </li>
      <li class="underline">Stonehenge</li>
    </ul>
  </body>
  ```
.css
----
```
li{
  border:4px solid blue;
}

#select{
  background: red;
}

.underline{
  text-decoration: underline;
}
```
All CSS Simple Selectors
------------------------
```
Selector	         Example                Example description
------------------------------------------------------------------
#id	               #firstname	     Selects the element with id="firstname"
.class	            .intro	         Selects all elements with class="intro"
element.class	   p.intro	         Selects only <p> elements with class="intro"
*	                 *	             Selects all elements
element	              p	             Selects all <p> elements
element,element,..	div, p	         Selects all <div> elements and all <p> elements
element element     div p            Select and style every <p> element that is inside <div> elements:
```
Adjacent Sibling Selector
---------------------------

The + selector is used to select an element that is directly after another specific element.

```
<style>
div + p {
  background-color: yellow;
}
</style>
```
```
<div>
  <p>Paragraph 1 in the div.</p>
  <p>Paragraph 2 in the div.</p>
</div>

<p>Paragraph 3. After a div.</p>
<p>Paragraph 4. After a div.</p>

```
Result: ```Paragraph 3. After a div.``` will be yellowed.


#### CSS Texts and Fonts

https://www.w3schools.com/css/css_font.asp

https://www.cssfontstack.com/

#### Debugging in CSS

First Method: Checl the console in the web-browser,if there is any error.
Second Method: Check priority ranking (inline>internal>external)

#### CSS Box Model

https://www.w3schools.com/css/css_boxmodel.asp

In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:

Explanation of the different parts:

Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent

Example
Demonstration of the box model:
```
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```
Width and Height of an Element
In order to set the width and height of an element correctly in all browsers, you need to know how the box model works.

Important: When you set the width and height properties of an element with CSS, you just set the width and height of the content area. To calculate the full size of an element, you must also add padding, borders and margins.

Example
This <div> element will have a total width of 350px: 

```
div {
  width: 320px;
  padding: 10px;
  border: 5px solid gray;
  margin: 0;
}
```
Here is the calculation:
```
320px (width)
+ 20px (left + right padding)
+ 10px (left + right border)
+ 0px (left + right margin)
= 350px
```
The total width of an element should be calculated like this:

```
Total element width = width + left padding + right padding + left border + right border + left margin + right margin
```

The total height of an element should be calculated like this:
```
Total element height = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin
```
#### CSS Position

https://www.w3schools.com/css/css_positioning.asp

The position property specifies the type of positioning method used for an element (static, relative, fixed, absolute or sticky).

The position Property
The position property specifies the type of positioning method used for an element.

There are five different position values:

static
relative
fixed
absolute
sticky

Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the position property is set first. They also work differently depending on the position value.

position: static
-----------------
HTML elements are positioned static by default.

Static positioned elements are not affected by the top, bottom, left, and right properties.

An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:


Here is the CSS that is used:

```
div.static {
  position: static;
  border: 3px solid #73AD21;
}
```
position: relative
-------------------
An element with position: relative; is positioned relative to its normal position. relative property is positioned according to its previous location.

Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.


Here is the CSS that is used:
```
div.relative {
  position: relative;
  left: 30px;
  border: 3px solid #73AD21;
}
```

position: fixed
----------------
An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.

A fixed element does not leave a gap in the page where it would normally have been located.

Notice the fixed element in the lower-right corner of the page. Here is the CSS that is used:

```
div.fixed {
  position: fixed;
  bottom: 0;
  right: 0;
  width: 300px;
  border: 3px solid #73AD21;
}
```

position: absolute
-------------------
An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

Note: Absolute positioned elements are removed from the normal flow, and can overlap elements.
absolute property affects other element.


```
div.relative {
  position: relative;
  width: 400px;
  height: 200px;
  border: 3px solid #73AD21;
}

div.absolute {
  position: absolute;
  top: 80px;
  right: 0;
  width: 200px;
  height: 100px;
  border: 3px solid #73AD21;
}
```

position: sticky
----------------
An element with position: sticky; is positioned based on the user's scroll position.

A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).

Note: Internet Explorer does not support sticky positioning. Safari requires a -webkit- prefix (see example below). You must also specify at least one of top, right, bottom or left for sticky positioning to work.

In this example, the sticky element sticks to the top of the page (top: 0), when you reach its scroll position.

```
div.sticky {
  position: -webkit-sticky; /* Safari */
  position: sticky;
  top: 0;
  background-color: green;
  border: 2px solid #4CAF50;
}
``` 

#### CSS float

```
.blue{
  width: 100px;
  height: 100px;
  background-color: blue;
  float:left;
}

.yellow{
  width: 100px;
  height: 100px;
  background-color: yellow;
  float:left;
}

.green{
  width: 200px;
  height:200px;
  background-color: green;
  clear:both;
  <!-- clear: both (The clear property controls the flow next to floated elements. The clear property specifies what should happen with the element that is next to a floating element.) -->
  margin-left: 500px;
  box-shadow: -7px -6px 5px black;

  /* border-radius: 15px 20px 30px 40px; */

  border-radius: 40px;
  transform:rotate(60deg);

}
```

#### CSS Display property

```
h1{
  background-color: red;
  display: inline-block;
  width: 200px;
  height: 200px;
}

p{
  background-color: blue;
  display: inline;
}

span{
  background-color: gray;
  display: block;
  width: 100px;
  height: 100px;
}
```

#### CSS Box-Sizing

The CSS box-sizing property allows us to include the padding and border in an element's total width and height.

Without the CSS box-sizing Property
------------------------------------
By default, the width and height of an element is calculated like this:

width + padding + border = actual width of an element
height + padding + border = actual height of an element

With the CSS box-sizing Property
--------------------------------
The box-sizing property allows us to include the padding and border in an element's total width and height.

If you set box-sizing: border-box; on an element, padding and border are included in the width and height.

```
.box1{
  width: 150px;
  height: 150px;
  border:3px solid blue;
  padding: 10px;
  /* box-sizing: content-box; */
}
/* content-box (by default)
width=150 +3 +3=156px
height=150+3+3=156px */


.box2{
  width: 150px;
  height: 150px;
  border:3px solid red;
  padding: 10px;
  /* box-sizing: border-box; */
}


html{
  box-sizing: border-box;
}
  *{
  box-sizing: inherit;
}

```

#### CSS Media Queries

| Value         | Description                                           |
| ------------- | ----------------------------------------------------- |
| all           | Used for all media type devices                       |
| print         | Used for printers                                     |
| screen        | Used for computer screens, tablets, smart-phones etc  |
| speech        | Used for screenreaders that "reads" the page out loud |

```
  .container{
    width: 850px;
    border:3px solid blue;
    margin: auto;

  }

  h1{
    text-align: center;
  }

  .box{
    width: 250px;
    height: 250px;
    background-color: red;
    display: inline-block;
    margin: 10px;
    
  }

  @media screen and (min-width: 700px) and (max-width: 1020px)
  {
    .container{
      width: 850px;
      border:3px solid blue;
      margin: auto;
  
    }
  
    h1{
      text-align: center;
    }
  
    .box{
      width: 250px;
      height: 250px;
      background-color: yellow;
      display: inline-block;
      margin: 10px;
      
    }
  }

```

#### CSS Flexbox

Before the Flexbox Layout module, there were four layout modes:

```
Block, for sections in a webpage
Inline, for text
Table, for two-dimensional table data
Positioned, for explicit position of an element
```

The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.

Flexbox Elements
----------------
To start using the Flexbox model, you need to first define a flex container.

A flex container with three flex items:

```
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
##### CSS Flex Container
------------------
Parent Element (Container)
Like we specified in the previous chapter, this is a flex container (the blue area) with three flex items:

The flex container becomes flexible by setting the display property to flex:

```
.flex-container {
  display: flex;
}
```

The flex container properties are:

flex-direction
flex-wrap
flex-flow
justify-content
align-items
align-content

The flex-direction Property
----------------------------
The flex-direction property defines in which direction the container wants to stack the flex items.
The column value stacks the flex items vertically (from top to bottom):
```
.flex-container {
  display: flex;
  flex-direction: column;
}
```
The column-reverse value stacks the flex items vertically (but from bottom to top):

```
.flex-container {
  display: flex;
  flex-direction: column-reverse;
}
```
The row value stacks the flex items horizontally (from left to right):

```
.flex-container {
  display: flex;
  flex-direction: row;
}
```
The row-reverse value stacks the flex items horizontally (but from right to left):
```
.flex-container {
  display: flex;
  flex-direction: row-reverse;
}
```

The flex-wrap Property
-----------------------
The flex-wrap property specifies whether the flex items should wrap or not.

The examples below have 12 flex items, to better demonstrate the flex-wrap property.
The wrap value specifies that the flex items will wrap if necessary:
```
.flex-container {
  display: flex;
  flex-wrap: wrap;
}
```
The nowrap value specifies that the flex items will not wrap (this is default):
```
.flex-container {
  display: flex;
  flex-wrap: nowrap;
}
```
The wrap-reverse value specifies that the flexible items will wrap if necessary, in reverse order:
```
.flex-container {
  display: flex;
  flex-wrap: wrap-reverse;
}
```
The flex-flow Property
-----------------------
The flex-flow property is a shorthand property for setting both the flex-direction and flex-wrap properties.

Example
```
.flex-container {
  display: flex;
  flex-flow: row wrap;
}
```
The justify-content Property
------------------------------
The justify-content property is used to align the flex items:

Example
The center value aligns the flex items at the center of the container:

```
.flex-container {
  display: flex;
  justify-content: center;
}
```

Example
The flex-start value aligns the flex items at the beginning of the container (this is default):

```
.flex-container {
  display: flex;
  justify-content: flex-start;
}
```

The flex-end value aligns the flex items at the end of the container:
```
.flex-container {
  display: flex;
  justify-content: flex-end;
}
```
Example
The space-around value displays the flex items with space before, between, and after the lines:
```
.flex-container {
  display: flex;
  justify-content: space-around;
}
```

Example
The space-between value displays the flex items with space between the lines:
```
.flex-container {
  display: flex;
  justify-content: space-between;
}
```

The align-items Property
-------------------------
The align-items property is used to align the flex items

In these examples we use a 200 pixels high container, to better demonstrate the align-items property.

Example
The center value aligns the flex items in the middle of the container:
```
.flex-container {
  display: flex;
  height: 200px;
  align-items: center;
}
```

Example
The flex-start value aligns the flex items at the top of the container:
```
.flex-container {
  display: flex;
  height: 200px;
  align-items: flex-start;
}
```
Example
The flex-end value aligns the flex items at the bottom of the container:
```
.flex-container {
  display: flex;
  height: 200px;
  align-items: flex-end;
}
```
Example
The stretch value stretches the flex items to fill the container (this is default):
```
.flex-container {
  display: flex;
  height: 200px;
  align-items: stretch;
}
```
Example
The baseline value aligns the flex items such as their baselines aligns:
```
.flex-container {
  display: flex;
  height: 200px;
  align-items: baseline;
}
```
Note: the example uses different font-size to demonstrate that the items gets aligned by the text baseline:

The align-content Property
--------------------------
The align-content property is used to align the flex lines.

In these examples we use a 600 pixels high container, with the flex-wrap property set to wrap, to better demonstrate the align-content property.

Example
The space-between value displays the flex lines with equal space between them:
```
.flex-container {
  display: flex;
  height: 600px;
  flex-wrap: wrap;
  align-content: space-between;
}
```
The space-around value displays the flex lines with space before, between, and after them:
```
.flex-container {
  display: flex;
  height: 600px;
  flex-wrap: wrap;
  align-content: space-around;
}
```
Example
The stretch value stretches the flex lines to take up the remaining space (this is default):
```
.flex-container {
  display: flex;
  height: 600px;
  flex-wrap: wrap;
  align-content: stretch;
}
```

Example
The center value displays display the flex lines in the middle of the container:
```
.flex-container {
  display: flex;
  height: 600px;
  flex-wrap: wrap;
  align-content: center;
}
```

Example
The flex-start value displays the flex lines at the start of the container:
```
.flex-container {
  display: flex;
  height: 600px;
  flex-wrap: wrap;
  align-content: flex-start;
}
```

Example
The flex-end value displays the flex lines at the end of the container: 
```
.flex-container {
  display: flex;
  height: 600px;
  flex-wrap: wrap;
  align-content: flex-end;
}
```

Perfect Centering
-----------------
In the following example we will solve a very common style problem: perfect centering.

SOLUTION: Set both the justify-content and align-items properties to center, and the flex item will be perfectly centered:

Example
```
.flex-container {
  display: flex;
  height: 300px;
  justify-content: center;
  align-items: center;
}
```

The CSS Flexbox Container Properties
------------------------------------
The following table lists all the CSS Flexbox Container properties:

```
-- align-content: Modifies the behavior of the flex-wrap property. It is similar to align-items,    but instead of aligning flex items, it aligns flex lines.

-- align-items	Vertically aligns the flex items when the items do not use all available space on the cross-axis.

-- display	Specifies the type of box used for an HTML element.

-- flex-direction	Specifies the direction of the flexible items inside a flex container.

-- flex-flow	A shorthand property for flex-direction and flex-wrap.

-- flex-wrap	Specifies whether the flex items should wrap or not, if there is not enough room for them on one flex line.

-- justify-content	Horizontally aligns the flex items when the items do not use all available space on the main-axis.
```

##### CSS Flex Items
--------------

Child Elements (Items)
----------------------
The direct child elements of a flex container automatically becomes flexible (flex) items.

The element above represents four blue flex items inside a grey flex container.

Example
```
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>
  <div>4</div>
</div>
```
The flex item properties are:

-- order
-- flex-grow
-- flex-shrink
-- flex-basis
-- flex
-- align-self

The order Property
------------------
The order property specifies the order of the flex items.

The first flex item in the code does not have to appear as the first item in the layout.

The order value must be a number, default value is 0.

Example
The order property can change the order of the flex items:

```
<div class="flex-container">
  <div style="order: 3">1</div>
  <div style="order: 2">2</div>
  <div style="order: 4">3</div>
  <div style="order: 1">4</div>
</div>
```

The flex-grow Property
The flex-grow property specifies how much a flex item will grow relative to the rest of the flex items.

The value must be a number, default value is 0.

Example
Make the third flex item grow eight times faster than the other flex items:
```
<div class="flex-container">
  <div style="flex-grow: 1">1</div>
  <div style="flex-grow: 1">2</div>
  <div style="flex-grow: 8">3</div>
</div>
```

The flex-shrink Property
The flex-shrink property specifies how much a flex item will shrink relative to the rest of the flex items.

The value must be a number, default value is 1.

Example
Do not let the third flex item shrink as much as the other flex items:

```
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div style="flex-shrink: 0">3</div>
  <div>4</div>
  <div>5</div>
  <div>6</div>
  <div>7</div>
  <div>8</div>
  <div>9</div>
  <div>10</div>
</div>
```


The flex-basis Property
------------------------
The flex-basis property specifies the initial length of a flex item.

Example
Set the initial length of the third flex item to 200 pixels:
```
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div style="flex-basis: 200px">3</div>
  <div>4</div>
</div>
```

The flex Property
------------------
The flex property is a shorthand property for the flex-grow, flex-shrink, and flex-basis properties.

Example
Make the third flex item not growable (0), not shrinkable (0), and with an initial length of 200 pixels:
```
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div style="flex: 0 0 200px">3</div>
  <div>4</div>
</div>
```

The align-self Property
-----------------------
The align-self property specifies the alignment for the selected item inside the flexible container.

The align-self property overrides the default alignment set by the container's align-items property.

In these examples we use a 200 pixels high container, to better demonstrate the align-self property:

Example
Align the third flex item in the middle of the container:
```
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div style="align-self: center">3</div>
  <div>4</div>
</div>
```

Example
Align the second flex item at the top of the container, and the third flex item at the bottom of the container:
```
<div class="flex-container">
  <div>1</div>
  <div style="align-self: flex-start">2</div>
  <div style="align-self: flex-end">3</div>
  <div>4</div>
</div>
```

The CSS Flexbox Items Properties
--------------------------------
The following table lists all the CSS Flexbox Items properties:

-- align-self:	Specifies the alignment for a flex item (overrides the flex container's align-items property)
-- flex:	A shorthand property for the flex-grow, flex-shrink, and the flex-basis properties
-- flex-basis:	Specifies the initial length of a flex item
-- flex-grow:	Specifies how much a flex item will grow relative to the rest of the flex items inside the same container
-- flex-shrink:	Specifies how much a flex item will shrink relative to the rest of the flex items inside the same container
-- order:	Specifies the order of the flex items inside the same container

##### CSS Flex Responsive

Responsive Flexbox

You learned from the CSS Media Queries chapter that you can use media queries to create different layouts for different screen sizes and devices.

For example, if you want to create a two-column layout for most screen sizes, and a one-column layout for small screen sizes (such as phones and tablets), you can change the flex-direction from row to column at a specific breakpoint (800px in the example below):

```
.flex-container {
  display: flex;
  flex-direction: row;
}

/* Responsive layout - makes a one column layout instead of a two-column layout */
@media (max-width: 800px) {
  .flex-container {
    flex-direction: column;
  }
}
```

Another way is to change the percentage of the flex property of the flex items to create different layouts for different screen sizes. Note that we also have to include flex-wrap: wrap; on the flex container for this example to work

Example
```
.flex-container {
  display: flex;
  flex-wrap: wrap;
}

.flex-item-left {
  flex: 50%;
}

.flex-item-right {
  flex: 50%;
}

/* Responsive layout - makes a one column layout instead of a two-column layout */
@media (max-width: 800px) {
  .flex-item-right, .flex-item-left {
    flex: 100%;
  }
}
```

#### CSS Grid

https://www.w3schools.com/css/css_grid.asp