# Gas-Detector

This project is a simple gas leakage detection system designed using an Arduino, the MQ-6 gas sensor, an I2C LCD display, a red LED, and a buzzer.



Components Used:
Arduino Uno

MQ-6 Gas Sensor

I2C 16x2 LCD Display

Red LED

Buzzer

Resistor (220Ω for LED)

Jumper wires & Breadboard

How it Works:
The MQ-6 sensor continuously monitors the air for the presence of gas.

If the gas level exceeds a certain threshold:

The red LED turns on.

The buzzer starts sounding an alarm.

The LCD screen displays a warning message like “GAS DETECTED!”.

If the environment is safe (below the threshold), the system displays “No Gas Detected” on the LCD.

Features:
Real-time gas level monitoring

Visual alert (LED + LCD)

Audio alert (buzzer)

Easy-to-read I2C LCD interface

Benefits:
Enhances home or industrial safety

Useful for kitchens, gas stations, or laboratories

Easy to build and modify for learning or real use
![gas detection](https://github.com/user-attachments/assets/b4afd736-eefd-49a8-afd0-3acae4fc6d6d)
