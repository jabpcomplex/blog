---
title: "Mostrar asteriscos al introducir una contraseña en la terminal de GNU/Linux"
date: 2024-05-08T23:19:52-06:00
draft: false #true borrador
---

Bienvenido usuario de Linux o sin dejar de lado la filosofia del codigo abierto, deberiamos llamarlo GNU/Linux. En esta nueva oportunidad te voy a enseñar un pequeño comando para que cuando escribas tu contraseña en la terminal se muestren asteriscos de acuerdo al tamaño de tu contraseña que es una propiedad que esta descactivada por defecto en la mayoria de los sistemas GNU/Linux. 

Este pequeño tutorial esta realizado para debian 12 sin embargo funciona para la mayoria de sistemas operativos con el kernel Linux.

Lo primero que debes hacer es abrir una nueva terminal y escribir el siguiente comando:

```shell

    jabp@complex:~$ sudo nano /etc/sudoers

```
&nbsp;

sudo es un comando para uniciar los privilegios de super usuario, nano es el editor de texto y /etc/sudoers es la ruta de un archivo que contiene configuraciones determinadas para los usuarios registrados en el sistema.

&nbsp;
![Imagen no disponible o eliminada](./static/images/terminal_1.png)
&nbsp;

Lo cual abrirà la sigueinte ventana

&nbsp;
![Imagen no disponible o eliminada](./static/images/terminal_2.png)
&nbsp;

Modificamos la linea donde se encuentra el siguiente texto: Defaults env_reset con el siguiente texto , pwfeedback. Como se muestra en la imagen.

&nbsp;
![Imagen no disponible o eliminada](./static/images/terminal_3.png)
&nbsp;

¡Y listo, eso seria todo! Ahora cada que escribas la contraseña de tu super-usuario se mostrarán los asteriscos correspondientes. En lo personal me parece más vistoso, además de que puedo ver cuando me equivoco al escribir mi contraseña en el sentido de que veo si escribí más o menos digitos de lo que en realidad son. Espero te sirva este comando. 


```shell

    jabp@complex:~$ echo CONTINUARÁ

```


