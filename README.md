# Firmware for the Rotary Head Controller
This repository is a part of a larger project. The description of it can be found in the [rotary-head-software](https://github.com/JanOlencki/rotary-head-software) repository.

## Description
This repository contains the firmware for the *STM8L101K3T* microcontroller, which is placed on [the PCB of the Rotary Head Controller](https://github.com/JanOlencki/rotary-head-electronics). The firmware is written in C and depends on the IAR Embedded Workbench library for STM8.

## Building and Uploading firmware
The binary can be built using the IAR Embedded Workbench for STM8. There is a SWIM interface exposed on the pin header of the mentioned PCB, which allows uploading the firmware using an ordinary programmer.