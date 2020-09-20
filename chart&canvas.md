# Chart js :
Pie and doughnut charts are probably the most commonly used charts. They are divided into segments, 
the arc of each segment shows the proportional value of each piece of data.

They are excellent at showing the relational proportions between data.

Pie and doughnut charts are effectively the same class in Chart.js, but have one different default value 
- their cutoutPercentage. This equates what percentage of the inner should be cut out. This defaults to 0 for pie charts, and 50 for doughnuts.

They are also registered under two aliases in the Chart core. Other than their different default value,
and different alias, they are exactly the same.

// For a pie chart
```var myPieChart = new Chart(ctx,{```
    ```type: 'pie',```
    ```data: data,```
    ```options: options```
```});```

// And for a doughnut chart
```var myDoughnutChart = new Chart(ctx, {```
    ```type: 'doughnut',```
    ```data: data,```
    ```options: options```
```});```

![](https://tr1.cbsistatic.com/hub/i/r/2013/08/16/09acee62-3e62-4c50-b7dc-7190cb49267c/resize/1200x/be8373cfb2c0b8f079f152dd7eff2acf/Chartjs_FigA_081613.jpg)

# canvas


<canvas> is an HTML element which can be used to draw graphics via scripting (usually JavaScript). This can, for instance, be used to draw graphs, combine photos, or create simple (and not so simple) animations. The images on this page show examples of <canvas> implementations which will be created in this tutorial.

This tutorial describes how to use the <canvas> element to draw 2D graphics, starting with the basics. The examples provided should give you some clear ideas about what you can do with canvas, and will provide code snippets that may get you started in building your own content.

First introduced in WebKit by Apple for the OS X Dashboard, <canvas> has since been implemented in browsers. Today, all major browsers support it.
    
 >Using the <canvas> element is not very difficult, but you do need a basic understanding of HTML and JavaScript. The <canvas> element is not supported in some older browsers, but is supported in recent versions of all major browsers. The default size of the canvas is 300 pixels × 150 pixels (width × height). But custom sizes can be defined using the HTML height and width property. In order to draw graphics on the canvas we use a JavaScript context object, which creates graphics on the fly.
    
   ![](https://i.ytimg.com/vi/82njuSr6qv8/maxresdefault.jpg)
