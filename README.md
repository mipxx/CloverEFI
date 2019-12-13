Clover EFI
================

:exclamation: Change 'MLB, 'BoardSerialNumber', 'SerialNumber' and 'SmUUID' Number to a valid value!

:exclamation: This configuration is not intended to be updated in the future. Please give [OpenCore](https://github.com/mipxx/OpenCoreEFI) a try.

<img src="https://github.com/mipxx/CloverEFI/blob/master/Docs/System/System_Info_1.png" width="698" height="465"/>

EFI Folder for Clover Bootloader.
Created with the help of [/r/Hackintosh Vanilla Desktop Guide](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/)

### Function Overview

| Function           | Status                   | Comment                 |
| ------------------ | :----------------------: | :---------------------- |
| AirDrop            | :heavy_check_mark:       | [with Fenvi FV-T919](https://www.aliexpress.com/item/4000167777406.html) |
| Apple Watch unlock | :grey_question:          |                         |
| FaceTime           | :grey_question:          |                         |
| FileVault 2        | :grey_question:          |                         |
| Handoff            | :heavy_multiplication_x: | no wifi card            |
| H.264              | :heavy_multiplication_x: | [with Radeon RX Vega 56](https://github.com/mipxx/CloverEFI/blob/master/Docs/System.md#hardware-encoding) |
| HEVC               | :heavy_multiplication_x: | [with Radeon RX Vega 56](https://github.com/mipxx/CloverEFI/blob/master/Docs/System.md#hardware-encoding) |
| hibernate          | :grey_question:          |                         |
| iMessage           | :heavy_check_mark:       | with valid serialnumber |
| native NVRAM       | :heavy_check_mark:       |                         |
| NVMe boot          | :heavy_check_mark:       |                         |
| sleep/wake         | :heavy_check_mark:       |                         |
| UEFI boot entry    | :heavy_check_mark:       | with UEFI edit          |
| Apple Music        | :heavy_check_mark:       |                         |
| Netflix DRM        | :grey_question:          |                         |


### Additional Information

- [Benchmarks](https://github.com/mipxx/CloverEFI/blob/master/Docs/Benchmark.md)
- [Screenshots](https://github.com/mipxx/CloverEFI/blob/master/Docs/System.md)
- [UEFI Settings](https://github.com/mipxx/CloverEFI/blob/master/Docs/UEFI.md)


### System Components

- [GIGABYTE B450 Aorus Pro Rev. 1.0](https://de.aorus.com/product-detail.php?p=794&t=53&t2=57&t3=121) (UEFI Version [F41](http://download.gigabyte.eu/FileList/BIOS/mb_bios_b450-aorus-pro_f41_n.zip))
- [AMD RYZEN 5 3600](https://www.amd.com/de/products/cpu/amd-ryzen-5-3600)
- [Crucial Ballistix Sport LT rot DIMM Kit 16GB, DDR4-3200, CL16-18-18](https://ballistixgaming.com/products/dram/sport/ballistix-sport-lt-ddr4/ballistix-sport-lt-ddr4-rc.html)
- [SAPPHIRE PULSE Radeon RX VEGA56 8G HBM2](https://www.sapphiretech.com/de-de/consumer/pulse-rx-vega56-8g-hbm2)
- [WD Blue SN500 NVMe SSD](https://shop.westerndigital.com/de-de/products/internal-drives/wd-blue-sn500-nvme-ssd#WDS500G1B0C)
- [HP ENVY 27s](https://store.hp.com/GermanyStore/Merch/Product.aspx?id=Y6K73AA&opt=ABB&sel=MTO) 4K Monitor via DisplayPort
- [Fenvi FV-T919](https://www.aliexpress.com/item/4000167777406.html) WiFi / Bluetooth Card PCIe

### Software Versions

- macOS Catalina 10.15.1 (19B88)
- Clover [5098](https://github.com/Dids/clover-builder/releases/tag/v2.5k_r5098)

### Drivers
- ApfsDriverLoader
- AptioMemoryFix
- HFSPlus
- NvmExpressDxe
- VirtualSMC [1.0.8](https://github.com/acidanthera/VirtualSMC/releases/tag/1.0.8)

### Kexts
- AMD-USB-Map for GIGABYTE B450 Aorus Pro
- AppleALC Layout 7 for Realtek ALC1220-VB [1.4.3](https://github.com/acidanthera/AppleALC/releases/tag/1.4.3)
- Innie [1.2.0](https://forums.macrumors.com/threads/innie-a-fix-for-pci-drives-seen-as-external.2136229/#post-26433989)
- Lilu [1.3.9](https://github.com/acidanthera/Lilu/releases/tag/1.3./)
- NoVPAJpeg [1.0.0]()
- NullCPUPowerManagement [1.0.0d2](https://cdn.discordapp.com/attachments/263757191608139779/643751774666358794/NullCPUPowerManagement.kext.zip)
- SmallTreeIntel82576 for Intel I-211AT Ethernet [1.0.6](https://drive.google.com/file/d/0B5Txx3pb7pgcOG5lSEF2VzFySWM/view)
- SMCProcessor [1.0.8](https://github.com/acidanthera/VirtualSMC/releases/tag/1.0.8)
- SMCSuperIO [1.0.8](https://github.com/acidanthera/VirtualSMC/releases/tag/1.0.8)
- VirtualSMC [1.0.8](https://github.com/acidanthera/VirtualSMC/releases/tag/1.0.8)
- WhateverGreen [1.3.4](https://github.com/acidanthera/WhateverGreen/releases/tag/1.3.4)

### Sources
- [/r/Hackintosh Vanilla Desktop Guide](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/)
- [Dids Clover Build Repository](https://cloverdb.com/)
- [r/hackintosh](https://www.reddit.com/r/hackintosh/)
- [Kext Repository](https://1drv.ms/f/s!AiP7m5LaOED-m-J8-MLJGnOgAqnjGw)
- [AMD-OSX Discord](https://discord.gg/EfCYAJW)
- [Wireless Buyers Guide](https://khronokernel-7.gitbook.io/wireless-buyers-guide/)