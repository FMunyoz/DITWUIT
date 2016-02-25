.. index:: pair: Funciones; Línea de Producción

.. _linea-de-produccion:

Línea de Producción
---------------------
.. image:: ../images/Funciones/Validacion.png  
   :scale: 50%
   :align: left 

El proceso de línea de producción es similar al de :ref:`validacion-de-etiqueta-vacia` con el añadido de que se solicita la ubicación destino para mover la mercancía desde el muelle (la línea de producción) a su ubicación definitiva.

.. image:: ../images/Funciones/RF/RF_Entrada.png  
   :scale: 50%
   :align: left 
   
Primero se solicita el código de la entrada a la que se va a asociar la mercancía a recibir de la línea de producción.

.. image:: ../images/Funciones/RF/RF_Muelle.png  
   :scale: 50%
   :align: left 

A continuación se solicita el muelle asociado a la línea de producción. Es la ubicación donde se va a registrar el bulto como ubicado una vez se valide.

.. image:: ../images/Funciones/RF/RF_LeaOrigen.png  
   :scale: 50%
   :align: left 

Seguidamente se pide que se lea el contenedor a recibir de la línea de producción.
 
|
 
|

|
 
|

|

|

|

.. image:: ../images/Funciones/RF/RF_Articulo.png  
   :scale: 50%
   :align: left 

Al detectar que el SSCC no está aún en DITWUIT se solicita que se lean los identificadores de aplicación (IA) que identifican la información del artículo.

.. image:: ../images/Funciones/RF/RF_LeaDestino.png  
   :scale: 50%
   :align: left 

A continuación procede a solicitar la ubicación del palet en su ubicación destino.

.. image:: ../images/Funciones/RF/RF_PalletValidado.png  
   :scale: 50%
   :align: left 
   
Una vez finalizado el proceso de validación del bulto se procede, si está así parametrizado, a mostrar el mensaje de palet validado para proceder con el siguiente.


   


