# DML
# Práctica de Operaciones DML en SQLite

Este repositorio contiene un script SQL diseñado para simular tareas comunes de un Analista de Datos utilizando SQLite, aplicando de forma segura operaciones DML (Data Manipulation Language).

## Estructura del Proyecto

- **`practica_dml.db`**: Base de datos SQLite generada durante la práctica.
- **`script_dml.sql`**: Archivo con las sentencias SQL organizadas por etapas.
- **`README.md`**: Documentación del proyecto.

## Descripción de las Tareas Resueltas

1. **Preparación y Consulta (`SELECT`)**: 
   - Se crea la estructura de la tabla `vendedores` con sus respectivos tipos de datos y restricciones (`PRIMARY KEY`, `AUTOINCREMENT`).
   - Se implementa una consulta filtrando por la zona `'Norte'` para extraer métricas específicas de nombre y ventas.
2. **Expansión (`INSERT`)**: 
   - Se incorporan nuevos registros de manera unitaria y masiva para simular el ingreso de nueva información comercial al sistema.
3. **Mantenimiento (`UPDATE`)**: 
   - Se actualizan registros específicos utilizando cláusulas `WHERE` estrictas (modificando métricas de ventas por ID y relocalizando zonas comerciales para aquellos que superan el umbral de 10,000 en ventas).
4. **Limpieza (`DELETE`)**: 
   - Se remueven datos transitorios de prueba y se valida la integridad de la tabla mediante un `SELECT` final.
