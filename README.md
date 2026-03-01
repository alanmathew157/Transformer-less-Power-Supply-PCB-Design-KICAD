[![Made with KiCad](https://img.shields.io/badge/Made%20with-KiCad-blue?logo=kicad&logoColor=white)](https://www.kicad.org/)
# TRANSFORMER LESS POWER SUPPLY PCB Design using KICAD -ALTIMUM
## PCB TOP VIEW
![PCB TOP VIEW](Frontview.png)
## PCB BOTTOM VIEW
![PCB BOTTOM VIEW](Backview.png)

## Project Overview
This project is a transformerless power supply designed in KiCad as part of my PCB design learning journey. Instead of using a bulky step-down transformer, the circuit employs a capacitive dropper (C4) to limit the AC current from the mains supply. The series resistor helps limit inrush current and improve safety. The reduced AC signal is then rectified using a full-wave bridge rectifier composed of four 1N4007 diodes, converting it into pulsating DC. Filter capacitors (C1, C2, and C3) smooth the rectified voltage by reducing ripple. Zener diodes provide voltage clamping and protection against overvoltage conditions. Finally, an LM7805 linear voltage regulator produces a stable 5V DC output suitable for low-power electronic applications. An LED indicator with a current-limiting resistor confirms the presence of output voltage.
