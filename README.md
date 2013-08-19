Android_gps
===========

Configuration files for Androids GPS and A-GPS system

For testing purpose only. Developed and tested on bq Aquarius 5 device.
If your device already has a file like this, make a backup before tampering.

If you like to use this file, you must be root on your device.
Copy the appropriate gps.conf[.provider] as gps.conf to the devices /system/etc/gps.conf file.
If you use a config that uses transport layer security (SUPL_TLS*) copy the appropriate certificate file (SuplRootCert*) to the same directory.

If you like to create your own file, remember to modify your NTP server and supplicant provider for your country. Use gps.conf as a base to start off. 

Feel free to contribute or to contact me.

Cheers
 Astralix
