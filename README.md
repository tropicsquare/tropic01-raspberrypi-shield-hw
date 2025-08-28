# TROPIC01 Raspberry Pi Shield

This repository contains the design files for the TROPIC01 development shield, designed for the Raspberry Pi form factor. Each folder corresponds to a specific PCB revision.

### About TROPIC01

For more information about the TROPIC01 secure element, please see the official documentation:

*   [TROPIC01 Datasheet](https://github.com/tropicsquare/tropic01/tree/main/doc/datasheet)
*   [TROPIC01 Website](https://www.tropicsquare.com/tropic01)

# Getting Started

This guide will help you set up and use your TROPIC01 Raspberry Pi Shield.

### Prerequisites

*   A Raspberry Pi board running a Linux-based operating system.

### Basic examples

To interact with the TROPIC01 chip on Linux-based systems like Raspberry Pi OS and Ubuntu, we provide the [`libtropic-linux`](https://github.com/tropicsquare/libtropic-linux) repository. This repository is an integration showcase of our platform-independent SDK, `libtropic`, which contains also basic examples.

We recommend to clone it and **follow instructions to build examples**. Once examples are built, two examples are particulary useful when starting with devkit:

*   **Get chip info**: Prints detailed information about the TROPIC01 chip on the shield.
*   **Firmware update**: Updates the chip's firmware to the latest version (recommended)

For more information, please follow `README.md` in the  [`libtropic-linux`](https://github.com/tropicsquare/libtropic-linux) repository.

### Utility example

To interact with the TROPIC01 chip on Linux-based systems like Raspberry Pi OS and Ubuntu, we provide [`libtropic-util`](https://github.com/tropicsquare/libtropic-util) repository. Follow [apropriate readme there](libtropic-util/docs/readmes for all devkits) based on devkit version you have.

Or list?
 * lt-util/doc/1501readme.md
 * lt-util/doc/1502readme.md
