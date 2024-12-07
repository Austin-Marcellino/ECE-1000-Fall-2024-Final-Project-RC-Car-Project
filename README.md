# ECE 1000 RC Car Project
![rcCarRenderCropped](https://github.com/user-attachments/assets/83a0ac1d-7e5d-448c-8d27-549cfa327627)

This GitHub contains all relevant files used during development of our RC car project for ECE 1000.

## Project Summary
In this project, we use a Rasberry Pi Pico WH to emit a bluetooth signal, control a motor driver, and drive a servo.
The entire project works on a 9V battery stepped down to 5V by the motor driver powering the pi pico, servo, and the DC motor.
We then connect to pi pico to a phone by Bluetooth and control the car through an app from the Google playstore listed here:
https://play.google.com/store/apps/details?id=de.kai_morich.serial_bluetooth_terminal&hl=en_US

Once connected to the RC car you can use the bluetooth terminal to send messages directly to the pi.
We use micro python to read these codes and then turn on a motor and a servo to move and turn the car.
The RC car chassis was custom made for this project in Fusion 360.

## Project Capabilities 
* Ability to move forward and backward, and to turn left and right
* Bluetooth capabilities up to around 30m (100 ft)
* Low cost, durable, 3D printable chassis
* Runs off a 9V battery that is easily swappable

## Links
Viewable Fusion 360 File:
https://a360.co/4gidKkq

6V-12V DC Motor:
https://www.amazon.com/AUTOTOOLHOME-Torque-Traxxas-Wheels-Electric/dp/B01M58POHF/ref=sr_1_31?sr=8-31

Servo Motor:
https://www.amazon.com/WWZMDiB-SG90-Control-Servos-Arduino/dp/B0BKPL2Y21/ref=sxin_16_pa_sp_search_thematic_sspa?cv_ct_cx=Micro%2BServo%2BMotor&s=toys-and-games&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sr=1-1-6024b2a3-78e4-4fed-8fed-e1613be3bcce-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9zZWFyY2hfdGhlbWF0aWM

Motor Driver Controller Board:
https://www.amazon.com/WWZMDiB-L298N-H-Bridge-Controller-Raspberry/dp/B0CR6BX5QL/ref=sr_1_1_sspa?sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1

5mm x 300mm Hex Rod:
https://www.amazon.com/Feelers-Stainless-Opposite-Hexagonal-Length/dp/B0BPGPT7BS/ref=sr_1_4?sr=8-4

608 Ball Bearings:
https://www.amazon.com/SHKI/dp/B09PKD8QZZ/ref=sr_1_4?sr=8-4
