# Artix-7 Development Board (XC7A100T-FGG484)

## Overview

This repository contains the design files for the custom **Artix-7 XC7A100T-FGG484** FPGA development board. This board is built for high-performance applications such as hardware acceleration, video processing, data communication, and FPGA-based prototyping. It includes a variety of interfaces and peripherals to support advanced FPGA design projects.

![Preview](https://github.com/user-attachments/assets/52b948dd-cf17-4580-91e0-16bb9e09ef52)

## Key Features

- **FPGA**: Xilinx Artix-7 XC7A100T-FGG484
  - 101,440 logic cells
  - 4.9Mb Block RAM
  - 240 DSP slices

- **Memory**:
  - 1x DDR3 SDRAM: **AS4C256M16D3** (4GB) for high-speed data buffering and storage
  - 1x QSPI Flash Memory: **MT25QL512ABB8ESF-0AAT** (512Mb) for configuration bitstream storage and other non-volatile data

- **Interfaces**:
  - **USB Debug**: For programming and debugging via standard USB interface
  - **USB Client Mode**: Enabling the board to communicate with a host PC or embedded systems in client mode
  - **HDMI 1.4**: High-Definition Multimedia Interface for video output applications
  - **PCIe x1**: PCI Express interface for high-speed data communication and FPGA offloading
  - **Ethernet Port**: Standard Ethernet interface for networking applications and high-speed data transfer

## Technical Specifications

| **Component**     | **Specification**                        |
|-------------------|------------------------------------------|
| **FPGA**          | Xilinx Artix-7 XC7A100T-FGG484            |
| **Memory**        | DDR3 SDRAM (4GB), QSPI Flash (512Mb)      |
| **USB Ports**     | USB Debug, USB Client Mode                |
| **Video Output**  | HDMI 1.4                                  |
| **Storage**       | MT25QL512ABB8ESF-0AAT QSPI Flash Memory   |
| **PCIe Slot**     | PCIe x1                                   |
| **Networking**    | Ethernet Port                             |
  
## Example Projects

- **DDR3 Memory Test**: Demonstrates interfacing with the AS4C256M16D3 DDR3 memory.
- **HDMI Output**: A simple video output project using the HDMI 1.4 interface.
- **PCIe Communication**: An example of using the PCIe x1 slot for data transfer.
- **Ethernet Communication**: Demonstrates networking applications with the Ethernet port.
- **USB Debug**: Example for programming and debugging using the USB Debug interface.

## Getting Started

### Requirements

- **Vivado ML**: To build and program the FPGA bitstream.

### License
- This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

### Contributing
- Feel free to contribute to this project by submitting a pull request or reporting issues.

### Contact
- For any questions or support, contact ledio.zajmi@gmail.com




