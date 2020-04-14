Quadcopter
Python project for an Raspberry Pi Autonomous Quadcopter Flight Controller

Index
Documentation

README.md - This file
piDrones.pdf - Documentation of piDrone details.
Code
piDrone - Shell script driving qc.py with -O performance parameter
qc.py - Python wrapper allowing automatic use of the pre-compiled .pyc version of Quadcopter.py
Quadcopter.py - Core flight controller code
RC.py - Remote Control code
Flight plans
20s_hover_fp.csv - Example simple flight plan CSV input file to hover a 1m
2m_square_fp.csv - Example flight plan CSV input file to fly a 1m square 1m above the ground
Python libraries
RPIO.tgz - clone of RPIO hardware PWM library (search GitHub for original)
smbus2.zip - clone of I2C variount required for the RC joysticks (search GitHub for original)
PCBs
RPi0-PCB.brd - Eagle board for Raspberry Pi 0 Quad
RPi3-PCB.brd - Eagle board for Raspberry Pi 3 X8
Sensors
IMU_spec.pdf - Invensense MPU-9250 specifications
GPS_spec.pdf - u-blox NEO-M8T specification
Sweep_spec.pdf - Scanse Sweep specification
LiDAR_spec.pdf - Garmin LiDAR-Lite v3 specification
LiDARv3HP_spec.pdf - Garmin LiDAR-Lite v3HP specification
Joystick_spec.pdf - Grayhill 67A specification
