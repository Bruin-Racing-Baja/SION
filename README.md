# SION
Super Informative Operating Name

This repository contains code that will run on the Raspberry Pi on our test bench
It will utilize an Analog Discovery 2 (AD2) device in order to generate and measure waveforms to interact with the Teensy

# Code Components

There will be multiple main components:
 - Library for interaction and control of AD2
 - Tools for aggregating and logging data recorded in Python
 - Python plotting tools

# Data format

The data will be recieved from the Teensy in a very specific way as laid out in the GROND repository
The python script will assume it is getting data in that way, irrespective of order