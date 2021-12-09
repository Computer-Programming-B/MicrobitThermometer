micro:bit Thermometer
--------------------
In this assignment you will program your micro:bit using the built-in temperature sensor. Here is a simple program that displays the current temperature in Celsius when the A button is pressed:
```python
from microbit import *

while True:
    if button_a.was_pressed():
        display.scroll(temperature())
```
The temperature sensor measures the temperature of the processor chip that can be found on the left hand side of the back of the micro:bit. The processor is circled in the picture below:      
![](thermometer2.png)   
Try holding your finger on the chip and see if you can increase the temperature sensor reading.

Program requirements
-----------------
* Your program must use at least two variables to store the maximum and minimum temperatures
* Your program must display both Celsius and Fahrenheit temperatures
* Every temperature displayed on the LED should be correctly labled as Celsius or Fahrenheit
* Submit both the Python code and an animated gif showing your program running to Google Classroom

Suggested steps to completing this assignment
----------
1. Using the program above as a guide, add code that displays the current temperature in Fahrenheit if the B button is pressed. You can do a google search to find the formula to convert Celisus to Fahrenheit
2. Add variables to store the current maximum and minimum temperatures
3. Modify the program to check the temperature every second. If the thermometer reads a temperature higher or lower than the previous maximum or minimum, update the appropriate variable
4. Modify the display to scroll 3 temperatures; current, maximum and minimum. The A button should display all three temperatures in Celsius and the B button should display the same temperatures converted to Fahrenheit. 

A technical note on the Degree Symbol °
-----------------
The degree symbol ° is not supported on the LED display of the micro:bit. The micro:bit LED display only supports ASCII characters 32 - 127 and the degree symbol ° is ASCII code 248. The asterix * or apostrophe ' are reasonable substitutes. (Note that even though they look very similar or even identical in some fonts, the apostrophe ' is not the same as the single quote ' which has a special meaning in Python. Python treats them differently because they have different ASCII codes.)

Extensions
----------
You could modify your program to display a graph showing the relative current, maximum and minimum when neither button is pressed.

**Are you hot?** Modify your program so that it tells a person how hot they are when they hold their finger on the processor. Pass your micro:bit to your friends and see which one is hottest.

Your thermometer program doesn't have to work or look like any other. Have fun and be creative!

Samples of Student Work
----------
*none yet!*
