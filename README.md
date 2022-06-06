# ACTIVIDADES DOCKER

<a href="https://youtu.be/ywpJx5aK44Y">![image](https://user-images.githubusercontent.com/91874727/166163516-03bc43e6-d173-4c13-9312-90ebd6d52ff0.png)
</a>

## Actividad 1

+ Descargamos una imagen de un archivo con el comando ***docker pull nombre_imagen:version*** descargará la última versión por defecto (Este comando nos permite descargar la imagen más reciente de ese repositorio)

![Sin título](https://user-images.githubusercontent.com/91874727/166213175-aed7590c-91ba-424a-9ed7-b2dc0501f943.png)

+ Como podemos ver  se descarga la imagen del archivo
![playwithdocker](https://user-images.githubusercontent.com/91874727/166213028-ba791ced-230d-4ea1-91dc-0a912fd3235a.png)

+  Iniciamos dicha imagen con el comando ***docker run*** (tras docker run debemos especificar la imagen que vamos a utilizar para crear el contenedor, además de algunos parámetros más.):

![3](https://user-images.githubusercontent.com/91874727/166213512-cbc11374-95f4-4e4e-8fa5-f587dd4a93db.png)
+ **-i:** es la abreviatura de -interactive y lo utilizamos porque vamos a ejecutar un proceso con el que vamos a interactuar, como es una terminal.

+ **Ubuntu** es el nombre de la imagen (en este caso estamos creando un contenedor con ubuntu instalado.

+ **-t:** es la abreviatura de -tty y sirve para habilitar un terminal tty para el contenedor.

+ Por otro lado al crear el contenedor entramos como (admin) root. Es el usuario con más privilegios.

## Actividad 2

+ Con el comando docker run iniciamos el contenedor con ubuntu para poder trabajar con dicho sistema operativo.
+ Además añadimos ***ls /*** (comando de linux para listar en este caso el directorio raíz).

![4](https://user-images.githubusercontent.com/91874727/166213888-347f6ecc-2b63-4550-855e-d476c7237b38.png)
+ Como resultado nos sale todo el contenido que tenemos en nuestro contenedor, es decir se nos muestran los directorios (carpetas) que tenemos donde hemos ejecutado el comando en este caso el directorio raíz

+ **ls** es el comando

+ / es donde se ejecutará (en la raíz) además la ruta puede ser relativa o absoluta (relativa se pone donde queremos ir desde donde estamos ahora y absoluta desde la raíz hasta nuestro destino).

## Actividad 4

+ Iniciamos debian en docker con el comando ***docker run -it -w***. Cosa que nos permite descargar el archivo (si no lo tenemos) poder ejecutarlo (run) y poder interactuar con él (-it)
+ Además utilizamos el comando ls para listar

![5](https://user-images.githubusercontent.com/91874727/166214209-50de3b93-2eaa-4588-a1a2-6f6be1c59e2d.png)
+ Como hemos visto en la anterior imagen nos muestra todo lo visto anteriormente en un solo comando ademas del comando w
++ Mostrar el contenido de una carpeta establecida con el parámetro -w
+ Para saber que contenedores tenemos activos en docker usamos el comando ***docker ps***

![6](https://user-images.githubusercontent.com/91874727/166214496-a6259dfe-b500-4d77-87d1-645e85c5401f.png)

+ Para saber que contenedores tenemos activos ***docker ps***

![image](https://user-images.githubusercontent.com/91874727/166214717-5e1bf06b-6e5a-439a-8d57-9c9b09bff771.png)

+ Para saber los contenedores que ya están en ejcución o parados usamos ***docker ps -a***

+ El parametro ***-a*** nos dice que el comando (en este caso **docker ps**) también tomará en cuenta a los contenedores parados (que no estén siendo utilizados). 
