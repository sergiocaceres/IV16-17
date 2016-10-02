## Ejercicios

#### 1. Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años.

**Equipo:** [*Dell Precision T7810 Workstation*](https://www.theserverstore.com/content/dell-precision-t7810-workstation)  
**Precio:** 2645 $ = 2369 €  
**Base imponible (precio sin IVA):** 2116 $ = 1895 €

Según [esta](https://ayuda.cuentica.com/tabla-anos-porcentajes-amortizacion-simplificada-autonomos-y-profesionales/) tabla de amortización simplificada para autónomos vemos que un ordenador entraría dentro del grupo 5: *Equipos para tratamiento de la información y sistemas y programas informáticos*.
Por lo tanto su coeficiente lineal máximo es del **26 % anual** durante un período máximo de 10 años.  
Eso significa que el **máximo amartizable** para la base imponible de nuestro servidor es de **492'7 € anuales** ( 26 % de 1895 ).

* Para 4 años: 473'75 € anuales (1895 / 4).
* Para 7 años: 270'75 € anuales (1895 / 7).

Por lo que en ningún caso excedemos el máximo amortizable anual ni el período máximo.

#### 2. Usando las tablas de precios de servicios de alojamiento en Internet y de proveedores de servicios en la nube, Comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.

* 1 % de uso mensual: 7,2 horas.
* 10 % de uso mensual: 72 horas.

| Servicio  | Procesador | RAM | Disco | €/hora | Coste mensual 1% uso | Coste mensual 10% uso |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Microsoft Azure Dv2 V2  | Intel Xeon E5-2673 v3 (Haswell) | 7 GB | 100 GB SSD | 0,236 | 1,7 € | 17 € |  
| Amazon EC2 m4.large | Intel Xeon E5-2676 v3 (Haswell) | 8 GB | 100 GB SSD (+8'9€/mes)| 0.107 | 0,77 € (+8'9€) | 16,6 € (con disco) | |
