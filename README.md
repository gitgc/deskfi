# deskfi
Things I need for [HifiBerryOS](https://github.com/hifiberry/hifiberry-os) room correction EQ via this [DSP](https://www.hifiberry.com/docs/data-sheets/datasheet-dac-dsp/) on the V3 ["Battle Station"](https://www.reddit.com/r/battlestations/). Calibration included for Jamo S803 speakers (measured at current battle station parking spot via [calibrated mic](https://www.minidsp.com/images/documents/Product%20Brief%20-%20Umik.pdf))/Hifiman HE-400i headphones, as well as configuration for Raspian machine running as touch screen controller for the DSP.
 
Hifiberry Machine is a [Raspberry Pi 4](https://static.raspberrypi.org/files/product-briefs/200521+Raspberry+Pi+4+Product+Brief.pdf) with the DSP attached. Giant heatsync optional 🔥

![the device!](https://raw.githubusercontent.com/gitgc/deskfi/master/images/deskfi.jpg)
 
Display Machine is also Pi 4, with official [touch screen](https://www.raspberrypi.org/documentation/hardware/display/) connected for controlling hifiberryOS/DSP via it's web UI. All Raspian OS interface elements stripped, auto boots to HifiBerry web UI.

![the other device!](https://raw.githubusercontent.com/gitgc/deskfi/master/images/deskfi-display.jpg)

Relying on mDNS to find devices for now.

* http://deskfi.local - DSP
* http://deskfi-display.local - Pi 4 with touchscreen locked in Chrome 'Kiosk Mode' to control `deskfi.local`.
 

## Folders

### display
The display directory contains key folders/customisations used to create Wifi touch screen machine for controlling HifiberryOS/DSP.

### hifiberry
This directory contains key files used to customise HifiBerry/DSP machine for my personal use.

### eq-settings
Backups of parabolic EQ adjustments taken from measurements.
