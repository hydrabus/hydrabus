HydraBus Schematic and Board CadSoft Eagle 7.x
========

This directory contains HydraBus Schematic and Board for CadSoft Eagle 7.1 or more (free version works too)

HydraBus: Hardware license [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (for commercial licence contact info@hydrabus.com)

For more details on the hardware see also http://hydrabus.com/hydrabus-1-0-specifications/

V1.0 Revision 1.2 (Fully Compatible with Previous Board V1.0 Rev1.1):
  * Labels on both sides of the PCB with GPIO names (PBx, PCx ...).
  * Added R7 10K on PB2, BOOT0 is connected to JMP1-2 for easier BOOT USB DFU.
    * BOOT USB DFU (do not require any wire):
      1. Press UBTN button then Press RESET button
      2. Keep pressing UBTN then Release RESET
      3. Wait 1s then Release UBTN
