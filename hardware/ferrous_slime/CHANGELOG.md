# Changelog

## v0.1.0
- Initial version of the board.
- Ordered PCB to test.

## v0.2.0
- Added 3 mounting holes.
- Added support for Adafruit BNO085.
- Improved legibility of silkscreen labels.
- Decreased sharpness of corners.
- Added support for soldering IMU breakouts flush with PCB.
- Fixed rendering of imu breakout pins.

## v0.3.0
- **Switched battery polarity** to match adafruit batteries.
- Moved silkscreen for "FULL" LED.
- Made measurement markings in mm with 2 digits of precision.
- PROG pin on TP4056 was incorrectly connected to VBUS, preventing LiPo charging.
  It is now fixed.
- Simplified name of IMU_Breakout.
- Satisfied ERC for VCC pin of aliexpress imus.
- Fixed footprint/symbols not referencing each other correctly for IMU.
- Added silkscreen labels for IMU breakout pins
- Connected TP4056 heatsink to GND

## v0.4.0
- Migrated to SRV05-04 for USB ESD, decreasing size and cost.
- Completely redesigned the board layout. Its much more efficient now, there is
  actually a large amount of unused space now.
- Removed all vias-in-pads, which was why v0.3.0 had faulty usb connection.
- Much better placement of capacitors, they now are near the pins they try to stabilize. 
- Antennas now have some keepouts on either side for a bit more signal strength. 

