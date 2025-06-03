# Smart-Parking---IoT
# Project Objectives:
# The primary objective of this project is to create a real-time parking availability system using IoT sensors, specifically ultrasonic sensors interfaced with an ESP32 microcontroller. The project aims to:
# IoT Sensor Setup:
# The IoT sensor setup includes ultrasonic sensors positioned in individual parking slots. These sensors detect the presence of vehicles by measuring the distance between the sensor and the car. The ESP32 microcontroller processes the sensor data to determine the parking slot's availability.
# The Blynk app serves as a user interface for monitoring parking availability remotely. This displays real-time data about each parking slot's status (occupied or vacant) using virtual pins linked to the ESP32. Users can view parking availability, monitor status changes in real time .
# ESP32 Integration:
# The ESP32 acts as the central controller that processes data from the ultrasonic sensors. It interfaces with the Blynk platform to transmit real-time parking availability data. The ESP32 also controls the OLED display to locally exhibit the parking status.
# Code Implementation:
# The code written for the ESP32 integrates the sensor readings, Blynk API, and display control. It collects data from sensors, communicates with the Blynk platform using Wi-Fi connectivity, updates virtual pins on Blynk, and simultaneously displays parking availability on the OLED screen.
