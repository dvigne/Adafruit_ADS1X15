# Adafruit_ADS1015

Driver for TI's ADS1X15: 12 and 16-bit Differential or Single-Ended ADC with PGA and Comparator

## Info

This fork of the Adafruit ADS1X15 removed the dependency on the Arduino and Wire library and replaces it with a generic I2C library for communication over Linux based systems and GPIO pins like the Raspberry Pi.

This family of ADCs provide 4 single-ended or 2 differential channels.
Each has a programmable gain amplifier from 2/3 up to 16x. Available
in 12 or 16 bit versions:

* [ADS1015 12-bit ADC](https://www.adafruit.com/product/1083)
* [ADS1115 16-bit ADC](https://www.adafruit.com/product/1085)

The chip's fairly small so it comes on a breakout board with ferrites to keep the AVDD and AGND quiet. Interfacing is done via I2C. The address can be changed to one of four options (see the datasheet table 5) so you can have up to 4 ADS1x15's connected on a single 2-wire I2C bus for 16 single ended inputs.

Adafruit invests time and resources providing this open source code, please
support Adafruit and open-source hardware by purchasing products from
[Adafruit](https://www.adafruit.com)!

## Requirements

* https://github.com/amaork/libi2c

## Credits

Thanks to @amaork for creating libi2c

## License

 BSD license, all text above must be included in any redistribution.
