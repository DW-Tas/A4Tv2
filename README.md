# A4Tv2: A new version of [A]nother [4]01x [T]oolhead

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

A4Tv2 is a new version of [A4T](https://github.com/DW-Tas/A4T), from: [![ko-fi](docs/images/Ko-fi_smol.png)](https://ko-fi.com/O5O5OCC0K) [DW-Tas](https://github.com/DW-Tas)

![A4Tv2 toolhead render](docs/images/A4Tv2.png)

> [!TIP]
> **A4Tv2 is a prerelease.** This design is still in development and should be treated as experimental. It is not a fully documented release.

## Documentation and assembly

There is currently no complete documentation for A4Tv2 and no installation or assembly instructions. The CAD, STL, and 3MF files have been exported and are available to get started with.

## Files

- `CAD/` contains STEP files, including the A4Tv2 assembly STEP and ZIP exports.
- `STL/` contains exported STL files.
- `3MF/` contains exported 3MF files.


## Fan Options

 - **`4015:`** Finding *GOOD* 4015 fans is a challenge. Peopoly [Magneto X Lancer Extruder Side Turbo Fan](https://peopoly.net/products/magneto-x-lancer-extruder-side-turbo-fan?variant=50568975810842)s have amazing flow and pressure (not far of 5015s), but, they require hardware PWM and slicer configuration to compensate for slow spin up time (around 1 second).
 - **`4010 inbuilt backflow inhibitor:`** These ducts for the GDStime 12k 4010 fans are made with the backflow inhibitor built in. Take the front off the fan before installing into the duct.
 - **`4010:`** A generic duct that fits most 4010 fans. Requires backflow inhibitors to be installed in the same way as A4T. Good to reuse fans with inhibitors already glued in place.

> [!WARNING]
>## UHF hotend screw warning
>
>The UHF versions, including Rapido X, use countersunk screws to hold the hotend to the main body. The wedge shape of a countersunk screw may put outward force on the printed plastic and cause it to creep or split over time. Treat these versions as experimental and inspect the printed part for cracking or deformation. Feedback encouraged.

<br/><br/>
> [!TIP] 
> ### You can help support the development of this project.<br/>
> Donate at https://ko-fi.com/dwtas<br/>
[![ko-fi](docs/images/Ko-fi_TextLogo.png)](https://ko-fi.com/dwtas)
<br/><br/>

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

### License clarification regarding non-commercial use:
The non-commercial aspect of this license is for cases where A4Tv2 is the product, not the use of A4Tv2 to create products.<br/>
For example, if you wish to sell A4Tv2 as a product, you would need to seek a commercial license before doing so. </br>
It is NOT intended to prevent the use of A4Tv2 in a printer that you use to provide commercial services. If you want to run A4Tv2 as a toolhead for your print farm printers, go right ahead.