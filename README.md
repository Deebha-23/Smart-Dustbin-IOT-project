♻️ Smart Campus Waste Management System (IoT Based)

An IoT-based Smart Waste Management System designed to monitor garbage bin fill levels in real time using sensors and microcontrollers. This project aims to optimize waste collection, reduce overflow, minimize operational costs, and promote a clean and sustainable campus environment.

📌 Project Overview

Traditional waste collection follows fixed schedules, leading to inefficient collections and overflowing bins. This project solves that problem by using IoT technology to continuously monitor garbage levels and provide alerts when bins are nearly full.
The system uses an Arduino UNO, Ultrasonic Sensor, LCD display, and LED indicators to detect and display garbage fill status. It can be extended to cloud platforms for remote monitoring.

🎯 Objectives

Monitor garbage bin fill levels in real time
Prevent overflow and unhygienic conditions
Optimize waste collection schedules and routes
Reduce fuel consumption and operational costs
Support smart campus and smart city initiatives

🛠️ Hardware Components Used

Arduino UNO R3
Ultrasonic Sensor (HC-SR04)
LCD Display (16x2 with I2C)
LED & Resistors
Connecting wires
Power supply

Software & Tools

Arduino IDE
Embedded C / Arduino Programming
Wokwi Simulator (for virtual testing)
Blynk Library (for IoT integration – optional)

🧩 System Architecture

Ultrasonic sensor measures the distance between the garbage surface and bin top
Arduino processes sensor data
Fill level is calculated and displayed on the LCD
LED glows when bin is nearly full
Serial monitor logs real-time data

⚙️ Working Principle

The ultrasonic sensor emits sound waves and measures the reflected signal
Distance is calculated using time-of-flight
If distance is below a defined threshold:
Bin is considered FULL
LED turns ON
LCD displays alert message
Otherwise, bin status is shown as EMPTY / PARTIALLY FILLED

📊 Results

Reduced unnecessary garbage collection trips
Prevented garbage overflow
Improved campus cleanliness
Provided real-time waste monitoring
System is scalable and cost-effective

👩‍🎓 Developed By

Deebha A
BE – Computer Science Engineering
Agni College of Technology
📧 Email: deebha2022@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/deebha-a-b164332b7
