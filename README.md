Ino-Delta-Marlin
================

A delta version of Marlin that can be compiled and written on an Arduino directly through the command line.  Created specifically for use with Ino on a Raspberrypi

In order for Ino to successfully compile and write some file structure changes were required:

-renamed Marlin directory to src
-renamed Marlin.ino to sketch.ino
-commented out FORCE_INLINE function

To run the identical firmware through Arduino software interface, revert the above changes. 
