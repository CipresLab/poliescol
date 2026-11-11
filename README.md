# Poliescol · Sitio web

Sitio de una sola página para Poliescol, construido sobre el Manual de Marca 2024.
HTML + CSS estático, sin dependencias: listo para publicar en GitHub Pages.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `poliescol-web`).
2. Sube todo el contenido de esta carpeta a la rama `main` (incluido el archivo oculto `.nojekyll`).
3. En el repo ve a **Settings → Pages**.
4. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
5. En 1–2 minutos el sitio queda en `https://<usuario>.github.io/poliescol-web/`.

### Dominio propio (www.poliescol.com)
En **Settings → Pages → Custom domain** escribe `www.poliescol.com`. Luego, en el DNS del dominio,
crea un registro `CNAME` de `www` apuntando a `<usuario>.github.io`. Activa **Enforce HTTPS** cuando aparezca.

## Estructura

```
index.html              página completa (estilos y script incluidos)
assets/logo-blanco.svg  logotipo vectorial para fondos oscuros
assets/logo-negro.svg   logotipo vectorial para fondos claros
assets/icono.svg        ícono "ventana de luz" (favicon)
assets/ic-*.png         íconos de categoría: automotriz, arquitectónico, metalmecánico, madera
```

## Sistema de marca aplicado

| Rol | Color | HEX | Pantone |
|---|---|---|---|
| Primario | Negro | `#000000` | Process Black C |
| Complementario 1 · Automotriz | Verde limón | `#B5FF04` | 389C |
| Complementario 2 · Arquitectónico | Azul agua marina | `#20F9F5` | 319C |
| Complementario 3 · Metalmecánico | Violeta | `#741DEC` | 814C |
| Complementario 4 · Madera | Naranja | `#FF621D` | 1585C |

Tipografía: **Claris Sans** para titulares (hoy sustituida en web por *Fredoka* hasta tener la licencia webfont),
**Roboto Black** para copys y **Roboto** para textos.

## Pendientes antes de lanzar

- Validar con Poliescol los datos de contacto y el número de WhatsApp (316 834 09 26).
- Confirmar los productos destacados y sus descripciones; agregar fotos de producto cuando existan.
- Si se adquiere la licencia web de Claris Sans, cargarla con `@font-face` (la variable `--titular` ya la prioriza).
