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

### CSS3 Translation Functions – a Definition
The three main CSS3 translation functions are rotate, skew, and translate. 
Rotate is when an object is turned clockwise or to counterclockwise, based on the degree value inputted. For instance, if the degree value inputted is 45deg, then the object will be turned 45 degrees clockwise. If the opposite degree value was inputted, -45deg, then the object would be turned 45 degrees counterclockwise.
Skew is when the object is transformed based on the x-axis or y-axis. For example, if the x-axis value is 20 degrees and the y-axis value is 10 degrees, then the object is slanted along the x-axis and y-axis.
Translate is when an object is moved from its original position to a new position on the x-axis or y-axis. For example, if the value translate(100px, 300px) was added to the CSS, then the object would move 100px to the right along the x-axis and 300px down from its current position. If negative values were used, then the object would move in the opposite direction along the x-axis and y-axis.

### CSS3 Translation Functions – Sample Use Cases
CSS3 2d translation has a few different uses to make a webpage stand out. Some use cases are to animate web pages, bring attention to content, and can be used in online help wizards. Also, 2d translation functions can be used to demonstrate geometric concepts. Finally, animation media queries such as prefers reduced motion: reduce, can be used to help make web pages more accessible for all users.

### CSS3 Translations – a Sample Implementation
In this section, I will use a geometric shape, and animate it using the rotation function in CSS. Later on in the article, a codepen is embedded to further explain the 2d translation functions and expand on their uses when applying them to webpages.
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
In this document CSS3 Translation Functions were defined, those functions being rotate, skew, and translate. Then, example cases for their use were provided, and how they can be used to improve the webpage. Lastly, a working example of a Translation Function was illustrated, showing how different values affect the object.
#### Sources:
URL 1: https://www.w3schools.com/css/css3_2dtransforms.asp

URL 2: Working with CSS3 2D Transform Functions - Tutorial Republic

URL 3: transform - CSS: Cascading Style Sheets | MDN (mozilla.org)

