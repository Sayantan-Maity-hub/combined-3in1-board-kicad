# combined-3in1-board-kicad
This repository contains a simple 3-in-1 hardware board designed using KiCad, combining three commonly used embedded hardware blocks:

🔧 1. Temperature Sensor Section (LM35)

The LM35 temperature sensor generates an analog output proportional to temperature.
Includes:

LM35 sensor

10k pull-down/bias resistor

Clean analog output for conditioning by the op-amp section

🔧 2. Op-Amp Signal Conditioning (LM358)

Used to amplify and filter the LM35 signal before feeding into a microcontroller or ADC.
Includes:

LM358 dual op-amp

Gain-setting resistors (10k & 22k)

Configured for single-supply amplifier use

Ideal for temperature sensing, control loops, or analog pre-processing

🔧 3. Motor Driver (H-Bridge / MOSFET Stage)

A simple MOSFET-based driver section to run a small DC motor from microcontroller PWM.
Includes:

Two IRLZ44N logic-level MOSFETs

Flyback diode (1N4148) for motor protection

Supports PWM control for speed regulation

📁 Project Files

Inside this repository you will find:

combined_3in1_board.kicad_sch   → Full KiCad schematic
README.md                        → Documentation


This project is meant for learning and practice with:

Analog circuits

Op-amp signal conditioning

Power electronics / MOSFET driving

KiCad schematic design

🚀 How to Use

Clone the repo or download as ZIP.

Open the .kicad_sch file in KiCad 6+.

Modify or extend the circuit as needed (add PCB layout, footprints, etc.).

🛠 Tools Used

KiCad (schematic design)

LTSpice / Falstad (simulation concepts)

Basic analog & power electronics principles

📌 License

Open-source — feel free to modify and build upon it.
