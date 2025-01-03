**8051 (AT89S51) and MAX7219**

Compiled with PlatformIO and SDCC

I have used ArduinoISP as programmer (have uncommented #define USE_OLD_STYLE_WIRING)

Was using this command for avrdude:

avrdude -c stk500v1 -P COM4 -p 89s51 -b 19200 -C "<YOUT PTH>\tools\avrdude\6.3.0-arduino17\etc\avrdude.conf" -U flash:w:firmware.hex:

![Demo](demo.gif)