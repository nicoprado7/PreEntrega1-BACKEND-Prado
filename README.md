# Primera entrega - Curso de Backend

# Autor: Nicolás Prado

## Realización
Este proyecto fue realizado para proporcionar una solución backend para un sistema de e-commerce. Permite la gestión de productos y carritos de compra, con funcionalidades para agregar, actualizar, eliminar y listar productos, así como crear carritos y agregar productos a los carritos.

## Tecnologías empleadas
- **Node.js**: Entorno de ejecución para JavaScript.
- **Express**: Framework de Node.js para la construcción de aplicaciones web y API.
- **File System**: Utilizado para la persistencia de datos en archivos JSON.

## Endpoints
Productos
- GET /api/products/: Lista todos los productos.
- GET /api/products/
: Obtiene un producto por su ID.
- POST /api/products/: Crea un nuevo producto.
- PUT /api/products/
: Actualiza un producto existente.
- DELETE /api/products/
: Elimina un producto por su ID.

Carritos
- POST /api/carts/: Crea un nuevo carrito.
- GET /api/carts/
: Lista los productos de un carrito.
- POST /api/carts/
/product/
: Agrega un producto a un carrito.
