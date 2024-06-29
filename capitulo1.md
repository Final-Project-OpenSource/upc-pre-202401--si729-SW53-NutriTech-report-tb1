feature-tb1
![Logo UPC](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)
## Universidad Peruana de Ciencias Aplicadas
## FACULTAD DE INGENIERÍA
### Desarrollo de Aplicaciones Open Source
**Sección:** SW53

**Docente:** Elio Navarrete

### Informe del Trabajo Final

**Nombre del Startup:** NutriTech

**Nombre del Producto:** FitHub Pro

**Integrantes:**

  - Ponce Loyola, Jorge Sebastian - U202120471
  - Shimabukuro Uku, Carlos Joel - U201912407
  - Cueto Dominguez, Juan Diego - U202012207
  - Valenzuela Huillcaya, Aldhair Johan Juan - U20201F572
  - Maguiña Corzo, Ricardo Jesus - U202121858 

*Abril de 2024*

---

**Registro de Versiones del Informe:**
En esta sección se resumen todas las modificaciones relevantes que sean realizadas sobre el informe durante el ciclo de vida del proyecto.

| Versión | Fecha    | Autor  | Descripción de modificación |
|---------|----------|--------|-----------------------------|
| TB1     | 13/04/24 | Grupo2 | Entregable TB1              |  
| TP1     | 02/05/24 | Grupo2 | Entregable TP1              |
| TB2     | 08/06/24 | Grupo2 | Entregable TB2              |
| TF1     | 23/06/24 | Grupo2 | Entregable TF1              |

---

## ÍNDICE

[1. **Capítulo I: Introducción**](#Capítulo-I:-Introducción)
 
   - [1.1. Startup Profile](##1.1.-Startup-Profile)
     - [1.1.1. Descripción de la Startup](###1.1.1.-Descripción-de-la-Startup)
     - [1.1.2. Perfiles de integrantes del equipo](###1.1.2.-Perfiles-de-integrantes-del-equipo)
   - [1.2. Solution Profile](##1.2.-Solution-Profile)
     - [1.2.1. Antecedentes y problemática](###1.2.1.-Antecedentes-y-problemática)
     - [1.2.2. Lean UX Process](###1.2.2.-Lean-UX-Process)
       - [1.2.2.1. Lean UX Problem Statements](####1.2.2.1.-Lean-UX-Problem-Statements)
       - [1.2.2.2. Lean UX Assumptions](####1.2.2.2.-Lean-UX-Assumptions)
       - [1.2.2.3. Lean UX Hypothesis Statements](####1.2.2.3.-Lean-UX-Hypothesis-Statements)
       - [1.2.2.4. Lean UX Canvas](####1.2.2.4.-Lean-UX-Canvas)
   - [1.3. Segmento Objetivo](##1.3.-Segmento-Objetivo)

[2. **Capítulo II: Requirements Elicitation & Analysis**](#Capítulo-II:-Requirements-Elicitation-&amp-Analysis)
 
   - [2.1. Competidores](##2.1.-Competidores)
     - [2.1.1. Análisis Competitivo](###2.1.1.-Análisis-Competitivo)
     - [2.1.2. Estrategias y tácticas frente a competidores](###2.1.2.-Estrategias-y-tácticas-frente-a-competidores)
   - [2.2. Entrevistas](##2.2.-Entrevistas)
     - [2.2.1. Diseño de entrevistas](###2.2.1.-Diseño-de-entrevistas)
     - [2.2.2. Registro de entrevistas](###2.2.2.-Registro-de-entrevistas)
     - [2.2.3. Análisis de entrevistas](###2.2.3.-Análisis-de-entrevistas)
   - [2.3. Needfinding](##2.3.-Needfinding)
     - [2.3.1. User Personas](###2.3.1.-User-Personas)
     - [2.3.2. User Task Matrix](###2.3.2.-User-Task-Matrix)
     - [2.3.3. User Journey Mapping](###2.3.3.-User-Journey-Mapping)
     - [2.3.4. Empathy Mapping](###2.3.4.-Empathy-Mapping)
     - [2.3.5. As-is Scenario Mapping](###2.3.5.-As-is-Scenario-Mapping)
   - [2.4. Ubiquitous Language](##2.4.-Ubiquitous-Language)

3. **Capítulo III: Requirements Specification**
   
   - 3.1. To-Be Scenario Mapping
   - 3.2. User Stories
   - 3.3. Impact Mapping
   - 3.4. Product Backlog

4. **Capítulo IV: Product UX/UI Design**
   
   - 4.1. Style Guidelines
     - 4.1.1. General Style Guidelines
     - 4.1.2. Web Style Guidelines
   - 4.2. Informations Architecture
     - 4.2.1. Organization Systems
     - 4.2.2. Labelling Systems
     - 4.2.3. SEO Tags and Meta Tags
     - 4.2.4. Searching Systems.
     - 4.2.5. Navigation Systems.
   - 4.3. Landing Page UI Design
     - 4.3.1. Landing Page Wireframe
     - 4.3.2. Landing Page Mock-up
   - 4.4. Web Applications UX/UI Design
     - 4.4.1. Web Applications Wireframes
     - 4.4.2. Web Applications Wireflow Diagrams
     - 4.4.3. Web Applications Mock-Ups
     - 4.4.4. Web Applications User Flow Diagrams
   - 4.5. Web Applications Prototyping
   - 4.6. Domain-Driven Software Architecture
     - 4.6.1. Software Architecture Context Diagram.
     - 4.6.2. Software Architecture Container Diagrams.
     - 4.6.3. Software Architecture Components Diagrams
   - 4.7. Software Object-Oriented Design
     - 4.7.1. Class Diagrams.
     - 4.7.2. Class Dictionary
   - 4.8. Database Design.
     - 4.8.1 Database Diagrams.

5. **Capítulo V: Product Implementation, Validation & Deployment**
   
   - 5.1. Software Configuration Management.
     - 5.1.1. Software Development Environment Configuration.
     - 5.1.2. Source Code Management.
     - 5.1.3. Source Code Style Guide & Conventions.
     - 5.1.4. Software Deployment Configuration.
   - 5.2. Landing Page, Services & Applications Implementation.
     - 5.2.1. Sprint 1
       - 5.2.1.1. Sprint Planning 1.
       - 5.2.1.2. Sprint Backlog 1.
       - 5.2.1.3. Development Evidence for Sprint Review.
       - 5.2.1.4. Testing Suite Evidence for Sprint Review
       - 5.2.1.5. Execution Evidence for Sprint Review.
       - 5.2.1.6. Services Documentation Evidence for Sprint Review.
       - 5.2.1.7. Software Deployment Evidence for Sprint Review.
       - 5.2.1.8. Team Collaboration Insights during Sprint.
   - 5.3. Validation Interviews.
     - 5.3.1. Diseño de Entrevistas
     - 5.3.2. Registro de Entrevistas
     - 5.3.3. Evaluaciones según heurísticas
   - 5.4. Video About-the-Product

**Conclusiones**

- Conclusiones y Recomendaciones
- Video About-The-Team

**Anexos**

**Bibliografía**

---

### LISTA DE FIGURAS

- Figura 1. Presentación del Lean UX Canvas referente a nuestro proyecto.
- Figura 2. Imagen de presentación de la primera entrevista realizada.
- Figura 3. Imagen de presentación de la segunda entrevista realizada.
- Figura 4. Imagen de presentación de la tercera entrevista realizada.
- Figura 5. Primer User Persona desarrollado para el segmento de mercado de Lufo.
- Figura 6. Segundo User Persona desarrollado para el segmento de mercado de Lufo.	
- Figura 7. Modelo de User Journey Mapping de nuestro primer user persona seleccionado.	
- Figura 8. Modelo de User Journey Mapping de nuestro segundo user persona seleccionado.	
- Figura 9. Empathy Map del primer user persona desarrollado.
- Figura 10. Empathy Map del segundo user persona desarrollado
- Figura 11. Impact Mapping de los dos user persona del proyecto.

---

### LISTA DE TABLAS

- Tabla 1. Presentación del modelo de las preguntas 5Ws y 2Hs con la que se analizaron los antecedentes y la problemática que abarca nuestro proyecto.
- Tabla 2. Análisis Competitivo organizado para todos los competidores potenciales de Lufo. 
- Tabla 3. Modelo de User Task Matrix definido para los dos user persona seleccionados.
- Tabla 4. Mapa de Escenario As-Is para nuestro primer user persona.
- Tabla 5. Mapa de Escenario As-Is para nuestro segundo user persona.
- Tabla 6. Mapa de Escenario To-Be para nuestro primer user persona.
- Tabla 7. Mapa de Escenario To-Be para nuestro segundo user persona.
- Tabla 8. Tabla de épicas establecidas para las historias de usuarios.
- Tabla 9. Tabla del Product Backlog organizado para las historias de usuario establecidas.

---

**Student Outcome**

En la carrera de Ingeniería de Software, el logro del curso contribuye a alcanzar el **ABET – EAC - Student Outcome 5**.

“La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos ”

En la siguiente sección se describen las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro mencionado.




| Criterio específico                                                                                                                                  | Acciones Realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Jorge Sebastian Ponce Loyola**<br> - **TB1**:<br>Durante la TB1, hemos logrado comunicar oralmente nuestras ideas en las diversas reuniones que tuvimos como equipo. Adaptamos el lenguaje y el niuvel de detalle según lo esperado presentando ideas claras y concisas, utilizando datos geograficos para respaldar los puntos claves. <br><br> -**TP1**: <br> Durante el TP1, hemos evidenciado mejoras significativas en la comunicación oral dentro de nuestro equipo, lo cual se refleja en nuestro notable progreso en el reporte hasta este punto del curso. Además, hemos demostrado habilidad para explicar nuestras ideas de manera clara y precisa, fundamentadas en los principios de ingeniería que hemos aprendido a lo largo de nuestra carrera.<br><br> -**TB2**: <br> Durante el TB2, hemos mejorado nuestra capacidad para comunicar objetivamente ideas y resultados a diversos públicos en nuestro proyecto de ingeniería. Nos hemos centrado en el desarrollo del backend de nuestra plataforma y en cumplir con las user stories definidas. Adaptamos nuestro lenguaje y detalle según las necesidades específicas de cada audiencia, asegurando una comunicación efectiva que respalda nuestro progreso y logros en el proyecto.<br><br> -**TF1**:<br> Durante este TF, hemos mejorado nuestra comunicación objetiva de los avances y resultados en nuestro proyecto de ingeniería. Completamos el desarrollo del backend y su integración con el frontend de la plataforma, marcando un hito significativo. Adaptamos nuestro mensaje según las necesidades específicas de cada grupo, asegurando una comunicación clara y efectiva.<br><br>  **Juan Diego Cueto Dominguez**<br> - **TB1**: <br> Durante la TB1, conseguimos transmitir nuestras ideas de manera efectiva en las distintas reuniones del equipo. Adaptamos nuestro lenguaje y nivel de detalle según las expectativas, presentando conceptos claros y concisos, y apoyándonos en datos geográficos para reforzar los puntos principales.<br><br> -**TP1**: <br>Durante el TP1, hemos experimentado un notable avance en nuestra capacidad de comunicación oral como equipo, lo cual ha contribuido significativamente a nuestro progreso en el reporte hasta la fecha actual del curso. Además, hemos demostrado competencia al explicar nuestras ideas de manera clara y estructurada, aplicando los principios y esquemas de ingeniería adquiridos durante nuestra formación académica. Estas mejoras no solo fortalecen nuestra colaboración interna, sino que también enriquecen la calidad y la precisión de nuestro trabajo en el proyecto. <br><br> **- TB2**:<br> Durante el TB2, hemos mejorado nuestra habilidad para comunicar de manera objetiva nuestros avances y resultados a diferentes públicos en nuestro proyecto de ingeniería. Nos hemos centrado en desarrollar el backend de nuestra plataforma y cumplir con las user stories establecidas, ajustando nuestro enfoque según las necesidades específicas de cada audiencia para garantizar una comunicación clara y efectiva. <br><br> **- TF1**:<br> Durante el TF1, hemos demostrado habilidades avanzadas en la comunicación objetiva de los progresos y resultados de nuestro proyecto. Completamos con éxito el desarrollo del backend y su integración completa con el frontend, adaptando nuestra presentación según las necesidades específicas de cada audiencia para asegurar una transmisión clara y efectiva de la información técnica y estratégica.</br><br> **Carlos Joel Shimabukuro Uku**<br> - **TB1**: <br>Para este trabajo, en las diversas reuniones del equipo, logramos expresar nuestras ideas de manera clara. Presentamos conceptos de manera precisa y concisa, ajustando el lenguaje y el nivel de detalle según lo requerido, y fortalecimos los puntos clave con datos geográficos. <br><br>  - **TP1**: <br> Durante el desarrollo del TP1, hemos fortalecido nuestra capacidad de comunicación oral como equipo, lo que ha impulsado notablemente nuestro progreso en el reporte hasta la fecha. Además, hemos demostrado competencia al expresar nuestras ideas de manera clara y coherente, fundamentadas en los principios de ingeniería que hemos adquirido durante nuestra formación académica. Estas mejoras no solo enriquecen nuestra colaboración interna, sino que también elevan la calidad y precisión de nuestro trabajo en el proyecto.<br><br>  - **TB2**: <br> Durante el desarrollo del proyecto, mejoramos la comunicación objetiva de nuestros avances y resultados en el proyecto de ingeniería. Nos centramos en desarrollar el backend de la plataforma y cumplir con las historias de usuario. Adaptamos nuestro enfoque según las necesidades de cada grupo, utilizando un lenguaje técnico adecuado para asegurar una comprensión clara de nuestros logros y progresos. <br><br> -**TF1**:<br>Durante el TF, mejoramos nuestra habilidad para comunicar eficazmente los avances técnicos y estratégicos de nuestro proyecto. Logramos integrar exitosamente el backend con el frontend, resaltando este logro clave en nuestro progreso. Adaptamos nuestra presentación para asegurar claridad ante diferentes audiencias, facilitando la comprensión y el apoyo hacia nuestros objetivos.</br><br> **Aldhair Johan Juan Valenzuela Huillcaya**<br> - **TB1**: <br> Durante mi participación en la TB1, comunicamos nuestras ideas y resultados de manera objetiva a un público diverso en las reuniones del equipo. Adaptamos el lenguaje y el nivel de detalle según las especialidades y niveles jerárquicos de los participantes, presentando conceptos claros y concisos, y respaldándolos con datos geográficos para fortalecer los puntos clave. <br><br> -**TP1**: <br>Durante este ciclo de desarrollo, fortalecimos nuestra habilidad de comunicación oral como equipo, fundamental para avanzar en el reporte. Mejoramos en la presentación de ideas complejas y adaptamos nuestro discurso según la audiencia, utilizando principios de ingeniería para argumentar de manera efectiva. Además, cultivamos un ambiente colaborativo donde integramos diversas opiniones para enriquecer nuestras soluciones. Esta mejora no solo optimiza nuestro trabajo diario, sino que también fortalece nuestra capacidad para enfrentar desafíos técnicos y estratégicos con seguridad y eficacia. <br><br>**- TB2:** <br>Durante mi participacion en el TB2, hemos mejorado la forma en que comunicamos de manera precisa los avances y resultados de nuestro proyecto de ingeniería. Nuestro enfoque se centró en el desarrollo del backend de la plataforma y en satisfacer las historias de usuario definidas. Ajustamos nuestro enfoque según las necesidades específicas de cada grupo, empleando un lenguaje técnico adecuado para garantizar una comprensión clara y detallada de nuestros logros y progresos.<br><br> -**TF1**:<br> Durante el TF, hemos consolidado nuestra capacidad para presentar de manera efectiva los avances y resultados técnicos de nuestro proyecto. Hemos completado la integración exitosa del backend con el frontend, destacando este hito crucial en nuestro desarrollo. Adaptamos nuestra comunicación para asegurar claridad y comprensión ante audiencias diversas, facilitando el apoyo y entendimiento hacia nuestros objetivos estratégicos.</br><br> **Ricardo Jesus Maguiña Corzo**<br> - **TB1**:<br>Durante la TB1, en el contexto del desarrollo de nuestro proyecto de ingeniería, hemos logrado comunicar de manera imparcial nuestras ideas y resultados a audiencias variadas en reuniones clave. Nos adaptamos al perfil y nivel de experiencia de cada grupo, empleando un lenguaje accesible y presentaciones estructuradas que incluyen datos relevantes para respaldar nuestros argumentos de manera efectiva.<br><br>  -**TP1**:<brDurante el TP1, mejoramos significativamente nuestra comunicación oral como equipo, crucial para avanzar en el reporte. Nos enfocamos en presentar ideas complejas de manera clara y efectiva, adaptando nuestro discurso según la audiencia y respaldando nuestros argumentos con principios de ingeniería. Fomentamos un ambiente colaborativo donde la integración de diversas perspectivas enriqueció nuestras soluciones, optimizando nuestra eficiencia y capacidad para abordar desafíos técnicos y estratégicos con confianza. <br><br>**TB2**: <br> Durante el TB2, hemos mejorado la comunicación efectiva de nuestros avances y resultados en el proyecto de ingeniería. Nos centramos en desarrollar el backend de la plataforma y cumplir con las historias de usuario definidas. Adaptamos nuestro enfoque según las necesidades de cada grupo, utilizando un lenguaje técnico para asegurar una comprensión clara de nuestros logros y progresos.<br><br> -**TF1**:<br> Durante el TF1, hemos mejorado nuestra capacidad para comunicar de manera efectiva los avances técnicos de nuestro proyecto al integrar con éxito componentes críticos como el backend y el frontend. Adaptamos nuestra presentación para garantizar claridad ante diversas audiencias, asegurando el respaldo continuo hacia nuestros objetivos estratégicos.</br><br>   | **TB1**: Como equipo en el desarrollo de nuestro proyecto de ingeniería, hemos demostrado habilidades sólidas en la comunicación objetiva de ideas y resultados. Nuestra capacidad para adaptar el mensaje según la audiencia, utilizando un lenguaje claro y respaldando nuestros puntos con datos concretos, ha sido fundamental para mantener una comunicación efectiva y transparente en todas las etapas del proyecto. Estas prácticas no solo fortalecen nuestra colaboración interna, sino que también aseguran que todos los niveles jerárquicos y especialidades involucradas comprendan y apoyen nuestro progreso y logros. <br><br> **TP1**: En resumen, durante el TP1 hemos experimentado un notable avance en la comunicación oral como equipo, lo cual ha sido fundamental para nuestro progreso en el desarrollo del reporte. Hemos perfeccionado la habilidad de presentar ideas complejas de manera clara y efectiva, adaptándonos a diferentes audiencias y respaldando nuestros argumentos con sólidos principios de ingeniería. Además, hemos cultivado un ambiente colaborativo que enriquece nuestras soluciones al integrar diversas perspectivas. Estas mejoras no solo optimizan nuestra eficiencia diaria, sino que también fortalecen nuestra capacidad para enfrentar desafíos técnicos y estratégicos con confianza y éxito. <br> <br> **TB2**: Durante el TB2, hemos fortalecido nuestra capacidad para comunicar de manera efectiva los avances y resultados en nuestro proyecto de ingeniería. Al concentrarnos en el desarrollo del backend de la plataforma y cumplir con las historias de usuario, hemos adaptado nuestro enfoque comunicativo según las necesidades específicas de cada grupo. Utilizando un lenguaje técnico apropiado, hemos asegurado una comprensión clara y precisa de nuestros logros y progresos. Estas mejoras no solo optimizan nuestra colaboración interna, sino que también refuerzan nuestra capacidad para enfrentar desafíos técnicos y estratégicos con confianza y eficacia.  <br><br> **TF1**: En conclusión durante el TF, hemos fortalecido nuestra capacidad como equipo para comunicar de manera efectiva los desarrollos técnicos de nuestro proyecto. La integración exitosa del backend y frontend representa un logro crucial. Esta habilidad nos ha permitido asegurar una comunicación clara y coherente ante diversas audiencias, fortaleciendo así nuestro trabajo colaborativo y el respaldo hacia nuestros objetivos compartidos.  <br>                                                                                                                                                                 |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería             | <br> **Jorge Sebastian Ponce Loyola**<br> - **TB1**: <br> Durante la TB1, me involucré activamente en la redacción objetiva de informes técnicos y análisis detallados dentro de nuestro proyecto de ingeniería de software. Este proceso incluyó la comunicación clara y concisa de nuestras soluciones adaptadas a las especificidades del sector empresarial, asegurando que cada documento reflejara de manera precisa los resultados alcanzados y las recomendaciones propuestas.<br><br> - **TP1**:<br> Durante el TP, he liderado la redacción de informes técnicos detallados que comunican claramente nuestras soluciones innovadoras para el sector objetivo. Mi enfoque se ha centrado en asegurar que cada documento refleje de manera precisa los avances tecnológicos y estratégicos alcanzados, adaptándome a las expectativas de diferentes niveles jerárquicos y especialidades dentro de la organización. <br><br> -**TB2**: <br>En el TB2, he sido responsable de comunicar de manera objetiva los avances en el desarrollo del backend y frontend de nuestro proyecto de ingeniería. Mi enfoque ha sido asegurar que cada informe técnico refleje con precisión las mejoras implementadas, adaptando el contenido para ser comprensible tanto para especialistas técnicos como para líderes estratégicos dentro de la organización.<br><br> -**TF1**:<br> En el TF, he liderado la redacción precisa y objetiva de informes que detallan el desarrollo completo del backend, su integración con el frontend y la implementación en diversas plataformas. Mi enfoque ha sido asegurar que cada documento refleje con claridad los resultados alcanzados, adaptando el contenido para ser comprensible y relevante para diferentes especialidades y niveles jerárquicos dentro de nuestra organización..</br><br> **Juan Diego Cueto Dominguez** <br> - **TB1**: <br> En nuestro proyecto, he sido responsable de comunicar de manera objetiva nuestros análisis competitivos y estratégicos a diversas audiencias. Esto implicó la redacción precisa de informes que destacaran nuestros puntos fuertes frente a los competidores actuales y potenciales, asegurando que cada comunicación estuviera adaptada a las necesidades específicas de cada nivel jerárquico y especialidad dentro de nuestra organización.<br><br> - **TP1**:<br> En este TP, he sido responsable de la redacción de análisis competitivos y estratégicos que destacan nuestra posición única en el mercado. He asegurado que nuestros informes no solo informen, sino que también persuadan a audiencias clave sobre la efectividad de nuestras estrategias, adaptando el contenido para captar la atención de diversos públicos especializados y de liderazgo.  <br><br> **TB2**:<br> Durante este periodo, me he concentrado en la redacción clara y objetiva de informes que destacan los progresos logrados en la implementación y optimización del backend y frontend de nuestro proyecto. He asegurado que cada comunicación esté adaptada a las expectativas específicas de diferentes niveles jerárquicos y especialidades dentro de nuestra empresa, facilitando así una comprensión completa y un respaldo efectivo hacia nuestras iniciativas. <br><br> -**TF1**:<br> Durante este periodo, me he concentrado en la redacción de informes técnicos que comunican de manera efectiva el éxito en la finalización y despliegue del backend y frontend del proyecto. He asegurado que cada comunicación esté adaptada a las expectativas específicas de audiencias técnicas y ejecutivas, proporcionando análisis detallados y recomendaciones estratégicas fundamentadas en nuestros logros tecnológicos..</br><br> **Carlos Joel Shimabukuro Uku**<br> - **TB1**: <br>Durante el desarrollo del proyecto, he liderado la redacción de documentación técnica detallada, comunicando los resultados de nuestras investigaciones sobre el modelo de negocio del sector objetivo. Esta comunicación escrita objetiva ha facilitado la comprensión y el apoyo continuo hacia nuestras soluciones tecnológicas, asegurando que cada informe sea accesible y relevante para audiencias de diferentes especialidades y niveles jerárquicos.<br><br>- **TP1**: <br>Durante el desarrollo del TP, he sido el encargado de comunicar de manera objetiva los resultados de nuestras investigaciones sobre el modelo de negocio del sector específico. He enfocado mis esfuerzos en presentar datos críticos y análisis que respalden nuestras decisiones tecnológicas y estratégicas, asegurando que cada informe sea claro y relevante para los stakeholders involucrados.<br><br>- **TB2**: <br> En el TB2, he liderado la redacción de informes técnicos detallados sobre el desarrollo y finalización del backend y frontend de nuestro proyecto. Mi enfoque ha sido transmitir de manera objetiva los resultados alcanzados, proporcionando análisis claro y relevante para las diversas audiencias dentro y fuera de nuestro equipo, lo que ha facilitado una toma de decisiones informada y estratégica.<br><br> -**TF1**:<br>En el marco del TF, he desempeñado un papel crucial en la redacción de informes técnicos detallados sobre la integración exitosa del backend y frontend, así como en su despliegue en múltiples plataformas. He enfocado mis esfuerzos en comunicar objetivamente los resultados y beneficios de nuestras soluciones tecnológicas, asegurando que cada informe sea accesible y relevante para diferentes audiencias especializadas y de liderazgo dentro de la empresa.</br><br> **Aldhair Johan Juan Valenzuela Huillcaya** <br>- **TB1**: <br> Mi rol en el proyecto ha incluido la redacción de informes técnicos que comunican claramente nuestra comprensión del sector empresarial abordado. Esto ha involucrado la presentación objetiva de datos y análisis sobre las demandas tecnológicas y estratégicas del sector, asegurando que cada documento sea informativo y persuasivo para diferentes públicos, desde técnicos hasta directivos. <br><br> -**TP1**: <br>Mi rol en el TP ha sido fundamental en la redacción de informes técnicos que clarifican nuestra comprensión del entorno empresarial donde opera nuestra aplicación de software. He investigado a fondo las demandas y desafíos del sector, asegurando que mis informes proporcionen una visión precisa y objetiva que facilite la toma de decisiones informadas en todos los niveles de la organización.<br><br>**- TB2**:<br> Mi rol durante este periodo ha sido fundamental en la comunicación escrita objetiva de los avances técnicos logrados en nuestro proyecto. He redactado informes que detallan con precisión las implementaciones realizadas en el backend y frontend, asegurando que cada documento sea accesible y valioso para técnicos especializados y líderes empresariales que requieren información específica para apoyar nuestras decisiones tecnológicas. <br><br> -**TF1**:<br> Durante el TF, me he destacado en la redacción de informes técnicos que documentan claramente el proceso de desarrollo completo del backend, su conexión con el frontend y la implementación en diversas plataformas. He asegurado que cada documento transmita de manera objetiva nuestra experiencia y logros, adaptándolo para informar y persuadir tanto a técnicos especializados como a líderes empresariales sobre los beneficios estratégicos de nuestro trabajo.</br><br>**Ricardo Jesus Maguiña Corzo**<br> - **TB1**: <br> Durante la TB1, he sido responsable de comunicar de manera efectiva los avances y resultados del proyecto en informes técnicos y documentos detallados. Esto ha incluido la redacción objetiva de nuestras estrategias y logros en el desarrollo de software, asegurando que cada comunicación esté adaptada a las necesidades y expectativas de diversas especialidades y niveles jerárquicos dentro y fuera de nuestro equipo. <br><br> - **TP1**:<br>Durante el TP, he destacado en la redacción de informes técnicos detallados que comunican efectivamente nuestros logros y estrategias en el desarrollo de software. Mi enfoque ha sido garantizar que cada comunicación esté adaptada a las necesidades específicas de diversas audiencias, desde técnicos hasta directivos, asegurando así una comprensión clara y un apoyo sólido hacia nuestros objetivos estratégicos. <br><br>-**TB2**: <br> Durante el TB2, me he destacado en la redacción de informes técnicos que comunican de manera efectiva los desarrollos significativos en el backend y frontend de nuestro proyecto. He asegurado que cada comunicación esté enfocada en proporcionar una visión clara y objetiva de nuestros logros, adaptándola a las necesidades y expectativas de diferentes públicos, desde especialistas técnicos hasta directivos interesados en los resultados estratégicos del proyecto. <br> <br> -**TF1**:<br> En este periodo final, he sido responsable de la comunicación escrita objetiva sobre el despliegue exitoso del backend y frontend en diferentes plataformas. Me he asegurado de redactar informes que destacan de manera clara y precisa los resultados alcanzados, adaptando cada comunicación para satisfacer las necesidades específicas de diversas audiencias dentro y fuera de nuestro equipo, lo que ha fortalecido nuestra reputación técnica y estratégica en el proyecto.<br><br>                                         | **TB1**: En conclusión, durante nuestro proyecto de ingeniería, hemos demostrado una habilidad sólida para comunicar de manera objetiva y efectiva a diversas audiencias a través de nuestros escritos. Desde la redacción detallada de informes técnicos hasta la presentación clara de análisis competitivos y estratégicos, cada miembro del equipo ha contribuido significativamente a asegurar que nuestros documentos reflejen con precisión nuestros avances y recomendaciones. Esta capacidad no solo fortalece nuestro trabajo colaborativo, sino que también garantiza que nuestras soluciones tecnológicas y estratégicas sean comprendidas y respaldadas adecuadamente por especialistas y líderes dentro de la organización.<br><br> **TP1**: En conclusión, durante el Trabajo Parcial, hemos mejorado nuestra capacidad para comunicar con precisión y efectividad las innovaciones y estrategias desarrolladas en nuestro proyecto de ingeniería. Cada uno de nosotros ha contribuido con habilidades únicas, desde la redacción detallada de informes técnicos que destacan nuestras soluciones específicas para el sector, hasta la presentación persuasiva de análisis competitivos y estratégicos. Esta colaboración ha enriquecido nuestra comprensión interna de las decisiones tecnológicas y comerciales, fortaleciendo nuestro posicionamiento estratégico en el mercado objetivo. <br><br> **TB2**: Durante el TB2, hemos demostrado habilidades robustas en la comunicación escrita objetiva al informar con precisión sobre el progreso del backend y frontend de nuestro proyecto de ingeniería. Cada uno de nosotros ha contribuido de manera única a garantizar que nuestros informes sean claros, detallados y adecuados para audiencias diversas, fortaleciendo así nuestra capacidad para avanzar estratégicamente en el desarrollo tecnológico.  <br><br> **TF1**: En conclusión, durante el Trabajo Final, hemos demostrado habilidades sólidas en la comunicación escrita al documentar con precisión el desarrollo del backend, su integración con el frontend y el despliegue en diversas plataformas. Cada uno contribuyó para asegurar que nuestros informes fueran comprensibles y pertinentes para audiencias técnicas y ejecutivas, fortaleciendo nuestra capacidad para comunicar eficazmente los logros tecnológicos y estratégicos del proyecto.  <br>         |

---

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1 Descripción de la Startup
- **Misión:** 

Nuestra misión es proporcionar a nuestros suscriptores las herramientas y el apoyo necesario para alcanzar sus objetivos de bienestar y salud, a través de una comunicación directa con coaches expertos y planes alimentarios personalizados.

- **Visión:** 

Aspiramos a ser líderes en el campo del bienestar personal, ofreciendo una plataforma innovadora y accesible que promueva hábitos saludables y un estilo de vida equilibrado para todos nuestros usuarios.
- **Valores:**

* Compromiso con nuestros suscriptores: Nos comprometemos a proporcionar un servicio de alta calidad que satisfaga las necesidades individuales de cada usuario, brindando un apoyo continuo y personalizado.
* Excelencia y profesionalismo: Nos esforzamos por mantener los más altos estándares de excelencia en todos los aspectos de nuestro negocio, desde la selección de nuestros coaches hasta la entrega de nuestros planes alimentarios, asegurando la máxima calidad en cada interacción.
* Innovación y adaptabilidad: Buscamos constantemente nuevas formas de mejorar y adaptarnos a las necesidades cambiantes de nuestros usuarios, utilizando tecnologías de vanguardia y métodos innovadores para ofrecer soluciones efectivas y actualizadas.
* Ética y transparencia: Operamos con integridad y transparencia en todas nuestras acciones, asegurando la confianza y la credibilidad de nuestra comunidad de usuarios en todo momento.
* Empoderamiento y motivación: Nos esforzamos por empoderar a nuestros usuarios para que tomen el control de su salud y bienestar, brindándoles las herramientas, el conocimiento y el apoyo necesario para alcanzar sus metas y mantener un estilo de vida saludable a largo plazo.

### 1.1.2 Perfiles de integrantes del equipo


#### Ponce Loyola, Jorge Sebastian - u202120471 - Ingeniería de Software 
Mi nombre es Jorge Ponce, tengo 20 años y estoy cursando el sexto ciclo de la carrera de Ingeniería de Software. Me encanta la música, el arte, pintar, el baloncesto. Me gusta dialogar, escuchar y aplicar el pensamiento crítico en cualquier ámbito. Me aseguraré de realizar un trabajo de calidad y de colaborar de manera activa y comprometida para lograr los resultados deseados. Tengo conocimientos en metodologías ágiles, desarrollo tanto en la parte web como en el backend, y también poseo una comprensión básica de ciberseguridad.

<img src="/assets/img/capitulo1/Profile-Jorge.jpg" alt="Jorge Sebastian Ponce Loyola" width="200" height="250">

---
#### Maguiña Corzo, Ricardo Jesus - U202121858 - Ingeniería de Software
Me llamo Ricardo Jesus Maguiña Corzo y tengo 20 años. Estudió la carrera de Ing. de Software en la UPC. En mis tiempos libres me gusta aprender nuevas tecnologías, salir a practicar 
fútbol y jugar en mi computadora. Conocimiento y habilidades: Poseo destrezas colaborativas, habilidades para abordar desafíos y un compromiso constante con el aprendizaje. Mi experiencia abarca metodologías ágiles, desarrollo web y backend, así como nociones fundamentales en ciberseguridad.

<img src="/assets/img/capitulo1/Profile-Ricardo.jpg" alt="Ricardo Jesus Maguiña Corzo" width="200" height="250">

---
#### Cueto Dominguez, Juan Diego - U202012207 - Ingeniería de Software
Mi nombre es Juan Diego Cueto Dominguez, actualmente soy estudiante de la carrera de Ingeniería de Software. Cuento con conocimiento y experiencia en el uso de Git y GitHub, con el cual estaré apoyando a mis compañeros. Además poseo mucha práctica con los lenguajes de programación C++, JavaScript, Python , HTML5 y CSS3. Estoy dispuesto a apoyar y trabajar en el tiempo y momento que se requiera.

<img src="/assets/img/capitulo1/Profile-Juan_Diego.PNG" alt="Juan Diego Cueto Dominguez" width="200" height="220">

---
#### Valenzuela Huillcaya, Aldhair Johan Juan - U20201F572 - Ingeniería de Software
Soy estudiante de Ingeniería de software en la Universidad peruana de Ciencias Aplicadas (UPC). Me considero una persona altamente responsable, organizada, puntual y empática. Mi capacidad de adaptación a entornos cambiantes y habilidad para trabajar colaborativamente en equipo son aspectos destacados de mi perfil. Tengo conocimientos en Python, C++, HTML, CSS, Javascript, MySQL, MongoDB y SQLite.

<img src="/assets/img/capitulo1/Profile_Aldhair_2.jpg"  alt="Aldhair Johan Juan Valenzuela Huillcaya" width="200" height="250">

---

#### Shimabukuro Uku, Carlos Joel - U201912407 - Ingeniería de Software
Mi nombre es Carlos Joel Shimabukuro Uku, soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC) y actualmente estoy en el quinto ciclo académico. Mi experiencia se centra principalmente en la programación orientada a objetos utilizando C++, además de tener conocimientos básicos en HTML, CSS y JavaScript. En este proyecto, mi objetivo es aplicar los conocimientos adquiridos hasta ahora y obtener una comprensión más profunda sobre mi futuro rol como profesional en esta área.

<img src="/assets/img/capitulo1/Profile-Carlos.png"  alt="Carlos Joel Shimabukuro Uku" width="200" height="250">

---

## 1.2. Solution Profile


### 1.2.1 Antecedentes y problemática
Para analizar los antecedentes y la problemática a la que nuestro proyecto se afronta, vamos a utilizar el modelo práctico de las 5Ws y 2Hs, con el fin de idear un sistema más estructurado y que se centre en las causas del problema principalmente.

**Antecedentes:**

Presentación del modelo de las preguntas 5Ws y 2Hs con la que se analizaron los antecedentes y la problemática que abarca nuestro proyecto.

| LAS 5W y 2H | Pregunta                                                | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|-------------|---------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Who?        | ¿Quién es afectado?                                     | Personas interesadas en mejorar su salud y condición física, así como profesionales del coaching en áreas como el ejercicio y la nutrición.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| What?       | ¿Cuál es el problema?                                   | La desmotivacion o dificultades que tienen las personas a la hora de trazar y empezar una rutina de entrenamiento, ya sea por salud o actividad propia. De acuerdo al Ministerio de Salud (MINSA, 2024), el 62% de peruanos mayores a 15 años sufre de obesidad, esto demuestra la carente disciplina, compromisos o mal hábito de alimentacion que tiene la población.                                                                                                                                                                                                                                                                                                                                                                                                                          |
| When?       | ¿Cuándo sucede el problema?                             | Es un problema que usualmente a estado presente en varias personas desde que intentaron iniciar una rutina de entrenamiento, con el objetivo de abordar sus necesidades y mejorar su estilo de vida. Añadiendo además aquellos profesionales del coaching que han deseado expandir su base de clientes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 
| Where?      | ¿Dónde surge el problema?                               | El problema surge de las necesidades y ubicacion de la persona, siendo los principales factores la distancia del gimnasio mas cercano y sus tiempos disponibles, por ende la aplicación estará disponible en línea, lo que permitirá el acceso desde cualquier lugar con conexión a internet.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Why?        | ¿Cuál es la causa del problema?                         | La creación de la aplicación se debe a la falta de orientación personalizada para las personas que desean mejorar su salud y condición física, así como la necesidad de los profesionales del coaching de llegar a nuevos clientes y ofrecerles un servicio efectivo y personalizado.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| How?        | ¿Qué llevó a la persona a esta situación?               | Segun un estudio realizado por Ipsos, un 44% de personas hace actividad fisica con frecuencia y percepciona que el 88% considera que tener una buena alimentacion es la clave para tener una vida saludable (Ipsos Perú, 2019), por ende nuestra aplicación facilitara la comunicación directa entre usuarios y coaches a través de reuniones virtuales además de proporcionar acceso a planes alimentarios personalizados. Los usuarios podran suscribirse mensualmente para acceder a estos servicios y recibir el seguimiento y apoyo continuo que necesitan para alcanzar sus objetivos de salud.                                                                                                                                                                                            |
| How Much?   | ¿Cuál es la cantidad, duración o intensidad del evento? | Según un estudio realizado por Fitness Pass (2019), se descubrió que un porcentaje alarmantemente alto del 80% de las personas optan por cancelar su membresía en el gimnasio después de tres meses de haberla adquirido. Este hallazgo preocupa a la industria del fitness, donde seguir un régimen de ejercicio a largo plazo parece ser desafiante para la mayoría de los individuos. Entre los motivos principales que impulsan esta decisión se encuentran la desmotivación y la falta de tiempo. La desmotivación puede surgir de diversas fuentes, incluida la falta de resultados rápidos o visibles. Además, en el mundo moderno, las demandas de tiempo suelen ser un factor determinante, ya que las personas luchan por equilibrar el trabajo, la familia y otras responsabilidades. |
### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements
Existe una creciente demanda de soluciones integrales y personalizadas para mejorar el bienestar y la salud personal. Sin embargo, el mercado carece de una plataforma que ofrezca comunicación directa con expertos en salud y planes alimentarios personalizados. Ante esta brecha, se necesita desarrollar una plataforma innovadora y accesible que promueva hábitos saludables y un estilo de vida equilibrado, permitiendo a los usuarios alcanzar sus metas de salud y bienestar de manera efectiva y sostenible.¿Cómo podemos diseñar una solución que empodere a los usuarios para tomar el control de su salud y bienestar, ofreciéndoles herramientas personalizadas y apoyo continuo para alcanzar sus objetivos de manera efectiva y sostenible?

#### 1.2.2.2. Lean UX Assumptions
**User Outcomes:** 

1: ¿Quién es el usuario?: 
- Nuestro usuario objetivo es aquel individuo interesado en mejorar su salud y bienestar, que busca una solución integral y personalizada para alcanzar sus metas de forma efectiva y sostenible.
 
2: ¿Dónde encaja nuestro producto en su trabajo o vida?: 
- Nuestro producto encaja en la vida diaria del usuario, proporcionándole herramientas y apoyo para adoptar hábitos saludables y mantener un estilo de vida equilibrado, tanto en casa como en movimiento.

3: ¿Qué problemas tiene nuestro producto y cómo se pueden resolver?: 
- Uno de los problemas de nuestro producto podría ser la falta de conciencia sobre la importancia de la salud y el bienestar personal. Esto se puede abordar mediante una sólida campaña de concienciación y educación sobre los beneficios de adoptar hábitos saludables.
- Otro problema podría ser la dificultad para seguir los planes alimentarios personalizados. Esto se puede resolver mediante una interfaz intuitiva y fácil de usar, junto con recordatorios y seguimientos personalizados.

4: ¿Cuándo y cómo es usado nuestro producto?: 
- Nuestro producto es utilizado por los usuarios diariamente, tanto para acceder a consejos y orientación de salud como para registrar sus progresos y recibir retroalimentación. Se utiliza a través de una aplicación móvil y una plataforma web, adaptándose así a las diferentes preferencias de los usuarios.

5: ¿Qué características son importantes?: 
- Características importantes incluyen comunicación directa con coaches expertos, planes alimentarios personalizados, seguimiento de progreso, recordatorios de hábitos saludables, y acceso a recursos educativos sobre nutrición y bienestar.

6: ¿Cómo debe verse nuestra aplicación y cómo debe comportarse?: 
- Nuestra aplicación debe tener un diseño limpio y moderno, con una interfaz intuitiva que permita a los usuarios navegar fácilmente por las diferentes funciones y características. Debe comportarse de manera fluida y receptiva, brindando una experiencia de usuario agradable y satisfactoria.

 **Business Outcomes:**
- Incremento en el número de suscriptores y retención de usuarios a largo plazo.
- Generación de ingresos a través de suscripciones premium y colaboraciones con marcas relacionadas con la salud y el bienestar.
- Posicionamiento como líder en el campo del bienestar personal, ganando reconocimiento y confianza de la comunidad de usuarios.



#### 1.2.2.3. Lean UX Hypothesis Statements

- **Hypothesis 1**
    Creemos firmemente que es esencial ofrecer planes de entrenamiento y nutrición personalizados, diseñados específicamente para cada usuario en base a sus necesidades, objetivos y restricciones individuales.

    Sabremos que hemos tenido éxito cuando los usuarios no solo experimenten un aumento en los resultados positivos relacionados con sus metas de salud y bienestar, sino también cuando expresen una mayor satisfacción y compromiso con sus programas de entrenamiento y nutrición personalizados.
    
- **Hypothesis 2**
    Creemos firmemente que sería ideal integrar elementos de gamificación, como logros y desafíos, dentro de la aplicación. Estos elementos pueden motivar a los usuarios, fomentar la competencia saludable y hacer que el proceso de entrenamiento y seguimiento de la nutrición sea más emocionante y atractivo.

    Sabremos que hemos tenido éxito en la integración de estos elementos cuando observemos un aumento significativo en la participación y la retención de los usuarios en la aplicación. Esto se reflejará en métricas como el tiempo de uso, la frecuencia de interacción y la retroalimentación positiva de los usuarios sobre la experiencia de gamificación en la aplicación.
    
- **Hypothesis 3**
    Creemos firmemente que se debería ofrecer un modelo de suscripción flexible con diferentes niveles para nuestra aplicación. Esto permitirá a los usuarios elegir el nivel de servicio que mejor se adapte a sus necesidades y presupuesto, brindando opciones que abarquen desde funcionalidades básicas hasta características premium y exclusivas.

    Sabremos que hemos tenido éxito en la implementación de este modelo cuando observemos un incremento notable en la adquisición de suscriptores en todos los niveles. Además, la satisfacción del cliente se traducirá en renovaciones de suscripción consistentes, indicando que los usuarios valoran la oferta de valor proporcionada en cada nivel de suscripción y están dispuestos a continuar utilizando nuestros servicios a largo plazo.
    
- **Hypothesis 4**
    Creemos que deberíamos ofrecer recomendaciones y sugerencias personalizadas basadas en los datos del usuario, utilizando información como su historial de entrenamiento, preferencias alimenticias, metas de salud y otros datos relevantes. Estas recomendaciones personalizadas pueden incluir desde rutinas de ejercicios específicas hasta sugerencias de comidas y consejos de bienestar adaptados a las necesidades individuales de cada usuario.

    Sabremos que hemos tenido éxito en la implementación de este enfoque cuando los usuarios experimenten una mayor relevancia y utilidad en las recomendaciones recibidas. Esto se reflejará en una mejor experiencia general para los usuarios, quienes encontrarán que la aplicación les ayuda de manera efectiva a alcanzar sus objetivos de salud y bienestar de manera personalizada y significativa.
    
- **Hypothesis 5**
    Creemos que se debe ofrecer una prueba gratuita o demostración de la aplicación a todos nuestros nuevos usuarios, permitiéndoles experimentar las características y beneficios que nuestra plataforma ofrece antes de comprometerse con una suscripción.

    Sabremos que hemos tenido éxito en esta estrategia cuando analicemos la conversión de usuarios de prueba a suscriptores de pago y observemos un incremento significativo desde el inicio hasta el plazo de 4 meses. Este aumento en la conversión indicará que la prueba gratuita o demostración está generando interés y confianza en los usuarios, lo que les lleva a optar por suscribirse y continuar utilizando nuestra aplicación a largo plazo.
    
- **Hypothesis 6**
    Creemos que se debería ofrecer un respectivo feedback y soporte continuo a través de sesiones con los respectivos coaches, proporcionando a los usuarios la oportunidad de recibir orientación personalizada y seguimiento regular en sus objetivos de entrenamiento, nutrición y bienestar.

    Sabremos que hemos tenido éxito en esta iniciativa cuando los usuarios experimenten una mejora significativa en sus hábitos de vida y bienestar físico, lo cual se verá reflejado en una encuesta de satisfacción. Al obtener comentarios positivos sobre la efectividad del feedback y el soporte proporcionado por los coaches, y al observar mejoras tangibles en la calidad de vida y el estado físico de los usuarios, confirmaremos el éxito de esta estrategia.


#### 1.2.2.4. Lean UX Canvas

###### Figura 1.

Presentación del Lean UX Canvas referente a nuestro proyecto.

<img src="/assets/img/capitulo1/Lean UX canvas Fithub.png" alt="Lean UX Canvas" >

## 1.3. Segmento Objetivo

* **Personas con el objetivo de mejorar su salud y condición física** : Este segmento incluye a los usuarios mayores de 18 años que residan en Perú y tengan el interés de mejorar su salud mediante la aplicación de una asistencia personalizada. Son individuos que están comprometidos con su bienestar y que buscan una guía confiable y constante para seguir rutinas de ejercicios o planes nutricionales. 

* **Coaches profesionales en el ámbito del entrenamiento físico y nutrición** : Este segmento incluye a los profesionales en las áreas de entrenamiento físico y nutrición alimenticia, mayores de 18 años que residan en el Perú y que estén respaldados con un certificado legítimo en sus respectivas profesiones. Son entrenadores y nutricionistas comprometidos con un enfoque profesional y orientado a resultados, en busca de una plataforma diseñada para apoyar y potenciar el trabajo de estos profesionales. Desde la creación de planes de entrenamiento personalizados hasta el seguimiento del progreso de los clientes.  

