# USB HID Button
Simple Programmable USB HID Button based on the Atmel ATMEGA32u4

![Board Image](https://github.com/miekush/usb-hid-button/blob/main/pcb_ortho.PNG)

# PCB

![Board Image](https://github.com/miekush/usb-hid-button/blob/main/gerber.PNG)

# Programming

In order to minimize the board footprint as much as possible, I decided to program the device over USB using the factory DFU bootloader that comes preprogrammed on the ATMEGA32u4. This eliminates the need for an ICSP header footprint which frees up some space. RESET and HWB are available on test points to enter the device into the DFU bootloader mode.

# License

MKE supports the open source hardware community by sharing hardware design files freely on GitHub!

Please support MKE by purchasing products on [Tindie](https://www.tindie.com/stores/mkengineering/)!

Designed by Mike Kushnerik (miekush)

Licensed under [Creative Commons Attribution-ShareAlike CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)

All text above must be included in any redistribution!
