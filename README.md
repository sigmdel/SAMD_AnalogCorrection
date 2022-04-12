# SAMD21/SAMD51 Analog Correction

## Sets and enables the digital correction logic of the SAMD ADC.

SAM D21 and SAM D51 microcontrolers are supported in this version which was pulled from the [Seeed-Studio SAMD Arduino core 1.7.0](https://github.com/Seeed-Studio/ArduinoCore-samd/tree/1.7.0/libraries/SAMD_AnalogCorrection). It was removed from that fork of the core in later versions.

## Upstream versions

The library available in the current (1.8.13) [Arduino SAMD Arduino Core](https://github.com/arduino/ArduinoCore-samd/tree/master/libraries/SAMD_AnalogCorrection) does not support the SAM D51.

The library available in the current (1.8.13) [Adafruit fork of the SAMD Arduino Core](https://github.com/adafruit/ArduinoCore-samd/tree/master/libraries/SAMD_AnalogCorrection) supports both version of the microcontroler but it also pulls in the `Adafruit_TinyUSB` library if the `USE_TINYUSB` macro is defined. Presumably this would be of value if `TinyUSB` is used.

## Installation

Obtain the library by clicking on the green **Code** button, then on `Download ZIP`. 

Follow the [Importing a .zip Library](https://docs.arduino.cc/software/ide-v1/tutorials/installing-libraries#importing-a-zip-library) instructions on how the downloaded archive is installed with the Arduino Library Manager in the Arduino IDE.

## License

LGPL-2.1
