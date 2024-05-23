# Balance
What?

Using PID I created a see-saw auto balancer that took in an error input from an ultrasonic sensor based on the position of the trolley. This computed error through an Arduino C++ program using PID calculations and outputted an angle for the servo motor to balance the see-saw

How?

Used AutoCAD to design the main chasey, then laser cut it using LightBurn
Designed Joinery pieces and screws using Inventor then 3D printed them
Used an Arduino UNO as the micro-controller, connecting to an ultrasonic sensor and a servo-motor

Results

Using the Ziegler-Nichols tuning method, I was able to get an Auto-Balance time of under .5 seconds for most error positions
