This project presents a gesture-controlled bot. It combines real-time computer vision, machine learning, and embedded systems to create an intuitive, contactless robot control system.
Using a webcam, the system captures hand gestures via OpenCV and Google's MediaPipe library. Detected gestures are translated into movement commands (forward, backward, left, right, stop) and transmitted to an ESP32 microcontroller, which controls the bot's motors accordingly. 

This solution emphasizes simplicity, low-cost hardware, and ease of use while incorporating advanced concepts like gesture recognition and serial communication.

Features
•	✅ Real-time hand gesture detection using MediaPipe
•	✅ Wireless control via Bluetooth or USB Serial
•	✅ Supports basic movement commands: forward, backward, left, right, and stop
•	✅ Low-cost, easily accessible components
•	✅ Structural stability with vibration and heat management considerations

Technologies Used
1.	Python (OpenCV, MediaPipe)
2.	ESP32 Microcontroller
3.	Arduino IDE
4.	Motor Driver: L298N
   
Hardware Components
1)	ESP32 Dev Board
2)	L298N Motor Driver Module
3)	BO Motors with Wheels
4)	Robot Chassis
5)	Battery Pack and Charging Module
6)	Jumper Wires, Zip Ties, Screws, and other basic hardware
7)	Software Requirements
1.	Python 3.8+ (Mediapipe will not run if python 3.15+ is installed) 
2.	VS Code and Pycharm
3.	Arduino IDE with ESP32 Board Package
4.	Required Libraries: OpenCV, MediaPipe, WiFi.h, WiFiUdp.h
   
Project Structure
1.	Gesture detection using MediaPipe on a laptop
2.	Command transmission to ESP32 via Bluetooth/Serial
3.	ESP32 interprets commands and drives motors accordingly
4.	Mechanical design optimized for balance, load distribution, and vibration resistance
   
Getting Started
1.	Clone the repository
git clone https://github.com/yourusername/recruitment-gesture-bot.git
2.	Set up the Python environment and required libraries.
3.	Upload the Arduino code to the ESP32.
4.	Run the Python script for gesture detection.
5.	Control the bot using predefined hand gestures.

Contributions and improvements are welcome! Please open an issue to discuss changes before submitting pull requests.

