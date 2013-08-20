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


Archivos de configuración para el sistema GPS y A-GPS del Aquaris 5.

Pruebas y testeos.

Esto ha sido desarrollado y probado para el bq Aquaris 5. Si su dispositivo tiene ya un archivo como este, haga una copia de seguridad antes de cambiarlo.
 
Si desea utilizar este archivo, debe ser root, copiar el gps.conf [ con su proveedor de satelite apropiado] en la ruta /system/etc/gps.conf de su dispositivo. 

Si usas una configuración que utiliza capa seguridad o encriptación (SUPL_TLS *) copia el archivo de certificado apropiado (SuplRootCert *) en el mismo directorio.

Si desea crear su propio archivo, recuerde que debe modificar su servidor NTP y el proveedor para su país. Use gps.conf como una base para empezar.

Podeis contribuir o poneros en contacto conmigo.

Saludos Astralix
