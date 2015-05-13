## PHPChart ##
A Simple PHPChart Library to draw Graphs and Pie Charts etc

### How to Use ###
Include the Chart Class
```
include 'Chart.php';
```

Initialize the Class by adding Data to show in Array
```
$chart = new Chart(array(
    "Jan" => 110,
    "Feb" => 130,
    "Mar" => 215,
    "Apr" => 81,
    "May" => 310,
    "Jun" => 110,
    "Jul" => 190,
    "Aug" => 175,
    "Sep" => 390,
    "Oct" => 286,
    "Nov" => 150,
    "Dec" => 196
));
```

Finally Call the drawBar method to draw bar
```
$chart->drawBar();
```

### Example ###
A simple Bar Graph
![Bar Graph](https://github.com/faizanayubi/PHPChart/blob/master/example.png?raw=true)

### How to Use ###
Include the Chart Class
```
include 'Chart.php';
```

Initialize the Class by adding Data to show in Array
```
$chart = new Chart(array(
    "Jan" => 110,
    "Feb" => 130,
    "Mar" => 215,
    "Apr" => 81,
    "Nov" => 150,
    "Dec" => 196
));
```

Finally Call the drawPie method to draw Pie Graph
```
$chart->drawPie();

### Example ###
A simple PIe Graph
![Pie Graph](https://github.com/faizanayubi/PHPChart/blob/master/example_pie.png?raw=true)
