# Smart Medibox

Smart Medibox is an IoT-based solution designed to help manage medication schedules efficiently. It integrates various sensors and components, ensuring medications are stored in optimal conditions and users are alerted at the right times. The device connects to WiFi and uses MQTT for communication, with a Node-RED dashboard for monitoring and control.

## Features

- **Sensors**:
  - **Temperature & Humidity Sensor (DHT22 or DHT11 also user can use BMP280 or BME280 with pressure sensing)**: Monitors the environment inside the Medibox to ensure medications are stored in optimal conditions.
  - **Light Intensity Sensors (2 x LDR)**: Measures ambient light levels to help ensure the Medibox is in an appropriate environment.
- **Alarms(Buzzer)**:
  - Configurable alarms for medication times, with notifications via LEDs and sound.
  - Alarms can be set using physical buttons on the Medibox or via the Node-RED dashboard.
- **OLED Display**: Shows real-time information about medication schedules, sensor data, and alerts.
- **Servo Motor**: Controls the medicine tray, which can be operated via the Node-RED dashboard.
- **Node-RED Dashboard**: Provides a user-friendly interface to monitor temperature, humidity, and light intensity with gauges and charts. It also allows for remote control of the medicine tray and alarm settings.
- **Connectivity**:
  - **WiFi**: Ensures the Medibox stays connected to the internet for real-time updates.
  - **MQTT**: Facilitates efficient communication between the Medibox and the Node-RED dashboard.

## Installation and Setup

1. **Hardware Assembly**: Connect the components as per the provided schematic.
2. **Software Installation**: Flash the firmware onto the microcontroller using the Arduino IDE or similar platform.
3. **Network Configuration**: Update the firmware with your WiFi credentials and MQTT broker details.
4. **Node-RED Setup**: Import the provided flow into Node-RED and configure the dashboard as per the instructions.

## Repository Contents

- **Code**: Firmware for the Medibox microcontroller.
- **Node-RED Flows**: JSON file to import into Node-RED.
- **Schematics and Diagrams**: Detailed visuals for hardware assembly and PCB design.
- **Documentation**: Comprehensive guide for setting up and using the Smart Medibox.

## Preview

### Required Components
| Component | Image |
| --------- | ----- |
| ESP32     | ![ESP32](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/ESP32.jpeg) |
| DHT22     | ![DHT22](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/DHT22.jpeg) |
| LDR     | ![LDR](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/LDR.jpeg) |
| OLED Display     | ![OLED Display](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/OLED.jpeg) |
| Servo Motor     | ![Servo Motor](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/Servo.jpeg) |
| Push Down Buttons     | ![Buttons](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/button.jpg) |
| Buzzer     | ![Buzzer](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/buzzer.jpeg) |
| LM1117     | ![LM1117](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/LM1117.jpeg) |
| Resistors     | ![Resistors](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/Resistors.jpg) |
| Jumper Wires     | ![Jumpers](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/Jumpers.jpg) |
| LEDs     | ![LEDs](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/LED.jpeg) |

### Components Connection Block Diagram

![Components Connection Block Diagram](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/BlockDiagram.png)

### PCB 3D View

![PCB 3D View](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/Circuit.png)

### Node-RED Dashboard View (UI)

![Node-RED Dashboard View (UI)](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/Dashboard.png)

### PCB 2D View

![PCB 2D View](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/PCB.png)

### Prototype Design View

![Prototype Design View](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/Prototype%20circuit.png)

### Schematic View

![Schematic View](https://github.com/TharushaDinujaya/Smart-Medibox-Control-System/blob/main/docs/Schematic.png)

## Contributing

We welcome contributions! Please fork this repository and submit a pull request for any enhancements, bug fixes, or new features.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries or support, please open an issue in this repository or contact us at tharushad.21@cse.mrt.ac.lk

By integrating various sensors and connectivity options, the Smart Medibox ensures you never miss a dose and your medications are stored in optimal conditions.
