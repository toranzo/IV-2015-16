#Ejercicios tema 2


##Ejercicio 1
###Instalar alguno de los entornos virtuales de node.js (o de cualquier otro lenguaje con el que se esté familiarizado) y, con ellos, instalar la última versión existente, la versión minor más actual de la 4.x y lo mismo para la 0.11 o alguna impar (de desarrollo).

HE SEGUIDO ESTE TUTORIAL: https://www.digitalocean.com/community/tutorials/how-to-install-node-js-with-nvm-node-version-manager-on-a-vps

En primer lugar descargamos el fichero install.sh con el comando:

curl https://raw.githubusercontent.com/creationix/nvm/v0.11.1/install.sh | bash
![captura descarga fichero install.sh](https://www.dropbox.com/s/syl4fjl0n2c0cot/1.png?dl=1)

Reinicio la máquina para que se puedan observar los cambios.

Con el comando "nvm ls-remote" podemos ver las distintas versiones de nvm e instalar la que necesitemos.

Instalamos la versión más actual de la v0.11 que es la v0.11.16 con el comando:
nvm install v0.11.16

Instalamos por otro lado la versión más actual de nvm (es la v4.2.1) mediante el comando:
nvm install stable 
![captura instalación última version nvm](https://www.dropbox.com/s/3bktc82dq8amujk/2.png?dl=1)

Y finalmente compruebo que se han instalado las dos versiones que le he indicado con el comando:
nvm ls
![captura visualiza versiones instaladas de nvm](https://www.dropbox.com/s/i2ebltq95393461/3.png?dl=1)

por otro lado he instalado también nodejs:
sudo apt-get install nodejs

y los paquetes del repositorios que necesita npm:
sudo apt-get install npm



##Ejercicio 2


##Ejercicio 3


##Ejercicio 4