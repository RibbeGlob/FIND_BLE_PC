# FIND_BLE_PC

## Overview
**FIND_BLE_PC** is a Python-based system that functions as an MQTT broker while also visualizing the location of Bluetooth Low Energy (BLE) broadcasting devices based on signal strength (RSSI). This project allows real-time tracking of BLE devices using signal triangulation and a graphical interface for location representation.

## Features
- **MQTT Broker**: Acts as a message broker for real-time BLE data exchange.
- **RSSI-based Localization**: Estimates the location of BLE devices based on signal strength.
- **Visualization**: Displays the detected BLE devices on a graphical interface.
- **Configurable MQTT Topics**: Allows integration with other MQTT clients and applications.

## Installation
### Prerequisites
Ensure that your system has the following dependencies installed:
- Python 3.x
- `paho-mqtt` (for MQTT communication)
- `matplotlib` (for visualization)
- `numpy` and `scipy` (for signal processing and localization)

### Steps
1. Clone the repository:
   ```bash
   git clone git@github.com:RibbeGlob/FIND_BLE_PC.git
   cd FIND_BLE_PC
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the program:
   ```bash
   python main.py
   ```

## Usage
### Visualization
- Detected BLE devices are displayed on a 2D plane.
- Color coding is used to represent signal strength.
- Devices can be selected for further inspection.

## Configuration
Modify `config.json` to adjust settings such as:
- MQTT port and host
- BLE scanning interval
- Visualization preferences

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.

## Author

https://www.linkedin.com/in/grzegorz-globisz/

