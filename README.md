# IoT Houseplant Monitoring System

## Overview
The IoT Houseplant Monitoring System is a project designed to help users maintain the health of their houseplants. By leveraging IoT devices, the system monitors essential plant care parameters such as soil moisture, light exposure, and temperature. Users receive alerts and can even enable automated watering to ensure their plants thrive.

## Features
- **Live Monitoring**: Track soil moisture, temperature, and light levels in real-time.
- **Notifications**: Receive alerts when moisture or light levels are below the defined threshold.
- **Automated Watering**: Optional feature to automatically water plants when the soil becomes too dry.
- **Web Application**: A user-friendly interface to monitor plant data, configure settings, and access care tips.

## Technology Stack
### Hardware
- **Arduino Uno R4**: Microcontroller for system control.
- **DHT11 Sensor**: For temperature and humidity measurement.
- **Soil Moisture Sensor**: To monitor soil water levels.
- **Light Sensor**: To measure the amount of light exposure.
- **Water Pump**: For automated watering.

### Software
- **Arduino IDE**: To program the Arduino Uno R4.
- **Flask**: Python-based backend framework.
- **React**: JavaScript library for the front-end web application.
- **HTML/CSS**: For structuring and styling the web interface.
- **GitHub**: For version control and data storage.

## System Architecture
1. **Sensors**: Collect real-time data on soil moisture, temperature, and light levels.
2. **Arduino Uno R4**: Processes data and controls the water pump based on thresholds.
3. **Web Application**: Displays live data, sends notifications, and allows configuration of settings.
4. **GitHub Repository**: Stores historical data and project source code.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/iot-houseplant-monitoring-system.git
   ```
2. Set up the Arduino IDE:
   - Install the required libraries for the sensors and water pump.
3. Install the backend and frontend dependencies:
   ```bash
   # Backend
   cd backend
   pip install -r requirements.txt

   # Frontend
   cd frontend
   npm install
   ```
4. Connect the hardware components as per the wiring diagram.
5. Run the backend and frontend applications:
   ```bash
   # Start the backend
   python app.py

   # Start the frontend
   npm start
   ```

## Usage
1. Access the web application at `http://localhost:3000`.
2. View live updates of your houseplant’s data.
3. Configure alerts and thresholds as needed.
4. Enable or disable automated watering via the settings panel.

## Future Enhancements
- Add support for multiple plants.
- Integrate voice control using virtual assistants.
- Implement AI-based plant health predictions.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Southern Illinois University Carbondale
- Professor Anas Alsobeh for guidance and feedback
