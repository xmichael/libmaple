#libmaple port to cheap stm32F1xx maple-mini alikes

## About
This is a port of libmaple to cheap sub-$5 STM32F103C8T6 boards found on ebay like the one described [here](http://www.rogerclark.net/stm32f103-and-maple-maple-mini-with-arduino-1-5-x-ide/)

## Quick Start
1. Flash the official maple bootloader using SWD (with a discovery board or even a bus pirate) by following the [upstream instructions](http://leaflabs.com/docs/bootloader.html)
2. Clone this fork of libmaple following the [upstream instructions](https://github.com/leaflabs/libmaple). The only difference is that you will need to define BOARD=minimal instead of e.g. BOARD=maple_mini
