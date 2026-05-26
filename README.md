# Tazita de Barro

Sitio web estático para una cafetería de especialidad. El proyecto incluye tres páginas principales: `index.html`, `nosotros.html` y `testimonios.html`, usando HTML semántico, CSS y TailwindCSS CDN para un diseño moderno, accesible y responsivo.

## Estructura del proyecto

- `index.html` - página de inicio con servicios, menú, horarios y contacto.
- `nosotros.html` - historia, misión, visión y valores de la marca.
- `testimonios.html` - reseñas de clientes y casos de uso.
- `styles.css` - estilos personalizados para navegación, layout, accesibilidad y mobile-first.
- `*.webp` - imágenes optimizadas usadas en testimonios y sección de historia.

## Usabilidad

- Navegación sencilla con enlaces claros hacia `Inicio`, `Nuestra Historia`, `Servicios`, `Menú`, `Horarios`, `Testimonios` y `Contacto`.
- Enlace "Saltar al contenido" (`skip link`) para usuarios de teclado y lectores de pantalla.
- Enlaces y botones con estados `:focus` visibles para mejorar la navegación por teclado.
- Tipografía legible y contrastes adecuados para una lectura cómoda.
- Tablas de precios con `overflow-x-auto` para que funcionen bien en pantallas pequeñas.

## Diseño mobile-first

- El sitio está construido con un enfoque `mobile-first` usando estilos responsivos y media queries.
- El menú de navegación se adapta a pantallas pequeñas mediante un botón de toggle y columnas en stack.
- Las secciones se reordenan y redimensionan con `flex`, `grid` y porcentajes para mantener una presentación consistente en móviles y escritorio.
- Imágenes se cargan de forma `lazy` para optimizar rendimiento en dispositivos móviles.

## Accesibilidad

- Uso de etiquetas semánticas como `<main>`, `<header>`, `<nav>`, `<section>`, `<article>` y `<footer>`.
- Texto alternativo (`alt`) en todas las imágenes.
- El sitio soporta navegación por teclado y ofrece foco visual claro.
- Scroll suave para una experiencia más fluida.

## Tecnologías

- HTML5
- CSS3
- TailwindCSS CDN
- Imágenes WebP

## Cómo usar

1. Abrir `index.html` en tu navegador.
2. Navegar entre páginas con los enlaces del encabezado.
3. En dispositivos móviles, el diseño se adaptará automáticamente.

## Recomendaciones futuras

- Agregar un formulario de contacto funcional.
- Incluir validación de formularios y microinteracciones.
- Optimizar aún más las imágenes y mejorar el rendimiento con `preload` o `lazy-loading` adicional.
- Añadir un footer con enlaces a redes sociales y horarios de atención.
