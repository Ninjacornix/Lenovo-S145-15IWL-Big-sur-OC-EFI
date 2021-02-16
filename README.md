# Lenovo S145-15IWL OC EFI for MacOS Big Sur

## Introduction

This is Lenovo S145-15IWL hackintosh configuration for OpenCore and it is 90% working.

 - This configuration has been tested on Big Sur `11.1`.

## Hardware configuration

 - Intel i5-8265u
 - Intel HD graphic 620
 - Screen 1920 x 1080 (FHD) TN
 - 256GB NVMe SSD
 - 8 GB DDR4 RAM
 - Nvidia MX110 GPU card (disabled in BIOS)
 
 ## What is working
 - Audio on speakers and Audio jack connector
 - Brightness control
 - ELAN touchpad
 - SD card reader
 - Graphic acceleration with Intel UMA because NVIDIA is disabled
 ## What is not working
 - Nvidia GPU
 - Realtek wifi chip

## Bios

In `BIOS` disable:

 - Intel Vt-d
 - WIFI chip
 - set display device to UMA

## Notes
- Audio on headphones is not working properly so use fix [here](https://www.elitemacx86.com/threads/fix-audio-distortion-when-using-headphones-on-laptops.185/)
- Battery bar can sometimes stuck
- DSDT is provided by MaLd0n on Olarila (Thanks for that 😁)
