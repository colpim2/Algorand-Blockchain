+++
title = "Árbol de Hash"
weight = 3
+++

###### Tiempo estimado:

---

Un árbol hash de Merkle (en inglés, Merkle hash tree) o árbol de Merkle o árbol hash es una estructura de datos en árbol, binario o no, en el que cada nodo que no es una hoja está etiquetado con el hash de la concatenación de las etiquetas o valores (para nodos hoja) de sus nodos hijo. Son una generalización de las listas hash y las cadenas hash.

Permite que gran número de datos separados puedan ser ligados a un único valor de hash, el hash del nodo raíz del árbol. De esta forma proporciona un método de verificación segura y eficiente de los contenidos de grandes estructuras de datos. En sus aplicaciones prácticas, normalmente el hash del nodo raíz va firmado para asegurar su integridad y que la verificación sea totalmente fiable. La demostración de que un nodo hoja es parte de un árbol hash dado requiere una cantidad de datos proporcional al logaritmo del número de nodos del árbol.

{{% button href="/introduccionalgorand/" %}}Siguiente unidad{{% /button %}}