An Obstacle Avoiding Bot is an intelligent robot, which can automatically sense and overcome obstacles on its path.

# obstacle-avoiding-car

Hardware Required:
  Arduino Uno
  L293D motor driver
  Ultrasonic Sensor HC-SR04
  Dc motor 300 rpm
  connecting wires
  


## Working principle

The Ultrasonic sensor HC-SR04 is the primary component of the obstacle-avoiding vehicle's operation. The distance from the objects in front of it is calculated by this sensor using the sonar principle. This sensor is used in a lot of projects that need to measure distances quickly and cheaply. Because the sensor is so small and can be mounted anywhere on the chassis, this is possible.

This project consists of four main components: Arduino Uno, Ultrasonic Sensor, DC engine, L293D engine driver.

The car begins to move and the motors begin to rotate as soon as the power supply is connected to the Arduino. In the Arduino code, a threshold distance is set by the user whenever the car approaches an obstacle. The ultrasonic sensor sends a signal to the Arduino if the obstacle's distance falls below this threshold.

After receiving the signal from the ultrasonic sensor, Arduino instructs the motor driver to halt motor rotation.

After that, it signals the driver once more to turn the vehicle to the left.

Additionally, the vehicle is turned to the left until there is no obstruction in front of it. The vehicle resumes its forward motion and continues to advance until it encounters yet another obstacle. This procedure is repeated until the power is turned off. You can customize the code by changing things like the threshold distance to meet your needs. Upload the code that was provided earlier and install the libraries.

Associate the power supply to the Arduino board.
