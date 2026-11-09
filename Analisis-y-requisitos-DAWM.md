# Proyecto 01 de DAWM · Portafolio de identidad digital

Anthony Santana · ESPOL  
Consulta de fuentes públicas: 9 de noviembre de 2026

## 1. Análisis de perfiles

El [catálogo de referencia](https://github.com/abhisheknaiidu/awesome-github-profile-readme) incluye a Abhishek Naidu en GitHub Actions, a Martin Heinz en A Little Bit of Everything y a Caneco en Minimalistic. La lectura en móvil y la accesibilidad de los tres perfiles se evaluaron a partir de su Markdown y su estructura renderizada por GitHub.

### Abhishek Naidu

- **Primeros 10 segundos.** Se entiende que acepta consultas de trabajo independiente y que le interesan la automatización y el seguimiento de actividad. Su perfil se define como generalista. El README tarda en explicar qué construye y en qué tecnologías trabaja.
- **Estructura.** Abre con el correo para trabajo. Después muestra actividad semanal, un botón de apoyo, métricas de Todoist y estadísticas de GitHub. Usa texto y negritas como rótulos, con pocos encabezados semánticos.
- **Habilidades.** Las demuestra indirectamente mediante automatizaciones y lenguajes visibles en las tarjetas de repositorios. Faltan una agrupación explícita y un vínculo directo entre cada habilidad y su aplicación.
- **Proyectos.** La selección fijada incluye el catálogo de perfiles y la acción Todoist README. Las tarjetas de GitHub aportan más contexto técnico que el texto del README.
- **Contacto.** Ofrece un enlace de correo para trabajo independiente en la primera línea. GitHub muestra además su cuenta de X en los datos del perfil.
- **Lectura y accesibilidad.** En computadora se distinguen los bloques por el espacio y las imágenes. En móvil, las tarjetas de estadísticas pueden reducir el tamaño del texto y el bloque de código puede requerir desplazamiento si se amplía. El botón de apoyo tiene texto alternativo. El nombre de usuario como texto alternativo de la tarjeta estadística aporta poca información sobre los datos de la imagen.

[Perfil de Abhishek Naidu](https://github.com/abhisheknaiidu) · [Markdown fuente](https://github.com/abhisheknaiidu/abhisheknaiidu/blob/master/README.md)

### Martin Heinz

- **Primeros 10 segundos.** La introducción identifica a un desarrollador de software e ingeniero DevOps de Bratislava. La biografía de GitHub añade Python, Docker, Kubernetes y Go.
- **Estructura.** Presenta una cabecera gráfica, un título y una introducción. Sigue con tecnologías y herramientas, artículos y estadísticas de GitHub. La sección de artículos usa una lista de títulos descriptivos.
- **Habilidades.** Las insignias distinguen lenguajes, herramientas, entorno y nube. La agrupación orienta al lector, aunque las habilidades del README se transmiten principalmente como imágenes con alternativas vacías.
- **Proyectos.** Incluye tarjetas de Python Project Blueprint y Go Project Blueprint en el README y repositorios fijados como Tekton Kickstarter.
- **Contacto.** Enlaza su sitio personal, X y LinkedIn. El perfil también publica Mastodon, y el README enlaza Medium y DEV para leer sus artículos.
- **Lectura y accesibilidad.** En computadora se escanea bien gracias a los encabezados. En móvil, la cabecera, las filas de insignias y las tarjetas aumentan el recorrido vertical. Varias imágenes carecen de texto alternativo descriptivo, incluidas tarjetas de proyectos.

[Perfil de Martin Heinz](https://github.com/MartinHeinz) · [Markdown fuente](https://github.com/MartinHeinz/MartinHeinz/blob/master/README.md)

### Caneco

- **Primeros 10 segundos.** Se reconoce a un desarrollador full stack que contribuye a la comunidad Laravel. La mención a Medicare y Laracon EU aporta contexto profesional y comunitario.
- **Estructura.** Saludo, subtítulo con el rol, dos líneas de contexto y una lista breve sobre herramientas, comunidad, proyectos y temas de conversación. Comienza con encabezados de tercer y cuarto nivel.
- **Habilidades.** Usa texto con extensiones de archivo como PHP, JavaScript, HTML y CSS. El formato ocupa poco espacio, aunque los nombres completos de las herramientas serían más claros para lectores sin experiencia.
- **Proyectos.** Cita aportes de diseño para Pest y North Meets South. GitHub muestra también Design Tips y Laravel Country Logomarks.
- **Contacto.** La última viñeta indica sobre qué temas conversar. El sitio personal y los enlaces sociales están en los datos públicos del perfil.
- **Lectura y accesibilidad.** El README es breve y sus listas se ajustan bien a columnas estrechas. La jerarquía inicial de encabezados y algunos rótulos con emojis podrían resultar menos claros al navegar con lector de pantalla.

[Perfil de Caneco](https://github.com/caneco) · [Repositorio del perfil](https://github.com/caneco/caneco)

## 2. Análisis de repositorios

### awesome-github-profile-readme

- **Descripción y propósito.** Catálogo comunitario para descubrir perfiles de GitHub y técnicas de presentación. La descripción destaca la selección de perfiles y sus actualizaciones.
- **Topics.** `awesome`, `awesome-list`, `github`, `github-profile-readme`, `github-readme`, `portfolio` y `profile-readme`.
- **README e instrucciones.** Incluye índice, categorías, herramientas, artículos y tutoriales. La guía de contribución orienta cómo añadir ejemplos mediante un pull request. La consulta del catálogo se hace desde GitHub.
- **Tecnologías y recursos visuales.** Markdown, GitHub y automatización del repositorio. La portada usa un GIF en `assets/`, insignias y recursos externos.
- **Licencia, exclusiones y estructura.** CC0 1.0. La raíz de `master` tiene `README.md`, `LICENSE`, `contributing.md`, `.github/` y `assets/`. En esa raíz no hay `.gitignore`.
- **Historial y colaboración.** El commit `a2f2de4` integra el PR #1763 con ejemplos. Los issues #1880 y #1879 reportan enlaces rotos. Los PR #1890 y #1889 proponen añadir un perfil y una herramienta. La rama principal es `master`; también figuran `gh-pages` y ramas `all-contributors/*`. GitHub no muestra releases publicadas.

[Repositorio, archivos e historial](https://github.com/abhisheknaiidu/awesome-github-profile-readme) · [Issues](https://github.com/abhisheknaiidu/awesome-github-profile-readme/issues) · [Pull requests](https://github.com/abhisheknaiidu/awesome-github-profile-readme/pulls)

### todoist-readme

- **Descripción y propósito.** Acción que actualiza el README con estadísticas del usuario de Todoist.
- **Topics.** `github-actions`, `github-readme`, `time-tracker`, `todoist`, `todoist-api` y `todoist-tasks`.
- **README e instrucciones.** Explica cómo configurar el secreto `TODOIST_API_KEY`, delimitar el bloque de Markdown con comentarios y ejecutar un workflow programado. Distingue la configuración para cuentas con y sin Premium.
- **Tecnologías y recursos visuales.** JavaScript, Node.js, GitHub Actions y API de Todoist. Incluye una captura de las estadísticas en `assets/todoist-stat.png`.
- **Licencia, exclusiones y estructura.** CC0 1.0. La raíz contiene `action.yml`, `index.js`, `exec.js`, manifiestos de npm y documentación. `dist/` guarda la distribución y `assets/` el material visual. El `.gitignore` excluye dependencias, cachés, registros, cobertura y archivos `.env`.
- **Historial y colaboración.** El commit `8b83661` registra la migración de la API a v9. Los issues #21 y #18 tratan de ocultar estadísticas y de permisos de GitHub Actions. El PR #16 propone usar Sync API v9 y enviar el token por cabecera. Las ramas visibles son `master` y `dependabot/npm_and_yarn/actions/core-1.2.6`. GitHub muestra las releases `v0.0.9` y `v0.0.7`.

[Repositorio, archivos e historial](https://github.com/abhisheknaiidu/todoist-readme) · [Issues](https://github.com/abhisheknaiidu/todoist-readme/issues) · [Pull requests](https://github.com/abhisheknaiidu/todoist-readme/pulls) · [Releases](https://github.com/abhisheknaiidu/todoist-readme/releases)

### python-project-blueprint

- **Descripción y propósito.** Plantilla de arranque para proyectos Python con tareas de desarrollo, pruebas, empaquetado y despliegue.
- **Topics.** `blueprint`, `boilerplate`, `docker`, `kubernetes`, `python` y `template`.
- **README e instrucciones.** El inicio rápido lleva a la configuración del proyecto. Después explica la ejecución con Python o Docker, las pruebas con Make, la limpieza, el registro de paquetes, Kubernetes con KinD y SonarCloud.
- **Tecnologías y recursos visuales.** Python, Pytest, Make, Bash, Docker, Kubernetes y GitHub Actions. Usa insignias de compilación, cobertura y calidad y muestra salidas de terminal como referencia de uso.
- **Licencia, exclusiones y estructura.** MIT. `blueprint/` contiene el paquete, `tests/` las pruebas, `k8s/` los manifiestos y `.github/` la automatización. En la raíz quedan el `Makefile`, los Dockerfiles y la configuración de herramientas. El `.gitignore` excluye bytecode, entornos virtuales, cachés de pruebas, credenciales y certificados.
- **Historial y colaboración.** Los commits `8ab5e0d` y `1d8a89a` actualizan la documentación. El issue #37 informa un problema con la configuración inicial. El PR #36 propone actualizar Flask y el #8 añadió trabajo de Kubernetes. Se observan `master`, `grpc` y `dependabot/pip/flask-2.3.2`. GitHub muestra la release `0.0.6`.

[Repositorio, archivos e historial](https://github.com/MartinHeinz/python-project-blueprint) · [Issues](https://github.com/MartinHeinz/python-project-blueprint/issues) · [Pull requests](https://github.com/MartinHeinz/python-project-blueprint/pulls) · [Releases](https://github.com/MartinHeinz/python-project-blueprint/releases)

## 3. Requisitos funcionales

| ID | Requisito | Criterio de aceptación |
| --- | --- | --- |
| RF-01 | Identificar al autor y sus estudios. | El título muestra el nombre y la presentación identifica la carrera y ESPOL. |
| RF-02 | Comunicar intereses y tecnologías. | Las áreas y herramientas se agrupan en listas breves con nombres reconocibles. |
| RF-03 | Presentar los dos proyectos seleccionados. | Cada ficha identifica el propósito, las tecnologías y el alcance implementado. |
| RF-04 | Dar acceso al código y las demos. | Cada ficha enlaza su repositorio real. El Mercado enlaza su sitio publicado y el Dashboard se identifica como prototipo. |
| RF-05 | Facilitar el contacto. | La sección Contacto enlaza la cuenta pública de GitHub. |
| RF-06 | Publicar el portafolio y conservar el historial. | Un README en la raíz de un repositorio público homónimo aparece en el perfil y el historial registra cambios por etapa. |
| RF-07 | Publicar una URL de entrega para el sitio. | La publicación de GitHub Pages desde la raíz de `main` abre el mismo portafolio, según la Guía 01 de DAWM. |

## 4. Requisitos no funcionales

| ID | Requisito | Criterio de aceptación |
| --- | --- | --- |
| RNF-01 | Lectura rápida y orden. | Nombre y estudios al inicio, secciones de segundo nivel y un subtítulo por proyecto. |
| RNF-02 | Adaptación a móvil. | El contenido se lee en una columna de 360 a 390 píxeles sin desplazamiento horizontal. |
| RNF-03 | Accesibilidad. | Los títulos siguen un orden semántico, las listas son nativas y los enlaces identifican su destino. La información principal está en texto. |
| RNF-04 | Exactitud y enlaces funcionales. | Los enlaces abren destinos públicos comprobados y las fichas corresponden al código y la documentación. |
| RNF-05 | Mantenimiento sencillo. | El perfil y el sitio se alimentan de un solo README en Markdown, con secciones editables e historial de Git. |
| RNF-06 | Carga ligera. | La lectura funciona sin banners, insignias, fuentes personalizadas ni widgets externos. |

## 5. Decisiones de diseño

- De Caneco se toma la brevedad de las listas. De Martin Heinz, una introducción que comunica el rol de inmediato y una división clara por temas. Los proyectos se describen con texto y enlaces identificables, como complemento a las tarjetas de GitHub.
- La colección de perfiles muestra el valor de una estructura que se pueda escanear. Los reportes de enlaces rotos motivan la comprobación de destinos antes de publicar. Todoist README ejemplifica el mantenimiento que implica una automatización externa. El portafolio prioriza un documento de texto que pueda editarse directamente.
- Del repositorio de Python se toma la idea de explicar el propósito antes de enlazar al código. El orden del perfil es presentación, Sobre mí, áreas de interés, tecnologías, proyectos y contacto.
- El Mercado se documenta como trabajo en equipo de DAWM. Su sitio muestra el calendario, los stands, la galería y los resultados de las encuestas. El Dashboard se describe como prototipo adaptable con alertas de ejemplo. Su código deja el selector, los indicadores, el gráfico y la tabla como espacios previstos.
- El CV de DAWM conserva enlaces y recursos de muestra. Queda como candidato cuando tenga contenido definitivo. ProyectoBaseDatos contiene código Java pero carece de README, de modo que también queda fuera de la selección actual.
- La Guía 01 indica usar GitHub Pages desde la rama `main` del repositorio personal. GitHub Pages admite `README.md` como archivo de entrada. Así, los cambios se hacen una vez y aparecen en ambos destinos tras el despliegue.

[Mercado Nocturno, código](https://github.com/antivsan796/mercado-nocturno-artesanias) · [Mercado Nocturno, sitio publicado](https://antivsan796.github.io/mercado-nocturno-artesanias/) · [Dashboard del Clima, código](https://github.com/antivsan796/Dashboard)

[Proyecto 01 de DAWM](https://dawm2.readthedocs.io/es/latest/proyectos/proyecto01.html) · [Guía 01 de DAWM, GitHub Pages](https://dawm2.readthedocs.io/es/latest/guias/guia01.html#github-pages) · [Documentación de GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

## 6. Publicación y verificación

- El README aparece en el perfil de GitHub y el repositorio homónimo es público. Su rama predeterminada es `main`.
- La URL de GitHub Pages sirve el portafolio con respuesta HTTP 200. El sitio se genera desde la raíz de `main` usando el mismo `README.md`.
- Los cuatro enlaces del portafolio respondieron HTTP 200. Los dos repositorios y el sitio del Mercado coinciden con las fichas. El Dashboard carece de una demo pública verificada.
- La vista previa local del Markdown renderizado por GitHub se revisó a 320, 360 y 390 píxeles. El texto, los títulos y los enlaces se ajustaron a la columna sin desbordamiento horizontal.
- El historial público conserva cinco commits atribuidos a `antivsan796`. En cada commit se revisó el diff y solo se incluyó `README.md`.

**URL de entrega** · [Portafolio en GitHub Pages](https://antivsan796.github.io/antivsan796/)

[Perfil de GitHub](https://github.com/antivsan796) · [Repositorio público](https://github.com/antivsan796/antivsan796) · [Historial de commits](https://github.com/antivsan796/antivsan796/commits/main/)
