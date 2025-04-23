<div align="center">

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
 U20<br>
 U20<br>
Bejarano Martínez Alvaro Leandro U202311640<br>
Cabanillas Meza Jose Mateo U202311458<br>
Luquillas Asto Omar U20211G641<br>
Sarmiento Medina Loreley U202310005<br>

# *Abril de 2025*
</div>

## Registro de Versiones del Informe

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TB1</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TP</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TB2</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TF</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>


## Contents

- [Student Outcome](#student-outcome)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [Capítulo I: Introducción](#capítulo-i-introducción)
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
  - [1.3. Segmentos objetivos](#13-segmentos-objetivos)

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

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
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
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
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
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
ReWear es una startup enfocada en transformar la manera en que las personas consumen, comparten y viven la moda. Creemos que cada prenda tiene una historia y que el estilo no debería depender de la producción masiva ni del consumo desechable. En ReWear, conectamos a usuarios apasionados por la autenticidad, la sostenibilidad y la expresión personal, a través de un mercado digital de ropa de segunda mano que combina tecnología, diseño y comunidad.
Nuestro primer producto, DeathClothe, es una plataforma web que permite a los usuarios subir, comprar, vender y descubrir prendas únicas, mientras reciben recomendaciones personalizadas basadas en su armario virtual. Más que una app, es una experiencia viva, donde la moda circula, evoluciona y encuentra nuevas almas.

Misión: Nuestra misión es ofrecer una nueva oportunidad a la ropa que ya no es deseada, brindando una segunda vida a las prendas y conectando a personas con gustos auténticos. A través de nuestra plataforma, buscamos que cada usuario pueda encontrar piezas únicas que se alineen con su estilo personal, sin tener que recurrir a la moda rápida. Fomentamos un consumo responsable, permitiendo que cada compra y venta de ropa sea un paso hacia un estilo más consciente, auténtico y sostenible.

Visión: Nos visualizamos como una empresa líder en el renacimiento de la moda circular, construyendo una comunidad global que redefine el estilo desde la autenticidad, el cuidado del planeta y la tecnología. Aspiramos a convertirnos en el referente para quienes ven en su ropa una extensión de su identidad, y que eligen transformar el mundo desde su armario.

### 1.1.2. Perfiles de integrantes del equipo
<table border="1" cellspacing="0" cellpadding="10">
  <tr>
    <th>Integrantes</th>
    <th>Perfil de Integrante</th>
  </tr>
  <tr>
    <td><img src="" alt="Integrante 1" width="100"/></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="" alt="Integrante 2" width="100"/></td>
    <td>Jose Mateo Cabanillas Meza - Ingeniería de Software-u202311458
Mi nombre es Mateo Cabanillas y en la actualidad estoy cursando el quinto ciclo de la carrera de ingeniería de software con una mente creativa y una actitud colaborativa. Mi amor por la programación y la resolución de problemas me impulsa a explorar nuevas soluciones y aportar ideas frescas a los proyectos. Como compañero de equipo, soy amable, atento y siempre estoy dispuesto a ayudar. Creo firmemente en la importancia de la comunicación efectiva y la colaboración para lograr resultados excepcionales.</td>
  </tr>
  <tr>
    <td><img src="" alt="Integrante 3" width="100"/></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="" alt="Integrante 4" width="100"/></td>
    <td></td>
  </tr>
  <tr>
    <td><img src="Report_Assets/integrante2.png" alt="Integrante 5" width="100"/></td>
    <td>Soy Loreley Sarmiento Medina con codigo de estudainte U202310005 y estudio la carrera de Ingeniería de Software y me especializo en aportar soluciones tecnológicas integrales dentro de equipos multidisciplinarios. Cuento con sólidos conocimientos en el modelado de wireframes y mockups utilizando Figma, lo que me permite contribuir eficazmente en la etapa de diseño de interfaces centradas en el usuario. Además, tengo experiencia en el modelado de bases de datos, facilitando la organización y estructura lógica de la información. Poseo conocimientos intermedios en HTML y CSS, lo cual me permite colaborar en el desarrollo de interfaces web funcionales y visualmente atractivas. También tengo una base sólida en lenguajes de programación, lo que me permite comprender e implementar soluciones tanto en el frontend como en el backend, aportando al desarrollo integral del producto</td>
  </tr>
 
</table>

## 1.2. Solution Profile
DeathClothe es una plataforma web que transforma la manera de consumir moda al permitir a los usuarios comprar, vender y descubrir ropa de segunda mano con recomendaciones personalizadas según su armario virtual. A través de una experiencia intuitiva, conecta a personas que buscan autenticidad, estilo y sostenibilidad, facilitando la circulación de prendas únicas y dándoles una nueva vida. Con un enfoque en la moda circular, la personalización y la comunidad, DeathClothe no solo es un mercado digital, sino un espacio donde el estilo evoluciona con propósito.
### 1.2.1. Antecedentes y problemática

**What**

DeathClothe es una plataforma digital centrada en la moda circular, que permite a los usuarios subir, comprar, vender y descubrir ropa de segunda mano. A través de un armario virtual y un sistema de recomendaciones inteligentes, la aplicación crea una experiencia personalizada para cada usuario, ayudándolo a encontrar prendas que se alineen con su estilo e identidad. Más que una simple tienda online, DeathClothe funciona como una comunidad donde cada prenda tiene una historia y cada intercambio fomenta un consumo más consciente, auténtico y sostenible.

**When**

DeathClothe se usa en cualquier momento en el que una persona quiera renovar su estilo, encontrar una prenda única, darle una segunda vida a ropa que ya no usa, o simplemente explorar tendencias sin recurrir a la moda rápida. Es útil tanto para quienes buscan una alternativa económica y ecológica para vestir, como para quienes desean liberar espacio en su armario sin desperdiciar. También se convierte en una herramienta ideal para quienes disfrutan curando su propio estilo a partir de piezas con historia.

**Where**

La plataforma está diseñada para ser utilizada desde cualquier lugar con acceso a internet, ya sea desde el hogar, durante trayectos diarios, en una cafetería o mientras se compara ropa en una tienda física. Su diseño web responsivo y amigable permite una experiencia fluida tanto en computadoras como en dispositivos móviles. Esto la convierte en una opción accesible y cómoda para todos aquellos que quieren vivir la moda de una manera más conectada, auténtica y sustentable.

**Who**

Usuarios eco‑conscientes y fashionistas que demandan alternativas sostenibles al fast fashion, buscando piezas únicas y auténticas sin contribuir al modelo de consumo desechable.
Personas con prendas en desuso que desean monetizar o dar nueva vida a su vestuario; en 2023, el 52 % de los consumidores adquirió ropa de segunda mano, destinando casi la mitad de su presupuesto de vestuario a este segmento.
Generación Z y Millennials digitales, atraídos por la combinación de sostenibilidad y estilo: un 64 % compra second‑hand para ahorrar dinero y un 36 % por conciencia medioambiental.

**Why**

El modelo de fast fashion genera 92 millones de toneladas de residuos textiles al año, el equivalente a un camión de basura lleno de ropa vertido en vertederos cada segundo, con un fuerte impacto ambiental.
En Estados Unidos, se descartan más de 34 000 millones de libras de textiles usados anualmente (más de 100 libras per cápita), evidenciando la incapacidad de los sistemas tradicionales para gestionar el ciclo de vida de la ropa.
Solo el 20 % de los textiles descartados se recolecta para reciclaje o reutilización; el resto acaba en vertederos o incinerado, lo que subraya la urgencia de modelos de negocio circulares que fomenten la reutilización.

**How**

Los usuarios interactúan con la plataforma DeathClothe mediante navegadores web y dispositivos móviles, explorando un catálogo curado que ofrece filtros inteligentes, alertas de nuevos artículos y recomendaciones basadas en su armario virtual.
Prefieren descubrir nuevas prendas a través de redes sociales e influencers, ya que las campañas digitales en Instagram y TikTok potencian la visibilidad y el alcance de mercados de segunda mano.
La adopción de algoritmos de personalización y técnicas de curation algorithm permite que cada usuario encuentre piezas acordes a su estilo individual, solucionando uno de los desafíos de los marketplaces más genéricos.
Sin embargo, la amplia variedad de inventario en recommerce crea obstáculos de descubrimiento; por ello, es crucial implementar estrategias de curación y filtrado avanzado para mejorar la experiencia de usuario y fomentar la retención.

**How Much**

La magnitud del problema es crítica. Según la Ellen MacArthur Foundation (2017), cada año se desechan 92 millones de toneladas de ropa, de las cuales menos del 1% se recicla. Esta situación se agrava porque, como señala McKinsey (2016), los consumidores compran un 60% más de prendas que hace dos décadas pero las conservan la mitad de tiempo. Aunque el 62% de los jóvenes prefiere opciones sostenibles (ThredUp, 2023), el mercado de segunda mano sigue siendo subutilizado, demostrando la urgente necesidad de soluciones innovadoras como ReWear para cerrar esta brecha entre intención y acción en el consumo responsable.


### 1.2.2. Lean UX Process

El Lean UX process es un enfoque ágil para diseño de productos que prioriza la experimentación rápida y el feedback real sobre documentación extensa. Se basa en crear prototipos simples, validar hipótesis con usuarios e iterar constantemente, optimizando tiempo y recursos.

#### 1.2.2.1. Lean UX Problem Statements

Hoy en día, muchas personas quieren comprar ropa de segunda mano para ser más sostenibles, pero se encuentran con varios problemas. Por un lado, los compradores tienen dificultades para encontrar prendas que realmente les gusten y que estén en buen estado. Las plataformas actuales no siempre muestran opciones atractivas o no permiten buscar fácilmente por estilo o talla, lo que hace que muchos prefieran seguir comprando ropa nueva por comodidad.

Por otro lado, quienes quieren vender su ropa usada se topan con procesos complicados o poco transparentes. Subir fotos, escribir descripciones y manejar envíos resulta tedioso, y a veces no vale la pena por los precios bajos que ofrecen. Esto hace que mucha ropa en buen estado termine guardada en el armario o en la basura.

En resumen, existe un círculo vicioso, como hay poca oferta atractiva de ropa usada, menos gente compra; y como cuesta vender, menos gente participa. DeathClothe busca solucionar esto haciendo más fácil tanto comprar como vender ropa de segunda mano, para que realmente sea una alternativa práctica a la ropa nueva y así reducir el impacto ambiental de la moda.

#### 1.2.2.2. Lean UX Assumptions

**Interés en la segunda mano**

Los usuarios están dispuestos a comprar y vender ropa de segunda mano si la plataforma les ofrece prendas únicas, de buena calidad y fácil acceso. Valoran la originalidad, el buen estado de las piezas y la posibilidad de consumir moda de forma más consciente y sostenible.

**Facilidad de uso en la carga de inventario**

Si el proceso para subir prendas es simple y rápido los usuarios se sentirán más motivados a ofrecer más artículos en la plataforma. Al reducir las barreras técnicas y el tiempo requerido para publicar, se facilita la participación activa de los vendedores, quienes podrán gestionar su inventario de manera más práctica y constante. Esta facilidad fomenta una mayor rotación de productos, enriqueciendo la variedad del catálogo disponible y mejorando la experiencia general de compra para toda la comunidad.

**Sensibilidad al precio y sostenibilidad**

Quienes compran ropa de segunda mano suelen priorizar precios accesibles, sin embargo, también valoran profundamente el trasfondo de cada prenda. Están dispuestos a pagar un poco más cuando sienten que están adquiriendo una pieza con historia, carácter y autenticidad comprobada. Esta disposición se fortalece si la plataforma brinda confianza a través de mecanismos que verifiquen el origen, el estado y la originalidad del artículo. En ese contexto, la prenda deja de ser solo un producto y se convierte en una experiencia única, algo que conecta emocionalmente con el comprador y justifica una inversión ligeramente mayor.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Carga de Prendas**

Creemos que si simplificamos el proceso de publicación de prendas a solo tres pasos clave (tomar una foto, completar los atributos esenciales y definir el precio) los usuarios se sentirán más motivados a listar sus artículos. Esta experiencia intuitiva y rápida facilitará que al menos el 80 % de los vendedores completen con éxito el proceso de alta, lo cual mediremos a través de la tasa de finalización de publicaciones dentro de la plataforma.

**Confianza mediante Valoraciones**

Creemos que si destacamos calificaciones de vendedores y compradores en cada perfil, la tasa de conversión de vista de objeto a compra mejorará en un 12 %, medido por unidades vendidas respecto a productos vistos.

**Historias de Prendas**

Creemos que si incorporamos un espacio donde se muestre la historia de cada prenda (incluyendo detalles como su origen, anécdotas o el estilo de su anterior dueño) los usuarios sentirán una mayor conexión emocional con los artículos. Esta narrativa añadida no solo reforzará el valor percibido de cada pieza, sino que también incentivará la curiosidad y el deseo de exploración. Esperamos que esta función aumente la tasa de clics en “Me interesa” en un 15 %, medido a través del ratio de interacciones por prenda visualizada.

#### 1.2.2.4. Lean Ux Canvas
![LeanUxCanvas](Report_Assets/LeanUxCanvas.PNG)

## 1.3. Segmentos Objetivos

Compradores:Personas entre 18 y 35 años interesadas en la moda, pero que buscan alternativas más económicas, sostenibles y auténticas a la moda rápida. Este segmento valora la originalidad, el consumo responsable y la posibilidad de acceder a prendas únicas a través de una experiencia fácil, visualmente atractiva y confiable. Su motivación principal es ahorrar dinero sin sacrificar estilo, descubrir ropa con personalidad y contribuir al cuidado del planeta.

Vendedores:Personas desde los 18 hasta los 50 años o más que desean vender ropa en buen estado que ya no usan, ya sea para generar ingresos extra, liberar espacio en su armario o apoyar un modelo de consumo más circular. Este grupo incluye tanto usuarios casuales como pequeños emprendedores o diseñadores independientes, motivados por la posibilidad de conectar con compradores que valoren sus prendas y por contribuir activamente a una moda más consciente y sostenible. 

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores

**Marketplace de Facebook:** Es la opción más usada para comprar y vender ropa usada en Perú. Es gratuito, tiene gran alcance, pero no está especializado en moda y carece de filtros adecuados.

**Instagram:** Muchas tiendas independientes venden ropa vintage o de segunda mano a través de Instagram, con una estética cuidada y fuerte conexión con su audiencia.

### 2.1.1. Análisis competitivo

<img src="Report_Assets/competidores 1era parte.png" alt="Nombre" width="500"> 
</a>

<img src="Report_Assets/competidores 2da parte nueva .png" alt="Nombre" width="500"> 
</a>

### 2.1.2. Estrategias y tácticas frente a competidores

**Diferenciación con Narrativa y Personalización**

Estrategia: Ofrecer historias de cada prenda (origen, uso, estilo previo) para añadir valor emocional y autenticidad.

Táctica: Implementar fichas de producto enriquecidas con inputs del vendedor (anécdotas, looks anteriores, inspiración), y recomendaciones personalizadas usando el “armario virtual”.

**Tecnología para la experiencia del usuario**

Estrategia: Convertir la app en una experiencia interactiva y visual que no sea solo un marketplace, sino una comunidad viva.

Táctica: Diseño UX moderno con navegación tipo red social, sistema de seguimiento entre usuarios, outfits sugeridos y gamificación.

**Confianza y autenticidad como pilares**

Estrategia: Construir una comunidad basada en la confianza, destacando calidad y procedencia de las prendas.

Táctica: Sistema de calificaciones, verificación de usuarios/vendedores, etiquetas de “pieza destacada”, y filtros visuales para el estado de las prendas.

**Facilidad de uso para vendedores**

Estrategia: Incentivar la participación constante de usuarios que suben ropa.

Táctica: Subida de prendas en 3 pasos, tips de fotografía, herramientas de edición automática y precios sugeridos según categoría y estado.

**Alianzas y comunidad local**

Estrategia: Posicionarse como la plataforma "de la gente para la gente" en Perú.

Táctica: Colaboraciones con creadores de contenido de moda sostenible, tiendas vintage locales, ferias presenciales y campañas con influencers que promuevan la moda circular.

**Integración logística**

Estrategia: Superar al Facebook Marketplace con soluciones reales de entrega.

Táctica: Alianzas con apps de delivery locales (como Urbaner, Olva o Rappi), ofreciendo opciones rápidas y seguras para envíos entre usuarios.


## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas
<p> La elaboración de las entrevista se basó en los objetivos del proyecto y en los perfiles específicos de compradores y vendedores. Se formularon preguntas personalizadas para entender hábitos, motivaciones y necesidades. En compradores, se exploraron sus preferencias por alternativas sostenibles, incluyendo a los compradores impulsivos para identificar qué los motiva. En vendedores, se abordaron razones para vender y expectativas hacia una plataforma que promueva el consumo responsable. </p>

#### 1. Preguntas para Comprador
##### 1.1 Información Demográfica
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

##### 1.2 Atributos Personales y Gustos
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
##### 2.2 Información Demográfica

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

##### 2.2 Atributos Personales y Gustos
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
      <td>08:25</td>
    </tr>
  </tbody>
</table>


**Detalles de la entrevista:** <br>
<img src="./Report_Assets/DanielaEntrevista1.png" alt="Entrevista 1" width="500">
</a><br>
[URL de la entrevista](.....)

**Resumen de la entrevista:** <br>
<p>Daniela Zarrillo, estudiante de 19 años de Lima, mencionó que utiliza con frecuencia internet para realizar compras. Hace pocos días adquirió ropa de segunda mano, motivada por el precio accesible y los estilos únicos. Comentó que organizaría su armario virtual por estilo, color, temporada y precio, y señaló como frustración principal la falta de precisión en tallas y descripciones. Además, resaltó la importancia de contar con fotos desde varios ángulos, descripciones claras y reseñas de otros usuarios. Considera esencial agilizar el proceso de pago con métodos como Yape, le interesan las recomendaciones basadas en su armario virtual y valoraría una función para vender automáticamente prendas no usadas. Finalmente, destacó que su plataforma ideal incluiría un sistema de tallas preciso, una experiencia personalizada y sugerencias adaptadas a su estilo.</p>

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
      <td>08:25</td>
    </tr>
    <tr>
      <td>Duración de la entrevista</td>
      <td>07:27</td>
    </tr>
  </tbody>
</table>

**Detalles de la entrevista:** <br>
<img src="./Report_Assets/AgustinEntrevista2.png" alt="Entrevista 2" width="500">
</a><br>
[URL de la entrevista](.....)

**Resumen de la entrevista:** <br>
<p> Agustín Venturos Aldaña, de 27 años y residente en Lima, compró ropa de segunda mano hace un mes tras buscar tiendas vintage en Instagram, revisar comentarios y tallas grandes, y completar el pago con Yape. Valora el estilo único y la sostenibilidad, por lo que organizaría su armario virtual por estilo, temporada, color y talla, con filtros de combinaciones personalizadas. Sin embargo, se frustra con descripciones imprecisas y fotos poco claras, de modo que confiaría en DeathClothe si incluyera verificación de calidad, medidas exactas y reseñas de expertos. Además, considera clave un proceso de pago ágil con cupones y alertas de oferta, recomendaciones tanto similares como contrastantes, clasificación automática de prendas para liberar espacio y un informe del impacto ambiental de sus compras. </p>

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
      <td>Anyelo Bill Alejos Jesus</td>
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
      <td>08:25</td>
    </tr>
    <tr>
      <td>Duración de la entrevista</td>
      <td>06:54</td>
    </tr>
  </tbody>
</table>


**Detalles de la entrevista:** <br>
<img src="./Report_Assets/AnyeloEntrevista3.png" alt="Entrevista 3" width="500">
</a><br>
[URL de la entrevista](.....)

**Resumen de la entrevista:** <br>
<p> Anyelo , estudiante de Ingeniería de Software de 20 años, buscó ropa de segunda mano atraído por modelos agotados y precios bajos.Organizaría su armario virtual por temporada y color, aunque lamenta la falta de fiabilidad de algunos vendedores y la llegada de prendas robadas o en mal estado, por lo cual considera esencial contar con descripciones claras, tallas exactas y fotos detalladas. Asimismo, verificaría la autenticidad comparando modelos en línea y valora un proceso de pago seguro con opciones de descuento. Asi mismo, le interesaría recibir recomendaciones basadas en su armario virtual y automatizar la venta o donación de prendas no usadas. Finalmente, identifica como funciones imprescindibles un sistema de tallas preciso, métodos de pago confiables y una organización clara de su armario virtual. </p>

#### Segmento :Vendedor
# Entrevista #4 – Datos del Entrevistado
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
      <td>Usualmente lo uso muy rara vez, solo en emergencias y cuando veo algo realmente interesante, como prendas de buena calidad o diseños únicos</td>
    </tr>
    <tr>
      <td>Inicio de la entrevista</td>
      <td>00:00</td>
    </tr>
    <tr>
      <td>Duración de la entrevista</td>
      <td>14:50</td>
    </tr>
  </tbody>
</table>


**Detalles de la entrevista:** <br>
<img src="./Report_Assets/DavidEntrevista4.png" alt="Entrevista 4" width="500">
</a><br>

**Resumen de la entrevista:** <br>
<p> Daniel Manuel Torres Méndez, de 20 años y residente en Lima, elige qué artículos poner en venta basándose en marca, estilo, color y talla, y los prepara con fotografías (incluso vistas 360°), descripciones detalladas y precios ajustados según la rareza o urgencia. Prefiere publicar desde la computadora porque es más estable que el celular, ya que en el móvil la carga de imágenes y la publicación suelen fallar; sin embargo, sueña con un armario virtual que agrupe prendas por demanda, temporada y exclusividad. Además, valoraría sugerencias automáticas de precios basadas en ventas similares, un chat integrado para resolver dudas rápidamente y múltiples opciones de envío, tanto nacionales como internacionales, y asegura que le motivaría ver que sus ofertas satisfacen las necesidades de los compradores. </p>

### 2.2.3. Análisis de entrevistas


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

**Compradores:**

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

