# Minibian

#### SourceForge:
minibian - https://sourceforge.net/projects/minibian/files/latest/download
win32diskimager - https://sourceforge.net/projects/win32diskimager/

#### Setup:
wi-fi - https://minibianpi.wordpress.com/how-to/wifi/
wi-fi adapter firmware (built-in):
```
apt install firmware-brcm80211
# util
apt install iw
# list networks
iw dev wlan0 scan | grep SSID
```
resize root fs - https://medium.com/100-days-of-linux/how-to-resize-a-linux-root-file-system-af3e5096b4e4#:~:text=Resizing%20a%20root%20partition%20is,size%20in%20the%20same%20position.
KDE:
```
apt install kde-standard
apt install xserver-xorg
startx
```

#### BerryBoot:
Installer https://sourceforge.net/projects/berryboot/

#### Raspberry Pi 3 Model B - Specifications:
- Quad Core 1.2GHz Broadcom BCM2837 64bit CPU
- 1GB RAM
- BCM43438 wireless LAN and Bluetooth Low Energy (BLE) on board
100 Base Ethernet
- 40-pin extended GPIO
- 4 USB 2 ports
- 4 Pole stereo output and composite video port
- Full size HDMI
- CSI camera port for connecting a Raspberry Pi camera
- DSI display port for connecting a Raspberry Pi touchscreen display
- Micro SD port for loading your operating system and storing data
- Upgraded switched Micro USB power source up to 2.5A
