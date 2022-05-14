# DockerDoom
Una ves instalado docker en nuestro sistema, Levantamos el número de contedenores que queramos

`for i in {1..2} ; do docker run -d -t ubuntu:14.04; done`

![image](https://user-images.githubusercontent.com/91567318/168450897-4fc6d22c-1677-4819-ad59-f97ade46d4e2.png)

[Descargamos](https://web.archive.org/web/20160310005603/https://gideonred.com/bins/dockerdoomd.tar.gz) y descomprimimos este binario, despues nos dirijimos a la carpeta de "Descargas"

```
cd Descargas

ls -a

gzip -d dockerdoomd.tar.gz

tar -vxf dockerdoomd.tar

```

![image](https://user-images.githubusercontent.com/91567318/168451085-445e6383-da2f-46c9-9f5c-839fa3a1c255.png)

Ejecutamos el servicio y comprobamos el puerto que se habilita

`./dockerdoom`

![image](https://user-images.githubusercontent.com/91567318/168451169-c76783f7-6d9f-4671-a096-f20b94f2f328.png)
 
 y recordamos este numero
 
Ahora iremos a pagina oficial de VNC VIEWER y lo [descargamos](https://www.realvnc.com/en/connect/download/viewer/linux/)

![image](https://user-images.githubusercontent.com/91567318/168451227-35cfe34e-cd4d-4541-8b1a-14dc0ed0ff1f.png)

al descargarlo clicamos el archivos y se no iniciara la tienda de ubuntu para descomprimir mejor el archivo, lo instalamos y ya estaria, despues iniciamos el programa

![image](https://user-images.githubusercontent.com/91567318/168451263-69507565-ea07-4819-af0d-a9643f8c5e81.png)

al iniciarse iremos al apartado "Archivo" y le daremos a "nueva conexion", a hora introducimos "localhost::5900" que es el numero que teniamos que recordar y introducimos un nombre

![image](https://user-images.githubusercontent.com/91567318/168451299-2060a7cb-4057-400f-bd62-7df17cb700a6.png)

despues de darle a "aceptar" nos pedira que introduzcamos una contraseña inventada para iniciar la conexion

![image](https://user-images.githubusercontent.com/91567318/168451314-0f3df5ab-bae0-446d-ab96-3e73fc861c56.png)
 
y ya estaria, ¡A JUGAR!

![image](https://user-images.githubusercontent.com/91567318/168451323-31322a46-0a15-4417-8f0f-3377cb225fbb.png)






