# Maze-X PCB

KiCad design files for a Raspberry Pi Pico-based maze robot controller. The board brings together motor control, sensor headers, power input, user controls, and expansion connectors on a single PCB.

## Highlights

- Raspberry Pi Pico controller
- L298N dual H-bridge motor driver
- Connections for two motors
- Infrared sensor and I2C-style sensor headers
- XT60 battery input and 5 V regulation
- Slide power switch and push buttons
- M3 mounting holes

## Project Files

| File | Description |
| --- | --- |
| `maze-x.kicad_sch` | Schematic |
| `maze-x.kicad_pcb` | PCB layout |
| `maze-x.kicad_pro` | KiCad project configuration |
| `images/` | Schematic and board screenshots |
| `maze-x-backups/` | KiCad backup files |

## Preview

### Schematic

![Maze-X schematic](images/Screenshot%202026-08-28%20192353.png)

### PCB Layout

![Maze-X PCB layout](images/Screenshot%202026-08-28%20214920.png)

### 3D View

![Maze-X PCB 3D view](images/Screenshot%202026-08-29%20040457.png)

## Opening the Project

1. Install [KiCad](https://www.kicad.org/).
2. Open `maze-x.kicad_pro` in KiCad.
3. Use the Schematic Editor to inspect the circuit and PCB Editor to inspect the board layout.

## Design Challenge

The main challenge was fitting the complete design onto a single-layer PCB while working to a strict deadline. This constraint influenced the routing, component placement, and board footprint, and is one reason a multilayer revision is planned for future development.

## Future Improvements

- Move to a multilayer PCB for improved routing, power distribution, and signal integrity.
- Increase the number of time-of-flight (ToF) sensors for more detailed maze and obstacle detection.
- Reduce the board footprint by optimizing component placement and connector locations.

## Status

This repository contains the current design files and visual previews. Review the schematic, run electrical-rule checks, and verify the board with your intended components and fabrication requirements before ordering.