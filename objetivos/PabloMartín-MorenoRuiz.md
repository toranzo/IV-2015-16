# Objetivos Pablo Martín-Moreno Ruiz

## Objetivos Primera semana

* Entender la metodología docente, de evaluación y de interacción de la asignatura.
* Darse de alta y comprender el funcionamiento básico de GitHub y la lista de correo de la asignatura; conocer el resto de los recursos de la asignatura.
* Entender el concepto de software libre y su aplicación práctica en clase.
* Vernos las caras.

### Otros objetivos
* Acceder al correo comunitario.
* Aprender a usar un poquito el github y git.
* Aprender a escribir un poco en lenguaje Markdown


## Objetivos Segunda semana

Ejercicio 1. http://www.dynos.es/servidor-hp-proliant-ml110e-gen9-xeon-e5-2620v3-2.4ghz-8gb-ddr4-lff-1tb-dvd-rom-array-b140i-888793950609__794996-425.html

El precio del ordenador es de 1499 euros.

 A) Amortización en 4 años.
 
  Entonces podemos amortizar cada año un 25%  que sería cada año 374.75 €.
  
 B) Amortización en 7 años.
 
  Entonces podemos amortizar cada año 14,29% que sería cada año 214,14 €.
  
  

Ejercicio 4 Comprobar si el procesador o procesadores instalados tienen estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden?

Si los tiene instalados y lo comprobamos con la siguiente orden egrep '^flags.*(vmx|svm)' /proc/cpuinfo. 

El prodecesador de mi máquina es Intel(R) Core(TM) i5 CPU       M 480  @ 2.67GHz
 
La salida de la orden introducida es la siguiente repetida 4 veces, una por cada hebra que maneja mi procesador.

flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe nx rdtscp lm constant_tsc arch_perfmon pebs bts xtopology nonstop_tsc aperfmperf pni dtes64 monitor ds_cpl vmx est tm2 ssse3 cx16 xtpr pdcm pcid sse4_1 sse4_2 popcnt lahf_lm ida arat dtherm tpr_shadow vnmi flexpriority ept vpid


