# droxeybot

<!-- omit toc -->
## Table of Contents

1. [Hardware](#hardware)
   1. [Hemera](#hemera)
2. [Software](#software)
   1. [Customized](#customized)
   2. [Installation](#installation)

## Hardware

- Printer: Ender 3
- Motherboard: [SKR Mini E3 1.3](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3)
- Screen: [BTT TFT35-E3 V3.0](https://github.com/bigtreetech/BTT-TFT35-E3-V3.0)
- Extruder: [E3D Hemera Direct Drive](https://e3d-online.com/e3d-hemera-175-kit)
- BLTouch v3.1

### Hemera

#### Printed Parts

- [Mount](https://www.myminifactory.com/object/3d-print-ender-3-compact-hemera-mount-plate-with-bltouch-110476)
- [Part Cooling Duct & Mount](https://www.thingiverse.com/thing:4042492)

#### Guides Used

- [Installation Tips & Tricks](https://gist.github.com/droxey/00eea91a62762b6dc2662ebc6ba28ef4)

## Software

- Marlin 2.x Base: [MarlinFirmware/Marlin](https://github.com/MarlinFirmware/Marlin)
- Hardware Config: [HackerHappyHour/Marlin](https://github.com/HackerHappyHour/Marlin)

### Customized

- All axes calibrated.
- Hemera [configuration](https://e3d-online.dozuki.com/Guide/01+-+E3D+Hemera+Marlin+firmware+modification+(Direct)/129) added.
- [Fix](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/issues/123) for accurate Neopixel colors implemented.

Any changes I've made can be found by searching for the following text:

```txt
Customized @droxey
```

### Installation

To build Marlin 2.0 you'll need [Arduino IDE 1.8.8 or newer](https://www.arduino.cc/en/main/software) or [PlatformIO](http://docs.platformio.org/en/latest/ide.html#platformio-ide). Detailed build and install instructions are posted at:

  - [Installing Marlin (**Arduino**)](http://marlinfw.org/docs/basics/install_arduino.html)
  - [Installing Marlin (**VSCode**)](http://marlinfw.org/docs/basics/install_platformio_vscode.html).
