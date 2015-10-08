# Ejercicios de Rubén Martín Hidalgo
## Tema 2
### Ejercicio 1: Instalar alguno de los entornos virtuales de node.js y, con ellos, instalar la última versión existente, la versión minor más actual de la 0.12 y lo mismo para la 0.11 o alguna impar.

En mi caso me he decantado por NVM. Para su instalación, hay que seguir los siguientes pasos:

1. Descargamos el script de instalación de nvm: *curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.28.0/install.sh | bash*

2. El comando anterior habrá clonado el repositorio en ~/.nvm y por tanto ya tenemos instalado nvm. 

3. Ejecutamos *source ~/.profile* en el terminal, para recargar el archivo ~/.profile.

4. Ya podemos instalar alguna versión de node.js, podemos ver las que hay disponibles con: *nvm ls-remote*

5. Para instalar la versión estable más moderna podemos poner: *nvm install stable* que nos instala la v4.1.2

6. También instalamos las versiones más recientes de la 0.12 y la 0.11 con: *nvm install v0.12.7* y *nvm install v0.11.16*

7. Por último, podemos ver las versiones instaladas con el comando *nvm ls*.

![Versiones nodejs instaladas](https://www.dropbox.com/s/brsg2qi0l38vmcg/VersionesNodejs.PNG?dl=1)
