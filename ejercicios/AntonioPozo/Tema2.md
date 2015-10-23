###Ejercicio 1
**Instalar alguno de los entornos virtuales de node.js (o de cualquier otro lenguaje con el que se esté familiarizado) y, con ellos, instalar la última versión existente, la versión minor más actual de la 4.x y lo mismo para la 0.11 o alguna impar (de desarrollo).**

He instalado NVM. Para su instalación, hay que seguir los siguientes pasos:

1. Tecleamos la siguiente orden:  curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.28.0/install.sh | bash

2. Ejecutamos source ~/.profile en el terminal, para recargar el archivo ~/.profile.

3. Instalamos node.js con la orden nvm install stable

4. También instalamos las versiones más recientes de la 0.12 y la 0.11 con: nvm install v0.12.7 y nvm install v0.11.16

5. Se pueden ver las versiones instaladas con la orden nvm ls.

![captura versiones nvm](http://s2.subirimagenes.com/imagen/previo/thump_9483947ej1.png)




###Ejercicio 2
**Como ejercicio, algo ligeramente diferente: una web para calificar las empresas en las que hacen prácticas los alumnos. Las acciones serían crear empresa y listar calificaciones para cada empresa, crear calificación y añadirla (comprobando que la persona no la haya añadido ya), borrar calificación (si se arrepiente o te denuncia la empresa o algo) y hacer un ránking de empresas por calificación, por ejemplo. Crear un repositorio en GitHub para la librería y crear un pequeño programa que use algunas de sus funcionalidades. Si se quiere hacer con cualquier otra aplicación, también es válido. Se trata de hacer una aplicación simple que se pueda hacer rápidamente con un generador de aplicaciones como los que incluyen diferentes marcos MVC. Si cuesta mucho trabajo, simplemente prepara una aplicación que puedas usar más adelante en el resto de los ejercicios**

He creado una aplicación web básica para la solución de este ejercicio sirviéndome de ![enlace codedrinks](http://www.codedrinks.com/como-crear-una-pagina-web-con-node-js-express-jade-y-stylus/)
Instalamos las herramientas necesarias para el funcionamiento de ésta aplicación:
    npm install express
    npm install jade
    npm install stylus


    

###Ejercicio 3
**Ejecutar el programa en diferentes versiones del lenguaje. ¿Funciona en todas ellas?**



###Ejercicio 4
**Crear una descripción del módulo usando package.json. En caso de que se trate de otro lenguaje, usar el método correspondiente.**




###Ejercicio 5
**Automatizar con grunt y docco (o algún otro sistema) la generación de documentación de la librería que se cree. Previamente, por supuesto, habrá que documentar tal librería.**





###Ejercicio 6
**Para la aplicación que se está haciendo, escribir una serie de aserciones y probar que efectivamente no fallan. Añadir tests para una nueva funcionalidad, probar que falla y escribir el código para que no lo haga (vamos, lo que viene siendo TDD).**


###Ejercicio 7
**Convertir los tests unitarios anteriores con assert a programas de test y ejecutarlos desde mocha, usando descripciones del test y del grupo de test de forma correcta. Si hasta ahora no has subido el código que has venido realizando a GitHub, es el momento de hacerlo, porque lo vamos a necesitar un poco más adelante.**


###Ejercicio 8
**Ejercicio: Haced los dos primeros pasos antes de pasar al tercero.**















