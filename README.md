Notes
-----

### Comments html & css

The comments in HTML & CSS are used to separate items in a more scannable manner, allowing for easy differentiation between HTML elements.

In the CSS file, the code is mostly written in chronological order, starting from main elements and progressing to nested elements. The pages are organized from left to right. As a result, the index page will be located at the top of the file, while the last page in the menu will be found at the bottom. This order is also maintained within media queries.

-   However, there is an exception to this order for blocks/components and general styling applied to HTML elements.

### General text and markup conversion

General styling is applied directly to the font elements themselves, such as h1, h2, h3, p, etc., and can be freely utilized inside all sections.

Additionally, we have introduced a new section called "paper", denoted by the class <section class="paper">. This section is designed for handling large amounts of text and can be reused for various purposes. Since it does not use any classes on the elements inside it will allow the user to copy and paste plain text elements.

A use case for this would be when you converting markup to plain html and pasting it inside the paper section

### class naming is done with the Bem naming convention:

BEM divides components into three main parts: blocks(), elements, and modifiers. A block represents a standalone component or a higher-level container that encapsulates related elements. Elements are the individual parts within a block that have no meaning or functionality outside of it. Modifiers, as the name suggests, are variations or states of a block or element that alter its appearance or behavior.

In terms of naming conventions, BEM suggests using a specific syntax: block__element--modifier. The double underscore (__) is used to separate a block from its elements, while the double dash (--) is used to separate a block or element from its modifiers. This naming convention helps to maintain a clear hierarchy and avoid naming conflicts.

Block = 	navigation
elements =	naviagation__list-item
modifier = 	navigation-–blue, navigation-–black

-   [Bem introduction](https://getbem.com/introduction/)

-   [Deeper dive into Bem](https://www.smashingmagazine.com/2016/06/battling-bem-extended-edition-common-problems-and-how-to-avoid-them/)

The main block/components name will most often be found in the <section></section> elements are reusable inside the <body> element
