# 📦 Object Counter for Smart Inventory System

An embedded system project built to automate inventory tracking using an object-counting mechanism. Designed for warehouse management, the system uses photo-resistors and a 7-segment display to track the number of objects passing a point in real time — entirely through hardware logic without any code.

---

## 🚀 Project Overview

- **Objective**: To create a smart inventory system capable of accurately counting physical objects as they enter or leave a warehouse.
- **Technology Used**: 7-segment display, photo-resistors (LDRs), Arduino UNO (or equivalent microcontroller), resistors, jumper wires, breadboard.
- **Application**: Warehouse automation, smart logistics, and small-scale inventory control.

---

## 🔧 Features

- Real-time object counting through hardware logic.
- No software/code used.
- 7-segment display updates count instantly based on circuit design.
- Low-power and cost-effective hardware solution.
- Can be simulated using Tinkercad.

---

## 🛠️ Hardware Components

| Name   | Quantity | Component                 |
| ------ | -------- | ------------------------- |
| P1     | 1        | 5V / 5V Power Supply      |
| U1     | 1        | 4-Bit Binary Counter      |
| U2     | 1        | 7-Segment Decoder         |
| Digit1 | 1        | Cathode 7-Segment Display |
| R1     | 1        | Photoresistor (LDR)       |
| R2     | 1        | 10 kΩ Resistor            |
| R3     | 1        | 1 kΩ Resistor             |

---

## 🔌 Working Principle

1. **Object Detection**: Two photoresistors (LDRs) detect objects as they interrupt a light source.
2. **Counting Logic**: The hardware circuit is designed to trigger segment changes on object detection using voltage fluctuations caused by light obstruction.
3. **Display**: The count is reflected instantly on a 7-segment display.

---

## 📷 Demo

![Smart Inventory Object Counter](ObjectCounter.png)

> Tinkercad schematic and simulation visuals are included for reference.

---

## 🔗 TinkerCad Project

You can explore and simulate the full project online using TinkerCad:

👉 [Click here to view the Smart Inventory Object Counter Simulation](https://www.tinkercad.com/things/aOqf5CfyX0U-smart-inventory-object-counter?sharecode=I-SY-1Mum2-f5NgT69GxJfjr14PnG7c2jVqiquOmZgk)


## 🧪 How to Run

1. Open the circuit diagram image: `SchematicDiagram.png`.
2. Recreate the circuit using the provided connections **in Tinkercad**.
3. Once set up, simulate the circuit to observe the object counting mechanism in action.
4. You can find example screenshots and simulation visuals under the `Images/` folder.

> 💡 **Note**: No Arduino code is required. The system is built purely with hardware logic.

---

## 📝 Future Improvements

- Add microcontroller logic to enhance counting accuracy.
- Enable wireless data logging via Bluetooth/Wi-Fi.
- Implement a threshold alert system using buzzers or LEDs.
- Connect to cloud-based inventory dashboards in the future.

---

## 👩‍💻 Author

- **Shreya** – [https://github.com/shreya-13-04](https://github.com/shreya-13-04)

---

## 📜 License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more details.
