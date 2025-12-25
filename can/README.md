# CAN Communication – C8051F500

## Overview
This repository contains a simple CAN (Controller Area Network) communication project implemented using the **C8051F500** development system. The project demonstrates both the theoretical background and a practical implementation of CAN-based communication between two microcontroller boards.

## Project Description
The project explains the purpose and advantages of CAN communication and demonstrates its operation through a basic two-node CAN network. Two C8051F500 boards are connected via a CAN bus, where each board is equipped with a **switch** and an **LED**.

Pressing the switch on one board sends a CAN message that turns on the LED on the other board, enabling **bidirectional communication**.

## System Functionality
- CAN communication between two C8051F500 microcontrollers
- Switch input on one board controls the LED output on the other board
- Bidirectional message exchange
- Real-time signal transmission over the CAN bus

## Project Scope
The project includes:
- Explanation of CAN usage and its importance in embedded and industrial systems
- Theoretical overview of signal flow from the CAN transmitter to the receiver
- Practical hardware implementation using two C8051F500 development boards

## Technologies Used
- **Microcontroller:** C8051F500
- **Communication Protocol:** CAN (Controller Area Network)
- **Development Environment:** Silicon Labs development tools

## Purpose
This project is intended for **educational purposes** and serves as an introductory example of CAN communication in embedded systems.
