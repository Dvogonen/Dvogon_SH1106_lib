Kernen SH1106 Library
=====================

This is an adaption of Adafruit's SSD1306 OLED driver library to fit the similarly looking SH1106 displays.
The original adaption was made by Wonho-Maker in 2015. here is a link to the original project:
https://github.com/wonho-maker/Adafruit_SH1106


The only major change in comparison to the original Adafruit library is that the display function has been changed.
Another difference is that the SH1106 does not provide scroll functionalities like the SSD1306.
The coresponding library functions were removed by Wonho-maker.


The library is intended to be used together with the Adafruit-GFX-Library
https://github.com/adafruit/Adafruit-GFX-Library


The somewhat lacking documentation of the adaption as well as a minor bug propted me (Dvogonen) to branch the library and fix those missing details.
The project name was changed to kernen_sh1106_lib.
This is not out of disrespect in regards to Adafruit or Wonho-Maker. I simply want to avoid confusion and mixup with the original Adafruit library and Wonho-Maker's version.


