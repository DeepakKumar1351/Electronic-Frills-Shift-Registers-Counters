# Electronic Frills using Shift Registers and Counters

## Project Overview
This Digital Logic Design Lab project demonstrates sequential lighting patterns using a 7×7 matrix of 49 red LEDs. The documented circuit uses a 555 timer in astable mode to generate clock pulses and three cascaded CD4017 decade counters to sequence the LED outputs.

The circuit was simulated in Proteus and assembled on a breadboard.

## Components
| Component | Specification | Quantity |
|---|---|---:|
| Timer IC | 555 | 1 |
| Decade counter IC | CD4017 | 3 |
| LEDs | 5 mm red | 49 |
| Capacitor | 100 µF | 1 |
| Resistor | 100 Ω | 1 |
| Power supply | 12 V battery | 1 |
| Breadboards | — | 2 |
| Jumper wires | — | Multiple |

## Working Principle
1. The 555 timer is configured in astable mode to produce a continuous clock signal.
2. The clock pulses drive the cascaded CD4017 decade counters.
3. The counter outputs activate LEDs in sequence to create a chaser-style lighting effect.
4. Timing components affect the clock rate and therefore the speed of the lighting sequence.

## Design and Testing
- Developed the circuit schematic in Proteus.
- Connected three CD4017 counters for sequential control.
- Arranged 49 LEDs in a 7×7 matrix.
- Simulated the timer and counter operation in Proteus.
- Assembled the circuit on a breadboard and tested the LED sequence.

## Applications
- Decorative and sequential lighting
- Moving-light displays
- Digital electronics demonstrations
- Learning clock generation and counter-based sequencing

## Repository Contents
- `README.md` — project overview, components, and working principle
- `report/ECE233_Electronic_Frills_Report.docx` — project report (add this file if it has not yet been uploaded)

## Implementation Note
Although the project title mentions shift registers, the supplied project details identify the 555 timer and CD4017 counters as the main sequencing components. No separate shift-register IC is specified here.

## References
1. CD4017 decade counter datasheet
2. 555 timer IC datasheet
3. Proteus Design Suite
4. Digital Logic Design laboratory materials
