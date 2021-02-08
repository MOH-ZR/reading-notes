# Basics of HTML, CSS & JS
## Text in HTML5    
When building a web page, we add tags to the physical contents of the page. These tags identify various parts of the page in a semantically consistent way. Without these tags the page would just be raw text. we wouldn't even be able to include images, because there would be no way for the browser to tell the difference between the regular text on the page and the code that identifies the source of the image file on the web server.

Elements in HTML5 could be either a *semantic* or *non-semantic(structural)* element.A semantic element clearly describes its meaning to both the browser and the developer while non-semantic tells nothing about its content.

Examples of non-semantic elements: `<div>` and `<span>`.  
Examples of semantic elements: `<table>`, `<header>` , and `<article>`.  

![non-semantic vs semantic](https://miro.medium.com/max/576/1*qBLobOINLXv38nCOmCZW2Q.jpeg)

### **non-semantic elements**

* Headings  
    * HTML has six "levels" of headings
    * `<h1>` is used for main headings and has the largest size.
    * `<h2>` is used for subheadings and so on. 
    * `<h6>` has the smallest size.  
    * ![headings](https://1.bp.blogspot.com/-Srnw_8jBHSY/XvHQqaCppZI/AAAAAAAAOuU/cikYtvXLix8dNc-qFMG4j50e-94FCpzLgCLcBGAsYHQ/s1600/heading%2B1%2Bto%2B6.jpg)
* Paragraphs
    * `<p>` element is used to create a paragraph.
    * each paragraph will be shown on a new line with some space between it and any subsequent paragraphs.
    * when the browser comes across two or more spaces next to each other, it only displays one space. similarly, it if comes across a line break, it treats that as a single space to. This is known as **white space collapsing**
* Bold & Italic
    * `<b>` used to make its content bold.
    * `<i>` used to make characters appear italic.
    * `<u>` used to underline a text.
    * ![examples](https://developersdesire.files.wordpress.com/2014/09/biu-page-0.jpg)
* Superscript & Subscript
    * `<sup>` used to contain characters that should be superscript such as raising a number to a power.
    * `<sub>` used to contain characters that should be subscript such as in chemical formulas.
    * ![super vs sub](https://support.content.office.net/en-us/media/0e396025-76a9-4051-8960-74ca0aeeb739.png)
* Line Breaks & Horizontal Rules
    * `<br />` used to make a line break.
    * `<hr />` used to create a horizontal line break. 

### **semantic elements**

* Strong & Emphasis
    * `<strong>` indicates that its content has strong importance so for example the words might be said with strong emphasis. browsers will show emphasized content in bold.
    * `<em>` indicates emphasis that subtly changes the meaning of a sentence. browsers will show the content in italic.
* Quotations
    * `<blockquote>` used for longer quotes that take up an entire paragraph. its content will be indented by browsers.
    * `<q>` used for shorter quotes that sit within a paragraph.
* Abbreviations
    * `<abbr>` used to define an abbreviation or an acronym like "HTML", "CSS" and "Prof".
    * ![Abbreviations](https://www.android-examples.com/wp-content/uploads/2016/03/abbr-tag.png)
*  Citations & Definitions
    * `<cite>` used to define a title of a work like a book, a poem. the content of cite tag is rendered in italic.
    * `<dfn>` used to indicate the defining instance of anew term.
* Author Details
    * `<address>` use to contain contact details for the author of the page. it can contain a physical address, phone number , and email address.
* Changes to Content
    * `<ins>` used to show the content that has been added into a document.
    * `<del>` used to show text that has been deleted from a document.
    * `<s>` indicates something that is no longer accurate but it should not be deleted. 

## Introducing CSS

CSS (Cascading style Sheet) makes web pages more attractive using rules that specify how the content of an element should appear. CSS teats each element inside HTML document as it if were represented by a box, as show below:  
![box model](https://miro.medium.com/max/576/1*xBACRohHubgriBk0GXVaaw.jpeg)  
 There are many way you can style HTML elements using css for example:
 * Boxes: width, height, border, background color and position.
 * Text: size, color and  bold.  
  
  CSS works by associating rules with HTML elements. A CSS rule contains two parts: a *selector* and a *declaration*. selector indicates which element the rule applies to and the declaration indicates how the element referred to in the selector should be styled. 
  Each declaration in css rule is made of two parts: a *property* and its *value*. the property indicates the aspects of the element you want to change and the value specify the settings for the property. 

  ![CSS rule](https://3wga6448744j404mpt11pbx4-wpengine.netdna-ssl.com/wp-content/uploads/2012/10/css-rule.jpg)

  There are three ways to write a css:
  * **inline**: by using style attribute.
  * **internal**: using style tag inside head element.
  * **external**: by creating a .css file and link it to HTML document using link empty element.  
  ![CSS](https://www.bitdegree.org/learn/storage/media/images/8c4493d3-110c-4a95-8b70-7626ce2d2f4e.jpg)  

  There are many different types of CSS selectors that allow you to target rules to specific elements in an html document.

  ![CSS selectors1](https://www.csssolid.com/images/35cssselectorstoremember/25-css-selectors-cheat-sheet-part1.png)
  ![CSS selectors2](https://www.csssolid.com/images/35cssselectorstoremember/25-css-selectors-cheat-sheet-part2.png)  
  ![CSS selectors3](https://www.csssolid.com/images/35cssselectorstoremember/25-css-selectors-cheat-sheet-part3.png)


**How CSS Rules Cascade?**
if there are two or more rules that apply to the same element, there will be a priority in applying these rules which are: 
* Last Rule: apply the last rule if they are identical
* Specificity: apply the most specific rule 
* Important: apply this rule over any other one by using ! mark

## Introduction to JavaScript

JavaScript is a programing language used mainly in front-end web development to make your web pages more interactive and dynamic by accessing and modifying web content based for example on some actions. It gives your web page some functionality to react for events.

examples of where we can use javascript in the browser:
* Slideshow
* Forms to get the data from it
* Reload part of page to load a new look
* filtering data foe example based on user input

JS is like any programing language has data types such as string, boolean, and number. 

for example:
* 'Ali' : considered as string type
* 23 : number
* true or false: boolean

and there are many other types.

arithmetic operations:
* "+":  addition and used to contact strings also
* "-": subtraction 
* "*": multiplication
* "/": division

comparison operators:
* ">": greater than
* "<": less than
* "==": is equal(compare just the value)
* "===": is equal(compare value and type of operands)

### Variables in JS
variable is like a container for any data you want.

in JS you can declare a variable like this : var x = 5;
when you declare a variable check the following points:
* the name must begin with a letter, $, or _
* don't use keywords like var.
* use meaningful names.

### Comments

developers use comments to explain code for others and to make it more clear. In JS there are two types of comments: 
* single-line comments: using by double forward slash //
* multi-line comments: using forward slash and star /* */  
![Single vs Multi](https://i.stack.imgur.com/MsLfq.png)

### Arrays
Array is a container for more than one value. it stores a list of values.

for example :  
```JS 
var  colors;
colors = ['white', 'black', 'yellow']
```
every item in an array is given a number called **index**. this can be used to access specific items in the array. 
for example:  
```JS
colors[0]; // will return white
``` 

### Expressions

expression evaluates into a single value. there are two types of expressions:
* assignment expression: 
    * ```JS
        var x = 5;
    ```
* using more than ne value.
    * ```JS
        var x = 5 * 3;
    ```

### Loops

loop take a condition and checks its value; if it returns true, a code block will run and after that will check a gain and again until the condition is false then will exit from loop.

There are three common types of loops:

* for: used to run a block of code a specific number of times.
    for example:
    ```JS
     for(var i = 0; i < 10; i++){
        console.log(i);
    }
    ```
    this loop will print numbers from 0 to 9 on the console

* While: used to run a code until the condition is false and you don't know how many numbers to run.
   for example:
   ```JS
    while(x != 6){
        // code to insert from user the value of x
    }
    ```
    here code will check the value inserted by the user and check if it equal to 6.

* do while: it is similar to while , but it will run the code inside the curly brackets even one time at least
    for example:
    ```JS
    do {
        // code
    } while (condition)
    ```
