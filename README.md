# EDuino
A very simple 8 bit computer based on an 8-bit Atmel microcontroller and/or an Arduino board.  
**(c) 2019 by ir. Marc Dendooven (ElDendo)**
## Introduction
EDuino is  part of a series of projects concerning building, extending and programming 8-bit computers. While the other projects focus on old computers or new designs with old components, we wil use a more recent approach here. 8-bit is not dead !
Atmel has a series of 8-bit microcontrollers like the *ATtiny* and the *ATmega* series. They contain not only an 8-bit processor, but also memory and I/O. 
Some of these are used in the *Arduino* boards, a *Libre Hardware* initiative. This means that everybody can build these boards, which make them very cheap. You can get an Arduino micro for less then €2 on online shops like aliexpress. For this price we have a complete computer system. Look [here](https://www.arduino.cc/) if you are new to Arduino. If you don't own an Arduino, you can use a simulator. I will use [Tinkercad Circuits](https://www.tinkercad.com/learn/circuits) to show the progress of the project. 
In this project we wil use it to build a 80's style computer. As the first step we will use a standard Arduino and make a basic interpreter for it. Later we can enhance the system.
## PART 1 - EDuino BASIC
a BASIC Interpreter for Atmel microcontrollers and Arduino
