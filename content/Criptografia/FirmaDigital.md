+++
title = "Firma Digital"
weight = 2
+++

###### Tiempo estimado:

---

Una **firma digital** es una técnica matemática utilizada para validar la **autenticidad** e **integridad** de un **mensaje**, **software** o **documento digital**. Es el equivalente digital a una firma manuscrita o sello estampado ya que ofrece una seguridad más inherente, y está destinada a resolver el problema de la **manipulación** y la **suplantación** en las **comunicaciones digitales**.

La firma digital proveé al destinatario la certeza de que el mensaje recibido proviene de un remitente esperado (autenticando la fuente de origen del mensaje), además, la firma digital garantiza que el remitente no puede negar ser la fuente del mensaje (no repudio) y que el mensaje no fue alterado en el tránsito de emisor a receptor (integridad del mensaje).

Dicho lo anterior, se evidencia que las firmas digitales pueden proporcionar garantías adicionales de origen, identidad y estado de un documento electrónico, transacción o mensaje y **reconocen el consentimiento informado por parte del firmante**.

Las firmas digitales se basan en la **criptografía de llave pública como RSA (criptografía asimétrica)**. Las firmas digitales funcionan a través de las dos llaves criptográficas dentro de un esquema de **llave pública** que se autentican mutuamente: 

La persona que está creando la firma digital utiliza su **llave privada** para **cifrar** los datos relacionados con el  mensaje; posteriormente, para realizar la autenticación de la firma se utiliza la **llave pública** del firmante ya que es la única manera de **descifrar** los datos del mensaje, a su vez, al utilizar la llave pública del emisor se puede corroborar la identidad del firmante ante los ojos del receptor.


{{% button href="/criptografia/arbolhash" %}}Siguiente{{% /button %}}