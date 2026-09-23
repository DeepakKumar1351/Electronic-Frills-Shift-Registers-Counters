[README.md](https://github.com/user-attachments/files/32573157/README.md)
# Electronic-Frills-Shift-Registers-Counters# Electronic Frills using Shift Registers and Counters

## Project Overview
This Digital Logic Design Lab project demonstrates how basic digital ICs can generate animated lighting patterns across a 7×7 LED matrix. The circuit uses a 555 timer in astable mode to produce clock pulses and three cascaded CD4017 decade counters to sequence the LED outputs.

The design was simulated in Proteus and then assembled and tested on a breadboard.

## Main Components
| Component | Specification | Quantity |
|---|---|---:|
| Timer IC | 555 | 1 |
| Decade counter | CD4017 | 3 |
| LEDs | 5 mm red | 49 |
| Capacitor | 100 µF | 1 |
| Resistor | 100 Ω | 1 |
| Power supply | 12 V battery | 1 |
| Breadboard | — | 2 |
| Jumper wires | — | Multiple |

## Working Principle
1. The 555 timer is configured in astable mode to generate a continuous clock signal.
2. The clock pulses are applied to cascaded CD4017 decade counters.
3. The counters produce sequential output signals that control the LED matrix.
4. The sequence creates moving or chaser-style lighting effects.
5. The timing components can be adjusted to change the pulse rate and visible animation speed.

## Design and Testing
- Created the schematic in Proteus.
- Connected three CD4017 counters for extended sequencing.
- Arranged 49 LEDs in a 7×7 matrix.
- Checked timer pulse generation and counter sequencing in simulation.
- Assembled the circuit on a breadboard and adjusted timing for visible effects.
- Tested the LED sequence and checked for stable operation.

## Applications
- Decorative lighting and stage effects
- Moving-light signboards
- Educational digital electronics demonstrations
- Logic-based timing and sequence control
- Light-based art installations

## Repository Contents
- `README.md` — project overview and operation
- `report/ECE233_Electronic_Frills_Report.docx` — original project report

## Notes
The project report describes the circuit as using a 555 timer and CD4017 counters. It does not identify a separate shift-register IC, so this README follows the documented implementation.

## References
1. CD4017 Decade Counter datasheet (Texas Instruments)
2. 555 Timer IC datasheet (Texas Instruments)
3. Proteus Design Suite
4. Digital Logic Design lectures and laboratory experience
