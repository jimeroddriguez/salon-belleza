# Salon de Belleza

## Propuesta TP - Lenguaje de Programación Java

## Grupo

### Integrantes

| Legajo | Apellido y Nombre |
|--------|-------------------|
| 51101 | Montenegro, Sofia |
| 54098 | Rodriguez, Jimena |

## Tema

Salón de belleza

### Descripción

La aplicación web cliente-servidor a desarrollar consiste en un sistema que permite reservar turnos para distintos tipos de servicios, como también la compra de productos de belleza. Los turnos podrán ser reservados y personalizados por cada cliente,  facilitando la organización semanal para los empleados y permitiendo, a su vez, la gestión de diversas promociones y descuentos establecidos por el dueño. Además, el sistema realizará una gestión de stock eficiente de productos a medida que son vendidos.


## Modelo

<img width="1093" height="715" alt="image" src="https://github.com/user-attachments/assets/61a8eca2-da79-417d-b602-8440574a0d00" />

## Checklist

### Regularidad

| Requerimiento | Detalle |
| :--- | :--- |
| **ABMC simple** | 1. Usuario<br>2. Servicio |
| **ABMC dependiente** | 1. Reserva {depende de} Usuario y Servicio|
| **CU NO-ABMC** | 1. CUU Realizar reserva |
| **Listado simple** | 1. Listado de reservas => Detalle muestra tipo de servicio reservado, día, horario, precio y empleado que lo realiza |
| **Listado complejo** | - |

### Aprobación Directa

| Requerimiento | Detalle |
| :--- | :--- |
| **ABMC** | 1. Usuario<br>2. Administrador<br>3. Cliente<br>4. Empleado<br>5. Servicio<br>6. Promoción<br>7. Producto<br>8. Venta<br>9. Reserva<br>10. LíneaVenta |
| **CU "Complejo"**(nivel resumen) | 1. CUR Realizar venta (CUU Cancelar venta, Modificar Venta, Gestionar stock)<br>2. CUR Realizar reserva (CUU Cancelar reserva)<br>3. CUR Establecer promoción<br>4. CUR Agregar stock |
| **Listado complejo** | 1. Listado de horarios posibles para reserva => filtrado por servicio y por horarios desponibles de los empleados |
| **Nivel de acceso** | 1. Usuario<br>2. Empleado<br>3. Administrador |
