# OpenCore EFI for Lenovo M720Q SEQUOIA 15.3.2

**macOS version**: 15.3.2

**OpenCore version**: 1.0.1

## Specification

| **Component**  | **Model**                               |
| -------------- | --------------------------------------- |
| CPU            | Intel i5-9500T                          |
| Motherboard    | Intel B360                              |
| RAM            | 24GB DDR4-2666                          |
| Audio Chipset  | ALC235                                  |
| GPU            | Intel® UHD Graphics 630 (DP, HDMI, VGA) |
| OS Disk (NVMe) | LITEON T10 NVMe 256G                    |
| WIFI           | Intel 7265                              |

## HIDPI fix

```bash
git clone https://github.com/xzhih/one-key-hidpi.git
cd one-key-hidpi
./hidpi.command
```

## All work

- CPU
- Dual monitors (Displayport & HDMI & VGA)
- Audio (ALC235)
- Ethernet
- USB
- Wifi
- App store, iCloud, iMessage, iTunes, FaceTime, etc
- Sleep, Wakeup, Shutdown, Restart
