# MUSTACHE and FLEXBOX
## Mustache  
Mustache is a logicless template engine for creating dynamic content like HTML, configuration files among other things. You can use mustache.js to render mustache templates anywhere you can use JavaScript. 

A mustache template is a string that contains any number of mustache tags. Tags are indicated by the double mustaches that surround them. {{person}} is a tag, as is {{#person}}. In both examples we refer to person as the tag's key. There are several types of tags available in mustache.js, described below.

There are several techniques that can be used to load templates and hand them to mustache.js, here are two of them:
* **Include Templates**
* **Load External Templates**

## FlexBox
Before the Flexbox Layout module, there were four layout modes:

* Block
* Inline
* Table
* Positioned
The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.The Flexbox Layout (Flexible Box) module aims at providing a more efficient way to lay out, align and distribute space among items in a container, even when their size is unknown and/or dynamic.
The main idea behind the flex layout is to give the container the ability to alter its items’ width/height (and order) to best fill the available space (mostly to accommodate to all kind of display devices and screen sizes). A flex container expands items to fill available free space or shrinks them to prevent overflow.

flex box elements are:
* **flex container**
* **flex items**

Properties for the Parent(container):
* display
* flex wrap
* flex flow
*  justify-content
Properties for the Children(flex items):
* order
* flex-grow
* flex-shrink
* flex-basis