Transducer Extension Cable
==========================

This box adapts the 3M Multitouch screen overlay for use with common cables. The metal enclosure houses the adapter board and provides an easier grip for cable changes.

One side connects to the computer via USB:
![](https://raw.githubusercontent.com/hoosierEE/touchscreen-kiosk/master/images/usbSide.jpg)

The other side connects to the overlay via an RJ45 extension cable (adapter required at the overlay end of the cable):
![](https://raw.githubusercontent.com/hoosierEE/touchscreen-kiosk/master/images/transducerSide.jpg)

Inside is just the adapter board and jacks:
![](https://raw.githubusercontent.com/hoosierEE/touchscreen-kiosk/master/images/wiring.jpg)

Pinouts
-------

![](https://raw.githubusercontent.com/hoosierEE/touchscreen-kiosk/master/images/pinouts.jpg)

### Computer Side

| USB B receptacle | 3M Microtouch USB controller |
|------------------|------------------------------|
| 1                | +5vdc                        |
| 2                | data (DN)                    |
| 3                | data (DP)                    |
| 4                | power return                 |
| 5                | shield                       |

### Touchscreen Side

| Transducer | fcn | Cat 5 Ethernet |
| ---------- | --- | -------------- |
| 1          | UL  | 8              |
| 2          | UR  | 6              |
| 3          | GND | 1, 3, 5, 7     |
| 4          | LR  | 4              |
| 5          | LL  | 2              |

> ...where UL = Upper Left, etc.
