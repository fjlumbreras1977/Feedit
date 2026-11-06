# Feedit

Genera feeds RSS desde páginas web o fuentes RSS/Atom y crea widgets personalizables para insertarlos en otras webs.

## Actualizar

Consulta `ACTUALIZAR.txt`. Reemplaza los archivos del repositorio en GitHub y confirma el cambio; Cloudflare despliega automáticamente la rama conectada. Después de cambiar las opciones del widget, reemplaza el código iframe anterior por el nuevo.

## Funciones

- Detección de feeds de WordPress, Substack, Medium, Blogger, Ghost, Tumblr y YouTube.
- Extracción de imágenes desde RSS y etiquetas HTML habituales, incluidas rutas lazy load, `srcset`, `media:content` y `enclosure`.
- Proxy de imágenes con caché y referencia del artículo para fuentes con protección contra hotlink.
- Siete diseños: muro, lista, carrusel, imágenes, cinta, revista y feed.
- Personalización de colores, cabecera, textos, velocidad, dirección, movimiento y número de entradas.
- Vista previa y código insertable que se actualizan con los controles.
- Tarjetas con texto adaptable, widget responsive e iframe con ajuste automático de altura.

## Requisitos

Feedit se ejecuta en Cloudflare Workers. El Worker se llama `feedit`; GitHub almacena el código y Cloudflare despliega ese Worker.
