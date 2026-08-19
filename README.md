# Adaptive Light-Triggered Alarm System Using Op-Amp Comparator Circuit

## About the Project

This is a hardware project that I worked on to detect changes in light intensity and give an alarm when the light level changes.

In this project, I used an LDR to sense the light. The signal from the LDR is given to an LM358 op-amp which is used as a comparator. Depending on the light level, the circuit turns the LED and buzzer ON or OFF.

## Components Used

- LDR
- LM358 Op-Amp
- Resistors
- Potentiometer
- LED
- Buzzer
- Transistor
- Breadboard
- 9V Battery
- Connecting wires

## Working

The LDR changes its resistance when the light falling on it changes. This produces a change in voltage in the circuit.

The LM358 compares this voltage with the reference voltage set using the potentiometer. When the light level crosses the set value, the output changes and the LED and buzzer are activated.

The potentiometer can be adjusted depending on the required light level.

## Hardware Implementation

This is the hardware setup that I built and tested.

![Hardware Implementation](Adaptive%20implementation%20image.jpeg)

## Result

I tested the circuit by changing the amount of light falling on the LDR. When the light level crossed the set limit, the LED turned ON and the buzzer produced an alarm.

The circuit worked as expected during the testing.


### Result Video
[▶️ Click here to view/download the result video](./result.mp4)
## Project Report

[📄 View Project Report](EXACT-FILENAME.pdf)

## Conclusion

This project helped me understand how an LDR can be used for light sensing and how an op-amp can be used as a comparator.

I also got practical experience in connecting the components on a breadboard and testing the circuit with a battery.

