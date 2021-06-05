
# MSI B450 Tomahawk MAX Ryzentosh macOS OpenCore EFI

This repository and project hosts the files necessary to boot macOS Big Sur successfully on custom desktop rig consisting of a MSI B450 Tomahawk MAX motherboard with a Ryzen 5 3600 CPU, and a XFX AMD Radeon RX 5700XT Triple Dissipation dGPU.

## Acknowledgements

 - [Core x86 Group & Team](https://discord.corex86.com)
 - [Dortania Team for their OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
 - [AMD-OSX and other devs for providing the Vanilla patches necessary to boot macOS bare metal on an AMD based machine](https://github.com/AMD-OSX/AMD_Vanilla)
  
## Authors

- [@osx86_iJB](https://www.github.com/osx86-ijb)
  

## Deployment

To deploy this project properly, please obtain the EFI folder from this repository, edit the config.plist to generate new serial number, rom, UUID, etcetera, then save config.plist, and place the files onto the appropriate ESP EFI partition in order to boot using OpenCore bootloader and proceed with your installation of macOS.
  
## Documentation

```The hardware used in this build is as follows:```

- AUDIO CHIPSET: Realtek ALC892 + Navi 10 HDMI Audio + USB DAC
- CPU: AMD Ryzen 5 3600 6-Core Processor @ 3.6GHz
- GPU: XFX AMD Radeon RX 5700 XT Triple Dissipation 8GB GDDR6 PCI-E Gen 4
- LAN CHIPSET: Realtek RTL8111H Gigabit Ethernet
- RAM: 64GB DDR4 3200MHz G.Skill Trident Z RGB 
- STORAGE / SSD: Inland Premium 512GB NVMe (OS Drive) + Much More Other Storage
- WIFI + BLUETOOTH = Fenvi FV-T919 (Broadcom BCM4360 802.11ac + Apple Inc BT 4.0 USB Host Controller)