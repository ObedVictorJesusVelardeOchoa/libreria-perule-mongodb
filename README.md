# Gestión de la Librería “Perule” – MongoDB

Proyecto académico desarrollado para el curso **Base de Datos II**, enfocado en el diseño e implementación de una base de datos NoSQL utilizando **MongoDB** para la gestión integral de una librería real.

## 🏪 Contexto
Librería “Perule”, pequeño negocio familiar ubicado en Lima, Perú, dedicado a la venta de libros y productos escolares.  
El proyecto surge tras una entrevista directa con la propietaria, donde se identificó la ausencia de un sistema digital de gestión.

## 🎯 Objetivo
Diseñar una base de datos no relacional que permita:
- Registrar ventas y clientes
- Controlar inventario
- Obtener reportes y estadísticas
- Gestionar usuarios con roles diferenciados

## 🗂️ Colecciones Implementadas
- Autores
- Clientes
- Libros
- OtrosProductos
- Ventas

## 🔗 Relaciones
- Referencias entre colecciones usando ObjectId
- Uso de `$lookup` para uniones virtuales
- Modelo escalable y normalizado para análisis avanzado

## ⚙️ Funcionalidades Técnicas
- Inserción de documentos en MongoDB
- Aggregation Pipeline con `$match`, `$group`, `$lookup`
- Consultas analíticas:
  - Top 5 libros más vendidos
  - Productos con mayor stock
  - Ventas por cliente y por autor
- Procedimientos de mantenimiento de datos
- Gestión de usuarios y roles con permisos diferenciados

## 🛠️ Tecnologías
- MongoDB
- MongoDB Compass
- JavaScript (consultas y agregaciones)
- NoSQL
