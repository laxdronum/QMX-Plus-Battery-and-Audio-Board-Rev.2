# **Assembly Guide**

---

## **Step 1 – Parts Needed**

![Step 1 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%201.jpg)

---

## **Step 2 – Solder the Battery Holders**

Solder the battery holders to the board and pay close attention to the polarity.

![Step 2 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%202.jpg)

---

## **Step 3 – Solder the BMS**

Modules should be soldered on top of 2.54mm standard pin headers. Insert the headers into the appropriate holes for different versions of the BMS module.

### **Step 3.1 – Insert the Pin Headers One by One**

![Step 3.1 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%203.1.jpg)

### **Step 3.2 – Solder the BMS and the Header Pins to the Board**

Clamping the module onto the board, as shown in the photo below, really helps.

![Step 3.2 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%203.2.jpg)

---

## **Step 4 – Solder the Charging Module and the Fuse Holder**

Solder the charging module in the same way as the BMS. You should align the Type-C port with the edge of the PCB if it is misaligned.

![Step 4 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%203.2.jpg)

### **Step 4.1 – Solder the Fuse Holder**

The fuse holder must have either 600mil (15.24mm) or 900mil (22.86mm) pin spacing.

![Step 4.1 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%204.1.jpg)

---

## **Step 5 – Solder the Audio Amplifier Module and the Resistors**

### **Step 5.1 – Reversing the Pins**

Soldering the audio module requires some skill. It comes with 1x4 headers pre-soldered, but you have to desolder them and solder another 1x4 header on the opposite side.

![Step 5.1 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%205.1.jpg)

### **Step 5.2 – Soldering onto the Board**

Placing some type of foam or double-sided tape under the board helps prevent excessive bending of the audio amp PCB.

![Step 5.2 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%205.2.jpg)

### **Step 5.3 – Soldering the Resistors**

You can solder either 0805 SMD or 1/4W THT resistors. I chose THT for this board.

![Step 5.3 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%205.3.jpg)

---

## **Step 6 (For 12V Boards) – Bridging the J4 Pad**

Short the J4 pad with a thick wire.

---

## **Step 6 (For 9V Boards) – Preparing and Soldering the Buck Converter**

> **Do not solder the buck converter and bridge the J4 at the same time. Magic smoke will appear.**

### **Step 6.1 – Inspecting the DC-DC Converter**

If you look closely, you'll see a few pads behind it. The ADJ pad is shorted by default. You need to cut the pad in the middle to disable its adjustment mode.

![Step 6.1 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%206.1.jpg)

### **Step 6.2 – Cutting the Pad**

You can cut the pad with an X-Acto knife. You need to go a little bit deep to sever the copper trace. Test it with a multimeter after cutting.

![Step 6.2 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%206.2.jpg)

### **Step 6.3 – Soldering the Headers**

You must solder the header pins in reverse. The longer pins must protrude from the back. If you solder the headers in the usual way, the buck converter won’t fit into place.

![Step 6.3 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%206.3.jpg)

### **Step 6.4 – Soldering the Module onto the Board**

This is the easiest step. Trim the protruding headers of the converter module and solder it in place.
**Never solder the DC-DC converter and short the J4 pads at the same time.**

![Step 6.4 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%206.4.jpg)

---

## **Step 7 – Shorten the Pins**

Now that all modules are soldered onto the board, you must shorten the pins on the backside of the board.

![Step 7 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%207.jpg)

---

## **Step 8 – Solder the Headers to the Board**

Soldering female headers to the battery board is recommended. This helps prevent shorts during handling.

![Step 8 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%208.jpg)

---

## **Step 9 – Solder the Corresponding Male Headers onto the QMX+**

![Step 9 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Step%209.jpg)

---

## **Step 10 - Assembly Finished**

Assembly is finished. You must test the board with a multimeter according to the schematic.

![Finished 1 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Finished%201.jpg)

![Finished 2 Photo](https://github.com/laxdronum/QMX-Plus-Battery-and-Audio-Board-Rev.2/blob/main/Images/Assembly/Finished%202.jpg)
