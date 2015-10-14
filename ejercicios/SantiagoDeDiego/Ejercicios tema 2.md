#Ejercicio 1

Yo he escogido para instalar nvm. Primero de todo abrimos una terminal y escribimos: ``sudo apt-get install -y curl build-essential libssl-dev git``

Una vez hecho esto, escribimos en nuestra terminal: 
``git clone https://github.com/creationix/nvm.git ~/.nvm && cd ~/.nvm && git checkout `git describe --abbrev=0 --tags` ``
De esta forma nos clonamos el repositorio, una vez hecho esto, escribimos: `. ~/.nvm/nvm.sh` para activarlo.

Estas sentencias la hemos obtenido del [Repositorio en github de nvm](https://github.com/creationix/nvm)

Comprobamos que esta correctamente instalado escribiendo nvm y en mi caso se ha ejecutado el programa, lo que quiere decir que está bien instalado.

Ahora, una vez instalado nvm vamos a buscar las versiones que tenemos de nvm, esto lo hacemos con: `nvm ls-remote`. En mi caso voy a instalar la 0.12.7 y 0.11.16. Ejecutamos: `nvm install 0.11.16` y `nvm install 0.12.7`

Ahora solo falta escoger la que queremos usar, en mi caso la última, por tanto escribo: `nvm use 0.12.7` y ya estamos usando la última versión.

##Instalación de virtualenv en MAC OSX
Primero de todo instalamos el gestor de paquetes pip. Esto además nos servirá para el siguiente ejercicio en el que instalaremos Django. Para ello escribimos `sudo easy_install pip` . Una vez instalado, ya solo tenemos que escribir `sudo pip install virtualenv` y ya tenemos instalado virtualenv en Mac.

El motivo de esta instalación es que utilizo bastante el mac para programar en python y me parecía interesante tener un entorno de python.

#Ejercicio 2
Primero de todo voy a instalar Django en el equipo. Empezamos escribiendo `ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"`. Ahora tenemos que instalar el gestor de paquetes pip, que eso ya lo hemos hecho en el ejercicio anterior. Instalamos Django mediante: `sudo pip install Django`.

Creamos un sitio de prueba mediante `django-admin.py startproject prueba` donde prueba es el nombre de mi sitio web. Ahora para arrancarlo solo escribimos `python manage.py runserver` y podemos ver en la dirección *http://127.0.0.1:8000/* como tenemos ya nuestro sitio alojado.

Sin más que ejecutar `python manage.py startapp mi_aplicacion` ya tenemos creada una aplicación web.