# Currículum Vitae — Cristian Lorca Silva

Currículum web personal, hecho con HTML y CSS puro (sin frameworks ni dependencias).

## Estructura del proyecto

```
.
├── index.html          # El currículum completo (estructura/contenido)
├── css/
│   └── styles.css      # Todos los estilos
├── assets/
│   ├── cristian.jpg    # Foto de perfil
│   └── icons/
│       ├── pentaho.svg # Ícono propio de Pentaho
│       └── json.svg    # Ícono propio de JSON
└── README.md           # Este archivo
```

## Cómo verlo

Abre el archivo `index.html` con doble clic en cualquier navegador (Chrome, Edge, Firefox).
No necesitas instalar nada ni levantar un servidor.

## Cómo editarlo

Todo el **contenido** (textos, datos, proyectos, etc.) está en `index.html`.
Toda la **apariencia** (colores, tamaños, espacios) está en `css/styles.css`.

### Cambios rápidos más comunes

| Quiero cambiar… | Dónde |
|---|---|
| Mi nombre, perfil, datos, proyectos | `index.html` (busca el texto a cambiar) |
| Colores del diseño | `css/styles.css`, en `:root` (las variables `--accent`, `--bg`, etc.) |
| Mi foto | Reemplaza `assets/cristian.jpg` por otra con el mismo nombre |
| Enlaces de WhatsApp / LinkedIn / GitHub | `index.html`, en los `href="..."` de los botones |

### Agregar una herramienta nueva

En `index.html`, dentro de `<div class="tools-grid">`, copia un bloque `<div class="tool">…</div>`
y cambia la URL del ícono y el nombre. Los íconos vienen de
[Devicon](https://devicon.dev/) (vía CDN).

### Agregar un proyecto nuevo

En `index.html`, dentro de `<div class="projects-grid">`, copia un bloque
`<div class="project">…</div>` y edita el título, la descripción y la insignia
(`badge-solo` para individual, `badge-team` para trabajos en equipo).

## Exportar a PDF

Abre `index.html` en el navegador → `Ctrl + P` → "Guardar como PDF".
La hoja de estilos ya incluye reglas de impresión.

## Notas

- Las tipografías (Google Fonts) y la mayoría de los íconos de tecnologías se
  cargan desde internet, así que para verse perfecto conviene tener conexión.
- Los íconos `pentaho.svg` y `json.svg` son locales porque no existen en Devicon.
