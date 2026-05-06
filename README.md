Documentación — Modelo Cars Marketplace
Descripción
Modelo de datos para una plataforma de compraventa de autos usados.

Base de datos: Vehicle_Storage

Tablas
marcas
vehiculos
customers
ordenes
pagos
Relaciones
Un cliente puede tener muchas órdenes
Una orden corresponde a un solo auto
Un pago corresponde a una orden
Notas técnicas
Las claves foráneas en Databricks son informativas.
La integridad referencial debe validarse en el pipeline de datos.
Autor
Nombre: Agustin Martinez Fecha: 05/05/2026
