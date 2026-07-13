# Nobodywhois0 — Portfolio

Personal developer portfolio. Dark theme, dotted grain background, lime accent, built with plain HTML, CSS and JavaScript — no frameworks, no build step.

**Live site:** https://nobodywhois0.github.io/portfolio/

Read this in [English](#english) or [Español](#español).

---

## English

### About

A single-page portfolio with four sections: Hero, About, Projects, and Contact. Includes a mobile nav menu, scroll-reveal animations, and a floating WhatsApp button.

### Tech stack

- HTML5
- CSS3 (custom properties, no preprocessor)
- Vanilla JavaScript (no dependencies)
- Fonts: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) & [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

### Project structure

```
.
├── index.html    # Markup and content
├── styles.css    # Theme, layout, animations
└── script.js     # Mobile menu + scroll-reveal
```

### Running locally

No build tools required. From the project root:

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173` in your browser.

### Deployment

Deployed automatically via **GitHub Pages** from the `main` branch, root directory. Any push to `main` updates the live site.

### License

Personal project — feel free to browse the code for reference, but please don't republish it as your own.

---

## Español

### Sobre el proyecto

Un portafolio de una sola página con cuatro secciones: Hero, Sobre mí, Proyectos y Contacto. Incluye menú de navegación móvil, animaciones al hacer scroll y un botón flotante de WhatsApp.

### Tecnologías

- HTML5
- CSS3 (variables personalizadas, sin preprocesador)
- JavaScript puro (sin dependencias)
- Fuentes: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) y [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) vía Google Fonts

### Estructura del proyecto

```
.
├── index.html    # Estructura y contenido
├── styles.css    # Tema, layout y animaciones
└── script.js     # Menú móvil + animaciones al hacer scroll
```

### Cómo correrlo localmente

No requiere herramientas de build. Desde la raíz del proyecto:

```bash
python3 -m http.server 4173
```

Luego abre `http://localhost:4173` en tu navegador.

### Despliegue

Se despliega automáticamente con **GitHub Pages** desde la rama `main`, directorio raíz. Cada push a `main` actualiza el sitio en producción.

### Licencia

Proyecto personal — siéntete libre de revisar el código como referencia, pero por favor no lo publiques como propio.
