# Tema 1. Introducción a la infraestructura virtual: concepto y soporte físico

##Ejercicio 1:
**Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar este artículo en Infoautónomos sobre el tema.**
Para realizar el ejercicio, voy a utilizar el servidor [Acer Predator G3-605_H_ELP] (http://www.pcgreen.com/acer-predator-g3-605-h-elp-820672-p.htm)

El precio sin iva de este servidor es de **789,71€**

Una Amortización a 4 años con un maximo del 25% por cada año serían 789,71 * 0.25 = 197.4275€ por año

Si se trata de una amortización a 7 años, los porcentajes cambian:

|    Año     |   Precio   | Porcentaje | Total Anual |
| ---------- | ---------- | ---------- | ----------- |
|    1       |  789,71    |    0.25    |  197.4275   |
|    2       |  789,71    |    0.25    |  197.4275   |
|    3       |  789,71    |    0.15    |  118.4565   |
|    4       |  789,71    |    0,15    |  118.4565   |
|    5       |  789,71    |    0.1     |   78.971    |
|    6       |  789,71    |    0.05    |   39.4855   |
|    7       |  789,71    |    0.05    |   39.4855   |


**Ejercicios 2:**Usando las tablas de precios de servicios de alojamiento en Internet y de proveedores de servicios en la nube, Comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo. 

Las compañias que he elegido para realziar el ejercicio son [Hostalia] (https://www.hostalia.com/) y [acens] (https://www.acens.com/)

![imagen](https://www.dropbox.com/s/1mveb1r2izzicha/hostalia.png?dl=0)

![imagen](https://www.dropbox.com/s/25ulm87aymi5cqz/acens.png?dl=0)

**Ejercicio 3:** ¿Qué tipo de virtualización usarías en cada caso? Comentar en el foro
Si deseará una virtualización plena, para disfrutar de todas las características de un sistema operativo, utilizaría  hipervisores o programas de control. Si quisiera hacer un estudio más detallado de algún recurso concreto, utilizaría la virtualización parcial de dicho recurso. Para conseguir una virtualización a nivel de sistema operativo utilizaría herramientas con las que ya estamos familiarizados como por ejemplo VMware.  

**Crear un programa simple en cualquier lenguaje interpretado para Linux, empaquetarlo con CDE y probarlo en diferentes distribuciones.**

He decidido utilizar como lenguaje python y el progragrama es ordenación por burbuja
```
#!/usr/bin/env python

	def Burbuja(elementos,tam):
   		 for i in range(1,tam):
   		     for j in range(0,tam-i):
   		         if(elementos[j] > elementos[j+1]):
   		             k = elementos[j+1]
   		             elementos[j+1] = elementos[j]
   		             elementos[j] = k
```

He intalado CDE mediante sudo apt-get install cde
Para empaquetar el programa y poder ejecutarlo, debemos utilizar la orden cde python ejercicio2.py
![imagen](https://www.dropbox.com/s/hui1qnjavnr2jeu/cde.png?dl=0)

**Ejercicio 4:** Comprobar si el procesador o procesadores instalados tienen estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden?
Para comprobar si el procesador tiene instalados dichos flags podemos fijarnos en la siguiente captura resultado de 
```cat /proc/cpuinfo
```
En la que ademas de monstrar el modelo de procesador, aparecen los flags disponibles, entre los que se encuentran vmx y svm
Modelo de procesador: 
![imagen](https://www.dropbox.com/s/i8dog6cd9uqhnco/cpu_info.png?dl=0)
Salida de la orden: 
![imagen](https://www.dropbox.com/s/7txdc5fi6d2k7sp/flags.png?dl=0)


**ejercicio 5:** 1- Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok.
Podemos observar en la salida de la orden, que el kernel de mi PC si contiene este módulo. 
![imagen](https://www.dropbox.com/s/sjtu2ao6jfxq7ch/kvm.png?dl=0)

2-Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios. 
Para la gestión de máquinas virtuales, siempre he utilizado [VirtualBox](https://www.virtualbox.org/) pero unos compañeros me han recomendado utilizar Xen y he decidido instalarlo mediante la orden:
```
sudo apt-get install xen-hypervisor-amd64
```












