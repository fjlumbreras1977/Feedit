# Dröma RSS Studio

Generador de feeds RSS desde páginas web o fuentes RSS/Atom, con widgets insertables, personalizables y responsive.

## Instalación rápida

Consulta `EMPIEZA-AQUI.txt`: contiene los pasos mínimos para subir el proyecto a GitHub y conectarlo con Cloudflare Workers.

## Funciones

- Detección de feeds de WordPress, Substack, Medium, Blogger, Ghost, Tumblr y YouTube.
- Extracción de imágenes y metadatos `media:content` en el RSS generado.
- Siete diseños de widget: muro, lista, carrusel, imágenes, cinta, revista y feed.
- Personalización de colores, cabeceras, textos, tamaño, número de entradas, movimiento y velocidad.
- Caché para reducir consultas repetidas y conservar la última respuesta válida ante límites temporales del sitio de origen.
- Diseño responsive para móvil y escritorio.

## Requisitos

La aplicación se ejecuta en Cloudflare Workers. GitHub almacena el código y Cloudflare lo publica. No está diseñada para instalarse subiendo archivos a un hosting PHP tradicional.
