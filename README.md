# RC-car

### Introduction

Our objective is to develop a simple robot that can be navigated using a remote controller device. This project can be completed easily using Arduino and built in modules but, here we use Pic microcontrollers for developing the robot. C language is used to programm the micro controllers. 

### What you need ?

•	8MHz oscillator

•	22pF capacitors – 2

•	10k resistor

•	Reset button

•	Power button

•	7805 regulators – 2

•	100nF capacitors – 2

•	HC 05 Bluetooth module

•	L293D motor driver IC

•	12V motors

•	850mAh 20C Li-Po battery

You can easily use a L293D motor module rather than builind it from scratch. 

Following circuit diagram will be very helpful in understanding the code given

![image](https://user-images.githubusercontent.com/45971162/55682859-926a2480-5956-11e9-8970-43c4d896c01b.png)

### Lets move straight into programming the PIC micro-controller

The micro-controller used here is PIC16f877A micro-controller. The whole RC car programm can be divided into two parts.
- Interfacing the remote controller with PIC
- L293D interfacing with PIC


