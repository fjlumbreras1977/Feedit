# Dröma RSS Studio

Generador de feeds RSS desde páginas web o fuentes RSS/Atom, con widgets insertables, personalizables y responsive.

## Funciones

- Detección de feeds en WordPress, Substack, Medium, Blogger, Ghost, Tumblr y YouTube.
- Extracción de imágenes y publicación de `media:content` en el RSS generado.
- Siete diseños de widget: muro, lista, carrusel, imágenes, cinta, revista y feed.
- Personalización de colores, cabeceras, textos, tamaño, número de entradas, movimiento y velocidad.
- Caché para limitar consultas repetidas y servir la última versión correcta cuando el origen limite temporalmente las peticiones.

## Publicar desde GitHub en Cloudflare Workers

Esta aplicación necesita el runtime de Cloudflare Workers; no basta con subir los archivos a un hosting PHP tradicional.

1. Sube el contenido de este repositorio a GitHub.
2. En Cloudflare, entra en **Workers & Pages** y crea una aplicación Worker conectada a Git.
3. Selecciona el repositorio y configura el despliegue con estos valores:
   - **Build command:** `npm install`
   - **Deploy command:** `npm run deploy`
   - **Root directory:** `/`
4. Guarda y despliega. Cloudflare usará `wrangler.toml` y `src/index.js`.
5. Al terminar, abre el dominio `*.workers.dev` asignado. Puedes configurar un dominio propio desde Cloudflare.

## Desarrollo local

Necesitas Node.js instalado. Ejecuta:

```bash
npm install
npx wrangler login
npm run dev
```

Para desplegar desde tu equipo:

```bash
npm run deploy
```

No requiere D1, R2 ni variables secretas para el funcionamiento básico. Los feeds y widgets deben servirse desde una URL pública para que otros sitios puedan insertarlos.
