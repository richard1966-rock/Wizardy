# Wizardy\_Pro

Fischer Technik Silberling module based on Arduino

The module features:

* 4 Analogue inputs
* 8 Digital inputs
* 4 Potmeters
* 4 FT Outputs (9V) (3 of them are shared with Servo)
* 4 Servo outputs (3 of them are shared with Outputs)
* 2 Motor outputs
* Display
* Reset button





This is the base file of the Wizardy pro



Any function to be build on Wizardy pro can use this sketch as basis. 

Functions of the base file:



* Define the name of the module
* Define the name of each input
* Define the name of the potmeters
* Define the max/min values of the potmeters
* Limits the refresh rate of the display to a minimum to speed up the loop code - active monitoring on changes on display
* All logic is present to do the multiplexing of the inputs \& potmeter scanning
* Flexible use of servo names
* 



