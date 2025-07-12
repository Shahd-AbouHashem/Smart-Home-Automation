# Standard Embedded Diploma - Mini Project 3
## Objective:
To design and implement a smart home system that automates the control of lighting and fan
speed based on environmental conditions. The project uses an ATmega32 microcontroller, LM35
temperature sensor, LDR (Light Dependent Resistor), Flame sensor, and a PWM-controlled
motor. An LCD provides real-time display, and an H-bridge circuit controls the fan motor.
Additionally, LEDs indicate varying light intensity levels.
## Project Overview:
This project involves developing a smart home system that adjusts lighting, fan speed, and safety
alerts based on environmental conditions:
1. Lighting Control: The LDR detects ambient light intensity and controls three LEDs to
indicate different levels of light.
2. Fan Speed Control: The LM35 temperature sensor adjusts the fan speed proportionally to
the room temperature.
3. Fire Detection: A flame sensor detects fire, triggers an alarm, and displays a critical alert
on the LCD.
4. LCD Display: Shows real-time temperature readings, fan status, light intensity, and alerts.
## Features:
• Automatic Lighting Control: Based on the LDR readings, the system controls three LEDs
according to light intensity thresholds.
• Automatic Fan Speed Control: Fan speed is automatically adjusted based on room
temperature, controlled by a PWM signal. The fan operates at different speeds based on
temperature ranges.
• Fire Detection and Alert: The system raises an alarm and displays "Critical alert!" on the
LCD if fire is detected. The system remains in alert mode until the flame is no longer
detected.
• LCD Display: Real-time feedback on system status:
o First Row: Displays "FAN is ON" or "FAN is OFF" based on the fan's state.
o Second Row: Displays "Temp= xxC LDR= xxx%" showing temperature and light
intensity.
