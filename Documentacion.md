# Documentación del Proyecto

## 1. Creación de una aplicación Flask para mostrar la IP de conexión (Puerto 8000)

1.1. El primer paso consistió en instalar el framework Flask, el cual es fundamental para el desarrollo de aplicaciones web ligeras en Python. Esta herramienta permite crear servidores web de manera sencilla y rápida.

![IMG](Imagenes/Imagen_1.png)

1.2. Una vez instalado Flask, se accedió a la carpeta de trabajo destinada al proyecto para proceder con la edición del archivo principal, denominado `sample_app.py`.

![IMG](Imagenes/Imagen_2.png)

1.3. En este archivo se desarrolló el script principal utilizando el editor nano. El código implementa una ruta que, al ser accedida, muestra la dirección IP desde la cual el usuario está conectado.

![IMG](Imagenes/Imagen_3.png)

1.4. Finalmente, se ejecutó el script y se verificó su funcionamiento accediendo a la aplicación desde un navegador. Se comprobó que la IP de conexión se muestra correctamente en pantalla, cumpliendo con el objetivo de esta primera etapa.

![IMG](Imagenes/Imagen_4.png)
![IMG](Imagenes/Imagen_5.png)
![IMG](Imagenes/Imagen_6.png)

---

## 2. Implementación de una interfaz web con HTML y CSS (Puerto 8181)

2.1. Para mejorar la experiencia del usuario, se modificó el código anterior incorporando una plantilla HTML y estilos CSS personalizados. Esto permitió presentar la dirección IP de una forma más visual y atractiva.

![IMG](Imagenes/Imagen_7.png)

2.2. Tras realizar las modificaciones, se ejecutó la nueva versión de la aplicación, esta vez configurada para funcionar en el puerto 8181. Se verificó que la interfaz web muestra correctamente la IP de conexión, ahora con un diseño más amigable y profesional.

![IMG](Imagenes/Imagen_8.png)
![IMG](Imagenes/Imagen_9.png)
![IMG](Imagenes/Imagen_10.png)

---

## 3. Despliegue en Docker mediante un script Bash (Puerto 8888)

3.1. En la última etapa, se creó el script `sample_app.sh`, encargado de automatizar el proceso de construcción y ejecución del contenedor Docker que alojará la aplicación web.

![IMG](Imagenes/Imagen_11.png)

3.2. Antes de continuar, se verificó la versión instalada de Docker en el sistema para asegurar la compatibilidad y correcto funcionamiento de los comandos utilizados en el script.

![IMG](Imagenes/Imagen_12.png)

3.3. Se añadieron todas las librerías y dependencias necesarias en la configuración del proyecto, garantizando que la aplicación pueda ejecutarse correctamente dentro del contenedor.

![IMG](Imagenes/Imagen_13.png)

3.4. Posteriormente, se editó el archivo `Dockerfile`, donde se definieron las instrucciones para construir la imagen del contenedor, incluyendo la instalación de dependencias y la configuración del entorno de ejecución.

![IMG](Imagenes/Imagen_14.png)

3.5. El archivo `Dockerfile` fue movido a la carpeta `tempdir` y se revisó su contenido para asegurar que todas las rutas y configuraciones fueran correctas.

![IMG](Imagenes/Imagen_15.png)

3.6. Se procedió a construir la imagen de Docker utilizando el comando `docker build -t rcristian .`, lo que generó una imagen personalizada lista para ser ejecutada.

![IMG](Imagenes/Imagen_16.png)
![IMG](Imagenes/Imagen_17.png)

3.7. Una vez finalizada la construcción, se comprobó que la imagen se hubiera creado correctamente, verificando su presencia en la lista de imágenes disponibles de Docker.

![IMG](Imagenes/Imagen_18.png)

3.8. Se revisó el estado de la configuración y de los contenedores en ejecución para asegurar que todo estuviera funcionando según lo esperado.

![IMG](Imagenes/Imagen_19.png)
![IMG](Imagenes/Imagen_20.png)

3.9. Finalmente, se accedió al sitio web expuesto en el puerto 8888 desde el contenedor Docker, comprobando que la aplicación funciona correctamente y que la IP de conexión se muestra como se esperaba.

![IMG](Imagenes/Imagen_21.png)
![IMG](Imagenes/Imagen_22.png)

