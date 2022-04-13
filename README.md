# SAMD21/SAMD51 Analog Correction

## Sets and enables the digital correction logic of the SAMD ADC.

SAM D21 and SAM D51 microcontrollers are supported in this version which was pulled from the [Seeed-Studio fork of the SAMD Arduino core 1.7.0](https://github.com/Seeed-Studio/ArduinoCore-samd/tree/1.7.0/libraries/SAMD_AnalogCorrection). It was removed from that fork of the core in later versions and remains unavailable in the current version (1.8.1).

## Upstream versions

The library available in the current (1.8.13) [Arduino SAMD Arduino Core](https://github.com/arduino/ArduinoCore-samd/tree/master/libraries/SAMD_AnalogCorrection) does not support the SAM D51.

The library available in the current (1.7.9) [Adafruit fork of the SAMD Arduino Core](https://github.com/adafruit/ArduinoCore-samd/tree/master/libraries/SAMD_AnalogCorrection) supports both versions of the microcontroller, but it also pulls in the `Adafruit_TinyUSB` library if the `USE_TINYUSB` macro is defined. Presumably, this would be of value if `TinyUSB` is used.

## Installation - Arduino

Obtain the library by clicking on the green **Code** button, then on `Download ZIP`. 

Follow the [Importing a .zip Library](https://docs.arduino.cc/software/ide-v1/tutorials/installing-libraries#importing-a-zip-library) instructions to install the downloaded archive  with the Arduino Library Manager.


## Installation - PlatformIO

As described in the PlatformIO documentation on [Library options](https://docs.platformio.org/en/latest/projectconf/section_env_library.html#lib-deps), add a `lib_deps` section in the project `platformio.ini` configuration file and include the URL of the library.

<pre>
[env:seeed_xiao]
platform = atmelsam
board = seeed_xiao
framework = arduino
<b>lib_deps =
  https://github.com/sigmdel/SAMD_AnalogCorrection</b>
</pre>
## License

LGPL-2.1
