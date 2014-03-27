Adafruit_TFT
============

Adafruit_TFT 2.8 

This is a port of Adafruit Arduino TFT and GFX Libraries compatible with the Spark Core.
Original Libraries are available at:

https://github.com/adafruit/Adafruit-GFX-Library
https://github.com/adafruit/TFTLCD-Library

The library should work with the following displays:

http://www.adafruit.com/products/376
http://www.adafruit.com/products/1651

and also low cost displays available at ebay:
http://cgi.ebay.com/ws/eBayISAPI.dll?ViewItem&item=290994460684&ssPageName=ADME:L:OC:US:3160

The display should be connected to the Spark core according to the following mapping:

A0 -> LCD_RD
A1 -> LCD_WR
A2 -> LCD_RS
A3 -> LCD_CS
A4 -> LCD_RST

D0 -> LCD_D0
D1 -> LCD_D1
D2 -> LCD_D2
D3 -> LCD_D3
D4 -> LCD_D4
D5 -> LCD_D5
D6 -> LCD_D6
D7 -> LCD_D7

5V and 3.3V connected to the spark
