# Asrock-Z690-PG-Reptide-hackintosh
EFI OpenCore and Clover Folders

Attention! If you have RX5700 (XT) graphics card, you may have to use the nameframe (ATI,Adder) to avoid WindowServer crashes!

## Hardware configuration:
* CPU: i5-13600kf RaptorLake (Undervolted)
* MB: Asrock Z690 PG Reptide 
* RAM: 2x16Gb DDR4 3600 ADATA XPG
* GPU: Radeon RX580 Sapphire Nitro+ 8Gb
* GPU: Radeon RX5700 Sapphire Pulse 8Gb
* SSD: 512Gb Netac 930E Pro NVME M2 (PCI-e 3.0) - Linux
* SSD: 1Tb Netac NV7000 NVME M2 (PCI-e 4.0) - Mac OS 13
* SSD: 2Tb Netac NV7000 NVME M2 (PCI-e 4.0) - Windows 11
* WIFI/BT: bcm943602CS in M2 A/E keys NGFF adapter or PCI-E adapter
* BIOS: [v18.01](https://pg.asrock.com/mb/Intel/Z690%20PG%20Riptide/index.ru.asp#BIOS)
* Display: LG 4K 60 Hz HDR via Display Port (27UK650-W)

### BIOS setup: 

* Default and Overclocking with undervolting

### Mac OS Monterey and Ventura EFI OpenCore loader 1.0.0 and Clover 5156
### Mac OS Sonoma, Sequoya beta with EFI OpenCore loader 1.0.1 and legacy Broadcom WiFi patch

FileVault2 and some Intel LAN not working in Sonoma with the OCLP patch!

* Only OpenCore loader configuration supports Sonoma, Sequoya wifi legacy patch with OCLP. 
* All mac os futures are working including DRM playback and sleep/wake S3
* Clover has issue with update under T2 mac models

Wifi legacy patch Sonoma, Sequoya beta. [OCLP](https://drive.google.com/file/d/1poXc2ZGHqONZTQKSdnTMutIrU6v9UOKp/view?usp=sharing)
