Microbit Thermometer
--------------------
In this assignment you will program your micro:bit using the built-in temperature sensor. Here is a simple program that displays the current temperature in Celsius when the A button is pressed:
```python
from microbit import *

while True:
    if button_a.was_pressed():
        display.scroll(temperature())
```
Suggested steps to completing this assignment
----------
1. Using the program above as a guide, add code that displays the current temperature in Fahrenheit if the B button is pressed. You can do a google search to find the formula to convert Celisus to Fahrenheit
2. Add variables to store the current maximum and minimu temperatures
3. Check the temperature every 2 seconds. If the thermometer reads a temperature higher or lower than the previous maximum or minimum, update the appropriate variable
4. Modify the display to scroll 3 temperatures; current, maximum and minimum. The A button should display all three temperatures in Celsius and the B button should display the same temperatures converted to Fahrenheit. 

Extensions
----------

Samples of Student Work
----------
*none yet!*
