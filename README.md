# Arduino-IDE-logical-operators

# Arduino Logical Operations (AND, OR, XOR, NOT)

This project demonstrates how to perform **basic logical operations** using an Arduino UNO and LEDs.  
The operations implemented are:

- AND
- OR
- XOR
- NOT (on A and B)
# COMPONENTS REQUIRED
Arduino IDE
proteus
# PROCEDURE
Step 1: Connect all the components as per the circuit diagram. 
Step 2: Open the Arduino IDE.
Step 3: Create a new sketch. 
Step 4: Type the program. 
Step 5: Save the program. 
Step 6: Click Verify to compile the code. 
Step 7: If no errors, connect the Arduino board to the computer via USB. 
Step 8: Select the correct board and port in Arduino IDE.
Step 9: Click Upload to flash the program. 
Step 10: Press the push buttons and observe the behavior of LEDs for each logical operation.
# THEORY
# Introduction

Logical operations are the foundation of digital electronics and computer systems. Using an Arduino, we can simulate logical gates by reading button inputs as binary signals and controlling LEDs as outputs.

The operations implemented are:

AND → LED glows if both inputs are 1.

OR → LED glows if at least one input is 1.

XOR → LED glows if inputs are different.

NOT → LED glows when the input is 0 (inverted signal).

# Arduino

Arduino UNO is an open-source microcontroller board based on the ATmega328P. It has 14 digital I/O pins, 6 analog inputs, operates at 16 MHz, and is programmed using the Arduino IDE. In this project, digital pins are used to read button states and drive LEDs for logical outputs.

# Push Button

A push button provides a digital input (0 or 1) to the Arduino. One terminal is connected to ground, and the other is connected to an Arduino digital pin with a pull-up or pull-down resistor. This allows Arduino to read the input state.

# LED

LEDs are used to visually indicate the result of each logical operation. If the result is 1, the LED turns ON; if the result is 0, the LED remains OFF.

# Working

Two push buttons are connected to Arduino digital pins as logic inputs (A and B).

The Arduino reads the button states using digitalRead().

Depending on the logic gate being simulated, the Arduino computes the result and sends it to LEDs using digitalWrite().

This demonstrates the behavior of AND, OR, XOR, and NOT gates in real-time.

# Applications

Teaching basic logic gate concepts 

Digital electronics experiments 

Educational demonstrations in labs 

Beginner Arduino projects 

Simulation of combinational logic circuits 


