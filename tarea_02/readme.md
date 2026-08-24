# 🚀 Proyecto Integrador: Diseña y Desarrolla tu Sitio Web WebMaster

¡Bienvenido/a al proyecto final del módulo de desarrollo web frontend! A lo largo de estas **3 semanas**, tendrás el desafío de planificar, diseñar y codificar desde cero un sitio web completo y profesional sobre una **temática de tu elección** (por ejemplo: un portfolio personal, un sitio para un negocio local, un blog de reseñas, un sitio de turismo, una landing page de un videojuego, etc.).

El objetivo es aplicar de manera integral y práctica todos los conceptos de **HTML semántico** y **CSS moderno** que hemos visto en clase.

---

## 🗂️ Estructura de Archivos Sugerida
Para mantener un código limpio y ordenado, tu proyecto deberá organizarse con la siguiente estructura de carpetas y archivos:

```text
mi-sitio-web/
│

├── pages/              # Carpeta que contiene las páginas secundarias
│   ├── index.html       # Página principal (Home)
│   ├── sobre-mi.html   # Ejemplo de página adicional (o servicios, productos, etc.)
│   └── contacto.html   # Página con formulario de contacto
├── css/
│   └── styles.css      # Archivo de estilos principal
└── assets/
└── images/         # Carpeta para imágenes y recursos multimedia
```

## 📌 Requisitos Generales del Proyecto

* **Código limpio y ordenado:** Utiliza una correcta indentación y comentarios explicativos en tu código.
* **Enfoque Mobile-First:** El sitio debe verse y funcionar perfectamente en dispositivos móviles y escalar con elegancia hacia pantallas de escritorio.
* **Tipografía y Paleta de Colores:** Define una identidad visual coherente utilizando variables CSS.
* **Trabajo Manual:** Todo el código HTML y CSS debe ser escrito de manera manual (prohibido el uso de frameworks CSS como Bootstrap o Tailwind).

---

## 🗓️ Plan de Trabajo (3 Semanas)

### 🟢 Semana 1: Estructura HTML y Contenido Semántico
**Objetivo:** Construir el esqueleto completo de tu sitio utilizando etiquetas HTML semánticas y asegurando una correcta jerarquía de la información.

#### Consignas de la Semana 1:
1. **Definición de la temática:** Elige de qué tratará tu sitio y realiza un pequeño esquema en papel o digital de sus secciones.
2. **Estructura Base (`index.html` y páginas adicionales):**
   * Tu sitio debe constar de al menos 2 o 3 páginas interconectadas (ej: Inicio, Sobre nosotros/Portfolio, Contacto).
3. **HTML Semántico:** Utiliza obligatoriamente las siguientes etiquetas donde corresponda:
   * `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`.
4. **Contenido Multimedia y Textual:**
   * Textos estructurados con títulos (`<h1>` a `<h6>`), párrafos (`<p>`), listas ordenadas y desordenadas (`<ul>`, `<ol>`, `<li>`).
   * Inclusión de imágenes (`<img>`) con sus respectivos atributos `alt` optimizados, y elementos multimedia si la temática lo requiere (videos o audios locales).
5. **Formulario de Contacto:**
   * En tu sección o página de contacto, implementa un formulario completo utilizando `<form>` que incluya diferentes tipos de `<input>` (texto, email, contraseña, número), áreas de texto (`<textarea>`), menús desplegables (`<select>` / `<option>`) y botones de envío (`<submit>`).
   * Asegúrate de utilizar etiquetas `<label>` asociadas correctamente a cada campo.

---

### 🟡 Semana 2: Estilos Base, Variables y Maquetación con CSS (Box Modeling, Flexbox y Grid)
**Objetivo:** Dar vida y diseño al esqueleto HTML, aplicando estéticas profesionales mediante la caja de modelos, sistemas de diseño flexibles y grillas.

#### Consignas de la Semana 2:
1. **Configuración y Variables CSS (`styles.css`):**
   * Configura un archivo de estilos externo y declara variables CSS (en `:root`) para tu paleta de colores principal, secundaria, colores de texto y tipografías.
2. **Modelo de Caja (Box Modeling):**
   * Aplica correctamente propiedades de `width`, `height`, `max-width`, `padding`, `margin` (incluyendo reseteo de márgenes por defecto con `box-sizing: border-box`).
   * Utiliza bordes (`border`, `border-radius`) y sombras (`box-shadow`) para dar profundidad a las tarjetas o contenedores.
3. **Tipografías y Fondos:**
   * Utiliza variantes completas de fuentes (familia, tamaño, peso `font-weight`, estilo `font-style`, alineación y altura de línea `line-height`).
   * Implementa variantes de fondo: colores sólidos utilizando las variables, imágenes de fondo con `background-image`, `background-size: cover`, `background-position`, y degradados (`linear-gradient`).
4. **Maquetación Avanzada:**
   * **Flexbox:** Utilízalo para alinear elementos en la barra de navegación (`<nav>`), centrar elementos, distribuir tarjetas o alinear elementos en el footer (`display: flex`, `justify-content`, `align-items`, `gap`, `flex-wrap`).
   * **CSS Grid:** Utiliza grillas para la estructura principal de contenidos o galerías complejas de imágenes (`display: grid`, `grid-template-columns`, `grid-template-rows`, `grid-gap`).

---

### 🔴 Semana 3: Interactividad, Pseudo-clases, Pseudo-elementos y Media Queries
**Objetivo:** Pulir la experiencia de usuario agregando interactividad visual y asegurando la adaptabilidad total a dispositivos móviles y tablets (Responsive Design).

#### Consignas de la Semana 3:
1. **Interactividad y Pseudo-clases:**
   * Implementa la pseudo-clase `:hover` en botones, enlaces y tarjetas para lograr efectos visuales atractivos al pasar el cursor (cambios de color, transformaciones sutiles con `transform`, o transiciones suaves con `transition`).
   * Utiliza pseudo-clases en el formulario de la Semana 1, como `:focus` en los inputs activos.
2. **Pseudo-elementos:**
   * Utiliza el pseudo-elemento `::placeholder` para personalizar el texto de ayuda dentro de los campos de texto del formulario.
   * Agrega elementos decorativos (como líneas, viñetas personalizadas o comillas) utilizando `::before` o `::after` en títulos clave de tu sitio.
3. **Diseño Responsivo (Media Queries):**
   * Implementa al menos dos puntos de quiebre (breakpoints) utilizando `@media queries` (por ejemplo, uno para tablets a partir de `768px` y otro para escritorios a partir de `1024px`).
   * Asegúrate de que los elementos que en mobile se apilan en una sola columna (usando Flexbox o Grid) pasen a distribuirse en filas o múltiples columnas en pantallas más grandes.
   * Verifica que no aparezcan barras de desplazamiento horizontal indeseadas en ningún dispositivo.

---

## 📋 Criterios de Evaluación

Tu proyecto será evaluado teniendo en cuenta los siguientes puntos:

- [ ] **Semántica HTML:** Uso correcto y lógico de las etiquetas estructurales.
- [ ] **Uso de CSS Moderno:** Aplicación limpia de Flexbox, Grid y Box Modeling sin errores de desbordamiento.
- [ ] **Implementación de Requisitos Obligatorios:** Presencia de variables CSS, pseudo-clases (`:hover`), pseudo-elementos (`::placeholder`), y adaptabilidad mediante Media Queries.
- [ ] **Diseño y Estética:** Armonía visual, legibilidad de tipografías, consistencia en la paleta de colores y prolijidad general.
- [ ] **Responsive Design:** Correcto funcionamiento y visualización fluida en celulares, tablets y computadoras de escritorio.

---

## 📅 Fecha de Entrega
* **Fecha límite:** Lunes 14 de septiembre.

---

¡Mucho éxito, manos a la obra y a codificar! 💻✨