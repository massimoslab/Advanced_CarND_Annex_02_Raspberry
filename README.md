[image1]: ./images/raspberry_pi_3.jpg
[image2]: ./images/arduino_micro.jpg
[image3]: ./images/arduino_micro_pins.jpg

# Annex 01 : Raspberry Pi Basics

In this Annex we will explore some of the basics of the Raspberry Pi. More specifically, we will look at:

* the Raspberry Pi device itself
* the programming language used for the Raspberry Pi
* an example of project made with a Raspberry Pi

## 01. The Raspberry Pi

The Raspberry Pi is essentially a computer running on Linux. Like the Arduino, the Raspberry Pi has also several pins in order to:
* process data that are provided as an input to the Raspberry Pi through its input pins, or
* process data so that a signal can be sent to external device through its output pins.

The Raspberry Pi's processor can be compared to that of many computers. The power of the Raspberry Pi is its ability perform multiple tasks. In our case these tasks will be:
* performing computer vision analysis through images provided via a camera
* allow to remotely control the self driving car through the keyboard
* connect complex sensors such as accelerometers, LIDARs, RADARs, GPS, etc.

## 02. The Raspberry Pi devices

The most commonly used Raspberry is the Raspberry Pi 3, shown in the image below:

![alt text][image1]

For our project, however, we do not need the full computational power and pins of the Arduino Uno and we can, therefore, use a cheaper version: the Arduino Micro. The image below shows the Arduino Micro:

![alt text][image2]

There are many other devices that belon to the Arduino family such as: the Arduino Due, Leonardo, Mega, Nano, Zero, M0 and many more.

## 03. Arduino Micro pins

All Arduino boards are equipped with sets of pins. The pins can be connected to a variety of sensors, motors, and other devices. The pins are of two types:
* digital, and
* analog

Furthermore, the pins can be used in two different ways, either as:
* input, or
* output

The image below shows the different pins of an Arduino Micro and how they can be used.

![alt text][image3]

## 04. Programming an Arduino

The language used to program the microcontrollers has very similar characteristics to C and C++. Therefore, if you have already programmed in either of these languages you should not have any particular issue.

Below is a "Hello World" code for the Arduino.

```
void setup() {
  Serial.begin(9600);
}

void loop() {
  Serial.println("Hello World!");
}
```

#### Understanding the code

The **void setup()** function is run first with its content between brackets. The **Serial.begin(9600)** sets up the speed of the serial port to 9600 baud. The baud setting in the serial monitor window must match this value so that the Arduino and serial monitor window are communicating at the same speed.

The **void loop()** function is run second with all its content between brackets.
The **Serial.println("Hello, world!")** sends the text *Hello World!* to the serial / USB port for display in the serial monitor window.

## 05. Purchases and Downloads
The Arduino can be purchased from the following link:
[Purchase an Arduino here](https://store.arduino.cc/)

The Arduino IDE can be downloaded from the following link:
[Download the Arduino IDE here](https://www.arduino.cc/en/Main/Software)

## Author

**Massimo Passamonti**: [email me](mailto:mpweb2.0@gmail.com)

## License

This project and its source code are licensed under the MIT License. [See MIT License](https://github.com/github/choosealicense.com/blob/gh-pages/LICENSE.md) file for details.
