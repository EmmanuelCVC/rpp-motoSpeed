# Raspberry Pi Pico Speed Meter

Emmanuel Carballo Vargas, December 2021 (first commit)

This is an analog to digital implementation, from a rotary signal to digital calculation of the speed, for the Honda-XR150L motorcycle movement.
Once implemented, other sensor/measures are added: time, temperature, vibration, etc.
A TFT LCD is used to display all content required.
It uses 3D modeled files to attach components to the existed frame. 

## 3D STLs files

Will be here soon!

# Files

- xr_speedmeter.py this is the main program for running the speed meter. Rename this to main.py and upload the Pico if you want this to always start...
- sysfont.py - you need this file to enable the tft_st7735 library to draw text
- tft_st7735.py - this is the ST7735 SPI driver library for the screen
- README.md - this is this file you are reading now
