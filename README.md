AMIWM 0.21pl2

An X11 window manager that is a clone of the Commodore Amiga desktop 
by Marcus Comstedt (marcus@mc.pp.se)
---------------------

Modified some code for my own use and includes my config file.

Requires Bison, Flex, and X11-dev to compile. Install these from your distribution. 

after downloading and uncompressing, open the amiwm* folder in a terminal and type:

  >chmod +x configure

  >./configure
  
  >make
  
  >sudo make install
 

copy the .amiwmrc file to your home folder and edit for your needs.

copy the amiwm.desktop file to /usr/share/xsessions

log off and select amiwm in your display manager.
