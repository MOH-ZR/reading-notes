# Audio, Video, Images, SEO
## Images

**Controlling sizes of images in CSS**  
You can control the size of an image in CSS using the width and height properties.  
```css
    img {
        width: 220px;
        height: 360px;
    }
```  
**Aligning images in CSS**  
You can align an image using float property in CSS with value either left or right.  
```css 
    img {
        float: left
    }
```
To center an image within its container it has to be block element and then using one of the following approaches:
* text-align: center (for its container)
* margin: 0 auto  
```css
    /*first method*/
    div {
        display: block;
        text-align: center;
    }

    /*second method*/
    img {
        display: block;
        margin: 0 auto;
    }
```  
**Adding background images**  
To add background image for HTML element, use background-image property.  
```css
    body {
        background-image: url("put image path");
    }
```  
There are many properties that can be applied for the background image :
* background-repeat that can have four values: repeat, repeat-x, repeat-y, or no-repeat.
* background-attachment: used when the image is shown once and have value: fixed, scroll.
* background-position: specify the position of the image and may take: left top , center bottom and many other.

Or use the shorthand of background as following:
```css
    body{
      background: #fefefe url("image-path") no-repeat top right;  
    }
```
**image rollovers & sprites**  
In CSS, it is possible to change the style a button or link when the user hover over or click on it this is called **rollover**.
**spirit** is a collection of images put into a single image. we can use it with rollover to change the style of a button or link depending on the action occurred.

**CSS3 Gradients**  
In CSS , you can use gradients as background images. There is many types of gradients ans the most common one is linear gradient that can be applied by specify two colors that the gradient is between.  
```css
    body {
        /*For Opera browser 11.10+*/
        background-image: -o-linear-gradient(#334455, #996611)
    }
```  
## Practical Information & Search Engin Optimization (SEO)

**search engin optimization(SEO)**  
**SEO** is the practice of trying to improve your website's visibility on search engines. SEO is often split into two areas: 
* **on-page techniques**: methods used to improve your site rating by include the terms on your web pages that most likely used by people to find your site. There are seven places where keywords can appear in order  to improve its    findability:
    * page title
    * URL/WEB address
    * headings
    * text
    * link text
    * image alt text
    * page descriptions
* **off-page techniques**: how many sites link to your web site.  

**using analytics to understand visitors**  
**Google analytics** is a free service provided by google used to learn more about your site visitors such as what they are looking at and at what point they are leaving and how many people coming to your site. These questions are viewed by google analytics in terms of many factors.

**How many people are coming to your site?**
* visits
* unique visits
* page views
* pages per visit
* average time on site
* date selector
* export  

**What are toy visitors looking at?**  
* pages
* landing pages
* top exit pages
* bounce rate: this show the number of people who left on the same page that they arrived on.

**Where are your visitors come from?**  
* references: shows the sites that have linked to you and the number of people who have come via those sites.
* direct: shows which page a user arrived on if they didn't come via a link on another site.
* search terms.  

## Domain Names & Hosting  

In order to put your site oon the web you will need a domain name and web hosting. The domain name is the site web address like google.com. Web hosting refers to upload your web site to a web server so that other people can see your site.

## FTP & Third Party Tools  

File Transfer Protocol (FTP) allows you to transfer files across internet from your computer to the web server hosting your site. There are many FTP programs that offer a simple interface that shows the files on your computer alongside the files that are on the web server.

Many companies provide platforms for blogging, email, newsletters, e-commerce and other popular website tools.These called third party tools. 

## HTML5 video and audio  

The `<video>` and `<audio>` elements allows us to embed video and audio into web pages. controls attribute of video element enables the default set of playback controls. and you can program your own with HTML, CSS, and JavaScript. 

**The HTMLMediaElement API**  
The HTMLMediaElement API provides features to control video and audio players programmatically.

## Flash  
Flash is a very popular technology used to add animations, video, and audio to web sites. 




