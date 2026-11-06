# Feedit

Genera feeds RSS desde páginas web o fuentes RSS/Atom y crea widgets personalizables para insertarlos en otras webs.

## Actualizar

Consulta `ACTUALIZAR.txt`. Reemplaza los archivos del repositorio en GitHub y confirma el cambio; Cloudflare despliega automáticamente la rama conectada. La vista previa utiliza el iframe real y cambia al modificar las opciones. Después de cambiar ajustes en Feedit, reemplaza en tu web el código iframe anterior por el nuevo para publicar esos cambios.

## Funciones

- Detección de feeds de WordPress, Substack, Medium, Blogger, Ghost, Tumblr y YouTube.
- Extracción de imágenes desde RSS y etiquetas HTML habituales, incluidas rutas lazy load, `srcset`, `media:content` y `enclosure`.
- Proxy de imágenes con caché y referencia del artículo para fuentes con protección contra hotlink.
- Siete diseños: muro, lista, carrusel, imágenes, cinta, revista y feed.
- Personalización de colores, cabecera, textos, velocidad, dirección, movimiento, número de entradas y visibilidad del sitio de origen.
- Vista previa y código insertable que se actualizan con los controles.
- Tarjetas con texto adaptable, widget responsive e iframe con ajuste automático de altura.
- Imágenes cargadas primero mediante el proxy y, si falla, directamente desde la fuente; las entradas sin imagen no intentan cargar la página del artículo como si fuera una foto.
- Vista previa del widget servida por el mismo iframe que se inserta, para que los ajustes se comprueben en el resultado real.

## Requisitos

Feedit se ejecuta en Cloudflare Workers. El Worker se llama `feedit`; GitHub almacena el código y Cloudflare despliega ese Worker.
