# Power Board

This is the repository for MOSAIC's Power Board.

For detailed documentation on the Power Board, check out its core documentation [here](https://www.mosaicsat.org/core_documentation/hardware/power_board/).

To get your own MOSAIC Main Board, visit the MOSAIC fabrication guide [here](https://www.mosaicsat.org/getting_mosaic/).

## Current Features

*Newest board version: 2.0*

| **Feature** |
| :----------- |
| 6x high-side DC sensors for solar cells |
| LiPo battery high side DC sensor |
| Single-cell LiPo battery charger circuit |
| 12x  2mm JST solar cell input jacks|
| 2x 2mm JST battery input jacks |
| LiPo battery overcharge protection |
| Solar cell reverse current protection |
| 2x Qwiic connectors for I2C connection to Main Board |

## Planned Changes

The following are the current plans for changes to MOSAIC's Power Board. 

- The current version of MOSAIC's Power Board is designed to be used with only a single-cell LiPo battery like [this one](https://www.sparkfun.com/lithium-ion-battery-2ah.html). Future iterations of the Power Board should include the option to utilize different energy storage methods, such as AA and 18650 batteries. This, of course, will require a different charger circuit for each method, so the board may include a new slot where users can plug in their preferred power charger circuit. 

## Change Log

You can find the change log for the Power Board on MOSAIC's website [here](https://www.mosaicsat.org/core_documentation/hardware/power_board/change_log/). 
