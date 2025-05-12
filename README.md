# RobotCarProject
`Johnathan Wheeler`

#### Description
Arduino Obstacle-Avoiding Robot Car that contains a L298N, Ultrasonic Sensor, Servo Motor, and made using the Arduino Leonardo.

#### Ultrasonic Sensor
The distance was coded to be converted into centimeters. It sits above the car approx. 9.5 cm above to prevent it from scanning obstacles from below that the wheels could easily roll over. It is on top of the servo motor.

#### Servo Motor
The servo motor scans from left to right after an obstacle is detected and the motors are stopped. It begins in the center of the car orginally. The motor is powered by the 4 1.5V battery box attached to the car, since there was no other power sources availble on my arduino. 

#### L298N
The L298N controls the motors which results in moving the wheels. Before going into this project, I spent my time learning about the driver. The 4 inputs are attached to my arduino digital pins.

#### Instructions
The servo moves from left to right when the car is powered, and the ultrasonic sensor begins to scan. If an obstacle is detected, the servo scans from left to right and then the car turns around 180 degrees and the process is repeated. The spinning is done by rotating wheels in the opposite direction.

