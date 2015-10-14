#Ejercicios - Jesús Prieto López
##TEMA 2

###Ejercicio 1:Instalar alguno de los entornos virtuales de node.js y, con ellos, instalar la última versión existente, la versión minor más actual de la 0.12 y lo mismo para la 0.11 o alguna impar. Si no se usa habitualmente este lenguaje, hacer lo mismo con cualquier otro lenguaje de scripting. 

He utilizado *nodeenv* para el entorno de node.js. Lo podemos instalar con el siguiente comando:

`$ sudo pip install nodeenv`

![Instalación nodeenv](http://i1175.photobucket.com/albums/r628/jesusgorillo/instalacion%20nodeenv_zpsuqrs7jat.png)

*En caso de necesitar **pip** lo instalamos con* `$ sudo apt-get install python-pip`

 Una vez instalado, creamos un entorno y lo activamos

`$ nodeenv env`

`$ . env/bin/activate`

Desde aquí podemos comprobar la versión con el siguiente comando:

`(env)$ node -v`

![Creación del entorno, activación y comprobación de versión](http://i1175.photobucket.com/albums/r628/jesusgorillo/entorno%20nodeenv_zps9hdhtwga.png)

Y desactivamos el entorno para seguir

`(env)$ deactivate`


He instalado la última versión minor de la 0.12, que es la 0.12.7, y la versión 0.11.16.

`$ nodeenv --node=0.12.7 --prebuilt env-0.12.7-prebuilt`

`$ nodeenv --node=0.11.16 --prebuilt env-0.11.16-prebuilt`

![Instalación de diferentes versiones de nodeenv](http://i1175.photobucket.com/albums/r628/jesusgorillo/instalacion%20versiones%20nodeenv_zpsaorhvpqf.png)

También he instalado *virtualenv*

![Instalación de virtualenv](http://i1175.photobucket.com/albums/r628/jesusgorillo/instalacion%20virtualenv_zpsw8nlixro.png)


