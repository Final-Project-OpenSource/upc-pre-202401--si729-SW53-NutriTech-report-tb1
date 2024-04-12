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
En esta sección se mostrarán las pautas, convenciones, estilos y principios que se utilizarán para cada uno de los lenguajes que se emplearán en la creación de nuestra aplicación, Medicare. La práctica de este conjunto de reglas es de suma importancia, ya que estas tienen el propósito de conservar la calidad estructural del software, dar una mayor legibilidad al código fuente y facilitar el mantenimiento del código.

Dado que en este proyecto se utilizarán HTML, CSS y JavaScript para la codificación de la plataforma web y Gherkins para el proceso de prueba del programa; a continuación, se nombrarán y describirán las reglas y recomendaciones generales que tomaremos en cuenta al momento de usarlos.
#### **Nomenclatura General**

A los nombres de las variables, objetos, elementos y funciones que se utilicen, se les designarán términos en inglés que estén relacionados y puedan describir a lo que están representando. No se usarán mayúsculas porque de acuerdo con W3Schools (s.f.), la mezcla de estas con las letras minúsculas luce mal y, además, el uso exclusivo de minúsculas otorga mayor legibilidad al código.

Ejemplo de nomenclatura estándar según Google (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.001.png" />

#### **Sangría**

En el momento de utilizar HTML, CSS y/o JavaScript se aplicará un espaciado antes de cada línea que se encuentre dentro de un bloque. Este espacio debe ser de dos y según W3Schools (s.f.) no se debe hacer uso de la tecla “Tabulación”.

Ejemplo de nomenclatura estándar de la sangría en HTML según W3Schools (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.002.png" />

Ejemplo de nomenclatura estándar de la sangría en CSS según W3Schools (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.003.png" />

Ejemplo de nomenclatura estándar de la sangría en JavaScript según W3Schools (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.004.png" />

Seguidamente, explicaremos las reglas específicas que se necesitan en cada lenguaje para entender el código de nuestro programa, FitHub Pro.

#### **HTML**
Llamado así por las siglas del nombre en inglés HyperText Markup Language. HTML es un lenguaje de marcado que define la estructura de una página web. Además, cuenta con funciones capaces de determinar el comportamiento de distintas partes del contenido de la página, tales como el cambiar el tamaño del texto, aplicar cursiva, entre otros. Nosotros emplearemos HTML5, y las características y pautas a seguir para hacer uso de este lenguaje son las siguientes:

#### **Declare Document Type**
El tipo de documento debe declararse en la primera línea de código. De acuerdo con Google (s.f.) HTML5 es de preferencia la mejor sintaxis para todo documento HTML, para declararla sólo es necesario copiar lo siguiente:

#### **Blank Lines**
Cada vez que, luego de un bloque, lista o tabla de gran longitud se inicie uno nuevo, se debe saltar la siguiente línea y dejarla en blanco para brindar mayor legibilidad y amenidad, así manifiesta W3Schools (s.f.).

Ejemplo:<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.007.png" />

#### **Quote Attribute Values**

Para los valores de los atributos se utilizan comillas dobles alrededor. De acuerdo con W3Schools (s.f.) Aunque esta característica no sea obligatoria, le da más legibilidad al código y es muy frecuente entre los desarrolladores.

Ejemplo:<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.009.png" />

#### **Multimedia Fallback**
Asegurar un acceso alterno a los objetos multimedia por si este fallara al cargar. De la misma forma, según la W3Schools (s.f.), es recomendable añadir las dimensiones del elemento porque así los navegadores guardan el espacio que utilizará antes de comenzar a cargarlo.

Ejemplo:<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.011.png" />

#### **Never Skip the Element**

El elemento permite que las páginas aparezcan en la lista de resultados al momento de buscar en un navegador web. Asimismo, esta es la que da el nombre de la página si se la añade a favoritos.

Ejemplo:<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.012.png" />

#### **HTML Line-Wrapping**

El hecho de que en un documento HTML no haya un límite de palabras por línea, no quiere decir que sea recomendable generar líneas muy extensas de código. Al contrario, esto dificulta la lectura del código. Para pasar a la siguiente línea es necesario utilizar al menos cuatro espacios para diferenciar de elementos hijos.

Ejemplo según Google (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.013.png" />

#### **CSS**

Llamado así por las siglas del nombre en inglés Cascading Style Sheets. CSS es un lenguaje de marcado que se centra en definir y mejorar la presentación de un documento que se basa en HTML. Las pautas que a seguir al momento de usar CSS son las siguientes:

#### **Shorthand Properties**
Hay que utilizar abreviación de propiedades, declarar los campos de los elementos en la menor cantidad de líneas posibles. De acuerdo con Google (s.f.), esto aumenta la eficacia del código y lo hace más entendible. De la misma manera, debemos evitar el colocar las unidades luego del valor cero.

Ejemplo:<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.014.png" /><br>

<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.015.png" /><br>

#### **Declaration Stops**

Hay que colocar un punto y coma luego de cada declaración al igual que gran parte de lenguajes de programación. Según Google (s.f.). esta característica ayuda a que haya más consistencia en el código

Ejemplo:<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.016.png" />

#### **Property Name Stops**
Debe existir un espacio entre los dos puntos que están luego del nombre de una propiedad y el valor ingresado. Siempre solo un espacio luego de los dos puntos, mas no antes.

Ejemplo estándar según Google (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.017.png" />

#### **Declaration Block Separation**
El uso de un separador de un espacio es necesario luego del nombre de un elemento seleccionado y la llave que inicia un bloque. Además, esta llave tiene que estar en la misma línea.

Ejemplo estándar según Google (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.018.png" />

#### **CSS Quotation Marks**
No se deben emplear las comillas dobles (“”), solo están permitidas las simples (‘’) para el uso exclusivo de selectores de atributos y valores de propiedades.

Ejemplo estándar según Google (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.020.png" />
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.021.png" />

#### **JavaScript**

Es un lenguaje de programación que otorga la posibilidad de indicar exactamente las acciones que debe ejecutar el navegador, indicando el orden de las tareas y el número de veces que se realizarán. Las indicaciones para usar JavaScript en nuestro proyecto son las siguientes:

#### **Spaces around operators**
Se debe colocar un espacio alrededor de cada operador matemático que se introduzca en el código. Esto también aplica a las comas.

Ejemplo estándar según W3Schools (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.022.png" />

#### **Simple Statement’s End**
Una indicación simple debe terminar en un punto y coma, esto se cumple también en muchos otros lenguajes de programación.

Ejemplo estándar según W3Schools (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.024.png" />

#### **Beginning and End of a Function**

Un bloque de función debe contar con una llave al final de la primera línea, para que el cierre de esta se encuentre sola en la última. Una función termina en llave y no en punto y coma. Lo mismo aplica para condicionales o bucles.

Ejemplo estándar según W3Schhol (s.f):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.026.png" />

#### **Object Rules**
Para la construcción de un objeto, al igual que en una función, se comienza con una llave al final de la primera línea, pero, esta vez, la llave de cierre debe estar acompañada de un punto y coma. Para las propiedades, se colocan dos puntos y un espacio para indicar su valor, el cual debe estar entre comillas dobles si este es un

*string*.

Ejemplo estándar según W3School (s.f.):<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.027.png" />

#### **Gherkin**
Es un Lenguaje Específico de Dominio (DSL por sus siglas en inglés) que tiene como objetivo la resolución de un problema en específico. Para ello, se generan casos para la validación de la característica en distintos escenarios. Gherkin cuenta con múltiples elementos, de los cuales, los más famosos y, además, más utilizados son *Feature, Scenario, Example, Scenario, Given, When* y *Then.* Las indicaciones para tomar en cuenta en el uso de Gherkin en nuestro código son las siguientes.

#### **Discernible Given-When-Then Blocks**
Aplicar sangría para los elementos que indiquen pasos a seguir del escenario. En el caso de *And*, aplicar dos veces. De acuerdo con Keiblinger (2021), Esto ayuda a detectar rápidamente las partes que forman un escenario.

Ejemplo:

**Scenario**: Ingreso los requisitos con claridad
**Given** que en el formulario de ingreso de oferta laboral
**When** escribo claramente los requisitos
**Then** se mostrará el mensaje
**And** mi oferta solo aparecerá a quienes cumplan con estos
**And** se habilita la opción
#### **Step with Tables**

Según Keiblinger (2021), para las partes del escenario que necesiten la introducción de valores, hay que agregar una tabla o crear un propio formulario que recree esa parte del escenario. Antes de esta representación se deben colocar dos puntos.

Ejemplo:<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.028.png" /><br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.029.png" /><br>

#### **Reducing Noise**
Con el fin de reducir la acumulación de demasiadas líneas de código en un escenario, se deben colocar valores por defecto dentro de los pasos para los campos que no sean muy relevantes para este. Los valores “estándar” que coloquemos, deben ir entre comillas simples. De acuerdo con Keiblinger (2021), esta acción reduce considerablemente el tamaño del código.

Ejemplo:<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.030.png" />

#### **Scenarios Separator**
Para la separación de dos escenarios, se debe insertar un salto de línea y, según Keiblinger (2021), de ser posible, hay que agregar una línea de comentario para facilitar la visualización de estos. De esta forma se halla rápidamente el inicio y fin de un escenario.

Ejemplo:<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.032.png" /><br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.033.png" /><br>

#### **TypeScript**
El equipo usara los siguientes estilos para determinadas categorías:

**UpperCamelCase:** clase/interfaz/tipo/enum/decorador/parámetros de tipo

**lowerCamelCase**: variable / parámetro / función / método / propiedad / alias de módulo **CONSTANT\_CASE:** valores constantes globales, incluidos los valores de enumeración Nunca se utilizan identificadores privados.

Variables y Funciones

#### **Mala Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.034.png" />

**Buena Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.035.png" />

![ref6]Clases

#### **Mala Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.036.png" />

**Buena Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.037.png" />

Propiedades y métodos de la clase

#### **Mala Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.038.png" />
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.039.png" />

**Buena Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.040.png" />

Interfaces

No emplear el prefijo I para nombrar interfaces

#### **Mala Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.041.png" />

**Buena Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.042.png" />

Enums

No emplear el prefijo I para nombrar interfaces

#### **Mala Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.044.png" />
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.045.png" />

**Buena Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.046.png" />

Visibility

Restringir la visibilidad de propiedades, métodos y tipos ayudaran a mantener el código desacoplado.

#### **Mala Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.047.png" />

**Buena Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.048.png" />

Getters and Setters

Se pueden utilizar los getters y setters para los miembros de la clase. También son útiles como medio para restringir la visibilidad de los detalles de implementación internos, aplicando la Programación Orientada a Objetos;

#### **Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.049.png" />
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.050.png" />

Variables

Uso de const o let para declarar variables. Utilice const de forma predeterminada, a menos que sea necesario reasignar una variable.
No usar var para declarar variables.

#### **Nomenclatura:**<br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.051.png" /><br>
<img src="/assets/img/capitulo5/Aspose.Words.a48e7a94-958e-481b-9be7-4e0d4e115cf1.052.png" /><br>

**Module**: import \\* as foo from '...';

**Destructuring**: import {SomeThing} from '...';

**Default**: import SomeThing from '...';

**Side-effect:** import '...'; Only to import libraries for their side-effects on load (such as custom elements)

#### **Angular**
Angular es un marco de diseño de aplicaciones y una plataforma de desarrollo para crear aplicaciones de una sola página eficientes y sofisticadas. Se usará Angular siguiendo las siguientes características y pautas.

#### **Naming Components:**
Se utilizará un formato estándar para el nombre de los componentes dentro del proyecto. Los nombres de los componentes serán separados por dots (puntos) y dashes (-). Y su estructura sería “feature.type.**ts**”.

Un ejemplo estándar sería:
Para el Feature de Information: “Information.component.ts”.
Para la selección de componentes en el código se usará la estructura “dased-case” él tiene como estructura: “feature-case.component”.

#### **Naming Services:**
Se utilizará un formato estándar para el nombre de los servicios. Se agregará el sufijo de “Service” y además cada palabra iniciará con mayúscula, por ejemplo “DataService” o “PaymentService”.

#### **Unit Test File Names**
Se utilizará el mismo formato de Component para la creación de Test Files, con la diferencia que estos tendrán un “.spec” antes del “ts” al final.
Un ejemplo de la estructura sería:
Feature Information Unit Test: “Information.component.spec.ts”.

#### **Java**
Angular es un lenguaje de promagración ampliamente utilizado para programación web. Se utilizará Java junto a:

#### **Function Declaratons**
Se seguirán las siguientes características para declarar una function:
Siempre especifique la visibilidad del método (público, protegido o privado). En caso de múltiples operadores, especifique el orden usando corchetes.
Evite escribir “this.” cuando sea posible.
Un ejemplo correcto de la declaración de una función sería:
public void setGroupNames (Group group, String name)

#### **Wrapping Lines**
Cuando una expresión no alcance en una sola línea de código se seguirán las siguientes características:
Salto después de una coma.
Romper antes de un operador.
Alinee la nueva línea con el comienzo de la expresión al mismo nivel en la línea anterior.
Si las reglas anteriores conducen a un código confuso o a un código que se aprieta contra el margen derecho, solo agregar una sangría de 8 espacios en su lugar.

#### **Loop Counters**
Las variables locales en Loop siempre deberán llamarse **i, j, k, l** en todos los casos.

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
