# ECE 1000 RC Car Project
![rcCarRenderCropped](https://github.com/user-attachments/assets/83a0ac1d-7e5d-448c-8d27-549cfa327627)
This GitHub contains all relevant files used during development of our RC car project for ECE 1000.

## Project Summary
In this project, we use a Rasberry Pi Pico WH to emit a bluetooth signal, control a motor driver, and drive a servo.
The entire project works on a 9V battery stepped down to 5V by the motor driver, powering the pi pico, servo, and the DC motor.
We then connect to pi pico to a phone by Bluetooth and control the car through an app from the Google playstore listed here:
https://play.google.com/store/apps/details?id=de.kai_morich.serial_bluetooth_terminal&hl=en_US
Once connected to the RC car you can use the bluetooth terminal to send messages directly to the pi.
We use micro python to read these codes and then turn on a motor and a servo to move and turn the car.

## Project Capabilities 
* Ability to move forward and backward, and to turn left and right
* Bluetooth capabilities up to around 30m (100 ft)
* Low cost, durable, 3D printable chassis
* Runs off a 9V battery that is easily swappable
