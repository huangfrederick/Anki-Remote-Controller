# Antimicrobial, Remineralizing Dental Composites

Simple wireless controller for reviewing anki decks. It's just 5 buttons to navigate the desktop UI.

Header file for bluetooth communications were obtained through open source software. Probably wasn't worth the time troubleshooting something written myself if there was already an existing platform for it. See uploaded 'ESP32-BLE-Keyboard' folder for details about the header file code.

Written for esp32 development boards.

Designs were drafted in KiCAD and production was outsourced to JLCPCB. Manufacturing settings can be found from their website.

Rest of the files are ones required by the manufacturer to produce the board.

## Description

### Why This Matters

Med students really like Anki for flashcards. Why do flashcards while sitting at a computer when you can do it from afar simultaneously with other tasks? 

### What This Aims to Achieve

Transmit button inputs as keystrokes to a personal computer.

## Getting Started

* Nothing really here. This is mainly for documentation. You can download the associated scripts used for sending and receiving data from the remote to a computer.
* If you want to make your own remote, you will need 1) any eCAD software, 2) ESP32 development board, and 3) female to male jumper wires with a battery bank or some way to power the board.

### Dependencies

* Again, nothing much here.
* If you want to replicate the workflow here, this'll require an active version of C++, an IDE of your choice, and libraries that are found within the uploaded files.

### Installing

* See uploaded files.

### Executing program

* Upload script to development board through an IDE like VSCode.

## Authors

Frederick Huang
