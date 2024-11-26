# DIY LC Meter Project

This project demonstrates how to build a DIY LC Meter capable of measuring inductance (L) and capacitance (C) values using an Arduino Nano, an LM311 comparator, and a 16x2 LCD display. The LC Meter is designed to be simple, affordable, and effective for electronics enthusiasts and DIY hobbyists. It is suitable for learning about measurement principles while also being a practical tool.

## Project Highlights:

### 1 - Circuit Schematic
A detailed circuit diagram explains the working principle and interconnection of components such as the LM311 comparator, relay, calibration buttons, and measurement probes. The schematic provides a foundation for assembling the hardware.

### 2 - PCB Design
A professionally designed double-layer PCB created with KiCad ensures clean routing and minimizes interference. It includes detailed silkscreen labels for easy assembly and debugging.

### 3 - 3D Model
A realistic 3D representation of the completed PCB with components mounted, offering a clear view of the final product and component placement.

### 4 - Firmware
The Arduino Nano is programmed with custom firmware to calculate inductance and capacitance values. Measurements are displayed on a 16x2 LCD in real time.

### 5 - Calibration and Functionality
The project includes functionality for calibration, zeroing, and easy measurement. Buttons on the PCB allow users to fine-tune settings for accurate results.

### Features:
- Frequency Range: 88 MHz – 108 MHz
- Microphone input for real-time audio transmission
- LED power indicator
- Compact PCB design
- Easy to assemble

## Watch the Build Process

You can watch the full build process of this FM transmitter on my YouTube channel [**Teknotrek**](https://www.youtube.com/@TeknoTrek). Click the link below to see how the circuit is assembled, soldered, and tested:

[Watch on YouTube](https://youtu.be/xPGkkRPhaV4)


## Circuit Schematic

![FM Transmitter Schematic](https://raw.githubusercontent.com/TeknoTrek/Fm-Transmitter/refs/heads/main/images/fm-transmitter-circuit.jpg)

The circuit consists of the following key components:
- **Q1 (BC548)**: The main transistor used for signal amplification and modulation.
- **C3 (0-30 pF)**: A variable capacitor for tuning the frequency.
- **L1 (Coil)**: Works with C3 to set the oscillation frequency.
- **Microphone**: Captures the audio to be transmitted.
- **Antenna**: Transmits the modulated FM signal.

## PCB Layout

![PCB Layout](https://raw.githubusercontent.com/TeknoTrek/Fm-Transmitter/refs/heads/main/images/fm-transmitter-pcb.jpg)

The PCB layout is designed to be compact, with clear labels for easy assembly. The board supports through-hole components for easier soldering.

## 3D Model

![3D Model](https://raw.githubusercontent.com/TeknoTrek/Fm-Transmitter/refs/heads/main/images/fm-transmitter-pcb-3d-model.jpg)

<img align="center"  alt="PCB 3D Model" src="https://raw.githubusercontent.com/TeknoTrek/Fm-Transmitter/refs/heads/main/images/fm-transmitter-pcb-3d.jpg">

<img align="center"  alt="PCB" src="https://raw.githubusercontent.com/TeknoTrek/Fm-Transmitter/refs/heads/main/images/fm-transmitter-pcb-2.jpg">

A 3D model of the assembled PCB is included to give you a better idea of how the final product will look.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/TeknoTrek/fm-transmitter.git
   ```

2. Open the project in KiCad and review the schematic and PCB layout.

3. Assemble the components as per the schematic, solder them to the PCB, and tune the frequency using C3.

4. Attach a suitable antenna and power the transmitter using a 9V battery.

---

Let me know if you'd like to adjust any part of it!