A PCB layout and schematic.

this is my fork with following features :

 * simple single sided board suitable for isolation routing
 * cheaper arduino mini instead of nano (no usb), can be used with my simplified single-sided arduino clone
 * additional A axis instead of spindle enable
 * ISP header (grbl cannot be programmed with bootloader anyway as it's too big)

TODO:
 * messy schematic and board, needs fixing
 * still using arduino nano header (unused pins just not connected) 
 * board is not really optimised
 * additional headers for tx/rx, fdti, additional arduino mini to support SD card, lcd and encoder

Made with Eagle PCB 8

##Requirements
* an arduino mini w atmega328 loaded with grbl http://github.com/grbl/grbl
* ISP programmer
* at least 1 Pololu A4988 Stepper motor driver
* power supply and motor ofcourse. 


