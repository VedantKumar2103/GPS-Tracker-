
# GPS Tracker using NodeMCU ESP8266 and NEO-6M GPS Module

## Overview
This project involves creating a GPS tracker using the NodeMCU ESP8266 and the NEO-6M GPS module. The tracker reads GPS coordinates and can be used for real-time location tracking with the help of Google Maps.

## Components Used
- **NodeMCU ESP8266**: A low-cost Wi-Fi microcontroller.
- **NEO-6M GPS Module**: A GPS receiver module that provides location data.
- **Jumper Wires**: Used to connect the components.

## Hardware Connections
1. **VCC (NEO-6M GPS Module) to 3.3V (NodeMCU)**
2. **GND (NEO-6M GPS Module) to GND (NodeMCU)**
3. **TX (NEO-6M GPS Module) to RX (NodeMCU)**
4. **RX (NEO-6M GPS Module) to TX (NodeMCU)**

## Software Setup
### Prerequisites
- **Arduino IDE**: Ensure you have the Arduino IDE installed. You can download it from [here](https://www.arduino.cc/en/software).
- **ESP8266 Board Package**: Install the ESP8266 board package in the Arduino IDE. Follow the instructions [here](https://arduino-esp8266.readthedocs.io/en/latest/installing.html).

### Libraries
- **TinyGPS++**: A library to parse GPS data.
- **SoftwareSerial**: To enable serial communication on digital pins.

### Installation
1. Open Arduino IDE.
2. Install the required libraries:
    - Go to **Sketch > Include Library > Manage Libraries**.
    - Search for **TinyGPS++** and install it.
    - Search for **SoftwareSerial** and install it.

## Testing
1. **Power the Setup**: Connect the NodeMCU to your computer via USB.
2. **Open Serial Monitor**: In the Arduino IDE, open the Serial Monitor (Tools > Serial Monitor) and set the baud rate to 115200.
3. **Verify GPS Data**: You should see GPS coordinates being printed on the Serial Monitor

## Acknowledgments
- **TinyGPS++**: Library for parsing GPS data.
- **Arduino Community**: For the support and resources.
   
#  Screenshots    
![Connection](https://github.com/user-attachments/assets/5735ca2f-d165-43cf-9bf1-dfe58ddec216)
![Output 1](https://github.com/user-attachments/assets/22f3daa0-bbf8-4ee9-ab25-3605ae143a8b)
![Output 2](https://github.com/user-attachments/assets/89e6c9e7-ca3d-4b61-88ef-39a9007a591e)

