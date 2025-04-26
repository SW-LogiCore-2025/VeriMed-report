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
                <td>Gianfranco Luna</td>
                <td>Se agregó los puntos 3.1, 3.2, 3.3 y 3.4.</td>
            </tr>
            <tr>
                <th>1.1</th>
                <td>04/25/2024</td>
                <td>Nicolás Zagal</td>
                <td>Se desarrollaron los puntos 4.2 y 4.3</td>
            </tr>
            <tr>
                <th>1.2</th>
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
      <h2>Pingus Rodriguez, Carlos Daniel </h2>
      <p>Código: U202113280 </p>
      <p>Conocimientos y Habilidades: <br>
      Soy estudiante de la carrera de ingeniería de Software. Me gusta la tecnología y como esta misma ha cambiado significativamente en mi tiempo de vida. Me considero alguien responsable y comprometido con los proyectos; Trato de estar a la par con mis compañeros y compartir con ellos mis conocimientos en ciertos temas específicos.</p>
    </td>
    <td><img src=""  alt=" " width="50%"></td>
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

# Conclusiones
# Bibliografía
# Anexos
