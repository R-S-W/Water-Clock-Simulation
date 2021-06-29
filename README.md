# Water Clock Simulation

I created a simple simulation to replicate a water fountain that prints pictures and designs.

## Intro
I was inspired by the Osaka Station Water Clock, a fountain that displays the current time with water.  The fountain is a line of programmable nozzles that creates a curtain of water.  They can be programmed to draw shapes, pictures, and designs by controlling when a nozzle fires water at a specific time.

Here lies an interesting problem: how does one program the nozzles to print out a shape?  A solution is more difficult than it appears.  Notice how all of the shapes start do stretch as they fall.  This is because the bottom part of the shape is in freefall for a longer time than the top part of the shape, meaning that gravity pulls the lower half down for a longer time.  The bottom portion picks up more speed and falls faster than the top part, creating a distortion as the shape is being printed.  The difference in speeds of the water droplets also cause the picture to elongate as time passes, so even if a perfect circle is drawn, it will immediately start to lengthen and become an oval.

So how do you draw it?  I sought to find out how can one draw a picture and have it be perfectly replicated without distortion.

## Simulation
I used 
