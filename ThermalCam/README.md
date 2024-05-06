## Overview
This repository contains code and instructions for connecting an MLX90640 sensor to an ESP32 microcontroller and creating a simple web application to collect and display temperature data. The temperature data is visualized on the website using color ranges, where red represents hot temperatures and blue represents cold temperatures.

## Components
- MLX90640 sensor
- ESP32 microcontroller
- Web browser with Bluetooth API support

## Dependencies
- Arduino IDE
- ESP32 board support for Arduino IDE
- Web Bluetooth API compatible web browser (e.g., Google Chrome)

## Setup
1. Connect the MLX90640 sensor to the ESP32 microcontroller.
2. Install the necessary libraries for the MLX90640 sensor in the Arduino IDE.
3. Upload the provided ESP32 code to the microcontroller.
4. Open the web application in a compatible web browser.
5. Click on the "Connect" button to view available Bluetooth devices.
6. Select the device named "Therma" to connect to the ESP32.
7. Start receiving temperature data from the sensor.

## Color Ranges
- Red: Hot temperatures
- Blue: Cold temperatures
- Other colors: Intermediate temperature ranges

## Demo
View the demo of the webpage [here](https://prnvgiri.github.io/IoT/ThermalCam/web/).

## Note
Ensure that your ESP32 has BLE capabilities and that your web browser supports the Web Bluetooth API for seamless communication between the microcontroller and the web application.

## Disclaimer
This project is provided as-is without any warranties. Use it at your own risk.
