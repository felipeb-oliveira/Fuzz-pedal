# Fuzz-pedal
A Fuzz guitar effect pedal, designed with inspiration for some classic Fuzz pedals.

## About
This guitar pedal was designed by me, and inspired by classic and simple Fuzz pedals. This was the second guitar pedal I ever projected, so there's definetely room for improvement. I used common two emmiter transistor configurations, with a DC bias which is later cut out by capacitors. The first transistor is responsible for most of the wave clipping, and the second one was designed so it would finish shaping the wave and adjusting the gain. There are two potentiometers, one for the Fuzz control, and one for the overall volume.

## Fuzz Schematic
*This is only the fuzz distortion circuit, without the inputs, outputs and supply circuits. Please open the 'Fuzz.sch' file for the full circuit.*

![Fuzz pedal schematic](https://github.com/felipeb-oliveira/Fuzz-pedal/blob/master/images/schematic.PNG)


## Board
![Fuzz pedal board](https://github.com/felipeb-oliveira/Fuzz-pedal/blob/master/images/board.png)

## Results
The results were as expected: hard wave clipping with high assymetry, as seen below.

Low Fuzz:

![Low Fuzz Simulation](https://github.com/felipeb-oliveira/Fuzz-pedal/blob/master/images/lowFuzz.PNG)


High Fuzz:

![High Fuzz Simulation](https://github.com/felipeb-oliveira/Fuzz-pedal/blob/master/images/highFuzz.PNG)


