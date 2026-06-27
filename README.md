# El PAPI BARBER

Proyecto final: sitio institucional estático en HTML y SASS.

## Estructura del proyecto
- `index.html`
- `page/Nosotros.html`
- `page/Servicios.html`
- `page/Sucursal.html`
- `page/Galeria.html`
- `css/main.css`
- `sass/style.scss`
- `sass/partials/` (variables, mixins, reset, base, layout, pages, mediaq, etc.)

## Principales mejoras aplicadas
- Meta tags SEO: `description`, `keywords`, `author`, `robots`, `theme-color`
- Accesibilidad: `lang="es"`, `aria-label`, `aria-current`, `title` en iframe y `alt` descriptivos
- Rendimiento: `preconnect`, `preload`, `loading="lazy"` en imágenes, CDN Bootstrap
- SASS: uso de `@use`, `@mixin`, `@extend`, `@placeholder`, `@media` responsive, `variables`, nesting
- Estilos avanzados: transformaciones, transiciones y animaciones en componentes

## Cómo compilar estilos
1. Instalar Sass si no está disponible: `npm install -g sass`
2. Compilar:
   ```bash
   npx sass sass/style.scss css/main.css
   ```

## Comandos Git
```bash
git init
git add .
git commit -m "Initial deliverable with HTML, Sass, responsive styles, and accessibility improvements"
```

## Enlaces de entrega
- Repositorio GitHub: `https://github.com/ivancito2990/PROYECTOLABARBERIADELPAPILOVE.git`
- Sitio desplegado: `DEPLOY_URL_A_AÑADIR`

> Nota: El proyecto está publicado en GitHub. Conectar este repositorio a Netlify o Vercel para desplegarlo en vivo.
