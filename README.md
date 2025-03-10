# Fridge Temperature Tester

A KiCad project for testing fridge cooling element temperatures. This project contains the schematic and PCB design files for a temperature monitoring system that can be attached to the back of a fridge's cooling element to monitor its performance.

## Features

- High-precision temperature monitoring using DS18B20 digital temperature sensor
- Arduino Nano-based control system
- Operating range: -55°C to +125°C
- Accuracy: ±0.5°C
- USB interface for easy data logging and monitoring
- Compact PCB design (100mm x 50mm)

## Project Structure

- `Fridge_Temperature_Tester.sch` - KiCad schematic file
- `Fridge_Temperature_Tester.kicad_pcb` - PCB layout file

## Hardware Requirements

- Arduino Nano V3.x
- DS18B20 temperature sensor (waterproof version recommended)
- 4.7kΩ resistor
- USB cable for Arduino Nano
- Thermal paste or thermal adhesive tape

## Assembly Instructions

1. Fabricate the PCB using the provided KiCad files
2. Solder components according to the schematic:
   - Arduino Nano
   - DS18B20 temperature sensor
   - 4.7kΩ pull-up resistor
3. Apply thermal paste to the DS18B20 sensor
4. Attach the sensor to the fridge cooling element
5. Connect the Arduino Nano via USB

## Development

This project is developed using KiCad 7.x. To modify the project:

1. Install KiCad 7.0 or later
2. Open the `.sch` file in KiCad Schematic Editor
3. Open the `.kicad_pcb` file in KiCad PCB Editor

## License

Open source hardware - feel free to modify and use as needed.

## Author

Created by Chris Boden at Peregian Digital Hub 