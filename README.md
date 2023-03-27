# Important Points about CSS

* Img and span tags are inline container.

* There are generally two types of animation in CSS <br>
1. Use the transition property and change the properties that you want to animate on an event like when we hover the element
2. Use key frames at-rule

* In transform : translate () <br>
Positive value means - it goes to right <br>
Neg value means - it goes to left

* For animation to work there are 2 prop that we have to really specify which are called animation name and anmiation duration.

* To centre block element use  <br>
margin: 0 auto;

* Emmet is an extension which allows us to write html code faster.

* display: inline-block. This will contain space only that text not full

* <b>Put the gradient into text :- </b> <br>
-webkit-background-clip : text; <br>
color : transparent;

* If there are more than one photos and we want them together then use positive absolute

* Using z-index we can specify the stack order of an element

* <b>When we want to show img in the entire page :- </b> <br>
background-size : cover ;

* Perspective property is used to give 3d positioned element some perspective.

* backface-visibility : hidden; &nbsp; Hides the back part of an element

* <b>Used to apply gradient on picture :-</b> <br>
background-blend-mode : screen 

* object-fit : cover; The element will fill the entire parent while still maintaining its aspect ratio

* .row:last-child() select the last child but .row:not(:last-child) select everything except last child

* If there are 2 radio buttons and we want one of them is selected then other one is not. For this, give the same name of both radio buttons

* <b>For removing the bottom line from links :- </b> text-decoration: none; 

* In html we have figure tag where we can put an img and then some caption with a figcaption element.

* If we want that paragraph to be in two columns then use <br>
column-count : 2; <br>
And for gap in columns then use <br>
column-gap <br>
And for the border between both columns use <br>
column-rule : 1px solid color <br>

* <b> CSS Rule </b>
<img src = '/ImagesReadme/CSSRule.jfif' alt = 'CSS Rule'>

* <b> What happens To CSS when we Load Up a Web Page ? </b>
<img src = '/ImagesReadme/LoadWebPage.png' alt = 'What happens To CSS when we Load Up a Web Page'>

* <b>What is Cascade ?</b> <br>
Process of combining different stylesheets and resolving conflicts between different CSS rules and declarations, when more than one rule applies to certain elements. 

* <b>What  are <b>em</b> and <b>rem</b> and why we use them?</b> <br>
em is a CSS unit relative to font size of the parent element, while rem is a CSS unit relative to font size of html element. Both are scalable units, meaning they gives us the ability to scale elements up and down, relative to a set value. The difference between them is that em use the parent or current element as a reference while rems use the root font-size as the reference. rems aren't supported below Internet Explorer 9. 

* Inline styles have highest specificity followed by IDs then classes, pseudo classes and attributes selector and least specific the element and pseudo element selector

* Way to convert code into BEM. -> element__element , element--modifier
```
<header class="header"> 
        <div class="header__logo-box"> //element__element 
<h1 class="heading-primary">
        <span class="heading-primary--main"> //element--modifier
```

* <b>Cascade and Specificity : WHAT YOU NEED TO KNOW</b><br>
⁕ CSS declaration marked with <b>!important</b> have highest priority. <br>
⁕ Inline styles will always have priority over styles in external stylesheets. <br>
⁕ A selector that contains 1 ID is more specific than one with 1000 classes. <br>
⁕ A selector that contains 1 class is more specific than one with 1000 elements. <br>
⁕ The universal selector * has no specific value (0,0,0,0). 

* What is specificity in css ? <br>
Specificity is an algorithm that calculates the weight that is applied to a given CSS declaration. The weight is determined by the number of selectors of each weight category in the selector matching the element (or pseudo-element).
<img src = '/ImagesReadme/Specificity.png' alt = 'Specificity'>
<img src = '/ImagesReadme/Parsed_CSS.png' alt = 'Parsed_CSS'>

* <b>Use of !important -</b>
<img src = '/ImagesReadme/Not_!imp.png' alt = 'Not_!important'>
<img src = '/ImagesReadme/!imp.png' alt = '!important'>

* <b>How CSS values are Processed ?</b> 
<img src = '/ImagesReadme/CSS Value1.png' alt = 'CSS values are Processed'>
<img src = '/ImagesReadme/CSS Value2.png' alt = 'CSS values are Processed'>
<img src = '/ImagesReadme/CSS Value3.png' alt = 'CSS values are Processed'>

* <b>How Units are converted from relative to absolute (Px) :</b>
<img src = '/ImagesReadme/Units To Px.png' alt = 'CSS values are Processed'>

* <b>CSS Value Processing : WHAT YOU NEED TO KNOW</b><br>
⁕ Each property has an initial value, used if nothing is declared (and if there is no inheritance). <br>
⁕ Browsers specify a <b>root font-size</b> for each page (usually 16px).<br>
⁕ Percentages and relative values are always converted to pixels.<br>
⁕ vh and vw are simply percentage measurements of the viewport's height and width.<br>
⁕ rem are always measured relative to the <b>document's root</b> font-size.<br>
⁕ em are measured relative to the current font-size, if used to specify lengths.<br>
⁕ em are measured relative to their parent font-size, if used to specify font-size.<br>
⁕ Percentages are measured relative to their parent's width, if used to specify lengths.<br>
⁕ Percentages are measured relative to their parent's font-size, if used to specify font-size.<br>

* Inheritence - 
<img src = '/ImagesReadme/Inheritence.png' alt = 'Inheritence'>

* <b>Inheritence : WHAT YOU NEED TO KNOW</b><br>
⁕ Inheritance passes the values for some specific properties from parents to children - more maintainable code.<br>
⁕ Inheritance of a property only works if no one declares a value for that property.<br>
⁕ The computed value of a property is what gets inherited, not the declared value.<br>
⁕ The inherit keyword forces inheritance on a certain property.<br>
⁕ The initial keyword resets a property to its initial value.<br>
⁕ Properties related to text are inherited: font-family, font-size, color, etc.<br>

* <b>What is VISUAL FORMATTING MODEL ? </b> <br>
Algorithm that calculates boxes and determines the layout of these boxes, for each element in the render tree, in order to determine the final layout of the page. 
<img src = '/ImagesReadme/VFM.png' alt = 'VISUAL FORMATTING MODEL'>
<img src = '/ImagesReadme/BoxModel.png' alt = 'Box Model'>
<img src = '/ImagesReadme/BoxModel2.png' alt = 'Box Model'>
<img src = '/ImagesReadme/BoxType.png' alt = 'Box Type'>
<img src = '/ImagesReadme/BoxType.png' alt = 'Box Type'>
<img src = '/ImagesReadme/BoxType2.png' alt = 'Box Type'>
<img src = '/ImagesReadme/BoxType2.png' alt = 'Box Type'>
<img src = '/ImagesReadme/PS.png' alt = 'Positining Scheme'>
<img src = '/ImagesReadme/Stacking Context.png' alt = 'Stacking Context'>
<img src = '/ImagesReadme/Stacking Context.png' alt = 'Stacking Context'>

# SASS 
* SASS is a CSS preprocessor, an extension of CSS that add power and elegance to the basic language.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sass Compiler <br>
&nbsp;&nbsp;&nbsp; SASS SOURCE CODE ---------------------> COMPILED CSS CODE <br>

### Mixin ->
A mixin is just a reusable piece of code that we write into a mixin. Whenever we use mixin that code is put in the place where we used or where we called that mixin. Mixin is used where code is repeated. we can pass an argument in mixin; if we want.
@mixin name(argument)
```
ex- nav {
    color: pink;
    padding: 8px; 
    height: 16vh;
}
a {
   color: pink;
    padding: 8px; 
    height: 16vh;
}
nav and a both have the same thing. Here we can use mixin.

@mixin qualities {
    color: pink;
    padding: 8px; 
    height: 16vh;
}

now use this -
nav {
   @include qualities;
}
a {
   @include qualities;
}
```

### FUNCTION ->
Functions allow you to define complex operations on SassScript values that you can re-use throughout your stylesheet. They make it easy to abstract out common formulas and behaviors in a readable way.
```
@function divide($a, $b){
  @return $a/$b;
}
```

### PLACEHOLDER ->
SASS supports placeholder selector using class or id selector. In normal CSS, these are specified with "#" or ".", but in SASS they are replaced with "%". To work with placeholder selector, they can be used with @extend directive. Without using @extend directive, you cannot display the result in CSS.

### What is the difference between mixin and extend in Sass?
@mixin is used to group css code that has to be reused a no of times. Whereas the @extend is used in SASS to inherit(share) the properties from another css selector.

### 7-1 SASS Architecture
7-1 SASS Pattern means 7 Folders and 1 FIle. 7 Folders have their meaningful labels which include sass snippets or partials. Outside the 7 folders, 1 file will include all the partials or snippets from 7 folders and compile it to 1 CSS file.

### Main SASS Features
<img src = '/ImagesReadme/Features.png' alt = 'SASS Features'>

### SASS and SCSS 
<img src = '/ImagesReadme/Difference.png' alt = 'SASS Vs SCSS '>

### Basic Responsive Design Principles
<img src = '/ImagesReadme/ResponsiveDesign.jpg' alt = 'Basic Responsive Design Principles'>

### Responsive Design Strategy
<img src = '/ImagesReadme/RDS.png' alt = 'Responsive Design Strategy'>
<img src = '/ImagesReadme/Max-Min.png' alt = 'Max and Min'>

### Types of Layouts
<img src = '/ImagesReadme/Layout.png' alt = 'Types of Layouts'>

### Grid System
A grid is just a design system which allows us to build consistent interfaces. 

### Is Mobile-First Right ?
<img src = '/ImagesReadme/Mobile-First.png' alt = 'Mobile-First'>

* <b>If we want to use css with sass variable use # like this #{$variable_name}</b>

* <b>CLEARFIX :- </b> Clearfix append a pseudo element after the element which will clear these floats.

### BackDrop-Filter
The backdrop-filter property is used to apply a graphical effect to the area behind an element.<br>
<b>Syntax :- </b> backdrop-filter : blur(1px);

### Selecting Breakpoints 
<img src = '/ImagesReadme/Breakpoints.png' alt = 'Breakpoints'>

### What are Responsive Image ?
<img src = '/ImagesReadme/ResponsiveImage.png' alt = 'Responsive Image'>

### When to use Responsive Image : The 3 Use Cases
<img src = '/ImagesReadme/UseCase.png' alt = 'Responsive Image'>