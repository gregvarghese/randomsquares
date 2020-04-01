# Random Squares

This sample shows how to generate squares dynamically based on the container dimensions, select a random color, and then do a fade on a random number of the squares. 

Notes:

* Currently uses a few jquery functions. I may revisit and convert to vanillajs at some point.
* Random shuffle is done using a Fisher-Yates implementation.   
* Color is set to be random but you can also hard code a specific color (example is commented out)
* Fade is set to be toggled and uses CSS3 transitions
* Call the random function and pass in the number of squares to fade randomly at a time. Easily adjust the speed and the number of slices to fade/in out.

## Working Demo

https://rawgit.com/gregvarghese/randomsquares/master/index.html
