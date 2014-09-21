hydrabus
========

HydraBus an open source multi-tool hardware

![HydraBus board](HydraBus_board.jpg)

Firmware source code:

    Directory firmware/microptyhon:
        For instructions and latest binary+tools to flash it on HydraBus
    Directory firmware/hydrafw:
        For instructions for HydraBus / HydraNFC Shield native firmware

Micro Python port for HydraBus (Beta version):
See https://github.com/bvernoux/micropython

To build micropython HydraBus port do:

    $ cd stmhal
    $ make BOARD=HYDRABUS

For more details see original micropython github: https://github.com/micropython/micropython
