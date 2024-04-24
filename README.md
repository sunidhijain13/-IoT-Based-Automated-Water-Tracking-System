# IoT_Project_Spring2024

# ESP32 IoT Automated Water Tracking System

This repository contains the code for an IoT-based environmental monitoring system using ESP32. The system measures temperature and humidity using a DHT22 sensor and water flow using a generic water flow sensor. It aims to provide real-time data for environmental conditions and water usage.

## Project Components

- **ESP32 Dev Module:** Acts as the central processing unit.
- **DHT22 Sensor:** Measures temperature and humidity.
- **Water Flow Sensor:** Monitors water flow and calculates water usage.
- **Additional Supplies:** Wokwi to stimulates.

## System Setup

### Hardware Setup

1. Connect the DHT22 sensor to the ESP32:
   - Connect the VCC to 3V3.
   - Connect GND to GND.
   - Connect the Data pin to a predefined GPIO on the ESP32.
2. Connect the water flow sensor to the ESP32:
   - Connect the VCC to 5V.
   - Connect GND to GND.
   - Connect the signal/output pin to a different predefined GPIO.

### Software Setup

1. Flash the provided code to the ESP32 using the Arduino IDE or similar platform.
2. Ensure your ESP32 board definitions and libraries are up to date.

## Code Description

The Jupyter notebook `IoT_Project.ipynb` contains the complete code for this project, including:
- Initialization and configuration of the sensors.
- Functions to read and process sensor data.
- Simulated random generation of water usage data.
- Visualization code for displaying sensor readings in real-time.

## Running the Project

Once the setup is complete, power the ESP32 module. The system will begin to collect and display data from the sensors. Check the serial monitor of your Arduino IDE to view the output data or any diagnostic messages.

## Visualization

This project includes a Python script to visualize the temperature, humidity, and water usage data graphically. Ensure you have Python installed on your computer and the necessary libraries such as matplotlib to run the visualization.

## Future Enhancements

- Integration with cloud platforms for data logging and analysis.
- Implementation of alert systems for abnormal conditions such as water leaks and monitoring.
- Expansion of sensor types and monitoring capabilities.


