---
title: "Personaliza Linux con Conky"
date: 2022-06-12T00:32:07-05:00
draft: false #true borrador
---

<style>body {text-align: justify}</style>

Conky es monitor del sistema disponible en GNU/Linux. Conky es un software que muestra información relevante sobre nuestra computadora, como por ejemplo la temperatura de nuestros procesadores, la intensidad de la señal Wi-Fi, el uso de la RAM, estado del CPU, memoria disponible,  bandejas de correo, y muchas otras características más.


&nbsp;

![Imagen no disponible o eliminada](https://i0.wp.com/nksistemas.com/wp-content/uploads/2015/11/conky1.jpg?w=700&ssl=1)



&nbsp;
 
Contrario a los monitores del sistema que usan widgets que consumen mucha memoria RAM, Conky consume relativamente menos recursos del sistema por la naturaleza de su creación, basado en el [sistema de ventanas X](https://es.wikipedia.org/wiki/Sistema_de_ventanas_X).

Conky ha sido nombrado como "uno de los mejores programas mejor mantenidos, y definitivamente uno de los más útiles programas en el mundo del código abierto" por Linux Magazine.

# Instalación

Para instalar Conky, necesita abrir una terminal y escribir el siguiente comando:


```shell

    sudo apt-get install conky-all 
      
```  

Para iniciar conky solo escribiremos la palabra `conky` en la consola y se abrirá algo como esto


&nbsp;

![Imagen no disponible o eliminada](https://www.fuukemn.biz/photo/lubuntu_37.png)



&nbsp;



Como habrán podido notar cuando lanzamos conky se ve bastante rústico, para personalizarlo debemos editar el archivo **.conkyrc** que se encuentra en la ruta */home/usuario*.



Para disfrutar de todos los beneficios de conky es necesario instalar los paquetes


* **curl** que nos facilita la transferencia de ficheros utilizando los protocolos HTTP,HTTPS y FTP, entre otros.

* **lm-sensors** da información sobre la temperatura y el estado de la CPU, tanto ventiladores o el voltaje.

* **hddtemp** nos mostrará la temperatura de los discos.


```shell

    sudo apt-get install curl lm-sensors hddtemp
      
```  



```shell

    CONTINUARÁ
      
```  
