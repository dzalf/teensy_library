Teensy symbol library for KiCAD
=======================================

This repo includes KiCAD symbols for the following Teensy versions:

  - Teensy 1.0
  - Teensy++ 1.0
  - Teensy 2.0
  - Teensy++ 2.0
  - Teensy 3.0
  - Teensy 3.1
  - Teensy 3.2
  - Teensy 3.5
  - Teensy 3.6
  - Teensy 4.0
  - Teensy 4.1
  - Teensy LC

There are two symbols for Teensy 3.5/3.6: one that includes the through-hole connections on Teensy and one that adds all of the SMT connections on the bottom of the Teensy.


For footprints look here: https://github.com/XenGi/teensy.pretty


**_dzalf's_ fork**

Changes and nomenclature:

1. A new branch titled "ported-to-KiCAD_7" was added. Useful for those using the latest version only.
2. All symbols were filled with body background color (default [#ffffc2](https://placehold.co/15x15/ffffc2/ffffc2.png) `#FFFFC2` from KiCAD).
3. Pins ending with "_~" are PWM-capable ones.
4. Changed some GND and voltage pins as Power Input/Output, accordingly.
5. Similarly, I homologated pin type convention for all 3.x and 4.x devices.
