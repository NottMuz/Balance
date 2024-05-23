# Balance

What?

I engineered an automated see-saw balancer employing PID (Proportional-Integral-Derivative) control. The system utilizes an ultrasonic sensor to detect the trolley's position and determine the positional error. This error is then processed by an Arduino program written in C++, which calculates the necessary corrections using PID algorithms. The output from these calculations adjusts the servo motor's angle to maintain the see-saw's balance.

How?

To create the main chassis, I utilized AutoCAD for the design phase and executed the physical cutting with LightBurn laser cutting software. For the intricate joinery pieces and screws, I designed them in Autodesk Inventor and produced them using a 3D printer. The control system is built around an Arduino UNO microcontroller, which interfaces with an ultrasonic sensor to measure the distance and a servo motor to adjust the see-saw’s angle in real time.

Results

By implementing the Ziegler-Nichols tuning method for PID controllers, I optimized the system to achieve an auto-balance time of less than 0.5 seconds for a wide range of error positions. This rapid response ensures that the see-saw quickly and effectively returns to equilibrium.
