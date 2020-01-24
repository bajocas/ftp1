## Instalar servidor FTP

Como primer paso de introducción al servidor FTP, vamos a instalarlo en neustra máquina virtual de Ubuntu 18.04 y vamos a ver unas pocas opciones con las que cuenta este servidor, además para hacerlo de manera más sencilla, vamos a hacerlo con la ayuda de webmin, que nos ayudará a hacer todos estos pasos de manera más sencilla.
En este se explica de manera muy sencilla como instalar webmin: [Webmin](https://clouding.io/kb/como-instalar-webmin-en-ubuntu-18-04/)

1. En el panel lateral de webmin, abrimos el apartado *Un-used Modules*

![imagen](/imagenes/Captura1.PNG)

2. Buscamos *ProFTPD* y aparecerá la siguiente página. Le daremos a *Install Now*.

![imagen2](/imagenes/Captura2.PNG)

3. Nos lleva a una página dónde nos muestra los distintos paquetes que va a instalar. Tendremos que volver a pulsar *Install Now*

![imagen3](/imagenes/Captura3.PNG)

4. Cuando finalice la instalación nos mostrará el panel de configuración del servidor

![imagen4](/imagenes/Captura4.PNG)

5. Aquí indicaremos la dirección IP, el puerto y el nombre para crear un nuevo sitio ftp y le daremos a *Create*

![imagen5](/imagenes/Captura5.png)

Tendrás que introducir la dirección ip de tu equipo y el puerto que desees, nómbralo servidor 1.

![imagen6](/imagenes/Captura6.PNG)

Ahora crea otro sitio ftp con la misma dirección ip pero con un puerto distinto y nómbralo ftp2

![imagen7](/imagenes/Captura7.PNG)

[Volver a página principal](README.md)
