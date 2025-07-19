# QMX+ Battery & Audio Board/Shield - Rev. 2

This is the second revision of the custom battery and audio board designed for the QRP-Labs QMX+ transceiver. The module is designed to be directly mounted on the mainboard of the QMX+ and is now **compatible with both 9V and 12V QMX+ versions.**

### Review by Colin MM0OPX (Video): [This SIMPLE Mod Makes the QMX+ Even Better](https://www.youtube.com/watch?v=ZL12OHniudg)

---

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

![Assembled Front](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembled%20Front.jpg)
![Assembled Back](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembled%20Back.jpg)
![Assembled Side](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembled%20Side.jpg)
![Schematic](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/QMX%2B%20Battery%20%2B%20Audio%20Board%20Rev.%202%20Schematic.jpg)
![MP2315 3D View](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/MP2315%203D.jpg)
![3D Front](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/3D%20Front.jpg)
![3D Back](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/3D%20Back.jpg)

## Warning and Disclaimer

**Always power off your QMX+ before connecting and disconnecting DC power. Connecting and disconnecting DC power while the board is installed can cause voltage transients and may damage the mainboard.**

**This version is compatible with both 9V and 12V QMX+ units. You must adjust the MP2315 output voltage correctly to 9V before first use. You must not solder the DC-DC converter if you want to use the board 12V.**

**Use at your own risk. Incorrect wiring or voltage configuration can damage your radio. I am not responsible for any damage, injury, or consequences resulting from use or misuse of this board.**

**Please do not copy or rebrand this project. You are free to use it with my labels.**

## Required Components

- **3x 1x18650 Li-ion Batteries:** I used 2900mAh INR18650 cells. There must be three 1x18650 battery holders.
- **3S 1A Multi Cell Charger Board (DDTCCRUB):** I used 1A and 2A versions. 3A might be a problem due to heating.
- **1x 3S 20A BMS Board** 
- **1x LM386 Audio Amplifier Breakout Board:** You have to desolder the pins.
- **1x 5x20mm 3A Fuse:** For further protection.
- **1x 5x20mm Fuse Holder:** Compatible with most 2 pin 5x20mm fuse holders. It must have 22.86mm (0.9in) or 15.24mm (0.6in) pin pitch.
- **2x 1K 1/4W THT or 0805 SMD Resistors:** Solder as you like SMD or THT.
- **8 Ohm Speaker:** Necessary for audio output. Use the screw terminals on the audio amplifier board. Small laptop speakers should work.
- **1x 2x3, 1x 2x2, 1x 1x5 2.54mm Female and Male Pin Headers:** To mount the PCB directly on the main board.
#### For 9V:
- **MP2315 DC-DC Buck Converter**
- **1x4 90 Degree Male Header**

## Assembly and Calibration

### Assembly

Check the ASSEMBLY.md file. Everything is same as Rev. 1.x if you are building it for 12V.

### Audio Calibration

After assembly and testing that your radio works you must calibrate the audio.

To calibrate the audio you must first lower the volume as down as you can using the volume knob of the radio. Then you must turn the variable resistor found on the audio board until you can hear the audio coming from the speaker barely. Audio is calibrated,  you should use the volume knob from now on.

## Notes on RFI

Since there is an RFI source inside the enclosure, some noise may occur in the 9V models. However, the 12V versions are free from battery board-induced noise, except during charging. Please keep this in mind when using it with 9V models.

> **In our tests with the 9V regulator, we observed that it caused QRM at certain frequencies. However, this noise was often at a lower level than QMX’s own birdies and was not disturbing. When we connected an antenna to the QMX and listened, the noise remained below the noise level coming from the antenna.**

## Notes

* Some power adapters are not working with this battery charger module (DDTCCRUB) because it lacks power delivery (PD) technology. If your charger doesn't work try another charger. 
* If you power the radio with DC jack while battery pack is installed, QMX+ will disconnect the batteries from radio. You can only charge the batteries from the Type-C port. QMX+'s own Type-C port is only for data.
* The 8mm x 8mm square behind the board is for JLCPCB order number. Select the **'2D Barcode' option and specify position** while ordering.

## Links

- [QRP-Labs Website](https://www.qrp-labs.com)
- [QRP-Labs QMX+ Transceiver](https://qrp-labs.com/qmxp.html)

### Special thanks to Hans Summers (G0UPL) for making this project possible.


### TA7MNA – laxdronum – GITRAD Radio Club YM7KK
