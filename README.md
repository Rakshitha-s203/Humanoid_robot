Humanoid Robot using ESP32
Project Overview

This project presents a multi-functional humanoid robot built using the ESP32 microcontroller. The robot is designed to simulate basic human-like actions such as movement, arm gestures, obstacle detection, and interactive feedback through display and audio.

The system integrates multiple hardware components including motors, sensors, servos, and communication modules to create an intelligent and responsive robotic system.

Key Features
1. Autonomous Movement using BO motors
2.Obstacle Detection using Ultrasonic Sensor
3. Human-like Arm Movement using Servo Motors
4.Real-time Display using OLED
5. Audio Output via Bluetooth Audio Module (AT106)
6. Sequential Task Execution (Servo → Motor → Audio)
7. Wireless Audio Control via Bluetooth
8.System Working

The robot operates based on distance detection:

The ultrasonic sensor continuously measures distance.
When an object is detected within a threshold (e.g., 20 cm):
Servo motors perform sequential arm movements.
BO motors drive the robot forward or stop.
OLED displays system status and distance.
Speaker module plays audio feedback.
When no obstacle is detected, the robot remains in idle mode.

 Components Used
🔹 Microcontroller
ESP32 Development Board
Dual-core processor
Built-in WiFi & Bluetooth
🔹 Sensors
Ultrasonic Sensor (HC-SR04)
Used for distance measurement and obstacle detection
🔹 Actuators
BO Motors (DC Motors)
Used for robot movement
Motor Driver (L298N / L293D)
Controls direction of motors
🔹 Servo Motors
2 × Servo Motors
Used for arm movement
Controlled using PWM signals
🔹 Display
OLED Display (SSD1306, 128×64)
Displays distance and robot status
Uses I2C communication
🔹 Audio Module
AT106 Bluetooth Audio Module
Plays audio via Bluetooth connection
Connected to speaker
🔹 Output Device
Speaker (3W / 5W)
Outputs sound from audio module
🔹 Power Supply
5V Battery / Power Bank
External supply for motors & servos
