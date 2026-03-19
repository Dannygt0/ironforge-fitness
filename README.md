# 🏋️‍♂️ IronForge Fitness - Entrega Final

**IronForge Fitness** es una plataforma web moderna diseñada para un gimnasio de alto rendimiento. El proyecto se enfoca en una experiencia de usuario fluida, diseño responsivo y una arquitectura de estilos escalable.

---

## 🚀 Demo
Puedes ver el sitio en vivo aquí: [https://dannygt0.github.io/ironforge-fitness/](https://dannygt0.github.io/ironforge-fitness/)

---

## 🛠️ Tecnologías Utilizadas

* **HTML5**: Estructura semántica para SEO y accesibilidad.
* **SASS (Syntactically Awesome Style Sheets)**: 
    * Uso de **Variables** para gestión de colores y fuentes.
    * **Mixins** para reutilización de código (Flexbox, transiciones).
    * **Operadores y @each** para la generación dinámica de clases de utilidades.
    * **Arquitectura de carpetas** (Base, Layout, Components).
* **Bootstrap 5.3**: Implementación de Sistema de Grillas, Navbars, Cards y utilidades de espaciado.
* **Git & GitHub**: Control de versiones y despliegue automatizado.

---

## 📂 Estructura del Proyecto

```text
/
├── index.html          # Página de inicio (Hero, Staff, Footer)
├── /pages              # Directorio de secciones secundarias
│   ├── clases.html     # Catálogo de disciplinas
│   └── contacto.html   # Formulario de inscripción
├── /scss               # Código fuente de estilos (Preprocesador)
│   ├── /base           # Variables, Reset y Mixins
│   ├── /layout         # Header, Nav y Footer
│   └── /components     # Cards de profes, Hero y Secciones
├── /css                # Estilos finales compilados (CSS nativo)
└── /img                # Recursos visuales y assets (Opcional)