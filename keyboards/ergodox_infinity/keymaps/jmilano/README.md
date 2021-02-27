# jmilano's ergodox_infinity keymap

The keymap for my daily driver...

## Features

Base Layers

- QWERTY
- Function Keys (mousekeys on this layer as well)
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
