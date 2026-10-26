# Portfolio — Brian Tomadin

Estructura:
- `index.html` — todo el sitio (HTML + CSS + JS, sin build step)
- `img/` — screenshots de Custodial (web + app, datos de demostración)

Bilingüe ES/EN con toggle. Dark mode con cielo pixel art en SVG.

## Pendientes antes de publicar (buscá "TODO" en index.html)

- [ ] **TODO-FOTO** — tu foto en "Sobre mí". Guardala como `img/brian.jpg`
      (vertical 4:5, buena luz, fondo neutro — idealmente la misma de LinkedIn)
      y reemplazá el bloque `.me-photo` por:
      `<img class="me-photo" src="img/brian.jpg" alt="Brian Tomadin">`
- [ ] **TODO-REPO** — los botones de SpringBank y SwissRoute apuntan a tu
      perfil (github.com/Tomadin). Cambialos al repo exacto y revisá que cada
      repo tenga README presentable.

## Notas

- Los logos de tecnologías se cargan desde el CDN de devicon (jsdelivr).
  Es la única dependencia externa además de Google Fonts.
- Las capturas son de un entorno local con datos mockeados (la nota al pie
  de la galería lo aclara — eso te protege frente al contrato con el cliente).

## Cambiar idioma por defecto

En el `<script>` al final: `const DEFAULT_LANG = 'es';` → `'en'`.

## Deploy en GitHub Pages

1. Repo público `Tomadin.github.io`
2. Subí `index.html` + carpeta `img/`
3. Settings → Pages → branch `main`, carpeta `/ (root)`
4. Sitio en `https://tomadin.github.io`
