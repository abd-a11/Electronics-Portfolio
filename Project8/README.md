# Electronic Speed Controller (ESC)

This project is an **Electronic Speed Controller (ESC)** designed for driving Brushless DC (BLDC) motors.  
It integrates an **STM32Fxxx microcontroller** with the **DRV8302 MOSFET driver** to provide efficient and precise motor control.

---


## Features
- **MCU:** STM32Fxxx series (ARM Cortex-M)  
- **Driver IC:** Texas Instruments DRV8302 (3-phase MOSFET driver)  
- Supports 3-phase BLDC motors  
- Integrated current and voltage sensing  
- PWM-based motor control  
- Overcurrent and thermal protection  
- Flexible power stage with external MOSFETs  

---

## Hardware Overview
- **Microcontroller (STM32Fxxx)**  
  Handles control algorithms, communication, and safety features.  

- **DRV8302 MOSFET Driver**  
  Provides gate drive for high- and low-side MOSFETs.  
  Includes current shunt amplifiers and protection circuitry.  

- **Power Stage**  
  External MOSFETs for 3-phase BLDC motor control.  

- **Sensing**  
  - Current sensing via low-value shunt resistors (VSENSE)  
  - Voltage feedback for monitoring and protection  

---

## Applications
- Electric skateboards  
- Drones and UAVs  
- RC cars and boats  
- Robotics projects  
- Other BLDC motor control systems  

---
Sheets Schematic Diagram:
![Schematic Preview](../Project8/Library/sheets-page.PNG)

---
Block Diagram:

![Schematic Preview](../Project8/Library/block-diagram.PNG)

---
INPUT PROTECTION:
![Schematic Preview](../Project8/Library/input-protection.PNG)

---
STEP DOWN:
![Schematic Preview](../Project8/Library/step-down.PNG)

---
MCU Schematic STM32F4:

![Schematic Preview](../Project8/Library/MCU.PNG)

---
DRV8302 MOSFET Driver Schematic:
![Schematic Preview](../Project8/Library/MOSFET_DRIVER.PNG)

---
MOSFET's
![Schematic Preview](../Project8/Library/MOSFETS.PNG)

---
CAN BUS:

![Schematic Preview](../Project8/Library/CAN.PNG)

---
FILTER:

![Schematic Preview](../Project8/Library/filters.PNG)

---
USB CONNECTOR:

![Schematic Preview](../Project8/Library/USB.PNG)

____________________________________________________________________________________________________________________________________________________________________

## PCB AND LAYOUT LEVEL:
![Schematic Preview](../Project8/Library/Final-Drawing.PNG)


## 3D View:

![Schematic Preview](../Project8/Library/3D-Front.PNG)
![Schematic Preview](../Project8/Library/3D-Rear.PNG)
