### This repo has deprecated in favor of [modern opencore efi](https://github.com/Dimon70007/msi-GF75-opencore-efi)

### Clover boot efi usb build for msi GF75 thin 9SC

This is a copy of files from usb drive EFI partition, used to run already installed macos monterey

#### Hardware 

- Intel(R) Core(TM) i7-9750H CPU
- Intel(R) UHD Graphics 630 & NVIDIA GeForce GTX 1650
- Intel® Display Audio
- Realtek High Definition Audio
- 32G RAM (16GBX2)
- 1Tb SATA ssd for Windows boot
- 1Tb NVMe ssd for Mac OS Monterey boot
- Realtek PCIe GbE Family Controller (RJ45)
- Intel® Wireless-AC 9560 160MHz
- Intel® Wireless Bluetooth®
- 17.3" FHD (1920x1080), IPS-Level
- Type-C USB3.2 Gen1
- HDMI (4K @ 30Hz)

#### What works

- Intel UHD graphics only (no support for nvidia card)
- HDMI video only (no audio)
- onboard audio with microphone and headphones
- samsung 980 nvme boot only with usb drive
- hw monitor smc2
- battery indication
- USB ports 3.0 and type C
- onboard keyboard and touchpad with voodoops2controller
- keyboard hotkeys
- display backlight, keyboard backlight
- camera (enable/disable with hotkeys)
- Intel wifi card works too

#### What does not work 

- HDMI audio - have no time to fix this
- Boot from nvme samsung 980 not find bootloader (only booting from usb flash bootloader with clover). may be driver needed
- Type C port works only on usb 3.0 speed. may be repatch for usb ports needed

Before copying this files to EFI folder on hard drive recommends to copy and run it from usb drive for testing

Special thanks to [ErrorErrorError with his Guide](https://github.com/ErrorErrorError/msi-gs65-gs75-hackintosh)
