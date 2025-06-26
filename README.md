# Autonomous Obstacle-Avoiding Rover

This project implements a microprocessor-based autonomous rover that can detect and avoid obstacles using an ultrasonic sensor mounted on a servo motor. It uses the Arduino Uno platform, integrating hardware and software components to navigate its environment without human intervention.

---

##  Project Overview

An autonomous four-wheeled rover that:
- Detects obstacles in real-time using an ultrasonic sensor.
- Makes navigation decisions autonomously.
- Demonstrates embedded systems, motor control, and autonomous navigation.

---

##  Objectives

- Build a four-wheeled robot powered by Arduino Uno.
- Implement ultrasonic obstacle detection with servo-mounted scanning.
- Ensure smooth and safe navigation through intelligent decision logic.
- Demonstrate core microprocessor-based design principles.

---

##  Hardware Components

| Component            | Details                                                |
|----------------------|--------------------------------------------------------|
| **Microcontroller**  | Arduino Uno R3 (ATmega328P, 16MHz, 5V)                 |
| **Motors**           | 4x DC motors (3–12V)                                   |
| **Wheels**           | 4x wheels (2.5", plastic + rubber)                     |
| **Motor Driver**     | L298N Dual H-Bridge                                    |
| **Sensor**           | Ultrasonic distance sensor (2–400cm range)             |
| **Servo**            | SG90 (180° rotation, 4.8–6V)                           |
| **Power Supply**     | 4x 3.7V lithium batteries + regulation circuit         |

---

##  Software Overview

- **Language:** C/C++ (Arduino)
- **IDE:** Arduino IDE
- **Control Logic:**
  - Initialize components
  - Scan area using servo-mounted ultrasonic sensor
  - Decide and act on path (forward, turn, reverse)
  - Repeat continuously

---

##  System Architecture

1. **Control Unit:** Arduino Uno  
2. **Locomotion:** 4 DC motors + motor driver  
3. **Sensing:** Ultrasonic sensor on a rotating servo  
4. **Power:** Separate supplies for logic and motors  
5. **Decision Logic:** Autonomous path selection based on real-time sensor input  

---

##  Implementation Steps

1. Construct chassis (wooden) and install motors/wheels.
2. Mount Arduino, sensors, and motor driver.
3. Connect all components according to circuit diagram.
4. Program and test individual components (motor, sensor, servo).
5. Integrate navigation and obstacle avoidance logic.

---

##  Performance Evaluation

- Tested in different lighting and surfaces
- Metrics:
  - Obstacle detection accuracy
  - Navigation consistency
  - Battery life
  - Maneuverability


---

##  Future Improvements

### Hardware:
- Add IR and light sensors
- Use better motor encoders
- Add wireless communication (e.g., Bluetooth)
- Upgrade to a more powerful microcontroller

### Software:
- Add SLAM (mapping and localization)
- Introduce path planning
- Integrate machine learning
- Data logging and UI for control

---

##  Project Preview
![WhatsApp Image 2025-05-21 at 21 50 37_d7104fc9](https://github.com/user-attachments/assets/6d7d98ad-f0f0-4e1e-9163-19e8bae84091)
![WhatsApp Image 2025-05-21 at 21 50 38_e434f9ca](https://github.com/user-attachments/assets/38937004-2229-4b77-b422-f1a7069ec4ca)


