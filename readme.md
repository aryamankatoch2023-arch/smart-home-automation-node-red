# Smart Home Automation using Node-RED

## Project Overview
This project implements a simulation-based Smart Home Automation System using Node-RED, JavaScript, and Dashboard 2.0.

The system allows users to control lights and a fan manually or automatically using simulated motion and temperature readings.

## Features
- Manual light and fan control
- Automatic lighting based on simulated motion detection
- Automatic fan control based on temperature thresholds
- Temperature and motion status monitoring
- System alerts
- Simulated power consumption monitoring with a graph

## Technologies Used
- Node.js
- Node-RED
- JavaScript
- Node-RED Dashboard 2.0

## How It Works
A Function node processes incoming dashboard commands and simulated sensor events. It updates device states, applies automation rules, and sends six outputs to dashboard widgets for monitoring.

## Installation and Execution
1. Install Node.js.
2. Install Node-RED using `npm install -g node-red`.
3. Install the `@flowfuse/node-red-dashboard` package through Manage Palette if it is not already installed.
4. Start Node-RED by running `node-red`.
5. Open `http://localhost:1880`.
6. Import `smart_home_flow.json` using Menu → Import.
7. Deploy the flow and open the dashboard at `http://localhost:1880/dashboard`.

## Limitations
This project uses simulated sensor readings and estimated power consumption. It does not require physical sensors or electrical measurement hardware.

## Future Enhancements
The project can be extended by integrating an ESP32, physical temperature and motion sensors, smart relays, and actual energy-monitoring hardware.