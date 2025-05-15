# <center>COURSE PROJECT</center>

<div style="text-align: center;">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img alt="UPC" src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"/><br>
    <strong>Ingeniería de Software - 2025-1</strong><br>
    <strong>Arquitecturas de Software Emergentes - SW81</strong><br>
    <strong>Profesor: Royer Edelwer Rojas Malasquez</strong><br>
    <br>INFORME DE TRABAJO FINAL - TB1
</div>

<div style="text-align: center;">
    <strong>Startup:LogiCore</strong><br>
    <strong>Producto:VeriMed</strong>
</div>

<div style="text-align: center;">
    <h3>Team Members:</h3>
</div>
<div style="display: flex; justify-content: center;">
    <table>
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Luna Morales, Gianfranco</td>
            <td>U201824343</td>
        </tr>
        <tr>
            <td>Pingus Rodriguez, Carlos Daniel</td>
            <td>U202113280</td>
        </tr>
        <tr>
            <td>Cabrera Camizan, Jeferson Smith</td>
            <td>U20211c211</td>
        </tr>
        <tr>
            <td>Zagal Vallejo, Nicolás</td>
            <td>U20201c429</td>
        </tr>
        <tr>
            <td>Frisancho Lévano, Sebastian Mathias Salomón</td>
            <td>U202224392</td>
        </tr>
    </table>
</div>
<br>
<div style="text-align: center;">
    <strong>Abril, 2024</strong>
</div>

<h1 style="text-align: center">Registro de versiones del Informe</h1>
<table>
        <thead>
            <tr>
                <th>Versión</th>
                <th>Fecha</th>
                <th>Autor</th>
                <th>Descripción de modificaciones</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>1.0</th>
                <td>04/23/2024</td>
                <td>Carlos Pingus</td>
                <td>Se agregó los puntos del capitulo I.</td>
            </tr>
            <tr>
                <th>1.1</th>
                <td>04/23/2024</td>
                <td>Jeferson Cabrera</td>
                <td>Se agregó todos los puntos del capitulo II del informe.</td>
            </tr>
            <tr>
                <th>1.2</th>
                <td>04/23/2024</td>
                <td>Gianfranco Luna</td>
                <td>Se agregó los puntos 3.1, 3.2, 3.3 y 3.4.</td>
            </tr>
            <tr>
                <th>1.3</th>
                <td>04/25/2024</td>
                <td>Nicolás Zagal</td>
                <td>Se desarrollaron los puntos 4.2 y 4.3</td>
            </tr>
            <tr>
                <th>1.4</th>
                <td>04/25/2024</td>
                <td>Sebastian Frisancho</td>
                <td>Se desarrollaron los puntos 4.1</td>
            </tr>
       </tbody>
</table>
<br><br>
            


## [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
## [Project Report Collaboration Insights](#project-report-collaboration-insights)

## [Contenido](#contenido)
## [Tabla de contenidos](#tabla-de-contenidos)
## [Student Outcome](#student-outcome)

## [Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
   - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
   - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
   - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
   - [1.2.2 Lean UX Process](#122-lean-ux-process-)
     - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
     - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
     - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
     - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

## [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis-)
- [2.1. Competidores](#21-competidores)
   - [2.1.1. Análisis competitivo](#211-analisis-competitivo)
   - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
   - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
   - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
   - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
   - [2.3.1. User Personas](#231-user-personas)
   - [2.3.2. User Task Matrix](#232-user-task-matrix-)
   - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
   - [2.3.4. Empathy Mapping](#234-empathy-mapping)
   - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

## [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
- [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1 Primary Functionality](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2 Quality Attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3 Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
- [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flow Modeline](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
- [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagram](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Software Architecture Container Level Diagram](#433-software-architecture-container-level-diagrams)
    - [4.3.4. Software Architecture Component Level Diagram](#434-software-architecture-component-level-diagrams)
    - [4.3.5. Software Architecture Deployment Diagram](#435-software-architecture-deployment-diagrams)
## [Capítulo VI: Solution UX Design](#capítulo-vi-solution-ux-design)
- [6.1. Style Guidelines](#61-style-guidelines)
  - [6.1.1. General Style Guidelines](#611-general-style-guidelines)
  - [6.1.2. Web, Mobile & Devices Style Guidelines](#612-web-mobile--devices-style-guidelines)
- [6.2. Information Architecture](#62-information-architecture)
  - [6.2.1. Labeling Systems](#621-labeling-systems)
  - [6.2.2. Searching Systems](#622-searching-systems)
  - [6.2.3. SEO Tags and Meta Tags](#623-seo-tags-and-meta-tags)
  - [6.2.4. Navigation Systems](#624-navigation-systems)
- [6.3. Landing Page UI Design](#63-landing-page-ui-design)
  - [6.3.1. Landing Page Wireframe](#631-landing-page-wireframe)
  - [6.3.2. Landing Page Mock-up](#632-landing-page-mock-up)
- [6.4. Applications UX/UI Design](#64-applications-uxui-design)
  - [6.4.1. Applications Wireframes](#641-applications-wireframes)
  - [6.4.2. Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
  - [6.4.3. Applications Mock-ups](#643-applications-mock-ups)
- [6.5. Applications Prototyping](#65-applications-prototyping)
## [Conclusiones](#conclusiones)
## [Bibliografía](#bibliografía)
## [Anexos](#anexos)

# Student Outcome
<table>
  <tr>
    <td><b>Criterio específico</b></td>
    <td><b>Acciones realizadas</b></td>
    <td><b>Conclusiones</b></td>
  </tr>
  <tr>
    <td>
      <p>Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. </p>
    </td>
    <td> 
      <p><strong>TB1</strong></p>
      <p><strong>Luna Morales, Gianfranco:</strong> Durante el desarrollo del To-be se comunicó con mi comparñero con respecto a As Is para tener una mejor visión de los beneficios de utilizar la app.</p>
      <p><strong>Zagal Vallejo, Nicolás:</strong> Durante el desarrollo de esta entrega se mantuvieron comunicaciones constantes con el equipo de trabajo en función de alcanzar los objetivos planteados y retroalimentar los entregables de cada integrante. </p>
      <p><strong>Frisancho Lévano, Sebastian:</strong> Durante el desarrollo del capítulo IV, me enfoqué en comunicar de forma clara y objetiva las decisiones estratégicas del diseño arquitectónico, considerando el perfil técnico y jerárquico de cada público. Esto me permitió asegurar que todos los involucrados entendieran la propuesta, sin importar su nivel de especialización.</p>
        <p><strong>Pingus Rodriguez, Carlos Daniel:</strong> Para el desarrollo del Capítulo 1 del informe, me comuniqué con mis compañeros de equipo para asentar la idea principal del proyecto y tener una visión clara de lo que tenemos que hace para llevar nuestra idea a los usuarios.</p>
      <p><strong>Cabrera Camizan, Jeferson Smith:</strong> Durante el desarrollo del As-Is Scenario Mapping, comuniqué de manera clara los procesos actuales y sus posibles mejoras, adaptándome a los niveles técnicos del equipo. También presenté perfiles de usuarios estructurados mediante las User Personas, alineando al equipo con la visión del usuario final.</p>
      <p><strong>TP</strong></p>
        <p><strong>Frisancho Lévano, Sebastian:</strong> Al trabajar en los lineamientos de estilo y la arquitectura de información, cuidé que el diseño de la interfaz y la estructura de contenidos respondieran a criterios de claridad visual y usabilidad. Esto facilitó la comprensión tanto para usuarios técnicos como no técnicos, reflejando una comunicación efectiva a distintos niveles de especialización.</p>
    </td>
    <td>
      <p><strong>TB1</strong></p> 
      <p>En conclusión: El mantener una buena comunicación aporta a un buen desarrollo del proyecto.</p>
    </td>
  </tr>
  <tr>
    <td>
      <b>Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. </b>
    </td>
    <td> 
      <p><strong>TB1</strong></p>
      <p><strong>Luna Morales, Gianfranco:</strong> Se comunicó con el grupo los puntos tratados del Capítulo III, para poseer una mejor visión en el desarrollo de los puntos consecuentes, como la elaboración C4.</p>
      <p><strong>Zagal Vallejo, Nicolás:</strong> Durante el desarrollo de esta entrega presente el event storming y los diagramas C4 de manera clara y estructurada al equipo de trabajo asegurando un claro entendimiento por parte de todos los miembros y fijar una línea de trabajo optima</p>
      <p><strong>Frisancho Lévano, Sebastian:</strong> Durante el desarrollo del capítulo IV, cuidé que la redacción fuese precisa y accesible para públicos con distintos niveles de conocimiento técnico. Esta forma de escribir me permitió transmitir los resultados del proyecto con objetividad y transparencia, facilitando la comprensión del diseño propuesto por parte de los lectores con distintos niveles de conocimiento.</p>
        <p><strong>Pingus Rodriguez, Carlos Daniel:</strong> Para el desarrollo de la primera parte del proyecto, comuniqué mis ideas a mis compañeros y también rercibí las suyas para definir bien nuestro alcance y poder dimensionar nuestro proyecto a las fechas límite ya establecidas.</p>
      <p><strong>Cabrera Camizan, Jeferson Smith:</strong> Durante el desarrollo del proyecto, comuniqué de manera clara y objetiva las ideas y resultados obtenidos, adaptándome a los diferentes niveles de especialización y jerarquía del público. Esto incluyó la presentación de análisis, propuestas y decisiones clave, asegurando la comprensión y alineación de todos los involucrados en el marco del desarrollo del proyecto.</p>
        <p><strong>TP</strong></p>
        <p><strong>Frisancho Lévano, Sebastian:</strong> Durante el desarrollo del capítulo 6.4, al diseñar y documentar los wireframes y wireflows de la aplicación, me aseguré de representar visualmente cada paso del flujo del usuario de forma intuitiva. Esta representación gráfica no solo mejora la comunicación con diseñadores y desarrolladores, sino que también permite a stakeholders sin perfil técnico comprender fácilmente la funcionalidad y experiencia esperada.</p>
    </td>
    <td>
      <p><strong>TB1</strong></p> 
      <p>En conclusión: Una comunicación con diferentes áreas del equipo permite un mejor entendimiento y desarrollo de los puntos del proyecto.</p>
    </td>
  </tr>
</table>

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Somos ‘LogiCore’, un startup innovador enfocado en crear soluciones de software basadas en arquitecturas y tecnologías de última generación. Nuestro objetivo es garantizar la máxima seguridad en la distribución de medicamentos para hospitales y farmacias, ofreciendo una plataforma tecnológica integral, robusta y fácil de implementar.
Actualmente, estamos aplicando los conocimientos adquiridos en el curso Arquitecturas de Software Emergentes para optimizar nuestro producto, el cual presentaremos como proyecto final. Esta iniciativa no solo nos permitirá validar nuestra solución, sino también perfeccionar nuestras habilidades en el desarrollo de tecnologías innovadoras.

### 1.1.2. Perfiles de integrantes del equipo
<table>
  <tr>
    <th>Información</th>
    <th>Foto</th>
  </tr>
  <tr>
    <td>
      <h2>Pingus Rodriguez, Carlos Daniel </h2>
      <p>Código: U202113280 </p>
      <p>Conocimientos y Habilidades: <br>
      Soy estudiante de la carrera de ingeniería de Software. Me gusta la tecnología y como esta misma ha cambiado significativamente en mi tiempo de vida. Me considero alguien responsable y comprometido con los proyectos; Trato de estar a la par con mis compañeros y compartir con ellos mis conocimientos en ciertos temas específicos.</p>
    </td>
    <td><img src="https://res.cloudinary.com/dydklnicb/image/upload/v1745581562/foto_carlos.jpg"  alt="foto-carlos" width="50%"></td>
  </tr>
  <tr>
    <td>
      <h2>Cabrera Camizan, Jeferson Smith </h2>
      <p>Código: U20211c211 </p>
      <p>Conocimientos y Habilidades: <br>
        Estudiante universitario de la carrera de ingeniería de software. Me gusta trabajar en conjunto para el desarrollo del proyecto. cuento con conocimientos en lenguajes html, css, js, c++ y Agile Project Managment.</p>
    </td>
   <td><img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745628789/imagen_2025-04-25_195308443_hzznhf.png" alt=" " width="80%"></td>

  </tr>
  <tr>
    <td>
      <h2>Zagal Vallejo, Nicolás </h2>
      <p>Código: u20201c4296</p>
      <p>Conocimientos y Habilidades: [<br>
        Estudiante universitario de la carreta de ingeniería de Software. Soy una persona proactiva que buscará siempre el mejor resultado del projecto, domino diversos lenguajes y frameworks como Vue.js, java, bootstrap, golang y flutter</p>
    </td>
<td><img src="static/img/Team%20Members/NicolasZagal.jpg" alt=" " width="1200"></td>
  </tr>
 <tr>
    <td>
      <h2>Gianfranco Luna Morales</h2>
      <p>Código: u201824343</p>
      <p>Conocimientos y Habilidades: [<br>
    Me gusta observar el comportamiento de las personas para así crear un ambiente cómodo y activo; soy práctico y racional para los percances que puedan surgir. Si bien poseo conocimientos básicos en la programación en el lenguaje C + +, aportaré en lo que pueda para realizar con éxito la idea planteada.</p>
    </td>

<td><img src="static/img/Chapter 1/Gianfranco.jpg" width="1000" height="300" style="border-radius: 50%;"></img></td>

  </tr>
 <tr>
    <td>
      <h2>Frisancho Lévano, Sebastian</h2>
      <p>Código: u202224392</p>
      <p>Conocimientos y Habilidades: <br>
          Estudiante de 8vo ciclo de la carrera de ingeniería de software. Soy una persona perseverante con mis metas propuestas, siempre busco la manera de sacar adelante los objetivos propuestos de los proyectos. Me gusta trabajar en entornos didactos y colaborativos, sin temor a expresar mis ideas o preocupaciones a lo largo de los proyectos. Me gusta más lo que son aplicaciones móviles y frontend web.</p>
    </td>
<td><img src="static/img/Team Members/Alumno.jpg" width="1200" style="border-radius: 50%;"></img></td>
  </tr>
</table>

## 1.2.  Solution Profile
VeriMed es una plataforma innovadora que combina blockchain y tecnología NFT para erradicar la falsificación de medicamentos. Cada lote farmacéutico se registra como un token único en la cadena de bloques, vinculado a un QR escaneable que permite a pacientes, farmacias y reguladores verificar en segundos el origen, autenticidad y recorrido completo del medicamento. Frente a sistemas tradicionales opacos y manipulables, VeriMed ofrece trazabilidad inmutable, seguridad descentralizada y una interfaz intuitiva, garantizando que ningún fármaco falsificado llegue a las manos del consumidor.

### 1.2.1. Antecedentes y problemática
La falsificación de medicamentos es una crisis global que pone en riesgo millones de vidas y representa pérdidas económicas millonarias. Según la OMS, 1 de cada 10 medicamentos en países en desarrollo es falsificado, mientras que sistemas tradicionales de serialización (como códigos de barras) resultan insuficientes ante redes criminales sofisticadas. VeriMed surge como respuesta a este desafío, aprovechando el potencial de blockchain y NFTs para crear una trazabilidad inquebrantable desde el laboratorio hasta el paciente.

| What	| Who	| Where |	When |	Why |
| ----- | ---- | ------ | ------- | ---- |
| Medicamentos falsificados o adulterados que ingresan a la cadena de suministro, representando ~$200 mil millones anuales (Interpol).	| Afectados: Pacientes (riesgo de salud), farmacias (reputación), laboratorios (pérdidas económicas), gobiernos (regulación fallida). Responsables: Redes criminales, distribuidores ilegales. |	Países en desarrollo (Asia, África, Latinoamérica) son los más vulnerables, pero el problema existe incluso en mercados regulados (EE. UU./UE). |	Crisis en aumento: La OMS reporta un incremento del 30% en incautaciones de fármacos falsos desde 2020 (post-pandemia).	| Sistemas actuales son centralizados, manipulables y no permiten verificación en tiempo real por parte del usuario final. |

| How |	How Much |
| --- | ----- |
| Falsificadores replican empaques, adulteran principios activos o roban lotes genuinos para revenderlos en mercados paralelos. |	**Salud:** 500,000 muertes anuales por medicamentos falsos (Universidad de Edinburgh). **Económico:** Laboratorios pierden hasta 15% de sus ingresos por falsificación. |

### 1.2.2. Lean UX Process. 
#### 1.2.2.1. Lean UX Problem Statements
La falsificación de medicamentos y la opacidad en la cadena de suministro exponen a pacientes a riesgos graves de salud, generan pérdidas millonarias a laboratorios y dificultan la acción regulatoria. Los sistemas actuales (códigos de barras, bases de datos centralizadas) no ofrecen trazabilidad en tiempo real, autenticación infalsificable ni accesibilidad para el usuario final.

#### 1.2.2.2. Lean UX Assumptions.
**User Assumptions:** <br>
•	Pacientes confiarán más en medicamentos con historial verificable. <br>
•	Farmacias preferirán proveedores que usen VeriMed para evitar riesgos legales. <br>
**Business Assumptions:** <br>
•	Laboratorios pagarán por una solución que reduzca falsificaciones y proteja su marca. <br>
•	Reguladores adoptarán VeriMed si cumple estándares globales (ej.: FDA, EMA). <br>
**Features:** <br>
•	Blockchain/NFT es escalable para millones de transacciones de lotes. <br>
•	Los usuarios (pacientes/farmacias) escanearán QR si la app es intuitiva. <br>

#### 1.2.2.3. Lean UX Hypothesis Statements
**Hipótesis 1:** "Si aseguramos la autenticidad de los medicamentos mediante NFTs + QR, reduciremos un 30% los incidentes por falsificaciones reportados por laboratorios en 12 meses." <br>
**Hipótesis 2:** "Si la aplicación muestra el historial de distribución de un medicamento en menos de 5 segundos, el 70% de los pacientes la usará recurrentemente." <br>

#### 1.2.2.4. Lean UX Canvas
<p>
    <img src="https://res.cloudinary.com/dydklnicb/image/upload/v1745634894/image_2025-04-25_213451659_k23udp.png" alt="leanux-canvas" width="850"
</p>
    
## 1.3.  Segmentos objetivo

Los segmentos objetivos son los siguientes:<br>
•	Pacientes que consumen medicamentos. <br>
•	Laboratorios que manufacturan los medicamentos.<br>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
| Nombre del competidor | Descripción |
|------------------------|-------------|
| <img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745544467/imagen_2025-04-24_202747315_e2dssh.png" alt="FarmaTrust" width="120"><br>[FarmaTrust](https://www.farmatrust.com) | FarmaTrust es una plataforma basada en blockchain que se enfoca en innovar y digitalizar el sector farmacéutico y de la salud. Su objetivo principal es proteger a los pacientes, eliminar los productos falsificados, aumentar la eficiencia y proporcionar herramientas de análisis de datos avanzadas. |
| <img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745544513/imagen_2025-04-24_202831867_sfpknt.png" alt="Chronicled" width="120"><br>[Chronicled](https://www.chronicled.com) | Es una plataforma basada en tecnología blockchain que busca mejorar la gestión y trazabilidad de la cadena de suministro de medicamentos, principalmente en el ámbito de la industria farmacéutica. Se enfoca en la transparencia, seguridad y eficiencia de los procesos de distribución y logística. |
| <img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745544544/imagen_2025-04-24_202903875_msbf3i.png" alt="VeChain" width="120"><br>[VeChain](https://vechain.org) | Es una plataforma de blockchain y criptomoneda que se centra en la gestión de la cadena de suministro, buscando mejorar la transparencia y eficiencia en este sector. Utiliza tecnología blockchain y contratos inteligentes para rastrear productos y verificar su autenticidad. |

## 2.1.1. Analisis competitivo

<center>
<table>

  <tr>
    <td colspan="2">Nombre y Logo del competidor</td>
    <td valign="top" align="center"><b>Verimed</b><br><img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745545511/imagen_2025-04-24_204509687_dgzjw1.png" width="100"/></td>
    <td valign="top" align="center"><b>FarmaTrust</b><br><img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745545581/imagen_2025-04-24_204620975_b4s8zu.png" width="100"/></td>
    <td valign="top" align="center"><b>Mediledger</b><br><img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745545603/imagen_2025-04-24_204642844_q3jjc9.png" width="100"/></td>
    <td valign="top" align="center"><b>VeChain</b><br><img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745545627/imagen_2025-04-24_204706432_khcrjq.png" width="100"/></td>
  </tr>

  <!-- Perfil -->
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>Plataforma basada en NFTs por lote para trazabilidad. Escaneo de QR por el usuario final para verificar autenticidad y distribución.</td>
    <td>Blockchain orientado a gobiernos y grandes laboratorios para trazabilidad y cumplimiento normativo.</td>
    <td>Cumplimiento regulatorio (DSCSA) en EE.UU. para verificación entre empresas farmacéuticas.</td>
    <td>Blockchain generalista para múltiples industrias, con uso de sensores IoT en trazabilidad farmacéutica.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva</td>
    <td>Verificación directa por el usuario. Transparencia, descentralización y participación del consumidor.</td>
    <td>Fuerte orientación institucional y cumplimiento normativo. Seguridad para grandes actores.</td>
    <td>Especialización en legislación de EE.UU. y trazabilidad mediante red privada.</td>
    <td>Adaptabilidad a industrias. Uso combinado de sensores físicos y blockchain.</td>
  </tr>

  <!-- Marketing -->
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td>Mercado Objetivo</td>
    <td>Laboratorios, farmacias y pacientes en regiones con riesgo de falsificación.</td>
    <td>Gobiernos, farmacéuticas y distribuidores globales.</td>
    <td>Industria farmacéutica estadounidense (DSCSA).</td>
    <td>Empresas de sectores diversos interesadas en IoT+Blockchain.</td>
  </tr>
  <tr>
    <td>Estrategia de Marketing</td>
    <td>Educación digital, ferias tecnológicas, alianzas con laboratorios.</td>
    <td>Foros institucionales, agencias regulatorias, innovación en salud.</td>
    <td>Colaboración con reguladores, publicaciones técnicas, redes B2B.</td>
    <td>Marketing cripto, comunidad blockchain, partners industriales.</td>
  </tr>

  <!-- Producto -->
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td>Productos & Servicios</td>
    <td>NFTs por lote, QR escaneable, dashboard de trazabilidad, app para usuarios.</td>
    <td>Validación de medicamentos, trazabilidad completa, cumplimiento regulatorio.</td>
    <td>Red blockchain para verificación, cumplimiento normativo, B2B.</td>
    <td>Sensores físicos, plataforma personalizada, infraestructura blockchain.</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>SaaS por laboratorio, licencias por lote/token, costos variables por volumen.</td>
    <td>Licencias institucionales, integración con sistemas regulatorios.</td>
    <td>Suscripción por nivel de uso, costos por volumen y cumplimiento legal.</td>
    <td>Pago por uso/nodo, consumo de red y servicios IoT complementarios.</td>
  </tr>
  <tr>
    <td>Canales de Distribución</td>
    <td>App móvil y web.</td>
    <td>Web institucional, APIs para entes reguladores.</td>
    <td>Red privada autorizada, plataformas B2B.</td>
    <td>Plataforma pública, API, documentación técnica.</td>
  </tr>

  <!-- SWOT -->
  <tr>
    <td rowspan="5">Análisis SWOT</td>

  </tr>
  <tr>
    <td>Fortalezas</td>
    <td>Acceso directo al consumidor; trazabilidad total con blockchain pública.</td>
    <td>Alianzas fuertes; cumplimiento legal consolidado.</td>
    <td>Madurez tecnológica y enfoque normativo claro en EE.UU.</td>
    <td>Escalabilidad e integración con hardware físico.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Gobiernos interesados en control sanitario; regiones con alta falsificación.</td>
    <td>Expansión a mercados emergentes con tecnología móvil.</td>
    <td>Escalar a países con marcos legales similares.</td>
    <td>Expandir a verticales farmacéuticas específicas.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Dependencia de la aceptación de tecnología blockchain y NFTs en el sector salud; necesidad de educación del usuario.</td>
    <td>Modelo muy institucional, no apto para consumidores; alta complejidad de implementación.</td>
    <td>Limitado a regulaciones específicas; poca interacción con el usuario final o paciente.</td>
    <td>No centrado en salud, puede carecer de enfoque profundo en las necesidades farmacéuticas.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Baja adopción en mercados conservadores; barreras regulatorias para innovación con blockchain pública..</td>
    <td>Nuevas startups más ágiles o con soluciones más orientadas al consumidor.</td>
    <td>Cambios en legislación o adopción de otras tecnologías de trazabilidad no blockchain.</td>
    <td>Competencia de soluciones especializadas en salud que ofrezcan mayor personalización.</td>
  </tr>
</table>
</center>

## 2.1.2. Estrategias y tácticas frente a competidores
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th><b>Descripción</b></th>
      <th><b>Estrategias</b></th>
      <th><b>Tácticas</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Fortalezas de los competidores</b><br>
        - Enfoque institucional consolidado<br>
        - Cumplimiento de normativas internacionales<br>
        - Madurez tecnológica y empresarial<br>
        - Infraestructura escalable
      </td>
      <td>
        - Centrarse en el usuario final como ventaja diferencial<br>
        - Operar en mercados desatendidos<br>
        - Transparencia abierta vía QR y blockchain pública
      </td>
      <td>
        - Interfaces simples y amigables para escaneo<br>
        - Pilotos con farmacias locales<br>
        - Campañas educativas en redes sociales
      </td>
    </tr>
    <tr>
      <td><b>Debilidades de los competidores</b><br>
        - Poca orientación al usuario final<br>
        - Soluciones centralizadas<br>
        - Falta de uso de NFTs por lote
      </td>
      <td>
        - Democratizar trazabilidad para laboratorios pequeños<br>
        - Uso de blockchain pública para accesibilidad<br>
        - Solución económica y flexible
      </td>
      <td>
        - Panel autogestionable para laboratorios<br>
        - Versión Lite para infraestructura baja<br>
        - Casos de éxito como prueba social
      </td>
    </tr>
    <tr>
      <td><b>Oportunidades frente a la competencia</b><br>
        - Mercados emergentes con necesidad de trazabilidad<br>
        - Alianzas con entidades públicas<br>
        - Aumento de conciencia ciudadana<br>
        - Ventajas de autenticación con NFTs
      </td>
      <td>
        - Posicionarse en regiones afectadas por falsificación<br>
        - Educación sobre seguridad en salud<br>
        - Integrar estándares internacionales
      </td>
      <td>
        - Participación en ferias y foros de innovación<br>
        - Alianzas con farmacias y ONGs<br>
        - Reportes de trazabilidad como prueba pública
      </td>
    </tr>
    <tr>
      <td><b>Amenazas en el entorno competitivo</b><br>
        - Evolución acelerada de tecnología<br>
        - Resistencia del sector salud a blockchain<br>
        - Entrada de grandes tecnológicas<br>
        - Cambios regulatorios restrictivos
      </td>
      <td>
        - Innovar continuamente<br>
        - Diseñar sistema con cumplimiento legal en mente<br>
        - Ofrecer modelos híbridos (blockchain pública/privada)
      </td>
      <td>
        - Monitoreo de cambios legales por región<br>
        - Participación en foros de tecnología en salud<br>
        - Infraestructura adaptable a normativas
      </td>
    </tr>
  </tbody>
</table>


## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### Segmento 1: Laboratorios farmacéuticos y fabricantes de medicamentos

1. ¿Cuál es su nombre y cargo dentro del laboratorio?
2. ¿Cuántos años lleva trabajando en la industria farmacéutica?
3. ¿Cuál es el tamaño de su laboratorio (pequeño, mediano, grande)?
4. ¿Actualmente cuentan con algún sistema de trazabilidad de medicamentos? ¿Cómo funciona?
5. ¿Qué tipo de tecnologías están usando para el control de lotes y distribución?
6. ¿Qué tan importante es para ustedes la lucha contra la falsificación de medicamentos?
7. ¿Han tenido incidentes relacionados con medicamentos falsificados o desviaciones en la cadena de distribución?
8. ¿Conocen o han considerado el uso de blockchain para trazabilidad? ¿Qué opinan?
9. ¿Qué ventajas perciben en un sistema que vincule cada lote a un token único (NFT)?
10. ¿Qué dificultades creen que podrían enfrentar al implementar una solución de este tipo?
11. ¿Quién tomaría la decisión de adoptar una tecnología como VeriMed en su empresa?
12. ¿Qué expectativas tendrían respecto a la seguridad, facilidad de uso e integración con sus sistemas actuales?
13. ¿Cómo imaginan el proceso ideal para garantizar que un medicamento llegue de forma segura al paciente final?
14. ¿Estarían dispuestos a participar en una prueba piloto del sistema VeriMed? ¿Qué condiciones necesitarían?
15. ¿Qué funcionalidades adicionales les gustaría que tenga un sistema de trazabilidad moderno?



### Segmento 2: Pacientes o consumidores de medicamentos

1. ¿Cuál es su nombre?
2. ¿Toma medicamentos de forma frecuente o esporádica?
3. ¿Alguna vez ha sospechado que un medicamento podría no ser auténtico?
4. ¿Conoce el problema de los medicamentos falsificados en su país o región?
5. ¿Le gustaría poder verificar si un medicamento es verdadero antes de consumirlo?
6. ¿Sabe cómo funcionan los códigos QR? ¿Ha escaneado alguno alguna vez?
7. ¿Le resultaría útil poder escanear un código en la caja del medicamento para ver su origen y ruta de distribución?
8. ¿Qué información le gustaría ver al escanear ese código (ej. fabricante, fecha de fabricación, lugar de distribución, etc.)?
9. ¿Con qué frecuencia usa su celular para temas de salud (apps, recordatorios, consultas)?
10. ¿Le genera confianza que una tecnología como blockchain esté detrás del sistema de verificación?
11. ¿Qué preocupaciones tendría sobre el uso de esta tecnología (privacidad, complejidad, confiabilidad)?
12. ¿Qué lo motivaría a usar esta herramienta cada vez que adquiera un medicamento?
13. ¿Cree que este tipo de solución podría ayudar a otras personas, como adultos mayores o pacientes crónicos?
14. ¿Qué sugerencias tendría para que una aplicación como VeriMed sea más fácil de usar o más confiable?
15. ¿Estaría dispuesto/a a participar en una prueba o encuesta futura sobre este sistema?

## 2.2.2. Registro de entrevistas

<table border="1">
  <tbody><tr>
    <td>
      <b>Nombres y apellidos:</b> Yoleny Cordova<br>
      <b>Edad:</b> 18 años <br>
      <b>Distrito:</b> Jaén <br>
      <b>Duración:</b> 06:00 minutos
    </td>
    <td align="center">
      <a target="_blank" rel="noopener noreferrer" href="https://res.cloudinary.com/drkelnilg/image/upload/v1745570702/imagen_2025-04-25_034500919_qqjn48.png"><img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745570702/imagen_2025-04-25_034500919_qqjn48.png" alt="img" width="80%" style="max-width: 100%;"></a>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <b>Enlace:</b> <a href="https://drive.google.com/file/d/1B2qt4G9smmQRBUSthqxa-DEpk66WVELi/view" rel="nofollow">https://goo.su/Ao2Pm</a>
      <br>
      <b>Resumen:</b> La entrevistada es una estudiante de 18 años que vive en Jaén. Ella toma medicamentos de forma esporádica y ha escuchado sobre el problema de los medicamentos falsificados. Le gustaría poder verificar la autenticidad de los medicamentos que consume, pero no tiene experiencia previa con códigos QR. Se siente cómoda usando su celular para temas de salud y le gustaría ver información sobre el fabricante y la fecha de fabricación al escanear un código.
    </td>
  </tr>
</tbody></table>

## 2.2.3. Análisis de entrevistas

<strong>Segmento objetivo 1: :</strong>

Los laboratorios farmacéuticos entrevistados destacaron la importancia de contar con sistemas robustos de trazabilidad para garantizar la autenticidad y seguridad de los medicamentos. Actualmente, muchos de ellos enfrentan desafíos relacionados con la falta de visibilidad en la cadena de suministro y el cumplimiento normativo. Aunque algunos ya utilizan tecnologías básicas para el control de lotes, existe interés en adoptar soluciones más avanzadas, como blockchain, siempre que estas sean compatibles con sus sistemas actuales y ofrezcan beneficios claros en términos de eficiencia y transparencia. Además, los entrevistados valoran la posibilidad de integrar herramientas que permitan una validación directa por parte de los consumidores, lo que fortalecería la confianza en sus productos.

<strong>Segmento objetivo 2: :</strong>

Del total de pacientes entrevistados, el 85% expresó preocupación por la autenticidad de los medicamentos que consumen, lo cual evidencia un alto nivel de desconfianza hacia el mercado farmacéutico informal. Aunque un 60% indicó no tener experiencia previa con códigos QR, la mayoría manifestó estar dispuesta a aprender a usarlos si esto contribuye a garantizar su seguridad al momento de consumir medicamentos.

Respecto a la información más valorada al escanear un código QR, el 100% coincidió en la importancia de conocer al fabricante, la fecha de fabricación y la ruta de distribución del producto. Esta necesidad de transparencia refuerza el valor de una plataforma como VeriMed para brindar confianza en la cadena de suministro.

Asimismo, casi todos los entrevistados afirmaron sentirse cómodos utilizando su celular para temas de salud, lo que facilita la futura implementación de herramientas digitales de verificación. Además, más del 70% indicó estar dispuesto a participar en pruebas piloto o encuestas futuras, lo que muestra un alto grado de compromiso y apertura hacia tecnologías innovadoras.


## 2.3. Needfinding


### 2.3.1. User Personas
### Segmento 1: Laboratorios farmacéuticos y fabricantes de medicamentos

Luis Rodríguez es un profesional altamente calificado que ocupa el cargo de Gerente de Producción en el laboratorio farmacéutico FarmaLife,
ubicado en Lima, Perú. Con formación en Ingeniería Química y más de 12 años de experiencia en el sector farmacéutico, Luis es responsable de
asegurar la calidad, seguridad y cumplimiento normativo de los medicamentos que produce su empresa. Su rol implica también supervisar la trazabilidad
y la integridad de la cadena de suministro.

<img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745568149/imagen_2025-04-25_030228314_zhdeeb.png" alt="Luis Rodríguez - FarmaLife"  />

### Segmento 2: Pacientes o consumidores de medicamentos
Rosa García es una mujer de 63 años, residente en Arequipa, Perú, actualmente jubilada después de una carrera como maestra de primaria.
Está casada y se encarga de su propio bienestar físico y emocional. Padece hipertensión y requiere medicación continua, lo que la convierte
en una consumidora frecuente de productos farmacéuticos.

<img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745568283/imagen_2025-04-25_030442706_ll00lp.png" alt="Rosa García - Paciente"  />

### 2.3.2. User Task Matrix


Este User Task Matrix presenta las tareas clave que realizan los usuarios involucrados en el sistema de trazabilidad de medicamentos basado en blockchain.Las tareas
listadas son independientes del uso de la solución tecnológica, y reflejan las acciones necesarias para garantizar la autenticidad, seguridad y trazabilidad de los productos farmacéuticos.

| Tarea                                                                 | Frecuencia   | Importancia |
|----------------------------------------------------------------------|--------------|-------------|
| Supervisar producción de medicamentos                                | Siempre      | Alta        |
| Registrar y vincular lote a sistema de trazabilidad                  | Siempre      | Alta        |
| Verificar trazabilidad del lote                                      | Siempre      | Alta        |
| Visualizar autenticidad mediante plataforma                          | Usualmente   | Alta        |
| Escanear QR para verificar origen del medicamento                    | Siempre      | Alta        |
| Leer información del fabricante o historial del producto             | Usualmente   | Media       |
| Reportar anomalía en trazabilidad                                    | A menudo     | Media       |


### 2.3.3. Empathy Mapping
**User Persona:** Luis Rodriguez - Gerente de Producción en FarmaLife.
Luis es Gerente de Producción en un laboratorio farmacéutico y busca soluciones innovadoras para garantizar la trazabilidad y autenticidad de sus productos. Le preocupan los errores en la distribución y el cumplimiento normativo. Está dispuesto a adoptar tecnología siempre que sea compatible con sus sistemas. Su motivación principal es optimizar procesos y proteger la reputación del laboratorio.

<img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745568946/imagen_2025-04-25_031545345_qxgnht.png" alt="Luis Rodríguez - FarmaLife"  />

**User Persona:** Rosa García - Paciente
Rosa es una paciente adulta que toma medicamentos regularmente y desea sentirse segura al consumirlos. Le preocupa adquirir productos falsificados, pero tiene limitaciones tecnológicas. Valora la simplicidad, la confianza y la transparencia al momento de comprar en farmacias. Busca herramientas fáciles que le permitan verificar la autenticidad del medicamento desde su celular.
<img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745569012/imagen_2025-04-25_031651783_xxyhjc.png" alt="Rosa Garcia "  />


### 2.3.4. As-is Scenario Mapping
**User Persona**: Luis M. Rodríguez.

Este mapa muestra el flujo de trabajo actual de Luis M. Rodríguez, gerente de producción de un laboratorio farmacéutico. A lo largo del proceso, Luis supervisa la producción, registra manualmente los lotes, coordina la logística de distribución y gestiona documentación de cumplimiento. Sin embargo, al no contar con un sistema robusto de trazabilidad, pierde visibilidad sobre la autenticidad y ubicación del producto una vez que sale de planta

<img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745569620/imagen_2025-04-25_032659230_xsxzt1.png" alt="Luis Rodríguez - FarmaLife"  />

**User Persona**: Rosa E. García.

Este mapa describe la experiencia de Rosa E. García, una paciente adulta que compra y consume medicamentos periódicamente. Desde que recibe su receta médica hasta el momento en que ingiere su medicamento, Rosa confía en lo que le ofrecen en la farmacia, sin contar con herramientas que le permitan validar el origen del producto. Aunque revisa etiquetas y busca información en internet, no logra confirmar si el medicamento es original ni de dónde proviene realmente.

<img src="https://res.cloudinary.com/drkelnilg/image/upload/v1745569656/imagen_2025-04-25_032735798_vawzdz.png" alt="Rosa Garcia "  />

### 2.4. Ubiquitous Language

Este glosario reúne los términos clave utilizados en el dominio de trazabilidad de medicamentos mediante tecnología blockchain.  
Su propósito es establecer un lenguaje común, claro y sin ambigüedades entre todos los miembros del equipo y los stakeholders.

1. **Pharmaceutical Lot**  
   Conjunto de unidades de un producto medicinal que han sido elaboradas bajo las mismas condiciones de producción y están identificadas por un mismo código. Es la unidad básica de trazabilidad en el sistema.

2. **Traceability**  
   Capacidad de seguir el recorrido, la historia y el estado de un medicamento a lo largo de toda la cadena de suministro, desde el fabricante hasta el consumidor final.

3. **Authenticity Verification**  
   Proceso por el cual se valida que un medicamento es original, autorizado y no ha sido falsificado ni manipulado durante su distribución.

4. **Blockchain Record**  
   Información almacenada de forma inmutable en una red blockchain que documenta cada evento relevante relacionado a un lote de medicamentos (producción, envío, recepción, etc.).

5. **Tokenized Lot**  
   Lote farmacéutico que ha sido vinculado a un token digital único e irrepetible (NFT), lo cual permite su identificación y seguimiento en la red blockchain.

6. **NFT – Non-Fungible Token**  
   Unidad digital única que representa la identidad y la historia de un lote específico de medicamentos. Garantiza la integridad de la trazabilidad y no puede ser duplicada ni modificada.

7. **QR Code**  
   Representación gráfica escaneable que permite acceder de manera inmediata a la información relacionada al lote del medicamento, incluyendo su origen y trayectoria.

8. **Supply Chain**  
   Red de actores y procesos que participan en la fabricación, distribución, transporte y venta de un medicamento, desde el laboratorio hasta el consumidor.

9. **Distribution Point**  
   Ubicación dentro de la cadena de suministro donde el producto cambia de manos (por ejemplo, del fabricante al distribuidor, o del distribuidor a la farmacia).

10. **Counterfeit Medicine**  
    Producto que se presenta como legítimo, pero ha sido producido o comercializado sin autorización legal, sin cumplir estándares de calidad, o con ingredientes alterados.

11. **Verification Platform**  
    Aplicación web o móvil que permite al usuario escanear el medicamento y verificar su autenticidad a través de la información registrada en blockchain.

12. **Origin Data**  
    Información crítica relacionada al lugar de fabricación, laboratorio responsable, fecha de producción y eventos logísticos registrados a lo largo de la vida del lote.


# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping


User Persona: Luis M. Rodríguez 
<td><img src="static/img/Chapter 3/to-be-fabric.jpg" alt="" width="50%" ;"></img></td>
<br><br>



User Persona: Rosa E. García 
<td><img src="static/img/Chapter 3/to-be-paciente.jpg" alt="" width="50%" ;"></img></td>


## 3.2. User Stories

| Epic / StoryId | Título | Descripción | Criterios de aceptación |
|----------------|--------|-------------|--------------------------|
| **EPIC-01: Verificación de medicamentos** |    |
| USER-001 | Visualizar el historial de producción | Como gerente de producción, quiero visualizar el historial de producción de los medicamentos para llevar un control de los lotes fabricados y su trazabilidad. | Escenario 1: Visualización de historial<br><br>Criterio 1:<br>Dado que el gerente accede al sistema,<br>Cuando navega al módulo de producción,<br>Entonces se muestra el historial detallado de los lotes producidos, incluyendo fecha, cantidad y estado. |
| USER-002 | Generar reporte de trazabilidad | Como gerente de producción, quiero generar reportes de trazabilidad para analizar el recorrido de cada lote producido. | Escenario 1: Generación de reporte<br><br>Criterio 1:<br>Dado que el gerente está en el módulo de producción,<br>Cuando selecciona un lote específico,<br>Entonces puede generar un reporte PDF con el recorrido completo del medicamento desde su producción hasta el punto de venta. |
| USER-003 | Recibir alertas por anomalías | Como gerente de producción, quiero recibir alertas cuando se detecten anomalías en la trazabilidad para actuar de inmediato. | Escenario 1: Alerta por desviación<br><br>Criterio 1:<br>Dado que el sistema detecta un desvío inusual en la cadena de suministro,<br>Cuando el lote no sigue el recorrido esperado,<br>Entonces se envía una alerta inmediata al gerente con los detalles del evento. |
| **EPIC-02: Acceso y experiencia de usuario** | |
| US-04 | Información adicional del medicamento | Como paciente quiero acceder a detalles del medicamento escaneado para conocer sus componentes, fabricante y fecha de expiración. | **Escenario uno: Información mostrada correctamente**<br>Dado que el paciente escanea un código válido<br>Cuando el sistema recupera los datos asociados<br>Entonces muestra el nombre del medicamento, fabricante, composición y vencimiento |
| US-05 | Acceso sin registro | Como paciente quiero acceder a la verificación sin registrarme para consultar rápidamente la autenticidad del medicamento. | **Escenario uno: El paciente accede sin cuenta**<br>Dado que el paciente abre la app sin iniciar sesión<br>Cuando ingresa a la sección de escaneo<br>Entonces puede escanear un QR sin necesidad de registrarse |
| US-06 | Modo offline para escaneo | Como paciente quiero poder escanear medicamentos incluso sin conexión a internet para verificar su autenticidad en cualquier lugar. | **Escenario uno: Escaneo sin conexión**<br>Dado que el paciente no tiene conexión<br>Cuando abre la app y escanea un código QR<br>Y ese código ya fue verificado previamente<br>Y se sincroniza con blockchain al recuperar la conexión<br>Entonces se muestra la autenticidad desde el caché local |
|  | US-07 | Historial de medicamentos verificados | Como paciente quiero ver un historial de los medicamentos que he verificado para tener un registro de lo que he consumido. | **Escenario uno: Usuario registrado accede a historial**<br>Dado que el paciente inicia sesión<br>Cuando accede a la sección “Historial”<br>Entonces se muestran los medicamentos escaneados previamente con sus fechas |
| **EPIC-03: Participación en seguridad** |    |
| US-08 | Reporte a autoridades | Como paciente quiero poder reportar medicamentos sospechosos para alertar a las autoridades correspondientes. | **Escenario uno: Reporte enviado exitosamente**<br>Dado que el paciente escanea un medicamento sospechoso<br>Cuando presiona el botón "Reportar"<br>Y completa el formulario de reporte<br>Entonces el sistema envía el reporte a la entidad reguladora |
| **EPIC-04: Registro y trazabilidad de lotes** |    |
| US-09 | Registro de lote con NFT | Como laboratorio quiero registrar cada lote como un NFT único en la blockchain para asegurar su trazabilidad inmutable. | **Escenario uno: Registro exitoso**<br>Dado que el laboratorio accede al panel de gestión<br>Cuando completa el formulario de registro de lote<br>Y confirma los datos del producto<br>Entonces se genera un NFT vinculado al lote y se almacena en la blockchain |
| US-10 | Generación de códigos QR | Como laboratorio quiero generar un código QR único para cada lote para que pueda ser escaneado y verificado por los usuarios. | **Escenario uno: Generación correcta de QR**<br>Dado que el lote ha sido registrado exitosamente<br>Cuando el sistema genera el NFT correspondiente<br>Entonces se crea automáticamente un código QR que se puede imprimir en el empaque |
| US-11 | Ver trazabilidad del lote | Como laboratorio quiero ver el historial completo de movimiento de cada lote para asegurar que no haya desvíos en la cadena de distribución. | **Escenario uno: Visualización de la trazabilidad**<br>Dado que el laboratorio accede al panel de control<br>Cuando selecciona un lote registrado<br>Entonces se muestra un historial de ubicaciones, fechas y actores en la cadena de suministro |
| US-12 | Control de fecha de vencimiento | Como laboratorio quiero registrar la fecha de caducidad de cada lote para alertar sobre productos expirados. | **Escenario uno: Registro de fecha de caducidad**<br>Dado que el laboratorio está registrando un lote<br>Cuando ingresa la fecha de vencimiento<br>Entonces el sistema almacena la información y la muestra durante los escaneos<br><br>**Escenario dos: Alerta de proximidad a vencimiento**<br>Dado que un lote está a menos de 30 días de expirar<br>Cuando el sistema ejecuta el análisis diario<br>Entonces se genera una alerta en el panel del laboratorio |
| **EPIC-05: Gestión de usuarios y seguridad** |    |
| US-13 | Gestión de acceso para empleados | Como laboratorio quiero asignar permisos a mis empleados para que solo accedan a funciones según su rol. | **Escenario uno: Creación de usuarios con roles**<br>Dado que el administrador del laboratorio está en la sección de usuarios<br>Cuando registra un nuevo empleado<br>Y selecciona un rol (Ej. técnico, supervisor)<br>Entonces el nuevo usuario solo accede a las funciones permitidas por su rol |
| US-14 | Verificación de integridad de lote | Como laboratorio quiero verificar que los datos de un lote no hayan sido alterados para garantizar que la información sigue siendo confiable. | **Escenario uno: Validación desde blockchain**<br>Dado que el laboratorio consulta un lote<br>Cuando el sistema revisa el hash registrado en la blockchain<br>Entonces se confirma que los datos no han sido modificados desde su creación |
| **EPIC-06: Monitoreo y analítica** |   |
| US-15 | Recepción de alertas por escaneos sospechosos | Como laboratorio quiero recibir notificaciones cuando se detecten escaneos sospechosos de mis lotes para poder actuar rápidamente. | **Escenario uno: Escaneo en ubicación no autorizada**<br>Dado que un lote es escaneado fuera de su ruta esperada<br>Cuando el sistema detecta la anomalía<br>Entonces se envía una alerta al laboratorio con los detalles del evento |
| US-16 | Análisis de métricas de distribución | Como laboratorio quiero acceder a estadísticas de escaneos y distribución para evaluar el comportamiento del mercado y posibles riesgos. | **Escenario uno: Acceso al dashboard analítico**<br>Dado que el usuario tiene rol de supervisor<br>Cuando accede al panel de métricas<br>Entonces puede visualizar gráficas de escaneos por zona geográfica, frecuencia y fechas |





## 3.3. Impact Mapping


User Persona: Luis M. Rodríguez 
<td><img src="static/img/Chapter 3/impact-map-fabric.jpg" alt="" width="50%" ;"></img></td>
<br><br>



User Persona: Rosa E. García 
<td><img src="static/img/Chapter 3/impact-map-paci.jpg" alt="" width="50%" ;"></img></td>

## 3.4. Product Backlog

| Orden | ID | Título | Descripción (Como... deseo... para...) | Story Points |
|-------|----|--------|------------------------------------------|--------------|
| 1 | US01 | Escaneo de código QR | Como paciente, deseo escanear un código QR para verificar si el medicamento es auténtico. | 3 |
| 2 | US02 | Landing Page informativa | Como usuario, deseo acceder a una landing page con información clara sobre VeriMed para entender su uso. | 2 |
| 3 | US09 | Registro de lote con NFT | Como laboratorio, deseo registrar un lote como NFT en blockchain para asegurar su autenticidad. | 4 |
| 4 | US10 | Generación de códigos QR | Como laboratorio, deseo generar un código QR único por lote para permitir su verificación. | 3 |
| 5 | US06 | Visualización del recorrido | Como paciente, deseo visualizar el recorrido del medicamento para asegurarme de su trazabilidad. | 4 |
| 6 | US03 | Notificación de medicamentos falsos | Como paciente, deseo recibir una alerta si el medicamento escaneado es falso o sospechoso. | 3 |
| 7 | US13 | Alertas de escaneos sospechosos | Como laboratorio, deseo recibir alertas cuando se escanee un lote en ubicaciones sospechosas. | 4 |
| 8 | US05 | Reporte a autoridades | Como paciente, deseo reportar un medicamento sospechoso a las autoridades competentes. | 5 |
| 9 | US14 | Análisis de métricas | Como laboratorio, deseo analizar métricas de escaneos y distribución para mejorar el control logístico. | 4 |
| 10 | US07 | Información del medicamento | Como paciente, deseo ver información adicional del medicamento como fabricante, fecha, composición, etc. | 2 |
| 11 | US04 | Historial de escaneos | Como paciente, deseo revisar el historial de medicamentos que he escaneado para control personal. | 3 |
| 12 | US15 | Control de fecha de vencimiento | Como laboratorio, deseo gestionar fechas de vencimiento para alertar sobre productos caducos. | 3 |
| 13 | US16 | Verificación de integridad | Como laboratorio, deseo verificar que los datos del lote en blockchain no han sido alterados. | 2 |
| 14 | US08 | Modo offline para escaneo | Como paciente, deseo escanear un QR sin conexión a internet para verificar autenticidad en zonas remotas. | 5 |
| 15 | US12 | Gestión de acceso a empleados | Como laboratorio, deseo gestionar el acceso a mi equipo para que solo usuarios autorizados manipulen datos. | 3 |
| 16 | US11 | Ver trazabilidad de lote | Como laboratorio, deseo ver en tiempo real la trazabilidad de mis lotes para asegurar su circulación. | 3 |
| 17 | US17 | Acceso sin registro | Como paciente, deseo verificar la autenticidad sin necesidad de registrarme para facilitar el acceso. | 2 |


# Capítulo IV: Strategic-Level Software Design

En este capítulo se presentan las decisiones estratégicas tomadas para la arquitectura del sistema **VeriMed**, centradas en un enfoque **Attribute-Driven Design (ADD)** y **Domain-Driven Design (DDD)**. Estas decisiones están alineadas con los objetivos de transformación digital que propone la solución, garantizando trazabilidad, seguridad y escalabilidad mediante el uso de tecnologías como **blockchain** y **NFT**. Se incluye además el modelado arquitectónico utilizando el **C4 Model**, específicamente en los niveles **Context** y **Container**, permitiendo visualizar de forma clara las responsabilidades, relaciones e interacciones entre los componentes de alto nivel del sistema.

## 4.1. Strategic-Level Attribute-Driven Design

Esta sección describe el enfoque basado en **Attribute-Driven Design (ADD)** para guiar la construcción de VeriMed como solución innovadora contra la falsificación de medicamentos. El proceso ADD permite tomar decisiones arquitectónicas sustentadas en atributos de calidad clave, los cuales definen la forma en que la arquitectura debe responder a requerimientos no funcionales críticos como **seguridad, disponibilidad, usabilidad y escalabilidad**.

### 4.1.1. Design Purpose

El diseño arquitectónico de VeriMed responde a la necesidad de enfrentar la creciente falsificación de medicamentos, una problemática que, según la OMS, afecta al 10% de los fármacos en países en desarrollo. Los sistemas tradicionales de serialización han demostrado ser vulnerables ante redes criminales sofisticadas.

VeriMed propone una solución basada en **blockchain** y **NFTs** para garantizar la trazabilidad y autenticidad de cada lote farmacéutico desde su origen hasta el consumidor final. El enfoque **ADD** permite priorizar atributos críticos como **seguridad, confiabilidad y usabilidad**, asegurando una arquitectura alineada con los objetivos del negocio.

Esta propuesta se orienta a satisfacer las necesidades de dos segmentos clave:

- **Laboratorios y fabricantes**, que buscan certificar y proteger sus productos.
- **Pacientes**, que requieren verificar fácilmente la autenticidad de sus medicamentos.

### 4.1.2. Attribute-Driven Design Inputs

Esta sección recopila los insumos necesarios para tomar decisiones estratégicas de diseño, incluyendo funcionalidades clave, atributos de calidad deseados, y restricciones técnicas o de negocio.

#### 4.1.2.1. Primary Functionality (Primary User Stories)

| Epic / User Story ID | Título                             | Descripción                                                                                                                                          | Criterios de Aceptación                                                                                                      | Relacionado con (Epic ID) |
|----------------------|-------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|----------------------------|
| US-01               | Escaneo de código QR                | Como paciente quiero escanear un código QR en el empaque del medicamento para verificar su autenticidad.                                            | Escenario uno: Código válido → Muestra información del lote desde blockchain. <br> Escenario dos: Código inválido → Alerta. | EPIC-01                    |
| US-03               | Notificación de medicamentos falsos | Como paciente quiero recibir una alerta si un medicamento es falso para no consumirlo y tomar medidas inmediatas.                                   | Escaneo de medicamento falsificado → Muestra alerta roja e instrucciones para reportarlo.                                   | EPIC-01                    |
| US-06               | Visualización del recorrido         | Como paciente quiero ver el recorrido del medicamento desde su fabricación para asegurarme de su procedencia y trazabilidad.                        | Escaneo válido → Muestra línea de tiempo del medicamento desde su origen hasta el punto de venta.                          | EPIC-01                    |
| US-09               | Registro de lote con NFT            | Como laboratorio quiero registrar cada lote como un NFT único en la blockchain para asegurar su trazabilidad inmutable.                              | Completar formulario de lote → Se genera NFT y se almacena en la blockchain.                                                | EPIC-02                    |
| US-10               | Generación de códigos QR            | Como laboratorio quiero generar un código QR único para cada lote para que pueda ser escaneado y verificado por los usuarios.                        | Tras registro exitoso del NFT → Se genera automáticamente un código QR.                                                     | EPIC-02                    |
| US-16               | Verificación de integridad de lote  | Como laboratorio quiero verificar que los datos de un lote no hayan sido alterados para garantizar que la información sigue siendo confiable.       | Consulta del lote → El sistema valida el hash en blockchain.                                                               | EPIC-02                    |

#### 4.1.2.2. Quality Attribute Scenarios

| Atributo     | Fuente            | Estímulo                                                    | Artefacto                          | Entorno                                 | Respuesta                                                   | Medida                                         |
|--------------|-------------------|-------------------------------------------------------------|------------------------------------|------------------------------------------|--------------------------------------------------------------|------------------------------------------------|
| Seguridad    | Usuario externo   | Un atacante intenta modificar los datos de un lote         | Smart contract de la blockchain    | Sistema en operación expuesto a internet | El sistema rechaza la modificación                          | 100% de intentos de modificación rechazados    |
| Disponibilidad | Usuario           | Accede al sistema para verificar medicamento               | Backend y base de datos distribuida | Alta carga o nodos caídos               | El sistema responde usando nodos activos o fallback         | 99.9% disponibilidad mensual                   |
| Rendimiento  | Usuario (paciente)| Escanea un código QR                                       | Backend + frontend                  | Condiciones normales                    | El sistema devuelve los datos rápidamente                   | Tiempo de respuesta < 2 segundos               |
| Escalabilidad| Laboratorio        | Se registran muchos lotes simultáneamente                  | Módulo de registro + blockchain API | Alta demanda (campañas masivas)         | El sistema escala dinámicamente                            | Soporta hasta 1000 registros por minuto        |
| Usabilidad   | Usuario (paciente)| Escaneo sin conocimientos técnicos                         | App móvil / interfaz web            | Acceso desde smartphone                 | Guía mediante interfaz intuitiva                            | 90% de usuarios completan sin asistencia       |

#### 4.1.2.3. Constraints

| Technical Story ID | Título                      | Descripción                                                                                                                                  | Criterios de Aceptación                                                                                  | Relacionado con (Epic ID) |
|--------------------|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|----------------------------|
| TS-01              | Uso obligatorio de Blockchain | El sistema debe utilizar blockchain para garantizar la inmutabilidad de los registros.                                                      | Los lotes deben almacenarse como NFT y verificables vía transacciones.                                   | EPIC-02                    |
| TS-02              | Escaneo por QR obligatorio   | El sistema debe permitir verificación únicamente mediante códigos QR.                                                                       | La funcionalidad QR debe estar disponible en todas las interfaces.                                       | EPIC-01                    |
| TS-03              | Idioma por defecto: español  | Toda la interfaz y mensajes deben estar en español.                                                                                          | El idioma predeterminado debe ser español.                                                               | EPIC-01, EPIC-02           |

### 4.1.3. Architectural Drivers Backlog

| Driver ID | Título de Driver                     | Descripción                                                                                           | Importancia para Stakeholders | Impacto en Technical Complexity |
|-----------|--------------------------------------|-------------------------------------------------------------------------------------------------------|-------------------------------|----------------------------------|
| FD-01     | Registro de lotes como NFT           | Permitir registro con identificador único en blockchain.                                              | High                          | High                             |
| FD-02     | Verificación por QR                  | Escaneo para autenticidad del medicamento.                                                            | High                          | Medium                           |
| QA-01     | Escalabilidad                        | Adaptarse al crecimiento de usuarios y transacciones.                                                 | High                          | High                             |
| QA-02     | Trazabilidad e inmutabilidad         | Asegurar integridad y rastreo de datos.                                                               | High                          | High                             |
| QA-03     | Disponibilidad del sistema           | Disponibilidad 99.9% para verificación constante.                                                     | High                          | Medium                           |
| QA-04     | Tiempo de respuesta                  | Respuesta ante escaneo menor a 3 segundos.                                                            | Medium                        | Medium                           |
| CT-01     | Uso obligatorio de Blockchain        | Toda gestión debe estar en blockchain privada.                                                        | High                          | High                             |
| CT-02     | Idioma por defecto: español          | Toda la interfaz debe estar en español.                                                               | Medium                        | Low                              |

### 4.1.4. Architectural Design Decisions

| Driver ID | Título de Driver                   | Pattern 1: Microservicios                                                                                          | Pattern 2: Arquitectura monolítica                                                                              |
|-----------|------------------------------------|---------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| FD-01     | Registro de lotes como NFT         | Pro: Escalabilidad y separación por dominios. <br> Con: Complejidad en gestión y despliegue.                       | Pro: Sencillo de desarrollar/desplegar. <br> Con: Escalabilidad limitada.                                       |
| QA-02     | Trazabilidad e inmutabilidad       | Pro: Trazabilidad granular por módulo. <br> Con: Riesgo de inconsistencia si no se sincroniza bien.               | Pro: Simple de implementar. <br> Con: Riesgo de cuello de botella.                                              |
| QA-03     | Alta disponibilidad                | Pro: Distribución entre instancias. <br> Con: Gestión avanzada de redundancia necesaria.                          | Pro: Menor riesgo de fallos múltiples. <br> Con: Todo el sistema cae si el monolito falla.                      |
| CT-01     | Uso obligatorio de Blockchain      | Pro: Integración modular con blockchain. <br> Con: Muchos puntos de integración.                                  | Pro: Lógica directa en una sola interfaz. <br> Con: Puede ser rígido y pesado.                                  |

### 4.1.5. Quality Attribute Scenario Refinements

#### Scenario Refinement for Scenario 1

- **Scenario**: Registrar un nuevo lote como NFT.
- **Business Goals**: Garantizar autenticidad e inmutabilidad.
- **Attributes**: Trazabilidad, Seguridad, Integridad.
- **Stimulus**: Laboratorio registra un lote.
- **Components**: Backend, servicio blockchain.
- **Source**: Usuario (laboratorio).
- **Environment**: Operación normal.
- **Artifact**: Módulo de registro, nodo blockchain.
- **Response**: Registro exitoso, NFT generado.
- **Measure**: < 5 segundos, sin pérdida.
- **Questions**: ¿Qué pasa si falla conexión blockchain?
- **Issues**: Necesaria lógica de reintento y verificación.

#### Scenario Refinement for Scenario 2

- **Scenario**: Alerta al escanear un medicamento inválido.
- **Business Goals**: Proteger pacientes.
- **Attributes**: Disponibilidad, Seguridad.
- **Stimulus**: Paciente escanea QR.
- **Components**: Frontend, backend, base de datos.
- **Source**: Usuario (paciente).
- **Environment**: Red móvil o Wi-Fi.
- **Artifact**: API de verificación.
- **Response**: Alerta de lote inválido.
- **Measure**: < 3 segundos.
- **Questions**: ¿Verificación offline posible?
- **Issues**: Versión ligera en el dispositivo.

#### Scenario Refinement for Scenario 3

- **Scenario**: Funcionamiento bajo carga masiva.
- **Business Goals**: Continuidad del servicio.
- **Attributes**: Escalabilidad, Disponibilidad, Rendimiento.
- **Stimulus**: Miles de usuarios simultáneos.
- **Components**: Infraestructura, balanceador, base de datos.
- **Source**: Usuarios concurrentes.
- **Environment**: Evento de salud pública.
- **Artifact**: Sistema completo.
- **Response**: Escala horizontalmente.
- **Measure**: Hasta 10,000 usuarios, < 5s de respuesta.
- **Questions**: ¿Pruebas de carga realizadas?
- **Issues**: Requiere pruebas de estrés y planificación.

## 4.2. Strategic-Level Domain-Driven Design.
En esta sección, el equipo de desarrollo de VeriMed presenta el proceso seguido para la toma de decisiones arquitectónicas de nivel estratégico aplicando el enfoque de Domain-Driven Design (DDD). Este enfoque se centra en el entendimiento profundo del dominio del problema (la industria farmacéutica y el manejo de medicamentos) y cómo estructurar la solución de software en base a ese conocimiento.
### 4.2.1. EventStorming.
Se abordó un enfoque colaborativo y visual que permitió modelar el contexto del dominio. Se exploraron las etapas de Candidate Context Discovery, Domain Message Flows Modeling y la creación de Bounded Context Canvases.


##### Unstructured Exploration:
<p>Es un enfoque visual que reúne a todas las partes interesadas para explorar el dominio de un sistema. Se utilizan notas adhesivas de diferentes colores para representar distintos elementos, facilitando la discusión y el descubrimiento de requisitos.</p>
<img src="static/img/Chapter%204/UnstructuredExploration.png" alt="Event Storming">


| Orden | ID | Título | Descripción (Como... deseo... para...) | Story Points |
|-------|----|--------|------------------------------------------|--------------|
| 1 | US01 | Escaneo de código QR | Como paciente, deseo escanear un código QR para verificar si el medicamento es auténtico. | 3 |
| 2 | US02 | Landing Page informativa | Como usuario, deseo acceder a una landing page con información clara sobre VeriMed para entender su uso. | 2 |
| 3 | US09 | Registro de lote con NFT | Como laboratorio, deseo registrar un lote como NFT en blockchain para asegurar su autenticidad. | 4 |
| 4 | US10 | Generación de códigos QR | Como laboratorio, deseo generar un código QR único por lote para permitir su verificación. | 3 |
| 5 | US06 | Visualización del recorrido | Como paciente, deseo visualizar el recorrido del medicamento para asegurarme de su trazabilidad. | 4 |
| 6 | US03 | Notificación de medicamentos falsos | Como paciente, deseo recibir una alerta si el medicamento escaneado es falso o sospechoso. | 3 |
| 7 | US13 | Alertas de escaneos sospechosos | Como laboratorio, deseo recibir alertas cuando se escanee un lote en ubicaciones sospechosas. | 4 |
| 8 | US05 | Reporte a autoridades | Como paciente, deseo reportar un medicamento sospechoso a las autoridades competentes. | 5 |
| 9 | US14 | Análisis de métricas | Como laboratorio, deseo analizar métricas de escaneos y distribución para mejorar el control logístico. | 4 |
| 10 | US07 | Información del medicamento | Como paciente, deseo ver información adicional del medicamento como fabricante, fecha, composición, etc. | 2 |
| 11 | US04 | Historial de escaneos | Como paciente, deseo revisar el historial de medicamentos que he escaneado para control personal. | 3 |
| 12 | US15 | Control de fecha de vencimiento | Como laboratorio, deseo gestionar fechas de vencimiento para alertar sobre productos caducos. | 3 |
| 13 | US16 | Verificación de integridad | Como laboratorio, deseo verificar que los datos del lote en blockchain no han sido alterados. | 2 |
| 14 | US08 | Modo offline para escaneo | Como paciente, deseo escanear un QR sin conexión a internet para verificar autenticidad en zonas remotas. | 5 |
| 15 | US12 | Gestión de acceso a empleados | Como laboratorio, deseo gestionar el acceso a mi equipo para que solo usuarios autorizados manipulen datos. | 3 |
| 16 | US11 | Ver trazabilidad de lote | Como laboratorio, deseo ver en tiempo real la trazabilidad de mis lotes para asegurar su circulación. | 3 |
| 17 | US17 | Acceso sin registro | Como paciente, deseo verificar la autenticidad sin necesidad de registrarme para facilitar el acceso. | 2 |
=======
##### Pain Points:
<p>Son los problemas o dificultades que enfrentan los usuarios y las partes interesadas en el contexto del sistema. Identificarlos ayuda a priorizar características y soluciones que realmente aborden las necesidades del usuario.</p>
<img src="static/img/Chapter%204/PainPoints.png" alt="Event Storming">


##### Timelines:
<p>Se refiere a la secuencia de eventos que ocurren en el sistema a lo largo del tiempo. Establecer una línea de tiempo ayuda a visualizar cómo los eventos interactúan y afectan el flujo de trabajo, así como a identificar puntos críticos en el proceso.</p>
<img src="static/img/Chapter 4/Timelines.png" alt="Event Storming">

##### Pivotal Points:
<p>Son momentos clave en el flujo de eventos que pueden cambiar el estado del sistema o influir significativamente en la experiencia del usuario. Identificar estos puntos ayuda a concentrar esfuerzos en las áreas más críticas.</p>
<img src="static/img/Chapter%204/PivotalPoints.png" alt="Event Storming">

##### Commands:
<p>Son las acciones o instrucciones que un usuario o sistema puede ejecutar para provocar un cambio en el estado del sistema.</p>
<img src="static/img/Chapter%204/Commands.png" alt="Event Storming">

##### Policies:
<p>Son las reglas o directrices que rigen cómo se deben tomar las decisiones dentro del sistema. Pueden incluir reglas de negocio que determinan cuándo se deben ejecutar ciertos comandos o cómo se deben manejar ciertos eventos.</p>
<img src="static/img/Chapter%204/Policies.png" alt="Event Storming">

##### Read Models:
<p>Son las representaciones de los datos que se utilizan para responder a consultas o solicitudes de información. Los modelos de lectura están diseñados para optimizar la consulta de datos, separándose de los modelos de escritura para mejorar el rendimiento y la escalabilidad.</p>
<img src="static/img/Chapter%204/ReadModels.png" alt="Event Storming">

##### External Systems:
<p>Se refiere a otros sistemas o servicios que interactúan con el sistema principal. Identificar estos sistemas ayuda a entender las dependencias y las integraciones necesarias para el funcionamiento del sistema.</p>
<img src="static/img/Chapter%204/ExternalSystems.png" alt="Event Storming">

##### Aggregates:
<p>Son grupos de objetos que se tratan como una única unidad para la gestión de datos y la lógica de negocio. Un agregado garantiza la consistencia de sus partes en las operaciones y encapsula la lógica de negocio relacionada.</p>
<img src="static/img/Chapter%204/Aggregates.png" alt="Event Storming">

##### Bounded Contexts:
<p>Es un límite claro dentro del dominio del sistema donde un modelo particular se aplica. Define la frontera en la que un conjunto de conceptos y términos tiene un significado específico, ayudando a evitar confusiones y a manejar complejidades en sistemas grandes y distribuidos.</p>
<img src="static/img/Chapter%204/BoundedContext.png" alt="Event Storming">

#### Link del Event Storming:  https://miro.com/app/board/uXjVIAALqDg=/?share_link_id=765648707914

### 4.2.2. Candidate Context Discovery.
Empleando la metodología de Event Storming con enfoque en la técnica de "start-with-simple", utilizamos la línea de tiempo para identificar nuestros candidatos para nuestros contextos delimitados, los cuales son:

Identificación de valores del negocio: Analizamos los valores clave que incluyen brindar al usuario la información correspondiente sobre la trazabilidad que ha seguido su medicamento desde que fue fabricado hasta que llego a sus manos, asegurando la inmutabilidad de la información.

Identificación de funcionalidades clave: Identificamos las funcionalidades básicas del servicio, las cuales incluyen la verificación de la trazabilidad mediante un codigo QR y el reporte de medicamentos sospechosos.

#### Factory Context
<img src="static/img/Chapter%204/FactoryContext.png" alt="Candidate Context Discovery">

#### Business Context
<img src="static/img/Chapter%204/BusinessContext.png" alt="Candidate Context Discovery">

#### Trace Context
<img src="static/img/Chapter%204/TraceContext.png" alt="Candidate Context Discovery">

#### Report Context
<img src="static/img/Chapter%204/ReportContext.png" alt="Candidate Context Discovery">

### 4.2.3. Domain Message Flows Modeling.
#### Registering a product on blockchain
<img src="static/img/Chapter%204/MessageFlow1.png" alt="Domain Message Flows Modeling">

#### Updating product trace on blockchain
<img src="static/img/Chapter%204/MessageFlow2.png" alt="Domain Message Flows Modeling">

#### Consulting product trace on blockchain
<img src="static/img/Chapter%204/MessageFlow3.png" alt="Domain Message Flows Modeling">

#### Reporting suspicious product trace on blockchain
<img src="static/img/Chapter%204/MessageFlow4.png" alt="Domain Message Flows Modeling">

### 4.2.4. Bounded Context Canvases.
#### Factory Management
<img src="static/img/Chapter%204/ContextCanvas1.png" alt="Bounded Context Canvases">

#### Business Transaction Management
<img src="static/img/Chapter%204/ContextCanvas2.png" alt="Bounded Context Canvases">

#### Traceability Verification
<img src="static/img/Chapter%204/ContextCanvas3.png" alt="Bounded Context Canvases">

#### Product Report & Audit
<img src="static/img/Chapter%204/ContextCanvas4.png" alt="Bounded Context Canvases">

### 4.2.5. Context Mapping.
<p>Un Context Map es un modelo visual que muestra cómo se relacionan los diferentes Bounded Contexts dentro de un sistema complejo. Es parte esencial del enfoque de Domain-Driven Design (DDD) y permite comprender las fronteras de responsabilidad de cada contexto, definir como de comunican entre si, identificas el tipo de relaciones y facilitar decisiones arquitectónicas y organizacionales.</p>
<p>El contexto del Business depende de factory porque solo puede operar si los productos fueron creados correctamente. Del mismo modo, el contexto Trace depende de Business ya que depende de la información registrada en cada business para mostrar al usuario final la trazabilidad de su producto. Por su parte el contexto Report depende de Trace y de Factory puesto que a partir de la información de estos contextos es que se generan los reportes y auditorias para la revisión de las productoras.</p>
<img src="static/img/Chapter%204/ContextMapping.png" alt="Context Mapping">

## 4.3. Software Architecture.
### 4.3.1. Software Architecture System Landscape Diagram.
<img src="static/img/Chapter%204/LandscapeDiagram.jpg" alt="Software Architecture System Landscape Diagram">

### 4.3.2. Software Architecture Context Level Diagrams.
<img src="static/img/Chapter%204/ContextDiagram.jpg" alt="Software Architecture System Landscape Diagram">

### 4.3.3. Software Architecture Container Level Diagrams.
<img src="static/img/Chapter%204/ContainerDiagram.jpg" alt="Software Architecture System Landscape Diagram">

### 4.3.4. Software Architecture Component Level Diagrams.
<img src="static/img/Chapter%204/ComponentDiagram.jpg" alt="Software Architecture System Landscape Diagram">

### 4.3.5. Software Architecture Deployment Diagrams
<img src="static/img/Chapter%204/DeploymentDiagram.jpg" alt="Software Architecture System Landscape Diagram">

## Capítulo VI: Solution UX Design

### 6.1 Style Guidelines

Se definió una interfaz limpia, intuitiva y centrada en el usuario. El diseño prioriza la claridad en la información, con textos legibles, íconos representativos y botones de fácil interacción. Se optó por un estilo minimalista, eliminando elementos innecesarios para mantener el enfoque del usuario en las acciones clave: escanear, visualizar y registrar datos.

#### 6.1.1 General Style Guidelines

- **Tipografía**: Se utiliza una fuente sans-serif para garantizar legibilidad en distintos tamaños de pantalla.  
- **Colores**: Uso de colores neutros para los fondos y colores contrastantes para acciones primarias (ej. botón "Registrar entrega").  
- **Iconografía**: Íconos simples para representar el escaneo, ubicación y acciones de navegación.  
- **Espaciado**: Se mantuvo un espaciado generoso entre componentes para evitar la sobrecarga visual y facilitar la navegación táctil.

#### 6.1.2 Web, Mobile & Devices Style Guidelines

Dado que la solución está orientada exclusivamente a dispositivos móviles:

- **Responsive Design**: Aunque no se desarrollará una web, se aplican principios responsivos para garantizar que la app se adapte a distintas resoluciones de móviles.  
- **Touch-Friendly**: Todos los botones y campos cumplen con las guías de accesibilidad móvil (mínimo 48x48 px de área táctil).  
- **Compatibilidad**: La interfaz está pensada para operar correctamente tanto en Android como en iOS.

---

### 6.2 Information Architecture

La arquitectura de la información se estructuró en tres vistas principales:

1. **Escaneo de QR**: Punto de inicio que permite leer el código del medicamento.  
2. **Visualización de información**: Muestra datos del medicamento (nombre, imagen, fechas, y trazabilidad).  
3. **Registro del vendedor**: Permite ingresar la empresa, RUC y vendedor, junto con la ubicación GPS y fecha/hora automática.

Este flujo asegura que la información esté organizada de forma secuencial y fácil de seguir para los distintos actores (usuarios y vendedores).

#### 6.2.1 Labeling Systems

Se emplearon etiquetas claras y directas:

- "Escanea el código QR del producto"  
- "Nombre del medicamento"  
- "Fecha de creación del lote"  
- "Registrar entrega"  

Esto minimiza la curva de aprendizaje del usuario y evita ambigüedades.

#### 6.2.2 Searching Systems

No se implementa un sistema de búsqueda textual en esta versión de la app. El acceso a la información se realiza exclusivamente a través del escaneo del código QR.

#### 6.2.3 SEO Tags and Meta Tags

No aplica directamente, ya que el sistema está enfocado en una aplicación móvil nativa sin una versión web pública indexada por motores de búsqueda. No obstante, se podría considerar en una futura API o dashboard web para administración y reportes.

#### 6.2.4 Navigation Systems

La navegación dentro de la aplicación se diseñó para ser intuitiva y centrada en tareas. Se aplicaron los siguientes principios:

- **Jerarquía clara**: La estructura de navegación sigue el flujo natural de uso: escanear → visualizar → registrar.
- **Menú minimalista**: Se evitó el uso de menús complejos. En su lugar, se utilizan botones de navegación directos en pantalla.
- **Navegación por pantallas**: Cada pantalla tiene un propósito único, lo cual reduce la carga cognitiva del usuario.
- **Botones de retroceso visibles**: Se incluyeron iconos de regreso en la parte superior izquierda para mantener la consistencia con patrones de navegación móviles.
- **Confirmaciones contextuales**: Al registrar una entrega, se muestra un mensaje de éxito con opción de volver al inicio o revisar datos registrados.

Este enfoque asegura que los usuarios puedan completar sus tareas con una cantidad mínima de pasos y sin confusión, incluso si es su primer uso de la app.

## 6.3. Landing Page UI Design
### 6.3.1. Landing Page Wireframe
### 6.3.2. Landing Page Mock-up
## 6.4. Applications UX/UI Design

### 6.4.1. Applications Wireframes

Los wireframes de la aplicación fueron diseñados para mostrar la estructura básica y la disposición de los elementos en pantalla, sin distracciones visuales complejas. Se priorizó una interfaz clara que facilite la navegación y el acceso rápido a las funciones principales:

- Pantalla de escaneo de código QR con un área central destacada para la cámara.
- Vista de detalles del medicamento, mostrando información esencial como nombre, imagen, fecha de creación y trazabilidad.
- Formulario simple para el registro de la entrega, con campos obligatorios resaltados y botones accesibles.
- Uso de elementos estándar de interfaz móvil para garantizar familiaridad, como barras de navegación, botones flotantes y notificaciones modales.

Los wireframes fueron validados con usuarios potenciales para asegurar que el flujo fuese natural y eficiente.

<img src="static/Chapter 6/Applications/AppWireframe.png" width="1200" style="border-radius: 16px;">

### 6.4.2. Applications Wireflow Diagrams

Los diagramas de wireflow combinan los wireframes con el flujo de interacción entre pantallas, permitiendo visualizar el recorrido completo del usuario dentro de la app:

- Inicio en la pantalla de escaneo, con acceso a la cámara para capturar el QR.
- Transición directa a la vista de información del medicamento tras la captura exitosa.
- Opción para registrar la entrega desde la pantalla de detalles, desplegando el formulario correspondiente.
- Confirmación visual del registro exitoso con opciones para regresar al inicio o revisar entregas previas.

Estos diagramas ayudan a identificar puntos críticos en la navegación, optimizar la experiencia de usuario y facilitar la comunicación entre diseñadores y desarrolladores.

<img src="static/Chapter 6/Applications/AppWireflow.png" width="1200" style="border-radius: 16px;">

### 6.4.3. Applications Mock-ups
## 6.5. Applications Prototyping

# Conclusiones
# Bibliografía
# Anexos

