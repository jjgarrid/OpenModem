Open Modem Firmware experimental version (forked)
==========

This is a fork of the original OpenModem firmware from Mark Qvist at [OpenModem page](https://unsigned.io/openmodem/)

The goal of this fork is to create a new PCB from the original schematics and to change the firmware to include other features.

This is a personal learning project that is meant to be used for experimentation, if you are interested in OpenModem and you want a stable product, you should go to the original creator github page.

Original README.md follows...

Open Modem Firmware is an open source firmware implementation of a AFSK modem supporting 300, 1200 and 2400 baud operation, suitable for communication over a wide variety of analogue mediums, both radio and wired. The firmware is designed for and compatible with [unsigned.io's OpenModem](https://unsigned.io/openmodem/), but can be used on any similar build.

Complete modems are available from [the unsigned.io shop](http://unsigned.io/shop), or can be build from scratch by referring to the schematics and documentation on the [OpenModem page](https://unsigned.io/openmodem/)

## A few highlights

- 300, 1200 and 2400 baud operation
- Full KISS TNC compatibility
- Secure in-modem AES-128 encryption
- SD card support
- Packet logging in PCAP format (WireShark compatible)
- Digitally adjustable input and output gain control
- Easy to use graphical config utility
- Supports standard GPS and bluetooth modules
- Supports large packets, 576 byte MTU
- Very large in-modem packet queue

## Usage

Please refer to the manual and instructions posted at the [OpenModem page](https://unsigned.io/openmodem/). The default serial connection settings are 115200 baud, 8N1. For configuring the modem, please see the OpenModem Config Utility.

## Support OpenModem Development
You can help support the continued development of open, free and private communications systems by donating via one of the following channels:

- Ethereum: 0x81F7B979fEa6134bA9FD5c701b3501A2e61E897a
- Bitcoin: 3CPmacGm34qYvR6XWLVEJmi2aNe3PZqUuq
- Ko-Fi: https://ko-fi.com/markqvist
