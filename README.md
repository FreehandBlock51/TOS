# TOS

 A custom OS for the raspberry pi 2

## Requirements

- To build this project on a computer that doesn't use an ARM processor, you'll need a cross-compiler (specifically gcc-arm-none-eabi), which can be downloaded [here](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads).  If you have an ARM processor, you should be able to use regular gcc.  Make sure to update the makefile in the build directory so you use the right compiler.

## Credits

- This project was bootstrapped using jsandler18's tutorial [*Building an Operating System for the Raspberry Pi*](https://jsandler18.github.io/).  You can find the tutorial's source code [here](https://github.com/jsandler18/raspi-kernel/).
