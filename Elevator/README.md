# Elevator PLC Project

## Overview
A three-floor elevator control system developed in Siemens TIA Portal.

## Hardware & Software
- PLC: Siemens S7-1500
- IDE: TIA Portal V19
- Language: LAD

## Architecture
- FB_Floors – floor management and request handling
- FB_Motor – motor control
- DB1 – global elevator state and request storage
- Instance DBs – function block data storage

## Features
- Three-floor operation
- Floor request queue
- Automatic direction selection
- Door locking logic
- TON timers
- State machine
- Modular FB-based architecture
