# TFTLCD_Mega2560
Arduino library for 8-bit TFT LCDs, specifically modified and tested for a 2.8" screen, using the Mega 2560

The TFT LCD shield that was used for testing was sold by Kumantech. Here is a link to their product: 

http://www.kumantech.com/kuman-uno-r3-28-inch-tft-touch-screen-with-sd-card-socket-for-arduino-nano-mega2560-320x240-28quot-lcd-k60_p0022.html

Repository notes: 
- This library has a selection of files that were copied from a contributer by the name of materone, and the file structure has been reorganized slightly. Here is a link to materone's repository: https://github.com/materone/ILI9341-Arduini-Mega2560-Lib
- Adafruit Industries is the original creator of this library (see Adafruit information below for more details). Here is a link to Adafruit's repository: https://github.com/adafruit/TFTLCD-Library
- As Adafruit states below, the Adafruit_GFX library is required and can be found at https://github.com/adafruit/Adafruit-GFX-Library , but it is IMPORTANT to note that compilation errors may occur with versions later than 1.5.3. Installing version 1.5.3 can be done within the Arduino IDE by going to Library Manager, searching for "Adafruit_GFX_Library" and installing the proper version. 
- https://github.com/adafruit/Adafruit_TouchScreen is a library that can also be associated with this touch screen

Adafruit Information: 

This library works with the Adafruit 2.8" TFT Breakout w/SD card
  ----> http://www.adafruit.com/products/335
as well as Adafruit TFT Touch Shield
  ----> http://www.adafruit.com/products/376
 
Check out the links above for our tutorials and wiring diagrams.
These displays use 8-bit parallel to communicate, 12 or 13 pins are required
to interface (RST is optional).
Adafruit invests time and resources providing this open source code,
please support Adafruit and open-source hardware by purchasing
products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.
MIT license, all text above must be included in any redistribution

To download. click the DOWNLOADS button in the top right corner, rename the uncompressed folder Adafruit_TFTLCD. Check that the Adafruit_TFTLCD folder contains Adafruit_TFTLCD.cpp and Adafruit_TFTLCD.

Place the Adafruit_TFT library folder your <arduinosketchfolder>/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE

Also requires the Adafruit_GFX library for Arduino. https://github.com/adafruit/Adafruit-GFX-Library
