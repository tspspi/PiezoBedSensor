# Piezo bed leveling sensor interface

NOTE: This readme will be extended soon.

This repository contains the KiCad files for an interface board
between four piezo disk level sensors and an 3D printer. Its based
on an ATMega328P that might either be powered from an existing
5V power rail or via the optional on board power regulator. It allows
interfacing via I2C to perform settings and calibration as well
as an traditional trigger output (for example to interface directly
with an RAMPS board) and an trigger input for a classical inductive
or capacitive leveling sensor.

More information can be found [at my webpage](https://www.tspi.at/2019/09/11/piezobedlevel.html).

Each piezo is biased independently.

## License

See LICENSE.md