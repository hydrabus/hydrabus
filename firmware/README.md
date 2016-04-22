hydrabus firmware
========

HydraBus firmware directories for HydraBus hardware

Firmware source code:

    Directory micropython:
        For instructions and latest binary+tools to flash it on HydraBus
    Directory hydrafw (submodule):
        For instructions for HydraBus / HydraNFC Shield native firmware (for windows & linux)

HydraFW for HydraBus/HydraNFC:
See https://github.com/bvernoux/hydrafw

Micro Python port for HydraBus (Beta version):
See https://github.com/bvernoux/micropython

To build micropython HydraBus port do:

    $ cd stmhal
    $ make BOARD=HYDRABUS

For more details see original micropython github: https://github.com/micropython/micropython
