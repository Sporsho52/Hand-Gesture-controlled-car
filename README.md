This project presents a hand-gesture-controlled bot. It combines real-time computer vision, machine learning, and embedded systems to create an intuitive, contactless robot control system.

Using a webcam, the system captures hand gestures via OpenCV and Google's MediaPipe library. Detected gestures are translated into movement commands (forward, backward, left, right, stop) and transmitted to an ESP32 microcontroller, which controls the bot's motors accordingly.

This solution emphasizes simplicity, low-cost hardware, and ease of use while incorporating advanced concepts like gesture recognition and serial communication.

Features:

✅ Real-time hand gesture detection using MediaPipe

✅ Wireless control via Bluetooth or USB Serial

✅ Supports basic movement commands: forward, backward, left, right, and stop

✅ Low-cost, easily accessible components

✅ Structural stability with vibration and heat management considerations


Technologies Used:

Python (OpenCV, MediaPipe)

ESP32 Microcontroller

Arduino IDE

Motor Driver: L298N


Hardware Components:

ESP32 Dev Board

L298N Motor Driver Module

BO Motors with Wheels

Robot Chassis

Battery Pack and Charging Module

Jumper Wires, Zip Ties, Screws, and other basic hardware

Software Requirements

Python 3.8+

VS Code / PyCharm / Thonny / IDLE

Arduino IDE with ESP32 Board Package

Required Libraries: OpenCV, MediaPipe, WiFi.h, WiFiUdp.h


Project Structure:

Gesture detection using MediaPipe on a laptop

Command transmission to ESP32 via Bluetooth/Serial

ESP32 interprets commands and drives motors accordingly

Mechanical design optimized for balance, load distribution, and vibration resistance

Getting Started

Clone the repository

git clone https://github.com/yourusername/recruitment-gesture-bot.git

Set up the Python environment and required libraries.

Upload the Arduino code to the ESP32.

Run the Python script for gesture detection.

Control the bot using predefined hand gestures.



Contributions and improvements are welcome! Please open an issue to discuss changes before submitting pull requests.
