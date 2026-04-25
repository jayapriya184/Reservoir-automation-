Reservoir Automation system 

This project uses Arduino with WiFi and ThingSpeak to monitor and control water levels in a reservoir.

Components Used
- ESP32
- Ultrasonic Sensors (2)
- Relay Module
- WiFi (Wokwi Simulation)
- ThingSpeak Cloud

Working

- Two ultrasonic sensors are used:
  - One sensor measures the main water level
  - Another sensor checks additional level conditions

- The system connects to WiFi and sends data to ThingSpeak.

- If water level is low:
  - Relay turns ON (motor ON)

- If water level is high:
  - Relay turns OFF (motor OFF)

- Data like distance is continuously updated to the cloud
- 
Features
- Automatic water level monitoring
- Motor control using relay
- Cloud data logging using ThingSpeak
