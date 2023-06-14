# LEAF
LEAF firewall files collection

The " RPI Zero " directory contains the firmware for the wifi and a preconfigured configdb.lrp file.

the configdb.lrp will add:

 in /etc/inittab : ttyAMA0::respawn:/sbin/getty -L ttyAMA0 115200 vt100
 
 in /etc/securetty : ttyAMA0
