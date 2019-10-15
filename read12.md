## Making Charts:

The first thing you need to do is download the chart.js script from gitHub then link it to your index.html page.

    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="utf-8" />
            <script src='Chartjs'></script>
        </head>
        <body>
        </body>
    </html>
  
  You can make bar charts or pie charts you just need to start with a canvas element, for example:
  
      <canvas id="votes" width="600" height="400"></canvas>
    
To make a nar chart you need to specify it as a bar chart by:

    var votes = document.getElementById("votes").getContext("2d");
    new Chart(votes).Bar(barData);
  
