# Breadboard Power Supply (5V / 3.3V) — KiCad Project

A beginner-friendly breadboard power supply PCB design (5V selectable / 3.3V) created in KiCad 6/7/9.

## Contents
- `project_files/` — KiCad schematic & PCB files
- `gerbers/` — gerber files for fabrication (ZIP)
- `bom/` — Bill of Materials and pick-and-place
- `docs/` — screenshots, 3D renders, thumbnails
- `hardware/` — assembly notes & test procedure

## Features
- Input: 9–12V DC (barrel jack)
- Outputs: Selectable 5V or 3.3V via jumper
- Input fuse, power LED, regulator indicators
- AMS1117 regulators (changeable to switching regulator for >500 mA)
- KiCad project + gerbers included

## How to open
1. Install KiCad (https://kicad.org)  
2. Open `project_files/power_supply.kicad_pro`

## Build & Test
- Generate Gerber files from KiCad: `File → Fabrication Outputs → Gerbers`
- Assemble using BOM in `bom/bom.csv`
- Power up with a current-limited bench supply and verify rails with a multimeter

## License
This project is licensed under the MIT License — see `LICENSE`.

## Contributing
PRs and issues welcome. Please include changes to BOM or schematic with a short explanation.

