# Line Follower Robot controlled by ATmega328p

### Project description
This project includes design a robot, which is controlled by ATmega328p microcontroller. The task of the robot is to follow a line made of black electrical tape placed on a white sheet of paper.
The act of following a line is accomplished by two photoresistors that perform measurments. If the measurment of photoresistor is too low, which means driving onto the tape, the vehicle changes direction
according to requirements. 

The robot is also equipped with a system for adjusting the boundary of direction change, allowing calibration for different light intensities in rooms. 
The project also utilizes UART communication to check the readings from the photoresistors before the robot starts moving.

### Project components
- ATmega328p: Microcontroller responsible for controlling the robot's movement and handling UART communication,
- 2x Photoresistor,
- 2x Motor,
- L298N Motor Driver,
- The remaining: 2x 9V Battery, 2x LED, Potentiometer, 4x Resistor, 3x Button, 2x small contact plate, contact plate, connecting cables, rotation wheel, chassis.

### User manual
- Startup the robot: Connect the microcontroller and power supply.
- (optional) Prepare computer to read the measurments: Connect the microcontroller with computer to start UART communication.
- Calibrating sensors: Place the vehicle so that one photoresistor is above the tape and the other above the paper. Press left button and then right button. The limit for changing the vehicle direction is counted by program.
- Starting driving: Place the vehicle on tape. Press middle (Start) button.
- Ending driving: To stop the motors press middle (Start) button again.

#### Author
Mateusz Synowski
