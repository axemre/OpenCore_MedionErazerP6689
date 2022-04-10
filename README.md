# OpenCore_MedionErazerP6689
EFI configuration for running macOS Monterey using OpenCore 


This configuration is still WIP, therefore, some functions may not work properly. 

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

What does not work?
* Battery indicator not updating properly (may be related to my battery..)
* more..

Feel free to contribute to this project. 

Tested on macOS Monterey 12.3!

Specs: 

* Intel Core i5-8250U Quad Core KabyLake Refresh CPU
* 16GB DDR4 RAM (upgraded on my machine)
* Intel Wireless 8265 + Bluetooth
* UHD 620 + GTX 1050 (disabled by SSDT, no need for -wegnoegpu boot-arg)
* Elan touchpad
