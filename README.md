# Servo Motor Control

This project demonstrates how to control four servo motors using Arduino Uno in Tinkercad.  
The servos first perform a sweep motion from 0° to 180°, then all reset to 90° position.  
The goal is to simulate basic servo behavior for robotics or mechanical applications.

Components Used:
- Arduino Uno
- 4 × Servo Motors
- Jumper wires

How it works:
1. Each servo is connected to a separate digital pin.
2. The servos move from 0° to 180° in sync with a small delay.
3. After the sweep, all servos are set to 90° and remain there.
4. The loop ends after this action (no repetition).

Code Overview:
- Uses the built-in Servo library in Arduino.
- Each servo is defined and attached to a digital pin.
- Motion is controlled using `servo.write(angle)`.
