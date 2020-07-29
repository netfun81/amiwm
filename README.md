AMIWM 0.21pl2
-------------
An X11 window manager that looks similar to the Commodore Amiga desktop 
by Marcus Comstedt (marcus@mc.pp.se)
https://www.lysator.liu.se/~marcus/amiwm.html

-------------
Modified some code located in the Patches folder and included my .amiwmrc config file.

Requires Bison, Flex, and X11-dev to compile. Install these from your distribution. 

Download and uncompress the files.

NOTE: If you want to use the Super key for menu hotkeys (rather than Alt) simply copy the
contents of the Patches folder to the amiwm* folder replacing the existing files.

To build, open the amiwm* folder in a terminal and type:

  >chmod +x configure
  >
  >./configure
  >
  >make
  >
  >sudo make install
 

copy the .amiwmrc file to your home folder and edit for your needs.

copy the amiwm.desktop file to /usr/share/xsessions

log off and select amiwm in your display manager.
