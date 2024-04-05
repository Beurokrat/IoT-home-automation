# IoT Project with Raspberry Pi and Azure IoT Cloud 🌐🍓🔌

This project demonstrates how to connect a Raspberry Pi to the Azure IoT Cloud, enabling you to monitor and control your IoT devices remotely. 📡💡

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

These instructions will get you a copy of the project up and running on your Raspberry Pi for development and testing purposes. 🛠️

### Prerequisites

Before you begin, ensure you have the following:

- A Raspberry Pi (any model should work, but a Raspberry Pi 3 or 4 is recommended for better performance)
- A microSD card with Raspberry Pi OS installed
- An active Azure account
- A Wi-Fi network

## Installation

1. **Set up your Raspberry Pi**: Insert the microSD card into your Raspberry Pi and connect it to a monitor, keyboard, and power supply.

2. **Connect to Wi-Fi**: Ensure your Raspberry Pi is connected to the internet.

3. **Install Azure IoT SDK**: Open a terminal on your Raspberry Pi and run the following command to install the Azure IoT SDK:

   ```bash
   sudo apt-get update
   sudo apt-get install -y azure-iot-sdk-c
   ```

4. **Create an Azure IoT Hub**: Follow the instructions on the [Azure portal](https://portal.azure.com) to create an IoT Hub.

5. **Register your Raspberry Pi**: In the Azure portal, register your Raspberry Pi as a device in your IoT Hub.

6. **Clone this repository**: Clone this repository to your Raspberry Pi:

   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   cd yourrepository
   ```

7. **Configure your device**: Edit the `config.py` file with your device connection string from the Azure portal.

8. **Run the application**: Execute the `app.py` script to start sending data to Azure IoT Hub:

   ```bash
   python3 app.py
   ```

## Usage

Once the application is running, your Raspberry Pi will start sending data to the Azure IoT Hub. You can monitor this data in the Azure portal.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before getting started.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

🚀 Happy coding!
