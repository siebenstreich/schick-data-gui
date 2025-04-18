
Schick data GUI
===============

Read, analyze/parse and display/browse data from files in 1992's computer game
**Die Schicksalsklinge** (*Realms of Arkania: Blade of Destiny*).

Currently, a lot of the contents of `SCHICK.DAT` and `SCHICKM.EXE` are supported.
The data segment in `SCHICKM.EXE` is parsed using the file `symbols.h` from the
Bright-Eyes project.

How to run
==========

This software is made for Linux systems, but it should also run on other
operating systems, as long as Python 3.5 or newer (with `tkinter`, `numpy` and `pillow`) is
installed. On Debian 12, for example, it suffices to install the packages `python3`,
`python3-tk`, `python3-numpy`, `python3-pillow` and `python3-pil.imagetk`.

It requires the files `SCHICK.DAT`, `SCHICKM.EXE` as well as `symbols.h` from the
Bright-Eyes project. Place these files in the same directory as schick-gui.py
before you start it (however, on Linux, a soft link is sufficient).

On Linux systems, `schick-data-gui.py` can be run from the command line. For other
operating systems this might or might not work.

Screenshots
===========

![screenshot4](https://raw.githubusercontent.com/tuxor1337/schick-data-gui/master/screenshot4.png "Display automap in SCHICKM.DAT")

![screenshot3](https://raw.githubusercontent.com/tuxor1337/schick-data-gui/master/screenshot3.png "Display a dialog in SCHICKM.DAT")

![screenshot1](https://raw.githubusercontent.com/tuxor1337/schick-data-gui/master/screenshot.png "Display FONT6 in SCHICKM.DAT")

![screenshot2](https://raw.githubusercontent.com/tuxor1337/schick-data-gui/master/screenshot2.png "Display a variable in SCHICK.EXE")

To do
=====

* Use the correct palettes for graphics that don't come with palette.
* Parse list of direction signs.
* Draw routes on the map.
* Display fight scenarios.
* Support for VOC and XMI file playback.
* Parse `FIGHT.LST`, `BSKILLS.DAT`, NPC files, ...

Links
=====

* Bright-Eyes project: https://www.github.com/Henne/Bright-Eyes
* Documentation of SCHICK.DAT contents: http://www.bright-eyes.obiwahn.de/index.php/SCHICK.DAT

