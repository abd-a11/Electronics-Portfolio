# 🌟 Stair LED Control System with Proximity Sensor

## 🔹 Overview
This project automates **LED lighting on stairs** using a **VCNL4200 proximity sensor** and an **ATTiny microcontroller**. When movement is detected near the stairs, the LEDs gradually turn on, improving **visibility and energy efficiency**.

### Key Features:
- **Proximity-Based Activation**: LEDs turn on when a person approaches.
- **Smooth LED Control**: Fades in and out for a pleasant effect.
- **Low Power Consumption**: Uses an **LP2985 Low-Dropout Regulator** for efficiency.
- **Logic Control**: **SN74LV1T32DBVRG4** logic gate ensures reliable signal processing.

---

## 🔹 Work Principle:
1. **VCNL4200 Sensor Detection**: Senses movement using **infrared proximity sensing**.
2. **ATTiny Microcontroller**: Processes the signal and controls the LED lighting sequence.
3. **MOSFET or LED Driver (if used)**: Switches LEDs with **PWM dimming** for smooth transitions.
4. **LP2985 LDO Regulator**: Supplies stable power to the microcontroller and sensor.

---

## 🔹 Schematic & PCB Design:
Here is the **schematic diagram** for the stair LED control system:  
![Schematic](./Images/stair_led_schematic.png)

Below is the **PCB layout**:  
![PCB Design](./Images/stair_led_pcb.png)

---

## 🔹 3D Model:
- **Top View**  
  ![Top View](./Images/stair_led_3d_top.png)

- **Side View**  
  ![Side View](./Images/stair_led_3d_side.png)

---

## 🔹 Applications:
- 🚶‍♂️ **Smart Stair Lighting**: Enhances safety and aesthetics.
- 🏠 **Home Automation**: Energy-efficient automatic lighting.
- 🏢 **Office & Commercial Spaces**: Provides modern motion-based stair illumination.

---

## 🔹 Future Improvements:
- 🛠️ Add **multiple sensors** for more accurate stair detection.
- ⚡ Integrate **wireless control** for remote operation.
- 🔋 Use a **battery-powered version** for off-grid applications.

---

## 🔹 License:
This project is open-source. Feel free to modify and improve it!

