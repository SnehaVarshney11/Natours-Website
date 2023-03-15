# Important Points about CSS

* Img and span tags are inline container.

* There are generally two types of animation in CSS <br>
1. Use the transition property and change the properties that you want to animate on an event like when we hover the element
2. Use key frames at-rule

* In transform : translate () <br>
Positive value means - it goes to right <br>
Neg value means - it goes to left

* For animation to work there are 2 prop that we have to really specify which are called animation name and anmiation duration.


* <b> CSS Rule </b>
<img src = '/ImagesReadme/CSSRule.jfif' alt = 'CSS Rule'>

* <b> What happens To CSS when we Load Up a Web Page ? </b>
<img src = '/ImagesReadme/LoadWebPage.png' alt = 'What happens To CSS when we Load Up a Web Page'>

* <b><ul> What is Cascade ? </ul></b> <br>
Process of combining different stylesheets and resolving conflicts between different CSS rules and declarations, when more than one rule applies to certain elements. 

* <b><ul> What  are <b>em</b> and <b>rem</b> and why we use them? </ul></b> <br>
em is a CSS unit relative to font size of the parent element, while rem is a CSS unit relative to font size of html element. Both are scalable units, meaning they gives us the ability to scale elements up and down, relative to a set value. The difference between them is that em use the parent or current element as a reference while rems use the root font-size as the reference. rems aren't supported below Internet Explorer 9. 

* Inline styles have highest specificity followed by IDs then classes, pseudo classes and attributes selector and least specific the element and pseudo element selector

* Way to convert code into BEM. -> element__element , element--modifier
```
<header class="header"> 
        <div class="header__logo-box"> //element__element 
<h1 class="heading-primary">
        <span class="heading-primary--main"> //element--modifier

