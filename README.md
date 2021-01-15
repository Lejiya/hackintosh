# Hackintosh
A repository containing the files of my Hackintosh USB.   
Currently running on macOS Big Sur 11.1 (updated through App Store)

## Laptop Specifications
- **Laptop Model**: Dell Inspiron 5567  
- **CPU Model**: Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz  
- **iGPU**: Intel Coproration HD Graphics 620 (rev 02)  
- **dGPU**: AMD Radeon R7 M440/M445  
- **Mouse**: I2C  
- **Keyboard**: Unknown  
- **Audio Codec**: ALC3246 Analog  
- **WLAN Chipset**: Intel Corporation Wireless 3165  
- **Ethernet Chipset**: Realtek RTL810xE PCI Express Fast Ethernet controller  
- **SATA Controller**: Intel Corporation Sunrise Point-LP SATA Controller [AHCI mode]  

## Working:
- HDMI
- Battery readouts
- Headphone audio output
- Keyboard and Trackpad (with gestures)
- External USB Keyboard and Wireless Mice
- App Store
- Time machine backup

## Not working:
- Headphone audio input (mic in)
- iMessage and FaceTime
- WiFi and Bluetooth (can be fixed with AirportItlwm and IntelBluetoothFirmware)

## Bugs:
- Sometimes on different desktops, a black bar appears on the top right, although it goes away if you switch back and forth a couple times.
- Shutting down the laptop by clicking the apple icon in the top left > Shut down... makes the OpenCore boot picker freeze on the subsequent boot, so the laptop has to be forced to power off by holding the power button, and then switching it on again. Although, switching off the laptop through Alfred does not make the boot picker freeze and as a side benefit, also starts up system startup apps faster on login.
