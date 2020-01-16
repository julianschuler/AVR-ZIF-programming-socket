# AVR ZIF programming socket
## Overview
This adapter board provides a simple way of connecting an In-System-Programmer to an AVR microcontroller in DIP format using a zero insertion force (ZIF) socket. It is intendet for fast prototyping, initial bootloader flashing and testing without the hassle of faulty breadboard jumpers or unnecassary connection errors. 

## Features
The programming socket provides support for all AVR microcontrollers available in the prototype friendly DIP format supporting In-System-Programming (ISP).
Furthermore the board supplies connections to 8Mhz crystals, thus the AVRs will also be programmable with the fuses set for an external crystal from 3-20Mhz, making it ideal for programming fuses and flashing programs for circuits utilizing external crystals.

## How to use
Put your AVR in the ZIF socket by aligning the IC mark for the first pin (the dot and/or indentation) with the lower edge of the ZIF socket (near the ZIF socket lever). Afterward, find your AVR name in the list below and connect your In-System-Programmer to the corresponding ISP header (see [AVRs per ISP header](#avrs-per-isp-header)).

## AVRs per ISP header
ISP header 1 is next to the ZIF socket lever.
- ISP header 1: ATtiny12 / ATtiny13 / ATtiny15L / ATtiny25 / ATtiny45 / ATtiny88
- ISP header 2: ATtiny24 / ATtiny44 / ATtiny84
- ISP header 3: ATtiny2313 / ATtiny4313
- ISP header 4: ATtiny26 / ATtiny261 / ATtiny461 / ATtiny861
- ISP header 5: ATtiny44 / ATtiny88 / ATmega8 / ATtmega48 / ATmega88 / ATmega168 / ATmega328
- ISP header 6: ATmega162 / ATmega8515 / ATmega8535 
- ISP header 7: ATmega16 / ATmega32 / ATmega164 / ATmega324 / ATmega644 / ATmega1284 / ATmega64RZAV

## License
This project is licensed under the MIT license, see [`LICENSE.txt`](LICENSE.txt) for further information.
