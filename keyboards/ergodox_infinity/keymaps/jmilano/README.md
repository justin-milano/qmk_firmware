# Qu4z can haz ergodox

Duplicates the layout I made for myself in the configurator that I:C will probably stop supporting any day now.
More importantly: All of my keyboards' firmware now builds from the same codebase!

## Features

Base Layers

- QWERTY
- Function Keys
- Numpad

## Building and flashing

1. Put your board in DFU mode with either the button on the bottom, or with a software key in your current firmware
2. Flash left half:
    ```bash
    make ergodox_infinity:jmilano:dfu-util
    ```
3. Flash right half:
    ```bash
    make ergodox_infinity:jmilano:dfu-util MASTER=right
    ```
