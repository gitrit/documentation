# Designs
A detailed breakdown of the different designs

## Table of Contents
All design elements are organized according to [Atomic Design](http://bradfrost.com/blog/post/atomic-web-design/). Basic elements like colors and links are Atoms. Reusable combinations of atoms are Molecules and large sections are  

1. [Atoms](#atoms)
    1. [Colors](#colors)
    2. [Graph Nodes](#graphnodes)
2. [Molecules](#molecules) 
    1. [Info Modal](#infomodal)
3. [Organisms](#organisms)
    1. [Header](#header)
    2. [Sections](#sections)

<div id="atoms"></div>
## Atoms

<div id="colors"></div>
### Colors
![Colors](mockups/Colors.png)
The site uses a bright color palette inspired by Google's [Material Design](https://www.google.com/design/spec/style/color.html). The center column is the base color. Each one has a light and dark variant.

<div id="graphnodes"></div>
### Graph Nodes
![Graph Nodes](mockups/Nodes.png)
These are the nodes that will be used in the graph. There are 12 base colors, which is what will be displayed by default. There is a dimmed variant and an active variant for each color. Each node is **25px in diameter** with a border that is **4px thick.**

<div id="molecules"></div>
## Molecules

<div id="infomodal"></div>
### Info Modal
![Info Modal](mockups/ModalMobile.png)
**Fonts**

 + _Main Header:_ Montserrat Bold (24px)
 + _Subheaders:_ Montserrat Bold (20px)

**Icons**
 
 + _Close:_ **30px x 30px**

This is the mobile view of the Modal. It appears below a selected Graph Node when it clicked in a way similar to [this demo.](http://codepen.io/recanti/pen/GpmgjM) There is a button at the top which will close the modal. It is located **8px from the top** and **8px from the right.** Tapping anywhere outside the modal will also close it. The arrow consists of a **35px x 35px** rectangle rotated **45 degrees**

Text content begins immediately after. The padding on the **Bottom, Left and Right** is **24px.** There is no padding on the top.

![Scrolled Modal](mockups/ModalMobileScrolled.png)
The main portion of the modal has a **fixed height of 355px.** If the content within overflows, the User can scroll through it. Spacing between subsections is **12px.**

![Large Modal](mockups/ModalLargeView.png)
When the screen size is larger than **Tablet View (768px)** The View changes slightly. It now appears beside the node and the arrow points to the left. It is located 35px from the top of the modal.

<div id="organisms"</div>
## Organisms

<div id="header"></div>
### Header
![Header](mockups/Header.png)
 
**Fonts**

 + _Header:_ Montserrat Bold (24px)
 + _Navigation:_ Montserrat Regular (24px)


**Icons**

 + _Sandwich Menu:_ **24px width x 25px height** (only in mobile view)
 

![Mobile Header](mockups/HeaderMarked.png)
This is the header of the page. The title is **20px** from the left and the menu is **20px** from the right. 

![Large Header](mockups/HeaderLarge.png)
Once the device width has expanded to tablet width (**768px**), the menu becomes a list of links, spaced **15px** apart, to each section. All content is vertically centered.

<div id="sections"></div>
### Sections
![Red Section](mockups/SectionRed.png)
![Blue Section](mockups/SectionBlue.png)
![Yellow Section](mockups/SectionYellow.png)
![White Section](mockups/SectionWhite.png)
 
**Fonts**

 + _Header:_ Montserrat Bold (30px)
 + _Body:_ Roboto Regular (13px)


![Section Measurements](mockups/SectionWhiteMarked.png) 
Content can be placed in different sections. Each section is described in a title, which is placed in the header section. Header text is horizontally centered and has a top and bottom margin of **24px**. The header has a bottom border that is **4px** thick. 

Body contents are **24px** from the bottom of the header, **36px** from the bottom of section, and **20px** from the edges. There is a 12px spacing between pieces of content.

![Section Measurements](mockups/SectionLargeMarked.png) 
The rules for the section change when it gets large enough. When the screen expands beyond tablet view (**768px**), content is spaced **50px** from the top and bottom of the section. Content has a maximum of width of 960px and will be be horiontally centered after it reaches that point.