# 🎓 Rediseño del sitio web de la UNSIJ: carrera IDSSI

Propuesta de **rediseño web** para la carrera de **Ingeniería en Desarrollo de Software y Sistemas Inteligentes (IDSSI)** de la **Universidad de la Sierra Juárez (UNSIJ)**, en Ixtlán de Juárez, Oaxaca. Primero se diseñó la interfaz en **Figma** y después se programó con **HTML, CSS y JavaScript**.

> ⚠️ Proyecto académico (examen ordinario de Diseño Web). **No es el sitio oficial de la UNSIJ.**
>
> Equipo: [PENDIENTE: si fue trabajo en equipo, agrega aquí los nombres de tus compañeros]

🔗 **Demo en línea:** https://arumando.github.io/rediseno-web-unsij/

🎨 **Diseño en Figma:** [PENDIENTE: enlace público al archivo de Figma]

## ✨ Qué incluye

El sitio tiene **4 páginas** con un menú común:

| Página | Contenido |
|---|---|
| **Inicio** (`index.html`) | Presentación de la carrera, objetivo, misión, visión y **formulario de contacto** |
| **Plan de estudios** (`plan-estudios.html`) | Materias de los **9 semestres**, que se cargan dinámicamente al elegir un semestre; optativas y requisitos de titulación |
| **Áreas** (`areas.html`) | Áreas de especialización (IA, Software, Seguridad, Robótica) con **ventanas modales** de detalle y campos laborales |
| **Instalaciones** (`instalaciones.html`) | Laboratorios y salas de cómputo |

Funciones con JavaScript:
- **Plan de estudios dinámico**: las materias de cada semestre se generan desde un objeto de JavaScript, sin recargar la página.
- **Formulario de contacto con validación** y envío real mediante [Formspree](https://formspree.io/) usando `fetch` y `async/await`.
- **Clima en tiempo real de Ixtlán de Juárez** consultando la API pública [wttr.in](https://wttr.in/).
- **Modales** para ver el detalle de cada área de especialización.
- Diseño **responsive** con media queries e íconos de Font Awesome.

## 🛠️ Tecnologías

- **Figma**: diseño de la interfaz (UI) y prototipo
- **HTML5** y **CSS3**
- **JavaScript**: DOM, eventos, `fetch`, `async/await`
- APIs: Formspree (formulario) y wttr.in (clima)
- Font Awesome (íconos)
- GitHub Pages (publicación)

## ▶️ Cómo ejecutarlo

```bash
git clone https://github.com/arumando/rediseno-web-unsij.git
cd rediseno-web-unsij
```

Abre `index.html` en tu navegador, o usa la extensión **Live Server** de VS Code. El formulario y el botón del clima necesitan conexión a internet.

## 📁 Estructura

```
├── index.html            # Inicio
├── plan-estudios.html    # Plan de estudios
├── areas.html            # Áreas de especialización
├── instalaciones.html    # Instalaciones
├── css/style.css         # Estilos
├── js/main.js            # Interactividad
└── img/                  # Logo e imágenes
```

## 📸 Capturas

[PENDIENTE: captura del diseño en Figma]

[PENDIENTE: captura de la página de inicio]

[PENDIENTE: captura del plan de estudios dinámico]

[PENDIENTE: captura en celular]

## 📚 Qué aprendí

<!-- Revisa esta lista y escríbela con tus propias palabras. -->
- Pasar de un diseño en Figma a código HTML y CSS respetando la propuesta visual.
- Organizar un sitio de varias páginas con un menú y estilos compartidos.
- Generar contenido dinámico con JavaScript manipulando el DOM.
- Consumir APIs externas con `fetch` y `async/await` y manejar errores de conexión.
- Publicar un sitio gratis con GitHub Pages.

## 👤 Autor

**José Armando García Bandera** — [github.com/arumando](https://github.com/arumando)
