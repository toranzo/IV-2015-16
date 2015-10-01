# Tema 1

### Ejercicio 1: Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años.

Mirando por Amazon he encontrado el servidor [HP 726042-425](http://www.amazon.es/dp/B00E88ZHLC/ref=asc_df_B00E88ZHLC29121151/?tag=googshopes-21&creative=24526&creativeASIN=B00E88ZHLC&linkCode=df0)

Su precio es de 682,51€ (IVA incl.), como necesitamos el precio sin IVA pues hacemos el cálculo:

682.51€ - 682.51€ * 0.21 = 539.18€

**Amortización a 4 años**

Con una amortización máxima del 25% por año: 

    - Primer año: 	539.18€ * 0.25 = 134.80€
    - Segundo año:	539.18€ * 0.25 = 134.80€
    - Tercer año:	539.18€ * 0.25 = 134.80€
    - Cuarto año:	539.18€ * 0.25 = 134.80€

**Amortización a 7 años**

En este caso se va reduciendo el coste del producto conforme pasan los años, los 2 primeros años se mantiene el 25% pero el 50% restante se divide de forma gradual en los 5 siguientes años como podemos ver a continuación:

    - Primer año: 	539.18€ * 0.25 = 134.80€
    - Segundo año:	539.18€ * 0.25 = 134.80€
    - Tercer año:	539.18€ * 0.15 =  80.88€
    - Cuarto año:	539.18€ * 0.15 =  80.88€
    - Quinto año:	539.18€ * 0.10 =  53.92€
    - Sexto año:	539.18€ * 0.05 =  26.96€
    - Séptimo año:  539.18€ * 0.05 =  26.96€

### Ejercicio 5.1: Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok.

![Captura módulo kvm](img/tema1-5.1.png)

