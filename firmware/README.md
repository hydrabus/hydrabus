hydrabus firmware
========

HydraBus firmware directories for HydraBus hardware

You can Buy HydraBus/HydraNFC Online in Seeed Studio Online Shop:
http://www.seeedstudio.com/depot/HydraBus-m-132.html

Firmware source code:

    Directory micropython:
        For instructions and latest binary+tools to flash it on HydraBus
    Directory hydrafw:
        For instructions for HydraBus / HydraNFC Shield native firmware (for windows & linux)

Micro Python port for HydraBus (Beta version):
See https://github.com/bvernoux/micropython

To build micropython HydraBus port do:

    $ cd stmhal
    $ make BOARD=HYDRABUS

For more details see original micropython github: https://github.com/micropython/micropython
