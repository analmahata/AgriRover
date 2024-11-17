# AgriRover 🌱🚜

**AgriRover** is an advanced agriculture-based automation project that integrates robotics and IoT technologies to perform key tasks such as irrigation, grass cutting, seed sowing, and sugarcane bud cutting. The project utilizes an **Arduino UNO**, **Raspberry Pi**, and various sensors to ensure efficient and intelligent farming operations.

---

## Features

- 🌾 **Plant Irrigation & Water Sprinkling**: Automated water distribution using soil moisture sensors and a 4.0 LPM pressure pump.
- ✂️ **Grass Cutting**: High-speed motors for precise and efficient grass cutting.
- 🌱 **Automatic Seed Sowing**: Servo motors and a seed hopper for controlled seed distribution.
- 🌿 **Sugarcane Bud Cutting**: Automated mechanism for precision cutting.

---

## Components Used

### Microcontrollers

- **Arduino UNO**: Main controller for task automation.
- **Raspberry Pi 3 B**: Used for image processing and AI-based decision-making.

### Sensors

- **Soil Moisture Sensors**: To measure soil humidity and regulate irrigation.
- **HC-SR04 Ultrasonic Sensor**: For distance measurement and obstacle detection.
- **RGB Camera**: For real-time plant health monitoring and image processing.
- **DHT11/DHT22**: Temperature and humidity sensors for environmental control.

### Actuators

- **4 Gear Motors**: To drive the movement of the AgriRover.
- **6 Servo Motors**: For precise seed planting.
- **3 High-Speed Motors**: Used for cutting tasks and other heavy-duty functions.
- **BALRAMA 4.0 LPM / 12V DC Pressure Pump**: For effective irrigation.

### Power Supply

- **Batteries**: 12x 3.7V lithium batteries with a 20A 3S BMS for power management.
- **Solar Panels**: 4x 6V panels to ensure sustainable energy for the rover.

### Motor Drivers

- **2x L298N Motor Drivers**: To control the motors efficiently.

---

## Project Setup

### Prerequisites

1. **Python 3.12.7** installed on your system.
2. Required hardware components connected and set up according to the design.

### Setting Up the Python Virtual Environment

To create a virtual environment with your system’s default Python version, run the following command:

```bash
python -m venv venv
```

> **Note**: If you have multiple versions of Python installed (e.g., 3.13, 3.12, 3.11, 3.9), use the following steps to specify the Python version when creating the virtual environment..

```bash
py -0  # Show available Python versions
```

To create a virtual environment using a specific Python version, run:

```bash
py -3.13 -m venv venv   # For Python 3.13
py -3.12 -m venv venv   # For Python 3.12
py -3.11 -m venv venv   # For Python 3.11
py -3.9 -m venv venv    # For Python 3.9
```

### Activating the Virtual Environment

- **Linux/macOS**

```bash
source venv/bin/activate
```

- **Windows**

```bash
.\venv\Scripts\Activate.ps1
```

> **Note**: Use `Python 3.12.7` for stable package support.

- Download and install [Python 3.12.7](https://www.python.org/downloads/release/python-3127/)

---

## Project Usage

- **Hardware Setup**: Connect all the hardware components according to the wiring diagram.
- **Software Setup**: Install the necessary Python packages and dependencies by running:

```bash
pip install -r requirements.txt
```

- **Run the Project**: Start the Python script to initiate the AgriRover's operations.

---

## License

This project is licensed under the [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0).

---

## Author

Developed by **Anal Mahata**

📧 Email: developer.anal@gmail.com
🐙 GitHub: [analmahata](https://github.com/analmahata)
