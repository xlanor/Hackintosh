# What's not working?

Wake on sleep. 
One case fan for some weird reason.

# What's working?
Dual Displays on Mojave.
All I/O ports (VGA not tested, HDMI/DP are fine)

# What's not tested?
Airdrop, wifi, etc. I'll wait for my ASUS BT400

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
```

# Things to note:
- Ethernet

AtherosE2200 works for the Realtek driver on this port.
- GPU

FakeID and ATI Inject MUST be done under the proper fakeID and FBName, or you'll end up stuck at gio.