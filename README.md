# EDES301 Project 01

Embedded Systems Digital I/O project for ATmega324PB.

## Project Overview
This project implements a digital I/O system with the following features:
- LED control
- Button input handling
- Timer-based operations

## Hardware Requirements
- ATmega324PB microcontroller
- LEDs (various colors)
- Push buttons
- Supporting passive components

## Software Tools
- AVR-GCC compiler
- AVRDUDE programmer
- VSCode with C/C++ extensions

## Building
```bash
make clean
make
```

## Programming
```bash
make program
```

## Project Structure
- `src/` - Source files
- `inc/` - Header files
- `Makefile` - Build configuration