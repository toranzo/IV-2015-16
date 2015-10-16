#Ejercicio 1

Yo he escogido para instalar npm por su facilidad de instalación en MAC. Solo tenemos que instalar el archivo que encontramos en la [Página oficial](https://nodejs.org/en/) y darle a siguiente, siguiente al estilo windows.
##Instalación de virtualenv en MAC OSX
Primero de todo instalamos el gestor de paquetes pip. Esto además nos servirá para el siguiente ejercicio en el que instalaremos Django. Para ello escribimos `sudo easy_install pip` . Una vez instalado, ya solo tenemos que escribir `sudo pip install virtualenv` y ya tenemos instalado virtualenv en Mac.

El motivo de esta instalación es que utilizo bastante el mac para programar en python y me parecía interesante tener un entorno de python.

#Ejercicio 2
Primero de todo voy a instalar Django en el equipo. Empezamos escribiendo `ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"`. Ahora tenemos que instalar el gestor de paquetes pip, que eso ya lo hemos hecho en el ejercicio anterior. Instalamos Django mediante: `sudo pip install Django`.

Creamos un sitio de prueba mediante `django-admin.py startproject prueba` donde prueba es el nombre de mi sitio web. Ahora para arrancarlo solo escribimos `python manage.py runserver` y podemos ver en la dirección *http://127.0.0.1:8000/* como tenemos ya nuestro sitio alojado.

Sin más que ejecutar `python manage.py startapp mi_aplicacion` ya tenemos creada una aplicación web.