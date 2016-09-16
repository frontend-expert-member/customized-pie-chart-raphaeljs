# customized-pie-chart-raphaeljs

Customized the color of the pie chart using Rapael JS Library

Let find the line below 

<pre>bcolor = Raphael.hsb(hue,saturation,value)</pre>

Assign the values of hue and saturation to the appropriate colors to customize it.

<pre>var colors = ["#colorCodes-1","#colorCodes-2","#colorCodes-3","#colorCodes-4"];</pre>

Sending color codes as an array object to push these color codes respectively based on the data to be shown on the pie chart. 

One more thing on the sector to assign the bcolor color value to the variable to get the value respectively.

<pre>p = sector(cx, cy, r, angle, angle + angleplus, 
    {fill: "90-" + bcolor + "-" + bcolor, stroke: stroke, "stroke-width": 1})</pre>
    
Finally achive the pie chart looks like below format:
