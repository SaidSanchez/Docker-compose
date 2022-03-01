# Proyecto del Segundo Parcial

## Nombre del proyecto

Tu primer sitio web.

## Descripción de la tarea: 

Utilizando los conocimientos adquiridos en la unidad, vamos a crear nuestro primer sitio web para esto toma en cuenta el siguiente problema:

Se tiene una empresa llamada “automax” de renta de autos que quiere promocionar sus unidades por internet, para esto la empresa tiene al rededor de 25 autos de los cuales cuenta con modelo, año, marca y precio por día de renta. 

1. Crear un servidor web que se ejecute sobre el puerto 8888 . (20 puntos)

2. Crear un sitio web que se hospede en el servidor que contenga lo siguiente:

 a) Landing page que presente a la empresa y los vehículos que tiene disponibles. (10 puntos)

 b) Pagina web de contacto con los datos para ubicar a la empresa. (10 puntos)

 c) Página web “acerca de ” con los datos de la empresa (ej. Misión, visión, etc.)  (10 puntos)

 d) Página web de detalle de los primeros 3 vehículos.  (15 puntos)

 e) Formulario de contacto que almacene en el servidor en un archivo de texto la información. (15 puntos)
3. Al terminar convierta el servidor y el sitio web en una imagen de Docker publicada en Docker hub. (20 puntos)

### Prerequisitos

Para ejecutar los programas en la terminal de linux para su facil ejecucion se debe de contar con alguna version de Node.js.

### Installing

Para actualizar a las ultimas versiones de Node.js, se pueden utilizar los siguientes comandos:


```
sudo apt-get update
```
```
sudo apt-get upgade
```
Para instalar Node.js

```
sudo apt-get install nodejs
```

1.-Necesitamos instalar Docker para correr un contenedor con la imagen que contiene nuestro sitio web. Para descargar e instalar Docker se deben seguir los siguientes pasos:
```
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
```
2.-Anadir la llave GPG

```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
```

3.-Instalar el motor de docker con el comando
```
sudo apt-get install docker-ce docker-ce-cli containerd.io
```



## Para ejecutar el archivo

Escribimos dentro de la carpeta donde se encuentra el archivo (todo esto en la consola):

```
node +NombreDelArchivo.js
```
Una vez que el servidor se este ejecutando, se puede verificar que el sitio web esta activo al ir a la siguiente direccion dentro del navegador:

```
localhost:8888/
```
### Elaborado con:

* [Atom]
* [Node.js (para ejecutr el programa)]
* [Nano]}
* https://hub.docker.com/r/saidsanchez/sitioweb (link para la imagen de docker)

## Authors:

* **Alan Said Sánchez Sausameda** 
* **Armando Chavéz Pérez**

## Licencia 

Licencia de libre uso 
