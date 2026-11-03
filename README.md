# Catálogo Astro Gamer

Catálogo de consolas de Astro Gamer, Manizales (Local 9-33).
Se publica en Netlify: https://astro-gamer.netlify.app

- `index.html` es la página: diseño Halo, productos, precios y pedidos por
  WhatsApp (324 130 2844). Los productos viven en el bloque de datos
  `ag-data`, al final del archivo.
- `img/` tiene las fotos. Cada nombre lleva una huella, así que una foto
  nueva siempre tiene un nombre nuevo y el navegador puede guardarlas para
  siempre.
- `robots.txt` y `sitemap.xml` son para los buscadores.
- Cada cambio en la rama `main` actualiza el enlace automáticamente.

## Versiones

- **Halo** (actual): la versión aprobada. Portada con arte propio, sección
  "Elige cómo juegas", buscador, filtros, comparador y panel "Gestiona tu
  catálogo".
- **Versión anterior**: queda guardada en la rama `respaldo-v1`
  (commit `ae61723`). Para volver a ella:

      git checkout respaldo-v1 -- .
      git commit -m "Vuelvo a la version anterior"
      git push
