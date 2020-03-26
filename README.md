# basic_img_signer

This script was written to sign Android partition imgs. Multiple partitions on MediaTek devices are signed by 2 certs. These certs are checked by the bootloader (LK), before the traditional Android boot process starts. cert1.der and cert2.der were extracted from Redmi Note 8 Pro (begonia)'s dtbo partition.
