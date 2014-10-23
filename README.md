hydrabus
========

HydraBus an open source multi-tool hardware

![HydraBus board](HydraBus_board.jpg)

You can Buy HydraBus/HydraNFC Online in Seeed Studio Online Shop:
http://www.seeedstudio.com/depot/HydraBus-m-132.html

![HydraBus pins assignment](http://hydrabus.com/HydraBus_1_0_PinAssignment.jpg)

Wiki for HydraFW: https://github.com/bvernoux/hydrafw/wiki

Wiki Getting Started: https://github.com/bvernoux/hydrafw/wiki/Getting-Started-with-HydraBus

HydraFW official firmware for HydraBus/HydraNFC: https://github.com/bvernoux/hydrafw

Firmware source code:

    Directory firmware/micropython:
        For instructions and latest binary+tools to flash it on HydraBus
    Directory firmware/hydrafw:
        For instructions for HydraBus / HydraNFC Shield native firmware

Micro Python port for HydraBus (Beta version):
See https://github.com/bvernoux/micropython

To build micropython HydraBus port do:

    $ cd stmhal
    $ make BOARD=HYDRABUS

For more details see original micropython github: https://github.com/micropython/micropython
