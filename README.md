# Mi Primer Sitio Web

Proyecto personal desarrollado con HTML y CSS, con diseño responsive mobile-first usando CSS Grid, Flexbox y Media Queries.

## Autora
Florencia Francos

## Tecnologías utilizadas
- HTML5
- CSS3 (Grid, Flexbox, Media Queries)

## Estructura del proyecto
```
├── index.html
├── styles.css
├── imagenes/
    ├── imagen.nena.jpg
    ├── logo.png
└── pages/
    ├── sobre-mi.html
    ├── contacto.html
    └── proyectos.html
```

## Páginas responsive completas
- `index.html`
- `pages/proyectos.html`
- `pages/sobre-mi.html`
- `pages/contacto.html`


## Características del diseño
- **Mobile-first**: el layout base (sin media queries) se apila al 100% del ancho.
- **CSS Grid con `grid-template-areas`**: usado en la sección de proyectos (`.proyectos`) para organizar la introducción y la lista de proyectos.
- **Diseño fluido**: uso de la unidad `fr` en las columnas de grid, sin anchos fijos en `px`.
- **Escalera responsiva** con dos media queries:
  - `min-width: 768px` (tablet): las listas de habilidades y proyectos pasan a 2 columnas.
  - `min-width: 1024px` (desktop): las secciones principales pasan a un layout de 2 columnas lado a lado.
- **Espaciado** consistente con `gap` en todos los contenedores de grid y flex.

## Cómo verlo
Abrí `index.html` en el navegador, o usá la extensión **Live Server** en VS Code para verlo con recarga automática.
