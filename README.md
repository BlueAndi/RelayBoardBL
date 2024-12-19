# Relay Board 01 - Bootloader<!-- omit in toc -->

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](http://choosealicense.com/licenses/mit/)
[![Repo Status](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Release](https://img.shields.io/github/release/BlueAndi/RelayBoardBL.svg)](https://github.com/BlueAndi/RelayBoardBL/releases)

A bootloader for [RelayBoard01](https://github.com/BlueAndi/RelayBoard01), which follows the VSCP standard bootloader algorithm.

## Bootloader Jumper
A simple bootloader which jumps only to the application.

## Bootlaoder VSCP
A bootloader which follows the VSCP standard bootloader algorithm.

# Used Libraries

| Library | Description | License |
| - | - | - |
| [Arduino](https://github.com/arduino/ArduinoCore-avr) | Arduino AVR Boards | LGPL |
| [avr-can-lib](https://github.com/dergraaf/avr-can-lib) | MCP2515 CAN transceiver driver. | BSD |
| [PlatformIO](https://platformio.org) | PlatformIO is a cross-platform, cross-architecture, multiple framework, professional tool for embedded systems engineers and for software developers who write applications for embedded products. | Apache-2.0 |
| [VSCP L1 Framework](https://github.com/BlueAndi/vscp-framework) | Very Simple Control Protocol (VSCP) Level 1 Framework. | MIT |
| [VSCP Bootloader](https://github.com/BlueAndi/vscp-bootloader) | Very Simple Control Protocol (VSCP) Level 1 Bootloader. | MIT |

# Issues, Ideas And Bugs
If you have further ideas or you found some bugs, great! Create a [issue](https://github.com/BlueAndi/RelayBoardBL/issues) or if you are able and willing to fix it by yourself, clone the repository and create a pull request.

# License
The whole source code is published under the [MIT license](http://choosealicense.com/licenses/mit/).
Consider the different licenses of the used third party libraries too!

# Contribution
Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, shall be licensed as above, without any
additional terms or conditions.
