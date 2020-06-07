# PCB adaptador de conector 2x5 pines 1.27 mm macho a conector 2x5 pines  de 2.54 mm  macho

Esta tarjeta fue creada para convertir del conector "pequeño" de 1.27 mm que trae el  Programador-Depurador J-Link EDU Mini a un conector macho de 2.54 mm.

*Lea esto en otros idiomas: [English](../README.md)*

![PCB 3D picture](pcb3d.png)

The J-Link EDU Mini sports a 2x5 1.27 mm male connector and includes a female to female 2x5 1.27 mm ribbon cable for target connection.

If for some reason your target doesn't have the same connector (debug pins scattered somewhere on the PCB), or want to connect to a circuit on a breadboard, this PCB will ease the task. 
## How to use this repository

The PCB was developed in KiCad V5.1, and include some elements that are not merged yet to the main KiCad library repo.  To make sure nothing  will break on the future, all the KiCad libraries were included as git submodules, so to clone the repo use the  --recursive option to get all submodules (about 5 Gb !!).

To setup KiCad to use the downloaded library from the repo instead of the stock that came with the installer, [this post](https://forum.kicad.info/t/library-management-in-kicad-version-5/14636) will give you some lights.

## Directory structure

* The root folder contains KiCad files: project, schematic and PCB.
* library directory (git submodule) contains schematics symbol libraries.
* modules directory (git submodule) contains footprint libraries.
* packages3d directory (git submodule) contains 3D model libraries.
* gerber/single directory contains ready to manufacture files, for a single board.
* gerber/panel_100mmx100mm directory contains ready to manufacture files that fits in a 100mm x 100mm panel (use Vcuts!).
* docs directory some additional info about the project.

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
