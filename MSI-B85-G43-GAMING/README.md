# What's not working?
- Wake on sleep. 
- Airdrop. I dont have a wifi chip yet.

# What's working?
- Dual Displays on Catalina.
- All I/O ports (VGA not tested, HDMI/DP are fine)
- Bluetooth (plug and play with ASUS BT400)
- iMessage

# Installation Process:
This is literally thrown together using the vanilla guide on /r/hackintosh. Everything worked OOTB, except for AtherosE2200 being required for an Ethernet Driver.

From there, I did a system upgrade to mojave, and then catalina. I initially installed it using OSX High Sierra

Build was scavenged together from some spare parts. 
Part List:
```
Mobo: MSI B85-G43-Gaming
CPU: i5-4570
RAM: 2x 8GB Corsair Vengance DDR3
PSU: EVGA Supernova 750W G3
SSD: Samsung 860 EVO 256GB
GPU: AMD Radeon R9 270 2GB
Cooler: CM Hyper 212 Turbo LED White
Case: Tecware Nexus TG ATX.
Bluetooth USB: ASUS BT400
```

# Things to note:
- Ethernet

AtherosE2200 works for the Realtek driver on this port.
- GPU

FakeID and ATI Inject MUST be done under the proper fakeID and FBName, or you'll end up stuck at gio.
