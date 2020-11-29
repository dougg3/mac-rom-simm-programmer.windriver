# Mac ROM SIMM Programmer Windows Driver
This is only necessary for Windows versions prior to Windows 10. Prior versions of Windows did not automatically support USB CDC serial port devices, such as the [Mac ROM SIMM Programmer](https://github.com/dougg3/mac-rom-simm-programmer), out of the box. They required an INF file that told Windows to use the generic USB CDC driver (usbser.sys). This repository provides that INF file. If you want to use the Mac ROM SIMM Programmer on versions of Windows prior to Windows 10, you will need this INF file.

Starting with Windows 10, this driver is not necessary. Windows will automatically install its built-in driver when you plug in the Mac ROM SIMM Programmer.
