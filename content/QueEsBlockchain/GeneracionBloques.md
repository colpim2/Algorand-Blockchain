+++
title = "Generación de bloques y funcionamiento básico"
weight = 4
+++

###### Tiempo estimado:

---

Blockchain es una BDD, compartida por un gran número de usuarios, bajo una arquitectura punto a punto donde la información almacenada es ordenada y no puede ser modificada.

La información se contiene en estructuras llamadas “bloques”. Los bloques forman una cadena con el orden en que fueron creados y se liga el bloque actual con el anterior. Los bloques sólo pueden ser creados por los nodos miembros de la blockchain (adicionalmente tiene que tener la función de minero) y únicamente se agregan a la cadena previa cuando existe un “acuerdo” entre la mayoría de los nodos, este acuerdo lleva el nombre de algoritmo de consenso y pretende que sólo se una a la blockchain bloques cuya información de verdadera y válida, pues una vez añadido el bloque la cadena no puede modificarse.

La cadena entera es almacenada en todos los nodos con el fin de tener respaldos de ésta y que no pueda ser modificada, además de asegurar la integridad de la blockchain

{{% button href="/sistemasdistribuidos/" %}}Siguiente unidad{{% /button %}}