# Real-Time Data Collection and Transmission System

## Description
This project focuses on the design and implementation of a system capable of collecting and transmitting real-time data from various sensors. The system leverages **STM32** and **ESP8266** microcontrollers, along with wireless communication protocols such as **Wi-Fi** to send data to **ThingSpeak** for visualization and analysis.

## Technologies Used
- **Microcontrollers:** STM32, ESP8266
- **Wireless Communication:** Wi-Fi
- **Cloud Platform:** ThingSpeak
- **Programming Languages:** C/C++ (STM32 and ESP8266)
- **Development Tools:** STM32CubeIDE, Arduino IDE

## Role
- Developed firmware for STM32 and ESP8266
- Integrated various sensors (e.g., temperature, humidity, pressure)
- Implemented communication protocols for data transmission
- Conducted performance tests for real-time data accuracy and network reliability

## Features
- **Sensor Integration:** Collects data such as temperature, humidity, and pressure from connected sensors.
- **Real-Time Data Transmission:** Data is sent to ThingSpeak via Wi-Fi for live monitoring.
- **ThingSpeak Integration:** Allows visualization of sensor data through the ThingSpeak platform.
- **Performance Optimization:** Tested for efficient data handling and reduced latency.

## How It Works
1. Sensors connected to the STM32 collect real-time environmental data.
2. The data is processed and sent to the ESP8266 via UART.
3. The ESP8266, acting as a Wi-Fi module, transmits the data to ThingSpeak.
4. ThingSpeak provides real-time visualization of the data.


Ce modèle pourra t'aider à structurer ton dépôt GitHub et donner une bonne impression aux personnes qui consulteront ton projet.
