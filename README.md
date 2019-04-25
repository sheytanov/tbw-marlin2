# Marlin 3D Printer Firmware Modified for Tevo Black Widow

This is a custom modification of [**Marlin**](http://marlinfw.org/) [**bugfix-2.0.x**](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x) for Tevo Black Widow 3D printers.

Characteristics:
- Using **TMC2208** for **X**, **Y** and **Z** axis in silent chop
- BLTouch is enabled
- Optimized bed leveling procedure - 9 points for leveling compared to standard 12 points
- Updated bed boundaries: **Xmax=340**, **Ymax=220**, **Zmax=240**
- Set **maximum power** for additional fans to **125 (~12V)**
- Configured **temp sensor** for Titan Aero Extruder

## Building Marlin 2.0

__Not for production use. Use with caution!__
See the official guide.

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
