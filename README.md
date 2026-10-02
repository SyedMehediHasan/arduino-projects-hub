# Arduino Projects Hub

Welcome to the Arduino Projects Hub! This repository contains a collection of beginner-friendly Arduino projects with documentation, source code, and wiring guidance.

## Table of Contents

- [Projects](#projects)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## Projects

### 1. LED Blink Control
A simple introduction to Arduino programming and digital output.
- Difficulty: Beginner
- Components: Arduino Uno, LED, 220Ω resistor, jumper wires
- Folder: `projects/01-led-blink-control`

### 2. Temperature & Humidity Monitor
Reads temperature and humidity using a DHT22 sensor and prints values to the Serial Monitor.
- Difficulty: Intermediate
- Components: Arduino Uno, DHT22 sensor, 10kΩ resistor, jumper wires
- Folder: `projects/02-temperature-humidity-monitor`

### 3. Motion Detection with PIR Sensor
Detects motion and turns on an LED or buzzer alarm.
- Difficulty: Intermediate
- Components: Arduino Uno, PIR sensor, LED, buzzer, jumper wires
- Folder: `projects/03-motion-detection`

### 4. LCD Display Control
Displays text on a 16x2 LCD panel with simple button input.
- Difficulty: Intermediate
- Components: Arduino Uno, 16x2 LCD, potentiometer, buttons, jumper wires
- Folder: `projects/04-lcd-display-control`

### 5. Ultrasonic Distance Meter
Measures distance using HC-SR04 and displays it in centimeters.
- Difficulty: Intermediate
- Components: Arduino Uno, HC-SR04 sensor, jumper wires
- Folder: `projects/05-ultrasonic-distance-meter`

## Getting Started

### Prerequisites
- Arduino IDE installed
- Arduino board (Uno recommended)
- USB cable
- Breadboard and jumper wires
- Required sensors/components for each project

### Steps
1. Clone this repository.
2. Open the project folder you want to use.
3. Open the `.ino` file in Arduino IDE.
4. Connect the circuit as described in the `README.md` file.
5. Upload the code to the board.

## Project Structure

```text
arduino-projects-hub/
├── README.md
├── projects/
│   ├── 01-led-blink-control/
│   │   ├── README.md
│   │   └── led-blink.ino
│   ├── 02-temperature-humidity-monitor/
│   │   ├── README.md
│   │   └── temp-humidity.ino
│   ├── 03-motion-detection/
│   ├── 04-lcd-display-control/
│   └── 05-ultrasonic-distance-meter/
└── docs/
    └── troubleshooting.md
```

## Contributing

Contributions are welcome. If you want to add new Arduino projects:

1. Create a new folder under `projects/`
2. Add a `README.md` with components and wiring details
3. Add a `.ino` source file
4. Keep the project easy to understand and test
5. Open a Pull Request with a short description

---

Happy building with Arduino!
