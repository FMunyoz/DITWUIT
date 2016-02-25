.. index:: pair: Producto; Datos Principales

Datos Principales
---------------------
.. image:: ../../images/Entidades/Producto/datos_principales.png
   :scale: 50%
   :align: center
   
Permite indicar los datos principales del artículo.

- **Propietario**. Organización propietaria de la mercancía.
- **Código**. Código del artículo.
- **Descripción**. Descripción del artículo.
- **Código principal**. Permite indicar un código de nivel superior.
- **Tipo rotación**. Permite indicar cómo rota el artículo:
	- FIFO. Primera entrada, primera salida.
	- Caducidad
	- Lote
- **Tipo, subtipo, familia y subfamilia**. Una estructura que permite la clasificación de los artículos.
- **Fragilidad**. Permite indicar la fragilidad del producto para poder realizar el proceso de preparación en función de la fragilidad.
- **Gestión reposición**. Permite estable el tipo de reposición de mercancía a las ubicaciones de picking. Por defecto la gestión es picking fijo.
- **ABC**. Permite indicar una clasificación ABC.
- **Precio**. Opcionalmente se puede indicar un precio para el producto.
- **Moneda**. Moneda aplicada al precio.
- **Stock mínimo**. Stock mínimo del producto.
- **Stock máximo**. Stock máximo del producto.
- **Estado del producto**. Estado del producto (ACTIVO, INACTIVO, ELIMINAR)

Unidades de medida
^^^^^^^^^^^^^^^^^^

En esta opción es posible indicar las unidades de medida en la que ver la información. 

Toda la información de stock en **DITWUIT** es almacenada en unidades mínimas. Para facilitar consultar la información en cada área del almacén es posible indicar la unidad en la que se desea ver la información.

Por ejemplo, si deseamos consultar l información en la recepción en cajas se indica que la unidad de recepción es la caja.

Es posible indicar dicha información para:

- **Unidad de recepción**. Unidad de media en la que mostrar la información de la mercancía a recibir.
- **Unidad de preparación**. Unidad de medida en la que mostrar la información de la mercancía a preparar.
- **Unidad de almacenamiento**. Unidad de medida en la que consultar el stock.

Consultas
^^^^^^^^^^
A continuación se detallan las consultas a las que se puede acceder desde esta pantalla:

Historial de operaciones
"""""""""""""""""""""""""

.. image:: ../../images/Entidades/Producto/historial_de_operaciones.png
   :scale: 50%
   :align: center

Permite realizar filtros de las operaciones realizadas.

Resumen de stock
""""""""""""""""

.. image:: ../../images/Entidades/Producto/resumen_de_stock.png
   :scale: 50%
   :align: center
   
Permite consultar el stock de un producto, cuánto está disponible, cuánto en entradas y cuanto en salidas.

Detalle de stock
""""""""""""""""
   
.. image:: ../../images/Entidades/Producto/detalle_de_stock.png
   :scale: 50%
   :align: center

Permite consulta el stock del producto a nivel de ubicación.

Acciones
^^^^^^^^^^

Copiar datos del producto
"""""""""""""""""""""""""

.. image:: ../../images/Entidades/Producto/copiar_datos_del_producto.png
   :scale: 50%
   :align: center
   
Permite copiar datos de un producto en el producto que estamos consultando. Se pueden copiar los datos principales, las presentaciones, los envases y la configuración.

Copiar datos a producto
"""""""""""""""""""""""

.. image:: ../../images/Entidades/Producto/copiar_datos_a_producto.png
   :scale: 50%
   :align: center
   
Permite copiar datos desde el producto que estamos consultando a otro. Se pueden copiar los datos principales, las presentaciones, los envases y la configuración.

