# G940 Total Conversion Kit
FFB Joystick Base Mod

This Mod is based on the gimbal design of: https://github.com/o-devices/bldc-ffb-joystick-base and the custom firmware patch by fred41: https://github.com/fred41/G940-firmware-fixes

![IMG_20210424_142404](https://user-images.githubusercontent.com/83156433/115984653-8f2b4b00-a5a8-11eb-8ae3-cd5bdb20b1a4.jpg)

It only uses the main PCB of the original G940 joystick base, it's magnetic axis sensor, the DC motors and the patched firmware.
Features:
- sturdy plywood construction (8mm laser cut)
- stronger gimbal for custom grips and extensions (designed by https://github.com/o-devices)
- active cooling via two 40mm 5V fans (USB powered)
- enhanced axis sensor precision without backlash
- lots of room for customization and addons

The main concept is a modifiable "gimbal tower" design, where you can add and change parts to fit your needs for customization.
![Gimbal_Tower](https://user-images.githubusercontent.com/83156433/115985229-22fe1680-a5ab-11eb-8fc5-f7e652d623b5.jpg)

![4](https://user-images.githubusercontent.com/83156433/115985722-68bbde80-a5ad-11eb-8a9d-f3659ec7684f.jpg)

The heart of the "Gimbal Tower" is the "Sensor Tower" to scale the axis deflection of the gimbal (~20° in every direction) down to ~15° for the Melexis magnetic sensor.

![SensorTower_design](https://user-images.githubusercontent.com/83156433/115985948-67d77c80-a5ae-11eb-8803-757ecc573d65.jpg)
![Screenshot 2021-04-18 104225](https://user-images.githubusercontent.com/83156433/115987027-9e63c600-a5b3-11eb-99f0-f029d3b58b45.jpg)


The pulleys are modified for 366-3M-9 timing belts (2x).

For stick extensions you can modify the firmware patch's main axis scaling. https://github.com/fred41/G940-firmware-fixes
fred41 was so kind to provide preset values with matching checksums:

Scale: 0x48 |  72 CRC32: 0x9cfb053c (huge)

Scale: 0x4c |  76 CRC32: 0xe12649ba

Scale: 0x50 |  80 CRC32: 0x94f5b39f (default)

Scale: 0x54 |  84 CRC32: 0xe928ff19

Scale: 0x58 |  88 CRC32: 0x6f4f2a93

Scale: 0x5c |  92 CRC32: 0x12926615

Scale: 0x60 |  96 CRC32: 0x84e8ded9

Scale: 0x64 | 100 CRC32: 0xf935925f

Scale: 0x68 | 104 CRC32: 0x7f5247d5 (recommended for Virpil's Flightstick Extension - 200mm)

Scale: 0x6c | 108 CRC32: 0x28f0b53

Scale: 0x70 | 112 CRC32: 0x775cf176

Scale: 0x74 | 116 CRC32: 0xa81bdf0

Scale: 0x78 | 120 CRC32: 0x8ce6687a

Scale: 0x7c | 124 CRC32: 0xf13b24fc

Scale: 0x80 | 128 CRC32: 0x27342928

Scale: 0x84 | 132 CRC32: 0x5ae965ae

Scale: 0x88 | 136 CRC32: 0xdc8eb024

Scale: 0x8c | 140 CRC32: 0xa153fca2

Scale: 0x90 | 144 CRC32: 0xd4800687 (very small)

