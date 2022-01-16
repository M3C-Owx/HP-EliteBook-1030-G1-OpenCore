# HP-EliteBook-1030-G1-OpenCore
 
## Device Specs
- Intel m5-6Y57 @ 1.10GHz
- Intel HD Graphics 515
- 8GB DDR4 (Memory soldered down)
- Toshiba XG5 256GB NVMe SSD
- ALPS I2C HID Touchpad (ALP000E:00 044E:120C)
- 1920x1080@60Hz 13,3" Display
- HD Audio Codec Conexant CX20724
- Intel Wireless-AC 7265

## Things that works
- Keyboard
- Touchpad /w gestures
- Intel WiFi
- Intel Bluetooth
- Battery status
- Speakers
- Audio jack
- Graphics
- USB2/3 Ports
- USB-C Port
- Integrated camera
- Microphone
- Sleep
- Mute button
- NO RTC error when booting

## Not tested
- HDMI Port
- HP 2013 UltraSlim Dockingstation
- HP USB-C/A Universal Dock G2 /w HP USB-C Universal Dock with 4.5 mm and USB Dock Adapter (2UF95AA)

## Not working
- Fingerprint sensor

## BIOS v1.53 Settings
###### Security
**TPM Embedded Security**
- TPM State -> Unchecked

###### Advanced
**Boot Options**
- Fast Boot -> Unchecked
- CD-ROM Boot -> Unchecked

**Secure Boot Configuration**
- Configure Legacy Support and Secure Boot -> Legacy Support Disable and Secure Boot Disable

**Built-In Device Options**
- Wake On LAN -> Disabled
- Video memory size -> 128 MB

**Power Management Options**
- Wake on USB -> Unckecked

