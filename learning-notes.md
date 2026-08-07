# Dia 1 

## Aprendí 

- Qué es una API.
- Qué hace FastAPI.
- Qué es un endpoint.
- Qué significa una petición GET.
- Cómo iniciar un servidor con Uvicorn.
- Cómo acceder a la documentación automática en `/docs`.

## Dudas 

- ¿Cómo funciona realmente el decorador `@app.get`?
- ¿Por qué FastAPI convierte un diccionario en JSON 

## Día 2

### Conceptos aprendidos

- Modelo
- Arquitectura del proyecto
- Separación de responsabilidades
- CRUD

### Lo que entendí

Antes de escribir código es importante diseñar la estructura del proyecto para que sea más fácil de mantener cuando crezca.

## Día 4

### ¿Qué aprendí?

- MySQL Server puede contener varias bases de datos.
- Una base de datos es un conjunto organizado de tablas.
- SQL es el lenguaje con el que damos instrucciones a MySQL.

### Mi primer comando SQL

```sql
CREATE DATABASE inventory_db;

## Models vs Schemas

### Models
Representan las tablas de la base de datos y utilizan SQLAlchemy.

### Schemas
Representan los datos que la API recibe y devuelve. Utilizan Pydantic para validar la información antes de llegar a la base de datos.

## PUT vs DELETE

PUT se utiliza para actualizar un recurso existente.

DELETE se utiliza para eliminar un recurso existente.

Ambos utilizan el ID del producto para localizar el registro.
## Query Parameters

Los query parameters permiten enviar filtros o parámetros en la URL.

Ejemplo:

GET /products/search?nombre=laptop

FastAPI puede recibirlos como parámetros de la función.

## Parámetros de ruta vs Query Parameters

Parámetro de ruta:

GET /products/5

El ID forma parte de la ruta.

Query parameter:

GET /products/search?nombre=laptop

El filtro se encuentra después de `?`.
