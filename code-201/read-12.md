# Chart.js & Canvas API  

## chart.js
it's a javascript plugin that uses HTML's canvas element to draw graph. Using chart.js you can draw bar charts, line charts, pie charts and more. You can use chart.js by imbed a link to it inside your HTML document.

Steps to draw a line chart:

* import chart.js plugin in side your html document
    * ```html  
        <html lang="en">
        <head>
            <meta charset="utf-8" />
            <title>Chart.js demo</title>
            <script src='Chart.min.js'></script>
        </head>
        <body>
        </body>
     </html>
     ```  
* create a canvas element in which chart.js can draw our chart
    * ```html
        <canvas id="buyers" width="600" height="400"></canvas>
      ```  
* write a script at the end of the body element that will retrieve the context of th canvas
    * ```html
        <script>
             var buyers = document.getElementById('buyers').getContext('2d');
             new Chart(buyers).Line(buyerData);
        </script>
      ```
* create your own data
    * ```html
        <script>
            var buyerData = {
            	labels : ["January","February","March","April","May","June"],
            	datasets : [
	            	{
		            	fillColor : "rgba(172,194,132,0.4)",
		            	strokeColor : "#ACC26D",
		            	pointColor : "#fff",
		            	pointStrokeColor : "#9DB86D",
			            data : [203,156,99,251,305,247]
		            }
	                ]
                }
        </script>
      ```  
 and the same steps for other charts.

 ## Canvas API  

 The Canvas API provides a means for drawing graphics via JavaScript and the HTML <canvas> element. Among other things, it can be used for animation, game graphics, data visualization, photo manipulation, and real-time video processing. the Canvas API largely focuses on 2D graphics.  
  for example the following code draws a green rectangle onto canvas:
  ```html
    <canvas id="canvas"></canvas>
  ``` 
using canvas you can draw rectangles, triangles, lines, arcs and curves. you can apply colors to a shape using two important properties:
* fillStyle
* strokeStyle

```html
    ctx.fillStyle = 'orange';
    ctx.fillStyle = '#FFA500';
    ctx.fillStyle = 'rgb(255, 165, 0)';
```  
In html5 you can draw texts onto a canvas. The canvas rendering context provides two methods to render text:

* fillText(text, x, y [, maxWidth])
* strokeText(text, x, y [, maxWidth])
