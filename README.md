# 🌟 SUMMARY: 
This project displays an animated Chopper (One Piece) face on a 1.3” SH1106 OLED screen.
The robot shows different facial expressions by switching between bitmap frames.

This project is part of my personal robotics development journey towards building an AI-based robotic companion.

# **⚙️ Project Versions**  
## Version 1 - ESP32 Animated Face

A simple animated face displayed on the OLED screen using an ESP32.
The animation switches between normal and happy expressions using bitmap frames.

**Hardware Used

- Elegoo ESP32 Development Board

- 1.3” SH1106 OLED Display (128x64, I2C)

- 4 Jumper wires

- Breadboard

- Type-C cable
### Wiring
- VDD  → 3.3V
- GND  → GND
- SCK  → D22
- SDA  → D21
  
### Overall Look:
![chopperoled](https://github.com/user-attachments/assets/4b23b2e3-8bb5-47f9-b348-b4867dc9e012)

## Version 2 - Ultrasonic Sensor Interaction (Arduino UNO)
In this version the robot becomes interactive.

An HC-SR04 ultrasonic sensor detects the distance of an object.
- If something comes closer than 5 cm, the robot becomes happy.
- If nothing is nearby, it returns to its normal face.

### Hardware Used

-Arduino UNO

-HC-SR04 Ultrasonic Sensor

-1.3” SH1106 OLED Display

-Breadboard

-Jumper wires
### Overall Look:
