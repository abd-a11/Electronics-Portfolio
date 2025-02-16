# 💡 FL5150-Based Dimmable LED Driver (MOSFET Control)

## 🔹 Overview
This project is a **phase-cut dimmable LED driver** using the **FL5150** IC. Instead of a TRIAC, this design uses a **MOSFET** for power control, improving efficiency and enabling smoother dimming. The circuit controls the **AC signal phase shift** to regulate power for **LED drivers and dimmable loads**.

### Key Features:
- **AC Phase Control**: Adjusts power by modifying the AC waveform.
- **MOSFET Switching**: Provides **higher efficiency** and **faster response** than TRIAC-based designs.
- **Smooth Dimming**: Flicker-free brightness adjustment for LED drivers.
- **Supports Various Loads**: Works with **LED drivers and other phase-cut dimmable loads**.

---

## 🔹 Work Principle:
1. **Phase Detection**: The **FL5150** detects AC zero-crossing points.
2. **MOSFET Switching**: Instead of a TRIAC, a **MOSFET** is used to regulate power flow.
3. **Phase Cut Control**: The IC adjusts the conduction angle to modify power delivery.
4. **Smooth Dimming**: The MOSFET ensures a **precise and efficient** dimming response.

---

## 🔹 Schematic & PCB Design:
Here is the **schematic diagram** of the dimmable LED driver:  
![Schematic](./Images/fl5150_schematic.png)

Below is the **PCB layout**:  
![PCB Design](./Images/fl5150_pcb.png)

---

## 🔹 3D Model:
- **Top View**  
  ![Top View](./Images/fl5150_3d_top.png)

- **Side View**  
  ![Side View](./Images/fl5150_3d_side.png)

---

## 🔹 Why Use a MOSFET Instead of a TRIAC?
✅ **Higher Efficiency**: MOSFETs have lower conduction losses.  
✅ **Better Dimming Control**: More precise brightness adjustment.  
✅ **Less Heat Dissipation**: MOSFETs operate cooler compared to TRIACs.  
✅ **Works with Low Voltage LEDs**: Ideal for modern **LED driver circuits**.  

---

## 🔹 Applications:
- 💡 **Smart LED Dimming**: Used in **home automation and smart lighting**.
- 🏠 **Dimmable LED Drivers**: Efficiently controls **brightness levels**.
- 🏭 **Industrial Lighting Systems**: Provides precise power regulation.

---

## 🔹 Future Improvements:
- 🛠️ Integrate **wireless control** (Wi-Fi/Bluetooth) for remote dimming.
- 🔋 Implement **power factor correction (PFC)** for better efficiency.
- ⚡ Optimize **MOSFET gate drive circuit** for even smoother transitions.

---

## 🔹 License:
This project is open-source. Feel free to modify and improve it!

