# Propuesta TP DSW

## Grupo
### Integrantes
* 51462 - Garcia Forestello, Joaquin
* 50328 - Petri, Guillermo

### Repositorios
* [frontend app](https://github.com/ValentinR19/tp-dsw-frontend)
* [backend app](https://github.com/ValentinR19/tp-dsw-backend)


## Tema
### Descripción
Sistema CRM para la gestión de clientes, productos y pedidos, orientado a la optimización de ventas . 
Permite gestionar usuarios, productos, realizar pedidos y consultar el historial de ventas.
Con enfoque en una experiencia de usuario sencilla .

### Modelo
![imagen del modelo](file:///home/peto/Descargas/tp-dsw.svg)

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
| Req | Detalle |
|:---|:---|
| CRUD simple | 1. **CRUD de Clientes**: manejo de datos de clientes (nombre, email, teléfono, etc.).<br>2. **CRUD de Productos**: gestión de productos (nombre, precio, stock, etc.).<br>3. **CRUD de Usuarios**: creación, autenticación y gestión de roles (Admin, Vendedor, Cliente).<br>4. **CRUD de Pedidos**: registro de pedidos realizados por los clientes, incluyendo productos seleccionados. |
| CRUD dependiente | 1. **CRUD Líneas de Pedido**: {depende de} CRUD Pedidos.<br>2. **CRUD Pedidos**: {depende de} CRUD Clientes y CRUD Productos. |
| Listado + detalle | 1. **Listado de Clientes**: filtro por nombre o email, muestra un listado de clientes.<br>2. **Listado de Productos**: filtro por nombre o precio, muestra productos disponibles.<br>3. **Listado de Pedidos**: filtro por fecha y estado, muestra los pedidos realizados. |
| CUU/Epic | 1. **Gestión de Clientes y Pedidos** |


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD ||
|CUU/Epic||


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados ||
|CUU/Epic||
|Otros|1. Impresion por PDF|

