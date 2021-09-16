# Requirements

## Introduction
The heat control system is used to control the temperature of the car seat. When a person gets seated on a car, the button sensor will be activated. After that, the user gets access to turn ON the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a microcontroller called Atmega328.


## Components used-
* ATmega328 microcontroller 
* temperature sensor (Potentiometer)
* Switches(button)
* LED 
* LCD diplay


## Features
* The System will be able to tell whether a person is seated or not.
* A person once seated gets the access to turn ON the heater.
* The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller.


## SWOT - Strengths, Weakness, Oppurtunities and Threats
### Strengths
- Easy accessibility.
- User friendly.
- Proper allocation of area.
- Maintaining the information of vehicles parked before.
- Amount to be paid can also be monitored.

### Weakness
- It needs few secured connection.
- Simple C code.

### Oppurtunities
- Few features can be added to make the project more robust, by making few changes.
- Can add identification of vehicle through number plates.
- Can use different languages to make an efficient code.

### Threats
- User must provide proper input value as provided in the options for proper execution.

## 4W's and 1H
* **What** - Parking Management System
* **Where** - In Malls, Restaurents, Function Halls
* **When** - Gettogethers, Meetings, Functions
* **Why** - To create traffic free parking areas
* **How** - By information provided by the user

## Detail Requirements
### High Level Requirements
| High Level Requirements      | Description |
| ----------- | ----------- |
| HLR1 | Microcontroller unit    |
| HLR2 | Switches |
| HLR3 | Temperature sensor |
| HLR4 | Heater |
| HLR5 | Display |

### Low Level Requirements
| Low Level Requirements      | Description |
| ----------- | ----------- |
| LLR1      | Add List of Vehicles     |
| LLR2   | Capacity|
| LLR3   | View Amount to be paid |
| LLR4   |View Previous Vehicles information |
| LLR5   | Get Data / Exit |

