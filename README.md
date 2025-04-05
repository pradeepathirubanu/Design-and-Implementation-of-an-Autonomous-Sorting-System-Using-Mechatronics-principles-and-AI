Design and Implementation of an Autonomous Sorting System Using Mechatronics principles and AI

Project Overview
This project implements an intelligent, autonomous sorting system that uses mechatronics components and artificial
intelligence (AI) to identify and sort objects based on physical attributes such as shape, size, and color. 
It automates the sorting process with high accuracy and adaptability for industrial and smart automation applications.


Features
AI-driven object detection and classification using computer vision

Dual-stage conveyor system for efficient object flow

Robotic arms and sensors for precise object handling

Real-time feedback and dynamic control

Scalable design suitable for various environments


Technologies Used
Hardware:
Raspberry Pi (for AI and image processing)

Arduino Uno (for sensor and actuator control)

IR Sensor, Ultrasonic Sensor, Color Sensor (e.g., TCS3200)

Servo Motors, Robotic Arms, Pneumatic Actuators


Software:
Python (OpenCV, TensorFlow Lite)

Arduino IDE (C/C++)

ML: Convolutional Neural Networks (CNN) for object classification


System Architecture
Dumping Zone: Mixed objects are placed.

Primary Conveyor: Moves objects under an AI camera.

AI Camera: Detects and classifies objects using ML.

Robotic Arm 1: Picks and places objects onto a secondary conveyor.

Secondary Conveyor: Moves objects for precise sensing.

Sensors: Validate attributes (size, color, shape).

Robotic Arm 2 / Pneumatic Actuator: Sorts objects into appropriate bins.


Goals
Minimize manual intervention

Improve sorting accuracy and speed

Enable adaptability to untrained objects

Provide a cost-effective, scalable automation solution


Future Enhancements
Integrate cloud-based training for improved learning

Add weight sensors for material-based sorting

Enable handling of multiple objects simultaneously

