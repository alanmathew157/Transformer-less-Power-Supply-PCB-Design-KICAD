[![Made with KiCad](https://img.shields.io/badge/Made%20with-KiCad-blue?logo=kicad&logoColor=white)](https://www.kicad.org/)
# TRANSFORMER LESS POWER SUPPLY PCB Design using KICAD -ALTIMUM
## PCB TOP VIEW
![PCB TOP VIEW](Frontview.png)
## PCB BOTTOM VIEW
![PCB BOTTOM VIEW](Backview.png)

## Project Overview
This transformer-less power supply converts 220–240V AC mains into regulated 5V DC without using a step-down transformer by first passing the AC input through capacitor C4 (2.2µF), which acts as a capacitive dropper to limit current using reactance, while resistor R3 (1Ω) helps reduce inrush current and surges; the reduced AC voltage is then rectified by diodes D1–D4 (1N4007) arranged as a bridge rectifier to convert AC into pulsating DC, after which C2 (1000µF) smooths the low-frequency ripple and C1 (0.1µF) filters high-frequency noise to produce a cleaner DC supply; zener diodes D5 and D6 provide over-voltage protection, and resistors R1 and R2 (20kΩ) assist in biasing and stabilization, then the filtered DC is fed into the L7805 voltage regulator, which maintains a constant 5V output, while C3 (470µF) improves output stability and reduces ripple; finally, R4 (2.2kΩ) limits current to LED D7, which indicates power ON status, and the regulated 5V is available at the output terminal—however, since the circuit is directly connected to mains and has no isolation, it must be handled with extreme caution. This project is my attempt at learning KiCad and understanding the design and working of transformer-less power supply circuits.
