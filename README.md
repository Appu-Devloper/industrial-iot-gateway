🌐 Herin Industrial IoT Platform
High-Performance ESP32-P4 + Flutter + PLC Automation Ecosystem

A production-deployed Industrial IoT platform that bridges legacy industrial machines to a modern real-time cloud architecture using a high-speed Ethernet RISC-V gateway.

📊 Live Production

🌍 Cloud Dashboard → https://heiot.herin.in

📱 Android App → https://play.google.com/store/apps/details?id=ccom.herin.iot

🍎 iOS App → https://apps.apple.com/in/app/herin-iot/id6642696241

Successfully deployed in 3 multinational manufacturing companies

🧠 System Overview
RS485 Sensors / PLCs
        │
        ▼
ESP32-P4 Industrial Gateway (Ethernet)
        │
 MQTT / WebSockets
        │
        ▼
Cloud Backend
        │
        ▼
Flutter Mobile App + Web Dashboard

⚙️ Hardware Engineering
🔹 Industrial Gateway

ESP32-P4 Nano (RISC-V High-Performance MCU)

Native 10/100 Ethernet (Reliable factory networking)

Real-time Modbus polling engine

Concurrent display rendering + communication tasks

🔹 Displays Integrated

Waveshare 4.3" HMI

Waveshare 5" HMI

Waveshare 11" Industrial Panel

🔹 Industrial Communication

Custom RS485 ↔ Ethernet Add-on Board (Designed by Herin Electronics)

High noise-immunity industrial wiring

Digital input monitoring

Industry-standard sensor reading via Modbus RTU

🧩 Firmware (ESP-IDF)

Core Technologies

ESP-IDF RTOS Task Scheduling

Modbus Master Stack

Ethernet MAC/EMAC Driver

MQTT Client

WebSocket Communication

Display Drivers

Key Features

Deterministic polling of multiple RS485 slaves

Parallel UI rendering + communication

Reliable real-time publishing to cloud

Register read/write abstraction layer

Industrial error recovery & retry handling

🏭 Industrial Control Logic
Temperature Automation

Users can configure temperature profiles remotely:

Time-based setpoints

Automatic transitions

Machine state synchronization

PLC Register Control

Backend sends MQTT commands → Gateway writes registers → Machine reacts

Cloud → MQTT → ESP32 → RS485 → PLC Register → Machine Action

PID Closed Loop Control

Implemented device modulation:

ON/OFF control

Variable output control

Stable industrial process regulation

📱 Software Platform
Flutter Applications

Cross-platform industrial monitoring:

Android

iOS

Web

Features:

Real-time machine monitoring

Alarm notifications

Historical graphs

Device control panel

Admin configuration portal

☁️ Cloud Architecture

Real-time MQTT messaging

Web dashboards

Device configuration APIs

Register scheduling engine

Multi-company support

Secure device authentication

🔁 Data Flow

Gateway polls PLC via Modbus RTU

Data published to cloud via MQTT

Dashboard displays real-time values

User sends control command

Cloud schedules register write

Gateway writes PLC register

Machine state changes

🧪 Real-World Results

Stable operation in high-noise factory environments

Continuous uptime deployment

Real-time industrial monitoring

Automated machine control

Reduced manual operator dependency

💡 Engineering Highlights

Designed custom RS485 hardware

Optimized Modbus communication reliability

Built full cloud + firmware + mobile ecosystem

Implemented real-time PLC automation logic

Solved industrial networking instability using Ethernet architecture

👨‍💻 Author

Herin Electronics

Specialization:

Embedded Systems

Industrial IoT

Flutter Applications

Industrial Automation

Protocol Integration (Modbus / MQTT)

📄 License

Proprietary / Industrial Deployment Project
(Contact author for collaboration or integration)
