# Capítulo V: Product Implementation, Validation & Deployment
## 5.1 Software Configuration Management
## 5.1.1 Software Development Environment Configuration
**Project Management:**

- HackMD.io
Plataforma en línea que permite la colaboración en la edición de documentos utilizando Markdown, facilitando la creación y edición conjunta de contenido de forma rápida y sencilla.
Ruta de referencia: [HackMD.io](https://hackmd.io/?nav=overview)

**Product UX/UI Design:**

- Figma
Herramienta de diseño de interfaz de usuario para crear prototipos interactivos y diseños de alta calidad.
Ruta de referencia: [Figma](https://www.figma.com/login)

- Edit.org
Herramienta para la creación de user personas para el proyecto
Ruta de referencia: [Edit.org](https://edit.org)

**Software Development:**

- Visual Studio Code
Editor de código fuente para el desarrollo de la landing page del proyecto.
Ruta de descarga: [Visual Studio Code](https://code.visualstudio.com)
- WebStorm
Entorno de desarrollo integrado (IDE) para el desarrollo futuro de la aplicación web utilizando Angular.
Ruta de descarga: [WebStorm](https://www.jetbrains.com/webstorm/download/#section=windows)
- IntelliJ IDEA
Entorno de desarrollo integrado (IDE) para el desarrollo futuro del backend de la aplicación web.
Ruta de descarga: [IntelliJ IDEA](https://www.jetbrains.com/idea/download/?section=windows)

**Software Deployment:**

- GitHub Pages
Plataforma de alojamiento estático para desplegar la landing page del proyecto.
Ruta de referencia: https://pages.github.com

**Version Control:**

- GitHub Desktop
Herramienta para gestionar y controlar versiones del proyecto en GitHub.
Ruta de descarga: https://desktop.github.com

## 5.1.2 Source Code Management
**Repositorios en Github:**
| Repositorio                         | URL                                            |
|-------------------------------------|------------------------------------------------|
| Landing Page Repository             | https://github.com/Final-Project-OpenSource/LandingPageFitHub      |
| Web Services Repository             |       |
| Frontend Web Applications Repository| |

**GitFlow Workflow:**

Se implementará el flujo de trabajo GitFlow, según lo descrito en el artículo "A successful Git branching model" de Vincent Driessen.
Branches creados:
- Main Branch (rama principal)
- Develop Branch (rama de desarrollo)
- Feature Branches (ramas de características): Se creará una rama para cada nueva característica y se nombrarán siguiendo las convenciones de Conventional Commits.
- Release Branches (ramas de lanzamiento): Se crearán para preparar nuevas versiones para el lanzamiento y se nombrarán utilizando Semantic Versioning.
- Hotfix Branches (ramas de corrección rápida): Se crearán para corregir errores críticos en producción y se nombrarán siguiendo las convenciones de Conventional Commits.

**Convenciones de Nombramiento:**

- Feature Branches: Se nombrarán utilizando el prefijo "feature/" seguido de una descripción corta y descriptiva de la característica.
- Release Branches: Se nombrarán utilizando el prefijo "release/" seguido de la versión en Semantic Versioning (por ejemplo, "release/1.0.0").
Hotfix Branches: Se nombrarán utilizando el prefijo "hotfix/" seguido de una descripción corta y descriptiva del error a corregir.

**Conventional Commits:**
Se utilizarán los mensajes de commit según las convenciones de Conventional Commits para mantener un registro claro y consistente de los cambios realizados en el proyecto. Esto facilitará la generación automática de registros de cambios y la gestión del proyecto en general.
## 5.1.3 Source Code Style Guide & Conventions
FitHub Pro - HTML Source Code Style Guide & Conventions

Este documento establece las convenciones y guías de estilo para el código fuente HTML utilizado en el desarrollo del sitio web FitHub Pro.

Indentación y Espaciado:

Utiliza una indentación consistente de 4 espacios para mejorar la legibilidad del código.
Usa espacios en lugar de tabulaciones para la indentación.
Comentarios:

Documenta secciones complejas o importantes del código con comentarios claros y concisos.
Utiliza comentarios para explicar la funcionalidad, el propósito o cualquier otra información relevante sobre el código.
Nombres de Clases y IDs:

Utiliza nombres de clases y IDs descriptivos que reflejen su propósito o función.
Sigue la convención de minúsculas y guiones ("-") para separar palabras en los nombres de clases (kebab-case).
Atributos de las Etiquetas:

Siempre rodea los valores de los atributos de las etiquetas con comillas dobles para garantizar la claridad y la consistencia del código.
Uso de Imágenes:

Utiliza imágenes relevantes y de alta calidad que mejoren la comprensión y la experiencia visual del usuario.
Enlaces y Botones:

Define claramente los enlaces y botones con texto descriptivo que indique la acción que realizarán.
Utiliza etiquetas "a" para enlaces y "button" para botones, según corresponda.
Formulario:

Estructura los formularios utilizando etiquetas semánticas como "label" para describir cada campo de entrada.
Mejora la accesibilidad y la usabilidad del formulario mediante una organización lógica y descriptiva.
Metaetiquetas:

Incluye metaetiquetas relevantes para mejorar el SEO del sitio web, lo que puede aumentar su visibilidad en los motores de búsqueda.
General:

Mantén el código limpio y legible, evitando líneas de código excesivamente largas o complejas.
Sigue las prácticas de codificación consistentes en todo el proyecto para facilitar la colaboración y el mantenimiento.
Este documento establece las pautas para garantizar la coherencia y la calidad del código HTML en el proyecto FitHub Pro. Se espera que todos los desarrolladores sigan estas convenciones al contribuir al código base del sitio web.

## 5.1.4 Software Deployment Configuration
En esta sección, describimos el proceso de despliegue de nuestra Landing Page utilizando GitHub Pages. Lo desplegamos desde la branch "main" siguiendo el flujo de trabajo GitFlow, asegurando así la estabilidad y la calidad de las implementaciones en producción.
### Deploy de la Landing Page:
<img src="/assets/img/capitulo5/Deploy-LP.png">

### Visualización de nuestra Landing Page desplegada:
<img src="/assets/img/capitulo5/Display-LP.png">


### Link de nuestra landing page:
https://final-project-opensource.github.io/LandingPageFitHub/
## 5.2 Landing Page, Services & Applications Implementation
## 5.2.1 Sprint n

## 5.2.1.1 Sprint Planning 1

|**Sprint**||
| :- | :- |
|Sprint Planning Background||
|Date|05/04/2023|
|Time|04:00 PM|
|Location|Servidor de Discord del Equipo|
|Prepared By|Ricardo Jesus Maguiña Corzo|
|Attendees (to planning meeting)|Ponce Loyola, Jorge Sebastian /Shimabukuro Uku, Carlos Joel / Cueto Dominguez, Juan Diego / Valenzuela Huillcaya, Aldhair Johan Juan / Maguiña Corzo, Ricardo Jesus|
|Sprint n Review Summary|En esta entrega, no hay un Sprint anterior, por lo tanto, no hay resúmen del Sprint.|
|Sprint n Retrospective Summary|En esta entrega, no hay un Sprint anterior, por lo tanto, no hay resúmen del Sprint.|
|Sprint Goal & User Stories||
|Sprint 1 Goal|La meta de este Sprint es la planificacion de la Landing Page, tanto su visualización, creacion del repositorio, acceso al repositorio y la visualización de los canales de comunicación de la empresa.|
|Sprint 1 Velocity|19 Velocity|
|Sum of Story Points|19 Story points|

## 5.2.1.2 Sprint Backlog n
## 5.2.1.3 Development Evidence for Sprint Review
## 5.2.1.4 Testing Suite Evidence for Sprint Review
## 5.2.1.5 Execution Evidence for Sprint Review
## 5.2.1.6 Services Documentation Evidence for Sprint Review
## 5.2.1.7 Software Deployment Evidence for Sprint Review
## 5.2.1.8 Team Collaboration Insights during Sprint

Comunicación efectiva: Observar cómo el equipo se comunica entre sí puede proporcionar información sobre la claridad y la eficiencia de la comunicación dentro del equipo. Una comunicación abierta y transparente es esencial para la colaboración exitosa.
Resolución de problemas: Durante el sprint, pueden surgir problemas y desafíos inesperados. La forma en que el equipo trabaja en conjunto para resolver estos problemas puede indicar su capacidad para enfrentar desafíos y adaptarse a situaciones cambiantes.
Apoyo mutuo: Observar cómo los miembros del equipo se apoyan entre sí puede revelar la fortaleza de las relaciones dentro del equipo y su capacidad para trabajar juntos hacia un objetivo común.
Creatividad e innovación: La colaboración efectiva a menudo fomenta la creatividad y la innovación. Observar cómo el equipo genera nuevas ideas y enfoques para abordar problemas puede proporcionar información valiosa sobre su capacidad para pensar de manera creativa y adaptarse a nuevas situaciones.
Toma de decisiones: Durante el sprint, el equipo puede enfrentarse a decisiones importantes que afectan el progreso del trabajo. Observar cómo el equipo toma decisiones colectivas puede proporcionar información sobre su capacidad para llegar a consensos y tomar decisiones informadas.

# Conclusiones y Recomendaciones
