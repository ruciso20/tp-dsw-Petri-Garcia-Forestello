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
|Req|Detalle|
|:-|:-|
| **CRUD Simple** | Clientes | Manejo de datos (nombre, email, teléfono, etc.) |
| | Productos | Gestión (nombre, precio, stock, etc.) |
| | Usuarios | Creación, autenticación y roles (Admin, Vendedor, Cliente) |
| | Pedidos | Registro de pedidos con productos seleccionados |
| **CRUD Dependiente** | CRUD Líneas de Pedido | {depende de} CRUD **Pedidos** |
| | CRUD Pedidos | {depende de} CRUD **Clientes** y CRUD **Productos** |
| **Listado + Detalle** | Clientes | Filtro por nombre/email |
| | Productos | Filtro por nombre/precio |
| | Pedidos | Filtro por fecha/estado |
| **CUU/Épica** | Gestión de Clientes y Pedidos |


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

