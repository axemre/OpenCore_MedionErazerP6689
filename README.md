# OpenCore_MedionErazerP6689
EFI configuration for running macOS Monterey using OpenCore 
 

What works?
* Boot
* CPU Management
* Audio using alcid=25
* Integrated mic
* Integrated Webcam
* FULL QE/CI acceleration
* WiFi using itlwm
* Touchpad with all gestures
* Bluetooth using IntelBTFirmware + BluetoolFixup
* Brightness (*)
* overall usage
* USB ports (mapped)
* Etc.

What does not work?
* Battery indicator not updating properly (may be related to my battery, but laptop has got an unique DSDT register which is not patchable. There are only 2-3 16-bit registers in the DSDT, which aren't calling any battery related registers..)
* more..

Feel free to open an issue if there are any with the EFI.

Tested on macOS Monterey 12.3!

Specs: 

* Intel Core i5-8250U Quad Core KabyLake Refresh CPU
* 16GB DDR4 RAM (upgraded on my machine)
* Intel Wireless 8265 + Bluetooth
* UHD 620 + GTX 1050 (disabled by SSDT, no need for -wegnoegpu boot-arg)
* Elan touchpad
