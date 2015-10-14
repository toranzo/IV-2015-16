# Tema 2. Desarrollo basado en pruebas

##Ejercicio 1: Instalar alguno de los entonrnos virtuales de node.js y, con ellos, instalar la última versión existente, la versión minor más actual de la 0.12 y lo mismo para la 0.11 o alguna impar. Si no se una habitualmente este lenguaje, hacer lo mismo con cualquier otro lenguaje de scripting.

**Paso 1:** Actualizar repositorios de Ubuntu y obtener los que permiten crear paquetes, mediante las intrucciones:

	$ sudo apt-get update

	$ sudo apt-get install build-essential libssl-dev

**Paso 2:** Descargar el script de instalación de nvm desde Github usando curl:

	$ curl https://raw.githubusercontent.com/creationix/nvm/v0.7.0/install.sh | sh

**Paso 3:** Acceder a la funcionalidad de nvm, para esto tenemos dos caminos, reiniciar el sistema  o recargar el archivo de configuración mediante la orden:

	$ source ~/.profile

**Paso 4:** Comprobar las versiones existentes mediante la orden:
	
	$ nvm ls-remote

**Paso 5:** Instalar la version que queramos. Por ejemplo, para la version inferior a la 0.12:

	$ nvm install 0.12.0

Para la 0.11:

	$ nvm install 0.11.0

**Paso 6:** Comprobar las versiones de Node y NPM que tenemos instaladas en nuestro equipo mediante las ordenes

	$ node -v

	$ npm -v 
![version node](https://www.dropbox.com/s/mzlbhkjyoi5yu1v/node_v.png?dl=1)
