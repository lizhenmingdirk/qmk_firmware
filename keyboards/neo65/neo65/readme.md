# Neo 65Cu

A customizable 85key keyboard.

![Neo 65Cu](https://raw.githubusercontent.com/Linyer-qwq/image/main/Neo 65Cu.jpg)

* Keyboard Maintainer: [LiWenLiu](https://github.com/LiuLiuQMK)
* Hardware Supported: Neo 65Cu PCB with es32fs026 microcontroller

Make example for this keyboard (after setting up your build environment):

    make essemi/Neo 65Cu:default

Flashing example for this keyboard:

    make essemi/Neo 65Cu:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (Esc key) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB
