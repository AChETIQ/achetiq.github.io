# Sección Simulaciones — archivos para el sitio oficial

Paquete generado el 2026-10-08 desde el repositorio de construcción `ingqcautnfrre-lab/achetiq-lab` (rama `claude/festive-gates-c0kbx5`, commit `8b066cd`), con `BASE_URL = "https://achetiq.github.io"`. Las URL canónicas, `og:url`, JSON-LD y `sitemap.xml` ya apuntan al sitio oficial.

## Contenido

La carpeta `archivos/` reproduce la estructura del repositorio: cada archivo va en la misma ruta dentro del repositorio oficial. Son 34 archivos: 21 nuevos y 13 modificados.

### Archivos nuevos (21)

- `assets/css/simuladores.css`
- `assets/js/materia-card.js`
- `assets/js/sim/absorcion.js`
- `assets/js/sim/acordeon.js`
- `assets/js/sim/armazon.js`
- `assets/js/sim/destilacion.js`
- `assets/js/sim/equilibrio.js`
- `assets/js/sim/esquema.js`
- `assets/js/sim/exportar.js`
- `assets/js/sim/grafico.js`
- `assets/js/sim/modelo-absorcion.js`
- `assets/js/sim/modelo-destilacion.js`
- `assets/js/sim/notacion.js`
- `assets/js/sim/numerico.js`
- `assets/js/sim/ui.js`
- `assets/js/simulaciones.js`
- `data/simulaciones.json`
- `docs/SIMULADORES.md`
- `pages/recursos/simulaciones.html`
- `pages/recursos/simulaciones/operaciones-unitarias-ii.html`
- `scripts/test-simuladores.mjs`

### Archivos modificados (13): reemplazan a los existentes

- `404.html`
- `assets/css/cards.css`
- `assets/css/main.bundle.css`
- `assets/css/recursos.css`
- `assets/js/apuntes.js`
- `data/navbar.json`
- `docs/DESIGN.md`
- `index.html`
- `package.json`
- `pages/recursos.html`
- `partials/footer.html`
- `sitemap.xml`
- `tokens.css`

**Advertencia.** Los archivos modificados se generaron a partir de la versión del sitio de construcción anterior a Simulaciones (commit `362f0f6`). Si en el repositorio oficial alguno de ellos tiene cambios propios posteriores, revisalos antes de sobrescribirlos: en particular `index.html`, `404.html`, `pages/recursos.html`, `assets/js/apuntes.js`, `assets/css/main.bundle.css`, `tokens.css` y `data/navbar.json`.

## Carga en GitHub (desde el navegador)

1. Descomprimir el ZIP.
2. En el repositorio oficial, abrir **Add file → Upload files**.
3. Arrastrar **el contenido** de la carpeta `archivos/` (las carpetas `assets`, `data`, `docs`, `pages`, `partials`, `scripts` y los archivos sueltos), no la carpeta `archivos` en sí. GitHub conserva la estructura de carpetas; son menos de 100 archivos, el límite de una carga.
4. Escribir un mensaje de commit (por ejemplo, «Recursos: sección Simulaciones con McCabe-Thiele para OU II») y confirmar.
5. Esperar la publicación de GitHub Pages y verificar `https://achetiq.github.io/pages/recursos/simulaciones`.

Este archivo (`LEEME.md`) no debe subirse.

## Opcional: regenerar con Node

Si el repositorio oficial tiene `site.config.mjs` con `BASE_URL = "https://achetiq.github.io"`, después de cargar los archivos se puede ejecutar `npm run build` y `npm run test:sim` (20 pruebas de los modelos). No es imprescindible: los archivos ya están generados para el dominio oficial.

## Verificación realizada

Se superpuso `archivos/` sobre una copia del sitio previa a Simulaciones, generada para `https://achetiq.github.io`. Se cargaron en Chromium el inicio, Recursos, Apuntes, el hub de Simulaciones y ambos simuladores: no hubo errores de consola, recursos faltantes ni violaciones de la política de seguridad (CSP).
