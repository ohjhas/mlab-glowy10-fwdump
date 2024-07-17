# mlab-glowy10-fwdump
Firmware Dump of tablet Microlab Glowy 10 (8990)

![image](https://github.com/user-attachments/assets/aaef216d-3ab6-4422-8ced-8922966b1926)

# Hardware:
SoC: Unisoc SC9863a


RAM: 2 GB (no estoy seguro que variante)


Battery: 6000 mAh


ROM: 32 GB eMMC 5.1


CPU: ARM Cortex-A55 a 1,60 GHz with 8 cores


Arquitectura: arm32-binder64 (The OS 32 bits but the SoC is compatible with 64 bits.)


GPU: PowerVR Rogue GE8322


Board: sp9863a_1h10_32b


Resolution: 800 x 1280 (Portrait), 1280 x 800 (Landscape)



# Software:
Android Version: Android 10 Go (con cosas de unisoc)


Android Security patch level: 5 de noviembre de 2020


Google Play System Update: 2020-03-01


Baseband: FM_BASE_18B_W20.24.2_P4|sc9863A_modem|04-26-2021 16:15:11
Marlin2_18A_W20.18.3|sharkl3_cm4|04-29-2020 02:47:56


Kernel: 4.14.133, compiled on 8 june 2021 17:25:07 PM


Build Number: MLAB_GLOWY10_user_W20.19.4_P1_20210608

# How to unlock bootloader:
i had no success on unlocking it 😢
Also, FW Files are not in .pac file (Unisoc packet file), so its not posible to flash it without unlocking it.

# Issues
When the tablet is on sleep mode (screen off) for a long time, WiFi and Bluetooth stop working. (at least on my unit)

The tablet has the ADUPS Fota app, which is an spyware, so not recommended to store personal files on there.

And for now only that.
