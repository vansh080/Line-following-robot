# Construction
This system is made up of-
1) Arduino Uno
2) Motor Driver Shield
3) Wheels (4x)
4) TT Gear Motor (4x)
5) Infrared Sensor
6) 18650 Li-on Battery (2x) 
7) 18650 Battery Holder
8) Female Jumper wire
9) Acrylic Sheet
10) DC Power Switch

- Motor Driver Shield is physically installed on the Arduino Uno Board.
- 4 DC Motors are connected to the Driver Shield through motor channels and ground pins.
- Wheels are attached to the motors.
- These 4 system of motors and wheels are then attached to a Acrylic sheet in an auto mobile mannner
- Arduino and driver shield is placed and screwed on top  of the sheet.
- Infrared sensors are attached in front of the mobile.
- Infrared sensors are then connected to the driver through analog, ground and +5V pins to Out, Gnd, VCC pins of sensors respectively.
- Battery is connect to the driver shield through +M and Gnd pins.

# Working
A line-following Robot operates using sensors to detect a line on the ground and adjust its movement to stay aligned with that line. Here's a basic overview of how it works:

Sensors: The car is equipped with one or more sensors, often infrared or reflective optical sensors, positioned underneath the chassis. These sensors emit light and detect the amount of light reflected back from the surface below.

Line Detection: As the car moves forward, the sensors continuously scan the ground beneath them. When they detect a line, there is a change in the amount of reflected light. This change is used to determine the position of the line relative to the car's current direction of travel.

Control Algorithm: The car is programmed with a control algorithm, often a proportional-integral-derivative (PID) controller, that interprets the sensor readings and determines the appropriate steering adjustments needed to keep the car following the line.

Steering: Based on the output of the control algorithm, the car adjusts its steering mechanism to stay aligned with the line. This could involve turning the wheels or adjusting the speed of individual motors (if it's a differential drive system) to steer the car in the correct direction.

Feedback Loop: The process is continuous, with the sensors providing feedback to the control algorithm, which then adjusts the steering accordingly. This creates a closed-loop system where the car constantly monitors its position relative to the line and makes real-time adjustments to maintain its course.

# Uses

Industrial Automation: Line-following robots are utilized in factories and warehouses for material handling tasks. They can follow lines painted on the floor to navigate through production lines, transport goods between workstations, or deliver items to specific locations within a facility.

Agricultural Automation: In agriculture, line-following robots can be used for tasks like planting, weeding, or harvesting crops. They can follow rows of crops in fields, autonomously navigating between them to perform various agricultural operations with precision.

Security Patrols: Line-following robots equipped with sensors and cameras can be used for security patrols in large areas such as parking lots, warehouses, or industrial facilities. They can follow predefined patrol routes marked by lines on the ground, scanning for any unusual activities or intrusions.

Public Transportation: In settings like airports or train stations, line-following vehicles could be employed for passenger transportation within terminals or between gates. These autonomous vehicles could follow designated paths, providing convenient and efficient transportation for passengers and luggage.


