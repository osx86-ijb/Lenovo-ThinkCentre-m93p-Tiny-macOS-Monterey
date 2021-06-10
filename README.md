
# Lenovo ThinkCentre M93P Tiny - OpenCore 0.7.0 - Monterey Bootable

This is the OpenCore 0.7.0 EFI files needed to boot the new beta of macOS, macOS 12.0 Monterey.

## !! ATTENTION !!
_**Whilst this is a booting and "mostly" working EFI for this machine, there are a few things are not working and still need to be fixed.**_

**1) The CFG Lock patches are enabled on this config.plist, as one has to manually unlock CFG Lock on their own Motherboards, so that will need to be done before one can disable the patches in use, and further enable proper power management.**

**2) The BrcmPathRAM drivers are currently broken and not working in this EFI for my specific hardware build. This is more than likely due to Apple having made changes to the IOBluetoothFamily.kext in Monterey, and also potentially their having moved things to userspace. Keep in mind that userspace patching has been broken since macOS Big Sur for Hackintosh's, and there might be a chance that it won't get fixed soon, unless someone feels kind enough to take on the undertaking of migrating everything and fixing it to reflect the changes that Apple has made.**

## Authors

- [@osx86_ijb](https://www.github.com/osx86-ijb)
- [@Core-x86 Team](https://discord.com/invite/yCYpdZE)

## Acknowledgements
- [Acidanthera & OpenCore Teams](https://github.com/acidanthera)
- [Dortania OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

## Documentation

[How to add EFI files to USB and or HDD/SSD, and more knowledge](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/opencore-efi.html)

## Badges

[![Hackintosh Legend](https://img.shields.io/badge/Core-x86-blue)](https://github.com/Core-x86)
[![Core x86](https://img.shields.io/badge/Hackintosh-Legend-red)](https://github.com/osx86-ijb)
[![AGPL License](https://img.shields.io/badge/Go%20There-Away%20From%20Me-brightgreeng)](https://www.youtube.com/watch?v=PjACk_dw1v8)
## Screenshots
![About This Mac](https://i.ibb.co/VtmGZd7/Screen-Shot-2021-06-07-at-9-16-58-PM.png)
![Hackintool - System](https://i.ibb.co/nkxvXG8/Screen-Shot-2021-06-09-at-11-17-32-AM.png)
![Hackintool - Peripherals](https://i.ibb.co/Y3cvRbP/Screen-Shot-2021-06-09-at-11-17-39-AM.png)
![Hackintool - USB](https://i.ibb.co/vzRRL23/Screen-Shot-2021-06-09-at-11-17-50-AM.png)
![Hackintool - PCIe](https://i.ibb.co/LZ4bfDq/Screen-Shot-2021-06-09-at-11-18-09-AM.png)
![System Information - Hardware Overview](https://i.ibb.co/kVZrLkn/Screen-Shot-2021-06-09-at-11-16-12-AM.png)
![System Information - Audio](https://i.ibb.co/Xx3J23p/Screen-Shot-2021-06-09-at-11-16-18-AM.png)
![System Information - Bluetooth](https://i.ibb.co/f2LL59C/Screen-Shot-2021-06-09-at-11-16-21-AM.png)
![System Information - Ethernet Cards](https://i.ibb.co/nCpfzbK/Screen-Shot-2021-06-09-at-11-16-26-AM.png)
![System Information - Graphics/Displays](https://i.ibb.co/Rb1htXz/Screen-Shot-2021-06-09-at-11-16-30-AM.png)
![System Information - Memory](https://i.ibb.co/3mkpwcV/Screen-Shot-2021-06-09-at-11-16-32-AM.png)
![System Information - PCI](https://i.ibb.co/WypVrqh/Screen-Shot-2021-06-09-at-11-16-38-AM.png)
![System Information - SATA](https://i.ibb.co/KWhRQSy/Screen-Shot-2021-06-09-at-11-16-45-AM.png)
![System Information - USB](https://i.ibb.co/VHnDvLW/Screen-Shot-2021-06-09-at-11-16-52-AM.png)
![System Information - WiFi](https://i.ibb.co/yfjWj5P/Screen-Shot-2021-06-09-at-11-17-16-AM.png)
