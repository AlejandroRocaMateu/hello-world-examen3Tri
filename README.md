# hello-world-examen3Tri

## APARTADO A

En este apartado vamos hacer una serie de ejercicio para descargar y crear contenedores e imagenes.


## EJERCICIO 1
En este ejercicio lo primero que vamos a hacer es logearnos para tener acceso dentro de nuestro docker hub
![Login](https://github.com/AlejandroRocaMateu/hello-world-examen3Tri/blob/6b2842d2a1131b4532e5ae16381809a862abb6b3/CapturaLogin.PNG)

Ahora comenzamos con la descarga de la imagen Ubuntu y tenerla instalada
![Descarga](https://github.com/AlejandroRocaMateu/hello-world-examen3Tri/blob/168f9ed28e9e6e25b05878baab70dfb4a8b123da/CapturaUbuntu.PNG)

Despues de tenerla instalada, lo que haremos sera crear un contenedor de Ubuntu que nos hemos descargado y tener acceso dentro de el.
![Crear Contenedor](https://github.com/AlejandroRocaMateu/hello-world-examen3Tri/blob/68cbf48ea13d03c7d05956aa49811dacfbf5003e/CapturaContenedor.PNG)

Cuando hayamos accedido a el, estaremos dentro como usuario root preterminado.



## EJERCICIO2
En este ejercicio, crearemos un Contenedor CENTos y veremos su listado de su carpeta:

Lo primero sera crear descargar su imagen
![IMAGEN](https://github.com/AlejandroRocaMateu/hello-world-examen3Tri/blob/a1d20dede23f1f6f75553d55b624e4333770e9f6/CapturaCentos.PNG)

Cuanbdo ya tengamos su imagen, y con el comando para crear el contenedor tambien listaremos su carpeta con ls
![Crear su contenedor](https://github.com/AlejandroRocaMateu/hello-world-examen3Tri/blob/95d856a7b23bdf2b9ba795984d2a621f2579f8ac/CapturaCentosls.PNG)

Nos mostrara el listado de la carpeta

## EJERCICIO3
En este ejercicio crearemos un contenedor de httpd que es el servidor de Apache
![Crear Contenedor](https://github.com/AlejandroRocaMateu/hello-world-examen3Tri/blob/9d4df8d0d23dffe605436d8e3b6497a51b694f13/Capturahttpd.PNG)


## EJERCICIO4
En este aparatado creamos un contenedor de debian y mostramos su contenido de una carpeta suya con el parametro -w
![Mostrar su contenido](https://github.com/AlejandroRocaMateu/hello-world-examen3Tri/blob/1275ec21bc26c92151869704e00d701538804381/CapturaDebian.PNG)

Esto nos mostrara la carpeta ls con todo sus archivos

## APARTADO B

En este apartado crearemos un archivo DockerFile y lo editaremos con el proyecto Tomcat y despues lo subiremos a nuestro perfil de DockerHub

## EJERCICIO TOMCAT

En el primer paso para hacer este ejercico, crearemos un directorio para guardar nuestro archivo.
![](https://github.com/AlejandroRocaMateu/hello-world-examen3Tri/blob/8a363148188f643becfe3ba1b20120c122ee5a09/CapturaMk.PNG)

Paso siguiente sera crear el archivo Dockerfile dentro de nuestro repositorio
![](https://github.com/AlejandroRocaMateu/hello-world-examen3Tri/blob/0e135e37eec5b7e3ee3d4146bcfff473a2711074/Capturatouch.PNG)


Cuando tengamos el archivo, lo editaremos con el editor vi y copiaremos las intrucciones que nos piden y saldremos.
![](https://github.com/AlejandroRocaMateu/hello-world-examen3Tri/blob/14e8e72668367b6c3c27df2e43a8588f98c851df/Capturavi.PNG)

Ahora cuando hayamos salido del editor, lo que haremos sera poner un tag, para saber el nombre del archivo y del contenedor
![]()

