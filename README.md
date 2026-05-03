📌 Project Overview

This project implements a closed-loop PID control system to regulate the speed of a DC motor using a Raspberry Pi. The system uses encoder feedback to continuously monitor motor speed and adjust the PWM signal in real time, ensuring stable and accurate performance.

⚙️ Features
Closed-loop speed control using PID algorithm

Real-time encoder feedback for accurate speed measurement

PWM-based motor control for smooth operation

PID tuning to minimize overshoot and settling time

Performance analysis of system response

🛠️ Technologies Used

Raspberry Pi

Python

PWM motor control

Encoder interface

Control systems (PID)

📊 System Working

The encoder measures the motor speed and sends feedback to the controller.
The PID algorithm calculates the error between desired and actual speed and adjusts the PWM duty cycle accordingly to maintain the target speed.

🎯 Outcomes
Achieved stable speed control with reduced oscillations
Improved response time through PID tuning
Demonstrated practical implementation of control system theory
