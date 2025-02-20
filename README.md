# B550 Desktop Ryzentosh (Ryzen 5 5600X)
OpenCore bootloader config files for my Hackintosh.
## System Information
| Name       |                     Model |
| :--------- | ------------------------: |
| CPU        |             Ryzen 5 5600X |
| GPU        |nVIDIA GeForce GTX 1050 Ti |
| SSD (NVME) |            WD SN770 (1TB) |
| SSD (SATA) |     Crucial MX500 (512GB) |
| SSD (SATA) |     Crucial BX500 (256GB) |
| Board      |            MSI B550 A-Pro |
| Ethernet   |      RTL8111H Gigabit LAN |

- OpenCore: v0.7.5
- macOS High Sierra (May work on newer versions)
### SMBIOS
Selected: `MacPro7,1`

Don't forget to change your device UUID, board serial and network MAC address.

Go to https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo for more information on setting up the SMBIOS platform info
## Kexts Used
| Package                  | Version |
| :----------------------- | ------: |
| AppleALC                 |   1.5.9 |
| Lilu                     |   1.5.2 |
| VirtualSMC               |   1.2.2 |
| AirportBcrmFixup         |   2.1.2 |
| RealtekRTL8111           |   2.4.0 |
| NVMeFix                  |   1.0.7 |
| AppleMCEReporterDisabler |   1.2.0 |
| RestrictEvents           |   1.0.0 |
## What works
- [x] Graphics
- [x] iServices
- [x] USB
- [x] Sleep
- [x] Audio
- [x] iOS Simulator
## What's not working
- Work in progress
## Pre Install
- Update your SMBIOS and MAC address
- Turn on 4GB above encoding, Turn off ReSize BAR support
