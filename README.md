# Aynix.x Soundlab — Portfolio 🎛️🎶

Proyecto 1: **HTML + CSS** creado como presskit / portfolio para el proyecto **Aynix.x**.

Landing de presentación donde se muestran:
- El proyecto y el equipo (`Who we are`)
- Una selección de trabajos (`What we do`)
- Un formulario de contacto funcional (`Contact`)

---

## ✨ Estructura de la página

El proyecto es una **single-page** (`index.html`) dividida en secciones principales:

---

### 🟣 **Header**
- Logo arriba a la izquierda.
- Navegación fija con enlaces internos:
  - welcome
  - who we are
  - what we do
  - contact
- En móvil → menú burger con panel flotante.

---

### 🎛️ **Hero**
- Pantalla completa (`100vh` menos header).
- Fondo ambientado + logo grande centrado a la izquierda.
- Funciona como entrada visual limpia.

---

### 🎤 **Who We Are**
Dos bloques tipo espejo:

#### **Guillem**
- Sound engineer, sound designer, integrador de audio, full-stack dev.
- Experiencia en Microfusa, Ledscontrol, Netflix ES, Ibiza Lights, Own Spirit, etc.
- Caja de texto tipo *glass* con sombra suave.
- Foto en formato tarjeta vertical.

#### **Fernando**
- Gestión de proyectos, bookings, producción de eventos.
- Mush Effect (Goa trance), fundador de Ohmnium Records.
- Producción en Own Spirit Festival.
- Layout invertido (imagen a la izquierda, texto a la derecha).

Cada bloque incluye:
- Imagen vertical
- Header gráfico personalizado
- Caja de texto semitransparente

---

### 🔥 **What We Do**

Incluye:
- **Banner gráfico grande** (recortado arriba/abajo) alineado al top.
- Título "WHAT WE DO – AYNIX.X" justo debajo.
- Grid responsive con 4 tarjetas:

1. **Aynix.x Live Set — Own Spirit Festival**  
   🎥 YouTube

2. **Time Travel Felt Weird — Fractal Joke & Aynix.x**  
   🎧 Spotify

3. **Replicant — Iboga Records (Rite of Passage)**  
   🎶 Beatport

4. **Support Us on Patreon**  
   💜 Patreon

Cada tarjeta:
- Imagen cuadrada
- Título
- Descripción corta
- Hover suave
- Redirección a plataformas externas

---

### 📬 **Contact + Redes**
Incluye:
- Formulario con:
  - Nombre
  - Email
  - Mensaje
  - Botón de envío
- Integra con **formsubmit.co** (sin JavaScript)
- Caja oscura para buena lectura sobre el fondo
- Debajo del formulario:
  - Título: "Follow Aynix.x on social media"
  - Iconos:
    - Instagram
    - SoundCloud
    - Spotify
    - YouTube

### **Footer**
- Línea final con © 2025 Aynix.x

---

## 🧱 Tecnologías utilizadas

### **HTML5**
- Semántica completa (`header`, `nav`, `section`, `article`, `footer`)
- Navegación interna por IDs
- Imágenes con `alt`
- `h1` oculto para accesibilidad sin romper diseño
- Formulario sin JS (solo HTML)

### **CSS3**
- Archivo único: `styles.css`
- Uso intenso de:
  - Variables CSS (colores, tipografías, sombras…)
  - Flexbox (header, hero, contacto, footer)
  - CSS Grid (Who we are, What we do, formulario)
  - Gradientes complejos:
    - Viñeta vertical
    - Viñeta izquierda/derecha
    - Overlays oscuros
  - Transiciones suaves
  - Diseño responsive:
    - `max-width: 900px`: menú móvil + layout en columna
    - `max-width: 600px`: ajustes de tipografía y márgenes

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
   │  ├─ what-we-do-banner.png
   │  ├─ bgcolor1fin.webp
   │  ├─ pandora-2025.webp
   │  ├─ about-club-1.webp
   │  ├─ CRI05266.jpg
   │  ├─ ttfw_fractal_COVER.jpg
   │  ├─ images.JPG
   │  ├─ caratulapsdkoan.png
   │  └─ (más imágenes usadas en fondos y secciones)
   └─ icons
      ├─ 1.png    (logo / Instagram)
      ├─ 5.png    (Spotify)
      ├─ 9.png    (YouTube)
      ├─ 17.png   (SoundCloud)
      └─ más iconos si se añaden