#Ejercicios tema 1


##Ejercicio 1
###Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años.
El ordenador que he elegido es *KIT SERVIDOR ML310 470065-800 XEON E3-1220V3 3.1GHZ 8GB DDR3 2X 1TB + FOUNDATION 2012* en la tienda de [Dynos](http://www.dynos.es/kit-servidor-ml310-470065-800-xeon-e3-1220v3-3.1ghz-8gb-ddr3-2x-1tb--mas-foundation-2012__KIT-ML310-1.html)

Algunas de sus caractirísticas son las siguientes:

- Nombre de Marca:	HP
- Gama de Producto:	ML310e G8
- Modelo de Producto:	470065-800
- Tipo de Producto:	Servidor
- Número de procesadores admitidos:	1
- Número de procesadores instalados:	1
- Fabricante de Procesador:	Intel
- Modelo de Procesador:	Xeon E3-1220V3
- Núcleo del Procesador:	Quad-core (4 Core)
- Velocidad de Procesador:	3,10 GHz
- Velocidad Turbo Máxima:	3,50 GHz
- Caché:	8 MB
- Procesamiento de 64 bits:	Sí
- Memoria Estándar:	8 GB
- Memoria Máxima:	32 GB
- Tecnología de la Memoria:	DDR3 SDRAM
- Número de Ranuras de Memoria (Total):	4
- Número de Discos Duros:	2
- Capcidad Total del Disco Duro:	2 TB
- Interfaz de Disco Duro:	Serial ATA/600
- RPM de Disco Duro:	7200
- Tipo de Unidad Óptica:	Lector DVD
- Compatibilidad con RAID:	Sí
- Niveles de RAID:	0, 1, 1+0
- Número de Ranuras de 3,5":	4
- Número Total de Ranuras de Expansión:	4
- Número de Ranuras PCI Express x4:	1
- Número de Ranuras PCI Express x8:	2
- Número de Ranuras PCI Express x16:	1
- Tecnología Ethernet:	Gigabit Ethernet
- Interfaces/Puertos
- Número total de puertos USB:	8
- Número de puertos USB 3.0:	2
- Red (RJ-45):	Sí
- Remote Management:	Sí

El precio de este producto es 969€ (con IVA)
El precio de amortización de un producto se realiza a partir del precio del producto sin IVA, así que lo primero que hacemos es rectarle el IVA al precio del servidor:
- precio con IVA: 969€
- IVA (21%): 168,18€
- precio sin IVA: 969 * 1,21 = 800,82€

###Amortización a 4 años
Deducimos el máximo del 25% de la amortización por año, con lo cual sería 800,82 * 0,25 = 200,205€ al año.

###Amortización a 7 años
Deducimos que los primeros años se amortiza más
<ol>
	<li>Primer año: 800,82 * 0,25 = 200,205</li>
	<li>Segundo año: 800,82 * 0,25 = 200,205</li>
	<li>Tercer año: 800,82 * 0,15 = 120,123</li>
	<li>Cuarto año: 800,82 * 0,15 = 120,123</li>
	<li>Quinto año: 800,82 * 0,15 = 120,123</li>
	<li>Sexto año: 800,82 * 0,10 = 80,082</li>
	<li>Séptimo año: 800,82 * 0,10 = 80,082</li>
</ol>

##Ejercicio 3.2
###Usando las tablas de precios de servicios de alojamiento en Internet y de proveedores de servicios en la nube, Comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.

<ol>
	<li>He instalado CDE con el comando: sudo apt-get install cde</li>
	<li>Me he creado un pequeño programa en python que imprime una frase</li>
	<li>He empaquetado mi programa con el comando: cde python programa.py</li>
	<li>Me he movido a la ruta ~/Desktop/cde-package/cde-root/home/parallels/Desktop que es donde se encuentra el archivo emmpaquetado por CDE</li>
	<li>Ejecuto el archivo creado</li>
</ol>
![captura de pantalla](https://github.com/ignaciorecuerda/IV-2015-16/blob/miramaejercicios/ejercicios/JoseIgnacioRecuerda/captura.png)


##Ejercicio 4
###Comprobar si el procesador o procesadores instalados tienen estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden?
Al usar mac el comando que he tenido que ejecutar para ver la información del procesador es: sysctl -a | grep machdep.cpu
y la salida ha sido la siguiente:
![captura de pantalla](https://github.com/ignaciorecuerda/IV-2015-16/blob/miramaejercicios/ejercicios/JoseIgnacioRecuerda/captura2.png)
