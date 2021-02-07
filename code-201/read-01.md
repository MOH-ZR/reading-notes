# Introductory HTML and JavaScript

## HTML Structure
HTML uses elements to describe the structure of pages. Most elements in HTML have the same structure as show below figure:

![HTML element anatomy](https://www.w3.org/community/webed/wiki/images/0/09/HTMLelement.gif)  

* **opening tag**: indicates the start of HTML element
* **closing tag**: indicates the end of HTML element
* **content**: such as text in parahraph element
* **attribute**: has a name and value and provide additional information about the contents of an element.

for example: 
```html
<p id="first"> Hello Code Fellows </p>
```

each web page must contain html, head, and boby tags. these structure the main part:
```html
<html>
    <head>
    </head>
    <body>
        <!-- this part will be shown by web browser-->
    </body>
</html>
```
## Extra Markup
Since the web was first created, there have been several different versions of HTML. Each new version was designed to be an improvement on the last.

* **HTML4**: released 1997
* **XHTML 1.0**: released 2000
* **HTML5**: released 2000

Because there have been different versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser the page is using HTML5 version.
```html
<!DOCTYPE html>
```

you can add comment to your code that will not be visible in the user's browser by adding text between these characters:
```html
<!-- comment will not be visible -->
```

In HTML there is mainly two types of elements:
* **Block elements**: always appear to start on a new line in the browser window such as p and div elements
* **Inline elements**: always appear to continue on the same line as their neighbouring elements

To add information about your page use meta tag in head element.meta element is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it and whether or not it is time sensitive(if the page tieis sensitive, it can be set to expire).

The most common attributes for meta element are the name and content attributes, which tend to be used together.

```html
<head>
    <meta name="article" content="a paragraph about programmiing"/>
</head>
```

### Escape characters
escape characters are used to include special characters in your web pages such as <, " and &.
for example, to write a left angled bracket you can use &lt as following

```html
&lt;
```
## HTML5 Layout
The new HTML5 elements indicates the meaning of different parts of a web page, help to describe its structure and provide cleare code.

Here are some new HTML5 layout elements:
* Headers: used to contain the site name , logo and navigation bar
```html
    <header> </header>
```
* Footers: used to contain copyright information, along with links to the privacy policy and terms and conditions
```html
    <footer> </footer>
``` 
* Navigation: used to contain the main navigational blocks on the site
```html
    <nav> </nav>
```
* Articles: used to acts as container for any section of the page that may be stand alone
```html
    <article> </article>
```

**Older browsers** such as Internet explorer 8 need additional JavaScrip code to make HTML5 works properly.

## Process & Design
There are many things that any **web designer** must bear in mind when he/she start creating a web site. These steps will make design process more clear and determined and achieve more in less effort and less time.

In the words of Bijay Chhetri:
> Design doesn’t mean that every person [is] gonna like, love it, but that’s the creativity of [an] eye which creates something different.

First of all as web designer you should check your work for the following important guides:
- who your target audience
- why they would come to your web site
- what information they want to find
- when they are likely to return

After anserwing for all the previous quetions, it's time for drawing your site map that help you to organize the information into setions or pages. it's like a diagram that shows all sectios or parts in cards as in the following figure:

![Site Map](https://www.imforza.com/wp-content/uploads/2014/07/sitemap-example.png)

Now you will start design the wireframe for your site, it show the layout for web sites pages and position for every section in the web page as in the following figure:

![Wireframe](https://miro.medium.com/max/700/0*K5476VixXhddhBkA.jpg)

Keep the following intructions while you design your web page:
* Design is about communication
* differentiate between pieces of information using color, size and style
* simplify the information you present using grouping and similarity

# JavaScript

**What is script and how to create one?**
A script is a series of instructions that a computer can follow to achieve a goal. 

you can use script in front-end to for example:
* Slideshow
* Forms to get the data from it
* Reload part of page to load a new look
* filtering data foe example based on user input

### Objects and Properties

object-oreinted programming style depends on reperesenting everything as objects in real world that has attributes. fore example : car is an object. color, type , model are attributes.

Each object in Javascript can have its own:
* properties: like name and age of a person 
* Events: used to trigger a specific section of code such as when click open new tab
* Methods: used to perform a any task such as drive for car , walk for people.
