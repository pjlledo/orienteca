# orienteca.es

**Biblioteca de recursos y utilidades para la orientación y la inclusión educativa.**

👉 **https://orienteca.es/**

Índice general (una sola página `index.html`, castellano/valenciano) que enlaza las herramientas.

## Añadir una herramienta

En `index.html`, copiar un bloque del array `TOOLS` con su `url`, `cat` (categoría, definidas en `CATS`) y los textos `es`/`va`. Subir el archivo y listo.

## Publicación

GitHub Pages (rama `main`, carpeta raíz) con el dominio propio `orienteca.es` (archivo `CNAME`). Se sirve desde GitHub y no a través del proxy de Cloudflare, porque este activa ECH y las redes con inspección de HTTPS (como la de la Conselleria) lo rechazan.

Licencia: EUPL-1.2.

Tipografía: [Atkinson Hyperlegible](https://www.brailleinstitute.org/freefont/) (Braille Institute), incrustada en `index.html` bajo licencia SIL OFL 1.1 (`OFL.txt`); no se carga nada de servidores externos.
