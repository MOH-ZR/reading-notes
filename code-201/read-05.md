# Images, Color and  Text

## Images
A picture equal to one thousand word, so images form a main part in your web site amd make it more beautiful and easy to communicate with people from different backgrounds.

Tom imped an image in HTML5 use the following tag:
```html
    <img src="path to the image"/ alt="describe your image" width="in px" height="in px">
``` 
Three rules for creating images:
* save images in the right format.
* save images at the right size.
* use the correct resolution.

The *resolution* of an image is the number of squares that fit within a 1 inch * 1 inch square area and it's measures in pixels.

## Color

In CSS you can change the color of text using color property. You can specify any color in css in one of three ways:
* **RGB values**: express colors in terms of how much red, green ,and blue are used to make it up.
```CSS
    p {
        color: rgb(100, 100, 95);
    }
```

* **HEX Codes**: express colors in terms of red, green and blue but in six-digit codes for example: #FF3e80
* **Color Names**: using predefined color names for example: red, cyan

## Text 
in CSS you can use font-family property to specify he typeface for text and the size using font-size property
```CSS
    h1 {
        font-family: Georgia, Times, serif;
        font-size: 50px;
    }
```

you can determine the size in CSS in many units 

* **pixels**
* **percentages**
* **Ems**

font-weight property allows you to create bold text and text-decoration to make it underline or none and tex-align property for alignment
```CSS
    .class1 {
        font-weight: bold;
        text-decoration: none;
        text-align: left;
    }
```


