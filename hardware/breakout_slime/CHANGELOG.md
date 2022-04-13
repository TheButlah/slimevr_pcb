# Changelog

## v0.1
- Ordered PCB to test. Tests confirmed that pcb works for MPU, but battery
  polarity reversed, and INT1 pin goes to wrong pad which breaks BNO unless INT pin
  disabled in firmware. Battery polarity was also reversed, requiring installing
  the connector in reverse.

## v0.1.1
- Filled back ground pour.
- Fixed battery polarity on JST battery connector.
- Fixed INT1 wiring.

## v0.1.2
- Added a front ground pour, and optimized the two ground pours.
- Added edge cut on D1 antenna region.
- Added keepout on d1 antenna region.
- Added edge cut on battery connector.
- Added revision number to silkscreen.

## v0.1.3
- Changed D1 mini model to not use super tall headers in 3d view.
- Added B+ and B- to silkscreen.
- Rounded out corners of edge cuts.
- Re-reversed the battery polarity. It now has B+ on pin 1 of the JST connector. This
  matches adafruit and sparkfun conventions, and also the batteries I ordered on
  aliexpress. Not all batteries follow this convention!
- Removed the redundant keepout region on antenna, since its got edge cuts now.
- Assigned the rest of the power nets to the power netclass.
- Redid the old nets to use the thicker power netclass thickness.
- Now using same switch 3d model as `ferrous_slime`.
