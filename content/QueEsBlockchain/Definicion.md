+++
title = "Definición Blockchain"
weight = 1
+++

###### Tiempo estimado:

---

Blockchain, traducido al español como cadena de bloques, es un registro único, consensuado y distribuido en varios nodos pertenecientes a una red. En otras palabras, es un registro histórico de todas las transacciones entre los nodos.

Cada bloque de la blockchain contiene información referente a una transacción y a su vez está ligado al bloque anterior, de tal forma que corromper el bloque actual o alterar la cadena es computacionalmente muy difícil, pues la información actual  no coincidiría con la que tiene el bloque anterior.

Por lo anterior, cada bloque tiene un lugar específico e inalterable dentro de la cadena de bloques que además de asegurar la integridad con el uso de funciones hash, también se busca que cada nodo participante almacene una copia exacta de la cadena. Esto con el propósito de que en caso de lograr alterar la cadena o que haya un error que comprometa la integridad de la cadena, al comparar la cadena corrompida de un nodo con la cadena almacenada en el resto de los nodos pertenecientes a la blockchain, pueda notarse el error y sea posible la recuperación de dicho nodo, sin comprometer la cadena original.

A medida que se agregan nuevos bloques, estos son verificados y validados por todos los nodos de la red antes de agregarlos y al verificar que la transacción fue correcta, es añadida a un bloque y enlazada en la cadena.


### Video Explicativo
{{< youtube _wI7sC4llbA>}} 

{{% attachments title="Material adicional" pattern="2. Que es Blockchain.pdf"  icon="file-pdf" /%}}

### Conceptos Importantes
- **Blockchain:** Cadena de bloques que representa un registro único.
- **Bloque:** Cada uno contiene información referente a una transacción y una liga al bloque anterior.
    - Tiene un lugar especifico e inalterable dentro de la cadena de bloques
    - Asegura la integridad con el uso de funciones hash
    - Cada nodo participante almacena una copia exacta de la cadena


{{% button href="/queesblockchain/elementosbasicos" %}}Siguiente{{% /button %}}