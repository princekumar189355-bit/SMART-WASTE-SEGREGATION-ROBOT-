# SMART-WASTE-SEGREGATION-ROBOT-

Overview

The AI Smart Waste Segregation Robot is an Arduino-based educational prototype that automatically detects and sorts waste into different categories using sensors and servo motors. The system demonstrates how embedded systems and automation can support smarter waste management by directing waste into biodegradable, recyclable, and non-recyclable bins.

---

Features

- Automatic waste detection
- Three-bin waste segregation
- Servo motor-controlled sorting mechanism
- Ultrasonic sensor for object detection
- OLED/LCD display for system status
- LED indicators for operation
- Buzzer for notifications
- Arduino Uno-based control system
- Simple and low-cost educational prototype

---

Components Used

- Arduino Uno R3
- HC-SR04 Ultrasonic Sensor
- 3 × SG90 Servo Motors
- OLED/LCD Display
- Active Buzzer
- Red, Yellow, and Green LEDs
- Breadboard
- Jumper Wires
- Resistors (220Ω)
- Robot Chassis
- Three Waste Bins
- Battery Holder / 5V Power Supply
- USB Cable

---

Working Principle

1. The ultrasonic sensor detects an object placed in front of the robot.
2. The Arduino processes the sensor input.
3. Based on the programmed sorting logic, the corresponding servo motor opens the appropriate waste bin.
4. LEDs and the buzzer indicate the system status.
5. The OLED/LCD display shows messages such as "System Ready" or "Waste Sorted".
6. After sorting, the servo returns to its initial position, ready for the next object.

---

Pin Connections

Component| Arduino Pin
Ultrasonic TRIG| D2
Ultrasonic ECHO| D3
Servo Motor 1| D5
Servo Motor 2| D6
Servo Motor 3| D7
Buzzer| D8
Green LED| D9
Yellow LED| D10
Red LED| D11
OLED SDA| A4
OLED SCL| A5

---

Applications

- Smart waste management demonstrations
- School and college science exhibitions
- Robotics and Arduino learning
- Environmental awareness projects
- Embedded systems education

---

Advantages

- Low-cost prototype
- Easy to understand and demonstrate
- Encourages proper waste segregation
- Improves knowledge of automation and robotics
- Expandable with AI and IoT features

---

Future Scope

- AI camera for automatic waste classification
- IoT-based remote monitoring
- Mobile application integration
- Cloud data storage and analytics
- Automatic bin fill-level monitoring
- Solar-powered operation

---

Safety Notes

- Check all wiring before powering the circuit.
- Use a regulated 5V power supply.
- Disconnect power before modifying connections.
- Keep liquids away from electronic components.
- Use only lightweight demonstration objects during testing.

---

Project Structure

AI_Smart_Waste_Segregation_Robot/
│
├── README.md
├── AI_Smart_Waste_Segregation_Robot.ino
├── Circuit_Diagram.png
├── BOM.csv
├── Project_Report.pdf
├── Project_Journal.pdf
├── Photos/
├── Demo/
└── Documentation/

---

Conclusion

The AI Smart Waste Segregation Robot demonstrates how Arduino, sensors, and servo motors can be integrated to automate waste sorting in an educational prototype. The project promotes environmental awareness while helping students learn embedded systems, robotics, and automation concepts.

---

Author

Prince Kumar

Student | Arduino Enthusiast | Robotics Learner

---

License

This project is released under the MIT License for educational purposes.