# basic_img_signer

### Deprecated
This script must be included [like this](https://github.com/PotatoDevices/device_redmi_begonia/commit/f881b19c4d1af3eb1a5076ef980e0dccc6d220ec). The script is no more maintained here. And new changes may not show up in this repository. Please check device configuration trees using this script for newer changes.

This script was written to sign Android partition imgs. Multiple partitions on MediaTek devices are signed by 2 certs. These certs are checked by the bootloader (LK), before the traditional Android boot process starts. cert1.der and cert2.der were extracted from Redmi Note 8 Pro (begonia)'s dtbo partition.
