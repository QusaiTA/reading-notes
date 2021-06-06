## Canvas element:

- its like image tag but without src or attributes you can just control its size, it can style normally.
- its required closing tag.
- we use getContex to render in canvas element.
- (0,0) point in the top left corner.
- fillRect(x, y, width, height): Draws a rectangular outline.
- clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent.
- strokeRect(x, y, width, height)Draws a rectangular outline.
- canvas just creating rectangular and paths and all other shapes are compine between paths.

**all function for drawing a path:**

- beginPath() Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
- Path methods Methods to set different paths for objects.
- closePath() Adds a straight line to the path, going to the start of the current sub-path.
- stroke() Draws the shape by stroking its outline.
- fill() draws a solid shape by filling the path's content area.

**commands for drawing text:**

- font = value  The current text style being used when drawing text, This string uses the same syntax as the CSS font property, The default font is 10px sans-serif.
- textAlign = value; Text alignment setting. Possible values: start, end, left, right or center, The default value is start.
- textBaseline = value; Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
- direction = value; Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.

## Charts:

> How to make line chart:

- donwnloae chart.js
- canvas id="buyers" width="600" height="400" /canvas
- script that will retrieve the context of the canvas
> script

> var buyers = document.getElementById('buyers').getContext('2d');

> new Chart(buyers).Line(buyerData);

> script

- create the data that will fill the chart.

**Drawing a bar chart:**

> same steps but the buyerdata different.