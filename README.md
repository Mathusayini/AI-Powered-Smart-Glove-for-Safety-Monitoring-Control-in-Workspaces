# AI-Powered-Smart-Glove-for-Safety-Monitoring-Control-in-Workspaces

This project presents a smart glove that uses AI to help keep workers safe in places like factories and other risky areas. The glove has several sensors that can find dangers in the environment and from physical sources. It sends instant feedback and helps guide actions to handle those threats.

# Overview
The AI-powered smart glove is an integrated safety device that uses a number of sensors to keep an eye on a worker's surroundings and physical condition.  It promptly notifies the user via haptic (vibration) and visual (LED) signs when it detects dangerous gas levels, unsafe temperatures, excessive force, and abnormal health signals.  For real-time monitoring and upcoming AI-based predictive analysis, it concurrently logs sensor data to a Firebase cloud database.

# Key Highlights
Real-time detection of environmental and physical hazards
Adaptive signal filtering for improved accuracy
Immediate alert system using LED and vibration motor
Cloud data logging every 5 seconds to Firebase
Machine learning-ready data pipeline (CSV generation)
Custom optical-based force sensor for accurate load sensing
Modular and scalable design for industrial applications

# Technologies Used
Arduino Uno – for accelerometer data transmission
DAQ Card – for connecting analog sensors to PC
Sensors:
LM35 – Temperature sensor
MQ135 – Gas sensor
Custom Force Sensor – Optical-based for load detection
Actuators:Vibration Motor, LED indicators

# Software & Tools
LabVIEW – Data acquisition, visualization, and control
Python – Filtering, Firebase integration, CSV generation
Arduino IDE – Microcontroller programming
Firebase – Real-time cloud database
Excel / Pandas – Data formatting and preprocessing

# Usage
Wear the glove and ensure sensors are connected to the DAQ card/Arduino.
Power the system and launch the Python and LabVIEW scripts.
The system will:
Read sensor values
Apply low-pass filtering
Send alerts via vibration/LED
Upload data to Firebase every 5 seconds
CSV data is auto-generated for AI/ML training or analysis.

# Created By
Mathusayini Thayalanesan
Thineth Sadeepa
Thiruvarankan Mathurakaran
