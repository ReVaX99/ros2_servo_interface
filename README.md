# Interface Micro Servo MS18 with Raspberry Pi using ROS2 Jazzy
This repository serves as a guideline for beginners to create the interface between a Micro Servo MS18 with a Raspberry Pi using ROS2 Jazzy.

A small program is executed to publish the angle of the servo motor in the `servomotor` topic, and rotates the angle to generate motion and test the proper working of the application.

The hardware required to follow the guideline is:
- Micro Servo 9g MS18.
- Raspberry Pi 5 4GB RAM.
- Dupont female-female wires for connections.

![Micro Servo MS18](images/MS18_servo.png)

Software requirements:
- ROS2 Jazzy on Ubuntu 24.04 LTS Server
