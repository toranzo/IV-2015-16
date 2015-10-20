#Ejercicios tema 2
--------
##Ejercicio 1

####Instalar alguno de los entornos virtuales de node.js (o de cualquier otro lenguaje con el que se esté familiarizado) y, con ellos, instalar la última versión existente, la versión minor más actual de la 4.x y lo mismo para la 0.11 o alguna impar (de desarrollo).

Instalamos nvm en mac OS X siguiendo los [pasos](http://blog.dynamicprogrammer.com/2014/02/18/installing-node-js-on-mac-osx.html)

Con el comando #nvm install v0.11.12 instalamos la verisión 0.11.12 de node.js

Con el mismo comando instalamos la version 4.2.1

Para cambiar la version de node se usa el comendo nvm use "version de node"

**Pasos para arrancar el servidor node.**

Entramos en el directorio .nvm
Luego listamos las versiones con el comando nvm ls. Luego  con el comando nvm use "version" seleccionamos la version.Luego ya podemos ejecutar cualquier fichero .js

##Ejercicio2
 
####Como ejercicio, algo ligeramente diferente: una web para calificar las empresas en las que hacen prácticas los alumnos. Las acciones serían crear empresa y listar calificaciones para cada empresa, crear calificación y añadirla (comprobando que la persona no la haya añadido ya), borrar calificación (si se arrepiente o te denuncia la empresa o algo) y hacer un ránking de empresas por calificación, por ejemplo. Crear un repositorio en GitHub para la librería y crear un pequeño programa que use algunas de sus funcionalidades. Si se quiere hacer con cualquier otra aplicación, también es válido.Se trata de hacer una aplicación simple que se pueda hacer rápidamente con un generador de aplicaciones como los que incluyen diferentes marcos MVC. Si cuesta mucho trabajo, simplemente prepara una aplicación que puedas usar más adelante en el resto de los ejercicios.

##Ejercicio 3
####Ejecutar el programa en diferentes versiones del lenguaje. ¿Funciona en todas ellas?
Ejecutamos el programa en las versiones v0.11.12 (inestable) y la version v.4.2.1 (estable). observamos que funciona en las dos versiones.

~~~
cvi081149:~ bogdan$ nvm ls
->     v0.11.12
         v4.2.1
node -> stable (-> v4.2.1) (default)
stable -> 4.2 (-> v4.2.1) (default)
unstable -> 0.11 (-> v0.11.12) (default)
iojs -> N/A (default)
cvi081149:~ bogdan$ node main.js 
el codigo de la empresa es: x
el nombre de la empresa es: 0
el calificacion de la empresa es: 10
el codigo de la empresa es: x
el nombre de la empresa es: 0
el calificacion de la empresa es: 10
el codigo de la empresa es: x
el nombre de la empresa es: 0
el calificacion de la empresa es: 10
el codigo de la empresa es: x
el nombre de la empresa es: 0
el calificacion de la empresa es: 10
cvi081149:~ bogdan$ nvm use stable
Now using node v4.2.1 (npm v2.14.7)
cvi081149:~ bogdan$ node main.js 
el codigo de la empresa es: x
el nombre de la empresa es: 0
el calificacion de la empresa es: 10
el codigo de la empresa es: x
el nombre de la empresa es: 0
el calificacion de la empresa es: 10
el codigo de la empresa es: x
el nombre de la empresa es: 0
el calificacion de la empresa es: 10
el codigo de la empresa es: x
el nombre de la empresa es: 0
el calificacion de la empresa es: 10
cvi081149:~ bogdan$ 
~~~




