# Solar-sail

Light-Seeking Solar Sail Mechanism is an Arduino-based prototype designed to demonstrate autonomous light tracking and solar-sail attitude control. The system uses four photoresistors positioned around the sail to determine the direction and relative intensity of a light source, then drives servo motors to adjust the sail's horizontal and vertical orientation. A third servo controls sail deployment, allowing the system to remain compact while searching and deploy once the light source is properly aligned. The project explores feedback control, sensor fusion, autonomous positioning, and concepts applicable to spacecraft attitude control and solar-energy collection. Future development includes integrating an IMU such as the MPU-6050 to account for changes in the system's physical orientation.

What it does and what problem it solves.

## Demo
Photo or GIF of the project working.

## Hardware
- Microcontroller: ESP32
- Sensors: soil moisture sensor, DHT22
- Actuators: 5V water pump, relay module
- Power: 5V USB supply

## Wiring / Schematic
Add a diagram image (Fritzing, KiCad, or a hand-drawn photo)
and a pin table:

| Component       | Pin   |
|-----------------|-------|
| Moisture sensor | GPIO34|
| Relay           | GPIO26|

## Firmware
Language/platform (Arduino C++, MicroPython), what it does,
and how to upload it.

## Software (optional)
Mobile app, web dashboard, or server, if any.

## Mechanical / Enclosure (optional)
3D print files (.stl), CAD files, dimensions.

## Setup
1. Wire the components as shown
2. Install the required libraries
3. Upload the code in /firmware
4. Power on
