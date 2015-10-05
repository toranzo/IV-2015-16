### Ejercicio 1

El pc servidor que voy a utilizar es el HP ProLiant ML350 Gen9, obtenido en la tienda Pccomponentes

( http://www.pccomponentes.com/hp_proliant_ml350_gen9_e5_2620v3_16gb_2x300gb.html )

Su precio base es:  2965 €
Su precio sin IVA es: 2450.41 € 

Supongamos siempre, para facilitar el cálculo que vamos a tomar la fecha de compra como el 1 enero del primer año de amortización (si no simplemente calculamos el equivalente porcentual (12-x)/12, con x el numero de mes en el que estamos y se lo multiplicamos al primer año y añadimos un año más con el factor 1-((12-x)/12) multiplicando)

Amortización en 4 años:

Como el máximo que podemos tomar es un 25% y en este tipo de componentes nos permiten tomar hasta un 26% tomamos un 25% cada año

Primer año: 2450.41*0,25 = 612,6025 €
Segundo año: 2450.41*0,25 = 612,6025 €
Tercer año: 2450.41*0,25 = 612,6025 €
Cuarto año: 2450.41*0,25 = 612,6025 €

En el caso de amortización en 7 años podemos hacer varias cosas, o hacer como en el caso anterior y pagar lo mismo cada año (100/7% cada año), o tomar un gasto descendente (25%+20%+20%+15%+10%+5%+5%)

Lo mismo cada año:

Primer año: 2450.41*1/7 = 350,058571 €
Segundo año: 2450.41*1/7 = 350,058571 €
Tercer año: 2450.41*1/7 = 350,058571 €
Cuarto año: 2450.41*1/7 = 350,058571 €
Quinto año: 2450.41*1/7 = 350,058571 €
Sexto año: 2450.41*1/7 = 350,058571 €
Séptimo año: 2450.41*1/7 = 350,058571 €

Con gasto descendente:

Primer año: 2450.41*0,25 = 612,6025 €
Segundo año: 2450.41*0,2 = 490,082 €
Tercer año: 2450.41*0,2 = 490,082 €
Cuarto año: 2450.41*0,15 = 367,5615 €
Quinto año: 2450.41*0,1 = 245,041 €
Sexto año: 2450.41*0,05 = 122,5205 €
Séptimo año: 2450.41*0,05 = 122,5205 €

### Ejercicio 4

Tras ejecutar la línea de comandos dada compruebo que mi procesador no posee esos flags (no me devuelve nada). Mi procesador es un intel T6400, el cual no posee la tecnología de virtualización de intel, por lo que es normal que no tenga dichos flags. 

Al ejecutar egrep 		'^flags.*(vmx|svm)' /proc/cpuinfo 		no me devuelve nada

Aquí dejo una captura donde se ve toda la información de mi cpu:

![Mi captura](https://www.dropbox.com/s/3bmlu00lwbgr9n4/4.png?dl=0)
![Mi captura2](https://www.dropbox.com/s/ghmm920gdd083en/4%2C1.png?dl=0)

### Ejercicio 5

#### Apartado 1

No lo soporta, aquí dejo lo obtenido al ejecutar la orden:

![ejer51](https://www.dropbox.com/s/v8gpjl742jlcda2/5%2C1.png?dl=0)

#### Apartado 2

Aquí dejo las capturas de la instalación de QEMU:

![ejer521](https://www.dropbox.com/s/gqq1qyrg5ul8c4a/Ejercicio5%2C2%2C1.jpg?dl=0)
![ejer522](https://www.dropbox.com/s/5f3j8ky0f8a0bun/ejercicio5%2C2%2C2.png?dl=0)
![ejer523](https://www.dropbox.com/s/dbdq448jzffd5ui/Ejercicio%205%2C2%2C3.png?dl=0)
![ejer524](https://www.dropbox.com/s/flwp2h7lb70p8ba/Ejercicio5%2C2%2C4.png?dl=0)