# Atlas - a map for FlightGear

This repository is based on Atlas v.0.3.0 downloaded from atlas.sourceforge.net
It is an attempt to update the code to get it compiling with current versions of
SimGear, FlightGear, updated library APIs (e.g. PNG lib) and modern C++ conventions.
Some progress has been made, but the project still fails to compile cleanly.
Anyone is welcome to help.


## Original README text follows

Welcome to the Atlas project.

The primary web page for this project is: <http://atlas.sourceforge.net>

For basic installation instructions see the "INSTALL" file.

To use the Atlas program, you must have some of the scenery from FlightGear
(a freeware flight simulator) installed. These files can be found at the
FlightGear homepage: <http://www.flightgear.org>

You also need to copy src/AtlasPalette from this package into your FlightGear
base directory (often /usr/local/lib/FlightGear).  If your FlightGear base
directory is somewhere else, you can either set the FG_ROOT environment
variable, or use the --fgroot=path command-line option to specify the
FlightGear base directory.

To build under Unix, follow these steps:

 ./autogen.sh
 ./configure
 make
 make install

This project is GPL'd.  For complete details on our licensing please
see the "COPYING" file.
