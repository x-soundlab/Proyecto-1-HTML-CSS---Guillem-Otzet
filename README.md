# Aynix.x Soundlab — Portfolio 🎛️🎶

Proyecto 1: **HTML + CSS** creado como presskit / portfolio para el proyecto **Aynix.x**.

La idea es tener una landing funcional donde se presentan:
- El proyecto y equipo (`Who we are`)
- Algunos trabajos seleccionados (`What we do`)
- Un formulario de contacto sencillo para colaborar o pedir info

---

## ✨ Estructura de la página

La web se compone de una sola página (`index.html`) dividida en secciones:

- **Header fijo**
  - Logo (arriba a la izquierda)
  - Menú de navegación con enlaces internos:
    - `welcome` (hero)
    - `who we are`
    - `what we do`
    - `contact`
  - En móvil el menú se convierte en un **burger menu** que despliega un panel flotante.

- **Hero**
  - Ocupa prácticamente el alto completo de la pantalla (`100vh` menos el header).
  - Imagen de fondo con ambientación del proyecto y logo central de Aynix.x.
  - Funciona como entrada visual limpia, sin texto adicional para no recargar.

- **Who we are**
  - Dos bloques (“Guillem” y “Fernando”) con estructura espejo:
    - Imagen vertical del artista con efecto de tarjeta flotante.
    - Bloque de texto con fondo oscuro tipo “glass” y borde suave.
    - Encabezados gráficos (`about-guillem-header.png` / `about-fernando-header.png`) que siguen la línea gráfica del proyecto.

- **What we do (Selected Works)**
  - Grid responsive de 4 tarjetas con portadas de temas y releases.
  - Cada tarjeta incluye:
    - Cover del tema / proyecto
    - Título
    - Descripción corta
    - Enlace externo (YouTube, Spotify, Beatport, Patreon…)

- **Contact + Footer**
  - Bloque central con un formulario:
    - Nombre
    - Email
    - Mensaje
    - Botón de envío
  - Integrado con [formsubmit.co](https://formsubmit.co/) mediante inputs ocultos.
  - Sección con fondo fotográfico muy difuminado para mantener legibilidad.
  - Footer con iconos enlazados a redes:
    - Instagram
    - SoundCloud
    - Spotify
    - YouTube

---

## 🧱 Tecnologías utilizadas

- **HTML5**
  - Estructura semántica:
    - `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
  - Enlaces internos mediante IDs para navegar por la misma página.
  - Imágenes con atributos `alt` descriptivos.
  - `h1` oculto con clase `visually-hidden` para SEO / accesibilidad sin romper el diseño.

- **CSS3**
  - Archivo único: `styles.css`
  - Uso de:
    - Variables CSS (`:root`) para colores, tipografías, sombras, radios, tamaños etc.
    - **Flexbox**:
      - Cabecera (logo + nav)
      - Hero (alinear logo)
      - Centrado del bloque de contacto
      - Footer y redes sociales
    - **CSS Grid**:
      - Layout de las secciones “Who we are”
      - Galería de trabajos (`What we do`)
      - Formulario de contacto
    - **Media queries** para adaptar el diseño:
      - `max-width: 900px` → menú burger, stack en vertical de los bloques, hero centrado.
      - `max-width: 600px` → tipografías y paddings ajustados para móviles pequeños.
    - Fondos con `background-image` y gradientes para:
      - Hero
      - Secciones “Who we are”
      - Sección de trabajos
      - Contacto

---

## 📁 Estructura del proyecto

```text
.
├─ index.html
├─ styles.css
└─ assets
   ├─ images
   │  ├─ ayni-logo-hero.png
   │  ├─ ayniport.png
   │  ├─ ayniport2.png
   │  ├─ about-guillem-header.png
   │  ├─ about-fernando-header.png
   │  ├─ bgcolor1fin.webp
   │  ├─ pandora-2025.webp
   │  ├─ about-club-1.webp
   │  ├─ CRI05266.jpg
   │  ├─ ttfw_fractal_COVER.jpg
   │  ├─ descarga.png
   │  ├─ caratulapsdV1.png
   │  └─ ... (resto de fondos / artworks que se usan en la web)
   └─ icons
      ├─ 1.png   (logo principal / también icono Instagram)
      ├─ 5.png   (Spotify)
      ├─ 9.png   (YouTube)
      ├─ 17.png  (SoundCloud)
      └─ ... (otros iconos si se añaden)