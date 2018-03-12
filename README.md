# Teensy Radio Controller

We had a radio controller for our RC car. We wanted to be able to have a computer control the car autonomously without hacking into the car. Our solution was have a teensy relay information between the controls on the controller and the radio transmitter. When a human is controlling the car, the teensy keeps a log of all input controls for training data. When a computer is controlling the car, the teensy acts as a ROS node subscribing to the computer's controls and transmits the controls to the car.  

## Authors

* **Ben Mains** - *Initial work* - [Github](https://github.com/)
* **Binit Shah** - *Integration* - [Github](https://github.com/binitshah)
