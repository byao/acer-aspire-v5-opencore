# Acer Aspire V5-573P-9899 OpenCore

Specs and OpenCore EFI configurations for Acer Aspire V5-573P-9899 laptop Hackintosh.

***This project is for educational purposes only.***

## Hardware Specs

- Intel Core i7-4500U processor **Haswell**
- 6GB DDR3L memory 
- 750GB hard drive 
- 15.6" Full HD widescreen CineCrystal multi-touch LED-backlit display (1920 x 1080)
- Intel HD Graphics **4400**
- Intel Audio **ALC282**
- 6.5-hour battery
- Wifi **Atheros 9462**
- Ethernet **Realtek RTL 8111**
- Bluetooth **Atheros 80211**

## Working

- Audio
- Display
- Ethernet
- WiFi
- Battery
- Bluetooth
- Touchpad
- Touchscreen
## Issues

1. On initial boot, screen is distorted. Workaround is manual sleep using power button, then turn on to reset display.

## Installation

Details of all steps are in OpenCore guide.

1. Fully review [Dortania OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/)

1. Create macOS install bootable USB drive.

1. Mount **EFI** partition of USB drive.

1. Copy *EFI* folder into **EFI** USB drive. *EFI* should be a root folder. USB drive can boot using hardware configuration

1. Restart Aspire and boot into USB drive.

1. Choose macOS Install (external) in OpenCore boot option.

1. Finish installation.

1. Boot using USB OpenCore and select installed MACOS.

1. Mount **EFI** partition of Aspire disk drive.

1. Copy *EFI* folder into **EFI** disk drive. *EFI* should be a root folder. Laptop disk EFI partition now has hardware configuration needed to start.

1. Restart and profit!

1. <a href="https://www.buymeacoffee.com/byao" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## Fixes

- [HiDPI Resolution Scaling](https://github.com/xzhih/one-key-hidpi)
