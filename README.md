# stk500boot_atmega256rfr2

Changes to the standard STK500 bootloader to support the ATMega256RFR2
(used by Altair). (Based on work by MeshThing http://www.m9design.co)

# Building

To build the firmware for the Altair or the ATMega256RFR2 Xplained
Pro.

```
make altair
```

To write the firmware to the board.

```
make flash
```

# Notes

For those of you trying to use this with the ATMega256RFR2 Xplained Pro, 
you must change the UART reguisters for RX1 and TX1 instead of RX0 and TX0.


# License
Licensed under the GPLv2 license.

