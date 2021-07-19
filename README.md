# PLD_programmer

I made a home built device called afterburner which is described in: https://github.com/ole00/afterburner

This GAL/PLD programmer is used to program ATF22V10C for the projects: 
[hansake/Z80_Computer_board: A simple Z80 based computer board](https://github.com/hansake/Z80_Computer_board)
and [hansake/Z180_Computer: Z180 computer with extended interfaces.](https://github.com/hansake/Z180_Computer).

To compile the .pld files to .jed files I am using WinCUPL 
([PLD Design Resources | Microchip Technology](https://www.microchip.com/en-us/products/fpgas-and-plds/spld-cplds/pld-design-resources)) 
under Wine ([WineHQ - Run Windows applications on Linux, BSD, Solaris and macOS](https://www.winehq.org/)) 
using PlayOnLinux ([Home - PlayOnLinux - Run your Windows applications on Linux easily!](https://www.playonlinux.com/en/)) on Linux Mint.

The Arduino sketch afterburner.ino is uploaded to and running on an Arduino UNO and the Linux program afterburner is CLI controlling
the programmer.
