## Smart Electricity Usage Monitoring and Billing System Using ESP32 and Current Sensors
![image](https://github.com/user-attachments/assets/a09a36d0-debb-4988-a16d-84035de01dc4)



### Project Domain
The project focuses on real-time energy monitoring and prepaid billing using an ESP32 microcontroller integrated with a PZEM-004T sensor to measure electrical parameters and manage power consumption efficiently.

### Problem Statements
- Manual monitoring of electricity usage is inefficient and prone to errors.
- Overconsumption of electricity can lead to unexpectedly high costs, especially in households or small businesses.
- Lack of real-time insights into energy usage makes it difficult to manage budgets and optimize consumption.

### Goals
- Automate the monitoring of electricity consumption in real-time.
- Provide accurate cost estimation based on customizable electricity tariffs.
- Enable prepaid billing and notifications to prevent overconsumption and promote efficient energy use.

### Solution Statements
- Integrate a PZEM-004T sensor to measure current, voltage, and energy consumption (in kWh).
- Use an ESP32 microcontroller to process sensor data, calculate costs, and manage prepaid billing logic.
- Implement a web interface (HTML) for remote monitoring and user interaction.
- Include a relay module to control power supply based on prepaid balance or consumption limits.
- Provide notifications when energy consumption exceeds predefined thresholds.

### Prerequisites
#### Component Preparation
- **ESP32**: Microcontroller for processing sensor data, running a web server, and controlling the system.
- **PZEM-004T V3 Sensor**: Measures current, voltage, and energy consumption accurately.
- **Relay Module (5V)**: Acts as an electronic switch to connect or disconnect the power supply to the load.
- **Power Supply**: Suitable power source for the ESP32 and other components (e.g., 5V adapter).
- **WiFi Connection**: Enables remote access to the system via a web interface.
- **Web Interface (HTML)**: Provides a user-friendly platform for monitoring and managing energy usage.

### Working Principle
To address the identified problems, the **ESP32-based Prepaid Energy Monitoring System with PZEM-004T Sensor and Web Interface** is designed as a comprehensive solution. The system enables users to:
1. **Facilitate Prepaid Billing**: Users can pay in advance, and the system deducts costs based on real-time consumption.
2. **Monitor Energy Usage in Real-Time**: Displays current, voltage, energy (kWh), and estimated costs via a web interface or serial monitor.
3. **Track Usage History and Statistics**: Logs consumption data for analysis and budgeting.
4. **Manage Electricity Budget**: Sets consumption limits and sends alerts when thresholds are exceeded.
5. **Control Power Supply**: Automatically disconnects the load via the relay if the prepaid balance is depleted or consumption limits are reached.

#### Key Components and Their Roles:
- **ESP32**: Acts as the system’s core, processing sensor data, running the web server, controlling the relay, and managing prepaid logic.
- **PZEM-004T Sensor**: Accurately measures electrical parameters (current, voltage, power, and energy).
- **Relay Module**: Controls the power supply to the load based on system logic.
- **Web Interface (HTML)**: Provides an interactive platform for users to monitor consumption, view statistics, and manage prepaid settings.

With this system, users gain full control over their electricity usage and costs, promoting wiser and more efficient energy consumption.

## Block Diagram
![image](https://github.com/user-attachments/assets/72cba199-2559-45e9-9862-7fd01549591e)

## Sequence Diagram
![image](https://github.com/user-attachments/assets/9b3fc6ed-a1ca-49dc-83d3-18b417de12da)


## Flow Diagram
![image](https://github.com/user-attachments/assets/c520558d-ec12-484e-8ad6-df6931557b45)

## Preview

![image](https://github.com/user-attachments/assets/5d84224d-069f-41fc-a725-a2d65529928d)
![image](https://github.com/user-attachments/assets/e1192467-0cb9-4b39-bada-5ec14fa9c38a)

## Data Sheets ESP32
![image](https://github.com/user-attachments/assets/4c69d258-e923-4d43-8856-16eef52316f8)

## Demo
https://youtu.be/AsEIP3yxGpQ?si=U26-7BNE_a0y1kis


## Our Team
- Abdul Haris Muhasibi               (235150307111047)
- Barru Wira Yasa                    (235150301111021)
- Farrel Firmanditto Azka            (235150307111040)
- Muhammad Shean Elliora Ribah       (235150307111046)
- Muhammad Syauqi Muttaqin           (235150307111036)
- Ruasa Azizan Zihni                 (235150301111046)
