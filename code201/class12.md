## how to use chart.js 

1- ***Setting up***

The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:
```html
<!DOCTYPE html>
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
2- ***Drawing a line chart***
- create a canvas element in our HTML
```html
<canvas id="buyers" width="600" height="400"></canvas>
```
- write a script that will retrieve the context of the canvas
```script
<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>
```
- Inside the same script tags we need to create our data
```script
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
```
3- ***Drawing a pie chart***
4 - ***Drawing a bar chart***

## Chart.js
***Installation***
- You can get the latest version of Chart.js from npm , the GitHub releases , or use a Chart.js CDN  Detailed installation instructions can be found on the installation page.

***Creating a Chart***
- It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>` node to render the chart.

***Contributing***
- Before submitting an issue or a pull request to the project, please take a moment to look over the contributing guidelines first.

## The `<canvas>` element
-  the <canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties.
- The <canvas> element differs from an <img> tag in that, like for <video>, <audio>, or <picture> elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it

### Drawing shapes with canvas like rectangles, paths, text .


