# Keychron K3V2 RGB ISO


*A 75% keyboard sold by keychron*

* Keyboard Maintainer: [definethis](https://github.com/KeijoMika) (based on work of dexter93 on a previous branch)
* Hardware Supported: *Keychron K3V2 RGB, MCU: SN32F248BF*
* Hardware Availability: *https://www.keychron.com/products/keychron-k3-hot-swappable-wireless-mechanical-keyboard*

Compile example for this keyboard (after setting up your build environment):

    qmk compile -kb keychron/k3/rgb/v2/optical_iso -km default

Compile example for this keyboard with VIA (after setting up your build environment):

    qmk compile -kb keychron/k3/rgb/v2/optical_iso -km via

This keyboard must be flashed with an external [GUI](https://github.com/SonixQMK/sonix-flasher) or [CLI](https://github.com/SonixQMK/SonixFlasherC)



See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Physical Bootloader Pins**: Turn off the keyboard, Using a pair of tweezers or a paperclip, short the 2 pins left from spacebar switch holes and hold the tweezers on the pins while turning the keyboard on, this should put it into the bootloader.
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available. In the default keymap Fn+Esc.
