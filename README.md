# Fixed Official Firmware for Klimerko

This repository provides a fixed version of the official firmware for Klimerko, addressing issues with WiFi connectivity.

## Fixes Implemented
- **WiFi Stability:** Added `WiFi.setSleep(WIFI_PS_NONE);` to improve WiFi performance.
- **Processor Frequency:** Adjusted processor frequency from 160MHz to 80MHz for better stability.

## Installation Procedure

1. **Clone the Repository:**
   ```sh
   git clone [repository-url]

2. Install or Open Arduino IDE:

- If you haven't installed the Arduino IDE, download and install it from [here](https://support.arduino.cc/hc/en-us/articles/360019833020-Download-and-install-Arduino-IDE).

3. Compile and Upload the Code:

- Open the cloned repository in Arduino IDE.
- Select the ESP32 Klimerko hardware board.
- Compile and upload the code to the Klimerko device.

4. Enjoy Your Klimerko Device:

- Your device should now be running with improved WiFi stability and optimized processor frequency.

