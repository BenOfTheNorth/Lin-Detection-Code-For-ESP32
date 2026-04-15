# LIN Frame Detection for ESP32 Boards

This is a project that allows you to connect and listen (sniff) to a LIN network for frames related to button presses - this is the tool I created and use to detect button presses on a LIN2 Steering Wheel to reverse engineer it into an older vehicle.

It's designed to run on a standard ESP32, however it could be re-purposed to run on most ESP32 boards. This should work on a Mac and Windows, though I've only tested with a Mac (Studio).

This was developed primarily for modern VAG steering wheels, but may be applicable to other vehicles too (though a tweak may be needed to the baud rates etc).

## Table Of Contents

- [Known Frames](#known-frames)
- [Software Required](#software-required)
- [Components Required](#components-required)
- Circuit / Wiring Diagram

## Known Frames

For frames that I have already sniffed (or added by the community via pull requests), you can check the [known-frames directory](/known-frames). This might saved you the work if you're planning on doing this yourself if the frames have already been sniffed.

## Software Required

- **IDE:** Visual Studio Code (Free)<br />   (Download from Microsoft: [https://code.visualstudio.com/](https://code.visualstudio.com/))<br /><br />
- **Extensions:** PlatformIO (Free)<br />   (Install Guide from PlatformIO: [https://platformio.org/install/ide?install=vscode](https://platformio.org/install/ide?install=vscode))

## Components Required

This is the complete list of parts you'll require:

**Primary Components**

- **Board:** ESP32 (WROOM-32) <br />  (Amazon: [https://www.amazon.co.uk/dp/B0DGLCWR76](https://www.amazon.co.uk/dp/B0DGLCWR76))<br /><br />
- **Lin Data Analyzer:** TJA1021<br />  (Ali Express: [https://www.aliexpress.com/item/1005006916261136.html](https://www.aliexpress.com/item/1005006916261136.html))<br /><br />
- **Resisters:**<br />1x 1kΩ<br />  (Amazon: [https://www.amazon.co.uk/dp/B0BTP6WYH1](https://www.amazon.co.uk/dp/B0BTP6WYH1))<br /><br />
- **Diodes:**<br />  1x 1N4148<br />  (Amazon: [https://www.amazon.co.uk/dp/B0C1V6Y8ND](https://www.amazon.co.uk/dp/B0C1V6Y8ND))

**Misc Components**

- **Jumper Wires (Pre Formed):**<br />  (Amazon: [https://www.amazon.co.uk/dp/B0D5M9DN2K](https://www.amazon.co.uk/dp/B0D5M9DN2K))<br /><br />
- **Jumper Wires (Dupont - Female to Male Required):**<br />  (Ali Express: [https://www.aliexpress.com/item/1005003219096948.html](https://www.aliexpress.com/item/1005003219096948.html))<br /><br />
- **12v Power Supply:**<br />  (Amazon: [https://www.amazon.co.uk/gp/aw/d/B0CJ8SQDLN](https://www.amazon.co.uk/gp/aw/d/B0CJ8SQDLN))<br /><br />
- **Breadboard:**<br />  (Ali Express: [https://www.aliexpress.com/item/1005006994564405.html](https://www.aliexpress.com/item/1005006994564405.html))<br /><br />
- **USB C Cable:** The ESP32's I linked to are USB-C powered, so you'll need a USB-C to either USB-C or USB-A (Whichever your computer has)
