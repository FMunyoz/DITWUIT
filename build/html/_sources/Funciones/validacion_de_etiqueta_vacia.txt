.. index:: pair: Funciones; Validación de etiqueta vacía

.. _validacion-de-etiqueta-vacia:

Validación de etiqueta vacía
----------------------------
.. image:: ../images/Funciones/Validacion.png  
   :scale: 50%
   :align: left 

El proceso de validación de etiqueta vacia consiste en la lectura de las etiquetas SSCC generadas por el proveedor o por un fabricante y de la que no conocemos el contenido. Al leer una de estas etiquetas se solicita toda la información del artículo para dar por validado el bulto.

.. image:: ../images/Funciones/RF/RF_Entrada.png  
   :scale: 50%
   :align: left 
   
Primero se solicita el código de la entrada a validar.

.. image:: ../images/Funciones/RF/RF_Muelle.png  
   :scale: 50%
   :align: left 

A continuación se solicita el muelle. Es la ubicación donde se va a registrar el bulto como ubicado una vez se valide.

.. image:: ../images/Funciones/RF/RF_LeaOrigen.png  
   :scale: 50%
   :align: left 

Seguidamente se pide que se lea el contenedor a validar.
 
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

Al detectar que el SSCC no tiene información asociada se solicita que se lean los identificadores de aplicación (IA) que identifican la información del artículo.

.. image:: ../images/Funciones/RF/RF_AyudaArticulo.png  
   :scale: 50%
   :align: left 

Si no se tiene identificador de artículo se puede pulsar Ayuda y se mostrará las líneas de la entrada para seleccionar la que se desea recibir.

.. image:: ../images/Funciones/RF/RF_AyudaArticuloAmpliada.png  
   :scale: 50%
   :align: left 
   
Una vez seleccionado el artículo se muestra la información ampliada.
 
|
 
|

|
 
|

|

|

|

.. image:: ../images/Funciones/RF/RF_ArticuloCantidad.png  
   :scale: 50%
   :align: left 

A continuación, si se no se tiene la información por la lectura de los IAs se procede a solicitar la cantidad.

.. image:: ../images/Funciones/RF/RF_ArticuloTrazabilidad.png  
   :scale: 50%
   :align: left 
   
A continuación, si el artículo requiere algún tipo de trazabilidad (lote, fecha de caducidad,...) se solicita dicha información.

.. image:: ../images/Funciones/RF/RF_PalletValidado.png  
   :scale: 50%
   :align: left 
   
Una vez finalizado el proceso de validación del bulto se procede, si está así parametrizado, a mostrar el mensaje de palet validado para proceder con el siguiente.


   


