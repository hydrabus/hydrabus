HydraBus
========

HydraBus an open source multi-tool hardware

![HydraBus board](HydraBus_board.jpg)

You can Buy HydraBus/HydraNFC Online in Seeed Studio Online Shop:
http://www.seeedstudio.com/depot/HydraBus-m-132.html

![HydraBus pins assignment](http://hydrabus.com/HydraBus_1_0_PinAssignment.jpg)

Wiki Getting Started: https://github.com/bvernoux/hydrafw/wiki/Getting-Started-with-HydraBus

HydraFW official firmware for Hydrabus
========

Wiki for HydraFW: https://github.com/bvernoux/hydrafw/wiki

See https://github.com/bvernoux/hydrafw

To build hydrafw do:
See instructions here: https://github.com/bvernoux/hydrafw#how-to-build-flash-and-use-hydrafw-on-windows

Micro Python port for HydraBus
========
See https://github.com/bvernoux/micropython

To build micropython HydraBus port do:

    $ cd stmhal
    $ make BOARD=HYDRABUS

For more details see original micropython github: https://github.com/micropython/micropython

Black Magic JTAG/SWD debugger port for HydraBus
========
See https://github.com/bvernoux/blackmagic

To build Black Magic HydraBus port do:

    $ cd blackmagic/src
    $ make PROBE_HOST=hydrabus

For more details on hydrabus port see:
https://github.com/bvernoux/blackmagic/tree/master/src/platforms/hydrabus

