# Home-Automation
The Smart Home Automation System is an Arduino-based project designed to improve home safety, energy efficiency, and comfort by automatically monitoring environmental conditions. The system integrates an LDR (Light Dependent Resistor) and a DHT22 temperature and humidity sensor to control household devices intelligently.
The LDR sensor continuously measures the surrounding light intensity. When the ambient light level falls below a predefined threshold, the Arduino automatically switches on an LED to simulate automatic lighting. When sufficient light is detected, the LED turns off, reducing unnecessary power consumption.
The DHT22 sensor monitors the room's temperature and humidity in real time. If the temperature exceeds a preset limit (35°C), the system activates an alert LED to indicate high-temperature conditions. It also calculates and displays the heat index, providing information about the perceived temperature based on humidity.
The system displays all sensor readings, including light level, temperature, humidity, heat index, and system status, on the Serial Monitor for continuous monitoring.
This project demonstrates the practical application of embedded systems and IoT concepts by combining multiple sensors with Arduino to create an intelligent home monitoring solution. It can be further expanded by adding Wi-Fi connectivity, mobile app control, relays for home appliances, motion sensors, gas leak detection, or cloud-based monitoring.
Key Features
Automatic light control using an LDR sensor.
Real-time temperature and humidity monitoring using a DHT22 sensor.
High-temperature alert using an LED.
Heat index calculation for enhanced environmental monitoring.
Energy-efficient automatic lighting system.
Continuous real-time data display through the Serial Monitor.
Easy to expand with IoT features for smart home applications.
