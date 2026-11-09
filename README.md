# Proyecto MOVEA-SHOP

En el proyecto lo que estoy buscando es hacer una tienda online para una tienda de ropa deportiva destinada a chicas.

Hasta ahora hice la primera estructura con html con las etiquetas basicas como: <header>, <main>,<footer>,<h1>,<h2> tambien use: <section>, <article>, <figure>, etc

y el primer diseño con css, en donde use principalmente class para definir a que queria referirime a la hora de modificar.

## Estilos (actualmente)

Hice la migracion de css nativo a scss.
Los estilos propios se mantienen en scss, organizados en partials.
La estructura SCSS separa utilidades, estilos base, layout y componentes. Bootstrap y Font Awesome se cargan desde sus CDN en el HTML.

Actualmente el proyecto quiero terminarlo como un ecommerce solo que en lugar de un carrito donde agregas tus productos y haces el pago luego, por el momento seria una landing para hacer consultas de un producto o varios mediante un boton con el que los clientes consultan directamente por el producto que les interesa

## Mejoras de SEO

En esta etapa trabajé para que la página se encuentre más fácil en Google:

- A cada página le agregué una meta description: es un texto corto dentro del `<head>` que explica de qué trata la página y que Google muestra abajo del título en los resultados. Hice una distinta para cada página (inicio, productos, ofertas, nosotros y contacto).
- Cambié los títulos, que es lo que se ve en la pestaña del navegador. Antes decían cosas como "Movea-OFertas" y ahora dicen qué se puede encontrar en cada página, por ejemplo "Ofertas Movea | Ropa deportiva femenina con descuento".
- Ahora todas las páginas tienen un solo título principal . A contacto y ofertas les faltaba, así que lo agregué. Después vienen los <h2>, y así sigue en orden sin saltear niveles.
- En los títulos y textos usé palabras clave del rubro, como "ropa deportiva para mujeres", "buzos", "tops" y "joggers", pero tratando de que suene natural y sin repetirlas de más.
- Les cambié el nombre a las imágenes para que todas estén en minúscula y con guiones.

## link de Netlify

**https://moveafitt.netlify.app**
