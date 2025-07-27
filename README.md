COMPANY:CODTECH IT SOLUTIONS 
NAME:MARILAKSHMI S 
INTERN ID:CT04DH848
DOMAIN:EMBEDDED SYSTEMS
DURATION:4 WEEKS
# Task-4-Speech-Recognition-System
A simulated emergency alert system that responds to voice commands like "HELP" or "FIRE" using Serial Monitor. Activates LED and buzzer alerts for quick response in critical situations.
Project Description: 
        This project simulates an emergency voice-activated alert system using an Arduino Uno, designed for situations such as fire, danger, or medical emergencies. Since voice input is not natively supported in Tinkercad, the system simulates voice commands using the Serial Monitor as input.  
        When a user enters predefined emergency commands like "HELP", "FIRE", "ALERT", or "DANGER" in the Serial Monitor (as if received from a voice recognition module), the system activates an alert mechanism:
        A red LED blinks to signal emergency
        A buzzer sounds an alarm for a few seconds
The system also rejects invalid or non-emergency inputs, simulating real-world command filtering.
This simulation demonstrates how embedded systems can respond to voice-based triggers in emergency scenarios, especially in areas like:
Home safety systems
Women's safety devices
Fire alert systems
Elderly care assistance


This project simulates a speech recognition-based emergency alert system using **Arduino Uno**, designed in **Tinkercad**.
Since Tinkercad doesn't support real-time voice input, we simulate recognized voice commands through the **Serial Monitor**.
##  Features
- Accepts emergency commands: `HELP`, `ALERT`, `FIRE`, `DANGER`
- Triggers an **LED alert** and **buzzer sound** for 2 seconds
- Ignores non-emergency inputs (e.g., "HELLO", "HI")
## System Simulation (Voice → Action)

| Simulated Command | Action |

| `HELP` | LED ON +  Buzzer sound (2s) |
| `ALERT` |  LED ON +  Buzzer sound (2s) |
| `FIRE` |  LED ON +  Buzzer sound (2s) |
| `DANGER` |  LED ON +  Buzzer sound (2s) |
| `Other` |  No action – marked as safe |
## Components Used
- Arduino Uno
- Red LED
- Buzzer
- 220Ω Resistor
- Serial Monitor (for input)

  
click here to watch the output demo:
https://drive.google.com/drive/folders/10vHvR0fS1olQ8mPNWyz6s_rVuGryVLsx?usp=drive_link
