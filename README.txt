This is the core graphics library for all our displays, providing basic graphics primitives (points, lines, circles, etc.). It needs to be paired with a hardware-specific library for each display device we carry (handling the lower-level functions).

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.
BSD license, check license.txt for more information.
All text above must be included in any redistribution.

To download, click the DOWNLOAD ZIP button, uncompress and rename the uncompressed folder Adafruit_GFX. Confirm that the Adafruit_GFX folder contains Adafruit_GFX.cpp and Adafruit_GFX.h

Place the Adafruit_GFX library folder your <arduinosketchfolder>/Libraries/ folder. You may need to create the Libraries subfolder if its your first library. Restart the IDE.


Draw XBitMap Files (*.xbm), exported from GIMP,
Usage:
Export from GIMP to *.xbm, rename *.xbm to *.c and open in editor.
C Array can be directly used with this function
void Adafruit_GFX::drawXBitmap(int16_t x, int16_t y,
const uint8_t *bitmap, int16_t w, int16_t h,
uint16_t color)
