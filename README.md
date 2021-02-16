# Lenovo S145-15IWL clover EFI

## Introduction

This is Lenovo S145-15IWL hackintosh configuration for Clover and it is 90% working.

 - This configuration has been tested on Catalina `10.15.6` & `10.15.7` .

## Hardware configuration

 - Intel i5-8265u
 - Intel HD graphic 620
 - Screen 1920 x 1080 (FHD) TN
 - 256GB NVMe SSD
 - 8 GB DDR4 RAM
 - Nvidia MX110 integrated card (disabled)
 
 ## What is working
 - Audio on speakers and Audio jack connector
 - Brightness control
 - ELAN touchpad
 - SD card reader
 - Graphic acceleration with Intel UMA because NVIDIA is disabled
 ## What is not working
 - Integrated graphic card
 - Realtek wifi chip

## Bios

In `BIOS` disable:

 - Intel Vt-d
 - WIFI chip
 - set display device to UMA

## Notes
- Audio on headphones is not working properly so use fix [here](https://www.elitemacx86.com/threads/fix-audio-distortion-when-using-headphones-on-laptops.185/)
- Battery bar can sometime stuck but this is fixable trough DSDT configuration
