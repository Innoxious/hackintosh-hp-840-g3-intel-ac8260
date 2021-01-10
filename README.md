# HP 840 G3 Hackintosh EFI

- i7 6600U (Intel 6th Gen - Skylake)
- Intel AC8260
- Elan Tech touchpad
- macOS Big Sur 11.1
- Open Core 0.6.5

**Things that work (non-exhaustive)**:
- Gestures
- ^WiFi (2.4Ghz and 5Ghz)
- ^Ethernet
- Display port
- Battery indicator
- Audio 
- Graphics (video playback is significantly smoother than Ubuntu 20.04 ???) 
- USB-C port
- M.2 NVMe SSD
- SD Card reader

^ WiFi and Ethernet do not perform as well as they would on Windows/Ubuntu. See [OpenIntelWireless's FAQ](https://openintelwireless.github.io/itlwm/FAQ.html#performance-sucks)

Speed stats:

| Device      | Actual (Mbps) | Expected (Mbps) |
|-------------|---------------|-----------------|
| WiFi (5Ghz) |  50 ⬇️  20 ⬆️   | 400 ⬇️ 200 ⬆️     |
| Ethernet    | 300 ⬇️ 120 ⬆️   | 900 ⬇️ 500 ⬆️     |

**Things that do not work (also non-exhaustive)**:
- When [docked in 2013 UltraSlim](https://support.hp.com/us-en/product/hp-2013-ultraslim-docking-station/5450893/) only one of the displays are detected by macOS


*Happy to help you set this up, open an issue 😃*
