# Snag Swapper
Overengineered, overspecced and overpriced MMU for printers using single toolhead. This project is intended to be used with Voron Trident and Voron 2.x series printers mainly, being partially integrated into their frame. Although, it also can be used in a standalone mode with any printer running Klipper software.

## Table of content
- [Changelog](#changelog)
- [Showroom](#showroom)
- [Details](#details)
- [BOM](#bom)
- [Acknowledgements](#acknowledgements)

## Changelog

## Showroom

## Details
This project is inspired by ERCF with these initial thoughts:
* structurally integrated into VORON printer
* no strain on plastic parts: no bends, no latches, no clips, no plastic-on-plastic moving joints.
* easy to print plastic parts
* driving bondtech gear engages only with selected filament -> thus no need for gate mechanisms or cutters
* minimum use of sensors, rely on gear motor steps counter

The main difference from ERCF, Prusa MMU and other similar designs is that here we have the auxiliary extruder mounted right on selector caret. Driving bondtech gear is mounted on articulating arm, powered by micro servo. Idler bondtech gear sits in filament block, mounted on an articulated arm, suspended on magnets. When engaged, selector caret and a filament block are combined into a BMG extruder of the sort, with magnetically attached latch.

There is no spool holder and/or filament buffer to accompany this MMU, feel free to use any of many designs available.

## BOM

## Acknowledgements
Thanks to VORON Design devs and members of VORON Discord server. Special thanks to Team DropBear (#MakerBogans of AU&NZ).
