# Salón de Belleza

### Propuesta TP - Lenguaje de Programación Java

## Integrantes

| Legajo | Apellido y Nombre |
|--------|-------------------|
| 51101 | Montenegro, Sofia |
| 54098 | Rodriguez, Jimena |

## Descripción

El sistema a desarrollar es una aplicación web cliente-servidor que permite tanto la reserva de turnos para distintos tipos de servicios como la compra de productos de belleza. Los turnos podrán ser reservados y personalizados por cada cliente, facilitando la organización semanal para los empleados y permitiendo, a su vez, la gestión de diversas promociones y descuentos establecidos por los administradores. Además, el sistema gestionará de forma eficiente el stock de productos a medida que se venden.

## Modelo de dominio

<img width="847" height="584" alt="image" src="https://github.com/user-attachments/assets/c163b6fc-ca8d-4324-b019-67469cf76ae3" />


## Checklist

### Regularidad

| Requerimiento | Detalle |
| :--- | :--- |
| **ABMC simple** | 1. Producto<br>2. Servicio |
| **ABMC dependiente** | 1. Promoción {depende de} Producto y Servicio|
| **CU NO-ABMC** | 1. CUU Reservar servicio |
| **Listado simple** | 1. Listado de reservas => Detalle muestra tipo de servicio reservado, día, horario, precio y empleado que lo realiza |
| **Listado complejo** | - |

### Aprobación Directa

| Requerimiento | Detalle |
| :--- | :--- |
| **ABMC** | 1. Usuario<br>2. Administrador<br>3. Cliente<br>4. Empleado<br>5. Servicio<br>6. Promoción<br>7. Producto<br>8. Venta<br>9. Reserva<br>10. LíneaVenta |
| **CU "Complejo"**(nivel resumen) | 1. CUR Realizar venta (CUU Cancelar venta, Modificar Venta, Gestionar stock)<br>2. CUR Realizar reserva (CUU Cancelar reserva)<br>3. CUR Establecer promoción<br>4. CUR Agregar stock |
| **Listado complejo** | 1. Listado de horarios posibles para reserva => filtrado por servicio y por horarios disponibles de los empleados |
| **Nivel de acceso** | 1. Usuario<br>2. Empleado<br>3. Administrador |
