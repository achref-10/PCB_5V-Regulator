
# 🔌 5V Voltage Regulator Mini Project

This project demonstrates how to build a simple **5V voltage regulator circuit** using the **LM7805 linear voltage regulator**, **capacitors**, and a **Schottky diode**. You’ll also learn how the circuit works, how to design and order your own **PCB**, and how to **solder** the components together.

---

## 📷 Preview

![5V Regulator Circuit]([5V Regulator Circuit.png](https://github.com/achref-10/PCB_5V-Regulator/blob/f0bc8fdec7d37055a307acca891646a1e02ef2de/5V%20Regulator%20Circuit.png))

---

## ✅ Features

- Regulates input voltage down to a stable 5V output
- Protects against reverse polarity using a Schottky diode
- Includes input/output capacitors for voltage smoothing
- Custom-designed PCB for compact integration
- Step-by-step guide for soldering and assembling

---

## 🧰 Components Used

| Component          | Quantity |
|-------------------|----------|
| LM7805 Regulator   | 1        |
| Schottky Diode     | 1        |
| 10μF Capacitor     | 2        |
| PCB (custom design)| 1        |
| Headers / Connectors | optional |

---

## 🛠️ How It Works

The **LM7805** linear voltage regulator accepts an input voltage (7V–20V) and outputs a **constant 5V**. The capacitors smooth input and output voltages, and the **Schottky diode** protects against incorrect polarity connection.

---

## 🔧 Getting Started

### 1. 🧪 Test on Breadboard

Before soldering:
- Connect the LM7805 as per the circuit diagram
- Use capacitors on input and output
- Check voltage output with a multimeter

### 2. 🖥️ Design the PCB

Designed using [KiCad] / [EasyEDA] / [Altium] (edit this with your tool).
- Export Gerber files
- Order from PCB manufacturers (e.g., JLCPCB, PCBWay)

### 3. 🔩 Assemble & Solder

- Carefully solder the components
- Start with smaller parts (diode, resistors), then the LM7805
- Test final output voltage

---

## 📁 Project Files

- `schematic.pdf` – Circuit diagram
- `PCB_Gerber.zip` – Gerber files for PCB manufacturing
- `regulator.kicad_pcb` – Editable PCB project (if applicable)

---

## 🧪 Testing & Use Case

- Test with a 9V or 12V input supply
- Output should stay close to 5.0V under moderate load
- Can be used to power sensors, microcontrollers (Arduino, ESP32, etc.)

---

## 📦 How to Order a PCB

1. Go to [JLCPCB](https://jlcpcb.com) or any other PCB manufacturer
2. Upload `Gerber.zip`
3. Choose quantity, color, thickness, etc.
4. Place the order and wait for delivery

---

## 📬 Contact

Created by [Achref Abdellaoui](https://github.com/achrefabdellaoui)  
If you have any questions or want to contribute, feel free to reach out!

---

## 📄 License

This project is open-source under the MIT License – feel free to use, modify, and share.
