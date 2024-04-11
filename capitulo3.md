# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

###### Tabla 6.



###### Tabla 7.




## 3.2. User Stories
Tabla de épicas establecidas para las historias de usuarios.

| Epic ID | Título                                    |
|---------|-------------------------------------------|
| EP01    | Experiencia del Visitante                 |
| EP02    | Experiencia de entrenamiento y nutrición  |
| EP03    | Desarrollo de Funcionalidades Principales |

###### Tabla 9.
Tabla de historias de usuario 
| Epic / Story ID|Título |Descripción | Criterios de Aceptación| Relacionado con (Epic ID)| 
|-|-|-|-|-|
|US01 | | | |EP01 |
|US02 | | | |EP01 |
|US03 | | | |EP01 |
|US04 | | | |EP01 |
|US05 | | | |EP01 |
|US06 |Seguimiento de progreso |**Como** usuario, **quiero** poder establecer metas de entrenamiento específicas para recibir recomendaciones personalizadas. |**Dado** que el usuario visita su perfil , **Cuando** da click en metas <br> **y** selecciona crear meta, **Entonces** la aplicación le brinda las herramientas necesarias para poder crear dicha meta. |EP02 |
|US07 |Asesoramiento nutricional |**Como** usuario, **quiero** un asesoramiento nutricional personalizado para ajustar mi dieta diaria. |**Dado** que el usuario visita la página principal , **Cuando** da click en Buscar Asesor, **Entonces** la aplicación deriva al usuario con un asesor para el correcto asesoramiento nutricional. |EP02 |
|US08 |Gamificacion para aumentar la motivación |**Como** usuario, **quiero** participar en desafíos de gamificación en donde pueda tener objetivos de entrenamiento. |**Dado** que el usuario visita la página desafíos , **Cuando** desplaza hacia abajo, **Entonces** la aplicación le muestra al usuario todos los desafíos activos para dicha fecha. |EP02 |
|US09 |Personalizacion de entrenamiento |**Como** usuario, **quiero** recibir planes de entrenamiento personalizadas basadas en mis preferencias para optimizar mi rendimiento y obtener resultados en mi salud. |**Dado** que el usuario visita la página principal , **Cuando** da click en Buscar Entrenador, **Entonces** la aplicación deriva al usuario con un entrenador especializado para el correcto asesoramiento de entrenamiento. |EP02 |
|US010|Planificación de sesiones de entrenamiento |**Como** usuario, **quiero** poder planificar y programar mis sesiones de entrenamiento para mantener una rutina organizada. |**Dado** que el usuario visita la página principal , **Cuando** da click en Mis sesiones, **Entonces** la aplicación le muestra su calendario con las sesiones que tiene programas **y** le muestra opciones para agregar una nueva sesión durante la semana. |EP02 |
|US011|Integrar Sistema con Servicio Externo  |**Como** desarrollador, **Quiero** integrar el sistema con un servicio externo, **Para** ampliar la funcionalidad y mejorar la interoperabilidad. |**Dado** que el desarrollador tiene la documentación y las credenciales necesarias del servicio externo. <br> **Cuando** el desarrollador implementa la integración siguiendo las especificaciones del servicio externo. <br> **Entonces** la integración se completa correctamente y el sistema puede comunicarse con el servicio externo. <br> **Dado** que el desarrollador intenta integrar el sistema sin entender los requisitos del servicio externo. <br> **Cuando** el desarrollador implementa la integración de manera incorrecta o incompleta. <br> **Entonces** la comunicación con el servicio externo falla o produce resultados incorrectos. |EP03 |
|US012|Refactorizar Código para Mejorar Mantenibilidad | **Como** desarrollador, **Quiero** refactorizar el código existente, **Para** mejorar su estructura y facilitar el mantenimiento futuro.                  | **Dado** que el desarrollador identifica áreas de código que pueden refactorizarse. <br> **Cuando** el desarrollador realiza cambios para mejorar la estructura y legibilidad del código. <br> **Entonces** el código refactorizado pasa las pruebas de unidad y las funcionalidades existentes no se ven afectadas negativamente. <br> **Dado** que el desarrollador intenta refactorizar el código sin entender completamente su funcionalidad. <br> **Cuando** el desarrollador realiza cambios que introducen errores o cambios no deseados en el sistema. <br> **Entonces** se revierten los cambios y se realiza una revisión más cuidadosa.    |EP03 |
|US013|Implementar Autenticación de Dos Factores       | **Como** desarrollador, **Quiero** implementar la autenticación de dos factores, **Para** mejorar la seguridad de la plataforma.                          | **Dado** que el desarrollador tiene especificaciones claras sobre la autenticación de dos factores. <br> **Cuando** el desarrollador implementa la funcionalidad según las especificaciones. <br> **Entonces** la autenticación de dos factores se activa y funciona correctamente para los usuarios. <br> **Dado** que el desarrollador intenta implementar la autenticación de dos factores sin entender los requisitos de seguridad. <br> **Cuando** el desarrollador realiza implementaciones incompletas o incorrectas. <br> **Entonces** la autenticación de dos factores no proporciona una capa de seguridad adecuada o causa problemas de acceso para los usuarios.    |EP03 |
|US014|Desarrollar Funcionalidad de Notificaciones     | **Como** desarrollador, **Quiero** desarrollar la funcionalidad de notificaciones, **Para** mantener a los usuarios informados sobre eventos importantes. | **Dado** que el desarrollador tiene especificaciones detalladas sobre los tipos de notificaciones requeridos. <br> **Cuando** el desarrollador implementa la funcionalidad de notificaciones de acuerdo con las especificaciones. <br> **Entonces** el sistema envía notificaciones apropiadas a los usuarios en los momentos adecuados. <br> **Dado** que el desarrollador intenta implementar la funcionalidad de notificaciones sin entender los casos de uso y la lógica de negocio. <br> **Cuando** el desarrollador realiza implementaciones incorrectas o incompletas. <br> **Entonces** las notificaciones no se envían correctamente o pueden causar confusión entre los usuarios.  |EP03 |
|US015|Crear Herramientas de Monitoreo y Depuración    | **Como** desarrollador, **Quiero** crear herramientas de monitoreo y depuración, **Para** facilitar la identificación y resolución de problemas.          | **Dado** que el desarrollador necesita herramientas para monitorear el rendimiento y depurar problemas. <br> **Cuando** el desarrollador implementa herramientas de monitoreo y depuración según las mejores prácticas. <br> **Entonces** las herramientas proporcionan información útil sobre el estado del sistema y ayudan a identificar y resolver problemas rápidamente. <br> **Dado** que el desarrollador intenta implementar herramientas de monitoreo y depuración sin entender completamente las necesidades del sistema. <br> **Cuando** el desarrollador crea herramientas inadecuadas o incompletas. <br> **Entonces** las herramientas no proporcionan información útil o pueden causar confusión al intentar utilizarlas. |EP03 |
|US016| | | |EP04 |
|US017| | | |EP04 |
|US018| | | |EP04 |
|US019| | | |EP04 |
|US020| | | |EP04 |
|US021| | | |EP05 |
|US022| | | |EP05 |
|US023| | | |EP05 |
|US024| | | |EP05 |
|US025| | | |EP05 |

## 3.3. Impact Mapping

###### Figura 12.


## 3.4. Product Backlog

|# Orden |User Story Id |Título |Descripción |Story Points (1 / 2 / 3 / 5 / 8) |
|-|-|-|-|-|
|1 | | | | |
|2| | | | |
|3 | | | | |
|4 | | | | |
|5 | | | | |
|6 | | | | |
|7 | | | | |
|8 | | | | |
|9 | | | | |
|10 | | | | |
|11 | | | | |
|12 | | | | |
|13 | | | | |
|14 | | | | |
|15 | | | | |
|16 | | | | |
|17 | | | | |
|18 | | | | |
|19 | | | | |
|20 | | | | |
|21 | | | | |
|22 | | | | |
|23 | | | | |
|24 | | | | |
|25 | | | | |
---


