# Poliescol · Manual de marca (versión web)

Manual de marca vivo de Poliescol, pensado para que **cualquier persona o IA** pueda diseñar piezas alineadas con la marca, en especial para Gestión Humana.

**Sitio:** https://cipreslab.github.io/poliescol/

| Archivo | Para qué |
|---|---|
| `index.html` | Manual visual navegable |
| `brand.md` | Todas las reglas en texto (instrucciones para IA) |
| `tokens.json` | Valores exactos: color, tipografía, tamaños, formatos |
| `llms.txt` | Índice estándar para modelos de lenguaje |
| `css/tokens.css` | Variables CSS + fuentes |
| `plantillas/*.html` | Plantillas 1080×1350 de Gestión Humana (editar los elementos con `data-editar`) |
| `assets/` | Logos SVG oficiales, íconos de categoría, fuentes, aplicaciones |

## Cómo crear una pieza nueva desde una plantilla
1. Abre la plantilla en el navegador (por ejemplo `plantillas/bienvenida.html`).
2. Cambia los textos marcados con `data-editar` (y la foto, con `style="background-image:url(...)"` en el elemento `.foto`).
3. Exporta como imagen con una captura del área de 1080×1350 px, o pídele a una IA que lo haga.

## Tipografía
El manual define **Claris Sans** para titulares. Para web se usa **Outfit** (licencia SIL OFL, incluida en `assets/fonts`), su equivalente geométrico más cercano. Si Claris Sans está instalada en el equipo, se usa primero.

## Alcance
Esta versión pública contiene solo la identidad visual, el tono de voz y las plantillas. La estrategia interna del manual impreso (ADN, propuesta de valor) no se publica aquí.
