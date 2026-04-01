# 🏋️‍♂️ IronForge Fitness - Entrega Final

**IronForge Fitness** es una plataforma web de alto rendimiento para entusiastas del fitness. Este proyecto es una demostración de **maquetación profesional**, arquitectura de estilos escalable y optimización de experiencia de usuario (UX).

---

## 🚀 Demo
👉 **[Ver sitio en vivo aquí](https://dannygt0.github.io/ironforge-fitness/)**

---

## ✨ Características Principales (Pro Highlights)

Para elevar este proyecto al nivel de portafolio profesional, se implementaron las siguientes soluciones técnicas:

* **Arquitectura SASS 7-1 Modular:** Organización profesional de archivos para mantener un código limpio, mantenible y escalable.
* **Efecto Glassmorphism:** Navbar moderno con desenfoque de fondo (`backdrop-filter`) y transparencia, optimizado para legibilidad durante el scroll.
* **Micro-interacciones Dinámicas:**
    * Filtros inteligentes en la sección de Coaches (Blanco y Negro a Color en `hover`).
    * Transiciones suaves con `transform: scale` y efectos elásticos en botones.
* **Diseño "Mobile-First":** Totalmente responsivo utilizando el sistema de grillas de Bootstrap 5.3 y *media queries* personalizadas en SASS.
* **Optimización SEO & Performance:** Uso de etiquetas semánticas, metaetiquetas Open Graph (OG) y `lazy loading` en imágenes de alta resolución.

---

## 🛠️ Stack Tecnológico

* **HTML5**: Estructura semántica, accesibilidad (Roles ARIA) y SEO.
* **SASS (Modern SCSS)**:
    * **Variables & Maps:** Gestión centralizada de la paleta de colores y tipografías (Oswald & Roboto).
    * **Mixins & Extends:** Reutilización de lógica de centrado y efectos de transición.
    * **Nesting & Parent Selector:** Código más legible y específico.
    * **@use Pattern:** Implementación del sistema de módulos moderno de SASS.
* **Bootstrap 5.3**: Componentes avanzados (Navbar, Grid System, Cards, Dropdowns).
* **Google Fonts & Bootstrap Icons**: Tipografía premium e iconografía vectorial.

---

## 📂 Estructura del Proyecto (Clean Architecture)

```text
/
├── index.html          # Landing Page principal (SEO optimized)
├── /pages              # Secciones secundarias del sitio
│   ├── clases.html     # Catálogo de disciplinas y horarios
│   └── contacto.html   # Formulario de inscripción
├── /scss               # Arquitectura modular de estilos
│   ├── /base           # Variables, Reset, Tipografía y Mixins
│   ├── /components     # Navbar (Glassmorphism), Hero, Cards, Buttons
│   └── style.scss      # Archivo maestro de compilación
├── /css                # Estilos transpilados finales (style.css)
├── /assets             # Recursos del proyecto
│   ├── /img            # Imágenes optimizadas y Favicon
└── .gitignore          # Exclusión de archivos innecesarios