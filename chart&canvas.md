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

