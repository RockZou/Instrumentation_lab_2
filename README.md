# Instrumentation_lab_2

This code is for NYUAD intrumentation class Lab 2 -- "Linerizing Force Sensitive Resistor"

In situations where the Matlab library method doesn't work, try this instead.

How to use:
	1. Connect the force sensor to Arduino accordingly. Make sure the input pin is A0 (or other analog pins, but you have to change the code a little)
	2. Upload this sketch.
	3. Look at the serial monitor. The number being spit out is the average of 100 readings within the last 500ms. That is, every 5ms, arduino takes a reading, and every 100 readings, arduino takes an average of the most recent 100 readings and give that out in a form of 0-5V and prints that on Serial monitor.