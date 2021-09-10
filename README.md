# Template for Embedded Rust project on TM4C123

This template has been tested on the Tiva C-Series Launchpad (EK-TM4C123GXL).

## Prerequisites

Install Rust using `rustup`. Add the `thumbv7em-none-eabihf` target.

Other system dependencies: `arm-none-eabi-*` GCC toolchain and `openocd`

## Running the example

Ensure the launchpad is plugged in with the switch set to "DEBUG" and the USB cable plugged in to the debug port.

In one open terminal window, run openocd using the provided configuration: `openocd -f ./openocd.cfg`

In another terminal, execute the program in the GDB debugger by running `cargo run`.
