# BCD Counter with 7-Segment Display and LED Output

**This repository contains the report for a BCD (Binary-Coded Decimal) Counter project developed as part of the Digital Logic Design class at AAST (Arab Academy for Science, Technology & Maritime Transport). The project explores the design and implementation of a digital logic circuit that counts from 0 to 9 in BCD format, displaying the decimal value on a 7-segment display and the corresponding binary value on four LEDs.**

## Features

- Counts from 0 to 9 in BCD format
- Displays decimal output on a common-cathode 7-segment display
- Shows binary equivalent on four LEDs
- Includes a push-button for manual reset
- Simulated in TinkerCAD
- Implemented on a breadboard with standard ICs
- Bilingual documentation (English/Arabic)

## Components

| Component                     | Description                          | Quantity |
|-------------------------------|--------------------------------------|----------|
| IC 74LS74                     | Dual D Flip-Flops                    | 1        |
| IC 7402                       | Quad NOR Gate                        | 1        |
| IC 7493                       | 4-Bit Binary Counter                 | 1        |
| IC 7447                       | BCD to 7-Segment Decoder             | 1        |
| Resistor 100k ohm             |                                      | 1        |
| Resistor 1k ohm               |                                      | 11       |
| 7-Segment Display (Common Cathode) |                                  | 1        |
| Push Button                   |                                      | 1        |
| Standard LED                  |                                      | 4        |
| Connecting Wires              |                                      | As needed |
| Power Supply (5V, 5A)         |                                      | 1        |

## Setup Instructions

### TinkerCAD Simulation

1. Open the TinkerCAD circuit
2. Verify the connections for the 74LS74, 7402, 7493, and 7447 ICs
3. Connect the 7-segment display and LEDs to the appropriate pins
4. Add resistors (1k ohm for LEDs/display, 100k ohm for push-button)
5. Simulate the circuit by clicking "Start Simulation"
6. Press the push-button to reset the counter

### Breadboard Implementation

1. Gather all components listed above
2. Follow the schematic provided in the report
3. Connect the power supply (5V) and ground
4. Test the circuit by powering it on
5. Press the push-button to reset and observe counting

## Usage

- **Reset**: Press the push-button to reset the counter to 0
- **Counting**: The counter increments automatically or manually
  - 7-segment display shows decimal (0-9)
  - LEDs show binary equivalent

### Troubleshooting

- If display shows incorrect digits: Check 7447 IC connections
- If counter behaves erratically: Verify push-button debouncing
- If components don't power on: Check 5V power supply stability

## Project Report Contents

1. Introduction to BCD Counter functionality
2. Detailed component list and roles
3. Logic expressions for all ICs
4. Design process (TinkerCAD + breadboard)
5. Bilingual explanations (English/Arabic)

### Collaborator
[Ahmed Mahmoud](https://github.com/ahmedmahmoud232)


