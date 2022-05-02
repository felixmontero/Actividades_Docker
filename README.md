# ACTIVIDADES DOCKER

## Actividad 1

+ Descargamos una imagen de un archivo con el comando ***docker pull***

![Sin título](https://user-images.githubusercontent.com/91874727/166213175-aed7590c-91ba-424a-9ed7-b2dc0501f943.png)

![playwithdocker](https://user-images.githubusercontent.com/91874727/166213028-ba791ced-230d-4ea1-91dc-0a912fd3235a.png)

+  Iniciamos dicha imagen con el comando ***docker run*** (si no se tiene la imagen se descargará previamente):

![3](https://user-images.githubusercontent.com/91874727/166213512-cbc11374-95f4-4e4e-8fa5-f587dd4a93db.png)

## Actividad 2

+ Con el comando docker run iniciamos el contenedor con ubuntu para poder trabajar con dicho sistema operativo.
+ Además añadimos ***ls /*** (comando de linux para listar en este caso el directorio raíz).

![4](https://user-images.githubusercontent.com/91874727/166213888-347f6ecc-2b63-4550-855e-d476c7237b38.png)

## Actividad 4

+ Iniciamos debian en docker con el comando ***docker run -it -w***. Cosa que nos permite descargar el archivo (si no lo tenemos) poder ejecutarlo (run) y poder interactuar con el (-it)
+ Además utilizamos el comando ls para listar

![5](https://user-images.githubusercontent.com/91874727/166214209-50de3b93-2eaa-4588-a1a2-6f6be1c59e2d.png)

+ Para saber que contenedores tenemos activos en docker usamos el comando ***docker ps***

![6](https://user-images.githubusercontent.com/91874727/166214496-a6259dfe-b500-4d77-87d1-645e85c5401f.png)

+ Para saber que contenedores tenemos activos y parados en docker usamos el comando ***docker ps -a***
![image](https://user-images.githubusercontent.com/91874727/166214717-5e1bf06b-6e5a-439a-8d57-9c9b09bff771.png)
