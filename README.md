# 2x5 pin 1.27 mm male to 2.54 mm male header adapter PCB

This board was created to convert  between the "small" J-Link EDU Mini Programmer-Debbuger 1.27 mm pitch connector to a 2.54 mm male header.

*Read this in other languages: [Español](README.es.md)*

![PCB 3D picture](docs/pcb3d.png)

The J-Link EDU Mini sports a 2x5 1.27 mm male connector and includes a female to female 2x5 1.27 mm ribbon cable for target connection.

If for some reason your target doesn't have the same connector (debug pins scattered somewhere on th PCB) or want to connect to a circuit on a breadboard, this PCB wil ease the task. 
## How to use this repository

The PCB was developed in KiCad V5.1, and include some elements that are not merged yet to the main KiCad library repo.  To make sure nothing  will break on the future, all the KiCad libraries were included as submodules, so to clone the repo use the  --recursive option to get all submodules (about 5 Gb !!).

To setup KiCad to use the downloaded library from the repo instead of the stock that came with the installer, [this post](https://forum.kicad.info/t/library-management-in-kicad-version-5/14636) will give you some lights.

download libraries, link to kicad setup external libs, license open source --recursive
