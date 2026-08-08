## CRUD

Implementé las operaciones principales de la API:

- POST: crear productos.
- GET: consultar productos.
- PUT: actualizar productos.
- DELETE: eliminar productos.

También aprendí a utilizar:
- db.add()
- db.commit()
- db.refresh()
- db.delete()
- query()
- filter()
- first()
## Búsqueda de productos

Implementé búsqueda de productos por:

- Nombre
- Categoría
- Nombre y categoría simultáneamente

Utilicé `filter()` e `ilike()` de SQLAlchemy.

## Seguridad de credenciales

Problema:
La contraseña de MySQL estaba escrita directamente en database.py.

Solución:
Moví las credenciales a variables de entorno utilizando un archivo .env.

También agregué .env a .gitignore para evitar que las credenciales se
suban al repositorio.
