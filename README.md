# project-template
This is the official template for student's projects

Lesson 1 : LedBlink
The LED plugged on the Arduino card is recognised thanks to the following line :
const int led = 13;
The digitalWrite() command ( on high and low ) in the infinite loop enables the LED to blink without interruption with the delay indicated in the code with the command delay()


Lesson 2 : Button
The button as well as the LED plugged onto the Arduino card are recognised thanks the to first two lines of the code. 
The button is initialised in the setup() command, so that when it is pressed for the first time the LED turns on and when it is pressed again the LED turns off.
The lines in the loop(), enable the action of turning on and off the LED when the pressing on the button


Lesson 5 : RGB LED
The three pin LED plugged on the card is recognised thanks to the first three lines of the code.
The loop() enables to display firstly the red color than after a delay the green color is displayed then another delay then blue etc.
