# Simulation

The heat control system is implemented in Embedded C program and the working is demonstrated using SimulIDE software.


## Problem statement

<img width="636" alt="ps" src="https://user-images.githubusercontent.com/89584926/133641534-decdda5d-5b5e-4096-8e24-c934256c1393.png">


## Functionality
* When the two buttons (switches) are closed, the LED glows indicating the actuation of the system and the heater.
* Next the analog input from the temperature sensor is received and digitized.
* The digitized temperature input is visualized using Pulse Width Modulation.

# Activity 1
* Button sensor will check whether a person is seated or not.
* LED Actuator shows whether a person is seated or not.
* Heater will check whether heater is turned ON or not.
* The heater can be turned ON or OFF using a switch when the seat is occupied and the same status is shown using LED.


## case-1

Button switch is OFF and heater switch is OFF so the LED is OFF

![case1](https://user-images.githubusercontent.com/89584926/133650558-5b247a64-58df-4917-8535-18c55fbfe73b.PNG)

## case-2

 Button switch is OFF and heater switch is ON so  the LED is OFF

![case2](https://user-images.githubusercontent.com/89584926/133650599-3025e045-d516-4cf2-bc27-37d43f33570d.PNG)

## case-3

 Button switch is ON and heater switch is OFF so the LED is OFF
 
![case3](https://user-images.githubusercontent.com/89584926/133650643-bfb664d0-80d4-4f12-bcfb-4694fdfaca32.PNG)

## case-4

 Button switch is ON and heater switch is ON so the LED is ON

![case4](https://user-images.githubusercontent.com/89584926/133650670-838df9b6-38b8-4891-a1be-4c9c25e8a05c.PNG)


# Activity 2
Potentiometer is used as a temperature sensor to read the temperature values and convert the Analog values obtained from the sensor to Digital values.

![case21](https://user-images.githubusercontent.com/89584926/133652773-1137da6f-4e5c-4ace-a697-5618593b1fb5.PNG)

# Activity 3
Temperature value is displayed by showing PWM signal from a temperature sensor (Potentiometer)

![Act3](https://user-images.githubusercontent.com/89584926/133661703-a1d52cd6-9ea0-4a8f-b4ac-f873234b42f8.png)



