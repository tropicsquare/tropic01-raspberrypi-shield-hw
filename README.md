# TROPIC01 Raspberry Pi Shield

This repository contains the design files for the TROPIC01 development shield, designed for the Raspberry Pi form factor. Each folder corresponds to a specific PCB revision.

### About TROPIC01

For more information about the TROPIC01 secure element, please see the official documentation:

*   [TROPIC01 Datasheet](https://github.com/tropicsquare/tropic01/tree/main/doc/datasheet)
*   [TROPIC01 Website](https://www.tropicsquare.com/tropic01)

# Raspberrypi Shield's Versions

Following table shows all versions of distributed shields.

| hw revision    | Picture                                                                                                            |
|----------------|----------------------------------------|
| 1501           |  [Top](./TS1501_design/img/top.png)    |

# Getting Started

To interact with the TROPIC01 chip on Linux-based systems like Raspberry Pi OS and Ubuntu, we provide the [`libtropic-linux`](https://github.com/tropicsquare/libtropic-linux) repository, containing integration examples of our platform-independent SDK, [`libtropic`](https://github.com/tropicsquare/libtropic).

 > [!IMPORTANT]
 > Before you start with various examples, we strongly recommend to do two things first:
 > * Read CHIP ID and TROPIC01's firmware versions and **save printed output for future reference**
 > * Update TROPIC01's both internal firmware to latest version.

In [`libtropic-linux`](https://github.com/tropicsquare/libtropic-linux) repository, you can find specifice instruction for both operations based on hardware you use.

### Command line utility

Once you saved results of `show_chip_id_and_fw_ver` example (for future reference) and after your chip is updated with `fw_update` example, you can test our comand line application. Check out [`lt-util`](https://github.com/tropicsquare/libtropic-util) repository, you can find there specifice instruction based on hardware you use.