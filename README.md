# 🚀 Dev Resources & Awesome Libraries

> Colección personal y curada de librerías, componentes, motores de animación, conjuntos de iconos y recursos web indispensables para el desarrollo de proyectos modernos.

---

## 📌 Tabla de Contenidos

- [🎬 Animación & Interactividad](#-animación--interactividad)
- [🎨 Iconos, Avatares & Activos Visuales](#-iconos-avatares--activos-visuales)
- [🧩 Componentes & Frameworks UI](#-componentes--frameworks-ui)
- [🛠️ Utilidades & Herramientas](#️-utilidades--herramientas)
- [📝 Guía para Agregar Recursos](#-guía-para-agregar-recursos)

---

## 🎬 Animación & Interactividad

### [Anime.js](https://animejs.com/)
> *JavaScript Animation Engine* · [Repositorio GitHub](https://github.com/juliangarnier/anime)

Motor de animación en JavaScript extremadamente ligero, potente y con una API limpia y expresiva. Permite orquestar animaciones complejas sobre propiedades CSS, atributos individuales, SVG (incluyendo morphing y stroke animation) y objetos nativos de JavaScript.

- **Categoría:** Motor de animación JavaScript
- **Licencia:** MIT (Open Source)
- **Formatos / Entornos:** Vanilla JS, React, Vue, Svelte, Node / Bundlers
- **Casos de uso ideales:**
  - Microinteracciones avanzadas y timelines secuenciales.
  - Efectos cinemáticos, animaciones de entrada/salida y motion design interactivo.
  - Trazado y deformación de vectores SVG dinámicos.
- **Instalación rápida:**
  ```bash
  npm install animejs
  # o vía CDN
  # <script src="https://cdn.jsdelivr.net/npm/animejs@3.2.2/lib/anime.min.js"></script>
  ```
- **Etiquetas:** `Animation Engine` `JavaScript` `SVG Morphing` `CSS Animation` `Timelines`

---

## 🎨 Iconos, Avatares & Activos Visuales

### [4000+ Free High-quality Animated Icons](https://animatedicons.co/)
> *Colección premium y gratuita de iconos animados para interfaces web y móviles.*

Extenso catálogo interactivo con más de 4,000 iconos vectoriales animados organizados por categorías temáticas (sistemas, comunicación, finanzas, interfaces, multimedia y más). Cuentan con soporte nativo para Lottie y múltiples opciones de descarga para integrarse directamente en producción.

- **Categoría:** Biblioteca de iconos vectoriales animados
- **Formatos disponibles:** JSON (Lottie), GIF, MP4, After Effects (AEP)
- **Licencia:** Gratuito (Uso personal y comercial bajo atribución / términos del autor)
- **Casos de uso ideales:**
  - Indicadores de estado en tiempo real (éxito, error, sincronización, carga).
  - Microinteracciones dinámicas en botones, pestañas y llamadas a la acción.
  - Ilustraciones animadas para onboarding y estados vacíos (empty states).
- **Integración sugerida:**
  - Integrable directamente mediante reproductores Lottie como `lottie-web` o `@dotlottie/player-component`.
- **Etiquetas:** `Icons` `Animated Icons` `Lottie` `Microinteractions` `UI/UX Assets`

---

### [blobatar](https://blobatar.dev/)
> *Deterministic geometric blobatars* · [Repositorio GitHub](https://github.com/Alain00/blobatar)

Generador de avatares geométricos deterministas ultraligero (~4.4 KB gzipped) y con cero dependencias. A partir de cualquier cadena de texto (nombre de usuario, correo electrónico, ID o hash), produce un avatar SVG único, reproducible y visualmente orgánico con paletas cromáticas y formas geométricas balanceadas.

- **Categoría:** Generador de avatares deterministas / Gráficos SVG
- **Licencia:** MIT (Open Source)
- **Formatos / Entornos:** Vanilla JS / TS, React (`@blobatar/react`), Vue 3 (`@blobatar/vue`), Svelte (`@blobatar/svelte`), Solid (`@blobatar/solid`), Preact (`@blobatar/preact`), React Native (`@blobatar/react-native`)
- **Casos de uso ideales:**
  - Avatares por defecto (*fallbacks*) en perfiles de usuario cuando no hay foto de perfil cargada.
  - Identificadores visuales automáticos en sistemas de comentarios, chats o registros de auditoría.
  - Representación visual de usuarios en plataformas SaaS, paneles administrativos y foros.
- **Instalación rápida:**
  ```bash
  # Core
  npm install blobatar

  # O con adaptador para React
  npm install blobatar @blobatar/react
  ```
- **Ejemplo rápido (React):**
  ```tsx
  import { Blobatar } from "@blobatar/react";

  export function UserAvatar({ email }: { email: string }) {
    return <Blobatar name={email} size={48} />;
  }
  ```
- **Etiquetas:** `Avatars` `SVG` `Deterministic` `Zero Dependencies` `React` `Vue` `Svelte` `UI/UX`

---

## 🧩 Componentes & Frameworks UI

*Espacio reservado para bibliotecas de interfaz de usuario, sistemas de diseño y primitives accesibles (ej. Radix UI, Tailwind CSS, Lucide Icons, etc.).*

---

## 🛠️ Utilidades & Herramientas

*Espacio reservado para herramientas de optimización, generadores de código, librerías de manipulación de datos y utilidades web.*

---

## 📝 Guía para Agregar Recursos

Para mantener la calidad y consistencia del catálogo, cada nueva herramienta o librería debe registrarse con la siguiente estructura:

```markdown
### [Nombre del Recurso](URL_OFICIAL)
> *Subtítulo o lema breve* · [Repositorio GitHub si aplica](URL_REPO)

Descripción concisa de qué hace la librería y qué problema resuelve.

- **Categoría:** Tipo de herramienta (ej. Animación, UI, Utilidad)
- **Licencia:** (ej. MIT, Apache 2.0, Comercial)
- **Formatos / Entornos:** (ej. React, TypeScript, Lottie, Node.js)
- **Casos de uso ideales:**
  - Caso 1
  - Caso 2
- **Instalación rápida:**
  ```bash
  npm install nombre-paquete
  ```
- **Etiquetas:** `Tag1` `Tag2` `Tag3`
```

---

<div align="center">

Mantenido por [AlcsPower](https://github.com/AlcsPower) · Hecho para potenciar proyectos de desarrollo y diseño web.

</div>
