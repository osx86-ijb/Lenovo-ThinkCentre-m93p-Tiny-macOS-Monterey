
# Lenovo ThinkCentre M93P Tiny - OpenCore 0.7.6 EFI for macOS 12.x.x

This is the OpenCore 0.7.6 EFI files needed to boot the new version of macOS, macOS 12.x Monterey on the Lenovo ThinkCentre m93p Tiny.

![Lenovo ThinkCentre m93p Tiny](https://i.ibb.co/C1xW6Th/Lenovo-Think-Centre-M93p-Tiny.jpg)

## !! ATTENTION !!
_**Whilst this is a booting and "mostly" working EFI for this machine, there are a few things are not working and still need to be fixed.**_

**1) The CFG Lock patches are enabled on this config.plist, as one has to manually unlock CFG Lock on their own Motherboards, so that will need to be done before one can disable the patches in use, and further enable proper power management.**

**2) The BrcmPathRAM drivers are currently broken and not working in this EFI for my specific hardware build. This is more than likely due to Apple having made changes to the IOBluetoothFamily.kext in Monterey, and also potentially their having moved things to userspace. Keep in mind that userspace patching has been broken since macOS Big Sur for Hackintosh's, and there might be a chance that it won't get fixed soon, unless someone feels kind enough to take on the undertaking of migrating everything and fixing it to reflect the changes that Apple has made.
EDIT: BlueToolFixup has been included, and should at the very least be able to get things enabled until a more complete fix is released.
**

## Authors

- [@osx86_ijb](https://www.github.com/osx86-ijb)

## Acknowledgements
- [Acidanthera & OpenCore Teams](https://github.com/acidanthera)
- [Dortania OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

## Documentation

[How to add EFI files to USB and or HDD/SSD, and more knowledge](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/opencore-efi.html)

## Badges

[![Core x86](https://img.shields.io/badge/Hackintosh-Legend-red)](https://github.com/osx86-ijb)
[![AGPL License](https://img.shields.io/badge/Go%20There-Away%20From%20Me-brightgreeng)](https://www.youtube.com/watch?v=PjACk_dw1v8)
## Screenshots
![About This Mac](https://i.ibb.co/K2vrJ3p/Screen-Shot-2021-12-10-at-5-06-29-PM.png)
![Hackintool - System](https://i.ibb.co/2cqVBMN/Screen-Shot-2021-12-10-at-8-45-36-PM.png)
![Hackintool - System Part II](https://i.ibb.co/B4pZbjV/Screen-Shot-2021-12-10-at-8-45-51-PM.png)
![Hackintool - OpenCore Version Loaded](https://i.ibb.co/3C8tg72/Screen-Shot-2021-12-10-at-8-46-31-PM.png)
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
