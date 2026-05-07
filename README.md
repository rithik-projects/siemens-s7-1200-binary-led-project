Siemens S7-1200 Binary Number LED Project

This project demonstrates a simple binary number indication system using a Siemens S7-1200 (CPU 1212C DC/DC/DC) PLC programmed in TIA Portal using Ladder Logic (LAD).

Two push buttons are used as binary inputs, and four LEDs indicate the corresponding binary state combinations.

| Input S1 | Input S2 | Output LED |
| -------- | -------- | ---------- |
| 0        | 0        | LED 1      |
| 0        | 1        | LED 2      |
| 1        | 0        | LED 3      |
| 1        | 1        | LED 4      |


Hardware Used:
Siemens S7-1200 CPU 1212C DC/DC/DC PLC
Push Buttons
24V LEDs
Connecting Wires
TIA Portal V19
24V DC Power Supply


Software:
Siemens TIA Portal
Ladder Logic Programming (LAD)


PLC Addressing:
Inputs
S1 → %I0.1
S2 → %I0.2
Outputs
LED1 → %Q0.1
LED2 → %Q0.2
LED3 → %Q0.3
LED4 → %Q0.4


Working Principle:

The PLC reads the status of two push buttons and performs binary combination logic using ladder logic conditions.

Depending on the input combination:

Only one corresponding LED glows
Each LED represents one binary state

This project helps beginners understand:

PLC digital inputs and outputs
Binary number concepts
Ladder logic implementation
Industrial automation basics
