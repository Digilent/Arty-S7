# Arty S7 Root Repository

## Arty S7-25 XADC Demo

### Description

This branch contains sources for the Arty S7-25 XADC Demo.

This simple XADC Demo project demonstrates a simple usage of the Arty S7's XADC pin capability. The behavior is as follows:
  * The 6 User LEDs increment from top right to left then bottom right to left as the voltage difference on the selected XADC pins gets larger.
  * The four switches select which channel to read from.

For more information on the Arty S7-25 XADC Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/arty-s7/demos/xadc) on the Digilent Wiki.

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

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Arty-S7-25-XADC/

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* Arty S7-25T
* Vivado 2020.1 installation
* MicroUSB cable
* Wires and a circuit to measure
