# BEAM-microbots
In this project I create microrobots with the ability to unite
---
## About progect
---
This project is dedicated to the creation of simple microrobots with the ability to combine into a single organism, imitating the behavior of simple organisms (for example, beetles). To load the project into the microcontroller, the UsbAsp program is required.

## Project goals
---
* develop a robot design
* develop a robot program
* create a robot prototype
* create a printed circuit board
  
## Where is everyfhing?
---
The frimware folder contains an ino file with the program. In the hardware folder there is a gerber file with a printed circuit board. The 3D folder stores parts to be printed on a 3D printer.

## How load code for Attiny13?
---
 To add Attini 13 support, launch the Arduino IDE and select File > Preferences. Copy the following URL into the Additional Board Manager URLs field: https://raw.githubusercontent.com/sleemanj/optiboot/master/dists/package_gogo_diy_attiny_index.json.
 ![Alt-text](https://voltiq.ru/wp-content/uploads/program-attiny-13-attiny-13-a-arduino-ide-5.jpg "Ork")
## Hardware
---
The microrobot runs on attini13. The robot receives information from the environment using a photoresistor, moves using a vibration motor, and also sends signals using an SMD LED located next to the printed circuit board.
## How it work
---
On top of the robot there is an LED and a photoresistor. If the light on the street or in the room is too bright, then the robot is inactive; if the light is too bright, then the robot is also inactive. When the light is not too bright, but not yet dark, the robot begins to move using a vibration motor and flashes the LED.
Robots can be united using magnets located on the edges of the robot.

