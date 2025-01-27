# CleanBotX

The Smart Vacuum Cleaner (CleanBotX) is an innovative device designed to clean dust, paper, and plastic covers, all while being controlled through your phone via Bluetooth. This device aims to make home cleaning easier and more convenient, acting as a cleaning buddy right in your pocket.

## Components
### Sensors
- **Ultrasonic Sensor**: Detects obstacles, enhancing adaptability and preventing collisions, and measures the distance of an object.
- **Bluetooth Module**: Establishes a wireless connection for remote control via smartphone.

### Actuators
- **Motor Wheels**: Drive the device, providing mobility for efficient navigation.
- **Motor Board**: Controls motor speed and direction, ensuring precise movement during cleaning.
- **Motor for Vacuum**: The driving force behind suction, crucial for lifting and capturing dirt and debris.

### Hardware Platforms
- **NodeMCU**: An open-source IoT platform popular for its WiFi capabilities and low cost.
- **Arduino Uno**: Used to program the microcontroller, read and process input data from the sensors, and allow remote control of the sensors and microcontroller.



## Integration with Thingspeak Platform
The Thingspeak platform provides an easy and cost-effective way to manage, store, and display sensor data from the cloud. Users can visualize data from multiple sources using the platform's user-friendly interface.


## Code Implementation
The code for moving the vacuum cleaner and connecting to the cloud is implemented using Arduino and ESP8266 libraries. The code includes functionalities for obstacle detection, Bluetooth control, and data transmission to the Thingspeak platform.



## Installation
1. Clone the repository.
2. Install the necessary libraries for Arduino and ESP8266.
3. Upload the code to the Arduino Uno and NodeMCU.
4. Connect the components as per the circuit diagram.

## Contributing
Feel free to submit issues and pull requests. Contributions are welcome!

## Contact
For questions or support, please contact:

- **Y Manish Kumar**: [ymanishk602@gmail.com](mailto:ymanishk602@gmail.com)

## License
This project is licensed under the MIT License.


