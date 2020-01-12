# What's not working?
- Nothing so far, that I've checked.

# What's working?
- Dual Displays on Catalina.
- All I/O ports (VGA not tested, HDMI/DP are fine)
- Bluetooth
- iMessage
- Airdrop
- Wifi

# Installation Process:
- Go into BIOS, switch RAM to XMP.
- Prepare clover according to the config.plist and ktexts provided.
- Install.
- I installed from Mojave (clean) and then upgraded to Catalina.

Part List:
```
Mobo: ASUS Strix Z390i Gaming
CPU: i9-9900k
RAM: 2x 16GB GSkill Ripjaws X 3000Mhz
PSU: Default with case
SSD: Lexar 1tb SATA
GPU: Powercolour RX580 Red Devil 8GB
Cooler: CoolerMaster ML120RGB
Case: Inwin A1 Plus
Wifi/BT: Dell DW1560
```

# Things to note:
- Z390 boards don't have nvram by default so you need to use EFI64. 
- With EFI64 u need to change the clover settings to auto install RC Scripts.
- I picked this particular m-itx because the wifi module was easily replaceable. I replaced it with a Dell DW1560 off aliexpress (It's OOS or I'd link it).
