---
title: Predominance in Smart Car Competitions
date: '2021-12-12'
summary: Smart car projects involve the development of autonomous vehicles performing complex tasks such as self-perception, decision-making, planning, and control. Ziyan Zhao is capable of independently developing a complete smart car system.
authors:
  - author_ziyan

tags:
  - Embedded Systems
  - Competition
---
{{< icon name="trophy" pack="fas" >}} * In the smart car project, Ziyan Zhao **independently** participated and **won first place** in both ***Meituan Cup 23rd Electronic Design Competition*** and ***TI Cup Tsinghua University 11th Digital System Innovation Contest***. Click to view [Certificate 1](EDC_prize.jpg) and [Certificate 2](TI_prize.jpg).

The smart car project involves designing and programming a vehicle to autonomously execute a series of complex tasks through self-perception, decision-making, planning, and control. These tasks include line following, obstacle avoidance, and reaching designated locations to score points. The competition evaluates the car's ability to intelligently navigate and respond to dynamic environments, testing the effectiveness of its algorithms, sensor precision, and overall design and speed.


```markmap
- STM32 Smart Car
  - Structure
    - Power Supply
      - Lithium Polymer Battery
      - Power Management
    - Motor
      - DC Motor
      - Motor Encoder
    - Wheels
      - Mecanum Wheels
    - Chassis
      - Material Selection
      - Structural Design
  - Hardware Circuit
    - Controller
      - Microcontroller
      - Peripherals
      - Interfaces and Pins
    - Drivers
      - H-bridge Motor Driver
      - PWM Control
    - Sensors
      - Infrared Tracking Sensor
      - Gyroscope
  - Software Algorithms
    - Tracking Algorithm
      - Sensor Data Processing
      - Control Logic
    - Body Control
      - Body Posture Control
      - Closed-loop Speed Control
  - Debugging
    - Software Debugging
      - IDE Usage
      - Real-time Debugging
    - Hardware Testing
      - Circuit Testing
      - Whole Vehicle Testing
```

The design, as outlined in the mindmap, includes:

- Structure: A chassis equipped with Mecanum wheels for maneuverability, powered by a lithium polymer battery and managed by an efficient power system.
- Hardware: Centralized around a TI or ST microcontroller, the car features an H-bridge motor driver for precise motor control, and sensors including infrared for line tracking and a gyroscope for stability.
- Software: Focuses on developing a robust tracking algorithm and body control systems, ensuring precise sensor data processing and effective vehicle posture and speed management.
- Debugging: Involves iterative software and hardware testing, utilizing an integrated development environment (IDE) for real-time debugging and comprehensive testing of the car's circuit and overall functionality.

This design aims to create a smart car that is not only fast but also accurate and adaptable to the varying conditions of the competition.

{{< video src="car1.mp4" controls="yes">}}
{{< video src="car2.mp4" controls="yes">}}
{{< video src="car3.mp4" controls="yes">}}


