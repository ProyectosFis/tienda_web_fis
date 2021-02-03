

Tienda Básica de un barrio, aplicando metodologías de historias de usuario

# Integrantes
* Christian Caro - 20181020027
* Neider Puentes - 20162021307
* Santiago Ríos - 20181020017

Inventario
Informacion Empleados
# Roles principales
### Vendedor
- Propietario Tienda

### Proveedor
- Carga la tienda de productos necesarios

### Cliente
- Comprador de los productos

### Domiciliario
- Entrega los productos

# Reglas, Procesos y Funcionalidades de venta

* Venta full Online
* Venta de productos perecederos y no perecederos
* Mercadeo e inventariado
* Envío y Recepción de Productos
* Proceso de venta de Producotos
* Validación métodos de Pago
* Facturación electrónica
* Creacion de Pedidos
* Despacho de Pedidos
* Seguimiento de Pedidos
* Comunicación Cliente, Vendedor y Proveedores
* Visualización de Pedidos
* Consumo de Productos en inventario.
* Confirmar Domiciliario
* Ruteo óptimo de Pedidos
* Estudio de mercadeo
* Sugerencia de Productos
* Generación de Promociones
* Alertar sobre Inventario
* Confirmación Venta y Pago

# Historias de Usuario:

## Cliente
* Realizar el pedido seleccionando de una lista de productos disponibles en la tienda
* Revisar las promociones en la tienda
* Confirmar el pedido con los productos seleccionados
* Confirmar el método de Pago
* Ofrecer ubicación
* Cancelar parcialmente un pedido (productos específicos)
* Sugerir al Tendero productos nuevos del inventario

## Tendero
* Reportes sobre solicitud de los productos para optimizar el inventario
* Crear campaña de promoción para mejora la imagen del negocio
* Generar facturas digitales y/o físicas para el Cliente
* Administrar lista de pedidos para despacho por domiciliario(s)
* Organizar el Inventario
* Solicitar productos al Inventario


### Requerimientos Tecnologicos y Arquitecturales
* Pagina web Optimizada para la Visualizacion de productos disponibles en una tienda
* Pagina Web con Opcion de Venta de una lista de productos
* Orientacion en Microservicios


## Historias Prioritarias
* Solicitar productos como cliente
* Como tendero despachar los productos para Envío de Pedidos
* Como tendero administrar los pedidos para ordenar la tienda y como cliente enviar ubicación para facilitar uso de app


## Lista de Tareas

* Llenado de Carrito en Web
* Estructurar la Base de Datos y poblado de la misma
* Microservicio de Consulta y Edicion de DB


## Definición de Roles

### Santiago Rios

 - Creación del proyecto.
 - Configuración de la base de datos.
 - Generar un arreglo de prueba para mostrar productos.
 - Diseñar e implementar inicio de sesión y crear cuenta.
 
### Neider Puentes

 - Implementar el home. Como usuario necesito tener una interfaz en la cual se puedan visualizar todos los productos que ofrece la tienda.
 - Mostrar ese arreglo de productos que ya está en la base de datos.
 
### Christian  Caro
 - Implementar el carrito. Como usuario necesito tener una interfaz en la cual pueda visualizar los productos que preseleccioné y también manejar la cantidad de productos de los mismos.
 - Registrar la compra con sus respectivos valores en la base de datos.