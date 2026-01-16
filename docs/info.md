<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project uses an SPI-controlled PWM (Pulse Width Modulation) peripheral for the Tiny Tapeout ASIC. The design features:
- SPI interface for serial communication and control
- PWM output signal generation with configurable duty cycle
- 16-bit control registers for output enable and PWM configuration

## How to test

The design can be tested using the provided Cocotb testbench. Load the SPI commands to set the PWM duty cycle and observe the PWM output on the designated output pins.

## External hardware

No external hardware required for basic operation.