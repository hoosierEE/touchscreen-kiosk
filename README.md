Touchscreen Stuff
=================

Building a Touchscreen from components.

Pinouts
-------

Computer Side

| USB B receptacle | 3M Microtouch USB controller |
|------------------|------------------------------|
| 1                | +5vdc                        |
| 2                | data (DN)                    |
| 3                | data (DP)                    |
| 4                | power return                 |
| 5                | shield                       |

Touchscreen Side

| Transducer | fcn | Cat 5 Ethernet |
| ---------- | --- | -------------- |
| 1          | UL  | 2              |
| 2          | UR  | 4              |
| 3          | GND | 1, 3, 5, 7     |
| 4          | LR  | 6              |
| 5          | LL  | 8              |

![](https://raw.githubusercontent.com/hoosierEE/touchscreen-kiosk/master/images/pinouts.jpg)

> ...where UL = Upper Left, etc.
