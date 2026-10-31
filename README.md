# Hackintosh OpenCore EFI for MAXSUN Terminator B760M
## Specifications
```
Model              MAXSUN B760M
CPU                Intel Core i5-13600KF
Memory             GLOWAY DDR4 4000MHz 16Gx2
Graphics           AMD Radeon RX6600XT 8GB
Audio              Realtek ALC897
Wi-Fi              DELL DW1820A
Storage            WD BLUE SN570 500GB
Monitor            FHD 1920x1080
BIOS Verison       H6.6G
macOS Version      Tahoe 26.7.1
OpenCore Version   1.0.8
```
## BIOS Settings
### Advanced
#### CPU Configuration
```
CFG Lock [Disabled]
```
#### Chipset Configuration
```
Serial Port [Disabled]
VT-d [Enabled]
Above 4G Decoding [Enabled]
Re-Size BAR Support [Enabled]
```
#### Graphics Configuration
```
Initiate Graphic Adapter [PEG Slot]
Internal Graphics [Disabled]
```
#### USB Configuration
```
Legacy USB Support [Enabled]
XHCI Hand-off [Enabled]
```
#### PCI Express Configuration
```
PCI Express Native Power Management [Disabled]
DMI Link ASPM Control [Disabled]
ASPM [Disabled]
L1 Substates [Disabled]
DMI ASPM [Disabled]
DMI Gen3 ASPM [Disabled]
PEG - ASPM [Disabled]
PCI Express Clock Gating [Enabled]
```
### Power
```
Enable Hibernation [Enabled]
ACPI Sleep State [S3 (Suspend to RAM)]
ErP Ready [Enabled]
USB Power On S4/S5 [Disabled]
```
### Startup
```
OS Type [Other OS]
Fast Boot [Disabled]
Launch CSM [Disabled]
```
