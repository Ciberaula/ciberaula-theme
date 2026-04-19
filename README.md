# Ciberaula Theme

Tema Jekyll propio de **Ciberaula** para los sitios del proyecto GEO publicados en GitHub Pages. Construido como overlay sobre [just-the-docs](https://github.com/just-the-docs/just-the-docs) — conserva toda su funcionalidad (búsqueda, navegación, sitemap) y sobrescribe solo la capa visual para aplicar la identidad corporativa editorial de Ciberaula.

## Uso

En el `_config.yml` de tu sitio:

```yaml
remote_theme: Ciberaula/ciberaula-theme

plugins:
  - jekyll-remote-theme
  - jekyll-seo-tag
  - jekyll-sitemap
```

## Componentes editoriales

El tema añade las siguientes clases Markdown que puedes usar con `{: .nombre-clase}` tras un bloque:

- `.lead` — Entradilla de artículo (20px, borde izquierdo Coral).
- `.pull-quote` — Cita destacada en Plus Jakarta italic sobre fondo Navy.
- `.callout-info` / `.callout-warning` / `.callout-danger` — Cajas de aviso coloreadas.
- `.stat` — Tarjeta con una cifra grande en Coral.
- `.key-point` — Párrafo destacado con fondo Sage Light y borde izquierdo Sage.

## Paleta oficial aplicada

- **Navy** `#1B2A4A` — headings, links, marca.
- **Coral** `#E07A5F` — acentos, separadores, CTAs.
- **Sage** `#6B8F71` — proceso, éxito, callouts informativos.
- **Cream** `#FAFAF7` — fondo base (nunca blanco puro).

## Tipografía

- **Plus Jakarta Sans** (400/600/700) — hero H1, títulos de impacto.
- **Outfit** (400/500/600/700) — cuerpo, navegación, interfaz.
- **Georgia italic** — pull-quotes y elementos editoriales.

## Licencia

MIT License. Contenido de sitios construidos con este tema: cada sitio puede aplicar su propia licencia (habitualmente CC BY-SA 4.0 para contenido editorial de Ciberaula).

---

Mantenido por **Ana María González** · Directora de Ciberaula · © 2026
