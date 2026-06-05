# IoT-Based Dual-Axis Solar Tracker

This project focuses on the development of an IoT-enabled dual-axis solar tracker system using Arduino UNO and ESP32 microcontrollers, integrated with the Blynk IoT platform for remote monitoring and control. The system aims to maximize solar energy absorption by rotating the solar panel 180° along both the X and Y axes, ensuring it constantly faces the direction of the strongest sunlight. Light Dependent Resistor (LDR) sensors are used to detect sunlight intensity, guiding the servo motors for precise alignment. The harvested solar energy is stored in a battery, which is then used to power auxiliary devices such as a light and a fan. Users can control these devices remotely through the Blynk mobile application from any location via internet connectivity. In addition, real-time data such as battery charge level, solar panel voltage, ambient temperature, and humidity are displayed on the Blynk interface, providing live environmental feedback. Communication between the ESP32 and the Blynk server is achieved through Wi-Fi, demonstrating the integration of IoT and wireless protocols in embedded systems. This project effectively combines microcontroller interfacing, sensor integration, actuator control, and IoT communication to deliver a smart energy solution. It highlights the importance of efficient energy utilization and showcases the potential of wireless technology in automating and managing renewable energy systems remotely.

## Project Video
A video demonstrating the entire project setup and operation is available in the file `495928011_10094783970565403_445891914178356042_n.mp4`.

## Getting Started

To run this project, you will need:

1.  Arduino IDE installed on your computer.
2.  The necessary boards (Arduino UNO and ESP32) connected via USB.
3.  The Blynk app installed on your smartphone and a configured project dashboard.
4.  Required libraries for the sensors, servo motors, and Blynk integration.

### Steps to upload code:

1.  Clone this repository:
    `git clone <repository-url>`
2.  Open `program-solar-tracker.txt` and `IoT-Solar-Monitoring.txt` in the Arduino IDE.
3.  Ensure your Arduino/ESP32 boards are selected in the Tools menu.
4.  Update the code with your Blynk auth token and Wi-Fi credentials.
5.  Upload the code to your microcontrollers.
