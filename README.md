# STRET-O-BOT-Smart-Stretcher-
Description:

The Smart Stretcher uses Arduino to autonomously transport patients within a hospital to designated locations like the operation theater or ICU. Equipped with motors, sensors, and navigation systems, it ensures safe, efficient, and timely movement, reducing manual effort and enhancing hospital workflow.

Project Overview:
The Smart Stretcher is an autonomous stretcher system designed to move patients within a hospital without manual intervention. It aims to assist hospital staff by reducing the need for manpower in patient transport and ensuring timely movement to critical destinations like the operation theater, ICU, or diagnostic rooms.

🔶 Objectives:
* Automate patient transportation within a hospital.

* Reduce human error and manual effort.

* Enhance response time during emergencies.

* Improve patient safety and comfort.

🔶 Key Features:
* Autonomous navigation to predefined hospital locations.

* Obstacle detection and avoidance for safety.

* Pre-programmed destinations (e.g., OT, ICU, Wards).

* Remote control override option for manual control.

* Voice/Touch input for destination selection (optional).

* Compact design suitable for hospital corridors.

🔶 Components Used:
* Arduino Uno / Mega – Main microcontroller.

* Motor Driver (L298N) – To control the motors.

* DC Gear Motors / Servo Motors – For movement.

* Ultrasonic Sensors – For obstacle detection.

* IR Sensors or Line Following Sensors – For path tracking (if line-following is used).

* RFID Module – For location-based navigation (optional).

* Bluetooth/Wi-Fi Module (e.g., HC-05 or ESP8266) – For communication or remote control.

* Battery Pack – Power supply.

* Chassis and Wheels – Structure of the stretcher.

🔶 Working Principle:
* The user selects the destination using buttons or a mobile app.

* The Arduino processes the input and initiates movement.

* Navigation can be based on:

* Line following: Tracks a pre-defined path using IR sensors.

* RFID Tags: Reads RFID tags placed at key hospital locations.

* Map-based Navigation (advanced): Uses Wi-Fi and indoor positioning.

* Ultrasonic sensors ensure that the stretcher avoids obstacles or stops if anything comes in the way.

* Once the stretcher reaches the destination, it stops and signals arrival (buzzer/light).

🔶 Applications:
* Emergency transport in hospitals.

* Hands-free patient movement in large medical facilities.

* Integration into smart hospital systems.

🔶 Future Enhancements:
* Voice command integration.

* IoT-based control and monitoring (e.g., via smartphone or web dashboard).

* Vitals monitoring system for the patient (heart rate, temp, etc.).

* Automatic bed leveling or lifting system.

* Integration with hospital management systems for patient tracking.
