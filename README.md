# RP2040 MCU Base Board Template
A template EasyEDA project with Raspberry Pi RP2040, USB-UART Bridge, 16MB Flash and 800mA LDO optimised for JLCPCB PCBA.

# Specifications

* 4-layer PCB optimized for JLCPCB PCB Assembly Service
* All components are available from JLCPCB
* Raspberry Pi RP2040 MCU
* CH340G USB-to-UART Bridge
* AMS1117-3.3V LDO
* Power Filtering Circuit
* Power Indicating LED
* USB Type-C for RP2040 USB
* USB Type-C for USB-to-UART Bridge
* Boot and Reset Buttons
* SWD Header for advanced debugging
* W25Q128JVSIQTR 16 MB Flash Chip

# Preview
![board](https://user-images.githubusercontent.com/6614616/152640249-a5a2907a-52f4-4841-9b09-49c20f084728.png)

# Schematic
![Schematic](https://user-images.githubusercontent.com/6614616/152642811-e23c4131-588b-4dc8-b0f7-8c02f960576f.png)

You can find the PDF [here](Schematic.pdf).

# Board Rules
* 0.127mm minimum trace width
* 0.127mm minimum trace spacing
* 0.127mm for low-current short connection
* 0.254mm for low-current long connections
* 0.4mm for power supply rails
* 0.4mm minimum outer via diameter
* 0.2mm minimum via diameter drill size

# Remaining Tasks
* Adjust ground planes to project layer setup
* Connect I/O according to project requirements

# License
This work is released under the CC BY SA 4.0 license.

You can find a copy of the license in the [LICENSE.md](LICENSE.md) file.
