#Tema 2 Teoria#
##Rafael Lachica Garrido##
==
<h3>1. Instalar alguno de los entornos virtuales de node.js y, con ellos, instalar la última versión existente, la versión minor más actual de la 0.12 y lo mismo para la 0.11 o alguna impar. Si no se usa habitualmente este lenguaje, hacer lo mismo con cualquier otro lenguaje de scripting. </h3>

Instalamos nodejs
![instalacionNodejs](http://i1383.photobucket.com/albums/ah302/Rafael_Lachica_Garrido/installnode_zpsgelt0lqx.png)
Comprobamos que se ha instalado correctamente y comprobamos su versión:
![nodeVersion](http://i1383.photobucket.com/albums/ah302/Rafael_Lachica_Garrido/node_zpsdg7z8ra6.png)

<h3>2. Web para calificar las empresas en las que hacen prácticas los alumnos.</h3>
Para ello he seguido un tutorial de Azure y he utilizado una base de datos en Azure DocumentDB. Me he basado en la estructura del código que usa tareas y lo he ajustado a empresas. He usado el framework *Express*.

Base de datos de DocumentDB en Azure:
![documentDB](http://i1383.photobucket.com/albums/ah302/Rafael_Lachica_Garrido/Captura%20de%20pantalla%20de%202015-10-11%20171835_zpsiwetznbe.png)

Web funcionando:
![imagenWeb](http://i1383.photobucket.com/albums/ah302/Rafael_Lachica_Garrido/apiNode_zpsx6jsnuuh.png)

[Directorio App Github](https://github.com/rafaellg8/empresaPracticas)
[Fuente](https://azure.microsoft.com/es-es/documentation/articles/documentdb-nodejs-application/)
<h3>3. Ejecutar el programa en diferentes versiones del lenguaje. ¿Funciona en todas ellas?</h3>

He probado varias versiones y funciona correctamente:

<h3>4. Crear una descripción del módulo usando package.json o el equivalente en otro lenguaje. </h3>
**package.json**
```
{
  "name": "empresaIV",
  "version": "0.0.1",
  "private": true,
  "scripts": {
    "start": "node ./bin/www"
  },
  "description": "Base de datos empresas prácticas",
  "author": {
    "name": "Rafael Lachica Garrido",
    "email": "rafaellg8@correo.ugr.es"
  },
  "dependencies": {
    "async": "^1.4.2",
    "body-parser": "~1.13.2",
    "cookie-parser": "~1.3.5",
    "debug": "~2.2.0",
    "documentdb": "^1.4.0",
    "express": "~4.13.1",
    "jade": "~1.11.0",
    "morgan": "~1.6.1",
    "serve-favicon": "~2.3.0"
  }
}

```
<h3>5. Automatizar con grunt y docco (o algún otro sistema para otro lenguaje de programación) la generación de documentación de la librería que se cree. Previamente, por supuesto, habrá que documentar tal librería.</h3>
He tenido problemas al ejecutar *grunt docco* a la vez, por eso he configurado el *Gruntfile.js* correctamente y he ejecutado grunt, y después **docco *.js**.



<h3>6. Para la aplicación que se está haciendo, escribir una serie de aserciones y probar que efectivamente no fallan. Añadir tests para una nueva funcionalidad, probar que falla y escribir el código para que no lo haga.</h3>

<h3>7. Convertir los tests unitarios anteriores con assert a programas de test y ejecutarlos desde mocha, usando descripciones del test y del grupo de test de forma correcta. Si hasta ahora no has subido el código que has venido realizando a GitHub, es el momento de hacerlo, porque lo vamos a necesitar un poco más adelante.</h3>
