# inventory-api
API REST para gestión de inventario.

## Arquitectura del proyecto

El proyecto está organizado separando responsabilidades:

- `main.py`: inicia la aplicación.
- `database.py`: administra la conexión con la base de datos.
- `models.py`: define las entidades.
- `schemas.py`: valida los datos de entrada y salida.
- `crud.py`: contiene la lógica para acceder a los datos.
- `routers/`: define los endpoints de la API.

## Día 4

### ¿Qué aprendí?

- MySQL Server puede contener varias bases de datos.
- Una base de datos es un conjunto organizado de tablas.
- SQL es el lenguaje con el que damos instrucciones a MySQL.

### Mi primer comando SQL

```sql
CREATE DATABASE inventory_db;
