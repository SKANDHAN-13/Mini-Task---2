1.ELectronic chameleon:
A project to replicate the colour changing power of a chameleon on a lamp.
We begin by creating an electronic circuit which can take input as colour and give back the output as the same colour.
An important sensor used in the project is the RGB colour sensor TCS34725, which has clear light sensing elements.
The sensor has dynamic range with adjustable integration time and gain so it is suited for use behind darkened glass.


![alt text](https://hackster.imgix.net/uploads/attachments/1233310/ezgif_com-gif-maker_(1)_ZJY8XFZdxw.gif?auto=format%2Ccompress&gifq=35&w=900&h=675&fit=min&fm=mp4)


![alt text](https://hackster.imgix.net/uploads/attachments/1233313/contenteetimes-images-edn-leds-a19-led-bulb-leds-exposed_J9qNSIF0Bb.jpg?auto=compress%2Cformat&w=740&h=555&fit=max)



2.Electronic voting machine:
A project using Adafruit 8051 micro controller.
The vote count is stored in EEPROM and an LCD display is provided to display the total number of votes polled and individual contestant-wise votes polled.
An erase button is also provided in order to make sure the contents of the EEPROM is brought to zero, before the start of the polling process.
A buzzer is provided for audio effect of the switch press. Whenever a switch is pressed, the system acknowledges the press by a short beep sound.If a voter tries to poll multiple times a longer beep sound is generated.
There's a separate port is dedicated for 8 push-button switches for eight contestants, and a master switch for polling officer.

![alt text](https://hackster.imgix.net/uploads/attachments/937795/simulation2_vAPGF7DaTE.png) - Proteus connection outline of the project


3.Starpointer:
The project for astronomical telescopes that helps the observer identify objects in the sky.
The StarPointer is designed to work with Stellarium's telescope control plugin. Its firmware has been developed to work with the Meade LX200 communication protocol
This unit can be attached to the telescope. It communicates with the PC using the inbuilt USB peripheral of the STM32F103C8 microcontroller. 
The StarPointer uses a few onboard sensors to determine its angle and position { ADXL345 3-axis accelerometer and HMC5883L 3-axis magnetometer}. After obtaining that information, the unit calculates the RA (right ascension) and DEC (declination) coordinates of the telescope and transfers those details to the Stellarium


![alt text](https://hackster.imgix.net/uploads/attachments/1458774/dscn3860-mid_EEOosgRl6H.jpg?auto=compress%2Cformat&w=740&h=555&fit=max)

4.3-Axis Magnetometer:
The project measure the magnitude and direction of the earth’s magnetic field. 
It’s a low-power device and can be found in mobile phones or navigation systems to provide an accurate compass heading.
One can also use them to detect ferrous (contains iron) metals since the iron within the metal changes the magnetic field when it’s in close proximity to the sensor.
In order to communicate with the device, we use the I2C protocol which only uses two pins, SCL and SDA. We use this to configure the registers on the device (i.e., setting the measurement mode and output rate), and acquire the X, Y, and Z magnetic field measurements. The device can only be 7-bit addressed at 0x1E, so you cannot have more than one of these devices on the I2C bus at one time.
The SCL and SDA pins will connect to the Arduino uno analog pins A5 and A4, respectively.


5.Electronic code lock:
In this project, we are building 555 Timer IC based Code Lock which has 8 buttons and one needs to press specific four buttons simultaneously to unlock the Lock.The 555 IC is configured as a Monostable Vibrator here.
Basically in this circuit we will have an LED at the output pin 3 which turns ON when trigger is applied by pressing those specific four buttons. 
LED remains on for some time and then turns off automatically. The on time can be calculated with this 555 monostable calculator. 
The combination of specific four buttons is the “Code”, which needs to open the Lock.


![alt text](https://hackster.imgix.net/uploads/attachments/889184/555-timer-based-electronic-code-lock-circuit_KwMGO0Jwoy.jpeg?auto=compress%2Cformat&w=900&h=675&fit=min)
