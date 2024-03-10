# uMSX
The uMSX is a MSX2+ FPGA implementation that basically mimics the Zemmix (one of the first FPGA based MSX2+ one chip MSX computers commercially available).

PCB created by BCH. 

The VHDL used is the well known [KDL PLD implementation for the MSX2+](https://github.com/gnogni/ocm-pld-dev) used by the vast majority of the FPGA based MSX computers known. The uMSX uses the first generation of the KDL VHDL source, also known by esemsx.

Based on the already obsolete (but relatively easy to find) Altera EP1C12 FPGA (specifically the EP1C12Q240C8N), the uMSX uses SMD based components (and a few PTH) in a nice compact form factor. It uses the 4 megabit EPCS4 active serial configuration flash memory to host the firmware and configure the FPGA chip at each time the circuit turns on.

A MT48LC16M16A2 SRAM chip offers memory for the computer, which also uses a few other components to implement the clock logic (NC7WV04P6X inverter and 21.47727 basic PTH crystal oscillator) and a 953B voltage detector and reset IC.

Heavily based on 0603 SMT resistance arrays, and other 0805 SMT components, the uMSX is a compact little OCM MSX that can be used to evolve your SMD soldering skills, challenge your knowledge of modern electronics applied to retro computing, and give you a lot of fun through the journey.

* Original thread (in Spanish) with details about the project [uMSX: Clon MSX2+ FPGA](https://www.va-de-retro.com/foros/viewtopic.php?f=63&t=6655)

* Article (in English) with details on how to build, BoM, tips and tricks [Yet another FPGA based MSX (The uMSX)](https://theretrohacker.com/2022/07/08/yet-another-fpga-based-msx-the-umsx/)

* Youtube video (in Portuguese) with additional details [YouTube Video](https://www.youtube.com/watch?v=aj3B5qDagoM)

## License 

![Open Hardware](Images/ccans.png)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

* If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
* You may not use the material for commercial purposes.
* You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

**ATTENTION**

This project was made for the retro community and not for commercial purposes. So only retro hardware forums and individual people can build this project.

THE SALE OF ANY PART OF THIS PROJECT WITHOUT EXPRESS AUTHORIZATION IS PROHIBITED!