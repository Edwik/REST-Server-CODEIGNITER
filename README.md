# REST-Server-CODEIGNITER
Esta es la configuración para utilizar el framework de php Codeigniter como servidor para nuestra App 
## Getting Started
Para empezar debemos descargar o clonar este repositorio en nuestra computadora, preferiblemente una carpeta que hayamos especificado para este fin.
### Lista de pasos para la correcta instalación
* El Archivo [reset.php](http://) debemos moverlo donde tenemos instalado nuestro framework y buscar la ruta *Aplication/config* y dentro de ella debemos colocarlo.
* En este mismo orden ahora los achivos [Format.php](http://) y [REST_Controller.php](http://) debemos moverlos igual a la ruta *Aplication/libraries*.
* Ahora por ultimo solo resta mover la carpeta [English](http://) y reemplazarla por la otra que tenemos en la ruta *aplication/language*.
### Archivo Format.php
Este archivo nos ayudara a enviar nuestra respuesta en el formato de texto que deseemos, Ej: XML,JSON,CSV...
### Archivo REST_Controller.php
Este archivo sera nuestro ayudante para convertir nuestros controladores normales en servicios rest.
#### Versiones Soportadas
* La version de codeigniter soportada es la Version 3.1.6 que puedes descargar en su pagina oficial.
* la version de que se probada es la Version 7
