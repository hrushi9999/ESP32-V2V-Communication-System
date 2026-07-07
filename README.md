# ESP32 Vehicle-to-Vehicle (V2V) Communication System


## Project Overview
This project is a Vehicle-to-Vehicle (V2V) Communication System developed using two ESP32 boards and the ESP-NOW communication protocol. The main aim of this project is to improve road safety by allowing two vehicles to exchange important information without using the internet.
The system sends alerts such as brake warning, hazard warning, and turn indications from one vehicle to another. When a message is received, it is displayed on an OLED screen, and a buzzer and LED are used to notify the driver.
This project demonstrates how embedded systems can be used to build smart and connected vehicles.


# Objectives
* To develop a real-time communication system between two vehicles.
* To reduce the chances of road accidents by sharing warning messages.
* To learn wireless communication using ESP-NOW.
* To understand the basics of automotive embedded systems.
# Features
* Real-time communication between two ESP32 boards
* Brake alert notification
* Hazard warning notification
* Left and right turn indication
* OLED display for received messages
* LED indication
* Buzzer alert for important warnings
* Low power and low latency communication

  
# Components Used
* 2 × ESP32 Development Boards
* 2 × OLED Displays (SSD1306)
* Push Buttons
* LEDs
* Buzzers
* Breadboards
* Jumper Wires
* USB Cables

  
# Software Used
* Arduino IDE
* ESP32 Board Package
* ESP-NOW Library
* C/C++.

  
# How It Works
1. Two ESP32 boards are paired using ESP-NOW.
2. One ESP32 acts as Vehicle A and the other acts as Vehicle B.
3. When a button is pressed on Vehicle A, a message is sent wirelessly.
4. Vehicle B receives the message instantly.
5. The received message is shown on the OLED display.
6. The LED and buzzer alert the driver about the received warning.

   
# Applications
* Smart transportation systems
* Connected vehicles
* Accident prevention
* Driver assistance systems
* Automotive embedded systems

  
# Future Improvements
* Add GPS to share vehicle location.
* Integrate CAN Bus communication.
* Display vehicle speed in real time.
* Send emergency vehicle alerts.
* Create a mobile app for monitoring.
* Add cloud data logging.

  
# Learning Outcomes
Through this project, I learned about:
* ESP32 programming
* ESP-NOW wireless communication
* Embedded system design
* GPIO and I²C communication
* Real-time message transmission
* Basic automotive communication concepts
* GitHub project organization

  
# Author
**Hrushikesh Parimi**
B.Tech – Electronics and Communication Engineering (Embedded Systems and iot)


# License
This project is created for learning and educational purposes. Feel free to use it for study, research, and personal projects.
