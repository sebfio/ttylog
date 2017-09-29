ttylog
======

This program writes everything comes from a serial device from /dev/tty* onto
stdout. You can specify the device and the baud rate of the device.  It was
originally written and packaged for Debian by Tibor Koleszar and is now
maintained by Robert James Clay.

Information about how to build ttylog can be found in the INSTALL file.

Copyright is GPL-2+, details of which can be found in the COPYRIGHT and LICENSE
files.


Usage:
------

ttylog [-b|--baud] [-d|--device] [-f|--flush] [-t|--timeout] > /path/to/logfile

If you are not using the timeout option, you can stop it running by pressing a
ctrl-c when it's going to the screen or doing "kill -HUP nnnn" if running it in
the background.

Web sites
-----------

ttylog website:  http://ttylog.sourceforge.net/
ttylog project:  https://sourceforge.net/projects/ttylog/

Code
----

ttylog Git repository:  http://sourceforge.net/p/ttylog/code/
ttylog at GitHub:       https://github.com/sebfio/ttylog 

Support
-------

https://sourceforge.net/p/ttylog/support-requests/
https://sourceforge.net/p/ttylog/bugs/
https://sourceforge.net/p/ttylog/patches/
https://sourceforge.net/p/ttylog/feature-requests/
https://github.com/rocasa/ttylog/issues


Sebastian Fiorini Changes
-------------------------
Added a binary `ttylog` device that is compiled for Raspberry pi's for
my convenience of not having to recompile the source each time it's cloned.

Changes were made to this software to support UART speeds of 3.5 Mhz
The software is now updated to version 0.30.0 to reflect these changes.
- Sebastian Fiorini <sebf465@gmail.com>

