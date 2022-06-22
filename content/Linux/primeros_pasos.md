---
title: "Primeros pasos para cambiarte a Linux"
date: 2022-06-12T00:32:07-05:00
draft: false #true borrador
---

Si estas harto de qué se trabe o ralentice tu computadora con windows y no te alcanza para comprar una imac o simplemente quieres dejar atrás windows. Este post tiene como objetivo ayudarte a cambiar a linux. 

Linux es un sistema operativo de código abierto, aunque nadie lo utiliza como tal, sino que recurren a las distribuciones (distros) ya que, con ellas, se vuelve mucho sencillo de utilizar y cada distro (ubuntu, kubuntu, debian, azure, etc) tiene su toque personal.

Vamos a comenzar por aprender que significan algunos términos que se utilizan en el mundo de Linux. Desde mi experiencia, teniendo claro que significan estos términos vamos a comprender mejor nuestra máquina (Hardware) y la distribución que hemos instalado (software).

## Términos importantes que debemos conocer


Se conoce como **sistema informático** al conjunto de ordenadores personales (uno o varios), junto con la persona que lo maneja, los programas que contiene y los periféricos que los envuelven (impresora, teclado, altavoces, mouse, cables, etc) 

El **hardware**,​ se refiere a las partes físicas, tangibles, de un sistema informático, sus componentes eléctricos, electrónicos, electromecánicos

Se conoce como **software** o​ soporte lógico al conjunto de los componentes lógicos necesarios que hace posible la realización de tareas específicas.

Un **sistema operativo** es el conjunto de programas de un sistema informático que gestiona los recursos de hardware y provee servicios a los programas de aplicación de software. 

&nbsp;

![Imagen no disponible o eliminada](https://i.pinimg.com/originals/42/e3/cb/42e3cba3e4f6765b15ddc31c4394a3b7.png)



## ¿Qué es el Kernel y para qué sirve?

El Kernel Linux es el núcleo del sistema operativo. Esta es la parte de software más importante de cualquier sistema operativo. Windows tiene su propio núcleo privado, Apple tiene el suyo (basado en Unix, por cierto), y Linux es el Kernel que utilizan todas las distribuciones. Y su principal función es encargarse de controlar el hardware del ordenador. Para conocer más a detalle sobre el kernel de linux visita el siguiente enlace:

https://www.softzone.es/programas/linux/kernel-nucleo-linux/

En el enlace anterior puedes conocer

- Que versiones existen

- Que versión de linux elegir para tu máquina 

- Cómo saber la versión de nuestro Kernel

- Y como actualizar el Kernel.



## Personaliza Linux con Conky

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
