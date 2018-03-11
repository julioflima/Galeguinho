# This is a KiCAD Library.

#### Forked in a @adamgreig.

This repository contains my collection of KiCAD symbols.

I encourage other people to use these parts; they're all licensed under a
permissive MIT licence and it's easy to simply copy one or two files from the
repository, or submodule the entire repo.

Contributions are also very welcome; please open a pull request and I will
carefully review the proposed additions. All contributions are likewise
licensed under the MIT licence. See `CONTRIBUITING`.

## Schematic Symbols

To use, add relative path `Galeguinho/lib`, in `Eeschema - Eletronic schematic editor > Preferences > Components Libraries` or `Schematic  library editor > Preferences > Components Libraries`. There is one `.lib` file per symbol, so you can add just some library that you find relevant.

## PCB Footprints

To use, add the path in:
> KICAD > Pcbnew - Printed circuit board editor  > Preferences > Configure Paths 

or 

> KICAD > PCB footprint editor > Preferences > Configure Paths

Click in add, in field name put the Path `DIRECTORY_OF_YOUR_COMPUTER_IGNORE_THIS_PHASE/Galeguinho` and in field Name put the tag `GALEGMOD` to do the 3D modules be reconized. Please pay attention in enviroment of your operational system, in UNIX (MAC, LINUX) the slashes are inclined to right `/`, and in Windows the slashes are inclined to left `\`.

Before that:
> KICAD > Pcbnew - Printed circuit board editor  > Preferences > Footprint Libraries Manager 
or 

> KICAD > PCB footprint editor > Preferences > Footprint Libraries Manager

Click in Append Library, in Nickname put Galeguinho for the footprints be recognize automatically and in  Library Path add `${GALEGMOD}/Galeguinho.pretty`.     

The major ones have 3D files.


## 3D PCB Footprints

If you wanna adit some 3D files, the ones are in `Galeguinho/CAD`. Hint: use the FreeCAD.

## Licence

All content licensed under the MIT licence. See `LICENSE`.