# HP 840 G3 Hackintosh EFI - macOS Monterey 12.6.5

![Screenshot - About this Mac](/showcase.png)

---

## How to update from Big Sur 11.5.2

1. Apply the latest EFI from the [Big Sur branch](https://github.com/Innoxious/hackintosh-hp-840-g3-intel-ac8260/tree/big-sur-11.5.2)
2. Download and reserve the latest Monterey EFI from the main branch.
3. Download and install macOS the Moneterey update - takes about 45 minutes to install.
4. Apply the latest Moneterey EFI. You need to do this to fix issues with audio, bluetooth and WiFi, hence why you should download it in advance.

## Features

- i7 6600U (Intel 6th Gen - Skylake)
- Intel AC8260
- Elan Tech touchpad
- macOS Monterey 12.6.5
- Open Core 0.9.2

**Things that work (non-exhaustive)**:

- Touchpad with gestures
- WiFi (2.4Ghz and 5Ghz)
- Bluetooth
- Ethernet
- Display port
- Battery indicator
- Speakers
- Headphone jack
- Graphics
- USB-C port
- M.2 NVMe SSD
- SD Card reader
- Dual boot with Windows - [Battery info doesn't show #19](https://github.com/Innoxious/hackintosh-hp-840-g3-intel-ac8260/issues/19)

**Things that do not work (also non-exhaustive)**:

- When [docked in 2013 UltraSlim](https://support.hp.com/us-en/product/hp-2013-ultraslim-docking-station/5450893/) only one of the displays are detected by macOS if they are both plugged into the Display Port output.
- [Trackpoint and top mouse buttons do not work](https://github.com/Innoxious/hackintosh-hp-840-g3-intel-ac8260/issues/21)

_Happy to help you set this up, open an issue 😃_

## BIOS Setup

![Advanced Menu](https://user-images.githubusercontent.com/5837038/131213423-0961664a-5936-46e2-8259-67dfb999c24b.jpg)
![Boot Options](https://user-images.githubusercontent.com/5837038/131213437-2262a93e-7c2a-406d-9140-bee39d8f2450.jpg)
![Secure Boot](https://user-images.githubusercontent.com/5837038/131213435-91f08cef-ba78-45ca-8678-df1a94ba97b3.jpg)

## How can I help?

- Keep OpenCore up to date. This is the most time consuming part of maintaining our hackintoshes.
- Keep Kexts up to date.
