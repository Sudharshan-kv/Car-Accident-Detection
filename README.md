# Car-Accident-Detection

Arduino-based car accident detection

This project is an Accident Detection System using an Arduino, MPU6050 Accelerometer, Vibration Sensor, Buzzer, and Motor Driver. It detects accidents through sudden changes in orientation and vibrations, and it triggers an alert through a buzzer.

Features: Accident Detection: Uses MPU6050 sensor (gyroscope and accelerometer) to detect sudden tilts. Vibration Detection: Uses a vibration sensor to detect collision impacts. Buzzer Alert: Buzzer rings when an accident is detected. Manual Stop: Button press stops the buzzer. Motor Control: Supports forward, backward, left, right movement for a robot car.

Components Used: Arduino Uno/Nano, MPU6050 Accelerometer + Gyroscope, Vibration Sensor, Buzzer, Push Button, L298N Motor Driver, DC Motors, Power Supply, Connecting wires

Working:

The system continuously monitors the vehicle’s tilt and vibration.
If a severe tilt or collision is detected:
Buzzer sounds an alert.
The alert can be manually stopped using a push button.
Basic car movements (forward, backward, left, right) can be controlled via serial commands.
