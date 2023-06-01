introduction
------------

The website is now ready for you manage it according to your needs. We have ensured that the website is fully functional, thoroughly tested, and optimized for performance across different devices and browsers. It is equipped with the necessary tools and features to enable you to update and maintain it easily.

As part of the handover process, we will provide you with comprehensive documentation that outlines the website's structure, features, and functionality. This documentation can be found in the readme.md and the comments of the html and css file. This documentation will serve as a valuable resource for guiding you through the website

### Comments html & css

The comments in HTML & CSS are used to separate items in a more scannable manner, allowing for easy differentiation between HTML elements.

In the CSS file, the code is mostly written in chronological order, starting from main elements and progressing to nested elements. The pages are organized from left to right. As a result, the index page will be located at the top of the file, while the last page in the menu will be found at the bottom. This order is also maintained within media queries.

### General text and markup conversion

General styling is applied directly to the font elements themselves, such as h1, h2, h3, p, etc., and can be freely utilized inside all sections.

Additionally, we have introduced a new section called "paper", denoted by the class <section class="paper">. This section is designed for handling large amounts of text and can be reused for various purposes. Since it does not use any classes on the elements inside it will allow the user to copy and paste plain text elements.

A use case for this would be when you converting markup to plain html and pasting it inside the paper section

### Class naming is done with the Bem naming convention:

BEM divides components into three main parts: blocks(), elements, and modifiers. A block represents a standalone component or a higher-level container that encapsulates related elements. Elements are the individual parts within a block that have no meaning or functionality outside of it. Modifiers, as the name suggests, are variations or states of a block or element that alter its appearance or behavior.

In terms of naming conventions, BEM suggests using a specific syntax: block__element--modifier. The double underscore (__) is used to separate a block from its elements, while the double dash (--) is used to separate a block or element from its modifiers. This naming convention helps to maintain a clear hierarchy and avoid naming conflicts.

-   Block = navigation

-   elements =  naviagation__list, naviagation__list-item

-   modifier = navigation---blue, navigation---black

-   [Bem introduction](https://getbem.com/introduction/)

-   [Deeper dive into Bem](https://www.smashingmagazine.com/2016/06/battling-bem-extended-edition-common-problems-and-how-to-avoid-them/)

The main block/components name will most often be found in the <section></section> elements and is reusable

### Licensing

License:  [Apache-2.0/](https://choosealicense.com/licenses/apache-2.0/)

The Apache License 2.0 is a permissive open-source license that allows unrestricted usage, modification, and distribution of software. It provides legal clarity and flexibility for incorporating open-source components into projects, whether personal or commercial. With patent grants, it offers protection against potential patent claims. The license allows seamless software redistribution and the option to sublicense under different terms. It also ensures proper attribution to original authors. The Apache License 2.0 is widely adopted due to its business-friendly terms, compatibility with other licenses, and the freedom it grants to developers and organizations to leverage and contribute to open-source software.
