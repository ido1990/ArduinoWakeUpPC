# ArduinoWakeUpPC
This project using an Arduino to keep PC powered on.

# About the project
I needed an option to keep a remote PC powered on all the time.
Wake on lan just didn't want to work properly so that's a nice solution.

# How it works
The Ardunino senses if 5V is present on the pin, if there's no 5V it'll ground the power switch to turn it on.

# Hardware
1. Arduino (Nano in my case).
2. Some jumper wires.

# Shrink it
I tried it with ATTiny85 and it's work great, same code, different pins.
