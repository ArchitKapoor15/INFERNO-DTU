# Mars Rover Project

## 📌 Overview
This repository showcases the development and implementation details of our **Mars Rover prototype**, designed for **autonomous and manual operations** in challenging terrains. The rover is built to perform **scientific analysis, object detection, and autonomous navigation** using advanced hardware and software integrations.

<p align="center">
  <img src="Images/Arohn.jpeg" alt="Rover in Action" width="600">
</p>

## 🚀 Key Components

### 🛠️ Microcontrollers
- **Arm Control:** ESP32/STM32 code to manage robotic arm movements.
- **Drive Control:** ESP32/STM32 code for manual driving operations.
- **Sensor Data:** Arduino scripts for publishing and subscribing science sensor data via ROS topics.
- **Wireless Communication:** Utilizes a **2.4GHz / 5GHz antenna** (depending on the competition) for stable data transmission between the rover and the base station.

### 🏎️ ROS Nodes
- **Arm Nodes:** Publish joystick values to control the robotic arm.
- **Drive Nodes:** Publish joystick values for manual driving.
- **Test Scripts:** Simulated scripts to display system behavior when publishing specific values without running the rover.

### 🔹 Autonomous Stack
- **Navigation System:** Scripts to control the rover’s autonomous movement, obstacle avoidance, and path planning.
- **Sensor Integration:** GPS and IMU data collected via an ESP32 module.

## 📸 Rover Gallery  
Here are some images of our rover in action:  
<img src="Images/IMG_6914.jpeg" width="400" height="300"> <img src="Images/IMG_6986.jpeg" width="400" height="300">  
<img src="Images/IMG_8368.jpg" width="400" height="300"> <img src="Images/IMG_6949.jpeg" width="400" height="300">

## 🌟 Features
✅ **Six-Wheel Drive:** Optimized for various terrains, ensuring stability and mobility.  
✅ **6-DOF Robotic Arm:** Capable of precise object manipulation and soil sample collection.  
✅ **Autonomous & Manual Operation:** Operates independently or via remote control.  
✅ **ROS Framework:** Uses the Robot Operating System (ROS) for efficient communication between components.  
✅ **Jetson Nano Computing Unit:** Handles real-time processing for object detection and navigation.  
✅ **Kinect v2 Depth Sensor:** Enables obstacle detection, terrain mapping, and object recognition.  
✅ **Scientific Assembly:** Equipped with sensors to analyze soil samples for potential signs of life.  
✅ **Wireless Communication:** Uses a **2.4GHz / 5GHz antenna** to maintain communication with the base station over an optimal range.  

## 🛠️ Technologies Used
- **Programming Languages:** C++, Python
- **Hardware Components:** Jetson Nano, Kinect v2, Robotic Arm, Antenna Module, Arduino, ESP32
- **Software Frameworks:** ROS, OpenCV
- **Communication Protocols:** ROS Topics & Services, Serial Communication

## 🔮 Future Enhancements
- **SLAM Integration:** Improve mapping and localization.
- **MoveIt Implementation for Arm:** Implementing MoveIt for advanced motion planning of the robotic arm.
- **MoveBase Implementation for Autonomous Stack:** Integrating MoveBase for improved autonomous navigation and obstacle avoidance.
- **Better Terrain Adaptability:** Enhance wheel design and suspension system.
- **Optimized Power Management:** Increase efficiency for extended missions.
- **AI-Based Decision Making:** Improve navigation and object recognition algorithms.
- **Shifting to ROS 2:** Transitioning the entire stack to ROS 2 for better performance and modularity.

## 👥 Contributors
This project is a collaborative effort by the **[Team Inferno DTU]**, a group of passionate engineers and researchers specializing in robotics, AI, and embedded systems.

## 🙌 Acknowledgments
- We extend our gratitude to **[Delhi Technological University]** for providing resources, mentorship, and a platform to develop this project.
- Open-source contributors and ROS community.
