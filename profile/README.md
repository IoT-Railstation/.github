## 👋 Welcome to IoT-Railstation
IoT-Railstation is an open-source project designed to modernize model railways using modern IoT technology.\
We use microcontrollers, MQTT and dedicated software to connect and control railway components such as trains, tracks, switches and signals. The project is currently in early development, and we are working towards our first release.\
\
![CurrentVersion](https://img.shields.io/badge/Current_Version-Currently_in_Development-darkred)
![License](https://img.shields.io/badge/license-MIT-orange)

> [!CAUTION]
> This Project is still in development. Only after the First Release an completly Install Guide and Tutorials will be final.

### 🌐 Current Infrastructure idea:
-> **IoT-Railstation Server** => A dedicated server service that manages the railway system and provides the central control logic. This allows the railway to operate independently without requiring a desktop application to be running at all times.\
-> **IoT-Railstation Desktop** => A Windows desktop application that connects to the IoT-Railstation Server. It allows users to monitor, control and configure their railway system, as well as create and edit tracks.\
-> **IoT-Railstation Slaves** => Microcontrollers that receive and execute commands from the IoT-Railstation Server. They handle the direct control of railway hardware such as motors, lights, switches and signals.

### 🗺️ Our Roadmap
- [ ] Think about the Architecture and more stuff
- [ ] Write the Core Architecture
- [ ] Add Slave Devices connect to Server
- [ ] Add Live Train Feature
- [ ] Add Track Editor to create custom Tracks
- [ ] Add Track Play Mode to use and see details for the Track
- [ ] Release IoT-Railstation v.1.0.0

### 💻 Tech Stack:
- MQTT
- C++
- Electron
- JavaScript
