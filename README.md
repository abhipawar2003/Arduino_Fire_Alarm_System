# Arduino_Fire_Alarm_System

Abstract

![image](https://github.com/abhipawar2003/Arduino_Fire_Alarm_System/assets/112234264/e35a8c7a-22c8-4068-8b88-d08f2044d47b)


In commercial buildings fire alarms are a necessity.
Normal fire alarms constantly monitor the surroundings for heat, flame, and smoke in case of a fire.
Our fire detection utilizes a Flame sensor and MQ 2 Gas Sensor

components

Arduino Uno	× 1	

Arduino UNO is a microcontroller board. It has 14 digital input/output pins, 6 analog inputs, a USB connection, a power jack, an ICSP header and a reset button. It contains everything needed to support the microcontroller.
Connecting it to a computer with a USB cable or power it with a AC-to-DC adapter or battery will get it started.

Flame Sensor× 1	

A flame-sensor is one kind of detector which is mainly designed for detecting as well as responding to the occurrence of a fire or flame. The flame detection response can depend on its fitting. It includes an alarm system, a natural gas line, propane & a fire suppression system.

MQ-2 Gas & Smoke Sensor× 1

The MQ2 sensor is one of the most widely used in the MQ sensor series. It is a MOS (Metal Oxide Semiconductor) sensor. Metal oxide sensing is based on the change in resistance of the sensing material when exposed to gasses.
Breadboard× 1
A breadboard is a construction base used to build semi-permanent prototypes of electronic circuits. 	

Jumper wires kit	× 1	

A jumper wire is an electric wire that connects remote electric circuits used for printed circuit boards. By attaching a jumper wire on the circuit, it can be short-circuited and short-cut (jump) to the electric circuit.

Green LED × 1

A green light-emitting diode is a semiconductor light source

Resistor Kit	× 1

A passive electrical component with two terminals that are used for either limiting or regulating the flow of electric current in electrical circuits.

Buzzer	×2	

A buzzer or beeper is an audio signaling device. It may be piezoelectric.
USB cable type A/B
USB A-Type: This is the standard rectangulat female port found on computers.
USB B-Type:Most USB 2.0 printer cables, scanner cables and some external hard drive cables are B-type connectors

Circuit Diagram

![image](https://github.com/abhipawar2003/Arduino_Fire_Alarm_System/assets/112234264/7d2168c0-81a5-413c-9887-294f0c9deeef)

working

The flame sensor module has a photodiode for light detection and an op-amp for sensitivity monitoring. It is used for fire detection and makes a HIGH signal. Arduino detects the signal and alerts the buzzer by turning it on. The flame sensor utilized is a flame sensor based on IR.

The MQ 2 sensor has an electrochemical sensor that varies its resistance to different flammable gas concentrations. The sensor is connected to a voltage divider circuit in series with a variable resistor, and the variable resistor is used to change sensitivity. When flammable gaseous elements come into contact with the sensor, it is heated. As a result, the sensor’s resistance changes. The voltage across the sensor changes as the resistance changes and this value can be read by a microcontroller. Here Arduino read the value and turning on the buzzer .



