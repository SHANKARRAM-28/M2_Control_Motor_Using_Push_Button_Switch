# Introduction
The ATmega328 is a single-chip microcontroller created by Atmel in the megaAVR family. It has a modified Harvard architecture 8-bit RISC processor core. ATmega328 is an eight bit AVR (Advanced Virtual RISC) based microcontroller.It is a powerful microcontroller with a built-in internal memory of around 32Kb.Most Arduino boards consist of an Atmel 8-bit AVR microcontroller with varying amounts of flash memory, pins, and features. Arduino Uno is a microcontroller board based on the ATmega328.

AVR microcontrollers are very easy to use. All AVR microcontrollers require Integrated Development Environment(IDE) such as Atmel Studio. Using this IDE, we can create, compile and debug program on all AVR microcontrollers.
# About
Here we are going learn how to control the working of motor using a push button switch. First we will connect the two motors with PB2 and PB3 of PORTB of the microcontroller.
A push button switch is then attached to PB0 pin and pulled-up using a resistor. The remaining terminal of the switch is grounded. The function of a pull-up resistor is to insure that while leaving the switch as not pressed, the status of the PB0 pin should remain high. There are 20K pull-up resistors built into the ATmega chip that can be accessed from software also.
But here we are using an external pull-up circuit.
When the switch is pressed, the two motor will starts run and will turn off while we release the switch. This is how the circuit will work.
# Circuit Diagram
![Circuit Diagram](https://user-images.githubusercontent.com/101858144/164627181-e0cb2800-9937-4e32-b1a5-b19d452c47bd.png)
