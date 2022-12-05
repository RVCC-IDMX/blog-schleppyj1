---
title: "Twist and Turn: An Introduction to 2D Translation Functions"
author: Jean Schleppy
description: In this article, I will go over some 2d translation functions in CSS.
date: 2022-12-05T03:58:38.433Z
tags:
  - post
image: /assets/blog/css-card-rotate.png
imageAlt: CSS featuring the rotate function.
---
## Introduction
Have you ever wondered how certain objects on a webpage are able to twist, turn or even grow? This document presents an introduction to CSS3’s 2D translation functions:  rotate, skew and translate.  The document begins with a definition of what the CSS3’s Translation Functions are, how they can benefit your web page designs, and finally the document presents a working example of a sample translation. 
A working embedded example of a codepen is also provided as a web link in the summary section. The strategy for animating the html objects is also outlined. These concepts can be extended beyond the simple html objects to html images, svg documents, and other html content.


### CSS3 Translation Functions – a Definition
The three main CSS3 translation functions are rotate, skew, and translate. 
Rotate is when an object is turned clockwise or counterclockwise, based on the degree value inputted. For instance, if the degree value inputted is 45deg, then the object will be turned 45 degrees clockwise. If the opposite degree value was inputted, -45deg, then the object would be turned 45 degrees counterclockwise.
Skew is when the object is transformed based on the x-axis or y-axis. For example, if the x-axis value is 20 degrees and the y-axis value is 10 degrees, then the object is slanted along the x-axis and y-axis.
Translate is when an object is moved from its original position to a new position on the x-axis or y-axis. For example, if the value translate(100px, 300px) was added to the CSS, then the object would move 100px to the right along the x-axis and 300px down from its current position. If negative values were used, then the object would move in the opposite direction along the x-axis and y-axis.
This article will concentrate on the 2d translation function rotate. The goal will be to demonstrate html objects that are animated by rotating them a number of degrees based off of web browser events such as mouse over.


### CSS3 Translation Functions – Sample Use Cases
CSS3 2d translation has a few different uses to make a webpage stand out. Some use cases are to animate web pages, bring attention to content, and can be used in online help wizards. Also, 2d translation functions can be used to demonstrate geometric concepts. For instance, CSS3 translation functions can be used to illustrate mathematical functions in education, and webpage design. Finally, animation media queries such as “prefers reduced motion: reduce”, can be used to help make webpages more accessible to those who are visually impaired.

### CSS3 Translations – a Sample Implementation
In this section, I will use a geometric shape, and animate it using the rotation function in CSS. Later on in the article, a codepen is embedded to further explain the 2d translation functions and expand on their uses when applying them to webpages. A fully animated codepen is an online development environment for web designers that show examples of html code snippets, animations, and interactivity that can be shared. This example will animate a rectangle by using the rotating function in CSS. Even though this is a simple example, this animation can demonstrate how to rotate more complex components, including SVG files to demonstrate geometric concepts, or provide interactivity into a webpage for purposes of instruction or highlighting key themes. To start, I added a div class with text in it. From there, using the class names in CSS, I used the transform rotation property to make the rectangle turn when the mouse is hovered over the card. The actual animation used was transform: rotateY. This was placed under the .card:hover and .card__text class, which would allow the rectangle to rotate when the mouse is hovered over the rectangle.
<﻿figure>
<iframe height="492" style="width: 100%;" scrolling="no" title="Rotation Example" src="https://codepen.io/schleppyj1/embed/RwJEbdm?default-tab=html%2Cresult" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/schleppyj1/pen/RwJEbdm">
  Rotation Example</a> by schleppyj1 (<a href="https://codepen.io/schleppyj1">@schleppyj1</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>
<﻿/figure>

<﻿figcaption>
T﻿he flipping card animation was inspired by this assignment: https://rvcc.instructure.com/courses/3569551/assignments/37763755?module_item_id=86367020
<﻿/figcaption>


### Summary
In this document CSS3 Translation Functions were defined, those functions being rotate, skew, and translate. Then, example cases for their use were provided, and how they can be used to improve the webpage. The example provided showed html code involving shapes and text were rotated using CSS 2d translation functions. Lastly, a working example of a Translation Function was illustrated, showing how different values affect the object.
The use of 2d translation functions and animation in webpages can be used to enhance the webpages provide visual interactivity, provide online help, illustrate mathematical concepts and assist in web accessibility for users of the website. 

#### Sources:
The blog site containing the Embedded Codepen for the example presented in this article is: https://codepen.io/schleppyj1/pen/RwJEbdm


URL 1: https://www.w3schools.com/css/css3_2dtransforms.asp

URL 2: Working with CSS3 2D Transform Functions - Tutorial Republic

URL 3: transform - CSS: Cascading Style Sheets | MDN (mozilla.org)


