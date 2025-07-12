# 🔴🔵 Ambulance Lights Project
## 📌 Overview
This project showcases how to blink two LEDs alternately using an Arduino Uno. It's a fundamental digital electronics task that introduces the concept of controlling multiple digital outputs with precise timing.

## 🧰 Components Used
- Arduino Uno board

- Breadboard

- 1x Red LED

- 1x Blue LED

- 2x 220Ω Resistors (to limit current to each LED)

- Jumper wires

## 🔌 Circuit Description
- The Red LED is connected to digital pin 8, and its cathode is grounded through a resistor.

- The Blue LED is connected to digital pin 9, similarly grounded through a resistor.

- The resistors help prevent damage to the LEDs by limiting current.

- Power and ground lines are connected between the Arduino and the breadboard.

## 🧠 Working Principle
The Arduino is programmed to:

1. Turn on the red LED and turn off the blue LED.

2. Wait for a second.

3. Turn on the blue LED and turn off the red LED.

4. Repeat this cycle indefinitely.
