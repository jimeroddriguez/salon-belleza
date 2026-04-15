# salon-belleza

## Propuesta TP Desarrollo - Lenguaje de Programación Java

## Grupo

### Integrantes

| Legajo | Apellido y Nombre |
|--------|-------------------|
| 51101 | Montenegro, Sofia |
| 54098 | Rodriguez, Jimena |

## Tema

Salón de belleza

### Descripción

La aplicación web cliente-servidor a desarrollar consiste en un sistema que permite reservar turnos para distintos tipos de servicios o la sumatoria de ellos, como también la compra de productos de belleza. Los turnos podrán ser reservados y personalizados por cada cliente,  facilitando la organización semanal para los empleados y permitiendo, a su vez, la gestión de diversas promociones y descuentos establecidos por el dueño. Además, el sistema realizará una gestión de stock eficiente de productos a medida que son vendidos.


## Modelo



## Checklist

### Regularidad

| Requerimiento | Detalle |
| :--- | :--- |
| **ABMC simple** | 1. Vianda<br>2. Ingrediente |
| **ABMC dependiente** | 1. Ingrediente_vianda {depende de} Vianda e Ingrediente |
| **CU NO-ABMC** | 1. CUU Realizar pedido |
| **Listado simple** | 1. Listado de las viandas => Detalle muestra información completa de las viandas y sus ingredientes |
| **Listado complejo** | - |

### Aprobación Directa

| Requerimiento | Detalle |
| :--- | :--- |
| **ABMC** | 1. Usuario<br>2. Administrador<br>3. Cliente<br>4. Empresa<br>5. Mayorista<br>6. Vianda<br>7. Ingrediente<br>8. Ingrediente_vianda<br>9. Pedido<br>10. Detalle_pedido |
| **CU "Complejo"**(nivel resumen) | 1. CUR Seguimiento de pedidos (CUU Consultar listado de pedidos por estado y CUU Actualizar estado de pedido) |
| **Listado complejo** | 1. Listado de pedidos confirmados |
| **Nivel de acceso** | 1. Usuario<br>2. Administrador |
