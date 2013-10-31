munin-twg870
============

Simple munin scripts for graphing TWG870 cable modem channel properties

Copy or symlink twg870_* to /etc/munin/plugins, and add some configuration 
to /etc/munin/plugin-conf.d/munin-node:

 [twg870_*]
 env.routerip 192.168.0.1
 env.routeruser admin
 env.routerpassword admin

then restart munin-node.

Created for firmware version STBA.01.50 - your cable modem configuration or
firmware may be different, if it doesn't work, please send me the source of 
your /RgConnect.asp and /BasicLan.asp pages.

Greetings go out to UPC Austria for the necessary inspiration.
