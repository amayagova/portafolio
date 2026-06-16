# Portafolio - HENRY AMAYA

Portafolio web personal construido con [Astro](https://astro.build).

## Tecnologías

- **Astro** — Framework de construcción de sitios estáticos
- **CSS** — Variables, animaciones, tema claro/oscuro
- **astro-icon** — Iconos SVG de Simple Icons

## Estructura

```
src/
├── layouts/Layout.astro      # Layout base con meta, tema y observer
├── components/
│   ├── Header.astro          # Navegación + toggle de tema
│   ├── Hero.astro            # Presentación con foto y typing effect
│   ├── ProjectCard.astro     # Tarjeta de proyecto con tags e iconos
│   ├── Skills.astro          # Barras de habilidades animadas
│   ├── Contact.astro         # Sección de contacto
│   └── Footer.astro          # Pie de página
├── pages/
│   ├── index.astro           # Inicio (Hero + Skills + Contact)
│   ├── projects.astro        # Proyectos
│   └── about.astro           # Sobre mí
└── styles/global.css         # Estilos globales, tema y animaciones
public/                       # Assets estáticos (imágenes, favicon)
```

## Comandos

| Comando | Acción |
|---|---|
| `npm run dev` | Inicia servidor de desarrollo |
| `npm run build` | Construye para producción |
| `npm run preview` | Previsualiza la build |
