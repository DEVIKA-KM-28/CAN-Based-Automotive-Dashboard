# CAN-Based-Automotive-Dashboard

Overview
This project is a CAN-Based Automotive Dashboard System developed using the PIC18F4580 microcontroller. The system monitors and displays real-time vehicle parameters such as speed, RPM, gear position, and indicator status using a CLCD display. CAN (Controller Area Network) protocol is used for communication between nodes to ensure reliable and efficient data transfer in automotive applications.

Features
Real-time vehicle parameter monitoring
Display of Speed, RPM, Gear Position, and Indicator Status
CAN message transmission and reception
CLCD-based dashboard display
Embedded C implementation for real-time processing
Peripheral interfacing with ADC, Timers, and Digital Keypad
Efficient vehicle monitoring system

Technologies Used
Embedded C
PIC18F4580 Microcontroller
CAN Protocol
MPLAB X IDE
XC8 Compiler
CLCD (Character LCD)
ADC
Timers
Digital Keypad
UART Communication

Hardware Components
PIC18F4580 Microcontroller
MCP2551 CAN Transceiver
CLCD Display
Potentiometer/Sensors for ADC input
Push Buttons/Digital Keypad
Power Supply Unit
Connecting Wires and Breadboard

Software Requirements
MPLAB X IDE
XC8 Compiler
Proteus (Optional for Simulation)

Project Working
Vehicle parameters are collected using sensors and ADC inputs.
The PIC18F4580 processes the data in real time.
CAN protocol is used for communication between nodes.
The processed information is displayed on the CLCD dashboard.
Indicators and gear status are updated dynamically based on user input and CAN messages.

Learning Outcomes
Understanding of CAN communication in automotive systems
Real-time embedded system development
Peripheral interfacing with PIC microcontrollers
Embedded C programming and debugging
CLCD interfacing and display management

Future Enhancements
GPS integration for vehicle tracking
IoT-based cloud monitoring
Touchscreen dashboard interface
Fault detection and diagnostics system
Wireless CAN monitoring
