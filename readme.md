# PFO 1 Front - Portafolio Personal — Ailén Páez

Trabajo Práctico correspondiente a la **Práctica Formativa Obligatoria 1 (PFO1)** de la materia Frontend, IFTS N.º 29.
Se trata de una landing page de portafolio personal desarrollada con HTML5 y CSS3, publicada mediante Vercel.

- 🔗 [**URL publicada:**](https://pfo-1-front2026.vercel.app/)
* 📁 [**Repositorio GitHub.**](https://github.com/ailenpaez/PFO1-front2026)

---

## Descripción

Landing page que presenta información personal, habilidades técnicas, experiencia laboral, películas y series favoritas, una playlist de Spotify y un formulario de contacto respetandola consigna. Incluye modo oscuro/claro con persistencia en `localStorage`.

---

## Checklist — Práctica Formativa Obligatoria 1

### Estructura del Proyecto

- [x] Archivo `index.html` ubicado en la raíz
- [x] Carpeta `css` que contiene el archivo `styles.css`
- [x] Carpeta `img` para recursos gráficos
- [x] Archivo `README.md` creado, con descripción del TP y checklist

### Repositorio y Publicación

- [x] Repositorio en GitHub creado
- [x] Proyecto subido al repositorio
- [x] En el `README.md` se indica la URL de publicación

### Uso de Google Fonts

- [x] Enlace a Google Fonts incluido en la sección `head` del HTML
- [x] La tipografía importada se aplica en el sitio
- **Fuente elegida:** Ubuntu
- **¿Por qué?** Es una tipografía moderna, clara y con buena legibilidad tanto en títulos como en texto corrido. Además es la fuente que utilizo en VSC.

### HTML

- [x] El documento inicia con la declaración `DOCTYPE` y usa el atributo `lang="es"`
- [x] Se incluyen las metaetiquetas obligatorias: `charset` y `viewport`
- [x] Se define un título descriptivo: `Portafolio - Ailén Páez`
- [x] Se vinculan correctamente el archivo CSS y el enlace a Google Fonts
- [x] Barra de navegación (`nav`) presente con enlaces
- [x] Se insertaron al menos 4 comentarios explicativos en el código HTML

**Secciones obligatorias en `main`:**

- [x] Presentación personal (`id="sobre-mi"`) con párrafo e imagen
- [x] Tarjetas/columnas (`id="tarjetas"`) con 3 tarjetas en Flexbox
- [x] Listado de habilidades (`id="habilidades"`) con grilla de tecnologías
- [x] Formulario de contacto (`id="contacto"`) con nombre, apellido, email, teléfono y botón submit
- [x] Películas favoritas (`id="peliculas"`) con título e imagen por película

### CSS

- [x] Existe el archivo `styles.css` con estilos personalizados
- [x] Se utilizan selectores basados en clases e identificadores
- [x] La tipografía importada desde Google Fonts se aplica en todos los elementos

**Layout y Organización:**

- [x] Se organizó el layout con Flexbox en las secciones de tarjetas, skills, películas y series
- **¿Qué ventajas encontré al usar Flexbox?** Me permitió alinear y distribuir los elementos de forma sencilla sin necesidad de calcular anchos manualmente. Con `flex-wrap` las tarjetas se adaptan al tamaño de la pantalla automáticamente, lo que facilitó el diseño responsivo.

**Estilización de Componentes:**

- [x] Se personalizaron estilos de botones, enlaces y formularios
- [x] Se ajustaron dimensiones de imágenes y contenedores con unidades relativas (`%`, `rem`)
- [x] Se implementaron animaciones y transiciones

- **¿Qué animaciones implementé y por qué?**
  - `transform: translateY(-6px)` en hover de las skill cards: genera un efecto de elevación que resalta la interacción del usuario con las tecnologías.
  - `transform: scale(1.03)` en hover de las tarjetas de experiencia: indica visualmente que el elemento es interactivo.
  - `transform: scale(1.04)` en hover de imágenes de películas y series: sutil zoom que mejora la experiencia visual.
  - `transition` en el cambio de modo claro/oscuro: suaviza el cambio de colores en todo el body.

### Consideraciones Adicionales

- [x] El diseño es responsivo con `@media (max-width: 768px)`
- [x] Se aplicaron buenas prácticas de accesibilidad: atributo `alt` en todas las imágenes
- [x] Se añadieron comentarios en el HTML describiendo cada sección
- [x] Modo oscuro/claro implementado con `localStorage` para persistencia entre sesiones
- [x] Footer con enlaces a LinkedIn y GitHub

---

## Tecnologías utilizadas

- HTML5
- CSS3 (Flexbox, variables CSS, media queries, transiciones)
- Google Fonts — Ubuntu
- Devicon (íconos de tecnologías)
- JavaScript vanilla (toggle de tema)
- Vercel