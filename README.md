# IoT-EBPL-Aqua-Culture-Monitoring-System
📌 Project Overview
The IoT – Aquaculture and Monitoring system is a prototype that simulates a smart aquaculture environment using Arduino-based hardware. It aims to monitor key water quality parameters such as:

pH Level

Turbidity

Dissolved Oxygen (DO)

Ammonia Concentration

Water Level

Using potentiometers as simulated sensors, the system alerts the user when environmental thresholds are breached. It is a foundation for a real-world IoT-enabled aquaculture monitoring solution.

⚙️ Technologies Used
Arduino Uno

Potentiometers (Sensor Simulation)

Arduino IDE (Software Logic)

Serial Monitor (Data Output)

Future Scope: ESP8266/NodeMCU, Cloud (ThingSpeak/Blynk), Real Sensors

🧪 Key Features
Real-time data monitoring and alerts

Sensor simulation with mapped ranges

Outputs displayed per second via Serial Monitor

Modular design for easy sensor replacement and scaling

Designed for integration with IoT platforms

🛠️ Setup Instructions
Hardware:
Connect five potentiometers to analog pins A0–A5 on Arduino Uno:

A0 – pH sensor

A1 – Turbidity sensor

A2 – DO sensor

A4 – Water level

A5 – Ammonia sensor

Connect Arduino Uno to PC via USB.

Software:
Open Arduino IDE.

Upload the provided sketch.

Open Serial Monitor at 9600 baud rate to view real-time feedback.

📘 Documentation Contents
System Architecture (block diagrams, sensor flow)

Source Code (with comments and thresholds)

User Guide (how to use system and read outputs)

Admin Guide (adjusting thresholds, maintenance)

Testing Report (various scenarios and expected outputs)

Final Report (summary of entire project life cycle)

✅ Completed Phases
Functional demonstration

Documentation and feedback incorporation

Final testing and validation

Project handover with hardware, software, and documents

🚀 Future Enhancements
Replace simulations with actual sensors

Enable wireless data transfer using Wi-Fi modules

Integrate with cloud dashboards for remote access

Add real-time notifications (SMS/Email)

Build a mobile/web app for visualization

📦 Output Examples (Serial Monitor):
yaml
Copy
Edit
pH: Alkaline | DO: Normal | Turbidity: Clean | Water Level: 35 cm | Ammonia: Safe
ALERT: Water too alkaline. Check filtration.


