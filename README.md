🌟 SUMMARY: 
-
This is a project I make to create a simple animated Chopper's (One Piece) face and displayed on a 1.3” SH1106 OLED screen using an ESP32.
The robot shows different facial expressions (normal and happy) by switching between bitmap frames.

This is part of my personal robotics development journey towards building an AI-based desktop robotic companion.

Hardware Used:
-
Elegoo ESP32 Development Board,
1.3” SH1106 OLED Display (128x64, I2C),
Jumper wires,
Breadboard

Wiring:
-
VDD - 3.3V,
GND - GND,
SCK - D22,
SDA - D21,

Libraries:
-
Adafruit_GFX,
Adafruit_SH110X,
Wire (I2C)

How I did it:
-
I used PixilArt to create the pixel art and animation. (@ddln - PixilArt account),
This is the site I used to create BitMap with my pixel art - "https://javl.github.io/image2cpp/"

Future Improvements:
-
Add blinking animation,
Add button interaction,
Add buzzer for feedback,
Add Pomodoro timer mode,
Add AI emotion system,
