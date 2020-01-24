# Instalación del servidor y discriminación de sitios FTP

Como primer paso de introducción a los servidores FTP, vamos a instalar uno en neustra máquina virtual de Ubuntu 18.04. Para hacerlo de una manera más sencilla, lo instalaremos con la ayuda de *webmin*.
[Aquí](https://clouding.io/kb/como-instalar-webmin-en-ubuntu-18-04/) se explica de manera muy sencilla como instalar webmin.

Una vez tengamos instalado *webmin*, instalaremos el servidor FTP

## Instalación

1. En el panel lateral de webmin, abrimos el apartado *Un-used Modules*

![imagen](/imagenes/Captura1.PNG)

2. Buscamos *ProFTPD* y aparecerá la siguiente página. Le daremos a *Install Now*.

![imagen2](/imagenes/Captura2.PNG)

3. Nos lleva a una página dónde nos muestra los distintos paquetes que va a instalar. Tendremos que volver a pulsar *Install Now*

![imagen3](/imagenes/Captura3.PNG)

4. Cuando finalice la instalación nos mostrará el panel de configuración del servidor

![imagen4](/imagenes/Captura4.PNG)

## Discriminación de sitios

En el siguiente apartado del panel de configuración indicaremos la dirección IP, el puerto y el nombre para crear un nuevo sitio ftp y le daremos a *Create*

![imagen5](/imagenes/Captura5.png)

Tendrás que introducir la dirección ip de tu equipo y el puerto que desees, nómbralo servidor 1.

![imagen6](/imagenes/Captura6.PNG)

Ahora crea otro sitio ftp con la misma dirección ip pero con un puerto distinto y nómbralo ftp2

![imagen7](/imagenes/Captura7.PNG)

[Volver a página principal](README.md)
