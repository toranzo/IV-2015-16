#Tema 3
##Rafael Lachica Garrido
#Ejercicio 1
##Instalar un entorno virtual para tu lenguaje de programación favorito (uno de los mencionados arriba, obviamente).

Instalo virtualenv para **python**:

```
rafaellg8: ~ $ sudo apt-get install python-virtualenv
Reading package lists... Done
Building dependency tree
```

#Ejercicio 2
##Darse de alta en algún servicio PaaS tal como Heroku, Nodejitsu u OpenShift.

Me daré de alta en el sistema de **Openshift**, accedemos a [Openshift](https://openshift.redhat.com) y nos registramos.

![Openshift](http://i1383.photobucket.com/albums/ah302/Rafael_Lachica_Garrido/openshift_zps6qi2uvc0.png)


#Ejercicio 3
##Crear una aplicación en OpenShift y dentro de ella instalar WordPress.
Pinchamos en crear aplicación y elegimos **WordPress**. Vamos asignando datos como la IP Pública y el dominio:
![WordPress](http://i1383.photobucket.com/albums/ah302/Rafael_Lachica_Garrido/Captura%20de%20pantalla%20de%202015-10-18%20125416_zpsdwttwvad.png)
[direcciónURL](http://php-rafaellg8.rhcloud.com)
Una vez configurado nos pedirá que instalemos WordPress en la página de inicio,donde nos pide el lenguaje, el nombre de la página el usuario y contraseña,además del email.
Una vez rellenado correctamente los campos, le damos a instalar.
Y ya tenemos nuestro WordPress con la primera entrada **HOLA MUNDO**:
![WordPress2](http://i1383.photobucket.com/albums/ah302/Rafael_Lachica_Garrido/Captura%20de%20pantalla%20de%202015-10-18%20130413_zps2h70qbx2.png)

#Ejercicio 4
##Crear un script para un documento Google y cambiarle el nombre con el que aparece en el menú,así como la función a la que llama.
```
function renameFile() {
  var file = DocumentApp.getActiveDocument();  
  file.setName('HOLA MUNDO');
  var ui = DocumentApp.getUi();
  ui.prompt("Nombre cambiado");
}
```
![googleAppScript](http://i1383.photobucket.com/albums/ah302/Rafael_Lachica_Garrido/Captura%20de%20pantalla%20de%202015-10-18%20185828_zpsoiebi2ta.png)
