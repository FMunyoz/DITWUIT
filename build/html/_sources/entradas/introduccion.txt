.. index:: pair: Entradas; Introducción

**********************
Entradas. Introducción
**********************
Todo almacén interactúa con el exterior. Dentro de las entradas nos referimos a todo movimiento que suponga una entrada de mercancía en el almacén.  El origen de esta mercancía puede ser muy variado:

- Entrada de Proveedor
- Devolución de Cliente
- Entrada de Fábrica
- Entrada de Otro almacén
- Entrada de un Manipulador (Copacking)
- …

En todos los casos podemos distinguir distintas formas de recibir la información de entradas.

- **Entrada con documento asociado**. Se recibe un documento previo  (orden de compra, pedido, …) con la información de la mercancía que se va a recibir. En este caso estaremos hablando de una **orden de entrada**. A su vez, podemos identificar cómo se recibe la mercancía y la información de la mercancía a recibir:
    - *Mercancía en una unidad logística identificada por un SSCC del proveedor o fabricante*. Toda la mercancía viene en, por ejemplo, palets y cada palet dispone de una etiqueta **GS1 128** susceptible de ser utilizada por **DITWUIT**.
        - Recepción electrónica de la mercancía recibida. Por ejemplo, recibiendo un mensaje **RECADV**. La información puede recibirse con el detalle de la paletización.
        - Sin recepción electrónica de la mercancía recibida.
    - *Mercancía no identificada*. La mercancía se recibe en unidades logísticas o se clasifica en unidades logísticas en recepción y es necesario emitir una etiqueta **GS1** para su identificación.
        - Recepción electrónica de la mercancía. En este caso se recibe sin detalle de la paletización.
        - Sin recepción electrónica de la mercancía recibida.
- **Entrada sin documento asociado**. En este caso se recibe mercancía sin un documento previo. 

En **DITWUIT** se permite crear manualmente la orden de entrada para proceder a realizar la entrada de la mercancía sin documento asociado.
