HydraBus
========

HydraBus an open source multi-tool hardware

![HydraBus board](HydraBus_board.jpg)

You can Buy HydraBus/HydraNFC Online: http://hydrabus.com/buy-online

![HydraBus pins assignment](HydraFW_Default_PinAssignment.png)

Wiki Getting Started: https://github.com/hydrabus/hydrafw/wiki/Getting-Started-with-HydraBus

HydraFW official firmware for Hydrabus
========

Wiki for HydraFW: https://github.com/hydrabus/hydrafw/wiki

See https://github.com/hydrabus/hydrafw

To build hydrafw see instructions here: 
* Windows: https://github.com/hydrabus/hydrafw/wiki/how-to-build-flash-and-use-hydrafw-on-windows
* Linux: https://github.com/hydrabus/hydrafw/wiki/how-to-build-flash-and-use-hydrafw-on-linux

Official Micro Python port for HydraBus
========
See https://github.com/micropython/micropython
Tested with GCC ARM 4.9 2015q3(GNU_ARM_4_9_2015q3) 
* See https://github.com/hydrabus/hydrafw_hydranfc_shield_v2/wiki `How to Build/Flash/Use HydraFW` for more details

To build micropython for HydraBus do:

    git clone --recursive https://github.com/micropython/micropython
    cd micropython/ports/stm32
    make BOARD=HYDRABUS

* At end of build you shall have:
 * GEN build-HYDRABUS/firmware.dfu
 * GEN build-HYDRABUS/firmware.hex
* In order to flash the *.dfu follow steps here: https://github.com/hydrabus/hydrafw/wiki/Getting-Started-with-HydraBus

For more details on official micropython hydrabus port see: https://github.com/micropython/micropython/tree/master/ports/stm32/boards/HYDRABUS

Official Black Magic JTAG/SWD debugger port for HydraBus
========
See https://github.com/blacksphere/blackmagic.git

Before to build the firmware check this issue (as you need a new GCC ARM Compiler >=4.9): https://github.com/blacksphere/blackmagic/issues/128
Tested with GCC ARM 4.9 2015q3(GNU_ARM_4_9_2015q3)
* See working version for reference blackmagic_branch_hydrabus_Firmware 1.5-00319-g49390fe-dirty.zip:
  * https://github.com/hydrabus/hydrabus/files/11436416/blackmagic_branch_hydrabus_Firmware.1.5-00319-g49390fe-dirty.zip
* Note: Latest version of blackmagic have "Device failed enumeration" issue see https://github.com/hydrabus/hydrabus/issues/4
* See https://github.com/hydrabus/hydrafw_hydranfc_shield_v2/wiki `How to Build/Flash/Use HydraFW` for more details

To build Black Magic for HydraBus do:

    git clone --recursive https://github.com/blacksphere/blackmagic.git
    cd blackmagic
    make PROBE_HOST=hydrabus

* At end of build you shall have:
 * OBJCOPY blackmagic.bin
 * OBJCOPY blackmagic.hex
 * Creating blackmagic.dfu
* In order to flash the *.dfu follow steps here: https://github.com/bvernoux/hydrafw/wiki/Getting-Started-with-HydraBus

For more details on official blackmagic hydrabus port see:
https://github.com/blacksphere/blackmagic/tree/master/src/platforms/hydrabus
