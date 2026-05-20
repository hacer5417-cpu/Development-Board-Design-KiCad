# Custom STM32 Development Board Design 🛠️

An open-source, custom STM32 microcontroller development board designed from scratch using **KiCad**. This project covers the entire hardware development lifecycle, including schematic capture, component selection, power management design, two-layer PCB layout routing, and 3D visualization.

---

## 📸 Hardware Gallery & Visuals

### 1. Schematic Design & Architecture
<img width="850" height="572" alt="image" src="https://github.com/user-attachments/assets/c0ca23ad-6389-4770-b6c0-bf3ab891786e" />


*Clean and structured schematic diagram featuring the STM32 microcontroller pinouts, crystal oscillators, decoupling capacitors, peripheral interfaces, and voltage regulation circuit.*

### 2. 3D Model View (Top Side)
![Top View](https://github.com/user-attachments/assets/22cc8107-48d1-4b13-a626-07a26d4fc03d)

*3D rendering of the populated top side, showcasing component alignments, RGB status LED, push buttons, micro-USB interface, and peripheral headers.*

### 3. 3D Model View (Bottom Side)
<img width="806" height="533" alt="image" src="https://github.com/user-attachments/assets/372e9d3b-d23f-4aca-896f-c6df0633e819" />


*3D rendering of the bottom side, featuring the power management component placement, ground planes, and custom silkscreen branding.*

---

## ⚡ Technical Specifications & Features

* **EDA Tool:** KiCad (Schematic Capture & PCB Layout)
* **Microcontroller:** STM32 Series (LQFP-48 Package)
* **Power Management:** On-board low-dropout (LDO) voltage regulator circuit with proper filtering capacitors for stable operation.
* **Signal Integrity:** Designed with short return paths, clear ground plane separation, and optimized routing for high-frequency (HSE) and low-frequency (LSE) crystal oscillators.
* **UI & Peripherals:** Integrated Reset/User buttons, an RGB LED indicator, boot mode configuration jumpers, and easily accessible breakout headers for all GPIOs.
* **Aesthetics:** Custom silkscreen layer layout featuring personalized branding.

---

## 🚀 Future Enhancements
* Automated hardware validation and basic firmware testing (Blinky, UART communication).
* Designing an external enclosure model using CAD tools.
