```
pymelab@workstation:~$ sudo apt-get install git-core autoconf automake libtool g++ python-dev swig libpcap0.8-dev 
[sudo] password for pymelab: 
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias       
Leyendo la información de estado... Hecho
autoconf ya está en su versión más reciente.
automake ya está en su versión más reciente.
g++ ya está en su versión más reciente.
libtool ya está en su versión más reciente.
python-dev ya está en su versión más reciente.
swig ya está en su versión más reciente.
Los paquetes indicados a continuación se instalaron de forma automática y ya no son necesarios.
  libmbim-glib0 libntdb1 libqmi-glib0 python-ntdb usb-modeswitch
  usb-modeswitch-data
Use 'apt-get autoremove' to remove them.
Se instalarán los siguientes paquetes NUEVOS:
  git-core libpcap0.8-dev
0 actualizados, 2 se instalarán, 0 para eliminar y 102 no actualizados.
Necesito descargar 206 kB de archivos.
Se utilizarán 703 kB de espacio de disco adicional después de esta operación.
¿Desea continuar? [S/n] S
Des:1 http://mx.archive.ubuntu.com/ubuntu/ trusty-updates/main git-core all 1:1.9.1-1ubuntu0.3 [1 464 B]
Des:2 http://mx.archive.ubuntu.com/ubuntu/ trusty/main libpcap0.8-dev amd64 1.5.3-2 [205 kB]
Descargados 206 kB en 1seg. (149 kB/s)   
Seleccionando el paquete git-core previamente no seleccionado.
(Leyendo la base de datos ... 282011 ficheros o directorios instalados actualmente.)
Preparando para desempaquetar .../git-core_1%3a1.9.1-1ubuntu0.3_all.deb ...
Desempaquetando git-core (1:1.9.1-1ubuntu0.3) ...
Seleccionando el paquete libpcap0.8-dev previamente no seleccionado.
Preparando para desempaquetar .../libpcap0.8-dev_1.5.3-2_amd64.deb ...
Desempaquetando libpcap0.8-dev (1.5.3-2) ...
Procesando disparadores para man-db (2.6.7.1-1ubuntu1) ...
Configurando git-core (1:1.9.1-1ubuntu0.3) ...
Configurando libpcap0.8-dev (1.5.3-2) ...
pymelab@workstation:~$ 
```

```
pymelab@workstation:~$ git clone git://git.osmocom.org/libosmocore.git
Clonar en «libosmocore»...
remote: Counting objects: 12480, done.
remote: Compressing objects: 100% (7281/7281), done.
remote: Total 12480 (delta 8379), reused 7333 (delta 4713)
Receiving objects: 100% (12480/12480), 2.08 MiB | 204.00 KiB/s, done.
Resolving deltas: 100% (8379/8379), done.
Comprobando la conectividad… hecho.
pymelab@workstation:~$ 
```