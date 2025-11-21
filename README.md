Aynix.x Soundlab — Portfolio 🎛️🎶

Proyecto 1: HTML + CSS creado como presskit / portfolio para el proyecto Aynix.x.

La idea es tener una landing funcional donde se presentan:

El proyecto y el equipo (Who we are)

Algunos trabajos seleccionados (What we do)

Un formulario de contacto sencillo para colaborar o pedir info

✨ Estructura de la página

La web se compone de una sola página (index.html) dividida en secciones:

Header fijo

Logo (arriba a la izquierda).

Menú de navegación con enlaces internos:

welcome (hero)

who we are

what we do

contact

En móvil el menú se convierte en un burger menu que despliega un panel flotante.

Hero

Ocupa prácticamente el alto completo de la pantalla (100vh menos el header).

Imagen de fondo con ambientación de Aynix.x y logo central.

Funciona como entrada visual limpia, sin texto adicional para no recargar.

Who we are

Dos bloques (“Guillem” y “Fernando”) con estructura espejo:

Imagen vertical del artista con efecto de tarjeta flotante.

Bloque de texto con fondo oscuro tipo glass y borde suave.

Encabezados gráficos (about-guillem-header.png / about-fernando-header.png) siguiendo la línea gráfica del proyecto.

Guillem: sound engineer, sound design, integración de audio y desarrollo full-stack.

Fernando: gestión de proyectos, bookings y producción de eventos (Own Spirit, Ohmnium Records, etc.).

What we do

Banner gráfico grande alineado al top de la sección.

Título corto debajo para mantener la jerarquía visual.

Grid responsive de 4 tarjetas con portadas de releases y proyectos:

Directo de Aynix.x en Own Spirit Festival (YouTube).

Time Travel Felt Weird con Fractal Joke (Spotify / Mad Cactus).

“Replicant” incluido en la compilación Rite of Passage de Iboga Records.

Enlace a Patreon con artwork original.

Cada tarjeta incluye:

Cover del tema / proyecto

Título

Descripción

Enlace externo

Contact + Footer

Bloque central con un formulario:

Nombre

Email

Mensaje

Botón de envío

Integrado con formsubmit.co
 mediante inputs ocultos.

Fondo fotográfico muy difuminado para mantener buena legibilidad.

Bloque adicional de redes sociales:

Follow Aynix.x on social media

Iconos de Instagram, SoundCloud, Spotify y YouTube.

Footer final con copyright.

🧱 Tecnologías utilizadas
HTML5

Estructura semántica completa:

header, nav, main, section, article, footer

Enlaces internos usando id en las secciones.

Imágenes optimizadas, con atributos alt descriptivos.

h1 oculto para accesibilidad y SEO sin romper el diseño.

Formulario básico sin JavaScript.

CSS3

Hoja de estilos única: styles.css

Uso de:

Variables CSS (:root) para colores, sombras, tipografías, radios, tamaños…

Flexbox en:

Cabecera

Hero

Contacto

Footer

CSS Grid en:

Secciones “Who we are”

Galería de “What we do”

Formulario de contacto

Fondos con gradientes + overlays diseñados para mejorar la lectura:

Viñetas verticales

Viñetas laterales izquierda/derecha según sección

Overlays oscuros para mejorar contraste en textos

Animaciones sutiles de “salto suave” en:

Fotos

Tarjetas

Navegación

Cajas de contenido

Media queries:

max-width: 900px: menú móvil, bloques en columna.

max-width: 600px: reajuste de tamaños y paddings.

📁 Estructura del proyecto
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
   │  └─ ... (resto de fondos/artworks usados en la web)
   └─ icons
      ├─ 1.png    (logo / Instagram)
      ├─ 5.png    (Spotify)
      ├─ 9.png    (YouTube)
      ├─ 17.png   (SoundCloud)
      └─ ... (otros iconos si se añaden)