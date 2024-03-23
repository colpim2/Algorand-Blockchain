+++
title = "Elementos básicos y estructura de Blockchain"
weight = 2
+++

###### Tiempo estimado:

---

La estructura de una blockchain particular, así como sus elementos fundamentales, pueden diferir según su aplicación, no obstante, una cadena de bloques comparte elementos genéricos, estos son:

**Red punto a punto**

Red punto a punto
Una blockchain utiliza la topología punto a punto donde cada peer es un nodo que pertenece a la Blockchain.

**Direcciones**

Son identificadores únicos usados en las transacciones de la blockchain. Con las direcciones se reconoce el emisor y el receptor. En una blockchain la dirección es usualmente una llave pública o un derivado de una. Una dirección puede ser reutilizada por el mismo usuario, sin embargo, la dirección en sí es única. Normalmente un usuario no reutiliza las direcciones, sino que genera una nueva para cada transacción.

**Transacción**

Representa la transferencia de valores, información o datos de una dirección a otra.

**Nodo**

Un nodo que pertenece a la red blockchain es una entidad física reconocida como miembro de la cadena de bloques. Puede realizar varias funciones, dependiendo del rol que tenga dentro de la blockchain; puede proponer y validar transacciones, es capaz de minar para facilitar el consenso y la seguridad de la red, entre otras dependiendo el tipo de blockchain y el tipo de nodo.

**Nodo minero**

Es un nodo que participa en el proceso de creación (escritura de los datos) de los bloques que serán agregados a la cadena de bloques, esto a cambio de una recompensa. El proceso de escritura se llama “minar” y el bloque resultante sólo puede ser añadido tras ser revisado y acordado su ingreso a la cadena de bloques si otros nodos lo avalan.

**Ledger**

Se trata de una red digital (base de datos) que registra datos e historial de transacciones de activos en nodos descentralizados.

**Bloque**

Un bloque es la unidad de información contenida en la blockchain. Está compuesto de múltiples transacciones, cada transacción tiene un apuntador al hash del bloque anterior, una la marca de tiempo -de cuando fue realizada la transacción-, la información referente al bloque actual y el número aleatorio Nonce utilizado para calcular los hashes.


{{% button href="/queesblockchain/mecanismosseguridad" %}}Siguiente{{% /button %}}