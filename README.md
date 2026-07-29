# Sensor-Based Fertilizer Dispensing System for Precision Agriculture

## Project Overview
This project develops an automated, sensor-based fertilizer dispensing system that monitors soil nutrients, moisture, and crop health in real time to optimize fertilizer application in precision agriculture. The system reduces fertilizer wastage by 30–40%, lowers environmental pollution, and promotes sustainable, cost-effective farming through IoT-based automation.

---

## Problem Statement
Conventional fertilizer application methods distribute fertilizer uniformly across entire fields without considering variations in soil nutrient levels, moisture, and crop health. This results in:
- **Nutrient wastage** due to over/under-application
- **Increased cultivation costs**
- **Reduced crop productivity**
- **Environmental pollution** from nutrient runoff

**Solution:** A cost-effective, automated, precision fertilizer dispensing system that applies the right fertilizer amount based on real-time field conditions.

---

## Objectives
1. Develop a sensor-based fertilizer dispensing system for real-time, site-specific fertilizer application
2. Optimize fertilizer usage by automatically controlling quantity and type based on soil and crop conditions
3. Reduce fertilizer wastage and environmental impact while improving crop productivity
4. Integrate IoT and sensor technologies for efficient monitoring and automated decision-making
5. Design a system retrofittable to existing farm vehicles, making precision farming affordable and accessible

---

## Key Features
- **Real-time soil parameter monitoring** (NPK, pH, EC, moisture, temperature)
- **Automated fertilizer dispensing** triggered by sensor data
- **IoT-enabled remote monitoring** via WiFi/Bluetooth
- **Vehicle-mountable design** for easy integration
- **Low-cost, scalable architecture** for small to medium farms
- **CAD-validated mechanical design** for reliability and durability

---

## Technical Specifications

### Components
| Component | Specification |
|-----------|---------------|
| Soil Sensor | 7-in-1 (NPK+pH+EC+Moisture+Temp), RS485 Modbus, IP68 |
| Microcontroller | ESP32 DevKit or Arduino Mega (WiFi/BLE enabled) |
| Motor Driver | L298N / BTS7960 (Dual channel, PWM) |
| Dispensing Mechanism | Auger-type metering (50–70 mm dia, geared motor) |
| Hopper Capacity | 15–25 kg (custom sheet metal/HDPE) |
| Geared Motor | 12V DC, high torque, PID-controllable with encoder |
| Control Display | 16x2 I2C LCD with backlight |
| Relay Module | 4-channel, 5V/12V trigger |

### Estimated Budget
**₹22,000 – ₹36,000** (includes sensors, motors, controllers, fabrication, and integration)

---

## System Architecture

### Hardware Layers
1. **Sensing Layer** – Soil sensors (NPK, moisture, pH, EC, temperature)
2. **Processing Layer** – ESP32/Arduino microcontroller
3. **Actuation Layer** – Motor driver, servo/DC motor, solenoid valve (if liquid variant)
4. **Mechanical Layer** – Auger metering mechanism, hopper, mounting frame
5. **Communication Layer** – WiFi/Bluetooth for IoT monitoring

### Control Flow
