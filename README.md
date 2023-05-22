# Obstacle Avoiding Car using Arduino and Ultrasonic Sensor

This repository contains the code and circuit diagram for an obstacle avoiding car built using Arduino and an ultrasonic sensor. The purpose of this project is to create a simple autonomous car that can navigate through its environment by avoiding obstacles.

## Components Used

To build this obstacle avoiding car, the following components are required:

1. Arduino board (e.g., Arduino Uno)
2. Ultrasonic sensor (e.g., HC-SR04)
3. Motor driver module (e.g., L298N)
4. DC motors (4)
5. Wheels and chassis 
6. Battery or power source (9V DC)

The circuit diagram for connecting the components is provided in the repository. It shows how to connect the Arduino board, ultrasonic sensor, motor driver module, and DC motors together. Make sure to follow the circuit diagram carefully to ensure proper connections.

## Functionality

The obstacle avoiding car works based on the input from the ultrasonic sensor and the control provided by the Arduino board. Here's an overview of its functionality:

Ultrasonic Sensor: The ultrasonic sensor is used to detect obstacles in the car's path. It emits ultrasonic waves and measures the time it takes for the waves to bounce back after hitting an object. Based on this time measurement, the distance to the obstacle is calculated.

Arduino Control: The Arduino board acts as the brain of the car. It receives the distance readings from the ultrasonic sensor and processes them to determine if there is an obstacle nearby.

Motor Control: The motor driver module is connected to the Arduino and controls the DC motors that drive the car's wheels. Depending on the distance readings from the ultrasonic sensor, the Arduino sends signals to the motor driver to control the movement of the car.

Obstacle Avoidance: When an obstacle is detected within a certain range, the Arduino sends commands to the motor driver module to stop or change the car's direction. This allows the car to navigate around the obstacle and continue moving forward.
Usage

## To use this repository, follow these steps:

1. Clone the repository to your local machine.
2. Set up the hardware components as per the provided circuit diagram.
3. Connect the Arduino board to your computer.
4. Upload the Arduino code provided in the repository to the Arduino board using the Arduino IDE or any compatible software.
5. Make sure the power source is connected, and the car is placed in an open environment to avoid collisions.
6. Turn on the car and observe its autonomous obstacle avoidance behavior.

## Conclusion

This project demonstrates the implementation of an obstacle avoiding car using Arduino and an ultrasonic sensor. By following the provided circuit diagram and uploading the Arduino code, you can build your own autonomous car capable of avoiding obstacles. Feel free to modify and expand upon the code and circuit design to add additional features or enhance the functionality of the car. Enjoy exploring the world of robotics and autonomous vehicles!
