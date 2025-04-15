# Adóptame 🐾

Este proyecto es una landing page *One Page* responsive para la iniciativa **"Adóptame"**, que busca fomentar la adopción de mascotas. Está desarrollada en HTML y CSS puro, siguiendo el enfoque *Mobile First*.

## 🧩 Estructura del sitio

- **Encabezado** con logotipo SVG animado y navegación.
- **Presentación** con mensaje central y botón de llamada a la acción.a
- **Galería de mascotas** con ilustraciones SVG personalizadas de un gato y un perro.
- **Sección de acción** con botón animado para poder adoptar.
- **Footer** con créditos.

## 🖼️ SVG y Animaciones

- Todas las imágenes SVG están incrustadas en el HTML.
- Las ilustraciones fueron creadas en Figma y optimizadas para web.
- El gato tiene una animación de orejas mediante `@keyframes`.
- El perro utiliza `stroke-dasharray` y `stroke-dashoffset` para simular un trazo progresivo.
- El perro tiene sensación de estar respirando usando `transform: scaleY()` aplicada con `@keyframes`
- Animaciones adicionales incluyen:
  - Entrada suave de elementos.
  - Transiciones al pasar el cursor sobre enlaces y botones.
  - Animación del logo al cargar la página apareciendo por el lado izquierdo.

## 🎨 Diseño

- Paleta basada en tonos rosados (#d63c61) y verdes (#a4d6a7).
- Tipografía sans-serif (Arial) para claridad y accesibilidad.
- Diseño responsive adaptado a móvil, tablet y escritorio.

## 📂 Estructura de entrega

- `index.html`
- `styles.css`
- `/assets` → contiene los SVG originales exportados desde Figma.
- `README.md` (este archivo)
