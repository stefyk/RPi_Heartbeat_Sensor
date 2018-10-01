# RPi_Heartbeat_Sensor

This code is built from https://github.com/tutRPi/Raspberry-Pi-Heartbeat-Pulse-Sensor/blob/master/pulsesensor.py and it aims to show a heartbeat measurement, using Raspberry Pi and an ADC converter MCP3208 or MCP3008. 
However, instead of using "from MCP3208 import MCP3208", which often causes permission errors, this code uses spidev channels that require identifying the specific bits in the code (start bit, choosing channels ect.) at the moment the identified bits are for a 10-bit ADC, however this code can be easily adjusted for a 12-bit ADC. For more information on how to use spidev, please read:
https://learn.sparkfun.com/tutorials/raspberry-pi-spi-and-i2c-tutorial#spi-on-pi
or https://learn.sparkfun.com/tutorials/python-programming-tutorial-getting-started-with-the-raspberry-pi/experiment-3-spi-and-analog-input
This project is still work in progress.
