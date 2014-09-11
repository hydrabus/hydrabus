hydrabus micropython port firmware
========

HydraBus an open source multi-tool hardware

![HydraBus board](HydraBus_board.jpg)

For windows users how to flash micropython firmware for HydraBus:
1) To enter in USB DFU bootloader in order to flash a new firmware 
 1-1) PowerOff HydraBus board (disconnect all USB)
 1-2) Connect HydraBus pin BOOT0 to 3V3 (using a dual female splittable jumper wire) to enter USB DFU
 1-3) Connect MicroUsb cable from PC to HydraBus USB1 board, now windows shall detect a new device
     (if you have problem to detect the device use an USB1.1 or 2.0 Hub
      as there is problem with USB3.0 port on some computer and windows version).
 1-4) Download the USB DFU driver from current directory STM32F4_USB_DFU_Driver.zip
  1-4-1) Extract the archive and install the drivers.
 1-5) Launch from current directory update_fw_usb_dfu_hydrabus.bat (will flash latest firmware during about 20s)
 1-6) Disconnect MicroUsb cable from HydraBus and Disconnect "BOOT0 to 3V3"
 1-7) Reconnect MicroUsb cable on USB1, Now micropython is started.

Micro Python port for HydraBus (Beta version):
See https://github.com/bvernoux/micropython

To build micropython HydraBus port do:

    $ cd stmhal
    $ make BOARD=HYDRABUS

For more details see original micropython github: https://github.com/micropython/micropython
