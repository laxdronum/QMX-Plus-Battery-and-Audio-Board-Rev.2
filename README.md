# QMX+ Battery & Audio Board/Shield - Rev. 2

This is the second revision of the custom battery and audio board designed for the QRP-Labs QMX+ transceiver. The module is designed to be directly mounted on the mainboard of the QMX+ and is now **compatible with both 9V and 12V QMX+ versions.**

### Next Steps After Assembling or Receiving your Board (Guide): [Link](https://ta7mna.com/blog/next-steps-after-receiving-your-fully-assembled-board-rev-2x)

### Review by Colin MM0OPX (Video): [This SIMPLE Mod Makes the QMX+ Even Better](https://www.youtube.com/watch?v=ZL12OHniudg)

## Features
- Integrated battery power supply
- Compatible with both 9V and 12V QMX+ transceivers
- MP2315 adjustable DC-DC converter onboard
- Built-in audio amplifier
- Direct mounting on QMX+ PCB
- Type-C port for charging
- Integrated BMS
- Easy to assemble and efficient design

## Revision History - Latest Revision: Rev. 2.0

* July 2025 Rev. 2.0 : Added support for 9V QMX+ by integrating an MP2315 buck converter to step down battery voltage. Minor layout and silkscreen adjustments made.

## Images

- Assembled Front
- Assembled With Speaker
- Top View
- Bottom View
- Schematic
- 3D Render Front and Back

## Warning and Disclaimer

**Always power off your QMX+ before connecting and disconnecting DC power. Connecting and disconnecting DC power while the board is installed can cause voltage transients and may damage the mainboard.**

**This version is compatible with both 9V and 12V QMX+ units. The onboard MP2315 step-down converter ensures safe operation with 9V models. You must adjust the MP2315 output voltage correctly to 9V before first use. You must not solder the DC-DC converter if you want to use the board 12V**

**Use at your own risk. Incorrect wiring or voltage configuration can damage your radio. I am not responsible for any damage, injury, or consequences resulting from use or misuse of this board.**

**Please do not copy or rebrand this project. You are free to use it with my labels.**

## Required Components
- **3x 18650 Li-ion Batteries** (e.g., 2900mAh INR18650)
- **3S 1A Multi Cell Charger Board (DDTCCRUB)**
- **3S 20A BMS Board**
- **MP2315 Adjustable Buck Converter Module**
- **LM386 Audio Amplifier Breakout Board**
- **1x 5x20mm 3A Fuse + Holder** (15.24mm or 22.86mm pin spacing)
- **2x 1K Resistors (THT or 0805 SMD)**
- **8 Ohm Speaker**
- **Various Female/Male Pin Headers (2x3, 2x2, 1x5)**

## Assembly, Calibration and Notes

### Assembly

- Pay close attention to battery holder polarity.
- Adjust MP2315 output voltage (9V or 12V depending on your QMX+ version) **before inserting batteries**.
- Follow standard header mounting technique to ensure flush contact with QMX+ mainboard.
- Drill back plate for Type-C port after the board is mounted.
- Test the fully assembled board with a multimeter before powering on.

### Audio Calibration

- Set radio volume to minimum.
- Adjust the LM386 board's variable resistor until audio is barely audible.
- Use radio's volume knob for future control.

## Notes

- Some chargers may not work with the battery charging module (no PD support).
- Charging only via Type-C port on the board, not the QMX+’s own Type-C port.
- Use the silkscreened square (8mm x 8mm) for JLCPCB barcode positioning.

## Links

- [QRP-Labs Website](https://www.qrp-labs.com)
- [QRP-Labs QMX+ Transceiver](https://qrp-labs.com/qmxp.html)

## Special Thanks

Special thanks to Hans Summers (G0UPL) for making this project possible.

---

**TA7MNA – laxdronum – GITRAD Radio Club YM7KK**
