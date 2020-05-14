HydraBus Schematic and Board KiCad (5.1.5)-2
========

This directory contains HydraBus Schematic and Board for KiCad (5.1.5)-2

HydraBus: Hardware license [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (for commercial license contact info@hydrabus.com)

For more details on the hardware see also http://hydrabus.com/hydrabus-1-0-specifications

Revision 1.4 (vs Rev 1.3)
- The BOM has been optimized to find/buy most of the parts on lcsc.com
- HydraBus v1 Rev1.4 is fully designed under KiCad 5.1.5-2 (Latest official stable release), before it was designed with Eagle 6.x
- 8MHz Crystal Y1 has been replaced by a SMD part (Yangxing Tech X50328MSB2GI) on top side of the PCB with better performances (X50328MSB2GI +/-10ppm vs +/-30ppm on FOXSLF/080-20).
- Capacitors C1 & C2 for the 8MHz Crystal are changed to 18pF (before it was 27pF) to prevent some USB issues on some board which does not work correctly with STM32F405 USB DFU (embedded in ROM).
- Decoupling capacitors (100nF replaced by 220nF, 1uF replaced by 2.2uF) are modified to use less references with higher value which also reduce the noise.
- microSD connector part replaced by compatible part HOAUC HYC77-TF09-200UBTN/BOOT DFU and RESET switch replaced by compatible part HYP (Hongyuan Precision) 1TS002G-2700-3500-CTTo summarize there is no any functional change between HydraBus v1 Rev1.4 and previous versions

To summarize there is no any functional change between HydraBus v1 Rev1.4 and previous versions
