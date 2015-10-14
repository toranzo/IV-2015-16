#Ejercicios del tema 1

##Ejercio1: Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar este artículo en Infoautónomos sobre el tema.

De acuerdo a la tabla de amortizaciones simplificada, para "equipos para tratamiento de la información y sistemas y programas informáticos" podemos aplicarle un coeficiente máximo del 26% a 10 años.

Para este ejercicio he decidido calcular el coste de amortización del [SERVIDOR HP PROLIANT ML110E GEN9 XEON E5-2620v3 2.4GHZ 8GB DDR4 LFF 1TB DVD-ROM ARRAY B140I](http://www.dynos.es/servidor-hp-proliant-ml110e-gen9-xeon-e5-2620v3-2.4ghz-8gb-ddr4-lff-1tb-dvd-rom-array-b140i-888793950609__794996-425.html) con un coste de __1499,00€ *IVA incluido*__ (consultado el día 30/09/2015).


Entonces tenemos que:

| Base imponible |   IVA   | Total factura |
|----------------|---------|---------------|
|      1185€     | 314.79€ |    1499.00€   |


Suponemos para ambos apartados que el servidor es adquirido al comienzo del año.

### 1.1 Amortización a cuatro años

Dividimos entre **4 años** la base imponible y obtenemos una **cuota de amortización de 296.25€**.

| Año | Cuota de amortización| Amortización acumulada | Valor neto contable |
|-----|----------------------|------------------------|---------------------|
|  1  | 296.25€              | 296.25€                | 888,75€             |
|  2  | 296.25€              | 512.5€                 | 592.5€              |
|  3  | 296.25€              | 888,75€                | 296.25€             |
|  4  | 296.25€              | 1185€                  | 0€                  |

### 1.2 Amortización a siete años

Dividimos entre **7 años** la base imponible y obtenemos una **cuota de amortización de 296.25€**.

| Año | Cuota de amortización| Amortización acumulada | Valor neto contable |
|-----|----------------------|------------------------|---------------------|
|  1  | 169.29€              | 169.29€                | 1015.71€            |
|  2  | 169.29€              | 338.55€                | 846.42€             |
|  3  | 169.29€              | 507.84€                | 677.13€             |
|  4  | 169.29€              | 667.13€                | 507.84€             |
|  5  | 169.29€              | 846.42€                | 338.55€             |
|  6  | 169.29€              | 1015.71€               | 169.29€             |
|  7  | 169.29€              | 1185€                  | 0€                  |


## Ejercicio 3

### Ejercicio 3.1

[Contestado en el issue](https://github.com/JJ/IV-2015-16/issues/1)

### Ejercicio 3.2

El programa simple está desarrollado en python

print "Hola mundo!"

Guardamos este programa tan complejo en un fichero... por ejemplo "holaKase.py".

El siguiente paso es descargar CDE. Podemos encontrarlo [aquí](http://www.pgbovine.net/cde.html). (En mi caso voy a descargar la versión de [64bits](https://github.com/downloads/pgbovine/CDE/cde_2011-08-15_64bit) aunque también está disponible la versión de [32bits](https://github.com/downloads/pgbovine/CDE/cde_2011-08-15_32bit))

Se descargará un ejecutable al que debemos dar permisos de ejecución:

$ *sudo chmod +x cde_2011-08-15_64bit*

Ya sólo tenemos que ejecutar el comando

$ *./cde_2011-08-15_64bit python holakAse.py*

Y se nos genera un directorio donde encontraremos el fichero "holakAse.py.cde" junto con otros ficheros de datos de cde.

Para probar si funciona hemos probado con un Sistema Operativo virtualizado tipo Unix. Hemos copiado el directorio generado y ahora accedemos a la ruta donde cde nos ha virtualizado el código.

Accedemos a la ruta:

$ *cd cde-package/cde-root/<ruta>*

Y ejecutamos nuestro programa:

$ *./python.cde holakAse.py*

Y tras la ejecución obtenemos un resultado idéntico al obtenido en la máquina principal.

Para realizar este ejercicio me he basado en la [guía de usuario](http://www.pgbovine.net/cde/manual/) de la página oficial.
