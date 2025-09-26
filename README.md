# Digital Attitude Indicator by Evan Genuise
## About
I’m building a Digital Attitude Indicator as a way to learn more about avionics and embedded systems. This project uses an ATmega328P microcontroller, an MPU-6050 accelerometer/gyroscope, and an SSD1306 OLED display to measure orientation and display a real-time artificial horizon.

My goals with this project are to:
- Explore how attitude indicators work in aircraft.
- Practice working with accelerometers and gyroscopes.
- Gain experience driving small OLED displays with real-time data.
- Create a simple, educational tool that could be expanded into more advanced avionics projects down the line.

This is still a work in progress, but I’m sharing it here both as documentation of my process and in case it’s useful for anyone else interested in motion sensing, flight instrumentation, or microcontroller projects.

## BOM
- [ATMEGA328P](https://www.microchip.com/en-us/product/atmega328p)
- [SSD1306](https://www.amazon.com/HiLetgo-Serial-128X64-Display-Color/dp/B06XRBYJR8/?th=1)
- [MPU-6050](https://www.amazon.com/HiLetgo-MPU-6050-Accelerometer-Gyroscope-Converter/dp/B01DK83ZYQ?th=1)

## Schematic
![Schematic](/KiCad/schematics/digital_attitude_indicator_revA_WIP.png)