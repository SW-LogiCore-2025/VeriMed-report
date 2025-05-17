# <center>COURSE PROJECT</center>

<div style="text-align: center;">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img alt="UPC" src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"/><br>
    <strong>Ingeniería de Software - 2025-1</strong><br>
    <strong>Arquitecrua de Software Emergentes - SW81</strong><br>
    <strong>Profesor: ----</strong><br>
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
            <td>---------</td>
            <td>U------</td>
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
                <td>Gianfranco Luna</td>
                <td>Se agregó los puntos 3.1, 3.2, 3.3 y 3.4.</td>
            </tr>
            <tr>
                <th>1.1</th>
                <td>04/25/2024</td>
                <td>Nicolás Zagal</td>
                <td>Se desarrollaron los puntos 4.2 y 4.3</td>
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
## [Conclusiones](#conclusiones)
## [Bibliografía](#bibliografía)
## [Anexos](#anexos)


# Student Outcome
<table> <tr> <td><b>Criterio específico</b></td> <td><b>Acciones realizadas</b></td> <td><b>Conclusiones</b></td> </tr> <tr> <td> <p>Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.</p> </td> <td> <p><strong>TB1</strong></p> <p><strong>Luna Morales, Gianfranco:</strong> Durante el desarrollo del To-be se comunicó de forma proactiva con su compañero para comprender mejor el As-Is, logrando un entendimiento profundo de los beneficios de utilizar la aplicación y facilitando la coordinación del equipo.</p> <p><strong>Zagal Vallejo, Nicolás:</strong> Mantuvo una comunicación constante con todo el equipo para asegurar el cumplimiento de los objetivos, además de ofrecer retroalimentación constructiva sobre los entregables, lo que contribuyó a mejorar la calidad del trabajo colaborativo.</p> <p><strong>Frisancho Lévano, Sebastian:</strong> Explicó claramente las decisiones estratégicas del diseño arquitectónico en el capítulo IV, adaptando su lenguaje a diferentes niveles de especialización, lo que permitió una comprensión efectiva por parte de todos los involucrados.</p> <p><strong>Cabrera Camizan, Jeferson Smith:</strong> Comunico de manera clara los procesos actuales y las posibles mejoras durante el As-Is Scenario Mapping, ajustando su discurso según el nivel técnico del interlocutor y alineando al equipo con la visión centrada en el usuario final.</p>
  <p><strong>TP</strong></p>
  <p><strong>Frisancho Lévano, Sebastian:</strong> Durante el desarrollo del capítulo 6.4, al diseñar y documentar los wireframes y wireflows de la aplicación, me aseguré de representar visualmente cada paso del flujo del usuario de forma intuitiva. Esta representación gráfica no solo mejora la comunicación con diseñadores y desarrolladores, sino que también permite a stakeholders sin perfil técnico comprender fácilmente la funcionalidad y experiencia esperada, facilitando la toma de decisiones informadas.</p>
  <p><strong>Luna Morales, Gianfranco:</strong> En la creación de la landing page, trabajé en la composición visual y textual para transmitir claramente la propuesta de valor de la aplicación, utilizando elementos gráficos y lenguaje accesible para captar la atención de diversos públicos, incluyendo clientes potenciales y usuarios finales.</p>
  <p><strong>Cabrera Camizan, Jeferson Smith:</strong> En la documentación del Domain Layer, me enfoqué en detallar las entidades, atributos y relaciones clave de manera estructurada y clara, para asegurar que tanto desarrolladores como analistas pudieran entender la arquitectura conceptual y técnica del sistema sin ambigüedades.</p>
  <p><strong>Pingus Rodriguez, Carlos Daniel:</strong> Contribuí en la definición y formalización del Domain Layer, aportando en la organización y presentación de la información para que el equipo pudiera mantener una visión común y facilitar la implementación coherente del modelo de dominio.</p>
  <p><strong>Zagal Vallejo, Nicolás:</strong> Al elaborar el diagrama C4 del bounded context, me aseguré de representar con precisión los componentes, sus interacciones y dependencias, lo que permitió al equipo técnico y a los stakeholders tener una visión clara y compartida de la arquitectura del sistema, facilitando la planificación y ejecución del proyecto.</p>
</td>
<td>
  <p><strong>TB1</strong></p>
  <p>En conclusión: La comunicación efectiva y constante entre los miembros favoreció la coordinación y el avance armónico del proyecto.</p>
  <p><strong>TP</strong></p>
  <p>En conclusión: La integración de roles mediante documentación clara, diseño visual y diagramas permitió al equipo compartir una visión común, lo que fortaleció la colaboración y el desarrollo integral del proyecto, mejorando la calidad y cohesión del trabajo final.</p>
</td>
</tr> <tr> <td> <p><b>Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.</b></p> </td> <td> <p><strong>TB1</strong></p> <p><strong>Luna Morales, Gianfranco:</strong> Presentó al equipo los puntos clave del Capítulo III para facilitar el desarrollo progresivo del proyecto y la elaboración del diagrama C4.</p> <p><strong>Zagal Vallejo, Nicolás:</strong> Expuso de forma clara y estructurada el event storming y los diagramas C4, garantizando que todos los miembros comprendieran la línea de trabajo establecida.</p> <p><strong>Frisancho Lévano, Sebastian:</strong> Redactó con precisión y claridad el capítulo IV, adaptando el lenguaje a públicos con distintos niveles técnicos, lo que permitió una comunicación transparente y objetiva del diseño.</p> <p><strong>Cabrera Camizan, Jeferson Smith:</strong> Expuso las ideas y resultados obtenidos de forma clara, asegurando la comprensión y alineación del equipo, tomando en cuenta las distintas especializaciones y niveles jerárquicos.</p>
  <p><strong>TP</strong></p>
  <p><strong>Frisancho Lévano, Sebastian:</strong> Diseñó y documentó wireframes y wireflows detallados en el capítulo 6.4, buscando representar de manera gráfica cada interacción y paso del usuario para asegurar la comprensión y alineación entre diseñadores, desarrolladores y stakeholders, incluso aquellos sin formación técnica.</p>
  <p><strong>Luna Morales, Gianfranco:</strong> En la landing page, desarrollé una presentación visual que destaca las funcionalidades y beneficios del producto, enfocándome en que el mensaje sea claro y atractivo para un público diverso, contribuyendo a una comunicación efectiva.</p>
  <p><strong>Cabrera Camizan, Jeferson Smith:</strong> Elaboró con detalle la documentación del Domain Layer, asegurando que la estructura y relaciones estuvieran bien definidas para facilitar la comprensión técnica y conceptual del proyecto.</p>
  <p><strong>Pingus Rodriguez, Carlos Daniel:</strong> Participó activamente en la documentación del Domain Layer, aportando claridad en la organización y presentación del modelo, lo que permitió una mejor alineación del equipo y una implementación más coherente.</p>
  <p><strong>Zagal Vallejo, Nicolás:</strong> Representó el diagrama C4 con precisión, destacando los componentes y su interacción, lo que ayudó a todos los miembros del equipo a entender la arquitectura y coordinar las actividades de desarrollo.</p>
</td>
<td>
  <p><strong>TB1</strong></p>
  <p>En conclusión: La comunicación interdisciplinaria permitió un mejor desarrollo y entendimiento del proyecto en todas sus fases.</p>
  <p><strong>TP</strong></p>
  <p>En conclusión: La elaboración detallada de wireframes y wireflows, junto con una documentación clara y estructurada, permitió comunicar de manera efectiva las ideas y resultados a públicos diversos, incluyendo técnicos y no técnicos. Esta comunicación visual y técnica facilitó la comprensión compartida, promovió la alineación del equipo y fortaleció la toma de decisiones colaborativa a lo largo del desarrollo del proyecto.</p>
</td>
</tr> </table>

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo
<table>
  <tr>
    <th>Información</th>
    <th>Foto</th>
  </tr>
  <tr>
    <td>
      <h2>Pingus Rodriguez, Carlos Daniel ]</h2>
      <p>Código: [U202113280 ]</p>
      <p>Conocimientos y Habilidades: [<br>
      Soy estudiante de la carrera de ingeniería de Software. Me gusta la tecnología y como esta misma ha cambiado significativamente en mi tiempo de vida. Me considero alguien responsable y comprometido con los proyectos; Trato de estar a la par con mis compañeros y compartir con ellos mis conocimientos en ciertos temas específicos.]</p>
    </td>
    <td><img src=""  alt=" " width="50%"></td>
  </tr>
  <tr>
    <td>
      <h2>[Cabrera Camizan, Jeferson Smith ]</h2>
      <p>Código: [U20211c211 ]</p>
      <p>Conocimientos y Habilidades: [<br>
        Estudiante universitario de la carrera de ingeniería de software. Me gusta trabajar en conjunto para el desarrollo del proyecto. cuento con conocimientos en lenguajes html, css, js, c++ y Agile Project Managment.]</p>
    </td>
   <td><img src="" alt=" " width="50%"></td>

  </tr>
  <tr>
    <td>
      <h2>[Zagal Vallejo, Nicolás ]</h2>
      <p>Código: [u20201c429 6]</p>
      <p>Conocimientos y Habilidades: [<br>
        Estudiante universitario de la carreta de ingeniería de Software. Soy una persona proactiva que buscará siempre el mejor resultado del projecto, domino diversos lenguajes y frameworks como Vue.js, java, bootstrap, golang y flutter]</p>
    </td>
<td><img src="static/img/Team%20Members/NicolásZagal.jpg" alt=" " width="1200"></td>
  </tr>
 <tr>
    <td>
      <h2>[Gianfranco Luna Morales]</h2>
      <p>Código: [u201824343]</p>
      <p>Conocimientos y Habilidades: [<br>
    Me gusta observar el comportamiento de las personas para así crear un ambiente cómodo y activo; soy práctico y racional para los percances que puedan surgir. Si bien poseo conocimientos básicos en la programación en el lenguaje C + +, aportaré en lo que pueda para realizar con éxito la idea planteada.]</p>
    </td>
<td><img src="" alt=" " width="50%"></td>
  </tr>
 <tr>
    <td>
      <h2>[------]</h2>
      <p>Código: [u------]</p>
      <p>Conocimientos y Habilidades: [-------]</p>
    </td>
<td><img src="" alt=" " width="50%"></td>
  </tr>
</table>


## 1.2.  Solution Profile
### 1.2.1. Antecedentes y problemática


### 1.2.2. Lean UX Process. 
#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions.

#### 1.2.2.3. Lean UX Hypothesis Statements


#### 1.2.2.4. Lean UX Canvas

## 1.3.  Segmentos objetivo

Los segmentos objetivos son los siguientes:

# Capítulo II: Requirements Elicitation & Analysis 

## 2.1. Competidores

## 2.1.1. Analisis competitivo


## 2.1.2. Estrategias y tácticas frente a competidores


## 2.2. Entrevistas


### 2.2.1. Diseño de entrevistas



## 2.2.2. Registro de entrevistas



## 2.2.3. Análisis de entrevistas

<strong>Segmento objetivo 1: :</strong>


<strong>Segmento objetivo 2: :</strong>

## 2.3. Needfinding


### 2.3.1. User Personas




### 2.3.2. User Task Matrix 




### 2.3.3. User Journey Mapping



### 2.3.4. Empathy Mapping


### 2.3.5. As-is Scenario Mapping


### 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping

## 3.2. User Stories


## 3.3. Impact Mapping



## 3.4. Product Backlog

# Capítulo IV: Strategic-Level Software Design
## 4.1. Strategic-Level Attribute-Driven Design.
### 4.1.1. Design Purpose.
### 4.1.2. Attribute-Driven Design Inputs.
#### 4.1.2.1. Primary Functionality (Primary User Stories).
#### 4.1.2.2. Quality attribute Scenarios.
#### 4.1.2.3. Constraints.
### 4.1.3. Architectural Drivers Backlog.
### 4.1.4. Architectural Design Decisions.
### 4.1.5. Quality Attribute Scenario Refinements.
## 4.2. Strategic-Level Domain-Driven Design.
### 4.2.1. EventStorming.
### 4.2.2. Candidate Context Discovery.
### 4.2.3. Domain Message Flows Modeling.
### 4.2.4. Bounded Context Canvases.
### 4.2.5. Context Mapping.
## 4.3. Software Architecture.
### 4.3.1. Software Architecture System Landscape Diagram.
### 4.3.2. Software Architecture Context Level Diagrams.
### 4.3.3. Software Architecture Container Level Diagrams.
### 4.3.4. Software Architecture Component Level Diagrams.
### 4.3.5. Software Architecture Deployment Diagrams




# Conclusiones
# Bibliografía
# Anexos
