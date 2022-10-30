# CR 10 BigTreeTech E3 V3 Firmware

## Printer Setup 
I have created firmware for a CR10 style printer with a blTouch and a BTT E3 V3 Motherboard. 

There are two options for wiring the blTouch:

### Option 1
Plug in BLTouch into BLTouch port on the motherboard. This is the standard way to connect the BLTouch would be to connect all five wires to the BLTouch port. This option provides an extra layer of protection in case the probe on the BLTouch has issues.

[Pictures Here](https://3dprintscape.com/bltouch-on-skr-mini-install-guide/)

### Option 2
Another common way to connect the BLTouch is to connect the probe stop into the z-stop port and not use the z-stop at all. 

[Pictures Here](https://3dprintscape.com/bltouch-on-skr-mini-install-guide/)




## Compile It Yourself 

- [ ]  Download [VS Code](https://code.visualstudio.com/download)


- [ ] Download the latest version of the [Marlin Firmware](https://marlinfw.org/meta/download/)

- [ ] Replace Configuration.h and Configuration_adv.h from your perfered wiring from this github with the ones in Marlin Firmware

- [ ] Open Marlin Folder in VSC and make any edits, click the marlin auto compiler, click build.



## Install

- [ ] If using precompiled firmware chose wiring option and rename to Firmware.bin

- [ ] Place Firmware.bin file on a sd

- [ ] Plug into printer and turn on

