Raspberry PI OLED Library Driver
================================

This is the port of some of the most used OLED drivers such as the Adafruit, Seeedstudio, Tindie, Generic... to
the Raspberry Pi. It can drive OLED with chipset such as SSD1306, SH1106, SSD1327 and SSD1308

This library replace the previous one named [ArduiPi_SSD1306][1]

This has been ported to work with the ArduiPi Project but it can work on almost any Raspberry PI.


Installation
============

Everything is documented on this dedicated [post][2] my [blog][3]


[1]: https://github.com/hallard/ArduiPi_SSD1306
[2]: http://hallard.me/adafruit-oled-display-driver-for-pi/
[3]: https://hallard.me

Cross compilation
=================

For corsscompilation under ubuntu set the following  environmentvariables:

``` CROSS_CXX ```, ``` CROSS_CC ``` and ```SYSROOT_PATH```

Example for the raspberry pi toolchain:
```
export CROSS_CXX=/tools/arm-bcm2708/gcc-linaro-arm-linux-gnueabihf-raspbian-x64/bin/arm-linux-gnueabihf-g++
export SYSROOT_PATH=/sysroot
```