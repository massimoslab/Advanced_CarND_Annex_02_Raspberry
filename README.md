[image1]: ./images/raspberry_pi_3.jpg
[image2]: ./images/raspberry_pi_zero.jpg
[image3]: ./images/raspberry_pi_pins.jp

# Annex 02 : Raspberry Pi Basics

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

## 03. Raspberry Pi 3 pins

The Raspberry Pi is equipped with a set of pins. The pins can be connected to a variety of sensors, motors, and other devices. The pins are of two types:
* digital, and
* analog

Furthermore, the pins can be used in two different ways, either as:
* input, or
* output

The image below shows the different pins of a Raspberry Pi 3 and how they can be used.

![alt text][image3]

## 04. Programming a Raspberry Pi

A Raspberry Pi can used to write programs in different programming languages as with any other computer. Python is by far the most widely used programming language and you will find several examples in internet. The power of python lies mainly in the many libraries which are freely available to be installed. These libraries allow you to use pre-written functions and procedures so that you can focus more on your project.

If you have prior experience in programming, python will be very intuitive to use. Below is a "Hello World" code for the Raspberry Pi.

```
message = "Hello World!"
for i in range(10):
    print(message)
```

#### Understanding the code

The **message = "Hello World!"** line of code assigns the text inside the brackets (*Hello World!*) to the variable **message**. There is no need to define the variable **message** as a sting variable beforehand; python understand this automatically.

The second and third line of the above code is a so-called for-loop. The variable **i** will assume all values between 0 and 10 (10 excluded) and will execute what is defined in the third line, which will print the text contained in the variable **message**.

## 05. Purchases and Downloads
The Raspberry Pi can be purchased from the following link:
[Purchase a Raspberry Pi here](https://www.raspberrypi.org/products/)

## Author

**Massimo Passamonti**: [email me](me@massimoslab.com)

## License

This project and its source code are licensed under the MIT License. [See MIT License](https://github.com/github/choosealicense.com/blob/gh-pages/LICENSE.md) file for more details.
