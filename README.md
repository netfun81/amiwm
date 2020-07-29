AMIWM 0.21pl2

This is an X11 window manager that is a clone of the Commodore Amiga desktop 
by Marcus Comstedt (marcus@mc.pp.se)

I will be adding some modifications for my own use and including my config file.

  07-28-2020
  * Changed Menu keys from ALT + <key> to Super + <key>


Requires Bison, Flex, and X11-dev to compile. Install these from your distribution. 

after downloading enter program directory and run these commands in terminal:
  ./configure
  make
  sudo make install

copy the .amiwmrc file to your home folder and edit for your needs.

edit .xinitrc or create a /usr/share/xsessions/amiwm.desktop file 
if using a desktop manager to start amiwm.
