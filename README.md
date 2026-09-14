# uSDXn

A simple, buildable, open-source QRP SDR transceiver.

> **The goal is not to create the most advanced uSDX.**  
> **The goal is to create one that you can actually build.**

## About uSDXn

uSDXn is an experimental QRP SDR transceiver project based on the uSDX concept, with a focus on simplicity, affordability, accessibility, and home construction.

The project is being developed with the idea that a radio should not only be technically capable, but also practical for the experimenter to build and understand.

## V1

The first version of uSDXn is being developed for the **40-meter amateur radio band**.

The V1 design uses:

- Arduino Nano / ATmega328P controller
- Si5351 frequency synthesizer
- Analog Core radio architecture
- Standard 1602A LCD
- Mechanical rotary encoder
- Simple push-button controls
- Through-hole components wherever practical
- Modular Controller and Analog Core architecture

## Architecture

The uSDXn is divided into two main functional sections:

### Controller

The Controller provides the user interface and control functions.

It includes:

- Microcontroller
- Display
- Rotary encoder
- Push buttons
- Controller interface

### Analog Core

The Analog Core is the actual radio.

It contains the RF, mixer, audio, transmit, receive, and associated analog circuitry.

The Controller and Analog Core communicate through a defined interface, allowing the Controller to remain relatively generic.

## Project Status

**uSDXn V1 is currently under development.**

The hardware, PCB, firmware, and documentation are being tested and refined before the first official release.

## Hardware

Hardware design files will include:

- Schematics
- PCB design files
- Bill of Materials (BOM)
- Gerber manufacturing files
- Assembly information

## Firmware

The uSDXn firmware will be published in this repository as the V1 development progresses.

## Documentation

Documentation will include:

- V1 Build Guide
- Hardware documentation
- Assembly information
- Testing procedures
- Firmware information
- Technical notes

## License

The uSDXn hardware design is licensed under the:

**CERN Open Hardware Licence Version 2 – Strongly Reciprocal (CERN-OHL-S-2.0)**

See the `LICENSE` file in this repository for the complete license text.
