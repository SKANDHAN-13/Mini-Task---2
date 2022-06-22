# ELECTRONIC LOCK WITH 555 TIMER

Sequence in which the lock functions -
* The lock has pushbuttons which take the input of set of four pushbuttons. The code is then compared by 555 timer for the right set of four pushbuttons.
* If the code is right then the lock opens for an interval that is indicated by the LED glowing up.
* If the circuit goes wrong , the sequence suggests fault in any one of these processes.

## Problem with pushbuttons :
The pushbutton may malfunction or be with a broken top. In order to ensure if the input is read by the timer, one can use a galvanometer across each of the buttons.

## Connection error with 555 timer :
Check if pin 4 is left floating as stray pulses may reset the chip although the reset pin (pin 4) is internally tied HIGH via approx 100k.

## Abnormalities with LED:
Checking if the threshold and proper functioning voltage values of LED are in line with circuit requirements.Moreover, it is necessary to check if the LED is not of poor quality and works well before it's used in the circuit.
