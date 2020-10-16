# Arty S7 Root Repository

## Arty S7-50 GPIO Demo

### Description

This branch contains sources for the Arty S7-50 GPIO Demo.

Introductory level demonstration project for the Arty S7's LEDs, switches, buttons, and USB-UART bridge.

All the switches are tied to their corresponding led. Every time a switch is toggled, the led directly above it will toggle with it.

The two tri-color LEDs will cycle colors with no interruption from other I/O. 

 On startup, the Arty S7 will transmit “ARTY GPIO/UART DEMO!”. Whenever a button is pressed, Arty S7 transmits “Button press detected!”.

For more information on the Arty S7-50 GPIO Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/arty-s7/demos/gpio) on the Digilent Wiki.

For more information on the Arty S7, including other demos that may be available, see its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/arty-s7/start) on the Digilent Wiki.

### Git Navigation Information

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Arty-S7).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes        |
| OS        | No         |
| SW        | No         |

FIXME: remove any submodules that are not present in the root repo.

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Arty-S7-50-GPIO/

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* Arty S7-50T
* Vivado 2020.1 installation
* MicroUSB cable
* Serial Terminal Emulator