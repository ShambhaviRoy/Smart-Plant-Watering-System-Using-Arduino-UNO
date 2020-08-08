# Smart Plant Watering System Using Arduino UNO
Developed a smart plant watering system which measures humidity of the soil to water plant without user intervention. This system notifies the user about dry soil or flood condition to user by SMS.

Hardware Components:
Arduino UNO

Soil Moisture sensor: The soil moisture sensor module used here has two output pins (digital output and analog output). The output from the probe of the moisture sensor is compared with a reference value using a LM393 comparator. The reference value can be changed by turning the potentiometer in the module. The digital pin gives an active low output when the soil is wet. Here we are using the analog output from the module by connecting it to one of the analog pins of Arduino. While using the analog output the wet detection value can be set/ adjusted within the program itself. The formatter will need to create these components, incorporating the applicable criteria that follow.

LEDs:These are used to indicate the status of the situations taking place like the detection of moisture and so on.

NodeMCU: It is used to send SMS alerts to user when plant needs watering
A motor can be connected to water plants as needed.

Conclusion:
In this project of automatic plant watering system, we aim to find the moisture content of soil using the soil moisture sensing module connected to Arduino UNO Board. The connected motor is switched on when the moisture is detected below the set limit. When the moisture level rises above the specified level, the pump is switched off.
