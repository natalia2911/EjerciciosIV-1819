
# Ejercicios tema 1
---


### Ejercicio 1. Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar [este artículo en Infoautónomos sobre el tema](http://infoautonomos.eleconomista.es/consultas-a-la-comunidad/988/).

Un ordenador tipo servidor tiene un precio aproximado de unos 850 euros.

Según [esta página](hhttps://cuentica.com/asesoria/tabla-anos-y-porcentajes-de-amortizacion-sociedades-a-partir-de-2015/) un equipo de para procesos de información tiene un porcentaje de amortización del 25%

* En 4 años = 850  euros
* En 7 años = 1487.5 euros
---


### Ejercicio 2. Usando las tablas de precios de servicios de alojamiento en Internet “clásicos”, es decir, que ofrezcan _Virtual Private Servers_ o servidores físicos, y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.

---


### Ejercicio 3. En general, cualquier ordenador con menos de 5 o 6 años tendrá estos _flags_. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, [el procesador del móvil](https://stackoverflow.com/questions/26239956/how-to-get-specific-information-of-an-android-device-from-proc-cpuinfo-flie)?

El procesador es : Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz

La orden que hemos usado es `egrep '^flags.*(vmx|svm)' /proc/cpuinfo`

---
![](https://github.com/natalia2911/EjerciciosIV-1819/blob/master/t1-ej3.png)

### Ejercicio 4. Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden `kvm-ok`. -Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios.
1. ![](https://github.com/natalia2911/EjerciciosIV-1819/blob/master/t1-ej4.1.png)

2.  ![](https://github.com/natalia2911/EjerciciosIV-1819/blob/master/t1-ej4.2.png)


### Ejercicio 5. Darse de alta en servicios de nube usando ofertas gratuitas o cupones que pueda proporcionar el profesor.


Estamos a la espera de que el profesor nos de una licencia de Azure.

---
### Ejercicio 6. Darse de alta en una web que permita hacer pruebas con alguno de los sistemas de gestión de nube anteriores.

---
