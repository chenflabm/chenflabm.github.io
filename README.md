# Gremial de Huleros de Guatemala — sitio web

Sitio de una sola página (bilingüe ES/EN) listo para publicar.

## Publicar en GitHub Pages

1. Crear un repositorio nuevo en GitHub.
2. Subir el contenido de esta carpeta a la raíz del repositorio (`index.html` debe quedar en la raíz).
3. En el repositorio: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `root`** y guardar.
4. En 1–2 minutos el sitio queda en `https://USUARIO.github.io/REPOSITORIO/`.

También funciona igual en Netlify, Vercel o Cloudflare Pages (arrastrar la carpeta).

## Archivos

- `index.html` — el sitio completo, autocontenido. No necesita servidor, build ni conexión: se puede abrir con doble clic. Es el único archivo necesario para publicar.
- `source/` — los archivos de trabajo, para editar el sitio más adelante:
  - `Gremial de Huleros.dc.html` — el sitio. Todos los textos están en el objeto `CONTENT` al inicio del archivo, con español e inglés lado a lado.
  - `map.html` — el mapa interactivo de regiones productoras.
  - `support.js` — runtime necesario para la versión de trabajo.
  - `_ds/` — el sistema de diseño (colores, tipografías, componentes).

`source/` no es necesario para que el sitio funcione, pero conviene conservarlo en el repositorio.

## Pendientes de contenido

Los datos marcados en tipografía monoespaciada son provisionales y deben reemplazarse:
precios de referencia, noticias, eventos, nombres de junta directiva y datos de contacto.
El desglose de hectáreas por departamento es una estimación.
