# Implementación de Base de Datos - Proyecto IS

Este proyecto forma parte de una actividad práctica de modelado y desarrollo de bases de datos relacionales. A través de un proceso completo, se pasa de la interpretación de un diagrama MER hasta la implementación de los scripts DDL en MySQL y el control de versiones mediante GitHub.
# Decisiones de Implementación


## Estructura del modelo

- Se respetó el diagrama MER original incluyendo todas las entidades: cliente, empleado, venta, detalle_venta, producto y categoria.
- Se utilizaron claves primarias tipo INT AUTO_INCREMENT para cada tabla.

## Relaciones

- Las relaciones entre tablas fueron implementadas mediante claves foráneas.
- Las relaciones uno a muchos (cliente → venta, producto → detalle_venta, etc.) fueron correctamente configuradas.

## Tipos de datos

- Para campos como nombre, apellido y email se usaron VARCHAR(45).
- Para valores monetarios (precio, salario) se usó el tipo DOUBLE.
- Los campos createdAt y updatedAt son de tipo DATETIME
