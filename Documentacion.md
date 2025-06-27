1.- se crea una aplicación flask debe mostrar la ip desde donde está conectado y debe correr en el puerto 8000
1.1.- Se Instala Flask

![IMG](Imagenes/Imagen_1.png)


1.2.- Se llega hasta la carpeta deseada para poder editar el sample_app.py

![IMG](Imagenes/Imagen_2.png)

1.3.- script que se pondrá en el nano

![IMG](Imagenes/Imagen_3.png)

1.4.- resultado del script 

![IMG](Imagenes/Imagen_4.png)
![IMG](Imagenes/Imagen_5.png)
![IMG](Imagenes/Imagen_6.png)

---------------------------------------------------------------


2.- levantamos una aplicación Python, y usando plantilla html y css, que levante un sitio web que verifique la ip de conexión y que corra en el puerto 8181
2.1.- cambiamos algunas cosas del codigo anterior

![IMG](Imagenes/Imagen_7.png)

2.2.- el resultado que deberíamos tener es

![IMG](Imagenes/Imagen_8.png)
![IMG](Imagenes/Imagen_9.png)
![IMG](Imagenes/Imagen_10.png)

---------------------------------------------------------------

3.- se creará un script en bash que cree y corra un contenedor Docker a partir de un archivo Dockerfile, que levante un sitio web y que exponga el puerto 8888. Compruebe conexión y que el contenedor está corriendo

3.1.- en sample_app.sh se crea este script

![IMG](Imagenes/Imagen_11.png)

3.2.- luego se verifica la version de Docker

![IMG](Imagenes/Imagen_12.png)

3.3.- se agregan las librerías antes vistas en la config de sample

![IMG](Imagenes/Imagen_13.png)

3.4.-  se modifica el nano Dockerfile

![IMG](Imagenes/Imagen_14.png)

3.5.- se mueve el dockfile a la carpeta de tempdir y se revisa contenido

![IMG](Imagenes/Imagen_15.png)

3.6.- se instala el contenido del Docker usando Docker build -t rcristian .

![IMG](Imagenes/Imagen_16.png)
![IMG](Imagenes/Imagen_17.png)

3.7.- se comprueba lo instalado

![IMG](Imagenes/Imagen_18.png)

3.8.- se verifica los estatus de la config

![IMG](Imagenes/Imagen_19.png)
![IMG](Imagenes/Imagen_20.png)

3.9.- se verifica que funciono la conexión

![IMG](Imagenes/Imagen_21.png)

