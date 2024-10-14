# Smart-LED
The Smart LED project enables control of LED lights via the WLED App and is powered by a D1 Mini microcontroller (ESP8266). This repository includes the firmware and setup instructions to control and automate LED lighting using Wi-Fi through the WLED app.

## Features
* WLED App Integration:Control LEDs through the WLED app for Android and iOS.
* D1 Mini (ESP8266): Wi-Fi enabled microcontroller for smart lighting control.
* Custom lighting effects: Create and apply various LED effects and animations.
* Power management: Efficient control to optimize power consumption.
* Easy setup: Minimal wiring and configuration needed with the D1 Mini.
## Getting Started
### Prerequisites
* D1 Mini (ESP8266) microcontroller
* LED strip (WS2812B or similar)
* Power supply for the LED strip (ensure it matches the voltage of your LED strip)
* WLED App (available for Android and iOS)
* USB cable for programming the D1 Mini
* Arduino IDE or PlatformIO (for uploading the firmware)
### Installation
* Clone the repository:

bash
Code kopieren
git clone https://github.com/yvsim001/Smart-LED.git
cd Smart-LED
Install the WLED firmware: You will need to flash the D1 Mini with the WLED firmware. You can do this by following the official WLED installation guide:
WLED Installation Guide.

* Connect the hardware:

Connect the LED strip to the D1 Mini as follows:
DIN (Data in) of the LED strip to D4 (GPIO2) of the D1 Mini.
Power the LED strip using a suitable power supply (usually 5V or 12V).
Connect the ground of the LED strip, power supply, and D1 Mini together.
Configure WLED:

After flashing the WLED firmware and powering the D1 Mini, connect to the D1 Mini's Wi-Fi network and configure it via the web interface.
Set up your home Wi-Fi and choose LED settings such as the number of LEDs in the strip.
Hardware Setup
D1 Mini Pinout:

The D1 Mini (ESP8266) should have the following connections to the LED strip:
GPIO2 (D4) for the LED data pin.
Power (VCC) and Ground should be connected appropriately.
Powering the LED Strip:

Ensure that your power supply matches the requirements of your LED strip (either 5V or 12V).
Always connect the ground of the power supply, LED strip, and D1 Mini together.
Usage
WLED App:

Download and install the WLED app on your smartphone.
Once the D1 Mini is connected to your home Wi-Fi, open the app, and it will automatically detect your device.
Use the app to control the LEDs, change colors, and apply custom lighting effects.
Web Interface:

WLED also provides a web-based interface accessible by entering the device's IP address in a web browser. You can configure settings and control the LEDs from there.
Customization
You can customize lighting effects and animations directly from the WLED app or by modifying the WLED source code. This repository includes additional setup instructions for hardware integration and specific configurations for the D1 Mini.

Firmware Updates
To update the WLED firmware, follow the WLED documentation for over-the-air (OTA) updates or flash new firmware using the USB connection.
Contributing
Feel free to submit pull requests or open issues if you find bugs or have suggestions for additional features.

License
This project is licensed under the MIT License - see the LICENSE file for details.

