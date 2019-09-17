# Piezo bed leveling sensor interface

This repository contains the kicad files for an interface board
between four piezo disk level sensors and an 3D printer. Its based
on an ATMega328P that might either be powered from an existing
5V power rail or via the optional on board power regulator. It allows
interfacing via I2C to perform settings and calibration as well
as an traditional trigger output (for example to interface directly
with an RAMPS board) and an trigger input for a classical inductive
or capacitive leveling sensor.

Each piezo is biased independently.

NOTE: This readme will be extended soon.