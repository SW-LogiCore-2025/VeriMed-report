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
      <p><strong>Cabrera Camizan, Jeferson Smith:</strong> Durante el desarrollo del As-Is Scenario Mapping, comuniqué de manera clara los procesos actuales y sus posibles mejoras, adaptándome a los niveles técnicos del equipo. También presenté perfiles de usuarios estructurados mediante las User Personas, alineando al equipo con la visión del usuario final.</p>
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
      <p><strong>Cabrera Camizan, Jeferson Smith:</strong> Durante el desarrollo del proyecto, comuniqué de manera clara y objetiva las ideas y resultados obtenidos, adaptándome a los diferentes niveles de especialización y jerarquía del público. Esto incluyó la presentación de análisis, propuestas y decisiones clave, asegurando la comprensión y alineación de todos los involucrados en el marco del desarrollo del proyecto.</p>
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
