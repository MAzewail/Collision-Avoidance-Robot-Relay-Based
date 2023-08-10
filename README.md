# Collision Avoidance Robot with Ultrasonic Sensor (Relay-Based)

Welcome to the Collision Avoidance Robot with Ultrasonic Sensor (Relay-Based) GitHub repository! This project showcases a robot that utilizes an ultrasonic sensor to detect obstacles and avoid collisions. The robot adjusts its path to navigate around obstacles by controlling the movement of its motors using relays.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Circuit Diagram](#circuit-diagram)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Collision Avoidance Robot with Ultrasonic Sensor (Relay-Based) is designed to navigate its surroundings while minimizing the risk of collisions. It achieves this by incorporating an ultrasonic sensor that measures the distance to objects in its path. Based on this distance information, the robot adjusts its path by controlling the movement of its motors using relays. By activating the appropriate relays, the robot can turn left or right to avoid obstacles.

- [TinkerCad link](https://www.tinkercad.com/things/jWn3xKmINRg)

## Features

- Collision avoidance mechanism utilizing an ultrasonic sensor.
- Adjusts path by controlling motor movement using relays.
- LED for displaying distance and direction information.

## Hardware Requirements

To set up and run this project, you will need the following hardware components:

- Arduino or compatible microcontroller board.
- Ultrasonic sensor module (e.g., HC-SR04) for obstacle detection.
- Relays for controlling motor movement.
- DC motors for robot movement.
- LED for visual feedback.
- Resistor(s) for LED connection.
- Jumper wires for circuit connections.
- Breadboard or PCB for assembling the circuit.

## Circuit Diagram

- [TinkerCad link](https://www.tinkercad.com/things/jWn3xKmINRg)

![Circuit Diagram](https://github.com/MAzewail/Collision-Avoidance-Robot-Relay-Based/blob/main/2WD%20robot%20using%20relays.png)

The circuit diagram above illustrates the connections between the microcontroller board, ultrasonic sensor module, relays, motors, LED, and other components. Ensure that you make the appropriate connections based on the diagram when setting up the hardware.

## Installation

1. Clone this repository to your local machine using the following command:

   ```
   git clone https://github.com/MAzewail/collision-avoidance-robot-relay-based.git
   ```

1. Connect the hardware components (microcontroller board, ultrasonic sensor module, relays, motors, LED, etc.) to your microcontroller board based on the circuit diagram provided.

1. Upload the code to your microcontroller board using the Arduino IDE or your preferred development environment.

## Usage

1. Ensure that the hardware is properly connected to the microcontroller board.

1. Power on the robot.

1. The ultrasonic sensor will start detecting obstacles in the robot's path.

1. The LED will display the distance to the nearest obstacle and indicate the direction in which the robot should turn to avoid the obstacle.

1. The relays will control the movement of the motors to adjust the robot's path accordingly.

1. Observe the robot as it navigates its surroundings and avoids collisions by turning left or right based on the distance information.

## Contributing

Contributions to this project are welcome and encouraged! If you would like to contribute, please follow these steps:

1. Fork the repository.

1. Create a new branch for your feature or bug fix.

1. Make your changes and commit them with descriptive commit messages.

1. Push your changes to your forked repository.

1. Submit a pull request, explaining the changes you have made.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as permitted by the license.

______________________________________________________________________

Thank you for your interest in the Collision Avoidance Robot with Ultrasonic Sensor (Relay-Based) project. If you have any questions or feedback, please don't hesitate to reach out. Happy coding!
