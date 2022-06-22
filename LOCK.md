# ELECTRONIC LOCK USING 555 timer

## Problem statement : 
Building a code lock that opens when a specific set of four buttons are pressed, without any microcontroller.

## Ideation and planning :

* Understanding the functioning of 555 timer IC in the project as monostable multivibrator and calculator.
* The LED represents the "Electric Lock" here which remains locked when there is no current and gets unlocked when current passes through it.
* Capacitor between PIN6 and ground has a capacitance that determines the turn on time of LED, once a trigger is passed.

## Part of the pipeline is as follows :

| Part of the pipeline | Feasibility | Advantages | Disadvantages |
|----|----|----|----|
| 555 timer as monostable vibrator and calculator | It is easy to buy and simpler to comprehend the circuit setup and working of the IC as a time delay in the circuit | Useful in producing time delay in the circuits & pulse generation | May require high value of resistance for higher value of time constant => delay and duty cycle has a high power dissipation |
| LED as electronic lock indicator | Simple to buy and include in the circuits | It indicates the time for which the lock remains unlocked (or the time for which current passes though the circuit) | No disadvantages |
|Capacitor to maintain turn on time of LED | It is simpler to integrate with the circuit | It charges when trigger is pressed and goes to peak capacity during the time when the door remains open |  May require high value of resistance for higher value of time constant => delay|

## Choosing a pipeline :

From the above, we can begin with 555 timer as a monostable calculator. The circuit assembly requires capacitor for both the aforementioned purpose and stable voltage as well. Hence, we require right value of capacitance, resistance to be used. Moving on, LED of appropriate voltage junction potential is required. 

## Prototyping phase :

The phase to assemble the circuit with proper connections to 555 timer, bread board and the other components.The LED & pushbuttons can be integrated to their respective positions, after that.

We might encounter circumstances where the LED , pushbuttons or capcitor may be improperly functioning. There are possibilities of using a higher voltage input than the prescribed range , which can damage the circuit. 
 
