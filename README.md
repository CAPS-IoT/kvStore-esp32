# _KV Store for ESP32_

## Overview
This project is a lightweight key-value store optimized for time-series data storage on ESP32 devices. It provides multi-level data storage (buffering, caching, and persistent storage) and enables seamless integration with an edge device for efficient data management.



## Features
•	Multi-Level Data Storage: Implements buffering, caching, and flash storage for efficient data handling.

•	Optimized for ESP32: Designed to work within the limited resources of an ESP32 device.

•	Edge Device Integration: Smoothly pushes data to an edge device for further processing.

•	Device-First Query Interface: Supports range-based queries directly from the ESP32.

•	Time-Series Focused: Ideal for applications requiring chronological data storage.


## Hardware Requirements
•	ESP32 Development Board

•	DHT11 Temperature and Humidity Sensor

•	Jumper Wires

•	USB Cable (for programming and power)

•	Wi-Fi Network

## Software Requirements
•	ESP-IDF: ESP32 development framework (v4.x or above recommended)

•	Python 3.x: Required by ESP-IDF for build tools

•	Serial Monitor: idf.py monitor or any serial terminal program

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Please follow these steps:

1.	Fork the repository.
2.	Create a new branch: git checkout -b feature/your-feature-name.
3.	Commit your changes: git commit -am 'Add new feature'.
4.	Push to the branch: git push origin feature/your-feature-name.
5.	Submit a pull request.

## Contact
For questions or support, please open an issue on the GitHub repository or contact the project maintainer at abhishek.karki@tum.de
