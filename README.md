# Arduino-automatic-irrigation-system
Arduino project using relay module , soil moisture sensor , arduino uno .

##  Overview
This project demonstrates an *Automatic Irrigation System* developed using an Arduino Uno, a soil moisture sensor, a photosensitive (light) sensor module, and a relay module.

The system automatically monitors soil moisture levels and controls irrigation to ensure that plants receive the right amount of water.

###  Objective
•⁠  ⁠Automate plant watering  
•⁠  ⁠Reduce water wastage  
•⁠  ⁠Enable efficient plant care using embedded systems  

---

##  Components Used
•⁠  ⁠Arduino Uno  
•⁠  ⁠Soil Moisture Sensor  
•⁠  ⁠Photosensitive Sensor Module (Light Sensor)  
•⁠  ⁠Relay Module  
•⁠  ⁠Water Pump  
•⁠  ⁠Jumper Wires  
•⁠  ⁠Power Supply  

---

##  Working Principle
The system continuously monitors soil moisture using the sensor.

•⁠  ⁠When moisture falls *below a threshold*:
  - Arduino activates the relay
  - Water pump turns *ON*

•⁠  ⁠When moisture reaches *sufficient level*:
  - Arduino deactivates the relay
  - Water pump turns *OFF*

Additionally:
•⁠  ⁠A *light sensor* detects ambient light
•⁠  ⁠Irrigation can be restricted to specific lighting conditions (e.g., daytime only)

---

##  Features
•⁠  ⁠Automatic soil moisture monitoring  
•⁠  ⁠Intelligent irrigation control  
•⁠  ⁠Water conservation  
•⁠  ⁠Simple and cost-effective design  
•⁠  ⁠Suitable for small-scale use  

---

##  Applications
•⁠  ⁠Smart agriculture systems  
•⁠  ⁠Home gardening automation  
•⁠  ⁠Greenhouse plant care  
•⁠  ⁠Agricultural water management  

---

##  Circuit Diagram
	 
The diagram should include:
•⁠  ⁠Arduino Uno  
•⁠  ⁠Soil moisture sensor  
•⁠  ⁠Light sensor  
•⁠  ⁠Relay module  
•⁠  ⁠Water pump  

---

## Basic Wiring Reference

| Component                  | Connection                          |
|--------------------------|------------------------------------|
| Soil Moisture Sensor     | Analog Pin (A0)                    |
| Light Sensor             | Analog Pin (A1)                    |
| Relay Module             | Digital Pin (D7)                   |
| Water Pump               | Connected via Relay Module         |


##  Future Improvements
•⁠  ⁠IoT integration for remote monitoring  
•⁠  ⁠Mobile app control  
•⁠  ⁠Soil moisture data logging  
•⁠  ⁠Solar-powered system  

---

## 👤 Author
*Ansh Rai*
