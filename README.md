# Raspberry Pi 3 Programmer for KidBright

### bootrom version 03

### Requirements
- [Raspberry Pi 3](https://www.raspberrypi.org/products/raspberry-pi-3-model-b)
- [ET-LCD SW HAT](http://www.ett.co.th/productPi/ET-LCD%20SW%20HAT/ET-LCD%20SW%20HAT.html)

### Instruction
- Attach ET-LCD SW HAT to Raspberry Pi 3
- Copy all files to a formatted single partition FAT32 sdcard
- Booting a Raspberry Pi 3

### Wiring
|  Pi 3         |  KidBright  |
|---------------|-------------|
| GND           |  GND        |
| GPIO14 (TXD)  |  RX         |
| GPIO15 (RXD)  |  TX         |
| GPIO21        |  RST        |
| GPIO20        |  IO0        |

### Programming Options
- BR = only bootrom
- QC = bootrom + hardware testing app
