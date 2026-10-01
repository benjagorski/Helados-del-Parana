# Helados del Paraná

Sitio web de dos páginas para una heladería, hecho como **Trabajo Práctico N.º 1** de Programación III (UTN San Nicolás). Usa solo HTML y CSS, sin JavaScript ni frameworks.

- **Autor:** [Benjamin Gorski]
- **Sitio publicado:** []

## Páginas

- `index.html`: landing con header, portada (hero), "Sobre nosotros", formulario de contacto y footer.
- `productos.html`: grilla de 8 productos en tarjetas, agrupados en helados, postres y bebidas.

Las dos páginas comparten el mismo header, footer y hoja de estilos, y la navegación funciona entre ambas.

## Tecnologías

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `footer`).
- CSS3 en una hoja externa:
  - Flexbox en el header, el nav y el hero.
  - Grid en la grilla de productos.
  - Variables CSS (`:root`) para los colores.
  - Media queries con enfoque mobile-first.
  - Efectos `:hover` con transiciones.

## Formulario

El formulario de contacto solo está maquetado: no envía datos. Se valida con atributos HTML (`required` y `type="email"`).

## Estructura

```
heladeria/
├── index.html
├── productos.html
├── styles/
│   └── styles.css
├── img/
│   └── (imágenes y favicon)
└── README.md
```

## Cómo verlo

Descargá o cloná el repositorio y abrí `index.html` en el navegador. No necesita instalar nada.

## Imágenes

Las ilustraciones son archivos SVG hechos para este proyecto.
