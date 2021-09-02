**macOS on CHUWI Corebook Pro**

**Laptop specs**  
CPU: Intel Core i3-6157U  
GPU: Intel Iris HD 550  
Wi-Fi Card: Intel Wireless 0x0910  
BT Card: Intel Bluetooth Card 0x0A2A  
SD Reader: Realtek RTS5129  

**Status**  
Everything is working

**Known Issues**  
MMC/SD Express cards are not supported. Follow SD card reader [driver updates](https://github.com/0xFireWolf/RealtekCardReader) to check progress.  

**Compatibility**  
The current configuration has been tested and working on macOS Big Sur 11.4  

**Bootloader**  
Clover 5127. Use preboot partition to boot macOS Big Sur and later. You can update Clover or switch to OpenCore if you prefer.  

**HI-DPI**  
The original display resolution (2560x1440) makes the macOS UI too small. You can use [one-key-hidpi](https://github.com/xzhih/one-key-hidpi) to enable UI scaling (HiDPI).  
The best HiDPI resolution is 1600x1066, but you can change it if you prefer.  

![screenshot](https://i.postimg.cc/nh8216zG/Schermata-2021-09-02-alle-09-57-26.png)
