## ideas
The road will be as a Nürburgring race track. The driverless car should pass it.

## Day one
Today, 26 of December 2019 I've got a package from Amazon. Smart Sensor Car Kit. Lovely staff was a motto "Make it easy & Make it Fun". We will check it out soon how easy it is.

![alt amazon's package](https://user-images.githubusercontent.com/3801054/71467434-71d74880-27cb-11ea-8695-bdc8f3fca9f9.jpg)
The PiCar
![alt amazon's package](https://user-images.githubusercontent.com/3801054/71467470-93383480-27cb-11ea-9764-90bacf923e9e.jpg)


## Day two - Building the Car
Today, 02-02-2020 is a perfect day to start building a PI-car.
The car equipped with three sensor modules:
  * ultrasonic obstacle avoidance;
  * light follower;
  * line follower;

Here a list of what I'm going to assemble:
  * Front Half chassis;
  * Front Wheels;
  * Steering Part;
  * Upper Plate;
  * Battery Holder;
  * Rear Wheels (screws)
  * PCB Assembly
  * Rear Wheels (Driving)

![alt_pi_car](https://github.com/olegtikhonov/self-driving-car-pi/blob/master/pictures/what_is_inside.jpg)
![alt_pi_car](https://github.com/olegtikhonov/self-driving-car-pi/blob/master/pictures/what_is_inside_002.jpg)
![alt_pi_car](https://github.com/olegtikhonov/self-driving-car-pi/blob/master/pictures/what_is_inside_003.jpg)

Added rear wheels, two engines and a gear :-)
![alt_pi_car](https://github.com/olegtikhonov/self-driving-car-pi/blob/master/pictures/20200303_145715.jpg)
![alt_pi_car](https://github.com/olegtikhonov/self-driving-car-pi/blob/master/pictures/20200303_145737.jpg)

## How ultrasonic sensor works
Sensor detects objects by emitting a short ultrasonic burst and then “listening” for the echo. Under control of a 
host micro-controller (trigger pulse), the sensor emits a short 40 kHz (ultrasonic) burst. This burst travels through the air, 
hits an object, and then bounces back to the sensor. The PING))) sensor provides an output pulse to the host that will terminate 
when the echo is detected; hence the width of this pulse corresponds to the distance to the target.

## How light follower works
It detects the amount of ambient light by using two light sensors – photo-resistors. Depending on the relation of 
readings between left and right sensor piCar can control rotation of it`s motors to turn itself towards direction of the light source.

## How line follower works
It detects a specific coloured line painted on a surface of different contrast, such as white on black.
Due to the difference of infrared reflection on black and white surfaces, it provides two voltages which can be amplified 
and used as logic states.

 




