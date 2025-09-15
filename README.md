# IoTMuseumSimulation

This repository contains a **Node-RED project** for simulating IoT environments in a museum setting.  
The flows define multiple rooms (exhibition and personal-only) instrumented with sensors such as temperature, air quality, illumination, smoke, and noise.

---
## 🏛️ Simulation Overview

The project emulates a museum environment with the following setup:

Rooms

* Exhibition rooms (3x): accessible to both personnel and visitors.
* Personal-only room (1x): restricted to personnel only.

Sensors per room
* Temperature sensor
* Air quality sensor
* Illumination sensor
* Smoke detector
* Noise detector

---

## 🚀 Getting Started

These instructions will help you set up and run the Node-RED project locally.

### 1. Install Node.js
Make sure you have [Node.js](https://nodejs.org/) installed.  
Recommended: LTS version 18.x or 20.x.  

Check your installation:
```bash
node -v
npm -v
```

### 2. Install Node-RED

Install Node-RED globally:
```bash
npm install -g --unsafe-perm node-red
```
Verify installation:
```bash
node-red --version
```

### 3. Clone this repository
```bash
git clone https://github.com/Alex23013/IoTMuseumSimulation.git
cd IoTMuseumSimulation
```
### 4. Install dependencies
```bash
npm install
```

This installs any extra Node-RED nodes required by the project.

### 5. Run Node-RED with this project

From inside the project folder:
```bash
node-red -u .
```
The -u . flag tells Node-RED to use the current folder as the user directory, so it loads the flows and settings from this repository.

### 6. Open the Node-RED editor

Once Node-RED is running, open your browser at:

👉 http://127.0.0.1:1880

You should see the flows already loaded.