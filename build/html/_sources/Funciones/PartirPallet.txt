.. index:: pair: Funciones; Partir pallet

Partir pallet
----------------------------------------
Para asignar parte de un pallet a una salida, primero hay que separar la cantidad a asignar y luego asignarlo como un pallet más. Para ello se utiliza el programa de radio-frecuencia **Partir Pallet**.

Con el programa partir pallet, sacamos parte de la mercancía de un pallet origen y la movemos a un pallet destino (normalmente a una etiqueta de pallet vacío como la de picking).

El programa partir pallet solicita leer el pallet origen, del cual sacaremos la mercancía:

.. image:: ../images/Funciones/LeerPaletOrigen.png
   :scale: 50%
   :align: center
 
Nos pregunta la cantidad (en unidades) a mover y que leamos la matrícula del pallet donde lo vamos a dejar:

.. image:: ../images/Funciones/IndiqueCantidadDestino.png
   :scale: 50%
   :align: center

Y se finaliza el proceso.

.. image:: ../images/Funciones/ProcesoFinalizado.png
   :scale: 50%
   :align: center
   

El pallet destino queda ubicado en el mismo sitio que el pallet origen. Lo podmeos ver en el histórico de operaciones:
 
Y en la consulta de stock:
 
El pallet destino es el que podemos añadir al pedido.
