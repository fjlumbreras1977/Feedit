# Feedit

Genera feeds RSS desde páginas web o fuentes RSS/Atom y crea widgets personalizables para insertarlos en otras webs.

## Actualizar el Worker

Consulta `ACTUALIZAR.txt`. Basta con reemplazar el contenido del repositorio en GitHub y confirmar el cambio. Cloudflare despliega la rama conectada automáticamente.

## Funciones

- Detección de feeds de WordPress, Substack, Medium, Blogger, Ghost, Tumblr y YouTube.
- Extracción de imágenes y metadatos `media:content` en el RSS.
- Siete diseños de widget: muro, lista, carrusel, imágenes, cinta, revista y feed.
- Personalización de colores, cabecera, textos, velocidad, dirección, movimiento y número de entradas.
- Vista previa y código insertable que se actualizan al cambiar los controles.
- Proxy de imágenes con caché para fuentes que bloquean la carga directa desde otros dominios.
- Widgets aislados en `iframe` y adaptables a móvil y escritorio.

## Requisitos

Feedit se ejecuta en Cloudflare Workers. GitHub almacena el código y Cloudflare despliega el Worker.
