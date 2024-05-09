---
title: "Mostrar asteriscos al introducir una contraseña en la terminal de GNU/Linux?"
date: 2024-05-12T00:32:07-05:00
draft: false #true borrador
---

Bienvenido usuario de Linux o sin dejar de lado la filosofia del codigo abierto, deberiamos llamarlo GNU/Linux. En esta nueva oportunidad te voy a enseñar un pequeño comando para que cuando escribas tu contraseña en la terminal se muestren asteriscos de acuerdo al tamaño de tu contraseña que es una propiedad que esta descactivada por defecto en la mayoria de los sistemas GNU/Linux. 

Este pequeño tutorial esta realizado para debian 12 sin embargo funciona para la mayoria de sistemas operativos con el kernel Linux.

Lo primero que debes hacer es abrir una nueva terminal y escribir el siguiente comando:

```shell

    jabp@complex:~$ sudo nano /etc/sudoers

```

sudo es un comando para uniciar los privilegios de super usuario, nano es el editos de texto y /etc/sudoers es la ruta de un archivo que contiene configuraciones determinadas para los usuarios registrados en el sistema.

