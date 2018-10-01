# RPi_Heartbeat_Sensor
This code is build from different codes and it aims to show a heartbeat measurement, using Raspberry Pi and ADC converter MCP3208 or MCP3008
This code is built from https://github.com/tutRPi/Raspberry-Pi-Heartbeat-Pulse-Sensor/blob/master/pulsesensor.py but instead of using 
"from MCP3208 import MCP3208", which often causes permission errors, this code uses spidev channels that take data by bits.
However, this code is still work in progress.
