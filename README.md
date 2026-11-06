# Feedit

Genera feeds RSS desde páginas web o fuentes RSS/Atom y crea widgets personalizables para insertarlos en otras webs.

## Actualizar

Consulta `ACTUALIZAR.txt`. Reemplaza los archivos del repositorio en GitHub y confirma el cambio; Cloudflare despliega automáticamente la rama conectada. Tras cambiar las opciones del widget, vuelve a copiar el código de inserción y sustituye el iframe anterior en tu web.

## Funciones

- Detección de feeds de WordPress, Substack, Medium, Blogger, Ghost, Tumblr y YouTube.
- Extracción de imágenes y metadatos `media:content` en el RSS.
- Siete diseños de widget: muro, lista, carrusel, imágenes, cinta, revista y feed.
- Personalización de colores, cabecera, textos, velocidad, dirección, movimiento y número de entradas.
- Vista previa y código insertable que se actualizan al cambiar los controles.
- Proxy de imágenes con caché, cabecera de referencia del sitio fuente y reconocimiento de formatos comunes.
- Widgets aislados en `iframe` y adaptables a móvil y escritorio.

## Requisitos

Feedit se ejecuta en Cloudflare Workers. GitHub almacena el código y Cloudflare despliega el Worker.
