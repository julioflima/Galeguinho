# Schematic Symbols

Directory                |  Contents
-------------------------|----------
[`connector`](connector) | Connectors
[`ic`](ic)               | ICs including microcontrollers, amplifiers, sensors,etc
[`misc`](misc)           | Other parts including generic/drawing symbols
[`module`](module)       | PCB subassemblies and modules
[`power`](power)         | Power symbols
[`passive`](passive)     | Passive and other two-terminal devices including crystals, etc
[`ui`](ui)               | User interface elements including buzzers, switches, etc

### Enforced automatically

* One symbol per library
    * Exception for automatically generated libraries such as `conn.lib`
* Library filename the same as the part name
* All pins on 100mil grid
* 100mil pin length for ICs and similar symbols
* No missing numbers in pin numbering sequence
* Text size 50mil (fields, pin names, pin numbers)
    * Exception for pin numbers that are words, e.g. "PAD"
* Part reference above the part
* Part name (value field) below the part
* Fields must be horizontal
* Name and reference fields must be visible unless explicitly overridden
* Other fields (footprint, datasheet, order codes) must be invisible
* ICs and similar symbols to be filled with background colour

## Associated documentation to include in README

* Link to datasheet/web page
* Common supplier order codes
* Names of available footprints
* Has the symbol been validated in practice? Where?
* Any other notes / gotchas
