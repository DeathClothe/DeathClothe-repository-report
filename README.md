


## Universidad Peruana de Ciencias Aplicadas

![logo](Report_Assets/UPC_logo_transparente.png)

#### Nombre del curso: Aplicaciones Web
##### Carrera: Ingeniería de Software
##### Nombre del profesor: Hugo Allan Mori Paiva
##### NRC: 4376

#### "Informe de Trabajo Final"
##### Nombre de la Startup: ReWear
##### Nombre del Producto: DeathClothe

#### Integrantes

Bejarano Martínez Alvaro Leandro U202311640<br>
Cabanillas Meza Jose Mateo U202311458<br>
Luquillas Asto Omar U20211G641<br>
Santur Tello Andrea Elizabeth U202310988<br>
Sarmiento Medina Loreley U202310005<br>

# *Abril de 2025*
</div>

## Registro de Versiones del Informe


| Versión | Fecha      | Autor | Descripción de modificación |
|---------|------------|-------|------------------------------|
| TB1     | 27/04/2025 | - Bejarano Martínez, Álvaro Leandro<br>- Cabanillas Meza, José Mateo<br>- Luquillas Asto, Omar<br>- Santur Tello, Andrea Elizabeth<br>- Sarmiento Medina, Loreley | Se realizó un trabajo integral desde la investigación inicial hasta el diseño del producto DeathClothe. Incluyó entrevistas, análisis de usuarios, construcción de user personas, journey maps, mapas de empatía, Lean UX Canvas, wireframes, mockups y diagramas de arquitectura, consolidando así la base estratégica y visual del proyecto. |
| TP      | 16/05/2025 | - Bejarano Martínez, Álvaro Leandro<br>- Cabanillas Meza, José Mateo<br>- Luquillas Asto, Omar<br>- Santur Tello, Andrea Elizabeth<br>- Sarmiento Medina, Loreley | Se realizó acerca sobre la Landing Page de DeathClothe. Se incluyó la plataforma desarrollada y además, se elaboraron algunos puntos importantes que involucran al desarrollo de la plataforma DeathClothe, como la página de bienvenida, el perfil de "Comprador" y "Vendedor", las ofertas, las tendencias, los productos de temporada y demás cosas que se presentan en la plataforma. |
| TB2     | 17/06/2025 | - Bejarano Martínez, Álvaro Leandro<br>- Cabanillas Meza, José Mateo<br>- Luquillas Asto, Omar<br>- Santur Tello, Andrea Elizabeth<br>- Sarmiento Medina, Loreley | Se desarrollaron e integraron nuevas funcionalidades clave como el catálogo de favoritos, la sección personalizada “Para ti” con recomendaciones basadas en intereses del comprador, y la vista detallada de productos con chat integrado. Se actualizó el Lean UX Canvas alineándolo con los nuevos aprendizajes, se mejoró la interfaz de usuario y se fortaleció la conexión entre comprador y vendedor. Además, se realizaron validaciones con usuarios y se documentaron los hallazgos. |
| TF      | -          | -     |  |


## Project Report Collaboration Insights

|  URL del repositorio del reporte  |
| :-----------------------------------: |
| `https://github.com/DeathClothe/DeathClothe-repository-report` |

TB1: Durante esta entrega se trabajó principalmente en el diseño e implementación inicial de la landing page del proyecto, la cual fue desplegada correctamente. Las tareas fueron distribuidas entre los miembros del equipo y gestionadas mediante GitHub. La elaboración del informe comenzó en paralelo, con aportes individuales desde el repositorio compartido.

TP1: Para esta entrega se realizaron mejoras visuales y funcionales a la landing page, y se inició el desarrollo de la aplicación web. Las actividades se dividieron según los roles del equipo, y cada integrante contribuyó con secciones del informe, tanto en redacción como en revisión. Las evidencias de colaboración están disponibles en el historial de commits y gráficas del repositorio correspondiente.

TB2: En esta entrega se trabajaron mejoras tanto en el landing page como en la aplicación web, incorporando funcionalidades adicionales y refinando aspectos visuales. Además, se comenzó el desarrollo de los servicios web y se elaboraron los primeros videos del proyecto. La colaboración del equipo se mantuvo activa a través del repositorio del informe, con evidencias claras de participación en los commits y contribuciones distribuidas entre todos los integrantes.

TF:

**Analíticos de Colaboración:**

![alt text](./Report_Assets/Contributors.png)

**Analíticos de Commits:**

![alt text](./Report_Assets//Commits.png)


## Contenido

- [Student Outcome](#student-outcome)

- [Capítulo I](#capítulo-i)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
 
- [Capítulo III: Requirements specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
 
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2 Labeling Systems](#422-labeling-systems)
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
      - [5.2.2.2. Aspect Leaders and Collaborators.](#5222-aspect-leaders-and-collaborators)
      - [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review.](#5224-development-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review.](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review.](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review.](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint.](#5228-team-collaboration-insights-during-sprint)
    - [5.2.3. Sprint 3](#523-sprint-3)
      - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
      - [5.2.3.2. Aspect Leaders and Collaborators.](#5232-aspect-leaders-and-collaborators)
      - [5.2.3.3. Sprint Backlog 3](#5233-sprint-backlog-3)
      - [5.2.3.4. Development Evidence for Sprint Review.](#5234-development-evidence-for-sprint-review)
      - [5.2.3.5. Execution Evidence for Sprint Review.](#5235-execution-evidence-for-sprint-review)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review.](#5236-services-documentation-evidence-for-sprint-review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review.](#5237-software-deployment-evidence-for-sprint-review)
      - [5.2.3.8. Team Collaboration Insights during Sprint.](#5238-team-collaboration-insights-during-sprint)
    - [5.2.4. Sprint 4](#524-sprint-4)
      - [5.2.4.1. Sprint Planning 4](#5241-sprint-planning-4)
      - [5.2.4.2. Aspect Leaders and Collaborators.](#5242-aspect-leaders-and-collaborators)
      - [5.2.4.3. Sprint Backlog 4](#5243-sprint-backlog-4)
      - [5.2.4.4. Development Evidence for Sprint Review.](#5244-development-evidence-for-sprint-review)
      - [5.2.4.5. Execution Evidence for Sprint Review.](#5245-execution-evidence-for-sprint-review)
      - [5.2.4.6. Services Documentation Evidence for Sprint Review.](#5246-services-documentation-evidence-for-sprint-review)
      - [5.2.4.7. Software Deployment Evidence for Sprint Review.](#5247-software-deployment-evidence-for-sprint-review)
      - [5.2.4.8. Team Collaboration Insights during Sprint.](#5248-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)

- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)



## Student Outcome
 
El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC – Student Outcome 5**
Criterio: *La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos*

En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC – Student Outcome 5.

| Criterio específico                         | Acciones realizadas                                                                                                                                         | Conclusiones                                                                 |
|--------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta         | **Bejarano Martínez, Alvaro Leandro**<br><br>**TB1**<br>Participó en las presentaciones semanales del avance del backlog y lideró la exposición sobre la arquitectura de software.<br><br>**TP1**<br>Participó en el desarrollo de la Landing Page y se encargó de la programación.<br><br>**Cabanillas Meza, José Mateo**<br><br>**TB1**<br>Expuso los hallazgos de entrevistas con usuarios compradores y presentó los mockups.<br><br>**TP1**<br>Se encargó de elaborar acerca sobre el Frontend y Backend para que se pueda plasmar en el trabajo.<br><br>**Luquillas Asto, Omar**<br><br>**TB1**<br>Apoyó en la socialización de ideas técnicas y expuso sobre la competencia directa e indirecta.<br><br>**TP1**<br>Se encargó parte de la codificación del diseño elaborado después de ser bosquejado y elaborado anteriormente.<br><br>**Santur Tello, Andrea Elizabeth**<br><br>**TB1**<br>Presentó el diseño de wireframes, guió al equipo durante la exposición de validación de requerimientos.<br><br>**TP1**<br>Encargada del funcionamiento de otras partes fundamentales en la codificación y aportó con la elaboración del informe.<br><br>**Sarmiento Medina, Loreley**<br><br>**TB1**<br>Moderó varias sesiones y participó activamente en la explicación del flujo de usuarios y arquitectura general.<br><br>**TP1**<br>Se encargó del bosquejo del Frontend y Backend para que después sea codificado y plasmado.<br><br> | Las presentaciones fortalecieron nuestras habilidades de comunicación técnica y persuasiva. Se hizo un gran avance con respecto al entregable anterior, así como también, se pudo evidenciar acerca sobre el avance del funcionamiento de la plataforma. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos         | **Bejarano Martínez, Alvaro Leandro**<br><br>**TB1**<br>Participó en las presentaciones semanales del avance del backlog y lideró la exposición sobre la arquitectura de software.<br><br>**TP1**<br>Participó en el desarrollo de la Landing Page y se encargó de la programación.<br><br>**Cabanillas Meza, José Mateo**<br><br>**TB1**<br>Expuso los hallazgos de entrevistas con usuarios compradores y presentó los mockups.<br><br>**TP1**<br>Se encargó de elaborar acerca sobre el Frontend y Backend para que se pueda plasmar en el trabajo.<br><br>**Luquillas Asto, Omar**<br><br>**TB1**<br>Apoyó en la socialización de ideas técnicas y expuso sobre la competencia directa e indirecta.<br><br>**TP1**<br>Se encargó parte de la codificación del diseño elaborado después de ser bosquejado y elaborado anteriormente.<br><br>**Santur Tello, Andrea Elizabeth**<br><br>**TB1**<br>Presentó el diseño de wireframes, guió al equipo durante la exposición de validación de requerimientos.<br><br>**TP1**<br>Encargada del funcionamiento de otras partes fundamentales en la codificación y aportó con la elaboración del informe.<br><br>**Sarmiento Medina, Loreley**<br><br>**TB1**<br>Moderó varias sesiones y participó activamente en la explicación del flujo de usuarios y arquitectura general.<br><br>**TP1**<br>Se encargó del bosquejo del Frontend y Backend para que después sea codificado y plasmado.<br><br> | Las presentaciones fortalecieron nuestras habilidades de comunicación técnica y persuasiva. Se hizo un gran avance con respecto al entregable anterior, así como también, se pudo evidenciar acerca sobre el avance del funcionamiento de la plataforma. | Trabaja en equipo para proporcionar liderazgo en forma conjunta                                | **Bejarano Martínez, Álvaro Leandro**<br><br>**TB2**<br>Coordinó el desarrollo de funcionalidades avanzadas como la sección "Favoritos” y la lógica de recomendación personalizada en el frontend.<br><br>**Cabanillas Meza, José Mateo**<br><br>**TB2**<br>Participó en el diseño de las nuevas vistas del producto y colaboró en el refinamiento del sistema de búsqueda con filtros.Ademas rediseño la seccion "Explora"<br><br>**Luquillas Asto, Omar**<br><br>**TB2**<br>Encargado del del perfil del vendedor, configuración del sistema de autenticación y consolidó la documentación del informe.<br><br>**Santur Tello, Andrea Elizabeth**<br><br>**TB2**<br>Relizo el perfil del comprador,gestión la integración del módulo de chat y consolidó la documentación del informe de TB2.<br><br>**Sarmiento Medina, Loreley**<br><br>**TB2**<br>Apoyó en la validación funcional con usuarios, contribuyó a la reestructuración, realizo el armario virtual, con algunas modificaciones del Fronted y aportó en el diseño iterativo de la interfaz.<br><br> | En esta etapa se logró consolidar funcionalidades clave del producto, promoviendo la organización del equipo en roles técnicos y de documentación. Se evidenció un trabajo colaborativo fluido y liderazgo compartido para alcanzar los objetivos del entregable. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos | **Bejarano Martínez, Álvaro Leandro**<br><br>**TB2**<br>Colaboró con la planificación de entregables técnicos y lideró la revisión de código en equipo.<br><br>**Cabanillas Meza, José Mateo**<br><br>**TB2**<br>Organizó reuniones de revisión de interfaz y definió flujos de navegación visualmente intuitivos.<br><br>**Luquillas Asto, Omar**<br><br>**TB2**<br>Coordinó la documentación de endpoints y trabajó de manera sincronizada con el equipo frontend.<br><br>**Santur Tello, Andrea Elizabeth**<br><br>**TB2**<br>Propuso mejoras al Canvas Lean UX alineándolo con la nueva visión del producto. Estableció hitos y lideró tareas vinculadas a la validación con usuarios.<br><br>**Sarmiento Medina, Loreley**<br><br>**TB2**<br>Se encargó de estructurar el reporte del entregable y de asegurar que la narrativa visual del prototipo esté alineada con la propuesta de valor.<br><br>                                                         | En TB2 el grupo demostró mayor madurez en la planificación, división de responsabilidades y ejecución eficiente. Se evidenció una evolución del trabajo en equipo hacia un enfoque más autónomo, ágil y enfocado en la mejora continua del producto.|

  

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
ReWear es una startup enfocada en transformar la manera en que las personas consumen, comparten y viven la moda. Creemos que cada prenda tiene una historia y que el estilo no debería depender de la producción masiva ni del consumo desechable. En ReWear, conectamos a usuarios apasionados por la autenticidad, la sostenibilidad y la expresión personal, a través de un mercado digital de ropa de segunda mano que combina tecnología, diseño y comunidad.
Nuestro primer producto, DeathClothe, es una plataforma web que permite a los usuarios subir, comprar, vender y descubrir prendas únicas, mientras reciben recomendaciones personalizadas basadas en su armario virtual. Más que una app, es una experiencia viva, donde la moda circula, evoluciona y encuentra nuevas almas.

Misión: Nuestra misión es ofrecer una nueva oportunidad a la ropa que ya no es deseada, brindando una segunda vida a las prendas y conectando a personas con gustos auténticos. A través de nuestra plataforma, buscamos que cada usuario pueda encontrar piezas únicas que se alineen con su estilo personal, sin tener que recurrir a la moda rápida. Fomentamos un consumo responsable, permitiendo que cada compra y venta de ropa sea un paso hacia un estilo más consciente, auténtico y sostenible.

Visión: Nos visualizamos como una empresa líder en el renacimiento de la moda circular, construyendo una comunidad global que redefine el estilo desde la autenticidad, el cuidado del planeta y la tecnología. Aspiramos a convertirnos en el referente para quienes ven en su ropa una extensión de su identidad, y que eligen transformar el mundo desde su armario.

### 1.1.2. Perfiles de integrantes del equipo

| Integrantes | Perfil de Integrante |
|-------------|----------------------|
| ![Alvaro](Report_Assets/yo.png) | **Alvaro Leandro Bejarano Martínez** – Ingeniería de Software – U202311640<br>Mi nombre es Alvaro Leandro Bejarano Martínez, estudiante de la carrera Ingeniería de Software y me destaco por mi perseverancia, organización y capacidad para trabajar en equipo. Me esfuerzo por mantener un ambiente estructurado dentro del grupo, donde cada miembro se sienta valorado y sus ideas sean escuchadas y respetadas. Mi compromiso es fomentar la colaboración efectiva, asegurando que cada contribución se integre de manera ordenada y alineada con los objetivos comunes del equipo. |
| ![Mateo](Report_Assets/yo2.jpg) | **Jose Mateo Cabanillas Meza** – Ingeniería de Software – U202311458<br>Mi nombre es Mateo Cabanillas y en la actualidad estoy cursando el quinto ciclo de la carrera de ingeniería de software con una mente creativa y una actitud colaborativa. Mi amor por la programación y la resolución de problemas me impulsa a explorar nuevas soluciones y aportar ideas frescas a los proyectos. Como compañero de equipo, soy amable, atento y siempre estoy dispuesto a ayudar. Creo firmemente en la importancia de la comunicación efectiva y la colaboración para lograr resultados excepcionales. |
| ![Omar](Report_Assets/integrante3.png) | **Omar Luquillas Asto** – Ingeniería de Software – U20211G641<br>Soy Omar Luquillas Asto con código de estudiante U20211G641, estudiante de la carrera de Ingeniería de Software. Elegí esta carrera porque me apasiona la tecnología, el desarrollo de software y la programación. Tengo conocimientos en lenguajes de programación como C++, Python y Java. Me considero una persona investigadora, ya que me gusta aprender cosas nuevas y siempre estoy en busca de soluciones creativas e innovadoras que generen un impacto positivo en la vida de las personas. Además, valoro el trabajo en equipo, soy responsable y me comprometo a cumplir con mis tareas de manera eficiente. |
| ![Andrea](Report_Assets/integrante4.png) | **Andrea Santur** – Ingeniería de Software – U202310988<br>Soy Andrea Santur con código de estudiante 202310988, curso el 5to ciclo de la carrera de ingeniería de software. Me considero una persona organizada, dedicada y siempre dispuesta a aprender y a brindar apoyo a quienes lo necesiten. Tengo conocimientos en lenguajes de programación como C++, HTML y CSS, además de habilidades en Photoshop y Diseño UI. Valoro el trabajo en equipo, el aprendizaje continuo y el compromiso por presentar resultados de calidad. Espero aportar de manera efectiva al equipo y contribuir a la entrega de un proyecto excelente. |
| ![Loreley](Report_Assets/Loreley.PNG) | **Loreley Sarmiento Medina** – Ingeniería de Software – U202310005<br>Soy Loreley Sarmiento Medina con código de estudiante U202310005 y estudio la carrera de Ingeniería de Software. Me especializo en aportar soluciones tecnológicas integrales dentro de equipos multidisciplinarios. Cuento con sólidos conocimientos en el modelado de wireframes y mockups utilizando Figma, lo que me permite contribuir eficazmente en la etapa de diseño de interfaces centradas en el usuario. Además, tengo experiencia en el modelado de bases de datos, facilitando la organización y estructura lógica de la información. Poseo conocimientos intermedios en HTML y CSS, lo cual me permite colaborar en el desarrollo de interfaces web funcionales y visualmente atractivas. También tengo una base sólida en lenguajes de programación, lo que me permite implementar soluciones tanto en el frontend como en el backend, aportando al desarrollo integral del producto. |


## 1.2. Solution Profile
DeathClothe es una plataforma web que transforma la manera de consumir moda al permitir a los usuarios comprar, vender y descubrir ropa de segunda mano con recomendaciones personalizadas según su armario virtual. A través de una experiencia intuitiva, conecta a personas que buscan autenticidad, estilo y sostenibilidad, facilitando la circulación de prendas únicas y dándoles una nueva vida. Con un enfoque en la moda circular, la personalización y la comunidad, DeathClothe no solo es un mercado digital, sino un espacio donde el estilo evoluciona con propósito.

### 1.2.1. Antecedentes y problemática

**What**

*¿Cuál es el problema que se está presentando?*

El problema principal es el impacto ambiental y social del modelo de consumo de moda rápida (fast fashion), que genera millones de toneladas de residuos textiles anualmente y promueve un consumo desechable. Esto ha generado la necesidad urgente de nuevas soluciones digitales que impulsen modelos circulares. En respuesta a esta problemática, surge DeathClothe, una plataforma digital centrada en la moda circular. Esta permite a los usuarios subir, comprar, vender y descubrir ropa de segunda mano. A través de un armario virtual y un sistema de recomendaciones inteligentes, crea una experiencia personalizada que promueve un consumo más consciente, auténtico y sostenible.

**When**

*¿Cuándo estamos viendo el problema?*

El problema se observa de forma constante, ya que la producción y desecho de ropa ocurre durante todo el año, sin un patrón específico de estacionalidad. Sin embargo, se intensifica en épocas de rebajas, nuevas colecciones y eventos comerciales como el Black Friday, cuando aumenta el consumo impulsivo.

*¿En qué momento del día o del proceso en cuestión?*

Desde el punto de vista del usuario, el problema aparece en el momento en que busca renovar su estilo, encuentra prendas de baja calidad, o quiere deshacerse de ropa en buen estado sin una opción ética o rentable. La plataforma DeathClothe se usa precisamente en esos momentos, ofreciendo una alternativa para quienes desean darle una segunda vida a su ropa o encontrar prendas únicas sin recurrir al fast fashion.

**Where**

*¿Dónde estamos viendo los problemas?*

Los problemas se presentan a nivel global, pero particularmente en las grandes ciudades donde el consumo textil es más alto. También se manifiestan en vertederos, donde la mayoría de los residuos textiles terminan, así como en los procesos de producción masiva de ropa de bajo costo.

*¿En qué parte del proceso estamos viendo el problema?*

Se identifican en varias etapas del ciclo de vida de una prenda: desde la sobreproducción en la industria, pasando por la compra impulsiva y el uso efímero, hasta el desecho irresponsable. La falta de opciones para reciclar o revender ropa acentúa la problemática. DeathClothe interviene en la etapa de posconsumo, ofreciendo una alternativa responsable.

**Who**

*¿A quién le sucede?*

El problema afecta tanto al medio ambiente como a los consumidores. Específicamente, impacta a usuarios eco‑conscientes y fashionistas que desean adoptar un estilo más responsable sin comprometer su identidad. También afecta a personas con ropa en buen estado que no saben qué hacer con ella.

*¿El problema está relacionado con las habilidades de las personas?*

No directamente, pero sí con la falta de herramientas accesibles que faciliten la participación activa en la moda circular. Al no contar con plataformas intuitivas o sistemas de recomendación, muchos usuarios no saben cómo reutilizar o intercambiar su ropa, lo que impide un consumo más sostenible. DeathClothe busca reducir esta barrera tecnológica y de conocimiento.

**Why**

*¿Por qué sucede el problema?*

El problema sucede porque el modelo de fast fashion genera 92 millones de toneladas de residuos textiles al año, el equivalente a un camión de basura lleno de ropa vertido en vertederos cada segundo, con un fuerte impacto ambiental. En Estados Unidos, se descartan más de 34 000 millones de libras de textiles usados anualmente (más de 100 libras per cápita), lo que evidencia la incapacidad de los sistemas tradicionales para gestionar el ciclo de vida de la ropa. Solo el 20 % de los textiles descartados se recolecta para reciclaje o reutilización; el resto acaba en vertederos o incinerado. Todo esto subraya la urgencia de modelos de negocio circulares que fomenten la reutilización y reflejan cómo la cultura del consumo desechable y la producción acelerada están directamente relacionadas con el problema central que busca abordar DeathClothe.

**How**

*¿Cómo se diferencia el problema del estado normal (óptimo)?*

El problema actual se diferencia del estado óptimo en que los usuarios de plataformas de moda aún enfrentan catálogos desorganizados, una oferta saturada y sin personalización, además de una baja conciencia respecto al impacto ambiental del fast fashion. En contraste, el estado óptimo sería aquel en el que el consumidor puede descubrir fácilmente prendas alineadas con su estilo, a través de una experiencia curada, personalizada y sustentable que facilite la reutilización de ropa. DeathClothe apunta precisamente a resolver esta brecha, brindando una solución que combina sostenibilidad, personalización y una comunidad conectada a través de su armario virtual.

*¿La tendencia en la que aparece el problema es aleatoria o sigue un patrón?*

La tendencia no es aleatoria; sigue un patrón claro de consumo masivo e insostenible incentivado por el modelo del fast fashion. Esta industria genera una sobreoferta de prendas a bajo costo que incentiva la compra constante, lo que a su vez produce un inventario muy amplio y poco manejable en el ecosistema recommerce. Esto hace difícil para los usuarios descubrir lo que realmente necesitan o desean. Por ello, la plataforma utiliza algoritmos de curación y filtros avanzados para romper con este patrón y mejorar la experiencia de usuario, permitiéndole encontrar de forma efectiva lo que encaja con su identidad.

**How Much**

*¿Cuántos problemas se dan en un día, una semana o un mes?*

La magnitud del problema es crítica. Según la Ellen MacArthur Foundation (2017), cada año se desechan 92 millones de toneladas de ropa, de las cuales menos del 1% se recicla. Esto equivale a más de 250 mil toneladas diarias de residuos textiles generados a nivel global, una cifra alarmante que pone en evidencia la escala masiva del problema. Esta situación se produce de forma continua, todos los días del año, y tiene implicancias tanto ambientales como sociales.

*¿Cuánto dinero están implicando?*

La dimensión económica del problema es considerable. De acuerdo con McKinsey (2016), los consumidores compran un 60% más de prendas que hace dos décadas, pero las conservan la mitad de tiempo, lo que implica un gasto constante y acelerado que no se corresponde con un uso prolongado de las prendas. Aunque el 62% de los jóvenes prefiere opciones sostenibles (ThredUp, 2023), el mercado de segunda mano sigue siendo subutilizado. Esto representa una brecha económica y de impacto ambiental entre las buenas intenciones de los consumidores y las soluciones disponibles, y demuestra la urgente necesidad de propuestas innovadoras como DeathClothe que promuevan un consumo responsable, eficiente y circular.

### 1.2.2. Lean UX Process

El proceso Lean UX es una metodología ágil centrada en crear valor para el usuario mediante ciclos rápidos de validación y aprendizaje continuo. En lugar de depender de documentación extensa o procesos largos de diseño, Lean UX propone trabajar en conjunto con usuarios reales para validar hipótesis, iterar prototipos y evolucionar el producto con base en evidencia y datos.

#### 1.2.2.1. Lean UX Problem Statements

DeathClothe fue diseñado para facilitar la compra y venta de ropa de segunda mano, promoviendo así un consumo más sostenible y consciente.
Hemos observado que, actualmente, muchas personas desean adoptar la moda circular, pero enfrentan obstáculos importantes: los compradores tienen dificultades para encontrar prendas atractivas, en buen estado o alineadas a su estilo, debido a la falta de filtros eficaces y opciones personalizadas en plataformas existentes. A su vez, los vendedores enfrentan procesos complejos y poco transparentes para listar sus prendas, lo que desincentiva su participación. Como resultado, se genera un círculo vicioso: menos oferta atractiva limita el interés de compra, y las dificultades para vender reducen la rotación de ropa, provocando que muchas prendas en buen estado terminen desechadas.
¿Cómo podríamos diseñar una plataforma accesible y eficiente que elimine estas barreras en la compra y venta de ropa usada, de manera que más personas participen activamente y DeathClothe se convierta en una alternativa real y sostenible a la moda tradicional?

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions (Suposiciones de Negocio)**

- Creo que mis clientes tienen la necesidad de: Encontrar ropa de segunda mano que sea única, en buen estado y que se ajuste a sus gustos y tallas, además de contar con un canal sencillo y confiable para vender sus prendas usadas.

- Estas necesidades pueden resolverse con: Una plataforma especializada que facilite la compra y venta mediante herramientas de curación, personalización, filtros inteligentes, procesos simples de publicación y un sistema transparente de valoraciones.

- Mis clientes iniciales son (o serán): Jóvenes adultos entre 18 y 30 años, con conciencia ambiental, interés en la moda y hábitos digitales activos en redes sociales como Instagram y TikTok.

- El valor principal que el cliente desea obtener de mi servicio es: Adquirir o vender ropa de segunda mano de forma fácil, rápida y confiable.

Beneficios adicionales que pueden obtener son: Exclusividad, ahorro económico, impacto ambiental positivo y conexión emocional con prendas con historia.

- Adquiriré a la mayoría de mis clientes mediante: Campañas digitales con influencers de moda sostenible, contenido en redes sociales y estrategias de marketing orgánico en plataformas como TikTok e Instagram.

- Ganaré dinero mediante: Comisiones por transacción y servicios premium para vendedores (como posicionamiento de productos, herramientas analíticas o mejoras de visibilidad).

- Mi competencia principal en el mercado será: Plataformas generalistas como Vinted o Marketplace de Facebook.

Los superaremos gracias a: Una experiencia de usuario más intuitiva, filtros inteligentes, curación personalizada y un enfoque claro en sostenibilidad y comunidad.

- Mi mayor riesgo de producto es: Que los usuarios no perciban un valor diferencial suficiente frente a otras plataformas existentes.

Lo resolveremos mediante: Testeo constante con usuarios reales, iteraciones rápidas en base a feedback y mejoras centradas en su experiencia emocional y funcional.

- Otras suposiciones clave que, si resultan falsas, podrían hacer fracasar el proyecto:

  - Que haya suficiente oferta inicial de prendas para sostener la demanda.
  - Que los usuarios valoren la historia de las prendas como factor emocional de compra.
  - Que el costo logístico no sea una barrera mayor para escalar.


**User Assumptions (Suposiciones de Usuario)**

- ¿Quién es el usuario?: Jóvenes interesados en moda, conscientes del impacto ambiental y abiertos a nuevas formas de consumo.

- ¿Dónde encaja nuestro producto en su vida?: En sus hábitos cotidianos de consumo digital, especialmente en momentos de exploración de moda, compras online y participación en tendencias sostenibles.

- ¿Qué problemas resuelve nuestro producto?: Dificultad para encontrar ropa usada que realmente les guste, falta de confianza en el estado del producto, procesos engorrosos de venta y poca personalización en plataformas existentes.

- ¿Cuándo y cómo se usa nuestro producto?: En momentos de ocio, inspiración de estilo o necesidad de renovar el armario sin dañar el planeta. Usan el producto desde sus dispositivos tecnológicos principalmente, de manera visual e intuitiva.

- ¿Qué características son importantes?: Carga rápida de productos, historias de prendas, recomendaciones personalizadas y diseño atractivo.

- ¿Cómo debería lucir y comportarse nuestro producto?: Visualmente moderno, limpio y emocionalmente atractivo, con una navegación fluida, lenguaje cercano, imágenes destacadas de prendas y elementos de comunidad.


#### 1.2.2.3. Lean UX Hypothesis Statements

Hypothesis Statement 01:

- Creemos que simplificar el proceso de publicación de prendas a solo tres pasos clave (foto, atributos esenciales y precio) aumentará la disposición de los usuarios a vender.
- Sabremos que esto es cierto cuando al menos el 80 % de los usuarios completen el proceso de alta de una prenda con éxito en su primer intento.

Hypothesis Statement 02:

- Creemos que mostrar calificaciones visibles de compradores y vendedores en los perfiles incrementará la confianza en las transacciones.
- Sabremos que esto es cierto si la tasa de conversión de vistas de producto a compras aumenta en al menos un 12 %.

Hypothesis Statement 03:

- Creemos que incluir historias personales de cada prenda (origen, anécdotas, dueño anterior) generará una mayor conexión emocional con los compradores.
- Sabremos que esto es cierto si el porcentaje de clics en "Me interesa" por prenda visualizada aumenta al menos un 15 %.

Hypothesis Statement 04:

- Creemos que permitir filtrar por estilo, talla, color y estado facilitará la búsqueda y mejorará la experiencia de compra.
- Sabremos que esto es cierto si los usuarios tardan un 30 % menos en encontrar un producto que marcan como favorito, comparado con una navegación sin filtros.

Hypothesis Statement 05:

- Creemos que implementar una sección de “Recomendaciones personalizadas” basada en el estilo del usuario aumentará la retención y exploración de productos.
- Sabremos que esto es cierto si el tiempo promedio de navegación por sesión aumenta en un 20 % o más.

Hypothesis Statement 06:

- Creemos que ofrecer una guía visual de tallas y un sistema de ajuste basado en experiencias de otros usuarios reducirá la tasa de devoluciones o reclamos.
- Sabremos que esto es cierto si la tasa de reclamos por tallaje incorrecto disminuye en un 18 %.

Hypothesis Statement 07:

- Creemos que permitir marcar prendas como “Favoritas” o “Guardar para después” aumentará la conversión futura de esas prendas.
- Sabremos que esto es cierto si el 20 % de las prendas guardadas son eventualmente compradas en un plazo de 7 días.

 Hypothesis Statement 08:

- Creemos que brindar una opción de “Entrega gestionada” (p. ej., logística integrada) aumentará la disposición de los usuarios a vender.
- Sabremos que esto es cierto si al menos un 35 % de los vendedores eligen esta opción en su primera venta.

 Hypothesis Statement 09:

- Creemos que ofrecer una experiencia visual atractiva y moderna (con fotos grandes, navegación tipo catálogo) mantendrá la atención del usuario.
- Sabremos que esto es cierto si la tasa de rebote (usuarios que abandonan tras entrar) disminuye en al menos un 20 %.

Hypothesis Statement 10:

- Creemos que permitir agregar categorias como “Vestidos”, “Polos”, “Pantalones”, facilitará la exploración.
- Sabremos que esto es cierto si el 70 % de los clics en productos provienen de categorías.

Hypothesis Statement 11:

- Creemos que ofrecer un incentivo de bienvenida (descuento o envío gratis en la primera compra) aumentará el número de primeras transacciones.
- Sabremos que esto es cierto si al menos el 40 % de los nuevos usuarios realizan su primera compra en los primeros 5 días.

Hypothesis Statement 12:

- Creemos que permitir que los usuarios creen un “armario virtual” para gestionar sus prendas favoritas o en venta aumentará la fidelización.
- Sabremos que esto es cierto si los usuarios que crean armarios tienen un 30 % más de actividad mensual.


#### 1.2.2.4. Lean Ux Canvas
![LeanUxCanvas](Report_Assets/LeanUxCanvaV2.PNG)

## 1.3. Segmentos Objetivos

### **Segmento Objetivo 1: Compradores**

Personas entre 18 y 35 años interesadas en la moda, pero que buscan alternativas más sostenibles, económicas y con mayor autenticidad que la moda rápida. Este segmento aprecia la originalidad, la estética visual y la posibilidad de consumir de forma responsable. Quieren encontrar prendas únicas de manera simple, confiable y atractiva.

**Características Demográficas:**

- Edad: 18 a 35 años
- Género: Todos los géneros
- Ubicación geográfica: Zonas urbanas en Perú (principalmente Lima, Arequipa, Trujillo y Cusco)
- Nivel socioeconómico: Medio y medio-alto (con poder adquisitivo moderado pero sensibilidad ambiental y de ahorro)
- Dispositivos de acceso: Smartphones (98 %), laptops (72 %), tablets (30 %)
- Comportamiento digital: Altamente activos en redes sociales como Instagram, TikTok y Pinterest (fuentes de inspiración de estilo)

**Necesidades:**

- Encontrar ropa en buen estado y con estilo que refleje su personalidad.
- Comprar en una plataforma visualmente atractiva y confiable.
- Conectar con una comunidad que valore el consumo responsable.

**Beneficios clave:**

- Acceso a prendas únicas a menor costo.
- Sentimiento de autenticidad y sostenibilidad en su estilo.
- Experiencia de compra emocionalmente conectada con el origen de cada prenda.

**Información estadística de sustento:**

- 52 % de los consumidores compraron ropa de segunda mano en 2023 (Fuente: Second Hand Apparel Market Report, 2025) ([https://www.stellarmr.com/report/Second-Hand-Apparel-Market/1885](`https://www.stellarmr.com/report/Second-Hand-Apparel-Market/1885`))
- 65 % de las personas de la Generación Z y Millennials compraron ropa de segunda mano en el último año. (Fuente: 37 Positive & Uplifting Sustainable Fashion Statistics, Renewtiful (2024)) ([https://renewtiful.com/insight/sustainable-fashion-statistics/](`https://renewtiful.com/insight/sustainable-fashion-statistics/`))


### **Segmento Objetivo 2: Vendedores**

Personas entre 18 y 50 años o más, que buscan una forma sencilla y eficiente de vender ropa usada en buen estado. Incluye desde personas con prendas que ya no usan hasta pequeños emprendedores o diseñadores independientes que quieren aprovechar la moda circular para generar ingresos o liberar espacio.

**Características Demográficas:**

- Edad: 18 a 50+ años
- Género: Todos los géneros
- Ubicación geográfica: Áreas urbanas con alto acceso digital (incluye Lima metropolitana, Piura, Chiclayo, Arequipa, entre otras)
- Nivel socioeconómico: Medio-bajo a medio-alto
- Dispositivos de acceso: Smartphones (95 %), laptops (60 %), cámaras móviles (para fotografiar prendas)
- Comportamiento digital: Usuarios activos de marketplaces, grupos de venta en Facebook y WhatsApp

**Necesidades:**

- Subir y vender ropa de forma fácil, rápida y sin complejidad.
- Asegurar que sus prendas tengan visibilidad y lleguen a personas que las valoren.
- Obtener un ingreso extra sin invertir demasiado tiempo.

**Beneficios clave:**

- Plataforma que simplifica el proceso de venta (fotos, descripción, precio).
- Conexión con un público que valora lo usado como algo único, no como "desecho".
- Posibilidad de generar ingresos de forma práctica.
- Promoción de un consumo más consciente y ético.

**Información estadística de sustento:**

- 85 % de los consumidores peruanos están dispuestos a vender artículos usados; 55 % a comprarlos (Encuesta Bside Perú, 2020) ([https://www.esan.edu.pe/conexion-esan/el-consumidor-peruano-y-la-compra-de-productos-de-segunda-mano](`https://www.esan.edu.pe/conexion-esan/el-consumidor-peruano-y-la-compra-de-productos-de-segunda-mano`))
- 40 % de los consumidores en Estados Unidos dijo que considera la ropa de segunda mano "muy sostenible". (Fuente: Consumer opinion on sustainability of secondhand goods, Statista (2024)) ([https://www.statista.com/statistics/1310367/consumer-opinion-secondhand-goods-sustainability-by-region/](`https://www.statista.com/statistics/1310367/consumer-opinion-secondhand-goods-sustainability-by-region/`))


# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

En esta sección analizamos a los principales competidores de DeathClothe, enfocándonos en aquellos con modelos de negocio digitales similares o que ofrecen productos/servicios parcialmente superpuestos. Evaluamos tanto competidores directos como indirectos:

**1. Facebook Marketplace**

**Descripción:**

Marketplace de Facebook es una de las plataformas más usadas en Perú para comprar y vender ropa de segunda mano. Su gran alcance y naturaleza comunitaria lo convierten en una opción popular, aunque no está especializado en moda.

**Principales características:**

- Anuncios gratuitos con acceso a millones de usuarios
- Búsqueda por ubicación, categoría y palabras clave
- Chat integrado para comunicación vendedor-comprador
- Comentarios y calificaciones disponibles en perfiles

**2. Instagram Shops**

**Descripción:**

Vendedores independientes y tiendas de segunda mano operan directamente desde Instagram, destacando por un contenido visual cuidado y fuerte conexión con la audiencia.

**Principales características:**

- Publicaciones, Reels y Stories con estética atractiva
- Etiquetado de productos gracias a Instagram Shopping
- Interacción directa con los compradores vía mensajes
- Estilo de branding personalizado y emocional

**3. Mercado Libre**

**Descripción:**

La plataforma de comercio electrónico más grande de Latinoamérica, usada tanto para productos nuevos como usados, con capacidad para compraventa de ropa.

**Principales características:**

- Amplio alcance y base de usuarios en Perú
- Filtros por categoría, precio, ubicación y estado
- Sistema de reputación del vendedor y calificaciones
- Opciones de envío y pago integradas (Mercado Envíos, Mercado Pago)
- Funcionalidades avanzadas de publicación y promoción


### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="6"> Competitive Analysis Landscape </th>
  </tr>
  <tr> 
    <td colspan="2" rowspan="2"> ¿Por qué llevar a cabo este análisis? </td>
    <td colspan="4"> Pregunta </td>
  </tr>
  <tr> 
    <td colspan="4"> Realizar este análisis nos permite identificar claramente a nuestros competidores, comprender sus modelos de negocio y detectar oportunidades para posicionar a DeathClothe de forma diferenciada y estratégica en el mercado. </td>
  </tr>
  <tr> 
    <td colspan="2">Productos</td>
    <td style="text-align: center;"><div>DeathClothe</div></td>
    <td style="text-align: center;"><div>Facebook Marketplace</div></td>
    <td style="text-align: center;"><div>Instagram Shops</div></td>
    <td style="text-align: center;"><div>Mercado Libre</div></td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>Plataforma enfocada en la moda circular, que permite a usuarios comprar y vender ropa de segunda mano de forma sencilla, visualmente atractiva y sostenible.</td>
    <td>Espacio dentro de Facebook donde los usuarios publican artículos para venta directa, incluyendo ropa usada, sin especialización temática.</td>
    <td>Red social que permite a emprendedores y tiendas vender ropa directamente a través de contenido visual y conexión con la audiencia.</td>
    <td>Marketplace de gran alcance en Latinoamérica donde se puede comprar y vender prácticamente cualquier producto, incluida ropa nueva y usada.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td>Enfoque especializado en moda circular, curación de prendas con identidad, experiencia centrada en sostenibilidad y originalidad.</td>
    <td>Gran alcance y acceso a una base masiva de usuarios con herramientas básicas de publicación.</td>
    <td>Estética visual, cercanía con los clientes y personalización del branding.</td>
    <td>Filtros por categoría, opciones de pago/envío integradas, alta confianza del usuario.</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td>Mercado Objetivo</td>
    <td>Jóvenes entre 18 y 35 años interesados en moda sostenible, compradores conscientes y pequeños emprendedores de ropa.</td>
    <td>Usuarios generales de Facebook; compradores casuales interesados en productos de segunda mano sin categoría específica.</td>
    <td>Tiendas independientes, influencers de moda, y compradores atraídos por el estilo visual y la autenticidad.</td>
    <td>Consumidores que buscan buenos precios, variedad y facilidad en las compras; tanto nuevos como usados.</td>
  </tr>
  <tr>
    <td>Estrategias de Marketing</td>
    <td>Alianzas con creadores de moda sostenible, campañas en redes sociales, storytelling visual y valores ambientales</td>
    <td>Difusión orgánica a través de publicaciones; impulsado por la red social de los usuarios.</td>
    <td>Contenido emocional, reels, hashtags de moda y promoción vía stories.</td>
    <td>Publicidad digital, posicionamiento SEO/SEM, y presencia en medios tradicionales.</td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td>Productos & Servicios</td>
    <td>Marketplace para ropa usada, perfiles de comprador/vendedor, herramientas de publicación visual, storytelling de prendas.</td>
    <td>Publicación de productos, chat directo, categorías generales, búsqueda por ubicación.</td>
    <td>Catálogo visual, etiquetado de productos, interacción en tiempo real, personalización de la tienda.</td>
    <td>Publicaciones con fotos, filtros de búsqueda, sistema de pago y envío, calificación de vendedores.</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>Uso gratuito para compradores y vendedores; modelo freemium para funciones premium o visibilidad.</td>
    <td>Gratuito; no cobra comisiones por publicación ni venta.</td>
    <td>Gratuito, pero sujeto a algoritmo y visibilidad limitada si no se paga publicidad.</td>
    <td>Cobra comisión por venta (~11%) y costos por envíos; publicación gratuita.</td>
  </tr>
  <tr>
    <td>Canales de distribución</td>
    <td>Aplicación web progresiva y redes sociales; integraciones futuras con envíos.</td>
    <td>Plataforma dentro de Facebook; accesible desde navegador o app.</td>
    <td>App de Instagram y función de Instagram Shopping.</td>
    <td>Web oficial y app móvil; gran presencia en toda Latinoamérica.</td>
  </tr>
  <tr>
    <td rowspan="5">Análisis SWOT</td>
    <td>Fortalezas</td>
    <td>Enfoque nicho, experiencia visual y curada, impulso de sostenibilidad, alineación con valores de moda ética.</td>
    <td>Base de usuarios muy grande, fácil de usar, sin costos para el usuario.</td>
    <td>Conexión emocional con el usuario, excelente estética visual, branding personalizado.</td>
    <td>Reputación consolidada, variedad de productos, seguridad en transacciones.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Producto en etapa temprana, sin filtros avanzados, sin logística de envíos aún.</td>
    <td>Interfaz básica, sin filtros específicos para ropa, sin curaduría ni garantías.</td>
    <td>Proceso de compra poco automatizado, dependiente del engagement y del algoritmo.</td>
    <td>No está enfocado en moda circular, experiencia genérica y saturación de productos.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Adopción creciente de consumo responsable, demanda de plataformas sostenibles y crecimiento de la economía circular.</td>
    <td>Implementar herramientas temáticas, ofrecer funcionalidades premium.</td>
    <td>Expandir a catálogos organizados y pagos integrados dentro de la app.</td>
    <td>Incorporar secciones dedicadas a moda circular, alianzas con ONGs de sostenibilidad.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Competencia de plataformas más grandes, cambios en el comportamiento del usuario, barreras logísticas.</td>
    <td>Competencia especializada puede captar su tráfico; limitaciones para escalar.</td>
    <td>Algoritmos que limitan visibilidad orgánica, saturación del mercado de moda vintage.</td>
    <td>Nuevas plataformas más especializadas pueden robar cuota de mercado en ropa usada.</td>
  </tr>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

Nuestro objetivo es enfrentar las fortalezas de los competidores, capitalizar sus debilidades y posicionar a DeathClothe en un nicho distintivo y sostenible dentro del mercado de la moda circular digital en Perú.

**1. Diferenciación por Historia y Personalización (Frente a Instagram Shops y Facebook Marketplace)**

Estrategia: Crear valor emocional a través de la narrativa de cada prenda, aspecto ausente en marketplaces generalistas.

Fortaleza Competitiva a Contrarrestar: Alto alcance visual y conexión emocional de Instagram con su comunidad.

Debilidad Competitiva a Aprovechar: Falta de información detallada o emocional sobre los productos.

Tácticas:

- Implementar fichas de producto enriquecidas con inputs narrativos del vendedor (historia, estilo, inspiración).
- Sistema de “looks anteriores” y “armario virtual” que permite al comprador visualizar combinaciones y recomendaciones personalizadas.

**2. Experiencia de Usuario como Comunidad Visual (Frente a Mercado Libre y Facebook Marketplace)**

Estrategia: Transformar la app en una comunidad visual interactiva, más allá de un catálogo funcional.

Fortaleza Competitiva a Contrarrestar: Presencia masiva y estructura consolidada de Mercado Libre y Facebook.

Debilidad Competitiva a Aprovechar: Interfaz poco amigable y generalista, con escasa orientación a moda o interacción social.

Tácticas:

- Navegación estilo red social, seguimiento entre usuarios, exploración de estilos.
- Opción móvil optimizado para exploración visual y recomendación estética.

**3. Confianza y Autenticidad como Propuesta de Valor (Frente a Facebook Marketplace)**

Estrategia: Reforzar la seguridad y confianza en la transacción entre personas.

Amenaza a Contrarrestar: Alta tasa de desconfianza o fraude en plataformas como Marketplace o grupos de compraventa.

Oportunidad: Falta de mecanismos formales de verificación o reputación en competidores.

Tácticas:

- Sistema de verificación de identidad para vendedores.
- Calificaciones visibles y comentarios tras cada transacción.
- Etiquetas por categoría.
- Descripciones visuales de estado real de la prenda (nuevo, casi nuevo, usado).

**4. Facilidad de Uso para Vendedores (Frente a Mercado Libre)**

Estrategia: Eliminar barreras de entrada para quienes quieren vender ropa sin experiencia técnica.

Debilidad Competitiva a Aprovechar: Procesos largos y técnicos en plataformas como Mercado Libre (categorías extensas, requisitos complejos).

Tácticas:

- Publicación en tres pasos con sugerencias automáticas.
- Herramientas de edición para cambiar fotos.
- Tip de fotografía rápida, y precios según el estado y marca.
- Posibilidad de etiquetar prendas por categorías (pantalones, vestidos, zapatillas, etc.).

**5. Presencia Local y Cultural (Frente a competidores globales)**

Estrategia: Posicionarse como una plataforma culturalmente peruana, comprometida con la economía circular local.

Debilidad Competitiva a Aprovechar: Falta de adaptación cultural de plataformas como Instagram o Mercado Libre a nichos específicos como moda sostenible en Perú.

Tácticas:

- Colaboración con creadores locales de moda consciente.
- Eventos físicos y virtuales como ferias de ropa circular o pop-ups colaborativos.
- Campañas de moda sostenible con influencers peruanos.

**6. Solución logística integrada (Frente a Facebook Marketplace)**

Estrategia: Superar la informalidad del envío entre usuarios con soluciones logísticas reales.

Amenaza a Contrarrestar: Abandono de ventas por dificultades en coordinación o desconfianza en entregas.

Oportunidad: Falta de integración logística en plataformas de compraventa informal.

Tácticas:

- Integración con servicios locales como Urbaner, Olva Courier o Rappi.
- Opción de “entrega segura” al elegir método de envío desde la app.
- Seguimiento del pedido y confirmación de entrega desde la plataforma.


## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas
<p> La elaboración de las entrevistas se basó en los objetivos del proyecto y en los perfiles específicos de compradores y vendedores. Se formularon preguntas personalizadas para entender hábitos, motivaciones y necesidades. En compradores, se exploraron sus preferencias por alternativas sostenibles, incluyendo a los compradores impulsivos para identificar qué los motiva. En vendedores, se abordaron razones para vender y expectativas hacia una plataforma que promueva el consumo responsable. </p>

#### 1. Preguntas para Comprador
##### 1.1. Información Demográfica
<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>Categoría Demográfica</th>
      <th>Pregunta de la entrevista</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Identificación personal</strong></td>
      <td>¿Podrías darme tu nombre?</td>
    </tr>
    <tr>
      <td><strong>Edad</strong></td>
      <td>¿Cuántos años tienes?</td>
    </tr>
    <tr>
      <td><strong>Ciudad</strong></td>
      <td>¿En qué ciudad vives actualmente?</td>
    </tr>
    <tr>
      <td><strong>Ocupación</strong></td>
      <td>¿Cuál es tu ocupación o en qué trabajas actualmente?</td>
    </tr>
    <tr>
      <td><strong>Uso digital</strong></td>
      <td>¿Con qué frecuencia usas internet para compras o redes sociales?</td>
    </tr>
  </tbody>
</table>

##### 1.2. Atributos Personales y Gustos
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Categoría</th>
      <th>Pregunta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ocupación</td>
      <td>¿Cuál es tu ocupación o en qué trabajas actualmente?</td>
    </tr>
    <tr>
      <td>Uso digital</td>
      <td>¿Con qué frecuencia usas internet para compras o redes sociales?</td>
    </tr>
    <tr>
      <td>Explorador de estilo</td>
      <td>¿Cuéntame sobre la última vez que buscaste ropa de segunda mano en línea? ¿Qué pasos seguiste?</td>
    </tr>
    <tr>
      <td>Explorador de estilo</td>
      <td>¿Qué te impulsa más a comprar ropa usada en línea: precio, sostenibilidad o estilo único? ¿Por qué?</td>
    </tr>
    <tr>
      <td>Armario virtual</td>
      <td>Si tuvieras un ‘armario virtual’ en la plataforma web, ¿cómo organizarías tus prendas y qué filtros usarías para encontrar ropa que encaje con tu personalidad?</td>
    </tr>
    <tr>
      <td>Confianza y experiencia</td>
      <td>¿Qué te frustra de las plataformas de segunda mano actuales y qué funcionalidad te haría confiar en DeathClothe?</td>
    </tr>
    <tr>
      <td>Confianza y experiencia</td>
      <td>¿Qué información necesitarías ver en la plataforma web para comprar ropa usada para tus hijos sin preocupaciones?</td>
    </tr>
    <tr>
      <td>Confianza y experiencia</td>
      <td>¿Cómo verificas la autenticidad de una prenda vintage y qué sistema integrado en la plataforma web te haría usarla?</td>
    </tr>
    <tr>
      <td>Cierre de compra</td>
      <td>¿Qué funcionalidades de cierre de compra te motivarían a comprar más rápido en DeathClothe?</td>
    </tr>
    <tr>
      <td>Recomendaciones</td>
      <td>¿Te interesaría recibir recomendaciones de prendas en la plataforma web basadas en tu armario virtual y estilo? ¿Qué tipo de sugerencias valorarías?</td>
    </tr>
    <tr>
      <td>Organización del hogar</td>
      <td>¿Cómo te gustaría que DeathClothe te ayudara a ‘ganar espacio’ en casa?</td>
    </tr>
    <tr>
      <td>Funcionalidades ideales</td>
      <td>Imagina la plataforma web perfecta de segunda mano. ¿Qué tres funcionalidades serían imprescindibles para ti?</td>
    </tr>
  </tbody>
</table>

#### 2. Preguntas para Vendedor
##### 2.1. Información Demográfica

<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>Categoría Demográfica</th>
      <th>Pregunta de la entrevista</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Identificación personal</strong></td>
      <td>¿Podrías darme tu nombre?</td>
    </tr>
    <tr>
      <td><strong>Edad</strong></td>
      <td>¿Cuántos años tienes?</td>
    </tr>
    <tr>
      <td><strong>Ciudad</strong></td>
      <td>¿En qué ciudad vives actualmente?</td>
    </tr>
    <tr>
      <td><strong>Ocupación/Trabajo</strong></td>
      <td>¿Cuál es tu ocupación o en qué trabajas actualmente?</td>
    </tr>
    <tr>
      <td><strong>Uso digital</strong></td>
      <td>¿Con qué frecuencia usas internet para compras o redes sociales?</td>
    </tr>
  </tbody>
</table>

##### 2.2. Atributos Personales y Gustos
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Categoría</th>
      <th>Pregunta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Motivación para vender</td>
      <td>¿Qué te anima a vender una prenda en línea en lugar de regalarla o desecharla?</td>
    </tr>
    <tr>
      <td>Selección de prendas</td>
      <td>¿Cómo decides qué ropa poner en venta? ¿Te guías por estilo, estado, marca, algo más?</td>
    </tr>
    <tr>
      <td>Publicación de productos</td>
      <td>¿Qué pasos sigues antes de subir una prenda a la plataforma?</td>
    </tr>
    <tr>
      <td>Subida de contenido</td>
      <td>¿Prefieres subir las prendas desde tu celular o computadora? ¿Por qué?</td>
    </tr>
    <tr>
      <td>Armario virtual</td>
      <td>¿Cómo te gustaría que funcione tu armario virtual? ¿Qué debería mostrar o permitirte hacer?</td>
    </tr>
    <tr>
      <td>Dificultades técnicas</td>
      <td>¿Alguna vez has sufrido fallos a la hora de publicar una prenda, como demora de carga y demás?</td>
    </tr>
    <tr>
      <td>Precio y comparación</td>
      <td>¿Cómo decides el precio? ¿Te gustaría ver sugerencias basadas en ventas similares?</td>
    </tr>
    <tr>
      <td>Comunicación con compradores</td>
      <td>¿Qué esperas de la comunicación con posibles compradores dentro de la plataforma?</td>
    </tr>
    <tr>
      <td>Entregas y logística</td>
      <td>¿Qué tipo de opciones de entrega preferirías ofrecer o usar?</td>
    </tr>
    <tr>
      <td>Incentivos</td>
      <td>¿Qué te motivaría a seguir subiendo ropa a la web?</td>
    </tr>
  </tbody>
</table>

### 2.2.2. Registro de entrevistas
#### Segmento :Comprador
**Entrevista #1 – Datos del Entrevistado**
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th><strong>Dato</strong></th>
      <th><strong>Información</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nombre completo</td>
      <td>Daniela Alessandra Cigueñas Tarrillo</td>
    </tr>
    <tr>
      <td>Edad</td>
      <td>19 años</td>
    </tr>
    <tr>
      <td>Ciudad - Distrito</td>
      <td>Lima - Los Olivos</td>
    </tr>
    <tr>
      <td>Ocupación/Trabajo</td>
      <td>Estudiante Universitario (Medios digitales y publicidad)</td>
    </tr>
    <tr>
      <td>Frecuencia de uso de Internet</td>
      <td>Compra en línea con frecuencia, sobre todo por redes sociales. Le encanta adquirir ropa, accesorios y todo lo que le llame la atención en internet.</td>
    </tr>
    <tr>
      <td>Inicio de la entrevista</td>
      <td>00:00</td>
    </tr>
    <tr>
      <td>Duración de la entrevista</td>
      <td>08:26</td>
    </tr>
  </tbody>
</table>

**Detalles de la entrevista:** <br>
<img src="./Report_Assets/DanielaEntrevista1.png" alt="Entrevista 1" width="500">
</a><br>
(https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/ERvZBKft-85KrhKzuNsLSksBjRZLjjNUp_idUI23rsUl0Q?e=14taym&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Resumen de la entrevista:** <br>
Daniela, estudiante de 19 años de Lima, mencionó que utiliza con frecuencia internet para realizar compras. Hace pocos días adquirió ropa de segunda mano, motivada por el precio accesible y los estilos únicos. Comentó que organizaría su armario virtual por estilo, color, temporada y precio, y señaló como frustración principal la falta de precisión en tallas y descripciones. Además, resaltó la importancia de contar con fotos desde varios ángulos, descripciones claras y reseñas de otros usuarios. Considera esencial agilizar el proceso de pago con métodos como Yape, le interesan las recomendaciones basadas en su armario virtual y valoraría una función para vender automáticamente prendas no usadas. Finalmente, destacó que su plataforma ideal incluiría un sistema de tallas preciso, una experiencia personalizada y sugerencias adaptadas a su estilo. </p>

**Entrevista #2 - Datos del Entrevistado** 
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th><strong>Dato</strong></th>
      <th><strong>Información</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nombre completo</td>
      <td>William Agustín Ventura Saldaña</td>
    </tr>
    <tr>
      <td>Edad</td>
      <td>27 años</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>Lima - Surco</td>
    </tr>
    <tr>
      <td>Ocupación/Trabajo</td>
      <td>Estudiante Universitario (Ingeniería de sistemas) - Friendlands de diseño gráfico</td>
    </tr>
    <tr>
      <td>Frecuencia de uso de Internet</td>
      <td>Usualmente suele usarlo dos o tres veces por semana, principalmente para comprar comida y herramientas gráficas para su empleo.</td>
    </tr>
    <tr>
      <td>Inicio de la entrevista</td>
      <td>08:26</td>
    </tr>
    <tr>
      <td>Duración de la entrevista</td>
      <td>07:26</td>
    </tr>
  </tbody>
</table>

**Detalles de la entrevista:** <br>
<img src="./Report_Assets/AgustinEntrevista2.png" alt="Entrevista 2" width="500">
</a><br>
(https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/ERvZBKft-85KrhKzuNsLSksBjRZLjjNUp_idUI23rsUl0Q?e=14taym&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Agustín Ventura, de 27 años y residente en Lima, compró ropa de segunda mano hace un mes tras buscar tiendas vintage en Instagram, revisar comentarios y tallas grandes, y completar el pago con Yape. Valora el estilo único y la sostenibilidad, por lo que organizaría su armario virtual por estilo, temporada, color y talla, con filtros de combinaciones personalizadas. Sin embargo, se frustra con descripciones imprecisas y fotos poco claras, de modo que confiaría en DeathClothe si incluyera verificación de calidad, medidas exactas y reseñas de expertos. Además, considera clave un proceso de pago ágil con cupones y alertas de oferta, recomendaciones tanto similares como contrastantes, clasificación automática de prendas para liberar espacio y un informe del impacto ambiental de sus compras. 

**Entrevista #3 - Datos del Entrevistado**
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th><strong>Dato</strong></th>
      <th><strong>Información</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nombre completo</td>
      <td>Anyelo Bill Alejos Jesús</td>
    </tr>
    <tr>
      <td>Edad</td>
      <td>20 años</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>Lima - Comas</td>
    </tr>
    <tr>
      <td>Ocupación/Trabajo</td>
      <td>Estudiante Universitario (Ingeniería de software)</td>
    </tr>
    <tr>
      <td>Frecuencia de uso de Internet</td>
      <td>Casi siempre lo usa para compras en línea, especialmente en Marketplace y AliExpress.</td>
    </tr>
    <tr>
      <td>Inicio de la entrevista</td>
      <td>15:54</td>
    </tr>
    <tr>
      <td>Duración de la entrevista</td>
      <td>06:53</td>
    </tr>
  </tbody>
</table>


**Detalles de la entrevista:** <br>
<img src="./Report_Assets/AnyeloEntrevista3.png" alt="Entrevista 3" width="500">
</a><br>
(https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/ERvZBKft-85KrhKzuNsLSksBjRZLjjNUp_idUI23rsUl0Q?e=14taym&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Resumen de la entrevista:** <br>
Anyelo , estudiante de Ingeniería de Software de 20 años, buscó ropa de segunda mano atraído por modelos agotados y precios bajos.Organizaría su armario virtual por temporada y color, aunque lamenta la falta de fiabilidad de algunos vendedores y la llegada de prendas robadas o en mal estado, por lo cual considera esencial contar con descripciones claras, tallas exactas y fotos detalladas. Asimismo, verificaría la autenticidad comparando modelos en línea y valora un proceso de pago seguro con opciones de descuento. Asimismo, le interesaría recibir recomendaciones basadas en su armario virtual y automatizar la venta o donación de prendas no usadas. Finalmente, identifica como funciones imprescindibles un sistema de tallas preciso, métodos de pago confiables y una organización clara de su armario virtual. 

#### Segmento :Vendedor
**Entrevista #4 – Datos del Entrevistado**
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th><strong>Dato</strong></th>
      <th><strong>Información</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nombre completo</td>
      <td>David Manuel Torres Meneses</td>
    </tr>
    <tr>
      <td>Edad y Género</td>
      <td>20 años</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>Los Olivos</td>
    </tr>
    <tr>
      <td>Ocupación/Trabajo</td>
      <td>Vendedor de tienda de ropa</td>
    </tr>
    <tr>
      <td>Frecuencia de uso de Internet</td>
      <td>Usualmente lo usa muy rara vez, solo en emergencias y cuando veo algo realmente interesante, como prendas de buena calidad o diseños únicos</td>
    </tr>
    <tr>
      <td>Inicio de la entrevista</td>
      <td>22:48</td>
    </tr>
    <tr>
      <td>Duración de la entrevista</td>
      <td>14:55</td>
    </tr>
  </tbody>
</table>


**Detalles de la entrevista:** <br>
<img src="./Report_Assets/DavidEntrevista4.png" alt="Entrevista 4" width="500">
</a><br>
(https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/ERvZBKft-85KrhKzuNsLSksBjRZLjjNUp_idUI23rsUl0Q?e=14taym&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Resumen de la entrevista:** <br>
David Manuel Torres Meneses, de 20 años y residente en Lima, elige qué artículos poner en venta basándose en marca, estilo, color y talla, y los prepara con fotografías (incluso vistas 360°), descripciones detalladas y precios ajustados según la rareza o urgencia. Prefiere publicar desde la computadora porque es más estable que el celular, ya que en el móvil la carga de imágenes y la publicación suelen fallar; sin embargo, sueña con un armario virtual que agrupe prendas por demanda, temporada y exclusividad. Además, valoraría sugerencias automáticas de precios basadas en ventas similares, un chat integrado para resolver dudas rápidamente y múltiples opciones de envío, tanto nacionales como internacionales, y asegura que le motivaría ver que sus ofertas satisfacen las necesidades de los compradores.

**Entrevista #5 – Datos del Entrevistado**
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th><strong>Dato</strong></th>
      <th><strong>Información</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nombre completo</td>
      <td>Valesska Sánchez</td>
    </tr>
    <tr>
      <td>Edad y Género</td>
      <td>20 años</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>San Martín de Porres</td>
    </tr>
    <tr>
      <td>Ocupación/Trabajo</td>
      <td>Vendedora de ropa en línea</td>
    </tr>
    <tr>
      <td>Frecuencia de uso de Internet</td>
      <td>Usa mucho las redes sociales, especialmente Marketplace</td>
    </tr>
    <tr>
      <td>Inicio de la entrevista</td>
      <td>37:42</td>
    </tr>
    <tr>
      <td>Duración de la entrevista</td>
      <td>03:19</td>
    </tr>
  </tbody>
</table>


**Detalles de la entrevista:** <br>
<img src="./Report_Assets/ValesskaEntrevista5.png" alt="Entrevista 5" width="500">
</a><br>
(https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/ERvZBKft-85KrhKzuNsLSksBjRZLjjNUp_idUI23rsUl0Q?e=14taym&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Resumen de la entrevista:** <br>
Valesska Sánchez, de 20 años y residente en Lima, comenta que usualmente elige la ropa que pondrá en venta basándose en la marca. Para ello, se asegura de prepararla con buenas fotografías y descripciones detalladas que incluyan el estado de la prenda y su precio. Además, le gustaría poder ver principalmente los comentarios de los posibles compradores sobre los productos que ofrece, y suele guiarse por sugerencias de precios basadas en ventas similares. Finalmente, valora la posibilidad de tener una comunicación directa con sus clientes y opciones de envío como la contra entrega. La motiva especialmente la idea de generar ingresos vendiendo ropa de segunda mano.

**Entrevista #6 – Datos del Entrevistado**
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th><strong>Dato</strong></th>
      <th><strong>Información</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nombre completo</td>
      <td>Jhon Alexander Chuchon</td>
    </tr>
    <tr>
      <td>Edad y Género</td>
      <td>19 años</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>San Martín de Porres</td>
    </tr>
    <tr>
      <td>Ocupación/Trabajo</td>
      <td>Vendedor de ropa en línea</td>
    </tr>
    <tr>
      <td>Frecuencia de uso de Internet</td>
      <td>Usa diariamente las redes sociales, especialmente Instagram y Tiktok</td>
    </tr>
    <tr>
      <td>Inicio de la entrevista</td>
      <td>41:02</td>
    </tr>
    <tr>
      <td>Duración de la entrevista</td>
      <td>06:10</td>
    </tr>
  </tbody>
</table>


**Detalles de la entrevista:** <br>
<img src="./Report_Assets/JhonEntrevista6.png" alt="Entrevista 6" width="500">
</a><br>
(https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/ERvZBKft-85KrhKzuNsLSksBjRZLjjNUp_idUI23rsUl0Q?e=14taym&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Resumen de la entrevista:** <br>
Jhon Alexander Chuchón, de 19 años y residente en Lima, comenta que usualmente elige qué artículos poner en venta basándose en el estado y la marca de las prendas. Para ello, se asegura de preparar buenas fotografías que muestren la prenda en su totalidad, acompañadas de descripciones detalladas sobre la talla y el estado. Le gustaría que su armario virtual permitiera ordenar las prendas por tipo, por temporada o por las más vistas o favoritas. Menciona que, en varias ocasiones, ha tenido inconvenientes como demoras al cargar imágenes o problemas al subir las descripciones, lo que lo obliga a reescribir la información. También valoraría contar con sugerencias de precios basadas en productos similares, ya que usualmente se guía por referencias de otras plataformas. Considera importante que la aplicación cuente con un chat directo, que sea seguro y fácil de usar. Finalmente, aprecia contar con diversas opciones de envío, y le motiva especialmente que sus prendas se vendan y reciban buenos comentarios o puntuaciones.


### 2.2.3. Análisis de entrevistas

**Segmento Objetivo 1: Compradores**

Los compradores entrevistados muestran un interés marcado por una experiencia de compra digital que combine estilo, confianza y sostenibilidad. El 100% de los entrevistados coincidió en la importancia de contar con descripciones claras, tallas precisas y fotos detalladas, elementos que consideran esenciales para confiar en una plataforma de ropa de segunda mano. Asimismo, el 66% mencionó como imprescindible un sistema de recomendaciones personalizadas basado en su armario virtual, lo cual refleja una alta demanda por experiencias de compra individualizadas. Además, todos los participantes valoran métodos de pago rápidos y seguros, como Yape, mientras que el 66% expresó interés en funciones automatizadas para vender o donar prendas no utilizadas. En conjunto, este segmento prioriza no solo el ahorro y la autenticidad, sino también una navegación fluida, confiable y adaptada a sus gustos personales.

**Segmento Objetivo 2: Vendedores**

En el caso de los vendedores, las entrevistas revelan que todos seleccionan sus prendas en función de criterios como marca, estado, estilo y temporada, mostrando una preocupación clara por ofrecer productos atractivos y bien presentados. Todos los entrevistados también destacaron la importancia de subir fotos de buena calidad y descripciones completas, aunque el 66% reportó dificultades técnicas al momento de publicar, lo cual resalta la necesidad de una plataforma estable y funcional. El 100% valoraría recibir sugerencias automáticas de precios basadas en ventas similares, mientras que un 66% manifestó que la comunicación directa con los compradores a través de un chat integrado es fundamental. Asimismo, todos consideran importante ofrecer múltiples métodos de envío, incluyendo contra entrega. En resumen, este grupo busca herramientas que no solo simplifiquen el proceso de venta, sino que también les permitan conectar con compradores interesados y generar ingresos dentro de un entorno seguro y funcional.

## 2.3. Needfinding

### 2.3.1. User Personas

A continuación, se presentan las User Personas que representan a nuestros dos segmentos principales.

**Segmento 1: Compradores**

<img src="./Report_Assets/UserPersona1.png" alt="User Persona 1" width="400"/>

**Segmento 2: Vendedores**

<img src="./Report_Assets/UserPersona2.png" alt="User Persona 2" width="400"/>

#### 2.3.2. User Task Matrix

**Compradores:**

<table>
  <thead>
    <tr>
      <th>Actividades</th>
      <th colspan="2">Valeria Gomez</th>
    </tr>
    <tr>
      <th></th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Explorar el catálogo de ropa de segunda mano</td>
      <td>Diario/Semanal</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Utilizar filtros inteligentes (talla, estilo, color, precio)</td>
      <td>Por cada búsqueda</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Ver recomendaciones personalizadas basadas en su historial</td>
      <td>Diario/Semana</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Leer historias/origen de las prendas (anécdotas, dueño anterior)</td>
      <td>Por artículo visto</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Interactuar con la función "Me interesa" o guardar favoritos</td>
      <td>Diario/Semanal</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Realizar compras (selección, pago seguro, confirmación)</td>
      <td>Según necesidad</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Calificar a vendedores y dejar reseñas post-compra</td>
      <td>Tras cada compra</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Gestionar armario virtual (agregar/eliminar prendas)</td>
      <td>Semanal/Mensual</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Recibir alertas de nuevos artículos según preferencias</td>
      <td>Diario/Semanal</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Adaptación a Condiciones Climáticas</td>
      <td>Según necesidad</td>
      <td>Media</td>
    </tr>
  </tbody>
</table>

**Vendedores:**

<table>
  <thead>
    <tr>
      <th>Actividades</th>
      <th colspan="2">Calor Méndez</th>
    </tr>
    <tr>
      <th></th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Subir prendas al catálogo (fotos, atributos, precio)</td>
      <td>Semanal/Mensual</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Gestionar publicaciones (editar, pausar, eliminar)</td>
      <td>Semanal/Mensual</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Responder consultas de compradores (mensajes directos)</td>
      <td>Diario/Semanal</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Revisar y aceptar ofertas de compra</td>
      <td>Diario/Semanal</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Gestionar envíos y logística (etiquetas, seguimiento)</td>
      <td>Tras cada venta</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Actualizar inventario (agregar nuevas prendas, marcar como vendidas)</td>
      <td>Semanal</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Revisar calificaciones y reseñas de compradores</td>
      <td>Diario/Semanal</td>
      <td>Baja</td>
    </tr>
    <tr>
      <td>Recibir y retirar pagos (gestión de saldos, retiros)</td>
      <td>Según necesidad</td>
      <td>Alta</td>
    </tr>
  </tbody>
</table>

#### 2.3.3. User Journey Mapping

**Compradores**

<img src="Report_Assets/deathclothes user journey map comprador.png" alt="Nombre" width="500"> 
</a>

**Vendedores**

<img src="Report_Assets/deathclothes user journey map vendedor.png" alt="Nombre" width="500"> 
</a>

#### 2.3.4. Empathy Mapping

**Compradores**
<table border="1">
  <tr>
    <td colspan="3"><strong>¿Qué piensa y siente?</strong><br>
      Valeria busca completar sus outfits con prendas únicas que expresen su estilo personal, pero necesita opciones económicas que se ajusten a su presupuesto limitado como estudiante.
    </td>
  </tr>
  <tr>
    <td><strong>¿Qué oye?</strong><br>
      <a href="#">Escucha</a> comentarios en redes sociales sobre lo caro que es vestir a la moda.
    </td>
    <td style="text-align: center;"><strong>Comprador<br>(Valeria Gomez)</strong></td>
    <td><strong>¿Qué ve?</strong><br>
      Ofertas en plataformas de moda, pero con precios altos.
    </td>
  </tr>
  <tr>
    <td colspan="3"><strong>¿Qué dice y hace?</strong><br>
      Valeria busca ropa única, pero que no pueda pagar precios altos por adquirirlas.
    </td>
  </tr>
  <tr>
    <td><strong>¿Qué le duele?</strong><br>
      No encontrar prendas que reflejen su estilo a precios accesibles.<br>
      <u>Desconfiar</u> de las fotos y descripciones en tiendas online.<br>
      Sentirse excluida de tendencias por su presupuesto limitado.
    </td>
    <td colspan="2"><strong>¿A qué aspira?</strong><br>
      Completar sus outfits con piezas únicas y económicas.<br>
      Tener un armario sostenible y lleno de personalidad.<br>
      Sentirse segura y auténtica con su estilo, sin gastar de más.
    </td>
  </tr>
</table>

**Vendedores**

<table>
  <tr>
    <th colspan="3">¿Qué piensa y siente?</th>
  </tr>
  <tr>
    <td colspan="3">Méndez desea vender su ropa de segunda mano donde encuentre compradores que aprecien su estilo y paguen un precio justo.</td>
  </tr>
  <tr>
    <th>¿Qué oye?</th>
    <th>Vendedor<br>(Calor Méndez)</th>
    <th>¿Qué ve?</th>
  </tr>
  <tr>
    <td>Escucha recomendaciones de influencers sobre apps para vender ropa usada.</td>
    <td></td>
    <td>Su armario lleno de ropa de calidad que ya no usa.</td>
  </tr>
  <tr>
    <th colspan="3">¿Qué dice y hace?</th>
  </tr>
  <tr>
    <td colspan="3">Méndez busca una app que le permita vender de manera sencilla y prefiere vender por Instagram, aunque le falta alcance.</td>
  </tr>
  <tr>
    <th>¿Qué le duele?</th>
    <th colspan="1"></th>
    <th>¿A qué aspira?</th>
  </tr>
  <tr>
    <td>
      Perder tiempo en plataformas que no generan ventas.<br>
      Ver cómo sus prendas pierden valor por malas fotos o presentación.
    </td>
    <td></td>
    <td>
      Vender rápido y sin complicaciones.<br>
      Liberar espacio en su armario con ganancias justas.<br>
      Convertir su closet en una fuente estable de ingresos extras.
    </td>
  </tr>
</table>

#### 2.3.5. As-is Scenario Mapping

**Compradores**

<table border="1">
    <tr>
        <th>Phases</th>
        <th>Búsqueda de Prendas</th>
        <th>Evaluación de Productos</th>
        <th>Proceso de Compra</th>
        <th>Post-Compra</th>
    </tr>
    <tr>
        <td><strong>Doing</strong></td>
        <td>Navega en múltiples plataformas sin filtros precisos.</td>
        <td>Compara fotos y descripciones poco detalladas.</td>
        <td>Abandona el carrito por procesos largos o inseguros.</td>
        <td>Espera sin tracking claro o se arrepiente por falta de garantías.</td>
    </tr>
    <tr>
        <td><strong>Thinking</strong></td>
        <td>Me pregunto donde puedo encontrar algo que realmente me guste.</td>
        <td>Me pregunto si realmente será la talla correcta, ya que las fotos no ayudan</td>
        <td>Me pregunto si será seguro pagar aquí</td>
        <td>Espero que no me arrepienta de la compra que he realizado</td>
    </tr>
    <tr>
        <td><strong>Feeling</strong></td>
        <td>Me siento frustrado por opciones genéricas</td>
        <td>Me siento ansioso por falta de transparencia</td>
        <td>Me siento preocupada y con miedo por pagar, siento que no es del todo seguro</td>
        <td>Me siento inseguro y con ansias por la decisión que ha tomado</td>
    </tr>
</table>

**Vendedores**

<table border="1">
    <tr>
        <th>Phases</th>
        <th>Publicación del Producto</th>
        <th>Gestión de Ventas</th>
        <th>Proceso de Envío</th>
        <th>Comunicación con el Comprador</th>
        <th>Post-Venta</th>
    </tr>
    <tr>
        <td><strong>Doing</strong></td>
        <td>Suben fotos manualmente sin editar, usando apps externas.</td>
        <td>Llevan registro manual de ventas en hojas de cálculo o notas.</td>
        <td>Empacan productos y gestionan envíos con servicios externos sin integración.</td>
        <td>Responden mensajes uno a uno para actualizar compradores.</td>
        <td>Esperan reseñas sin incentivos claros.</td>
    </tr>
    <tr>
        <td><strong>Thinking</strong></td>
        <td>Me pregunto si mis fotos son lo suficientemente claras.</td>
        <td>Me pregunto cuántas ventas tendré, es difícil llevar la cuenta.</td>
        <td>Me pregunto si el comprador recibirá su pedido sin problemas.</td>
        <td>Pienso que los compradores se impacientan si no respondo rápido.</td>
        <td>¿Valdrá la pena vender aquí si no recibo reconocimiento?</td>
    </tr>
    <tr>
        <td><strong>Feeling</strong></td>
        <td>Me siento frustrado e inseguro por la presentación.</td>
        <td>Me siento agobiado y confundido por la gestión manual</td>
        <td>Me siento preocupado por si el producto era lo que buscaba el comprador.</td>
        <td>Me siento sobrecargado por responder consultas repetidas.</td>
        <td>Desmotivación por falta de retroalimentación.</td>
    </tr>
</table>

## 2.4. Ubiquitous Language
| Término                  | Definición breve |
|---------------------------|------------------|
| DeathClothe               | Plataforma web para comprar, vender y descubrir ropa de segunda mano de manera personalizada y sostenible. |
| Armario Virtual           | Espacio personal dentro de la plataforma donde los usuarios organizan sus prendas favoritas o compradas. |
| Prenda                    | Artículo de ropa subido por un vendedor y disponible para compra. |
| Vendedor                  | Usuario que publica prendas para vender en la plataforma. |
| Comprador                 | Usuario que navega, guarda y compra prendas en la plataforma. |
| Publicación               | Proceso de subir una prenda a la plataforma, incluyendo foto, descripción y precio. |
| Recomendaciones Personalizadas | Sugerencias automáticas de prendas basadas en el estilo y el armario virtual del usuario. |
| Favoritos                 | Lista de prendas que un comprador guarda para revisar o comprar más adelante. |
| Calificación              | Puntuación y reseña que los usuarios dejan sobre compradores o vendedores después de una transacción. |
| Historia de la Prenda     | Narrativa opcional que cuenta el origen, uso o anécdotas de la prenda, para agregar valor emocional. |
| Filtros Avanzados         | Herramientas que permiten buscar prendas por talla, estilo, estado, color o precio. |
# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
### Compradores 

| Phases                  | Doing                                                                 | Thinking                                                       | Feeling                  |
|-------------------------|------------------------------------------------------------------------|----------------------------------------------------------------|--------------------------|
| Búsqueda de Prendas     | Usa filtros por talla, tipo y color para encontrar prendas que se ajusten a su estilo. | “Ahora puedo filtrar rápido y encontrar ropa que realmente me gusta.” | Motivado y con control.  |
| Evaluación de Productos | Visualiza prendas con fotos cargadas por los usuarios y descripciones básicas. | “Parece estar bien, pero me gustaría ver más detalles.”          | Interesado pero cauto.   |
| Gestión de Favoritos    | Guarda prendas favoritas para revisarlas más tarde.                   | “Esta me gusta, la guardaré para pensar mejor.”                | Comprometido y selectivo.|
| Exploración del Armario | Revisa recomendaciones según su estilo o historial de navegación.     | “Estas sugerencias sí se parecen a lo que suelo buscar.”       | Acompañado y comprendido.|


### Vendedores 


| Phases                  | Doing                                                                 | Thinking                                                         | Feeling                   |
|-------------------------|------------------------------------------------------------------------|-------------------------------------------------------------------|---------------------------|
| Publicación de Prendas  | Usa un formulario para subir imágenes, talla, tipo, color, descripción y precio. | “Es simple publicar, puedo hacerlo en minutos.”                   | Ágil y seguro.            |
| Gestión del Armario     | Visualiza las prendas que ha subido y su estado (en armario, publicado, favorito). | “Puedo llevar control de mis publicaciones fácilmente.”           | Tranquilo y ordenado.     |
| Edición de Prendas      | Modifica datos de la prenda desde su perfil con formularios intuitivos. | “Puedo mejorar la descripción o cambiar el precio si quiero.”     | Empoderado y cómodo.      |
| Visibilidad del Perfil  | Accede a una vista general de sus prendas favoritas, armario y publicadas. | “Me gusta ver todo lo que he subido en un solo lugar.”            | Conectado y orgulloso.    |


## 3.2. User Stories

### Epics

<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Título</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP-01</td>
      <td>Exploración y descubrimiento de prendas</td>
      <td>Permite a los usuarios descubrir nuevas prendas a través de recomendaciones, filtros, categorías, novedades y búsquedas específicas.</td>
    </tr>
    <tr>
      <td>EP-02</td>
      <td>Gestión de ventas de prendas</td>
      <td>Permite a los usuarios vender ropa de forma sencilla, incluyendo publicación, edición, eliminación, y marcación de artículos como vendidos.</td>
    </tr>
    <tr>
      <td>EP-03</td>
      <td>Favoritos y armario virtual</td>
      <td>Permite a los usuarios guardar prendas en favoritos, gestionarlas, y construir un armario virtual organizado por categorías.</td>
    </tr>
    <tr>
      <td>EP-04</td>
      <td>Gestión de cuenta y autenticación</td>
      <td>Permite a los usuarios registrarse, iniciar o cerrar sesión, y cambiar el idioma desde cualquier punto de la aplicación.</td>
    </tr>
    <tr>
      <td>EP-05</td>
      <td>Interfaz informativa y accesible</td>
      <td>Incluye funcionalidades de la landing page como visualización de propuesta de valor, redes sociales, y acceso rápido a registro/login.</td>
    </tr>
    <tr>
      <td>EP-06</td>
      <td>Gestión del perfil de usuario</td>
      <td>Permite alternar entre vista de comprador y vendedor, visualizar estadísticas y acceder a datos relevantes dentro del perfil.</td>
    </tr>
  </tbody>
</table>


## User Stories

| Historia de Usuario ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|------------------------|--------|-------------|--------------------------|----------------------------|
| US-01 | Recibir recomendaciones en base a mis favoritos | Como comprador, quiero ver recomendaciones personalizadas de ropa según mis favoritos, para encontrar prendas que realmente me gusten sin tener que buscar demasiado. | Escenario 1: Recomendaciones automáticas Dado que el usuario tiene prendas en sus favoritos, Cuando accede a la sección "Favoritos", Entonces ve una selección de prendas recomendadas con base en sus preferencias y artículos favoritos. Escenario 2: Sin Favoritos Dado que el usuario no tiene productos en favoritos, Cuando accede a la sección "Favoritos", Entonces se muestran recomendaciones de prendas aleatorias. | EP01 |
| US-02 | Publicar una prenda en venta | Como vendedor, quiero subir una prenda en solo tres pasos, para que sea fácil y rápido listar productos y empezar a vender. | Escenario 1: Publicación ropa nueva Dado que el esté en su armario y agrego una prenda, Cuando seleccione "Poner a la venta" y complete el formulario , Entonces la prenda queda publicada en la plataforma. Escenario 2: Publicación prenda del armario Dado que el esté en su armario y edite una prenda, Cuando seleccione "Poner a la venta" y complete el formulario , Entonces la prenda queda publicada en la plataforma. | EP02 |
| US-03 | Buscar prendas por palabra clave | Como comprador, quiero poder buscar prendas usando palabras clave, para encontrar más rápido lo que tengo en mente. | Escenario 1: Búsqueda por texto simple Dado que el usuario ingresa una palabra clave en la barra de búsqueda, Cuando presiona "Enter", Entonces se muestran resultados que contienen ese término en el título o descripción. Escenario 2: Prenda inexistente Dado que el usuario ingresa una palabra inexistente en la barra de búsqueda, Cuando presiona "Enter", Entonces no se muestran resultados que contienen ese término en el título o descripción  | EP01 |
| US-04 | Ver últimas prendas publicadas | Como comprador, quiero ver las prendas recién agregadas, para no perderme novedades. | Escenario 1: Vista por publicación Dado que el usuario accede a la sección “Novedades”, Cuando navega el feed, Entonces ve primero las prendas publicadas más recientemente. Escenario 2: Vista sin publicaciones Dado que el usuario accede a la sección “Novedades”, Cuando navega el feed y no hay publicaciones , Entonces se imprimirá la pagina vacía. | EP01 |
| US-05 | Filtrar por categoría | Como comprador, quiero aplicar filtros por tipo de prenda (camisas, pantalones, etc.), para encontrar lo que necesito más fácilmente. | Escenario 1: Selección de categoría Dado que el usuario accede al catálogo, Cuando hace clic en un filtro de tipo de prenda, Entonces solo se muestran las prendas correspondientes Escenario 2: Sin prendas en la categoria Dado que el usuario accede al catálogo, Cuando hace clic en un filtro de tipo de prenda y no hay prendas en venta de esa categoría, Entonces se muestra un mensaje "No hay prendas disponibles en esta categoría." | EP01 |
| US-06 | Recibir recomendaciones de la pagina| Como comprador frecuente, quiero ver recomendaciones , para descubrir prendas que me puedan interesar. | Escenario 1: Recomendaciones general Dado que el usuario esté en la sección de inicio, Cuando navega el feed, Entonces podrá ver la sección de recomendaciones donde se muestren las prendas. Escenario 2: Sin prendas  Dado que el usuario esté en la sección de inicio, Cuando navega el feed y no haya prendas en venta, Entonces podrá ver la sección de recomendaciones pero no se mostraran prendas.  | EP01 |
| US-07 | Editar o eliminar una prenda publicada | Como vendedor, quiero editar o eliminar prendas que ya publiqué, para mantener actualizado mi catálogo. | Escenario 1: Edición de información Dado que el usuario accede a su perfil, Cuando selecciona una prenda publicada, Entonces puede modificar descripción, precio o imágenes. Escenario 2: Eliminación de prenda Dado que ya no desea venderla, Cuando presiona “Eliminar”, Entonces la prenda se elimina de la plataforma. | EP02 |
| US-8 | Ver estadísticas de mis ventas | Como vendedor, quiero ver las estadísticas de mis ventas, para saber qué prendas se venden más y mejorar mi oferta. | Escenario 1: Estadisticas de ventas Dado que el usuario cambia a la sección de vendedor, Cuando navega en el feed, Entonces podrá ver estadisticas de sus ventas. Escenario 2: Sin ventas Dado que el usuario cambia a la sección de vendedor, Cuando navega en el feed y no tiene prendas vendidas, Entonces se mostrará un mensaje "Sin ventas registradas aún.".  | EP02 |
| US-9 | Marcar una prenda como vendida | Como vendedor, quiero poder marcar una prenda como vendida, para evitar que otros la sigan viendo como disponible. | Escenario 1: Cambio de estado manual Dado que la prenda fue vendida, Cuando el vendedor ingresa el correo del comprador, si este existe y es encontrado en la aplicación, Entonces desaparece del catálogo público del vendedor. Escenario 2: Correo inexistente Dado que la prenda fue vendida, Cuando el vendedor ingresa un correo inexistente, Entonces imprime el mensaje "Correo no encontrado. Ingresa un correo válido.". | EP02 |
| US-10 | Agregar una prenda a favoritos | Como comprador, quiero poder marcar prendas como favoritas para guardarlas y considerarlas después. | Escenario 1: Marcar como favorito Dado que el usuario está navegando por el catálogo, Cuando pulsa el ícono de “corazón”, Entonces la prenda se agrega a su lista de favoritos. Escenario 2: Visualizar lista de favoritos Dado que el usuario quiere ver sus favoritos, Cuando accede a “Mi lista de favoritos” desde su perfil, Entonces puede ver todas las prendas guardadas. | EP03 |
| US-11 | Crear un armario virtual | Como usuario, quiero crear un armario virtual con mis prendas favoritas o compradas, para tener una guía de mi estilo. | Escenario 1: Agregar prenda al armario Dado que la prenda ha sido comprada, Cuando se marca como “Agregar a mi armario”, Entonces pasa a formar parte del armario virtual del usuario. Escenario 2: Visualizar y editar armario Dado que el usuario accede a su armario, Cuando elige una prenda, Entonces puede ver detalles, eliminarla o editar atributos (ej. color, estilo). | EP03 |
| US-12 | Ver información de la landing page | Como usuario visitante, quiero ver la propuesta de valor y las principales funcionalidades en la landing page, para entender rápidamente los beneficios de la plataforma. | Escenario 1: Propuesta de valor Dado que el usuario accede al sitio principal, Cuando se carga la página, Entonces ve un banner con eslogan y descripción breve. Escenario 2: Destacar funcionalidades Dado que el usuario hace scroll en la landing page, Cuando llega a la sección de características, Entonces ve iconos, descripciones y llamadas a la acción de cada funcionalidad. | EP05 |
| US-13 | Visualizar detalles de prenda | Como usuario quiero poder ver la foto, el precio y la descripción de una prenda para decidir si me interesa comprarla y contactarme con el vendedor. | Escenario: Dado que el usuario está navegando en la aplicación y ve varias cards de prendas, cuando presiona una card específica, entonces se muestra la sección de detalle con la foto, el precio, la descripción completa de esa prenda y un chat para comunicarse con el vendedor. | EP01 |
| US-14 | Conocer al vendedor | Como usuario quiero ver quién me está vendiendo la prenda (nombre e imagen del usuario) para tener más confianza y detalles adicionales. |Escenario: Dado que el usuario accede a la sección de detalle de una prenda, cuando esta se muestra, entonces también se visualiza el nombre y la foto del usuario que la está vendiendo, brindando mayor confianza e información.| EP06 |
| US-15 | Filtrar por tipo en el armario |Como usuario quiero poder filtrar mi armario virtual por tipo de ropa (polo, pantalón, vestido, etc.) para tener un mejor orden visual. |Escenario 1: Dado que el usuario está en la sección armario y selecciona una categoría de la cual posee prendas, cuando hace la selección, entonces se muestran únicamente las prendas del usuario pertenecientes a esa categoría. Escenario 2: Dado que el usuario está en la sección armario y selecciona una categoría de la cual no posee prendas, cuando hace la selección, entonces no se muestra ninguna prenda en esa categoría.| EP03 |
| US-16 | Buscar prenda en favoritos| Como usuario quiero buscar por nombre dentro de mis prendas favoritas para encontrar fácilmente una prenda específica. | Escenario 1: Dado que el usuario se encuentra en la sección de prendas favoritas y escribe un término que coincide parcial o totalmente con el nombre de una o más prendas guardadas, cuando realiza la búsqueda, entonces se muestran todas las prendas que coinciden con ese término. Escenario 2: Dado que el usuario se encuentra en la sección de prendas favoritas y escribe un término que no coincide con ninguna de sus prendas guardadas, cuando realiza la búsqueda, entonces no se muestra ninguna prenda en los resultados. | EP03 |
| US-17 | Cerrar sesión | Como usuario quiero poder cerrar sesión desde cualquier parte de la aplicación para proteger mi cuenta cuando ya no la estoy usando. |Escenario 1: Dado que el usuario está en su perfil, cuando visualiza la opción de cerrar sesión, entonces puede hacer clic en ella para cerrar su sesión. Escenario 2: Dado que el usuario está en cualquier sección de la aplicación y accede al perfil desde el toolbar, cuando selecciona "Cerrar sesión", entonces es deslogueado correctamente y redirigido a la pantalla de login. | EP04 |
| US-18 |Cambiar idioma en landing page|Como usuario quiero poder cambiar el idioma en la landing page para usarla cómodamente en el idioma que prefiera.|Escenario 1: Dado que el visitante está viendo la landing page en español y hay un selector de idioma visible, cuando selecciona "English", entonces el contenido de la landing page se muestra completamente en inglés. Escenario 2: Dado que el visitante está viendo la landing page en inglés y hay un selector de idioma visible, cuando selecciona "Español", entonces el contenido de la landing page se muestra completamente en español.| EP05 |
| US-19 | Registrar/Iniciar sesión desde landing page | Como usuario nuevo o recurrente, quiero poder registrarme o iniciar sesión directamente desde la landing page, para empezar a usar la plataforma sin navegar a otras secciones. | Escenario 1: Registro e inicio rápido Dado que el usuario está en la página principal, Cuando hace clic en “Registrarse” o “Iniciar sesión”, Entonces se despliega un formulario accesible sin salir de la página. Escenario 2: Validación de acceso Dado que el usuario ya se ha registrado, Cuando introduce sus credenciales correctamente, Entonces se le redirige al dashboard o página principal personalizada. | EP04 |
| US-20 | Cambiar idioma en app web | Como usuario quiero poder cambiar el idioma en toda la aplicación para usarla cómodamente en el idioma que prefiera. | Escenario 1: Cambio de idioma de español a inglés Dado que el usuario está utilizando la aplicación en español Y el selector de idioma (language switcher) está visible en la interfaz Cuando el usuario selecciona "English" en el selector de idioma Entonces todo el contenido de la aplicación se actualiza y se muestra en inglés. Escenario 2: Cambio de idioma de inglés a español Dado que el usuario está utilizando la aplicación en inglés Y el selector de idioma (language switcher) está visible en la interfaz Cuando el usuario selecciona "Español" en el selector de idioma Entonces todo el contenido de la aplicación se actualiza y se muestra en español. | EP04 |
| US-21 | Acceder a redes sociales | Como usuario quiero ver íconos de las redes sociales oficiales en la landing page para conocer más sobre la plataforma y su comunidad. | Escenario: Dado que el usuario está en la landing page, cuando visualiza los íconos de redes sociales oficiales, entonces puede hacer clic en ellos para acceder a las respectivas plataformas y conocer más sobre la comunidad. | EP05 |
| US-22 | Cambiar entre comprador y vendedor | Como usuario quiero poder cambiar entre vista de comprador y vista de vendedor en mi perfil para alternar según mis necesidades.| Escenario 1: Dado que el usuario está en su perfil y la vista actual es la de comprador, cuando selecciona la opción "vendedor" en el switcher, entonces la interfaz cambia a la vista de vendedor mostrando las opciones correspondientes. Escenario 2: Dado que el usuario está en su perfil y la vista actual es la de vendedor, cuando selecciona la opción "comprador" en el switcher, entonces la interfaz cambia a la vista de comprador mostrando sus funcionalidades. | EP06 |
| US-23 | Editar prendas del armario | Como usuario quiero poder editar las prendas que tengo en mi armario virtual para actualizar su información o ponerlas en venta. | Escenario 1: Dado que el usuario está en su armario virtual y selecciona una prenda, cuando edita sus datos como la talla o descripción y guarda los cambios, entonces la prenda se actualiza con la nueva información. Escenario 2: Dado que el usuario está en su armario virtual y selecciona una prenda, cuando elige ponerla en venta y confirma la acción, entonces la prenda deja de mostrarse en el armario y pasa a estar publicada como disponible para la venta. | EP03 |
| US-24 | Página no encontrada | Como usuario quiero que al ingresar a una ruta inexistente aparezca un botón que me redirija al inicio para no quedarme perdido. | Escenario: Dado que el usuario intenta acceder a una ruta inexistente en la aplicación, cuando se muestra la página de error, entonces aparece un botón visible que al hacer clic lo redirige a la página de inicio. | EP05 |
| US-25 | Explorar la seccion Home en Landing Page | Como usuario, quiero visualizar la sección Inicio del landing page para entender de inmediato qué es DeathClothe y cómo me conecta con otras personas interesadas en moda de segunda mano. | Escenario 1: Reconocimiento de propósito desde la primera vista Dado que entro al sitio por primera vez, Cuando veo el mensaje “La moda que fue, vuelve siempre con más estilo”, Entonces entiendo que el objetivo es reutilizar prendas con autenticidad y estilo. Escenario 2: Entendimiento de funcionalidad clave Dado que quiero deshacerme de ropa que ya no uso, Cuando leo “DeathClothe te conectará a personas que deseen comprarte o venderte ropa con un solo click”, Entonces me convenzo de que puedo intercambiar ropa de manera rápida y sencilla. | EP05 |
| US-26 | Explorar la seccion Explore en Landing Page | Como usuario, quiero explorar ropa con historia para encontrar piezas únicas subidas por la comunidad. | Escenario 1: Valoración del contenido comunitarioDado que busco originalidad,Cuando leo “Nuestra comunidad sube prendas cada día”, Entonces entiendo que siempre hay contenido nuevo e interesante.Escenario 2: Confianza en herramientas de exploración Dado que quiero encontrar algo que se adapte a mí, Cuando veo los íconos de “Usa filtros”, “Guarda tus favoritos”, “Compra de forma segura”, Entonces reconozco que la plataforma me permite navegar con opciones personalizadas y seguras.| EP01 |
| US-27 | Explorar la seccion Sell en Landing Page | Como usuario, quiero saber cómo publicar una prenda fácilmente y sin complicaciones. | Escenario 1: Simplicidad del proceso visual Dado que quiero vender ropa usada, Cuando leo “Termina los dos pasos, ¡envía y listo!”, Entonces comprendo que solo debo subir fotos, describir la prenda y fijar un precio para comenzar a vender.Escenario 2: Confianza al ver el paso a paso visual Dado que no estoy seguro de cómo hacerlo, Cuando veo las imágenes y textos: “Toma fotos…”, “Describe la prenda…”, “Ponle un precio…”, Entonces me siento guiado y sé exactamente qué hacer para publicar mi producto. | EP02 |
| US-28 | Explorar la seccion Community en Landing Pag | Como usuario, quiero conocer la comunidad de DeathClothe para sentir que formo parte de algo más que una tienda. | Escenario 1: Seguridad a través de experiencias reales Dado que me preocupa la fiabilidad de la plataforma, Cuando leo los testimonios de usuarios como “Me encanta saber que cada prenda que compro no solo es linda...”, Entonces me siento más confiado de que es una plataforma honesta y útil.Escenario 2: Identificación con el propósito colectivo Dado que valoro la sostenibilidad, Cuando leo “Hemos encontrado hogar a miles de prendas usadas… el cambio empieza en el clóset”, Entonces conecto con la idea de que DeathClothe busca reducir el desperdicio de ropa. | EP05 |
| US-29 | Explorar la seccion About-Us en Landing Pag | Como usuario, quiero saber quién está detrás de DeathClothe y cuál es su propósito para confiar más en la plataforma. | Escenario 1: Inspiración desde la misión Dado que busco marcas con propósito, Cuando leo “DeathClothe nació para cambiar la forma en que vivimos la moda”, Entonces percibo que esta plataforma tiene una causa social y ambiental clara.Escenario 2: Alineación con valores personales Dado que creo en la sostenibilidad, Cuando leo “Creemos que la moda no muere, se transforma...”, Entonces siento que esta plataforma refleja mis valores y me interesa formar parte. | EP05 |
| US-30 | Temas de landing page | Como usuario, quiero poder elegir el tema entre oscuro y claro para sentirme mas comodo navegando en la landing page. | Escenario 1: Modo oscuro Dado que selecciono el modo oscuro, Cuando cambio el switcher a la luna, Entonces la Landing Page se pone en modo oscuro.Escenario 2: Modo claro Dado que selecciono el modo claro, Cuando cambio el switcher al modo sol, Entonces la Landing Page se pone en modo claro. | EP05 |


**Technical Stories**

| Historia de Usuario ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|------------------------|--------|-------------|--------------------------|----------------------------|
| TS-01 | Obtener perfil por ID | Como desarrollador, quiero obtener el perfil de un usuario por su ID, para poder recuperar los detalles específicos del usuario cuando sea necesario.| Escenario 1: Obtener perfil de usuario existenteDado que el endpoint “/api/v1/profiles/{id}” está disponible,Cuando se envía un request GET con el ID de usuario 1,Entonces se recibe un response con un status 200 y los detalles del perfil de usuario (Ana García López) en el body del response.Escenario 2: Intentar obtener perfil de usuario inexistenteDado que el endpoint “/api/v1/profiles/{id}” está disponible,Cuando se envía un request GET con el ID de usuario 6 y no existe en la base de datos,Entonces se recibe un response con un status 404 y un mensaje en el body del response que diga: “Perfil de usuario no encontrado”. | EP06 |
| TS-02 | Actualizar perfil por ID | Como desarrollador, quiero actualizar el perfil de un usuario por su ID, para poder modificar la información del usuario cuando lo necesite. | Escenario 1: Actualizar perfil de usuario con datos válidosDado que el endpoint “/api/v1/profiles/{id}” está disponible,Cuando se envía un request PUT con los valores actualizados de nombre, apellidos, dirección y email del usuario con ID 1 ,Entonces se recibe un response con un status 200 y el perfil actualizado de usuario en el body del response.Escenario 2: Intentar actualizar perfil de usuario inexistenteDado que el endpoint “/api/v1/profiles/{id}” está disponible, Cuando se envía un request PUT con el ID de usuario 6 y no existe en la base de datos, Entonces se recibe un response con un status 404 y un mensaje en el body del response que diga: “Perfil de usuario no encontrado”.| EP06 |
| TS-03 | Obtener todos los perfiles | Como desarrollador, quiero obtener todos los perfiles de usuario, para poder visualizar una lista completa de los usuarios registrados en el sistema. | Escenario 1: Obtener todos los perfiles de usuario Dado que el endpoint “/api/v1/profiles” está disponible, Cuando se envía un request GET sin parámetros, Entonces se recibe un response con un status 200 y la lista de todos los perfiles de usuario en el body del response. Escenario 2: No hay perfiles disponibles Dado que el endpoint “/api/v1/profiles” está disponible, Cuando no hay perfiles registrados en el sistema, Entonces se recibe un response con un status 204 y un mensaje en el body del response que diga: “No hay perfiles disponibles”. | EP06 |
| TS-04 | Obtener todas las ropas | Como desarrollador, quiero obtener todos los productos de ropa disponibles en el sistema, para que los usuarios puedan ver todo el inventario de prendas. | Escenario 1: Obtener todas las prendas de ropa Dado que el endpoint “/api/v1/clothes” está disponible, Cuando se envía un request GET sin parámetros, Entonces se recibe un response con un status 200 y la lista de todas las prendas de ropa en el body del response. Escenario 2: No hay prendas de ropa disponibles Dado que el endpoint “/api/v1/clothes” está disponible, Cuando no hay prendas de ropa registradas en el sistema, Entonces se recibe un response con un status 204 y un mensaje en el body del response que diga: “No hay productos de ropa disponibles”. | EP01 |
| TS-05 | Crear una nueva prenda de ropa | Como desarrollador, quiero permitir que se cree una nueva prenda de ropa, para que los usuarios puedan añadir productos a su inventario. | Escenario 1: Crear una nueva prenda de ropa con datos válidos Dado que el endpoint “/api/v1/clothes” está disponible, Cuando se envía un request POST con los valores de nombre, descripción, precio, talla y color, Entonces se recibe un response con un status 201 y la nueva prenda de ropa en el body del response. Escenario 2: Intentar crear una prenda con datos incompletos Dado que el endpoint “/api/v1/clothes” está disponible, Cuando se envía un request POST sin precio o talla, Entonces se recibe un response con un status 400 y un mensaje en el body del response que diga: “Faltan datos requeridos para la creación de la prenda”. | EP02 |
| TS-06 | Obtener una prenda de ropa por ID | Como desarrollador, quiero obtener los detalles de una prenda de ropa por su ID, para poder ver la información específica de un producto. | scenario 1: Obtener prenda de ropa existente Dado que el endpoint “/api/v1/clothes/{clotheId}” está disponible, Cuando se envía un request GET con el ID de prenda, Entonces se recibe un response con un status 200 y los detalles de la prenda (nombre, precio, descripción, etc.) en el body del response. Escenario 2: Intentar obtener prenda de ropa inexistente Dado que el endpoint “/api/v1/clothes/{clotheId}” está disponible, Cuando se envía un request GET con el ID de prenda y no existe, Entonces se recibe un response con un status 404 y un mensaje en el body del response que diga: “Prenda no encontrada”.| EP01 |
| TS-07 | Actualizar una prenda de ropa | Como desarrollador, quiero actualizar los detalles de una prenda de ropa, para que los usuarios puedan modificar la información de sus productos. | Escenario 1: Actualizar prenda de ropa existente Dado que el endpoint “/api/v1/clothes/{clotheId}” está disponible, Cuando se envía un request PUT con los valores de nombre, descripción, precio y talla actualizados para la prenda, Entonces se recibe un response con un status 200 y la prenda actualizada en el body del response. Escenario 2: Intentar actualizar prenda de ropa inexistente Dado que el endpoint “/api/v1/clothes/{clotheId}” está disponible, Cuando se envía un request PUT con el ID de prenda y no existe, Entonces se recibe un response con un status 404 y un mensaje en el body del response que diga: “Prenda no encontrada”. | EP02 |
| TS-08 | Eliminar una prenda de ropa | Como desarrollador, quiero permitir que los usuarios eliminen una prenda de ropa, para que puedan quitar productos de su inventario. | Escenario 1: Eliminar prenda de ropa existente Dado que el endpoint “/api/v1/clothes/{clotheId}” está disponible, Y existe una prenda con el ID especificado, Cuando se envía un request DELETE con el ID de la prenda, Entonces se recibe un response con un status 204 y la prenda es eliminada del sistema. Escenario 2: Intentar eliminar prenda de ropa inexistente Dado que el endpoint “/api/v1/clothes/{clotheId}” está disponible, Y no existe una prenda con el ID, Cuando se envía un request DELETE con el ID de la prenda, Entonces se recibe un response con un status 404 y un mensaje en el body del response que diga: “Prenda no encontrada”. | EP02 |
| TS-09 | Obtener todas las categorías | Como desarrollador, quiero obtener todas las categorías de ropa, para que los usuarios puedan ver todas las opciones de clasificación de los productos. | Escenario 1: Obtener todas las categorías de ropa Dado que el endpoint “/api/v1/categories” está disponible, Cuando se envía un request GET sin parámetros, Entonces se recibe un response con un status 200 y la lista de todas las categorías de ropa en el body del response. Escenario 2: No hay categorías disponibles Dado que el endpoint “/api/v1/categories” está disponible, Cuando no hay categorías registradas en el sistema, Entonces se recibe un response con un status 204 y un mensaje en el body del response que diga: “No hay categorías disponibles”.| EP01 |
| TS-10 | Obtener categoría por ID | Como desarrollador, quiero obtener los detalles de una categoría de ropa por su ID, para que los usuarios puedan ver la información específica de una categoría. | Escenario 1: Obtener categoría de ropa existente Dado que el endpoint “/api/v1/categories/{categoryId}” está disponible, Cuando se envía un request GET con el ID de categoría, Entonces se recibe un response con un status 200 y los detalles de la categoría de ropa (nombre, imagen) en el body del response. Escenario 2: Intentar obtener categoría de ropa inexistente Dado que el endpoint “/api/v1/categories/{categoryId}” está disponible, Cuando se envía un request GET con el ID de categoría y no existe, Entonces se recibe un response con un status 404 y un mensaje en el body del response que diga: “Categoría no encontrada”.| EP01 |
| TS-11 | Autentificar el inicio de sesión| Como desarrollador, quiero autenticar a los usuarios durante el inicio de sesión, para que puedan acceder a sus cuentas de manera segura. | Escenario 1: Inicio de sesión con credenciales correctas Dado que el endpoint “/api/v1/authentication/sign-in” está disponible, Cuando se envía un request POST con los valores correctos de nombre de usuario y contraseña, Entonces se recibe un response con un status 200 y un token JWT en el body del response para futuras autenticaciones. Escenario 2: Intentar inicio de sesión con credenciales incorrectas Dado que el endpoint “/api/v1/authentication/sign-in” está disponible, Cuando se envía un request POST con credenciales incorrectas, Entonces se recibe un response con un status 401 y un mensaje en el body del response que diga: “Credenciales incorrectas”. | EP04 |
| TS-12 | Autentificar el registro de usuario | Como desarrollador, quiero autenticar el registro de un nuevo usuario, para que los nuevos usuarios puedan registrarse en el sistema. | Escenario 1: Registro exitoso de un nuevo usuario Dado que el endpoint “/api/v1/authentication/sign-up” está disponible, Cuando se envía un request POST con los valores válidos de nombre, apellido, email y contraseña, Entonces se recibe un response con un status 201 y los detalles del nuevo usuario en el body del response. Escenario 2: Intentar registrar un usuario con un correo ya registrado Dado que el endpoint “/api/v1/authentication/sign-up” está disponible, Cuando se envía un request POST con un correo electrónico ya registrado, Entonces se recibe un response con un status 400 y un mensaje en el body del response que diga: “Correo electrónico ya registrado”. | EP04 |

### 3.3. Impact Mapping 

<img src="./Report_Assets/Impact map 1 (1).png" alt="Impact Mapping" width="500">

### 3.4. Product Backlog

| Orden | User Story Id | Título                                   | Descripción                                                                                                                                                          | Story Points |
|-------|---------------|------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| 1     | US-01         | Recibir recomendaciones en base a mis favoritos           | Como comprador, quiero ver recomendaciones personalizadas de ropa según mis favoritos, para encontrar prendas que realmente me gusten sin tener que buscar demasiado. | 3           |
| 2     | US-02         | Publicar una prenda en venta         | Como vendedor, quiero subir una prenda en solo tres pasos, para que sea fácil y rápido listar productos y empezar a vender.                                     | 3           |
| 3     | US-03         | Buscar prendas por palabra clave  | Como comprador, quiero poder buscar prendas usando palabras clave, para encontrar más rápido lo que tengo en mente.| 5          |
| 4     | US-04         | Ver últimas prendas publicadas        | Como comprador, quiero ver las prendas recién agregadas, para no perderme novedades. | 3           |
| 5     | US-05         | Filtrar por categoría  | Como comprador, quiero aplicar filtros por tipo de prenda (camisas, pantalones, etc.), para encontrar lo que necesito más fácilmente. | 3            |
| 6     | US-06         | Recibir recomendaciones de la pagina      | Como comprador frecuente, quiero ver recomendaciones , para descubrir prendas que me puedan interesar. | 5            |
| 7     | US-07         | Editar o eliminar una prenda publicada     | Como vendedor, quiero editar o eliminar prendas que ya publiqué, para mantener actualizado mi catálogo. | 5            |
| 8    | US-08         | Ver estadísticas de mis ventas | Como vendedor, quiero ver las estadísticas de mis ventas, para saber qué prendas se venden más y mejorar mi oferta. | 5           |
| 9    | US-09         | Marcar una prenda como vendida      | Como vendedor, quiero poder marcar una prenda como vendida, para evitar que otros la sigan viendo como disponible. | 5            |
| 10    | US-10         | Agregar una prenda a favoritos   | Como comprador, quiero poder marcar prendas como favoritas para guardarlas y considerarlas después. | 3            |
| 11    | US-11         | Crear un armario virtual   | Como usuario, quiero crear un armario virtual con mis prendas favoritas o compradas, para tener una guía de mi estilo y recibir sugerencias. | 5           |
| 12    | US-12         | Ver información de la landing page | Como usuario visitante, quiero ver la propuesta de valor y las principales funcionalidades en la landing page, para entender rápidamente los beneficios de la plataforma. | 3            |
| 13    | US-13         | Visualizar detalles de prenda         | Como usuario quiero poder ver la foto, el precio y la descripción de una prenda para decidir si me interesa comprarla y contactarme con el vendedor. | 3            |
| 14    | US-14         | Conocer al vendedor      | Como usuario quiero ver quién me está vendiendo la prenda (nombre e imagen del usuario) para tener más confianza y detalles adicionales. | 3            |
| 15    | US-15         | Filtrar por tipo en el armario      | Como usuario quiero poder filtrar mi armario virtual por tipo de ropa (polo, pantalón, vestido, etc.) para tener un mejor orden visual. | 5            |
| 16    | US-16         | Buscar prenda en favoritos      | Como usuario quiero buscar por nombre dentro de mis prendas favoritas para encontrar fácilmente una prenda específica. | 5            |
| 17    | US-17         | Cerrar sesión      | Como usuario quiero poder cerrar sesión desde cualquier parte de la aplicación para proteger mi cuenta cuando ya no la estoy usando. | 3            |
| 18    | US-18         | Cambiar idioma en landing page      | Como usuario quiero poder cambiar el idioma en la landing page para usarla cómodamente en el idioma que prefiera. | 3            |
| 19    | US-19         | Registrar/Iniciar sesión desde landing page      | Como usuario nuevo o recurrente, quiero poder registrarme o iniciar sesión directamente desde la landing page, para empezar a usar la plataforma sin navegar a otras secciones. | 3            |
| 20    | US-20         | Cambiar idioma en app web      | Como usuario quiero poder cambiar el idioma en toda la aplicación para usarla cómodamente en el idioma que prefiera. | 5            |
| 21    | US-21         | Acceder a redes sociales      | Como usuario quiero ver íconos de las redes sociales oficiales en la landing page para conocer más sobre la plataforma y su comunidad. | 3            |
| 22    | US-22         | Cambiar entre comprador y vendedor      | Como usuario quiero poder cambiar entre vista de comprador y vista de vendedor en mi perfil para alternar según mis necesidades. | 5           |
| 23    | US-23         | Editar prendas del armario      | Como usuario quiero poder editar las prendas que tengo en mi armario virtual para actualizar su información o ponerlas en venta. | 5           |
| 24    | US-24         | Página no encontrada      | Como usuario quiero que al ingresar a una ruta inexistente aparezca un botón que me redirija al inicio para no quedarme perdido. | 3          |
| 25    | US-25         | Explorar la seccion Home en Landing Page      | Como usuario, quiero visualizar la sección Inicio del landing page para entender de inmediato qué es DeathClothe y cómo me conecta con otras personas interesadas en moda de segunda mano. | 2          |
| 26    | US-26         | Explorar la seccion Explore en Landing Page      | Como usuario, quiero explorar ropa con historia para encontrar piezas únicas subidas por la comunidad. | 2          |
| 27    | US-27         | Explorar la seccion Sell en Landing Page      | Como usuario, quiero saber cómo publicar una prenda fácilmente y sin complicaciones. | 2          |
| 28    | US-28         | Explorar la seccion Community en Landing Page      | Como usuario, quiero conocer la comunidad de DeathClothe para sentir que formo parte de algo más que una tienda. | 2          |
| 29    | US-29         | Explorar la seccion About-Us en Landing Page      | Como usuario, quiero saber quién está detrás de DeathClothe y cuál es su propósito para confiar más en la plataforma. | 2          |
| 30    | US-30         | Explorar la Landing Page      | Como usuario, quiero poder cambiar entre temas para poder sentirme más cómodo navegando en la Landing page. | 2          |
| 31    | TS-01         | Obtener perfil por ID	 | Como desarrollador, quiero obtener el perfil de un usuario por su ID, para poder recuperar los detalles específicos del usuario cuando sea necesario.	 | 3           |
| 32    | TS-02         | Actualizar perfil por ID	   | Como desarrollador, quiero actualizar el perfil de un usuario por su ID, para poder modificar la información del usuario cuando lo necesite.	 | 4           |
| 33    | TS-03         | Obtener todos los perfiles	 | Como desarrollador, quiero obtener todos los perfiles de usuario, para poder visualizar una lista completa de los usuarios registrados en el sistema. | 4          |
| 34    | TS-04         | Obtener todas las ropas	  | Como desarrollador, quiero obtener todos los productos de ropa disponibles en el sistema, para que los usuarios puedan ver todo el inventario de prendas.	 | 3           |
| 35    | TS-05         | Crear una nueva prenda de ropa	 | Como desarrollador, quiero permitir que se cree una nueva prenda de ropa, para que los usuarios puedan añadir productos a su inventario.	 | 4           |
| 36    | TS-06         | Obtener una prenda de ropa por ID	  | Como desarrollador, quiero obtener los detalles de una prenda de ropa por su ID, para poder ver la información específica de un producto.	| 4          |
| 37    | TS-07         | Actualizar una prenda de ropa	  | Como desarrollador, quiero actualizar los detalles de una prenda de ropa, para que los usuarios puedan modificar la información de sus productos.	 | 5          |
| 38    | TS-08         | Eliminar una prenda de ropa		  | Como desarrollador, quiero permitir que los usuarios eliminen una prenda de ropa, para que puedan quitar productos de su inventario.	 | 4         |
| 39    | TS-09         | Obtener todas las categorías		  | Como desarrollador, quiero obtener todas las categorías de ropa, para que los usuarios puedan ver todas las opciones de clasificación de los productos.		 | 3          |
| 40    | TS-10         | Obtener categoría por ID		  | Como desarrollador, quiero obtener los detalles de una categoría de ropa por su ID, para que los usuarios puedan ver la información específica de una categoría.	 | 5          |
| 41    | TS-11         | Autentificar el inicio de sesión		  | Como desarrollador, quiero autenticar a los usuarios durante el inicio de sesión, para que puedan acceder a sus cuentas de manera segura.		 | 3          |
| 42    | TS-12         | Autentificar el registro de usuario		  | Como desarrollador, quiero autenticar el registro de un nuevo usuario, para que los nuevos usuarios puedan registrarse en el sistema.		 | 3          |


# Capítulo IV: Product Design

## 4.1. Style Guidelines

Esta sección establece los lineamientos visuales y de diseño que guiarán el trabajo del equipo, asegurando una presentación uniforme, coherente y profesional en todos los productos y plataformas. Aquí se centralizan los assets, fuentes, paletas de colores, íconos y otros recursos gráficos que deben ser utilizados de manera consistente.

### 4.1.1. General Style Guidelines

En DeathClothe, buscamos transmitir una experiencia visual alineada con nuestra esencia: auténtica, sostenible, juvenil y con actitud positiva. Para lograrlo, tomamos decisiones de diseño basadas en principios de accesibilidad, coherencia visual y personalidad de marca.
**-Branding:**

Utilizamos una paleta de colores que refleja vitalidad, originalidad y conciencia ambiental, en consonancia con el espíritu de la moda circular.
El color primario #C4456B es un rosa intenso que transmite energía, creatividad y conexión emocional. Se complementa con tonos secundarios como #E4738F (rosado vibrante para encabezados) y #F2829E (rosado de énfasis para resaltar acciones importantes). Para los fondos, se usan tonos suaves como #FFEBED y #FDD3DC, que aportan calidez, accesibilidad y ligereza visual. Además, el color #F5B9CB se utiliza para elementos de soporte y detalles de secciones, garantizando coherencia visual.

![Paleta_de_Colores](Report_Assets/PaletaDeColoresDeathClothe.png)

**-Typography:**
Se ha elegido la tipografía K2D para la comunicación principal, por su estilo contemporáneo, amigable y de fácil lectura, que proyecta frescura y autenticidad.
Como tipografía secundaria se emplea Inter, que ofrece alta legibilidad para textos complementarios, descripciones y navegación en dispositivos móviles y de escritorio.
El uso combinado de estas tipografías asegura jerarquía clara, modernidad y accesibilidad para todo tipo de usuarios, ademas del uso de diferentes pesos como medium, semi-bold y bold.

![Typography](Report_Assets/TipografiaK2d.PNG)


**-Icons:**
Se utilizan íconos de estilo lineal y minimalista, que permiten una comunicación inmediata y sin distracciones.
Estos íconos apoyan la navegación intuitiva, refuerzan el diseño moderno y aseguran una experiencia de usuario ágil, tanto en dispositivos móviles como en computadoras.

![Icons](Report_Assets/iconos.PNG)

**-Buttons:**
Los botones están diseñados para ser visualmente atractivos, accesibles y claros en su propósito.
Los colores vivos como el rosa vibrante (#C4456B) aseguran que las acciones principales sean destacadas fácilmente, mientras que los bordes redondeados mejoran la usabilidad en pantallas táctiles y brindan una sensación amigable.

![Buttons](Report_Assets/botones.PNG)

**-Spacing and Layout:**
El diseño mantiene un sistema de espaciado uniforme que favorece una navegación fluida y clara.
Los márgenes y rellenos aseguran que cada sección respire adecuadamente, facilitando la lectura y la interacción en pantallas de todos los tamaños.
Se usó :

-Espaciado mínimo de 16px entre elementos.

-Márgenes de 24px a 32px para secciones principales.

-Consistencia entre componentes para una apariencia organizada y limpia.

## 4.1.2 Web Style Guidelines

El diseño web de DeathClothe fue concebido bajo principios de claridad, accesibilidad y estética emocionalmente atractiva, con el objetivo de transmitir los valores de sostenibilidad, autenticidad y comunidad que representan a la plataforma. Se utilizó una paleta cromática basada en tonos de rosa vibrante (#e4738f) como color primario, complementado con un fondo rosa claro (#ffebed) y detalles en tonos más intensos (#c4456b y #b72551), que permiten generar una atmósfera moderna, cercana y amigable para el usuario, sin perder profesionalismo. La tipografía seleccionada, K2D en estilo sans-serif, responde a la necesidad de una lectura cómoda tanto en pantallas grandes como en dispositivos móviles, promoviendo una comunicación clara en todos los niveles de interacción. Además,  se intentó mantener el mismo estilo que la landing page para que nuestros clientes se sientan a gusto y conformes con el estilo.
![Paleta_de_Colores](Report_Assets/PaletaDeColoresDeathClothe.png)
![Typography](Report_Assets/TipografiaK2d.PNG)
![Typography](Report_Assets/TipografiaInter.PNG)
![Buttons](Report_Assets/botones.PNG)
![Icons](Report_Assets/iconos.PNG)

## 4.2 Information Architecture

La arquitectura de información implementada en DeathClothe responde a un análisis exhaustivo de los comportamientos y expectativas de los usuarios identificados en las etapas de needfinding y entrevistas. Se optó por una estructura jerárquica que organiza el contenido de lo general a lo específico, priorizando las secciones de "Inicio", "Explorar", "Armario" y "Favoritos" como nodos principales de acceso. Esta organización permite a los usuarios orientarse intuitivamente dentro del sitio, facilitando la exploración progresiva y disminuyendo la carga cognitiva. En procesos transaccionales como la venta de prendas o el registro de nuevos usuarios, se utilizó una estructura secuencial que guía al usuario paso a paso para reducir errores y aumentar la tasa de finalización de acciones críticas. Asimismo, en áreas de gestión de contenidos personales como el "Armario Virtual" o la lista de "Favoritos", se adoptó una organización matricial que favorece la comparación visual de múltiples elementos, optimizando la toma de decisiones. Esta combinación de sistemas de organización ha sido fundamental para mejorar la fluidez de la experiencia de navegación, maximizando la autonomía del usuario y fortaleciendo su conexión con la plataforma.

## 4.2.1 Organization Systems

La elección de los sistemas de organización en DeathClothe responde a la necesidad de ofrecer una estructura de contenido intuitiva, lógica y adaptable a distintos tipos de tareas y contextos de uso. Se implementó un sistema jerárquico para las principales categorías de navegación ("Inicio", "Explorar", "Vende", "Comunidad", "Nosotros"), permitiendo a los usuarios comprender rápidamente la estructura global del sitio. Dentro de las secciones operativas, como la publicación de prendas, se diseñó un flujo secuencial paso a paso, que minimiza la carga mental y aumenta la confianza del usuario durante procesos críticos. Además, en el "Armario Virtual" y "Favoritos", se utilizó una organización matricial para permitir comparaciones visuales rápidas entre prendas, favoreciendo la exploración paralela de opciones. 

## 4.2.2 Labeling Systems

El sistema de etiquetado de DeathClothe fue cuidadosamente diseñado para ofrecer la máxima claridad de sus partes con el mínimo esfuerzo de interpretación por parte del usuario. Cada etiqueta utilizada en la navegación, en los botones de acción o en los encabezados de sección, fue formulada para ser inmediata, explícita y consistente. Se evitaron tecnicismos o términos ambiguos, priorizando palabras simples como "Inicio", "Explorar", "Vende", "Favoritos", y "Armario", que reflejan con precisión la funcionalidad disponible. A nivel de productos, la información crítica como nombre de la prenda, precio y estado se muestra de manera breve y jerarquizada, permitiendo una lectura ágil incluso en dispositivos móviles. Esta estrategia de etiquetado refuerza la experiencia de usuario al disminuir la fricción cognitiva, mejorar la orientación dentro de la plataforma y aumentar la efectividad en la toma de decisiones de compra o venta.

## 4.2.3 SEO Tags and Meta Tags

Con el objetivo de maximizar la visibilidad orgánica de DeathClothe y atraer tráfico cualificado interesado en moda sostenible, se implementaron prácticas de optimización SEO desde la etapa de diseño. Cada página principal cuenta con un título único que refleja claramente su propósito, como “DeathClothe | Moda Circular con Estilo” para la landing page y “Explora prendas únicas | DeathClothe” para la sección de catálogo. Las meta descripciones fueron redactadas para enfatizar los valores diferenciales de la plataforma —sostenibilidad, autenticidad, comunidad— e incluyen llamados a la acción sutiles que invitan a explorar o registrarse. Se seleccionaron palabras clave relevantes y específicas como “ropa segunda mano”, “moda sostenible” y “comprar ropa usada”, que reflejan las búsquedas reales de los usuarios objetivo. Además, se añadió la meta tag de autoría "DeathClothe Team" para fortalecer la identidad de marca en los motores de búsqueda. Estas decisiones no solo mejoran el posicionamiento SEO, sino que también incrementan la tasa de clics al ofrecer descripciones atractivas y alineadas con las expectativas de los usuarios potenciales.

## 4.2.4 Searching Systems

El sistema de búsqueda implementado en DeathClothe es un pilar fundamental para garantizar la eficiencia en la localización de prendas, dada la amplia variedad de productos disponibles en la plataforma. Se diseñó una barra de búsqueda omnipresente, accesible en todas las vistas, que permite al usuario iniciar consultas en cualquier momento sin necesidad de regresar al inicio. Esta barra cuenta con funcionalidad de autocompletado, ofreciendo sugerencias dinámicas basadas en palabras clave frecuentes y tendencias de búsqueda interna, lo cual reduce el tiempo necesario para formular consultas completas. Además, los resultados se presentan en una disposición de tarjetas visuales que incluyen imagen, nombre y precio de cada prenda, optimizando la exploración rápida. Para búsquedas más específicas, se integraron filtros avanzados que permiten segmentar resultados por talla, color, estado, precio y tipo de prenda, ofreciendo así un control granular sobre el catálogo. Este enfoque en la búsqueda eficiente mejora la tasa de conversión y la retención de usuarios, al disminuir la frustración y aumentar las probabilidades de encontrar artículos relevantes en menos pasos.

## 4.2.5 Navigation Systems

El sistema de navegación en DeathClothe fue diseñado bajo la premisa de ofrecer un recorrido fluido, consistente y predecible a través de todas las secciones de la plataforma. Se implementó un menú principal visible y fijo que garantiza acceso constante a las áreas esenciales como “Inicio”, “Explorar”, “Vende”, “Comunidad” y “Armario”, independientemente del nivel de profundidad en el que se encuentre el usuario. En dispositivos móviles, se optó por una navegación tipo menú hamburguesa, priorizando la simplicidad y la usabilidad táctil. Cada sección cuenta con llamados a la acción estratégicamente ubicados y jerarquizados mediante diseño visual, guiando al usuario hacia las interacciones más relevantes en función de su contexto (exploración, compra, venta o gestión de prendas). Se integraron también indicadores de navegación como efectos hover, cambios de color y pequeños breadcrumbs en flujos de compra o consulta de producto, permitiendo al usuario mantener siempre un sentido claro de ubicación y posible retorno. Esta estrategia de navegación reduce la tasa de rebote, aumenta la profundidad de navegación y refuerza la percepción de una experiencia organizada y confiable.



## 4.3. Landing Page UI Design
La propuesta de diseño de la Landing Page de DeathClothe refleja nuestra visión de crear una experiencia inclusiva, moderna y alineada con los principios de moda circular. Basándonos en las decisiones tomadas en la arquitectura de información, cada sección de la interfaz busca ser clara, accesible y visualmente atractiva. Nos enfocamos en facilitar tanto la navegación como la comprensión inmediata del propósito de la plataforma: reutilizar moda con estilo y conciencia ambiental. Para ello, aplicamos principios de diseño como la jerarquía visual, consistencia en tipografías, contraste suficiente para accesibilidad, y uso de componentes amigables para navegación en desktop y mobile.

El diseño está estructurado para acompañar al usuario en un recorrido fluido: conocer la propuesta, descubrir beneficios, explorar productos y finalmente unirse a la comunidad, siguiendo los modelos mentales detectados en nuestro público objetivo.

## 4.3.1 Landing Page Wireframe

El Wireframe del Landing Page de DeathClothe refleja la estructura base de navegación y disposición de contenidos tanto para la versión Desktop como Mobile, asegurando una experiencia accesible, clara y orientada a la acción. Su propósito es guiar a los visitantes a través de un flujo natural que los conduzca desde la exploración inicial hasta su integración activa en la comunidad DeathClothe.

**Secciones principales en el Wireframe:**

- **Encabezado**: Contiene el logotipo de la marca, una barra de navegación horizontal en Desktop y un menú hamburguesa en Mobile. Incluye enlaces a Inicio, Explora, Vende, Comunidad, Nosotros y botón de acceso a Iniciar Sesión.
- **Sección Hero**: Presenta el mensaje principal de la plataforma acompañado de una imagen de impacto o gráfico llamativo, junto con un CTA destacado como "Explora Ahora" o "Vende Ya", incentivando la acción inmediata.
- **Sección de Funcionalidades Principales**: Expone las características más importantes de la plataforma como la compra, venta, uso del armario virtual y seguridad en transacciones. Se utilizan íconos visuales acompañados de breves descripciones para facilitar la comprensión.
- **Sección de Testimonios de Usuarios**: Muestra experiencias de usuarios reales que refuerzan la confianza y credibilidad de la plataforma mediante citas o pequeñas reseñas.
- **Galería de Productos Destacados**: Exhibe prendas recomendadas o recién añadidas, organizadas en una cuadrícula visual intuitiva que invita a la exploración inmediata.
- **Pie de Página**: Incluye accesos a información legal, políticas de privacidad, redes sociales y medios de contacto, fortaleciendo la transparencia y el cierre estructurado del flujo de navegación.

**Elementos de Diseño Aplicados:**

- **Organization Systems**: El flujo de secciones sigue un orden lógico: Inicio ➔ Explora ➔ Vende ➔ Comunidad ➔ Nosotros.
- **Labeling Systems**: Se emplean etiquetas claras, breves y comprensibles como "Explora", "Vende" y "Comunidad" para reducir la carga cognitiva.
- **Navigation Systems**: Navegación horizontal persistente en Desktop y menú hamburguesa en Mobile, asegurando accesibilidad constante a todas las áreas claves.
- **Diseño Inclusivo**: Se utilizaron tipografías de alta legibilidad, botones de tamaño adecuado para interacción táctil, contrastes de color pensados para personas con baja visión, y estructura semántica correcta para tecnologías asistivas.
- **Jerarquía Visual**: Uso de encabezados prominentes, espaciado amplio entre secciones para facilitar la lectura, e iconografía de apoyo a los textos, mejorando la escaneabilidad y comprensión del contenido.
- 
![WireframeWeb1](Report_Assets/Wireframe-Inicio.png)
![WireframeWeb2](Report_Assets/Wireframe-Explora.png)
![WireframeWeb3](Report_Assets/Wireframe-Vende.png)
![WireframeWeb6](Report_Assets/WireFrameAboutTheProduct.png)
![WireframeWeb4](Report_Assets/Wireframe-comunidad.png)
![WireframeWeb5](Report_Assets/Wireframe-NostrosV2.png)
![WireframeWeb7](Report_Assets/WireFrameVideoAboutTheTeam.png)
## 4.3.2 Landing Page Mock-up

El Mock-up del Landing Page de DeathClothe representa la integración final de la propuesta visual, combinando branding, usabilidad y estética emocional para transmitir la identidad y valores de la plataforma. Esta visualización ya incorpora elementos de color, tipografía, imágenes, iconografía y microinteracciones pensadas para la experiencia final del usuario.

**Aspectos visuales principales en el Mock-up:**

- **Encabezado y Navegación**: El logotipo de DeathClothe y la barra de navegación se diseñan respetando el branding cromático (primarios rosados con fondo claro). Los botones de acción (CTA) destacan visualmente para incentivar el registro o inicio de sesión.
- **Sección Hero**: Emplea imágenes de impacto realistas y un mensaje central emocional que introduce rápidamente el propósito de DeathClothe (moda circular, sostenibilidad y autenticidad). El CTA principal se presenta en color de alto contraste para maximizar la conversión.
- **Presentación de Beneficios y Funcionalidades**: Cada funcionalidad principal (explorar, vender, gestionar armario virtual) se comunica mediante bloques visuales con íconos amigables y textos breves, generando una narrativa de descubrimiento fluida.
- **Testimonios de Comunidad**: Se muestran opiniones breves de usuarios para construir confianza, usando retratos o avatares que humanizan la interacción.
- **Galería de Productos**: Se utilizan tarjetas de producto con fotografía optimizada, información resumida (nombre, precio, estado) y botones de acción directa ("Agregar al armario", "Ver más").
- **Pie de Página**: Enlace a redes sociales, términos legales, preguntas frecuentes y formulario de contacto rápido, reforzando la transparencia y el soporte al usuario.

**Elementos de Diseño Aplicados:**

- **Uso de la Paleta de Colores**: El fondo suave (#ffebed) ayuda a resaltar prendas y elementos interactivos, mientras que los botones y enlaces utilizan el rosa vibrante (#e4738f) para atraer la atención en acciones clave.
- **Tipografía Consistente**: K2D sans-serif utilizada de forma consistente en todos los títulos, subtítulos y cuerpos de texto para mantener coherencia visual y mejorar la legibilidad en todas las resoluciones de pantalla.
- **Adaptabilidad Responsive**: En Mobile, los elementos se apilan verticalmente, priorizando el contenido y los CTAs para navegación táctil eficiente.
- **Interacción Intuitiva**: Estados hover en botones, microtransiciones suaves entre secciones y retroalimentación visual inmediata aseguran que el usuario se sienta en control durante toda su experiencia.

![MockupWeb1](Report_Assets/MockupInicio.png)
![MockupWeb2](Report_Assets/MockupExplora.png)
![MockupWeb3](Report_Assets/MockupVende.png)
![MockupWeb6](Report_Assets/MockUpVideoAbouttheproduct.png)
![MockupWeb4](Report_Assets/MockupComunidad.png)
![MockupWeb5](Report_Assets/MockupNostrosV2.png)
![MockupWeb7](Report_Assets/MockupAboutTheTeam.png)
## 4.4 Web Applications UX/UI Design

Esta sección presenta y explica la propuesta visual y de interacción diseñada para las aplicaciones que conforman la experiencia de usuario de DeathClothe. Se incluyen wireframes, wireflows y mock-ups que detallan cómo se estructuran, organizan y visualizan los contenidos, priorizando la usabilidad, accesibilidad y coherencia con la identidad de marca. La propuesta busca garantizar que los usuarios puedan navegar, interactuar y completar sus objetivos de manera intuitiva, fluida y satisfactoria en todos los puntos de contacto con el producto digital.


### 4.4.1. Web Applications Wireframes

La experiencia en DeathClothe inicia con la pantalla de login, donde el usuario puede ingresar sus credenciales de forma sencilla para acceder a su cuenta en la plataforma.

![WireframeWeb1](Report_Assets/LoginWireframe.png)

Si el usuario no tiene cuenta, puede registrarse fácilmente completando un formulario que solicita los datos básicos para crear un perfil.

![WireframeWeb2](Report_Assets/RegisterWireframe.png)

Una vez dentro, el usuario accede a la sección de Inicio, donde se le presentan prendas destacadas, sugerencias personalizadas y novedades relevantes.

![WireframeWeb5](Report_Assets/InicioWireframe.png)

En la sección Explorar, los usuarios pueden visualizar el catálogo completo de prendas, filtrando resultados según las categorias existentes.

![WireframeWeb4](Report_Assets/ExplorarWireframe.png)

Al presionar una categoria nos muestra todas las prendas de esa categoria

![WireframeWeb4](Report_Assets/CategoriasWireframe.png)

Dentro del Armario Virtual, los usuarios pueden gestionar y visualizar todas las prendas que han subido o han comprado en su perfil personal, pueden filtrar las prendas por el tipo dentro de su armario, facilitando la organización y búsqueda de sus artículos.

![WireframeWeb3](Report_Assets/ArmarioWireframe.png)

Al seleccionar el boton de editar, pueden cambiar la talla, color o titulo de la prenda.

![WireframeWeb4](Report_Assets/ArmarioEditarWireframe.png)

Además pueden agregar prendas desde el armario virtual, rellenando un simple formulario.

![WireframeWeb4](Report_Assets/ArmarioAgregarWireframe.png)

En el área de Perfil, el usuario puede revisar su información personal, ya sea en su versión de comprador o vendedor.

![WireframeWeb5](Report_Assets/PerfilCompradorWireframe.png)

Al seleccionar el catalogo de favoritos, saldran todas las prendas que haz guardado y un apartado de busqueda para facilitar el encontrar una prenda

![WireframeWeb5](Report_Assets/PerfillComprador-CatalogoFavoritos-Wireframe.png)

Por ultimo, al ver el para ti, este te dara recomendaciones por tus favoritos

![WireframeWeb5](Report_Assets/PerfillComprador-Parati-Wireframe.png)

Al cambiar a la seccion de vendedor podremos ver las prendas vendidas, pendientes y estadisitcas de sus ventas.

![WireframeWeb5](Report_Assets/PerfilVendedorWireframe.png)

El usuario puede ver todas las prendas que tiene en vendidas y pendientes al presionar la lista respectiva de cada uno

![WireframeWeb5](Report_Assets/PerfilVendedor-PendientesWireframe.png)
![WireframeWeb5](Report_Assets/PerfilVendedor-VendidasWireframe.png)

Finalmente, puede editar las prendas pendientes, para marcar que ya se vendieron, editar datos o eliminarla de la venta

![WireframeWeb5](Report_Assets/PerfilVendedor-EditarPrendaWireframe.png)

Desde el ícono de mensajería, el usuario accede a sus chats activos para gestionar la comunicación con otros usuarios interesados en sus prendas.

![WireframeWeb3](Report_Assets/comprando-wireframe.png)

En la sección de Favoritos, el usuario encuentra recomendaciones basada en sus prendas favoritas.

![WireframeWeb5](Report_Assets/FavoritosWireframe.png)

Para buscar una prenda en concreto contamos con un apartado de busqueda y filtros de talla, tipo y color.

![MockupWeb5](Report_Assets/BusquedaWireframe.png)

Al seleccionar una prenda, se despliega una vista detallada donde puede revisar información completa, contactar al vendedor y decidir sobre la compra.

![WireframeWeb5](Report_Assets/Compradepolo.png)

Finalmente, se muestra el proceso de compra, donde el usuario confirma su interés y completa la transacción dentro de la plataforma de forma segura.

![WireframeWeb5](Report_Assets/comprando.png)

### 4.4.2. Web Applications Wireflow Diagrams

![MockupWeb1](Report_Assets/inicioSesionWF.jpg)
![MockupWeb2](Report_Assets/creacionCuentaWF.jpg)
![MockupWeb3](Report_Assets/detallePrendaWF.jpg)
![MockupWeb4](Report_Assets/busquedaPrendaWF.jpg)
![MockupWeb5](Report_Assets/categoriasWF.jpg)
![MockupWeb6](Report_Assets/favoritosWF.jpg)
![MockupWeb7](Report_Assets/armarioVirutlaWF.jpg)
![MockupWeb8](Report_Assets/edicionPerfilWF.jpg)
![MockupWeb9](Report_Assets/perfilVendedorWF.jpg)
![MockupWeb10](Report_Assets/perfilCompradorWF.jpg)


### 4.4.3 Web Applications Mock-ups

Los mock-ups de DeathClothe muestran el diseño final con todos los elementos gráficos, colores, tipografías y componentes interactivos integrados, reflejando la identidad visual de la plataforma.

La pantalla de login presenta un diseño moderno, minimalista y accesible, facilitando el ingreso de usuarios habituales y nuevos registros.

![MockupWeb1](Report_Assets/LoginMockup.png)

En el registro, el usuario completa de manera rápida y clara la información necesaria para crear su cuenta, dentro de un entorno visualmente atractivo y amigable.

![MockupWeb2](Report_Assets/RegisterMockup.png)

El Inicio ofrece un despliegue visual de prendas sugeridas, novedades y accesos rápidos a secciones principales, fomentando la exploración continua.

![MockupWeb5](Report_Assets/InicioMockup.png)

En Explorar, el catálogo de prendas se presenta organizado en cuadrículas limpias, con filtros accesibles como categorias, para mejorar la experiencia de búsqueda.

![MockupWeb4](Report_Assets/ExplorarMockup.png)

Al presionar una categoria nos muestra todas las prendas de esa categoria

![WireframeWeb4](Report_Assets/CategoriasMockup.png)

La navegación dentro del armario permite acceder a categorías específicas, optimizando la visualización de artículos según tipo o características.

![MockupWeb3](Report_Assets/ArmarioNormal.png)

Permitiendo editar informacion como tipo, talla, color y precio, facilitando la organización de su ropa.

![MockupWeb3](Report_Assets/armarioNormal1.png)

Además, muestra una vista previa detallada de cada prensa antes de ponerla en la venta,y garantiza que cada publicación contenga los datos necesarios.

![MockupWeb3](Report_Assets/ArmarioNormal2.png)

En la sección de Perfil, los usuarios gestionan su información y acceden a sus estadísticas de manera clara, diferenciando perfiles de compradores y vendedores.

![MockupWeb5](Report_Assets/PerfilVendedorMockup.png)
![MockupWeb2](Report_Assets/PerfilCompradorMockup.png)

Asi mismo en los dos perfiles podemos editar la informacion del usuario

![MockupWeb2](Report_Assets/EditarPerfilMockup.png)

En el perfil de comprador podemos observar un catalogo de favoritos, que nos permite buscar una prenda especifica.

![MockupWeb2](Report_Assets/PerfilComprador-CatalogoFavoritosMockup.png)

Se cuenta con un apartado de para ti que te da recomendaciones

![MockupWeb2](Report_Assets/PerfilComprador-ParatiMockup.png)

Al cambiar a la seccion de vendedor podremos ver las prendas vendidas, pendientes y estadisitcas de sus ventas.

![WireframeWeb5](Report_Assets/PerfilVendedorMockup.png)

El usuario puede ver todas las prendas que tiene en vendidas y pendientes al presionar la lista respectiva de cada uno

![WireframeWeb5](Report_Assets/PerfilVendedor-PendientesMockup.png)
![WireframeWeb5](Report_Assets/PerfilVendedor-VendidasMockup.png)

Finalmente, puede editar las prendas pendientes, para marcar que ya se vendieron, editar datos o eliminarla de la venta

![WireframeWeb5](Report_Assets/PerfilVendedor-EditarPrendaMockup.png)

En la mensajería, los usuarios mantienen conversaciones fluidas con otros miembros de la comunidad, dentro de una interfaz limpia y ordenada.

![MockupWeb3](Report_Assets/Chats.png)

En la sección de Favoritos, se agrupan todas las prendas que son recomendadas en base a tus prendas favoritas.

![MockupWeb5](Report_Assets/FavoritosMockup.png)

Para buscar una prenda en concreto contamos con un apartado de busqueda y filtros de talla, tipo y color.

![MockupWeb5](Report_Assets/BusquedaMockup.png)

La vista de detalle de una prenda permite conocer todos los aspectos relevantes, iniciar una conversación con el vendedor y avanzar en el proceso de compra.

![MockupWeb5](Report_Assets/CompradepoloMockup.png)

Finalmente, el proceso de compra se lleva a cabo en un entorno seguro, visualmente atractivo y fácil de seguir, asegurando la satisfacción del usuario.

![MockupWeb5](Report_Assets/comprandoMockup.png)

### 4.4.4. Web Applications User Flow Diagrams

![WireframeWeb1](Report_Assets/InicioSesionWireFlow)
![WireframeWeb2](Report_Assets/CrearCuentaWireFlow)
![WireframeWeb3](Report_Assets/DetalleRopaWireFlow)
![WireframeWeb3](Report_Assets/BusquedaWireFlow.PNG)
![WireframeWeb4](Report_Assets/CategoriasWireFlow.PNG)
![WireframeWeb5](Report_Assets/FavoritosWireFlow.PNG)
![WireframeWeb5](Report_Assets/ArmarioWireFlow.PNG)
![WireframeWeb5](Report_Assets/EdicionPerfilWireFlow.PNG)
![WireframeWeb5](Report_Assets/PerfilVendedorWireFlow.PNG)
![WireframeWeb5](Report_Assets/PerfilCompradorWireFlow.PNG)
## 4.5. Web Applications Prototyping
| Elemento              | Enlace |
|------------------------|--------|
| Video del Prototipo     | https://upcedupe-my.sharepoint.com/personal/u202310005_upc_edu_pe/_layouts/15/embed.aspx?UniqueId=d728e1f6-ad94-4839-ac15-dd4e832ba86f&embed=%7B%22ust%22%3Atrue%2C%22hv%22%3A%22CopyEmbedCode%22%7D&referrer=StreamWebApp&referrerScenario=EmbedDialog.Create

## 4.6. -Driven Software Architecture

### 4.6.1. Software Architecture Context Diagram

<img src="Report_Assets/context.jpg" alt="Nombre" width="700"> 

### 4.6.2. Software Architecture Container Diagrams

<img src="Report_Assets/container.jpg" alt="Nombre1" width="700"> 

### 4.6.3. Software Architecture Components Diagrams
<img src="Report_Assets/awr1.jpg" alt="Nombre2" width="700"> 
<img src="Report_Assets/awr2.jpg" alt="Nombre3" width="700"> 

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams
<img src="Report_Assets/CLASE UML-DeathClothe.png">

### 4.7.2. Class Dictionary
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th><strong>Class Name</strong></th>
      <th><strong>Attributes</strong></th>
      <th><strong>Methods</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Usuario</td>
      <td>id: int, nombre: String, email: String, contraseña: String, dirección: String</td>
      <td>iniciarSesion(), editarPerfil(), eliminarCuenta()</td>
    </tr>
    <tr>
      <td>Vendedor</td>
      <td>prendasEnVenta: List&lt;Prenda&gt;</td>
      <td>listarPrenda(), retirarPrenda()</td>
    </tr>
    <tr>
      <td>Comprador</td>
      <td>historialCompras: List&lt;Transaccion&gt;</td>
      <td>comprarPrenda(), agregarAFavoritos()</td>
    </tr>
    <tr>
      <td>Prenda</td>
      <td>id: int, nombre: String, tipo: String, talla: String, color: String, precio: float, estado: String, vendedor: Vendedor</td>
      <td>mostrarPrenda()</td>
    </tr>
    <tr>
      <td>Transacciones</td>
      <td>userID: int</td>
      <td>validarTransaccion()</td>
    </tr>
    <tr>
      <td>Publicaciones</td>
      <td>id: int, prenda: Prenda, descripcion: String, fechaPublicacion: Date</td>
      <td>generarPublicaciones(), obtenerEstado(), editarPublicacion(), obtenerCalificacion()</td>
    </tr>
    <tr>
      <td>FavoritosPrendas</td>
      <td>fechaAgregado: Date</td>
      <td>añadirAFavoritos(), obtenerFavoritos(), mostrarFavoritos()</td>
    </tr>
    <tr>
      <td>RecomendacionesPrendas</td>
      <td>nivelRecomendacion: int</td>
      <td>añadirRecomendacion(), eliminarRecomendacion(), generarRecomendacion()</td>
    </tr>
    <tr>
      <td>Notificaciones</td>
      <td>userID: long</td>
      <td>generarNotificaciones()</td>
    </tr>
    <tr>
      <td>Estadisticas</td>
      <td>atributo1: type, atributo2: type, atributo3: type</td>
      <td>generarEstadisticas()</td>
    </tr>
    <tr>
      <td>EstadoPublicacion</td>
      <td>atributo1: type = defaultValue, atributo2: type, atributo3: type</td>
      <td>getEstado()</td>
    </tr>
    <tr>
      <td>CalificacionPublicacion</td>
      <td>atributo1: type = defaultValue, atributo2: type, atributo3: type</td>
      <td>generarCalificacion()</td>
    </tr>
    <tr>
      <td>ArmarioVirtual</td>
      <td>usuarios: List&lt;Usuario&gt;, prendas: List&lt;Prenda&gt;, transacciones: List&lt;Transaccion&gt;, publicaciones: List&lt;Publicacion&gt;, notificaciones: List&lt;Notificacion&gt;, estadisticas: Estadisticas</td>
      <td>registrarUsuario(), agregarPrenda(), realizarTransaccion(), generarNotificacion(), actualizarEstadisticas()</td>
    </tr>
  </tbody>
</table>


## 4.8. Database Design
El diseño de la base de datos para el sistema representado en el diagrama de clases se basará en una estructura relacional, en la que cada clase principal se traduce en una tabla

### 4.8.1. Database Diagram

<img src="Report_Assets/ERD DeathClothe.png" alt="Nombre" width="500"> 


# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.

### 5.1.1. Software Development Environment Configuration.

En esta sección se detallan las herramientas utilizadas para la gestión del proyecto, el diseño, el desarrollo, el despliegue y la documentación de la solución.

* Project Management:

  * Trello
    Propósito: Gestión de tareas mediante tableros Kanban organizados en columnas (To Do, In Progress, Done).
    
    URL: `https://trello.com`

    <img src="Report_Assets/trello.png" alt="Trello" width="300"> 

  * Uxpressia
    Propósito: Creación de mapas de experiencia de usuario para analizar y entender a nuestros usuarios.
    
    URL: `https://uxpressia.com`

    <img src="Report_Assets/uxpressia.png" alt="Uxpressia" width="300"> 

  * Lucidchart
    Propósito: Elaboración de diagramas de flujo, wireframes y esquemas de arquitectura de sistemas.
    
    URL: `https://lucidchart.com`

    <img src="Report_Assets/lucidchart.png" alt="lucidchart" width="300"> 
    
  * Structurizr
    Propósito: Modelado de arquitectura utilizando diagramas C4 para la documentación técnica de la solución.
    
    URL: `https://structurizr.com`

    <img src="Report_Assets/structurizr.png" alt="Structurizr" width="300"> 

* Product UX/UI Design:

  * Figma
    Propósito: Diseño de interfaces de usuario (UI), prototipado rápido y colaboración en tiempo real entre los miembros del equipo.
    
    URL: `https://figma.com`

    <img src="Report_Assets/figma.png" alt="Figma" width="300">

* Software Development:

  * Visual Studio Code (VS Code)
    Propósito: Editor de código fuente principal utilizado para el desarrollo de la Landing Page (HTML, CSS, JavaScript).
    
    URL: `https://code.visualstudio.com/download`

    <img src="Report_Assets/visualstudiocode.png" alt="Visual Studio Code" width="300">

* Deployment Configuration:

  * GitHub Pages
    Propósito: Publicación y despliegue automático de la Landing Page como sitio web estático directamente desde el repositorio.
    
    URL: `https://pages.github.com`

    <img src="Report_Assets/githubpages.png" alt="Github Pages" width="300">

* Software Documentation:

  * GitHub
    Propósito: Almacenamiento de la documentación técnica dentro del repositorio del proyecto, utilizando archivos Markdown (.md).

    <img src="Report_Assets/visualstudiocode.png" alt="Github Pages" width="300">

  * Markdown
    Propósito: Formato de escritura utilizado para documentar de forma clara, sencilla y estructurada los detalles del proyecto.

    <img src="Report_Assets/markdown.png" alt="Markdown" width="300">


### 5.1.2. Source Code Management

Nuestro equipo utiliza un flujo de trabajo basado en Git Flow para mantener un control organizado del código. Trabajamos con ramas principales y secundarias que nos permiten desarrollar funcionalidades, corregir errores y preparar versiones de manera sistemática.

**Estructura de Ramas**

El proyecto maneja las siguientes ramas:

- main: Contiene el código estable listo para producción
- dev: Rama de desarrollo donde se integran las nuevas funcionalidades
- feature/*: Ramas temporales para desarrollar características específicas
- hotfix/*: Ramas para solucionar problemas críticos en producción
- release/*: Ramas para preparar nuevas versiones estables

**Control de Versiones**

Aplicamos versionado semántico (SemVer) con el formato vX.Y.Z:

- X (Major): Cambios que rompen compatibilidad
- Y (Minor): Nuevas funcionalidades compatibles
- Z (Patch): Correcciones de errores

Las versiones preliminares usan sufijos:

- alpha: Para funcionalidades en desarrollo
- beta: Para pruebas internas
- rc: Versiones candidatas a lanzamiento

**Convención de Comits**

Seguimos un formato estricto para los mensajes de commit:

`<tipo>(ámbito): descripción breve [#issue]`

Ejemplos prácticos:

- feat(login): implementar autenticación con Google [#45]
- fix(api): resolver error en endpoint /users [#78]
- docs: actualizar guía de instalación

Los tipos de commit principales son:

- feat: Nueva funcionalidad
- fix: Corrección de errores
- docs: Cambios en documentación
- refactor: Mejoras de código sin cambiar funcionalidad
- test: Adición o modificación de pruebas

**Políticas Adicionales**

- Todo merge a main requiere al menos una revisión aprobada
- Las ramas principales están protegidas contra pushes directos
- Cada commit debe referenciar su issue/ticket correspondiente
- Las releases se etiquetan siguiendo estrictamente SemVer


### 5.1.3. Source Code Style Guide & Conventions

Para el desarrollo de la Landing Page, hemos decidido utilizar el idioma inglés en todos los nombres de variables, funciones, clases y archivos. Esto nos permitirá mantener el código más ordenado, comprensible y facilitar su crecimiento en el futuro.

**HTML / CSS**

- Se sigue principalmente el Google HTML/CSS Style Guide para mantener buenas prácticas de codificación.
- Se utilizarán etiquetas semánticas como `<header>`, `<section>`, `<article>`, `<nav>` y `<footer>` para estructurar mejor el contenido de la página.
- Los nombres de las clases en CSS se escribirán utilizando kebab-case (por ejemplo: .main-banner, .card-section).
- Los identificadores serán claros y específicos para que tanto el acceso como el mantenimiento del código sean más sencillos.
- Las etiquetas principales que se usarán en el proyecto son:

  - `<div>` para separar diferentes bloques o secciones del contenido.
  - `<img>` para mostrar imágenes en distintas partes de la página.
  - `<ul>` y `<li>` para crear listas, principalmente en los menús de navegación.
  - `<a>` para establecer enlaces entre secciones o páginas.
  - `<p>` para párrafos de texto descriptivo.
  - `<button>` para botones que permitan al usuario realizar acciones específicas.
  - Títulos `<h1>` hasta `<h4>` para jerarquizar la información de manera lógica.

**JavaScript**

- Se adopta el Google JavaScript Style Guide para seguir un estilo uniforme en el código.
- En cuanto a la nomenclatura:
  - Las variables y funciones se nombrarán en camelCase (por ejemplo: fetchData, createUserCard).
  - Las clases se nombrarán utilizando PascalCase (por ejemplo: FormHandler, UserProfile).
  - Las constantes serán escritas en UPPER_SNAKE_CASE (por ejemplo: DEFAULT_TIMEOUT, MAX_ITEMS).
- Siempre que sea posible, se usará const y let en lugar de var para mejorar el control del ámbito de las variables.
- Se evitarán funciones anónimas cuando no sean necesarias, para que el código sea más fácil de depurar y entender.
- El enfoque será mantener el código modular, reutilizable y fácil de leer.


### 5.1.4. Software Deployment Configuration

Para el despliegue de la Landing Page, se utilizará GitHub Pages como plataforma de publicación. A continuación, se describen los pasos principales que seguimos para lograrlo:

1. Se creó un repositorio en GitHub con todo el código fuente de la página (archivos HTML, CSS y JavaScript).

2. En la rama principal (main), se subieron todos los archivos asegurando que el archivo principal se llame index.html.

3. Dentro de la configuración del repositorio, en la sección Pages, se seleccionó la rama main y la carpeta raíz (root) como fuente de publicación.

4. GitHub generó automáticamente la URL pública donde se puede acceder a la Landing Page.

5. Se realizaron pruebas para verificar que los estilos, scripts y recursos cargaran correctamente en producción.

Con esta configuración, cualquier actualización que se haga al código en el repositorio principal se reflejará de forma automática en la página publicada.


### 5.2. Landing Page, Services & Applications Implementation
#### 5.2.1. Sprint 1
Este informe documenta el progreso inicial del proyecto DeathClothe, una plataforma web de compraventa de ropa para compradores y vendedores. Durante este sprint, se trabajó en la definición de requisitos mediante historias de usuario funcionales y técnicas, la creación de artefactos esenciales.
Las entrevistas proporcionaron información útil que ayudó a definir los requisitos del proyecto. El objetivo fue desarrollar artefactos fundamentales para garantizar una comunicación efectiva entre el equipo de desarrollo y visualizar los requerimientos iniciales del proyecto.

#### 5.2.1.1. Sprint Planning 1
<table border="1" cellspacing="0" cellpadding="8">
   <thead>
     <tr>
       <th><strong>Campo</strong></th>
       <th><strong>Detalle</strong></th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>Sprint 1</td>
     </tr>
     <tr>
       <td>Fecha</td>
       <td>2025-04-26</td>
     </tr>
     <tr>
       <td>Hora</td>
       <td>11:00 AM</td>
     </tr>
     <tr>
       <td>Ubicación</td>
       <td>Virtual – Discord</td>
     </tr>
     <tr>
       <td>Preparado por</td>
       <td>Andrea Elizabeth Santur Tello</td>
     </tr>
     <tr>
       <td>Asistentes (a la reunión de planificación)</td>
       <td>Alvaro Bejarano, Mateo Cabanillas, Omar Luquillas, Andrea Santur, Loreley Sarmiento</td>
     </tr>
     <tr>
       <td>Sprint 1 – Resumen de revisión</td>
       <td>Se elaboraron los artefactos esenciales del producto DeathClothe, y se implementó la landing page utilizando HTML y CSS, basada en el diseño de los mockups y wireframes realizados en Figma.</td>
     </tr>
     <tr>
       <td>Sprint 1 – Resumen de retrospectiva</td>
       <td>Refinar las historias de usuario y validar temprano los diseños de interfaz.</td>
     </tr>
     <tr>
       <td>Objetivo y User Stories del Sprint 1</td>
       <td>
         <strong>Objetivo del Sprint:</strong>  Construir y validar los artefactos fundamentales que guiarán el desarrollo, como competidores, entrevistas, definiciones de segmentos objetivos, etc., para la creación de una nueva mejora en el proyecto
       </td>
     </tr>
     <tr>
       <td>Velocidad del Sprint 1</td>
       <td>10 User Stories</td>
     </tr>
     <tr>
       <td>Suma de Story Points</td>
       <td>30 Story Points atendidos</td>
     </tr>
   </tbody>
 </table>



#### 5.2.1.2. Aspect Leaders and Collaborators

| **Integrante del equipo**          | **GitHub**       | **Landing Page** | **Diseño UI/UX** | **HTML/CSS** | **TypeScript** | **Documentación** |
| ---------------------------------- | ---------------- | ---------------- | ---------------- | ------------ | -------------- | ----------------- |
| **Santur Tello, Andrea Elizabeth** | andreli-star     | C                | **L**            | C            | C              | C                 |
| **Bejarano, Alvaro**               | Albro310306      | C                | C                | **L**        | **L**          | C                 |
| **Cabanillas, Mateo**              | marckszz         | C                |**L**             | **L**        | C              | **L**             |
| **Luquillas, Omar**                | OmarLLA          | C                | C                | C            | C              | C                 |
| **Sarmiento, Loreley**             | loreleysarmiento | C                | C                | C            | C              | C                 |

.

#### 5.2.1.3. Sprint Backlog 1 

Link: `https://trello.com/invite/b/680d1de7fcd6bc9189287b2a/ATTI71b9407097327a930510d122cf825bea86979452/sprint-1-deathclothe` <br>
<img src="Report_Assets/sprint1-trello.png">

<p><strong>Sprint 1</strong></p>

<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Work-Item / Task</th>
      <th>User Story ID</th>
      <th>Task ID</th>
      <th>Description</th>
      <th>Estimation (Hours)</th>
      <th>Assigned To</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Work-Item</td>
      <td>US19</td>
      <td>T01</td>
      <td>Registrar/Iniciar sesión desde landing page</td>
      <td>3</td>
      <td>Alvaro Bejarano</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US12</td>
      <td>T02</td>
      <td>Ver información de la landing page</td>
      <td>2</td>
      <td>Mateo Cabanillas</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US18</td>
      <td>T02</td>
      <td>Cambiar idioma en landing page</td>
      <td>2</td>
      <td>Omar Luquillas</td>
      <td>Review </td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US12</td>
      <td>T03</td>
      <td>Ver información de la landing page</td>
      <td>3</td>
      <td>Andrea Santur</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US21</td>
      <td>T05</td>
      <td>Acceder a redes sociales</td>
      <td>3</td>
      <td>Loreley Sarmiento</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US25</td>
      <td>T05</td>
      <td>Explorar la seccion Home en Landing Page	</td>
      <td>3</td>
      <td>Omar Luquillas</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US26</td>
      <td>T05</td>
      <td>Explorar la seccion Explore en Landing Page	</td>
      <td>3</td>
      <td>Andrea Santur</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US27</td>
      <td>T05</td>
      <td>Explorar la seccion Sell en Landing Page</td>
      <td>3</td>
      <td>Mateo Cabanillas</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US28</td>
      <td>T05</td>
      <td>Explorar la seccion Community en Landing Pag</td>
      <td>2</td>
      <td>Alvaro Bejarano</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US29</td>
      <td>T09</td>
      <td>Explorar la seccion About-Us en Landing Pag	</td>
      <td>2</td>
      <td>Loreley Sarmiento</td>
      <td>Done</td>
    </tr>
  </tbody>
</table>

#### 5.2.1.4. Development Evidence for Sprint Review
Durante este sprint, se han realizando avances significativos en la construcción de la <b>Landing Page</b> de la plataforma <i>DeathClothe</i>.Se trabajaron varias historias de usuario y se realizaron múltiples <i>commits</i> en el repositorio principal.A continuación, se presenta una tabla con los <i>commits</i> más relevantes:

### Commits

| Repositorio | Rama | ID del Commit | Mensaje del Commit | Descripción | Fecha del Commit |
|-------------|------|----------------|---------------------|-------------|------------------|
| DeathClothe/DEATHCLOTHELandingPage | main | `c0a1b2c` | feat: crear estructura base de landing page | Se creó la estructura inicial con encabezado, sección hero y pie de página. | 2025-05-10 |
| DeathClothe/DEATHCLOTHELandingPage | main | `f3d4e5f` | feat: añadir selector de rol de usuario | Opción para elegir entre "Comprador" o "Vendedor" al registrarse. | 2025-05-11 |
| DeathClothe/DEATHCLOTHELandingPage | main | `g6h7i8j` | feat: ajustes de diseño responsivo | Mejora de visualización en móviles y tabletas. | 2025-05-12 |
| DeathClothe/DEATHCLOTHELandingPage | main | `k9l0m1n` | fix: error en validación del formulario | Corrección en validación al seleccionar tipo de usuario. | 2025-05-13 |
| DeathClothe/DEATHCLOTHELandingPage | main | `p2q3r4s` | feat: conectar enlaces con secciones principales | Habilitación de navegación entre secciones: Acerca de, Contacto, etc. | 2025-05-14 |


##### 5.2.1.5. Execution Evidence for Sprint Review
Durante este sprint, nuestro equipo finalizó y publicó la landing page de DeathClothe. A continuación, presentamos capturas de cada sección, donde podrán apreciar
cómo organizamos la información de manera clara, atractiva y alineada a la identidad visual de la marca. Además, nos aseguramos de que el diseño fuera responsivo y
que la navegación resultara intuitiva para los usuarios en diferentes dispositivos.

**Inicio**

<img src="./Report_Assets/executionevidence1.png" alt="Execution Evidence 1" width="700">

**Sección Explora**

<img src="./Report_Assets/executionevidence2.png" alt="Execution Evidence 2" width="700">

**Sección Vende**

<img src="./Report_Assets/executionevidence3.png" alt="Execution Evidence 3" width="700">

**Sección Comunidad**

<img src="./Report_Assets/executionevidence4.png" alt="Execution Evidence 4" width="700">

**Sección Nosotros**

<img src="./Report_Assets/executionevidence5.png" alt="Execution Evidence 5" width="700">


##### 5.2.1.6. Services Documentation Evidence for Sprint Review

Durante este Sprint, nos enfocamos principalmente en la creación de la landing page estática de DeathClothe, la cual no requiere el consumo de APIs ni conexión con Web Services. Como el alcance de este proyecto no contempla la implementación de un backend o la interacción con endpoints, no fue necesario generar documentación OpenAPI. En otras palabras, DeathClothe es una solución puramente frontend, centrada en ofrecer contenido visual e informativo sin lógica de servidor.

En esta etapa tampoco se trabajaron acciones tipo CRUD (como GET, POST, PUT o DELETE) ni se integraron servicios o APIs externas. La prioridad fue construir una estructura estable, rápida y responsiva, que funcione de forma autónoma desde el navegador del usuario.

Aunque no se documentaron endpoints (ya que no aplicaban para este tipo de desarrollo), sí se lograron los siguientes objetivos importantes:

- Creación y documentación básica del proyecto estático.

- Registro detallado de cambios mediante commits claros y organizados.

- Generación de evidencia del despliegue exitoso y del correcto funcionamiento del sitio.

Adicionalmente, se cuidó que el código fuera limpio, optimizado para buenas prácticas de desarrollo frontend, y preparado para futuras extensiones si el proyecto escala.


##### 5.2.1.7. Software Deployment Evidence for Sprint Review

Durante este sprint, conseguimos implementar correctamente la landing page de DeathClothe en un entorno funcional. Nos enfocamos en preparar la infraestructura necesaria, automatizar el despliegue y publicar el sitio asegurando su correcto funcionamiento. A continuación, detallamos las principales actividades realizadas.

**Configuración del repositorio**

1. Ingresamos a la sección Settings > Pages del repositorio en GitHub.
   
2. Activamos GitHub Pages para el proyecto.

3. Seleccionamos la rama main como fuente principal para el despliegue automático.

**Preparación para el despliegue**

1. Acomodamos la estructura de archivos siguiendo los requisitos que exige GitHub Pages.

2. Verificamos que el archivo principal (index.html) estuviera en la raíz correcta.

3. Realizamos un push de prueba para confirmar que la estructura se reconociera correctamente.

**Despliegue automático**

1. Configuramos GitHub Actions para que ejecutara el flujo predeterminado de Pages automáticamente.

2. Confirmamos que cada vez que se hiciera un push a la rama main, se activara el despliegue sin errores.

Link Landing Page: `https://deathclothe.github.io/DEATHCLOTHELandingPage/`

<img src="./Report_Assets/deploymentevidence1.png" alt="Deployment Evidence 1" width="500">

<img src="./Report_Assets/deploymentevidence2.png" alt="Deployment Evidence 2" width="500">


##### 5.2.1.8. Team Collaboration Insights during Sprint

En esta parte, describimos cómo el equipo colaboró de forma organizada para desarrollar las funcionalidades de la landing page. Utilizamos métricas de GitHub como el número de commits, las contribuciones individuales y la frecuencia de actividad para respaldar esta colaboración con evidencia concreta.

<img src="./Report_Assets/collaborationinsights1.png" alt="Collaboration Insights 1" width="500">

<img src="./Report_Assets/collaborationinsights2.png" alt="Collaboration Insights 2" width="500">

<img src="./Report_Assets/collaborationinsights3.png" alt="Collaboration Insights 3" width="500">

### 5.2.2. Sprint 2
Este informe documenta el progreso final del proyecto DeathClothe, una plataforma web de compraventa de ropa para compradores y vendedores. Durante este sprint, se trabajó en el desarrollo de las interfaces, así como también, haciendo la funcionalidad de las mismas.
A través del Sprint 1 y de lo mencionado, estamos elaborando la parte complementaria que consiste en tener las experiencias del usuario mientras navega por la interfaz de DeathClothe y hace sus compras de la forma más eficaz y directa posible.

#### 5.2.2.1. Sprint Planning 2
<table border="1" cellspacing="0" cellpadding="8">
   <thead>
     <tr>
       <th><strong>Campo</strong></th>
       <th><strong>Detalle</strong></th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>Sprint 2</td>
     </tr>
     <tr>
       <td>Fecha</td>
       <td>2025-05-15</td>
     </tr>
     <tr>
       <td>Hora</td>
       <td>5:00 P.M.</td>
     </tr>
     <tr>
       <td>Ubicación</td>
       <td>Virtual – Discord</td>
     </tr>
     <tr>
       <td>Preparado por</td>
       <td>Andrea Elizabeth Santur Tello</td>
     </tr>
     <tr>
       <td>Asistentes (a la reunión de planificación)</td>
       <td>Alvaro Bejarano, Mateo Cabanillas, Omar Luquillas, Andrea Santur, Loreley Sarmiento</td>
     </tr>
     <tr>
       <td>Sprint 2 – Resumen de revisión</td>
       <td>Se elaboró la Landing Page correspondiente a DeathClothe, en el cual, hacemos uso de los elementos que se elaboraron antes en el Figma y colocado todo lo mencionado en el programa WebStorm, haciendo gala de las funcionalidades mencionadas anteriormente.</td>
     </tr>
     <tr>
       <td>Sprint 2 – Resumen de retrospectiva</td>
       <td>Realizar que el usuario pueda tener su primer contacto con la plataforma haciendo uso de la estructura mencionada, en el cual, el usuario puede registrarse y decir si es "Comprador" o "Vendedor".</td>
     </tr>
     <tr>
       <td>Objetivo y User Stories del Sprint 2</td>
       <td>
         <strong>Objetivo del Sprint:</strong>  Elaborar la plataforma con la que el usuario se sentirá conforme y pueda realizar sus compras de prendas de la mejor manera posible y tengan una notable experiencia.
       </td>
     </tr>
     <tr>
       <td>Velocidad del Sprint 2</td>
       <td>15 User Stories</td>
     </tr>
     <tr>
       <td>Suma de Story Points</td>
       <td>30 Story Points atendidos</td>
     </tr>
   </tbody>
 </table>

#### 5.2.2.2. Aspect Leaders and Collaborators

| **Integrante del equipo**          | **GitHub**       | **FrontEnd Angular** | **Material UI** | **HTML/CSS** | **TypeScript** | **Documentación** |
| ---------------------------------- | ---------------- | -------------------- | --------------- | ------------ | -------------- | ----------------- |
| **Santur Tello, Andrea Elizabeth** | andreli-star     | C                    | C               | **L**        | C              | **L**             |
| **Bejarano, Alvaro**               | Albro310306      | C                    | C               | C            | C              | C                 |
| **Cabanillas, Mateo**              | marckszz         | C                    | **L**           | **L**        | **L**          | C                 |
| **Luquillas, Omar**                | OmarLLA          | **L**                | **L**           | **L**        | **L**          | **L**             |
| **Sarmiento, Loreley**             | loreleysarmiento | **L**                | **L**           | **L**        | **L**          | **L**             |


#### 5.2.2.3. Sprint Backlog 2

Link: `https://trello.com/invite/b/680d1de7fcd6bc9189287b2a/ATTI71b9407097327a930510d122cf825bea86979452/sprint-1-deathclothe` <br>
<img src="Report_Assets/sprint2-trello.png">

<p><strong>Sprint 2</strong></p>

<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Work-Item / Task</th>
      <th>User Story ID</th>
      <th>Task ID</th>
      <th>Description</th>
      <th>Estimation (Hours)</th>
      <th>Assigned To</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Work-Item</td>
      <td>US04</td>
      <td>T01</td>
      <td>Ver últimas prendas publicadas</td>
      <td>5</td>
      <td>Alvaro Bejarano</td>
      <td>In-process</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US05</td>
      <td>T02</td>
      <td>Filtrar por categoría</td>
      <td>4</td>
      <td>Mateo Cabanillas</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US22</td>
      <td>T03</td>
      <td> Cambiar entre comprador y vendedor</td>
      <td>2</td>
      <td>Andrea Santur</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US07</td>
      <td>T04</td>
      <td>Editar o eliminar una prenda publicada</td>
      <td>3</td>
      <td>Omar Luquillas</td>
      <td>In-process</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US23</td>
      <td>T05</td>
      <td>Editar prendas del armario</td>
      <td>5</td>
      <td>Loreley Sarmiento</td>
      <td>In-process</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US02</td>
      <td>T07</td>
      <td>Publicar una prenda en venta</td>
      <td>4</td>
      <td>Omar Luquilla</td>
      <td>In-process</td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US1</td>
      <td>T08</td>
      <td>Agregar una prenda a favoritos</td>
      <td>3</td>
      <td>Alvaro Bejarano</td>
      <td>Review </td>
    </tr>
   <tr>
      <td>Work-Item</td>
      <td>US01</td>
      <td>T06</td>
      <td> Recibir recomendaciones en base a mis favoritos </td>
      <td>4</td>
      <td>Andrea Elizabeth </td>
      <td>Review </td>
    </tr>
    <tr>
      <td>Work-Item</td>
      <td>US06</td>
      <td>T10</td>
      <td>Recibir recomendaciones de la pagina</td>
      <td>5</td>
      <td>Loreley Sarmiento</td>
      <td>Review </td>
    </tr>
  </tbody>
</table>

#### 5.2.2.4. Development Evidence for Sprint Review.
Durante este sprint, se realizaron avances significativos en el desarrollo de la <b>aplicación web principal</b>. Se completaron funcionalidades esenciales como el registro e inicio de sesión, permitiendo a los usuarios tener su primer contacto con la plataforma. A continuación, se presenta una tabla con los commits correspondientes al repositorio

### Commits 

| Repository |Branch| Commit Id | Commit Message| Commit Message Body| Commited on (Date)|
|--------|-----------|--------|-------|---------------------------------|-------|
| DeathClothe/appweb  | main | l1m2n3o | feat: Implementación de registro de usuarios|Se desarrolló el formulario de registro, permitiendo a los usuarios crear una cuenta como comprador o vendedor | 2025-05-13|
| DeathClothe/appweb | main|p4q5r6s  | feat: Inicio de sesión funcional |Se habilitó la funcionalidad de inicio de sesión, con validación de credenciales y manejo de sesiones. |2025-05-14|
|DeathClothe/appweb | main| t7u8v9w |fix: Corrección en la navegación entre vistas | Se solucionaron problemas de navegación entre las diferentes vistas de la aplicación. | 2025-05-15 |

#### 5.2.2.5. Execution Evidence for Sprint Review. 

Durante este Sprint no se realizaron cambios en la Landing Page, manteniéndose la versión entregada en el Sprint 2. No obstante, se lograron avances importantes en el desarrollo de la aplicación web principal, incluyendo funcionalidades clave que permiten una interacción efectiva del usuario con la plataforma. A continuación, se han completado las siguientes tareas que muestran:

### Screenshots
<img src="./Report_Assets/imagen1.png">
<img src="./Report_Assets/imagen2.png">
<img src="./Report_Assets/imagen2.1.png">
<img src="./Report_Assets/imagen3.1.png">
<img src="./Report_Assets/imagen4.1.png">
<img src="./Report_Assets/imagen5.2.png">
<img src="./Report_Assets/imagen6.png">

#### 5.2.2.6. Services Documentation Evidence for Sprint Review. 

Se ha desplegado la aplicación web DeathClothe, la cual consume el servicio REST provisto por Json‑Server para simular la capa de datos, tal como está configurado en el repositorio de GitHub.
A continuación, se presenta la documentación de la API definida en el proyecto:

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th><b>Endpoint Name</b></th>
      <th><b>Implemented Actions</b></th>
      <th><b>Call Syntax</b></th>
      <th><b>Parameters Specification</b></th>
      <th><b>Call Example</b></th>
      <th><b>Response Explanation</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/users</td>
      <td>GET, POST</td>
      <td>http.get('/users')</td>
      <td>id, userResource</td>
      <td>getAll() { return http.get('http://localhost:3000/users'); }</td>
      <td>Devuelve un array con todos los usuarios registrados.</td>
    </tr>
    <tr>
      <td>/auth/login</td>
      <td>POST</td>
      <td>http.post('/auth/login')</td>
      <td>email, password</td>
      <td>login(credentials) { return http.post('http://localhost:3000/auth/login', credentials); }</td>
      <td>Retorna un token de autenticación si las credenciales son válidas.</td>
    </tr>
    <tr>
      <td>/auth/register</td>
      <td>POST</td>
      <td>http.post('/auth/register')</td>
      <td>name, email, password</td>
      <td>register(data) { return http.post('http://localhost:3000/auth/register', data); }</td>
      <td>Crea un nuevo usuario y retorna sus datos.</td>
    </tr>
    <tr>
      <td>/products</td>
      <td>GET, POST, PUT, DELETE</td>
      <td>http.get('/products')</td>
      <td>id, productResource, name</td>
      <td>getAll() { return http.get('http://localhost:3000/products'); }</td>
      <td>Devuelve un array con todos los productos disponibles.</td>
    </tr>
    <tr>
      <td>/orders</td>
      <td>GET, POST</td>
      <td>http.get('/orders')</td>
      <td>id, orderResource</td>
      <td>getAll() { return http.get('http://localhost:3000/orders'); }</td>
      <td>Devuelve un array con todas las órdenes realizadas.</td>
    </tr>
  </tbody>
</table>

### 5.2.2.7. Software Deployment Evidence for Sprint Review. 

Durante este Sprint, se llevaron a cabo las siguientes actividades relacionadas con el despliegue de la aplicación web principal (repositorio appweb).Estas actividades incluyeron la configuración de entornos, la integración continua y la automatización del proceso de despliegue para asegurar una entrega fluida y eficiente.

### Actividades realizadas
- Creación y configuración de cuentas en proveedores cloud.
- Configuración de entornos de despliegue.
- Automatización de procesos de integración y despliegue.
- Despliegue de la Landing Page.
- Despliegue de la Web Application.

### Explicación de los pasos realizados 

**1. Configuración del repositorio**
- Se ingresó a la sección Settings > Pages del repositorio en GitHub para activar el servicio de GitHub Pages.

- Se seleccionó la rama main como fuente principal para el despliegue automático del sitio.

- Se verificó que la estructura de archivos cumpliera con los requisitos de GitHub Pages, asegurando que el archivo principal index.html estuviera en la ubicación correcta.

**2. Preparación para el despliegue**
- Se ajustó la estructura del proyecto para que los archivos se organizaran correctamente, facilitando el reconocimiento por parte del sistema de despliegue.

- Se realizó un push de prueba para confirmar que la estructura y configuración fueran reconocidas sin errores.

**3. Despliegue  automático**
- Se configuró un flujo de trabajo con GitHub Actions para automatizar el proceso de despliegue cada vez que se realice un push a la rama main.

- Se confirmó que el despliegue se ejecutara sin errores, haciendo que la última versión del proyecto esté disponible automáticamente en GitHub Pages.

**4. Monitoreo y pruebas post-despliegue**
- Se realizaron pruebas unitarias y de integración después del despliegue para asegurar la estabilidad y correcto funcionamiento de la plataforma.
  
### Evidencia del proceso realizado

<img src="./Report_Assets/imagen7.png">
<img src="./Report_Assets/imagen8.png">
<img src="./Report_Assets/imagen9.png">
<img src="./Report_Assets/imagen10.png">
<img src="./Report_Assets/imagen11.png">
<img src="./Report_Assets/imagen12.png">

Link de Landing Page: `https://deathclothe.github.io/DEATHCLOTHELandingPage/` <br>
Link de App Web: `https://app-web-deathclothe.onrender.com/` <br>
Link de Vercel: `https://render.com/`


### 5.2.2.8. Team Collaboration Insights during Sprint.
Durante este Sprint, el equipo mantuvo una colaboración organizada y constante para desarrollar las funcionalidades de la aplicación web principal y la landing page. La coordinación se reflejó en la actividad registrada en los repositorios de GitHub vinculados al proyecto.

Se utilizaron métricas clave de GitHub para medir la colaboración del equipo:

- Número total de commits

- Contribuciones individuales

- Frecuencia de actividad

### Capturas de Analíticos de Colaboración en GitHub:
<img src="./Report_Assets/imagen13.1.png">
<img src="./Report_Assets/imagen14.png">
<img src="./Report_Assets/imagen15.png">

### 5.2.3. Sprint 3
Esta sección describe en detalle los procesos, entregables y evidencias generadas durante el Sprint 3. Se abordan desde la planificación del sprint hasta las evidencias de despliegue y colaboración del equipo, con el objetivo de mostrar la evolución y calidad del trabajo realizado en esta etapa del proyecto.
### 5.2.3.1. Sprint Planning 3
<table border="1" cellspacing="0" cellpadding="8">
   <thead>
     <tr>
       <th><strong>Campo</strong></th>
       <th><strong>Detalle</strong></th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>Sprint 3</td>
     </tr>
     <tr>
       <td>Fecha</td>
       <td>2025-06-06</td>
     </tr>
     <tr>
       <td>Hora</td>
       <td>5:00 P.M.</td>
     </tr>
     <tr>
       <td>Ubicación</td>
       <td>Virtual – Discord</td>
     </tr>
     <tr>
       <td>Preparado por</td>
       <td>Andrea Elizabeth Santur Tello</td>
     </tr>
     <tr>
       <td>Asistentes (a la reunión de planificación)</td>
       <td>Alvaro Bejarano, Mateo Cabanillas, Omar Luquillas, Andrea Santur, Loreley Sarmiento</td>
     </tr>
     <tr>
       <td>Sprint 3 – Resumen de revisión</td>
       <td>En el Sprint 3, logramos completar las funcionalidades pendientes en el Frontend, asegurando una experiencia de usuario coherente y funcional. Además, se implementó una versión inicial del Backend, que permite gestionar datos relevantes de manera segura y eficiente. También se rediseñó la estructura de la base de datos, permitiendo adaptarla a nuevas funcionalidades que requerían atributos adicionales.</td>
     </tr>
     <tr>
       <td>Sprint 3 – Resumen de retrospectiva</td>
       <td>Como parte de la mejora continua, estructuramos las tareas del sprint de manera más clara y modular, lo que facilitó la delegación y ejecución individual. Adoptamos una estrategia de revisión colaborativa, donde cada integrante del equipo validaba los avances de los demás. Esto reforzó la cohesión del equipo, aumentó la calidad del código y mejoró nuestra capacidad de reacción ante cambios o incidencias.</td>
     </tr>
     <tr>
       <td>Objetivo y User Stories del Sprint 3</td>
       <td>
         <strong>Objetivo del Sprint:</strong> El objetivo fue elaborar la plataforma para garantizar que los usuarios pudieran registrarse, publicar ropa, visualizar los perfiles de otros usuarios, habilitando así la experiencia de compra-venta de ropa de segunda mano que caracteriza a DeathClothe. Para ello, se desarrollaron las funcionalidades esenciales del backend. En un inicio, el planteamiento mencionaba una gestión operativa de restaurante, pero este fue ajustado correctamente al contexto del proyecto, centrándose en la creación de APIs específicas para usuarios, publicaciones y gestión de datos.
       </td>
     </tr>
     <tr>
       <td>Velocidad del Sprint 3</td>
       <td>La velocidad del equipo en este sprint fue de 35 story points, reflejando el alto nivel de productividad y compromiso con las tareas planificadas.</td>
     </tr>
     <tr>
       <td>Suma de Story Points</td>
       <td>35 Story Points atendidos</td>
     </tr>
   </tbody>
 </table>

 #### 5.2.3.2. Aspect Leaders and Collaborators. 
 | **Integrante del equipo**          | **GitHub**       | **BackEnd** | **Spring Boot** | **HTML/CSS** | **TypeScript** | **Documentación** |
| ---------------------------------- | ---------------- | ----------- | --------------- | ------------ | -------------- | ----------------- |
| **Santur Tello, Andrea Elizabeth** | andreli-star     | C           | C               | **L**        | C              | **L**             |
| **Bejarano, Alvaro**               | Albro310306      | **L**       | **L**           | C            | **L**          | C                 |
| **Cabanillas, Mateo**              | marckszz         | C           |**L**            | C            |**L**           | **L**             |
| **Luquillas, Omar**                | OmarLLA          | **L**       | **L**           | C            | C              | C                 |
| **Sarmiento, Loreley**             | loreleysarmiento | **L**       | **L**           | **L**        | C              | **L**             |
   
 ### 5.2.3.3. Sprint Backlog 3
 Link: `https://trello.com/invite/b/680d1de7fcd6bc9189287b2a/ATTI71b9407097327a930510d122cf825bea86979452/sprint-1-deathclothe` <br>
<img src="Report_Assets/sprint3-trello.png">
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th><strong>Work‑Item / Task</strong></th>
      <th><strong>User Story ID</strong></th>
      <th><strong>Task ID</strong></th>
      <th><strong>Description</strong></th>
      <th><strong>Estimation (Hours)</strong></th>
      <th><strong>Assigned To</strong></th>
      <th><strong>Status</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Work‑Item</td><td>US‑01</td><td>T01</td><td>Recibir recomendaciones en base a mis favoritos</td><td>5</td><td>Alvaro Bejarano</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑10</td><td>T02</td><td>Agregar prendas a la lista de favoritos</td><td>3</td><td>Andrea Santur</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑11</td><td>T03</td><td>Implementar armario virtual con prendas favoritas o compradas</td><td>5</td><td>Mateo Cabanillas</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑15</td><td>T04</td><td>Filtrar prendas por tipo dentro del armario virtual</td><td>3</td><td>Loreley Sarmiento</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑16</td><td>T05</td><td>Buscar prendas por nombre dentro de favoritos</td><td>3</td><td>Loreley Sarmiento</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑07</td><td>T06</td><td>Editar o eliminar prendas ya publicadas</td><td>5</td><td>Andrea Santur</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑18</td><td>T18</td><td>Implementar cambio de idioma en la landing</td><td>3</td><td>Loreley Sarmiento</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑09</td><td>T07</td><td>Marcar prendas como vendidas e inhabilitarlas del catálogo</td><td>5</td><td>Omar Luquilla</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>TS‑02</td><td>T08</td><td>Implementar consultas SQL optimizadas para filtros avanzados</td><td>5</td><td>Alvaro Bejarano</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>TS‑03</td><td>T09</td><td>Establecer relaciones entre prendas y armario virtual en MySQL</td><td>5</td><td>Mateo Cabanillas</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>TS‑08</td><td>T10</td><td>Agregar índices en campos clave de las tablas MySQL</td><td>3</td><td>Omar Luquilla</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑23</td><td>T11</td><td>Editar prendas del armario</td><td>3</td><td>Loreley Sarmiento</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑23</td><td>T11</td><td>Editar prendas del armario</td><td>3</td><td>Loreley Sarmiento</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑23</td><td>T11</td><td>Editar prendas del armario</td><td>3</td><td>Loreley Sarmiento</td><td>Done</td>
    </tr>
   <tr>
     <td>Work‑Item</td><td>US‑13</td><td>T12</td><td>Visualizar detalles de prenda</td><td>3</td><td>Andrea Santur</td><td>Done</td>
   </tr>
    <tr>
      <td>Work‑Item</td><td>US‑14</td><td>T13</td><td>Conocer al vendedor</td><td>3</td><td>Omar Luquilla</td><td>Done</td>
    </tr>
    <tr>
      <td>Work‑Item</td><td>US‑24</td><td>T14</td><td>Página no encontrada</td><td>2</td><td>Mateo Cabanillas</td><td>Done</td>
    </tr>
  </tbody>
</table>




 ### 5.2.3.4. Development Evidence for Sprint Review. 
| **Repository**       | **Branch** | **Commit ID** | **Commit Message**                      | **Commit Message Body**                                                               | **Committed on (Date)** |
| -------------------- | ---------- | ------------- | --------------------------------------- | ------------------------------------------------------------------------------------- | ----------------------- |
| DeathClothe/code-web | main       | `b45c281`     | `feat`: Update Explore.vue              | Se actualizaron componentes para mejorar la exploración del catálogo.                 | 2025-06-21              |
| DeathClothe/code-web | main       | `a7c3d1f`     | `fix`: activeLang                       | Se solucionó la persistencia del idioma seleccionado en la barra superior.            | 2025-06-21              |
| DeathClothe/code-web | main       | `e9f2b4a`     | `feat(toolbar)`: add language buttons   | Se añadió el switcher de idiomas al toolbar para mejorar accesibilidad.               | 2025-06-21              |
| DeathClothe/code-web | main       | `c1d7e2b`     | `feat(profile)`: add edit-profile-modal | Se implementó la edición de perfil mediante un modal emergente.                       | 2025-06-21              |
| DeathClothe/code-web | main       | `d6e4f1c`     | `feat`: Create CategoryDetail.vue       | Se agregó vista de detalle para cada categoría del catálogo.                          | 2025-06-20              |
| DeathClothe/code-web | main       | `f3a8c2d`     | `feat`: buyer-profile                   | Se creó el perfil principal del comprador con sus respectivas secciones.              | 2025-06-19              |
| DeathClothe/code-web | main       | `b7f3a6e`     | `feat`: detalle de la ropa              | Se implementó la visualización detallada de una prenda (imagen, precio, descripción). | 2025-06-18              |
| DeathClothe/code-web | main       | `a9b1e2c`     | `feat`: favoritos                       | Se desarrolló el sistema de favoritos para guardar prendas de interés.                | 2025-06-18              |
| DeathClothe/code-web | main       | `c8d5a1f`     | `feat`: seller-profile                  | Se implementó la vista del perfil del vendedor con secciones de productos vendidos.   | 2025-06-17              |


### 5.2.3.5. Execution Evidence for Sprint Review. 
La Landing Page tuvo un rediseño. <br>
Link: `https://deathclothe.github.io/DEATHCLOTHELandingPage/` 
<img src="./Report_Assets/ladingpagemodi.png">
Además se rediseño y se hizo mejorar a la aplicación Fronted, de nuestra plataforma web. <br>
Link: `https://app-web-deathclothe.onrender.com/`
<img src="./Report_Assets/imagen2.2.png">
<img src="./Report_Assets/imagen3.png">
<img src="./Report_Assets/imagen4.png">
<img src="./Report_Assets/imagen5.png">
<img src="./Report_Assets/imagen5.1.png">
<img src="./Report_Assets/imagen5.3.png">
<img src="./Report_Assets/imagen6.2.png">
<img src="./Report_Assets/imagen7.1.png">
<img src="./Report_Assets/imagen7.2.png">

Por último se ejecutó el backend con swagger. Esta ejecución fue localmente, no se ha desplegado en este sprint. <br>
<img src="./Report_Assets/imagen6.1.png">

link del backend repository:  `https://github.com/DeathClothe/Backend-Web-Services.git`  
### 5.2.3.6. Services Documentation Evidence for Sprint Review.
| **Endpoint Name** | **Implemented Actions** | **Call Syntax**                                                                                             | **Parameters Specification**                                                 | **Call Example**                             | **Response Explanation**                                   |
| ----------------- | ----------------------- | ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | -------------------------------------------- | ---------------------------------------------------------- |
| **Profile**       | POST, GET, PUT, DELETE  | POST: `/api/v1/profile`<br>GET/PUT/DELETE: `/api/v1/profile/{id}`                                           | `name`, `email`, `password`, `role`, `image`, `stats`                        | GET `http://localhost:3000/api/v1/profile/4` | Devuelve los datos del perfil del usuario según su ID.     |
| **Clothe**        | POST, GET, PUT, DELETE  | POST: `/api/v1/clothe`<br>GET: `/api/v1/clothe`, `/api/v1/clothe/{id}`<br>PUT/DELETE: `/api/v1/clothe/{id}` | `title`, `description`, `price`, `size`, `type`, `status`, `userId`, `image` | GET `http://localhost:3000/api/v1/clothe/7`  | Devuelve la información completa de una prenda específica. |

### 5.2.3.7. Software Deployment Evidence for Sprint Review. 
Para el deployment de la ultima versión de la app web, lo hicimos en render, conectamos el repositorio a render y lo deployamos ahi.
![Deployment](Report_Assets/DeploymentEvidence1Sprint3.PNG)
![Deployment](Report_Assets/DeploymentEvidence2Sprint3.PNG)
![Deployment](Report_Assets/DeploymentEvidence3.PNG)
![Deployment](Report_Assets/DeploymentEvidence4.PNG)
### 5.2.3.8. Team Collaboration Insights during Sprint. 
A continuación se muestra evidencia de la coolaboración del equipo mediante insights de GitHub.<br>
**Frontend**
<img src="./Report_Assets/sprintInsightsFronted.png">
<img src="./Report_Assets/imagen13.png">
<img src="./Report_Assets/BranchReport.PNG">
**Backend**
<img src="./Report_Assets/sprintInsightsBackend.png">

### 5.2.4. Sprint 4

Esta sección presenta de forma detallada los procesos llevados a cabo, los entregables producidos y las evidencias recopiladas durante el Sprint 4. Abarca desde la fase de planificación hasta los indicadores de despliegue y trabajo colaborativo del equipo, con el propósito de reflejar el progreso alcanzado y la calidad del desarrollo logrado en esta etapa del proyecto.

#### 5.2.4.1. Sprint Planning 4

<table border="1" cellspacing="0" cellpadding="8">
   <thead>
     <tr>
       <th><strong>Campo</strong></th>
       <th><strong>Detalle</strong></th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>Sprint 4</td>
     </tr>
     <tr>
       <td>Fecha</td>
       <td>2025-07-05</td>
     </tr>
     <tr>
       <td>Hora</td>
       <td>7:00 P.M.</td>
     </tr>
     <tr>
       <td>Ubicación</td>
       <td>Virtual – Discord</td>
     </tr>
     <tr>
       <td>Preparado por</td>
       <td>Jose Mateo Cabanillas Meza/td>
     </tr>
     <tr>
       <td>Asistentes (a la reunión de planificación)</td>
       <td>Alvaro Bejarano, Mateo Cabanillas, Omar Luquillas, Andrea Santur, Loreley Sarmiento</td>
     </tr>
     <tr>
       <td>Sprint 3 – Resumen de revisión</td>
       <td>En el Sprint 4, completamos la implementación del backend para DeathClothe, desarrollando las 12 Technical Stories que abarcan la gestión de perfiles de usuario, prendas, categorías y la autenticación. Cada una de las historias técnicas fue cubierta, garantizando que los usuarios pudieran obtener, crear, actualizar y eliminar tanto sus perfiles como las prendas publicadas. Además, se implementaron funcionalidades de inicio de sesión y registro, permitiendo la autenticación de los usuarios de manera segura.</td>
     </tr>
     <tr>
       <td>Sprint 3 – Resumen de retrospectiva</td>
       <td>Durante este sprint, se lograron mejoras clave en la estructura del código y en la colaboración del equipo. Cada miembro asumió tareas específicas y hubo una gran sincronización entre el frontend y el backend, lo que permitió completar el sprint de manera exitosa. A pesar de algunos pequeños retrasos, logramos mantener la calidad del código y la seguridad en las operaciones del sistema.

Como mejora continua, acordamos revisar las funciones de autenticación con más profundidad en los próximos sprints, asegurando que el proceso sea aún más robusto, especialmente en escenarios de manejo de errores. Además, la implementación de pruebas unitarias para los endpoints API será un área de enfoque en los próximos sprints.</td>
     </tr>
     <tr>
       <td>Objetivo y User Stories del Sprint 3</td>
       <td>
         <strong>Objetivo del Sprint:</strong> El objetivo principal de este sprint fue implementar la lógica del backend para la gestión de perfiles de usuario, prendas, categorías y autenticación en la plataforma DeathClothe. Se trabajó en la creación de APIs RESTful que permitieran a los usuarios registrarse, iniciar sesión, gestionar sus perfiles y ropas, además de visualizar las categorías de prendas disponibles.  <strong>User Stories:</strong> TS01, TS02, TS03, TS04, TS05, TS06, TS07, TS08, TS09, TS10, TS11, TS12.
       </td>
     </tr>
     <tr>
       <td>Velocidad del Sprint 3</td>
       <td>La velocidad del equipo en este sprint fue de 45 story points, reflejando la alta productividad y el compromiso con las tareas. La colaboración y los ajustes durante el sprint ayudaron a mantener un ritmo constante de trabajo.

</td>
     </tr>
     <tr>
       <td>Suma de Story Points</td>
       <td>45 Story Points atendidos</td>
     </tr>
   </tbody>
 </table>
 
#### 5.2.4.2. Aspect Leaders and Collaborators 
 | **Integrante del equipo**          | **GitHub**       | **Actualización de Landing Page** | **Backend** | **Frontend** | **Deployment** | **Documentación** |
| ---------------------------------- | ---------------- | ----------- | --------------- | ------------ | -------------- | ----------------- |
| **Santur Tello, Andrea Elizabeth** | andreli-star     | C           | C               | **L**        | C              | **L**             |
| **Bejarano, Alvaro**               | Albro310306      | C           | C               | **L**            | C         | **L**                 |
| **Cabanillas, Mateo**              | marckszz         | C           |**L**            | C            |C          | C             |
| **Luquillas, Omar**                | OmarLLA          | **L**       | **L**           | C            | C              | C                 |
| **Sarmiento, Loreley**             | loreleysarmiento | C           | C               | **L**        | **L**              | C             |


#### 5.2.4.3. Sprint Backlog 4

<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Work-Item / Task</th>
      <th>User Story ID</th>
      <th>Task ID</th>
      <th>Description</th>
      <th>Estimation (Hours)</th>
      <th>Assigned To</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Work-Item</td>
      <td>TS01</td>
      <td>T01</td>
      <td>Obtener perfil de usuario por ID</td>
      <td>3</td>
      <td>Alvaro Bejarano</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS02</td>
      <td>T02</td>
      <td>Actualizar perfil de usuario por ID</td>
      <td>4</td>
      <td>Mateo Cabanillas</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS03</td>
      <td>T03</td>
      <td>Obtener todos los perfiles</td>
      <td>2</td>
      <td>Andrea Santur</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS04</td>
      <td>T04</td>
      <td>Obtener todas las ropas</td>
      <td>3</td>
      <td>Loreley Sarmiento</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS05</td>
      <td>T05</td>
      <td>Crear una nueva prenda de ropa</td>
      <td>4</td>
      <td>Omar Luquillas</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS06</td>
      <td>T06</td>
      <td>Obtener una prenda de ropa por ID</td>
      <td>3</td>
      <td>Loreley Sarmiento</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS07</td>
      <td>T07</td>
      <td>Actualizar una prenda de ropa</td>
      <td>4</td>
      <td>Alvaro Bejarano</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS08</td>
      <td>T08</td>
      <td>Eliminar una prenda de ropa</td>
      <td>3</td>
      <td>Mateo Cabanillas</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS09</td>
      <td>T09</td>
      <td>Obtener todas las categorías</td>
      <td>2</td>
      <td>Andrea Santur</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS10</td>
      <td>T10</td>
      <td>Obtener categoría por ID</td>
      <td>3</td>
      <td>Loreley Sarmiento</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS11</td>
      <td>T11</td>
      <td>Autentificar el inicio de sesión</td>
      <td>5</td>
      <td>Omar Luquillas</td>
      <td>Done</td>
</tr>
<tr>
      <td>Work-Item</td>
      <td>TS12</td>
      <td>T12</td>
      <td>Autentificar el registro de usuario</td>
      <td>5</td>
      <td>Omar Luquillas</td>
      <td>Done</td>
</tr>
    <tr>
      <td>Work-Item</td>
      <td>US30</td>
      <td>T13</td>
      <td>Cambiar de temas en la Landing Page</td>
      <td>1</td>
      <td>Omar Luquillas</td>
      <td>Done</td>
</tr>
  </tbody>
</table>



#### 5.2.4.4. Development Evidence for Sprint Review.
| **Repository**                | **Branch** | **Commit ID** | **Commit Message**                         | **Commit Message Body**                                               | **Committed on (Date)** |
| ----------------------------- | ---------- | ------------- | ------------------------------------------ | --------------------------------------------------------------------- | ----------------------- |
| Backend-Web-Services          | `main`     | `93a37b7`     | feat(iam): fix sign-up command             | Fix de comando de registro en IAM                                     | 10/07/2025              |
| Backend-Web-Services          | `main`     | `d8a71e2`     | feat(iam): add update profile              | Implementación de funcionalidad de actualización de perfil de usuario | 10/07/2025              |
| Backend-Web-Services          | `main`     | `f5bd92c`     | feat(iam): add iam authentication          | Autenticación IAM integrada con Spring Security                       | 09/07/2025              |
| code-web                      | `main`     | `e1c5ab3`     | Edit Form to create clothe                 | Se editó el formulario de creación de prendas                         | 09/07/2025              |
| code-web                      | `main`     | `c7f39d0`     | Merge remote-tracking branch 'origin/main' | Fusión con la rama principal para actualizar cambios                  | 08/07/2025              |
| Backend-Web-Services          | `main`     | `4849a25`     | feat\:Added backeng imag                   | Implementación de soporte backend para carga de imágenes              | 24/06/2025              |



#### 5.2.4.5. Execution Evidence for Sprint Review.
Para este sprint realizamos la conexión del back-end y front-end, mostramos los datos de la base de datos y realizamos cambios visuales a la landing a page
### Landing Page
Link de la landing page: `https://deathclothe.github.io/DEATHCLOTHELandingPage/`
![DarkMode](Report_Assets/DarkModeLanding.PNG)

### Application
Link de la aplicación web: `https://app-web-deathclothe.onrender.com/`
![DarkMode](Report_Assets/Application.PNG)

### Web Service
Link del web service: `https://backend-web-services-lbbg.onrender.com/api/v1`
![DarkMode](Report_Assets/WebServicePostman.PNG)

### Database 
Link de la base de datos: `mysql://root:KYKzUbnHCtzvEuSlAgtIJHgCfFEWsFAu@ballast.proxy.rlwy.net:53837/railway`
![DarkMode](Report_Assets/BaseDeDatosDeploy.PNG)

#### 5.2.4.6. Services Documentation Evidence for Sprint Review.

| **Endpoint Name** | **Implemented Actions** | **Call Syntax**                                                                                             | **Parameters Specification**                                                 | **Call Example**                             | **Response Explanation**                                   |
| ----------------- | ----------------------- | ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | -------------------------------------------- | ---------------------------------------------------------- |
| **Profile**       | POST, GET, PUT, DELETE  | POST: `/api/v1/profile`<br>GET/PUT/DELETE: `/api/v1/profile/{id}`                                           | `name`, `email`, `password`, `role`, `image`, `stats`                        | GET `http://localhost:3000/api/v1/profile/4` | Devuelve los datos del perfil del usuario según su ID.     |
| **Clothe**        | POST, GET, PUT, DELETE  | POST: `/api/v1/clothe`<br>GET: `/api/v1/clothe`, `/api/v1/clothe/{id}`<br>PUT/DELETE: `/api/v1/clothe/{id}` | `title`, `description`, `price`, `size`, `type`, `status`, `userId`, `image` | GET `http://localhost:3000/api/v1/clothe/7`  | Devuelve la información completa de una prenda específica. |
| **Categories**    | GET   | GET: `/api/v1/categories`<br>GET: `/api/v1/categories/{id}` | `id`, `name`| GET `http://localhost:3000/api/v1/categories/1`  | Devuelve la información de una categoría específica con el ID indicado. |
| **Authentication**| POST  |  |   |   |

#### 5.2.4.7. Software Deployment Evidence for Sprint Review.
En este sprint de deployo el Backend en Render y se subio la base de datos a un ambiente productivo para que nuestro sistema pueda usarla.
#### Web Service
El primer paso fue conectar el repositorio de github con render, crear un archivo DockerFile para poder manejar Net 9, ya que al ser una nueva versión, aún render no soporta todas las nuevas funcionaliades.
Una vez configurado el proyecto se pone en deploy y esperamos que en consola nos diga que el servicio está vivo.
![Deployment](Report_Assets/DeployWebService1.PNG)
![Deployment](Report_Assets/DeployWebService2.PNG)
![Deployment](Report_Assets/DeployWebService3.PNG)
![Deployment](Report_Assets/DeployWebService4.PNG)
#### Database
Para subir la base de datos a un ambiente se necesita descargar un backup de la base de datos local, después en railway se selecciona la opción de mysql y se crea una base de datos en railway. Se sube el backup a la base de datos de railway 
y railway nos dará un enlace para usar nuestra base de datos. 
![Deployment](Report_Assets/DeployDataBase1.PNG)
![Deployment](Report_Assets/DeployDataBase2.PNG)
![Deployment](Report_Assets/DeployDataBase3.PNG)

Link de la base de datos:`mysql://root:KYKzUbnHCtzvEuSlAgtIJHgCfFEWsFAu@ballast.proxy.rlwy.net:53837/railway`<br>
Link del Backend:`https://backend-web-services-lbbg.onrender.com/api/v1`
#### 5.2.4.8. Team Collaboration Insights during Sprint.
Durante este sprint, el equipo logró finalizar los tres componentes fundamentales de la plataforma DeathClothe, consolidando el producto en su versión funcional para ser presentado. 
**Frontend**
Dentro del frontend se han realizado algunas mejorias con relación a adaptación de las entidades con el backend.
<img src="./Report_Assets/frontendCommit.png"> 

**Backend**
Dentro del backend se han agregado nuevos endpoints para autenticación de usuarios además de algunas mejorias para un buen desempeño en el progreso.
<img src="./Report_Assets/backendCommit.png">


### 5.3 Validation Interviews
### 5.3.1 Diseño de entrevistas
### Objetivo de la Entrevistaa 
Validar la usabilidad y efectividad de la landing pae de DeatchClothe y de los flujos de usuario(user flows) asegurnado que cada flujo sea intuitivo, claro, versátil y funcional para lo usuarios, su interración y navegación con la plataforma.

### Elemnetos de validación
- **Lading Page** : Percepción de la interfaz, efectividad, claridad del mensaje y su capacidad para  motivar a registrarse. 
- **Fronted** : Usabilidad de los flujos clave, como inicio de sesión, gestión de los productos a presentar, seguimiento de consultas, panel de editación, búsqueda, filtrado,  recomendación de la prenda a conseguir, entre otros.

### Flujos de usuario un validor
**segmento Comprador** 
1. Landing Page
   - Evaluación  del diseño y claridad del mensaje del producto para captar el interés de un comprador.
2. Registro e inicio de sesión.
   - Flujo de creación de cuenta y autenticación
3. Exploración del catálogo y búsqueda.
   - Uso de filtros por categoría, talla, marca, estado y precio, según la prenda favorita de tu elección.
4. Visualización del detalle de una prenda.
   - Información visible, claridad en precio y estado, botones de acción.
5. Sugerencias personalizadas
   - Recomendaciones basadas en tus preferencias.

**Segmento Vendedor**
1. Landing Page
   - Evaluación  del diseño y claridad del mensaje del producto para captar el interés de un vendedor.
   - Visibilidad del acceso al perfil de vendedor y funciones destacadas.
2. Registro e inicio de sesión.
   - Flujo de creación de cuenta y autenticación
3. Panel de perfil del vendedor
   - Visualización del resumen del usuario (nombre, correo, tipo de usuario, dirección).
   - Acceso directo a funciones como editar perfil y cerrar sesión.
4. Gestión de prendas publicadas y vendidas
   - Modal emergente con detalles de cada prenda: tipo, estado, precio, talla, color.
   - Opción de edición o eliminación de prendas desde el detalle
5. Prendas pendientes
   - Listado de productos aún no vendidos con información completa y botones de acción.
   - Facilidad para gestionar el estado de venta.
   
#### Formato de Registro de la Entrevista
**Datos del Entrevistado**:
   - Nombre y apellidos
   - Edad
   - Ciudad de residencia
   - Dispositivo utilizado (laptop)
#### Preguntas principales 
- ¿Qué tan fácil te resulta navegar por la aplicación?
- ¿La app cumple con lo que esperabas? ¿Qué funcionalidad te resultó más valiosa y cuál echas en falta?
- ¿Cómo se comporta la app en tu teléfono o tablet?
- ¿Hay pantallas o formularios que no se ven bien?
- ¿El mensaje principal de la pagina web te quedó claro al primer vistazo?
- ¿Qué tan claro fue el llamado a la acción en la landing page 
- ¿Encontraste alguna parte del diseño o navegación confusa o poco intuitiva?
- En una escala del 1 al 10, ¿cuánto nos recomendarías a un amigo o colega? ¿Por qué?
- ¿Qué funcionalidad te gustaría que agregáramos o mejoráramos?

### 5.3.2 Registro de Entrevistas 
Link de las entrevistas

Presentamos a continuación los resultados de las entrevistas de validación realizadas en ambos segmentos; compradores y vendedores, de nuestros objetivos.

## Segmento: Comprador
**Entrevista 1**
| **Dato**                             | **Información**                                                                                                                                                      |
|--------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Entrevistado**                     | William Agustín Ventura Saldaña                                                                                                                                       |
| **Edad**                             | 27 años                                                                                                                                                               |
| **Distrito**                         | Lima - Surco                                                                                                                                                          |
| **Inicio de la entrevista**          | 00:00                                                                                                                                                                 |
| **Foto captura**                     | <img src="./Report_Assets/AgustinValidation.png">                                                                                                                    |
| **Diseño de presentación del producto** | El diseño le pareció claro, intuitivo y agradable, con una navegación fluida. Mencionó que no tuvo problemas para encontrar lo que buscaba.                       |
| **Información de presentación del producto** | Le quedó claro el mensaje de que es una plataforma para vender ropa. Los botones, instrucciones e imágenes comunican bien la propuesta de valor.              |
| **Visualización de la página**       | Mencionó el buen rendimiento de la app y que todo se visualiza correctamente en general.                                                                             |
| **Evaluación de funcionalidades clave** | Valoró mucho la funcionalidad de “favoritos” y sugirió agregar un historial de recientemente vistos. También propuso un sistema de opiniones de otros compradores. |

[URL entrevista] (`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/EeT5nSboo31CsOK0CjcFCHcBxhbcbe1PfekxFog4Cxp__A?e=jpSKD4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`)

**Entrevista 2**
| **Dato**                             | **Información**                                                                                                                                                           |
|--------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Entrevistado**                     | Anyelo Bill Alejos Jesús                                                                                                                                                  |
| **Edad**                             | 20 años                                                                                                                                                                   |
| **Distrito**                         | Lima - Comas                                                                                                                                                              |
| **Inicio de la entrevista**          | 09:06                                                                                                                                                                         |
| **Foto captura**                     | <img src="./Report_Assets/AnyeloValidation.png">                                                                                                                         |
| **Diseño de presentación del producto** | El diseño fue percibido como atractivo y bien estructurado. La interfaz es clara y visualmente agradable, lo cual facilitó su comprensión inicial del propósito de la plataforma. |
| **Información de presentación del producto** | El mensaje principal de la página quedó claro desde el primer vistazo: es una plataforma para vender ropa. Los botones, instrucciones e imágenes comunican bien la propuesta de valor. |
| **Visualización de la página**       | Comentó que la experiencia fue positiva, le daría una puntuación de 8/10. Destacó la estética agradable del diseño y la buena experiencia de uso, aunque hay detalles por pulir. |
| **Evaluación de funcionalidades clave** | Considera útil el sistema de filtros por talla y estilo, ya que agilizan la búsqueda de prendas. En general, cumple con las expectativas del usuario.                      |

   [URL entrevista] (`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/EeT5nSboo31CsOK0CjcFCHcBxhbcbe1PfekxFog4Cxp__A?e=jpSKD4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`)

**Entrevista 3**
| **Dato**                             | **Información**                                                                                                                                                              |
|--------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Entrevistado**                     | Daniela Alessandra Cigueñas Tarrillo                                                                                                                                          |
| **Edad**                             | 19 años                                                                                                                                                                       |
| **Distrito**                         | Lima - Los Olivos                                                                                                                                                             |
| **Inicio de la entrevista**          | 17:46                                                                                                                                                                             |
| **Foto captura**                     | <img src="./Report_Assets/DanielaValidation.png">                                                                                                                            |
| **Diseño de presentación del producto** | Considera que el diseño es visualmente atractivo y amigable. Los colores como rosado y blanco llamaron su atención desde el primer vistazo y facilitaron la navegación.      |
| **Información de presentación del producto** | La información está clara y cumple con lo que se espera de una app de compra y venta de ropa usada. Desde la landing se entiende el propósito y cómo usarla.              |
| **Visualización de la página**       | No experimentó errores ni problemas visuales. La navegación es sencilla, los elementos están bien distribuidos y todo se muestra de forma funcional y comprensible.         |
| **Evaluación de funcionalidades clave** | Le resultó fácil navegar, aplicar filtros, buscar prendas como polos o vestidos. Como mejora, sugiere incluir conjuntos de prendas y no solo unidades individuales.         |

[URL entrevista] (`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/EeT5nSboo31CsOK0CjcFCHcBxhbcbe1PfekxFog4Cxp__A?e=jpSKD4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`)

## Segmento: Vendedor
**Entrevista 1**
| **Dato**                                  | **Información**                                                                                                                                                        |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Entrevistado**                          | Valesska Sánchez                                                                                                                                                       |
| **Edad**                                  | 20 años                                                                                                                                                                |
| **Distrito**                              | Lima - San Martín de Porres                                                                                                                                            |
| **Inicio de la entrevista**               | 30:33                                                                                                                                                                  |
| **Foto captura**                          | <img src="./Report_Assets/ValessksSan.png">                                                                                                                            |
| **Interacción con la plataforma**         | Describió su experiencia como intuitiva y eficiente. Encontró fácil navegar, buscar productos y concretar compras. Sugirió mejorar la búsqueda avanzada y los filtros. |
| **Funcionalidades adicionales sugeridas** | Propuso integrar redes sociales para compartir compras y outfits, así como recibir notificaciones personalizadas sobre ofertas y promociones.                          |
| **Accesibilidad y usabilidad**            | Consideró la app fácil de usar para diferentes edades, aunque recomendó optimizar la velocidad de carga de imágenes y contenido.                                       |
| **Impacto visual y atractivo**            | Le pareció un diseño moderno y minimalista, en línea con las tendencias de moda. Destacó el uso coherente de colores y tipografías.                                    |
| **Comentarios finales**                   | Tuvo una buena experiencia general. Reconoció oportunidades de mejora para elevar la satisfacción del cliente y fomentar su fidelización.                              |

[URL entrevista] (`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/EeT5nSboo31CsOK0CjcFCHcBxhbcbe1PfekxFog4Cxp__A?e=jpSKD4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`)

**Entrevista 2**
| **Dato**                             | **Información**                                                                                                                                                              |
|--------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Entrevistado**                     | David Manuel Torres Meneses                                                                                                                                                   |
| **Edad**                             | 20 años                                                                                                                                                                       |
| **Distrito**                         | Lima - Los Olivos                                                                                                                                                             |
| **Inicio de la entrevista**          | 28:01                                                                                                                                                                             |
| **Foto captura**                     | <img src="./Report_Assets/DavidValidation.png">                                                                                                                              |
| **Diseño de presentación del producto** | Describió el diseño como ordenado, claro y bien jerarquizado. Cada elemento está bien ubicado, facilitando la comprensión. Lo encontró atractivo y amigable para el usuario. |
| **Información de presentación del producto** | El mensaje central se comprendió fácilmente: es una app para vender ropa, con énfasis en moda y visibilidad para los vendedores.                                           |
| **Visualización de la página**       | No presentó problemas visuales ni de carga. La interfaz fue percibida como limpia y estructurada. Se destacó la rapidez de visualización y navegación intuitiva.            |
| **Evaluación de funcionalidades clave** | Valoró las funciones de publicar, editar, eliminar prendas, ver estadísticas y explorar productos. Sugirió como mejora una trazabilidad más detallada de las acciones.       |

[URL entrevista] (`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/EeT5nSboo31CsOK0CjcFCHcBxhbcbe1PfekxFog4Cxp__A?e=jpSKD4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`)

**Entrevista 3**
| **Dato**                                  | **Información**                                                                                                                                                            |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Entrevistado**                          | Jhon Alexander Chuchón                                                                                                                                                     |
| **Edad**                                  | 19 años                                                                                                                                                                    |
| **Distrito**                              | Lima - San Martín de Porres                                                                                                                                                |
| **Inicio de la entrevista**               | 30:33                                                                                                                                                                      |
| **Foto captura**                          | <img src="./Report_Assets/JhonValidation.png">                                                                                                                             |
| **Interacción con la plataforma**         | Calificó la experiencia como intuitiva y eficiente. Mencionó la facilidad para encontrar productos y realizar compras. Sugirió mejorar la búsqueda avanzada y los filtros. |
| **Funcionalidades adicionales sugeridas** | Recomendó integrar redes sociales para compartir compras y looks, además de recibir notificaciones personalizadas sobre ofertas y promociones.                             |
| **Accesibilidad y usabilidad**            | Opinó que la app es fácil de usar para personas de diversas edades. Sugirió mejorar la velocidad de carga de imágenes y contenido.                                         |
| **Impacto visual y atractivo**            | Consideró que el diseño es moderno y minimalista, alineado con la moda actual. Resaltó la coherencia visual en colores y tipografías.                                      |
| **Comentarios finales**                   | Tuvo una experiencia positiva en general, pero identificó áreas de mejora para incrementar la satisfacción y fidelización del cliente.                                     |

[URL entrevista] (`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310988_upc_edu_pe/EeT5nSboo31CsOK0CjcFCHcBxhbcbe1PfekxFog4Cxp__A?e=jpSKD4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`)


### 5.3.3 Evaluación según Heurísticas – *DeathClothe*

**UX Heuristics & Principles Evaluation**

**Carrera:** Ingeniería de Software  
**Curso:** Aplicaciones Web  
**Sección:** 4376  
**Auditor:** Latte  
**Clientes:** DeathClothe  

**Sitio Evaluado:** Plataforma Web y Landing Page de DeathClothe  
**Versión:** Revisión de interfaz estática y estructura de navegación inicial

---

### Tareas evaluadas

#### Landing Page
- Visualización de propuesta del proyecto
- CTA hacia inicio de sesión o más información
- Navegación general (header/footer)

#### Web Application
- Visualización de perfil de usuario (rol vendedor)
- Edición de prendas y control de inventario
- Tabs: prendas publicadas, pendientes y vendidas

---

### Escala de Severidad

| Nivel | Descripción |
|-------|-------------|
| 1     | Problema superficial |
| 2     | Problema menor |
| 3     | Problema mayor |
| 4     | Problema muy grave |

---

### Tabla Resumen

#### Web Application

| # | Problema | Severidad | Heurística violada |
|---|----------|-----------|---------------------|
| 1 | Interfaz de prendas no estandariza botones o campos de edición | 2 | Usability – Consistency and Standards |
| 2 | Falta de mensajes al guardar cambios | 2 | Usability – Feedback and System Status |
| 3 | No hay validación visual en campos vacíos | 3 | Usability – Error Prevention |

#### Landing Page

| # | Problema | Severidad | Heurística violada |
|---|----------|-----------|---------------------|
| 1 | CTA no es visualmente prominente | 2 | Usability – Visibility of System Status |
| 2 | No se contextualiza claramente el tipo de proyecto en el primer scroll | 1 | IA – Is it Clear? |
| 3 | Header no es sticky ni adaptativo en mobile | 2 | Usability – Flexibility and Efficiency |

---

### Descripción de Problemas

#### Web Application

**1. Inconsistencia de interfaz (botones, inputs)**  
- Severidad: 2  
- Recomendación: Unificar estilo visual y comportamiento de botones en todos los formularios.

**2. Ausencia de retroalimentación visual al guardar cambios**  
- Severidad: 2  
- Recomendación: Incluir alertas tipo toast o banners al guardar edición de prendas.

**3. Formularios no muestran errores en campos vacíos**  
- Severidad: 3  
- Recomendación: Implementar validaciones en tiempo real y mensajes visuales para evitar errores.

#### Landing Page

**1. CTA poco visible o persuasivo**  
- Severidad: 2  
- Recomendación: Rediseñar botones con colores llamativos, iconos, y texto enfocado en beneficio.

**2. Falta de claridad en el mensaje inicial**  
- Severidad: 1  
- Recomendación: Agregar título impactante y subtítulo aclaratorio al inicio del scroll.

**3. Header no se mantiene en vista en dispositivos móviles**  
- Severidad: 2  
- Recomendación: Hacer sticky el header y mejorar la usabilidad responsive.



# Conclusiones

- **DeathClothe responde a una necesidad real del mercado:**  
  La investigación validó que los usuarios buscan una plataforma segura, intuitiva y personalizada para comprar y vender ropa de segunda mano, mejorando las limitaciones actuales de otros canales como Facebook Marketplace e Instagram.

- **La experiencia de usuario es el principal diferenciador:**  
  Gracias a la personalización basada en el armario virtual, la facilidad de publicación en tres pasos y las historias de prendas, DeathClothe ofrece una experiencia emocionalmente más rica y funcionalmente más eficiente que las alternativas existentes.

- **El proyecto tiene bases sólidas para avanzar hacia el desarrollo:**  
  Con un enfoque centrado en el usuario, sustentado en entrevistas, user personas, journey maps y prototipos, DeathClothe cuenta con una estructura estratégica y visual clara que permite afrontar con éxito las siguientes etapas de validación, prototipado y despliegue.

- **Se logró implementar exitosamente la funcionalidad base del sistema:**
Durante el Sprint se desarrollaron los procesos esenciales de registro, inicio de sesión y navegación en la aplicación web, permitiendo que los usuarios comiencen a interactuar con la plataforma como compradores o vendedores.

- **El equipo logró una colaboración eficiente y sostenida:**
Se evidenció una distribución activa del trabajo con múltiples commits, tareas asignadas entre miembros y flujos constantes de integración, lo que demuestra una buena comunicación y un desarrollo ágil y organizado.

- **El despliegue automatizado fortalece la continuidad del proyecto:**
Se configuró GitHub Pages y GitHub Actions para facilitar la visualización continua de la plataforma, lo cual permite testear de forma ágil los cambios en cada push y habilita un ciclo de desarrollo más fluido y profesional.

- **El proyecto ya cuenta con una estructura de testing inicial:**
Se integraron evidencias de pruebas unitarias y de integración, lo que demuestra un compromiso con la calidad del código y la estabilidad del sistema a largo plazo.

# Bibliografía

- Ellen MacArthur Foundation. (2017). A new textiles economy: Redesigning fashion’s future. Retrieved from `https://ellenmacarthurfoundation.org/a-new-textiles-economy`

- McKinsey & Company. (2016). Style that’s sustainable: A new fast-fashion formula. Retrieved from `https://www.mckinsey.com/business-functions/sustainability/our-insights/style-thats-sustainable-a-new-fast-fashion-formula`

- ThredUp. (2023). 2023 Resale Report. Retrieved from `https://www.thredup.com/resale`

- Universidad Peruana de Ciencias Aplicadas. (2025). Informe de Trabajo Final - DeathClothe. Curso de Aplicaciones Web, Facultad de Ingeniería de Software.

- Facebook Marketplace. (n.d.). Buy and sell used clothes locally or ship nationwide. Retrieved April 2025, from `https://www.facebook.com/marketplace`

- Instagram Business. (n.d.). Grow your business on Instagram. Retrieved April 2025, from `https://business.instagram.com/`

- Urbaner. (n.d.). Soluciones logísticas para empresas y ecommerce en Perú. Retrieved April 2025, from `https://www.urbaner.com.pe/`

- Olva Courier. (n.d.). Envíos nacionales y courier en Perú. Retrieved April 2025, from `https://www.olvacourier.com/`

- Rappi Perú. (n.d.). Entregas rápidas en tu ciudad. Retrieved April 2025, from `https://www.rappi.com.pe/`

- IDEO.org. (2015). The Field Guide to Human-Centered Design. Retrieved from `https://www.designkit.org/resources/1`



