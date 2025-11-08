# sebviteri.github.io

Sitio personal de Sebastián Viteri publicado con GitHub Pages. La portada muestra el currículum y un resumen de las entradas del blog.

## Desarrollo local

1. Instala dependencias Jekyll (Ruby) si quieres compilar localmente: `bundle install`.
2. Ejecuta `bundle exec jekyll serve` para levantar el sitio en `http://localhost:4000`.
3. Alternativamente, usa `python3 -m http.server` si solo necesitas previsualizar el HTML estático.

## Estructura

- `index.html`: página principal (currículum + resumen del blog).
- `_posts/`: artículos del blog en formato Markdown.
- `blog/`: listado completo del blog.
- `_layouts/`: plantillas usadas por Jekyll.
- `style.css`: estilos compartidos.
- `cv/`: fuentes del currículum y recursos derivados.

## Publicación

Los cambios en `main` se publican automáticamente con GitHub Pages. Asegúrate de que los posts tengan nombre `YYYY-MM-DD-titulo.md` y encabezado YAML con `layout: post`.
