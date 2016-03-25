# LineLights
###  This *Algorithm* is my contribution to the topic Generative Design, first project in the class *Steel Ant - Eingabe Ausgabe* taught by Fabian Morón Zirfas, University of applied science - Potsdam (Germany).

View live demonstration site at http://martakarta.github.io/LineLights

### Analogue Algorithm
This project started in a really analogue way. Two times 10 people were asked to follow some instructions and perform an algorithm.

##### Given Instructions: 
######  1.  Fix the cord on the grid (on any pin).
######  2.  Create a pattern.
######  3.  You are allowed to connect neighbours pins an not to skip.
######  4.  You must use the whole length of the cord.
######  5.  Fix the end of the cord to any pin.

##### The analogue results:


<img src="https://raw.githubusercontent.com/martakarta/LineLights/master/1an.png"/>

<img src="https://raw.githubusercontent.com/martakarta/LineLights/master/2an.png"/>

### Digital Algorithm
The next goal was to translate the analogue into a digital algorithm using p5.js. The main difficulty was to create a grid, in which the programm could connect a starting point to one of its neighbour points and set the reached point as the new starting point for the next repetition.

The following logical explanation allows to create a grid of any misure, in which every point has an index and a mathematical relationship to its neighbour points.

<img src="https://raw.githubusercontent.com/martakarta/LineLights/master/grid.png"/>
*x = number of points in a column



##  The first neighbour code:

<img src="https://raw.githubusercontent.com/martakarta/LineLights/master/neighbours.gif"/>

<img src="https://raw.githubusercontent.com/martakarta/LineLights/master/neighbours2.png"/>

After the raw code for the neighbour points was written, was the moment to style the line, make the algorithm visual interesting and find some application of use. 

In the final version the code draws a multiparallel line in different colours, what gives more dinamic to the canvas.
http://martakarta.github.io/LineLights


### Mockup

This algorithm could be used in public enviroments as light walls, for example in airports also showing the arrivals and departures of the plains.

<img src="https://raw.githubusercontent.com/martakarta/LineLights/master/m1.png"/>

<img src="https://raw.githubusercontent.com/martakarta/LineLights/master/m2.png"/>
