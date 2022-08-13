# WeatherStation
This is a weather station that works with Arduino IDE.
This program allows you to visualize the current ambient temperature in C, humidity, light level.  

Version 2.0

Components:
- Arduino UNO R3 board
- LCD display 16x2
- jumper wires (many)
- potentiometer 
- DS1307 (external clock)
- prototype expansion module + mini breadboard
- photoresistor
- 10k ohm resistor
- red LED light
- 330 Ohm resistor
- I2C module (PCF8574 chip based backpack)

Currently working on:
- designing protective case
- adding gy-521 module to detect shakings that trigger the lcd display
- figuring out a better power source to allow long-term functioning (9v batteries die quickly & a wall outlet is not always available)


Ideas for future version:
- activate TFT LCD when being shaked (use GY-521 module) > order from aliexpress
- add solar cell to power it
- add air usb port to extract the data from the sd card without opening the lid of the container box
- add bluetooth module to send data wirelessly
- add air quality sensor
- add 3d printed protective case

Future steps:
- solder all the connections 
