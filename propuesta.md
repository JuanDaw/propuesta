% Sitio web de busqueda de productos de belleza "YourBeauty"
% JUan Antonio Villoria del Moral
% Curso 2020/21

# Descripción general del proyecto

YourBeauty será un sitio web de busqueda de productos de belleza que acercará estos mismos a todos los usuarios que quieran buscarlos sea cual sea su género.

Los usuarios podrán ver los productos más relevantes (más buscados o recomendados) o podrán utilizar el buscador como deseen (buscando por producto, por categoría de producto o por marca).

Los usuarios que lo deseen también podrán ofrecer sus productos en la misma página, creando así una sección de productos patrocinados.

## Funcionalidad principal de la aplicación

La funcionalidad principal será el motor de búsqueda de los productos para después redirigir al cliente a la página de compra oficial de ellos. Además se dará la opción al usuario de publicar sus propios productos en la página lo cuál creará una sección de productos patrocinados.

En la página principal aparecerá los productos destacados y relevantes, así como el motor de búsqueda de productos.

Los usuarios podrán registrarse, loguearse, valorar los productos, subir sus propios productos y añadir productos a favoritos.

Habrá un modo administrador para la gestión del sitio web, pudiendo crear, añadir, modificar o borrar productos. Además es el encargado de cribar las opiniones de los usuarios.

## Objetivos generales

- Objetivo: "Busqueda y publicación de productos (usuario), y gestión de productos (administrador)".
- Casos de uso:
  - Invitado: "registrarse", "buscar productos".
  - Usuario: "iniciar sesión", "cerrar sesión", "buscar productos", "añadir un producto a favorito", "quitar un producto de favorito", "ver su perfil", "modificar su perfil", "añadir un producto al sitio web", "quitar un producto del sitio web", "añadir un comentario en un producto", "editar un comentario de un producto", "quitar un comentario de un producto", "eliminar la cuenta".
  - Administrador: "iniciar sesión", "cerrar sesión", "crear productos", "añadir productos", "modificar productos", "borrar productos", "cribar opiniones".

# Elemento de innovación

- Uso de Amazon S3 para el almacenamiento de las fotos de productos.
- Multilenguaje (Español e Inglés).
