<div align="center">

<p align="center">
  <img src="assets/upc_logo.png" alt="logo" width="200"/>
</p>

<h3 align="center">
Universidad Peruana de Ciencias Aplicadas
</h3>

<h3 align="center">
Ingeniería de Software  
<br><br>
Ciclo: 2026-10
<br><br>
1ASI0728 - Arquitecturas de Software Emergentes
<br><br>
NRC: 17957
<br><br>
Profesor: Marino Humberto Jara Palacios  
<br><br>
<strong>Informe de Trabajo Final</strong>  
<br><br>
Startup:
<br><br>
Producto:
<br><br>
<strong>Integrantes</strong>
<br><br>
</h3>

<table align="center">
  <tr>
    <th>Nombre</th>
    <th>Código</th>
  </tr>
  <tr>
    <td>Luquillas Asto, Omar</td>
    <td>U20211G641</td>
  </tr>
  <tr>
    <td>Peña Riofrio, Maria Fernanda</td>
    <td>U202113279</td>
  </tr>
  <tr>
    <td>Pilares Pocohuanca, Maria</td>
    <td>U202215528</td>
  </tr>
  <tr>
    <td>Sanchez Silva, Luciana Celeste</td>
    <td>U202215979</td>
  </tr>
  <tr>
    <td>Sandoval Paiva, Valentino</td>
    <td>U20211A962</td>
  </tr>
</table>

<br><br>

<h3 align="center">
Abril 2026
</h3>
<br>
</div>


## Registro de Versiones del Informe

| Versión | Fecha      | Autor | Descripción de modificación |
|---------|------------|-------|-----------------------------|
| TB1     | 09/04/2026 | Omar Luquillas Asto | Creación de estructura inicial del informe |
| TB1     | /04/2026 |  |  |
| TB1     | /04/2026 |  |  |
| TB1     | /04/2026 |  |  |
| TB1     | /04/2026 |  |  |


## Project Report Collaboration Insights

|  URL del repositorio del reporte  |
| :-----------------------------------: |
| [https://github.com/G2-Arqui-Emergentes/Report](https://github.com/G2-Arqui-Emergentes/Report) |


## Contenido

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

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
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
        - [4.1.2.1. Primary Functionality](#4121-primary-functionality-primary-user-stories)
        - [4.1.2.2. Quality Attribute Scenarios](#4122-quality-attribute-scenarios)
        - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Context Level Diagrams](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Container Level Diagrams](#433-software-architecture-container-level-diagrams)
    - [4.3.4. Deployment Diagrams](#434-software-architecture-deployment-diagrams)

- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

- [Bibliografía](#bibliografía)

- [Anexos](#anexos)


## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:<br>
**ABET – EAC - Student Outcome 3**

**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*<br>
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.</strong></td>
      <td>
        Luquillas Asto, Omar<br>
        <em>TB1</em><br> A <br><br>
        Peña Riofrio, Maria Fernanda<br>
        <em>TB1</em><br> B <br><br>
        Pilares Pocohuanca, Maria<br>
        <em>TB1</em><br> C <br><br>
        Sanchez Silva, Luciana Celeste<br>
        <em>TB1</em><br> D <br><br>
        Sandoval Paiva, Valentino<br>
        <em>TB1</em><br> E
      </td>
      <td>
        TB1:<br> A
      </td>
    </tr>
    <tr>
      <td><strong>Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.</strong></td>
      <td>
        Luquillas Asto, Omar<br>
        <em>TB1</em><br> A <br><br>
        Peña Riofrio, Maria Fernanda<br>
        <em>TB1</em><br> B <br><br>
        Pilares Pocohuanca, Maria<br>
        <em>TB1</em><br> C <br><br>
        Sanchez Silva, Luciana Celeste<br>
        <em>TB1</em><br> D <br><br>
        Sandoval Paiva, Valentino<br>
        <em>TB1</em><br> E
      </td>
      <td>
        TB1:<br> A
      </td>
    </tr>
  </tbody>
</table>


## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

#### 1.1.2. Perfiles de integrantes del equipo

### 1.2. Solution Profile

#### 1.2.1 Antecedentes y problemática

#### 1.2.2 Lean UX Process

##### 1.2.2.1 Lean UX Problem Statements

##### 1.2.2.2 Lean UX Assumptions

##### 1.2.2.3 Lean UX Hypothesis Statements

##### 1.2.2.4 Lean UX Canvas

### 1.3. Segmentos objetivo


## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

#### 2.1.1. Análisis competitivo

#### 2.1.2. Estrategias y tácticas frente a competidores

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

#### 2.2.2. Registro de entrevistas

#### 2.2.3. Análisis de entrevistas

### 2.3. Needfinding

#### 2.3.1. User Personas

#### 2.3.2. User Task Matrix

#### 2.3.3. Empathy Mapping

#### 2.3.4. As-is Scenario Mapping

### 2.4. Ubiquitous Language


## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

### 3.2. User Stories

### 3.3. Impact Mapping

### 3.4. Product Backlog


## Capítulo IV: Strategic-Level Software Design

### 4.1. Strategic-Level Attribute-Driven Design

#### 4.1.1. Design Purpose

#### 4.1.2. Attribute-Driven Design Inputs

##### 4.1.2.1. Primary Functionality (Primary User Stories)

##### 4.1.2.2. Quality Attribute Scenarios

##### 4.1.2.3. Constraints

#### 4.1.3. Architectural Drivers Backlog

#### 4.1.4. Architectural Design Decisions

#### 4.1.5. Quality Attribute Scenario Refinements

### 4.2. Strategic-Level Domain-Driven Design

En esta sección se describe el proceso seguido por el equipo para la toma de decisiones a nivel estratégico aplicando Domain-Driven Design (DDD). El objetivo fue comprender el dominio del sistema de gestión de proyectos, identificar sus principales subdominios y definir límites claros mediante Bounded Contexts.

Para ello, se utilizaron técnicas como EventStorming para explorar los eventos y flujos clave del negocio, así como el descubrimiento de contextos candidatos, el modelado de flujos de mensajes y la elaboración de Bounded Context Canvases. Finalmente, se estableció un Context Map que define las relaciones e interacciones entre los distintos contextos.

#### 4.2.1. EventStorming

El equipo realizó una sesión de EventStorming con una duración aproximada de entre 1 y 2 horas, con el objetivo de obtener una primera aproximación al modelado del dominio del sistema de gestión de proyectos. Esta actividad permitió identificar los eventos principales del negocio y establecer un punto de partida para comprender la dinámica de la aplicación.

Durante esta fase inicial, se llevó a cabo una lluvia de ideas, en la que se identificaron los eventos más significativos del dominio. Estos hechos, representados mediante post-its de color naranja, se redactaron en tiempo pasado para describir acciones que ya han ocurrido, tales como la creación de proyectos, el registro de tareas o la asignación de prioridades.

Este ejercicio facilitó la detección de conceptos clave y las primeras interacciones entre los roles de Team Leader y Team Member, estableciendo una base sólida para el posterior descubrimiento de subdominios y la definición de Bounded Contexts. A continuación, se presentan las capturas correspondientes a esta primera etapa de exploración.

![Event Storming](assets/TB1/event_storming_step1.png)

#### 4.2.2. Candidate Context Discovery

Tras la fase de exploración inicial, el equipo procedió a refinar el modelo del dominio mediante un proceso iterativo de diseño estratégico. Esta etapa se enfocó en dar estructura a los eventos identificados, analizando las causas, las reglas de negocio y las interacciones necesarias para consolidar la arquitectura del sistema de gestión de proyectos. A través de este refinamiento, se logró una transición fluida desde una lluvia de ideas desorganizada hacia la definición de límites de contexto claros y consistentes.

Inicialmente, los eventos de dominio se organizaron de forma cronológica para establecer el flujo de valor del sistema. Se priorizó el diseño del "happy path", representando el escenario ideal donde el líder crea el proyecto y los miembros completan sus tareas sin contratiempos. Posteriormente, se integraron flujos alternativos para cubrir casos como la expulsión de miembros o el vencimiento de tareas, asegurando que la línea de tiempo reflejara la realidad operativa del negocio.

![Candidate Context Discovery](assets/TB1/event_storming_step2.png)

Una vez establecida la línea de tiempo, se analizaron los puntos de fricción o incertidumbre conocidos como pain points. En esta fase se identificaron cuellos de botella y riesgos potenciales, como la posible expiración de códigos de acceso o la sobrecarga de trabajo de los integrantes. Este análisis permitió detectar qué partes del proceso requerían una mayor atención a nivel de diseño o una automatización más robusta.

![Candidate Context Discovery](assets/TB1/event_storming_step3.png)

Posteriormente, se identificaron los eventos pivotales que marcan cambios significativos en el estado o contexto del negocio. Estos hitos sirvieron para dividir el flujo en fases lógicas, separando claramente el momento de configuración del proyecto del periodo de ejecución y seguimiento. Estos puntos de quiebre facilitaron la visualización de los límites naturales entre las diferentes etapas del ciclo de vida del software.

![Candidate Context Discovery](assets/TB1/event_storming_step4.png)

Con el flujo estructurado, se definieron los comandos que representan las intenciones de los usuarios y disparan los eventos del sistema. Estas acciones se formularon en modo imperativo, vinculándolas a los actores específicos, como el Team Leader o el Team Member. Este paso fue fundamental para entender qué operaciones debe exponer el sistema en cada interfaz para que los usuarios puedan interactuar con el dominio.

![Candidate Context Discovery](assets/TB1/event_storming_step5.png)

Para gestionar la lógica automática, se establecieron políticas de automatización que conectan eventos con comandos sin intervención humana directa. Estas reglas permiten que, ante un hecho específico como el cambio de estado de una tarea, el sistema responda automáticamente ejecutando análisis de rendimiento o enviando notificaciones, lo que garantiza una respuesta proactiva ante las dinámicas del equipo.

![Candidate Context Discovery](assets/TB1/event_storming_step6.png)

Asimismo, se identificaron los modelos de lectura o vistas necesarias para que los actores puedan tomar decisiones informadas. Estos representan la información visual, como el tablero Kanban o los dashboards de analítica, que los usuarios consultan antes de ejecutar cualquier comando. La definición de estos modelos asegura que el sistema proporcione los datos adecuados en el momento preciso del flujo.

![Candidate Context Discovery](assets/TB1/event_storming_step7.png)

El modelo se complementó mediante la integración de sistemas externos que interactúan con el dominio pero no forman parte de su núcleo. Se mapearon servicios de terceros para la sincronización de calendarios y el envío de correos electrónicos, identificando cómo estos servicios externos reaccionan a los eventos internos o cómo inyectan información relevante hacia nuestro sistema.

![Candidate Context Discovery](assets/TB1/event_storming_step8.png)

En una etapa avanzada de refinamiento, los elementos se organizaron en agregados para garantizar la consistencia y la integridad de los datos. Estos grupos de objetos de dominio actúan como una unidad, recibiendo comandos y produciendo eventos bajo reglas de negocio estrictas. Esto permitió encapsular la lógica relacionada con entidades clave como el proyecto, las tareas y la gestión de usuarios.

![Candidate Context Discovery](assets/TB1/event_storming_step9.png)

Finalmente, se determinaron los límites de los contextos delimitados analizando la cohesión entre los agregados y la influencia de las políticas de automatización. Esta agrupación final permitió segmentar el dominio en unidades lógicas independientes y manejables, resultando en la identificación de los cinco Bounded Contexts que estructuran la solución tecnológica.

![Candidate Context Discovery](assets/TB1/event_storming_bc1.png)
![Candidate Context Discovery](assets/TB1/event_storming_bc2.png)
![Candidate Context Discovery](assets/TB1/event_storming_bc3.png)
![Candidate Context Discovery](assets/TB1/event_storming_bc4.png)
![Candidate Context Discovery](assets/TB1/event_storming_bc5.png)

#### 4.2.3. Domain Message Flows Modeling

En esta sección se describe el proceso seguido para modelar la interacción entre los distintos Bounded Contexts del sistema, con el objetivo de entender cómo colaboran para resolver los principales escenarios del negocio. Para ello, se utilizó la técnica de Domain Storytelling, representando el flujo de mensajes mediante diagramas de tipo Domain Message Flow.

Estos diagramas permiten visualizar cómo se intercambian commands y events entre actores, sistemas y bounded contexts, facilitando la comprensión de la comunicación y reduciendo el acoplamiento entre componentes. A continuación, se presentan los escenarios más representativos del sistema.

**Escenario 1: Create and Assign Task**

Este escenario describe el proceso mediante el cual un Team Leader crea y asigna una nueva tarea dentro del sistema. El flujo inicia cuando el usuario envía un comando desde la aplicación, el cual es procesado por el bounded context de Gestión de Proyectos y Tareas, generando el evento Task Created.

A partir de este evento, otros bounded contexts reaccionan de forma independiente: Notificaciones envía alertas al usuario asignado, Visualización y Seguimiento actualiza los tableros de tareas, y Analítica y Reportes actualiza las métricas relacionadas con la carga de trabajo. Este escenario muestra claramente un flujo basado en eventos, donde un cambio en el dominio se propaga hacia otros contextos sin generar un fuerte acoplamiento.

![Domain Message Flows Modeling](assets/TB1/domain_message_flows_modeling_1.png)

Escenario 2: Complete Task

En este escenario, un Team Member actualiza el estado de una tarea a completada. Esta acción genera un comando que es procesado por el bounded context de Gestión de Proyectos y Tareas, produciendo el evento Task Completed.

Como consecuencia, el bounded context de Analítica y Reportes recalcula las métricas de desempeño, Visualización y Seguimiento actualiza los dashboards para reflejar el nuevo estado de la tarea, y Notificaciones informa al líder del proyecto sobre la finalización. Este flujo evidencia cómo múltiples contextos colaboran a partir de un único evento de negocio.

![Domain Message Flows Modeling](assets/TB1/domain_message_flows_modeling_2.png)

Escenario 3: Task Overdue Detection

Este escenario representa la detección automática de tareas vencidas dentro del sistema. El flujo es iniciado por un proceso interno (scheduler), que verifica periódicamente las fechas límite de las tareas. Cuando se detecta que una tarea ha superado su fecha de vencimiento, el bounded context de Gestión de Proyectos y Tareas emite el evento Task Overdue.

Este evento es consumido por Analítica y Reportes, que actualiza los indicadores de riesgo, por Visualización y Seguimiento, que muestra alertas en la interfaz, y por Notificaciones, que envía avisos a los usuarios correspondientes. Este escenario demuestra la automatización del sistema y la reacción de múltiples contextos ante eventos críticos.

![Domain Message Flows Modeling](assets/TB1/domain_message_flows_modeling_3.png)

#### 4.2.4. Bounded Context Canvases

Con el fin de estructurar el dominio del sistema y delimitar responsabilidades claras, el equipo diseñó los Bounded Context Canvases correspondientes a cada contexto identificado. Para ello, se siguió un proceso iterativo que incluyó la definición del contexto, la identificación de reglas de negocio, el análisis de capacidades, el reconocimiento de dependencias y la evaluación del diseño.

Cada bounded context fue analizado considerando su propósito dentro del sistema, su lenguaje ubicuo, los mensajes que intercambia con otros contextos y las decisiones de negocio que gobiernan su comportamiento.

La separación en bounded contexts permite reducir la complejidad, facilitar la escalabilidad y mantener la coherencia del modelo, asegurando que cada parte del sistema responda a objetivos específicos con bajo acoplamiento.

A continuación, se describe cada uno de estos contextos, resaltando su propósito, responsabilidades y su rol dentro de la arquitectura del sistema.

**Registro y Autenticación de Usuario**

Este bounded context es responsable de la gestión de identidades dentro del sistema. Permite el registro de usuarios, el inicio de sesión y la validación de credenciales, así como la asignación de roles según el tipo de usuario.

Su función principal es garantizar que solo usuarios autorizados puedan acceder al sistema y realizar acciones dentro de él. Además, proporciona la información necesaria para que otros contextos puedan identificar correctamente a los actores involucrados en cada proceso.

![Bounded Context Canvases](assets/TB1/bounded_context_canvases_1.png)

**Gestión de Proyectos y Tareas**

Este bounded context representa el núcleo del sistema, ya que se encarga de la creación, organización y gestión de proyectos y tareas. Permite a los Team Leaders definir fechas, prioridades y asignar responsables, mientras que los Team Members pueden actualizar el estado de sus tareas.

Asimismo, este contexto genera eventos clave del dominio, como la creación, actualización o vencimiento de tareas, los cuales son consumidos por otros bounded contexts. De esta manera, actúa como el principal emisor de información dentro del sistema y como punto central de coordinación de procesos.

![Bounded Context Canvases](assets/TB1/bounded_context_canvases_2.png)

**Visualización y Seguimiento**

Este contexto se encarga de presentar la información del sistema de manera clara y organizada, utilizando herramientas visuales como tableros y calendarios. Su objetivo principal es facilitar el monitoreo del progreso de las tareas y proyectos por parte de los usuarios.

Adicionalmente, integra indicadores visuales que permiten identificar situaciones relevantes, como retrasos o posibles riesgos en la ejecución de tareas. Para ello, consume información tanto del contexto de Gestión de Proyectos y Tareas como de Analítica y Reportes.

![Bounded Context Canvases](assets/TB1/bounded_context_canvases_3.png)

**Notificaciones**

Este bounded context gestiona la comunicación entre el sistema y los usuarios. Recibe eventos relevantes generados en otros contextos y los transforma en notificaciones que son enviadas en tiempo real.

Asimismo, incorpora mecanismos de automatización que permiten generar recordatorios automáticos, alertas por vencimiento y notificaciones inteligentes sin intervención manual. Esto asegura que los usuarios se mantengan informados de manera oportuna sobre los cambios y eventos importantes dentro del sistema.

![Bounded Context Canvases](assets/TB1/bounded_context_canvases_4.png)

**Analítica y Reportes**

Este bounded context tiene como finalidad procesar la información generada por el sistema para transformarla en métricas y reportes útiles para la toma de decisiones. A partir de los eventos recibidos, calcula indicadores relacionados con el desempeño del equipo y el estado de los proyectos.

Además, incorpora capacidades de análisis que permiten evaluar el rendimiento de los miembros, identificar tareas atrasadas y analizar la carga de trabajo. Estos resultados pueden ser utilizados por otros contextos, como Visualización y Seguimiento, para mejorar la interpretación de la información por parte de los usuarios.

![Bounded Context Canvases](assets/TB1/bounded_context_canvases_5.png)


#### 4.2.5. Context Mapping

En esta sección, el equipo describe el proceso seguido para definir las relaciones entre los distintos Bounded Contexts del sistema, utilizando Context Mapping como herramienta para visualizar la interacción estructural entre ellos.

A partir de la información obtenida en las etapas anteriores, se analizaron múltiples alternativas de organización del dominio, evaluando cómo distribuir las responsabilidades y capacidades entre los contextos. Durante este proceso, se plantearon preguntas como: qué ocurriría si ciertas funcionalidades se movieran a otro contexto, si algunos contextos se dividieran en partes más pequeñas o si se centralizaran ciertas capacidades compartidas.

Inicialmente, se consideró la posibilidad de integrar funcionalidades como la visualización y la analítica dentro del contexto de Gestión de Proyectos y Tareas. Sin embargo, esto generaba un alto acoplamiento y dificultaba la escalabilidad del sistema. Por ello, se decidió separar estas capacidades en contextos independientes, permitiendo una mayor modularidad.

Asimismo, se evaluó la opción de centralizar la generación de notificaciones dentro del contexto principal. No obstante, se determinó que mantener un contexto independiente de Notificaciones permite desacoplar la lógica de comunicación del resto del sistema, facilitando su evolución y automatización.

También se analizó la posibilidad de compartir directamente modelos entre contextos. Sin embargo, esto podría generar dependencias fuertes, por lo que se optó por una comunicación basada en eventos, reduciendo el impacto de cambios entre contextos.

Como resultado de este proceso, se definieron las siguientes relaciones entre bounded contexts:

**Relaciones entre Bounded Contexts**

| Destino (Downstream)            | Origen (Upstream)              | Tipo de Relación   | Descripción                                                                 |
|--------------------------------|--------------------------------|--------------------|-----------------------------------------------------------------------------|
| Visualización y Seguimiento    | Gestión de Proyectos y Tareas  | Customer/Supplier  | Consume información de tareas y proyectos para mostrar el estado en tableros y calendarios. |
| Analítica y Reportes           | Gestión de Proyectos y Tareas  | Customer/Supplier  | Utiliza los eventos generados para calcular métricas y reportes.             |
| Notificaciones                 | Gestión de Proyectos y Tareas  | Customer/Supplier  | Recibe eventos para generar notificaciones en tiempo real.                  |
| Visualización y Seguimiento    | Analítica y Reportes           | Customer/Supplier  | Muestra métricas e indicadores generados por el contexto analítico.         |
| Notificaciones                 | Analítica y Reportes           | Partnership        | Colabora para generar alertas inteligentes basadas en métricas.             |
| Gestión de Proyectos y Tareas  | Registro y Autenticación       | Conformist         | Depende de este contexto para validar usuarios y roles sin modificar su modelo. |
| Todos los contextos            | Registro y Autenticación       | Shared Kernel      | Comparten información básica de usuarios y roles para garantizar consistencia. |

Finalmente, se consideró el uso de patrones de diseño de Domain-Driven Design, como Customer/Supplier, Conformist, Partnership y Shared Kernel, con el fin de definir claramente las responsabilidades y dependencias entre los contextos.

El resultado de este análisis se representa en el siguiente Context Map, el cual muestra de manera visual las relaciones estructurales entre los bounded contexts del sistema.

![Context Mapping](assets/TB1/context_mapping.png)


### 4.3. Software Architecture

En la arquitectura de software primero nos enfocamos en aterrizar la estructura técnica de TaskMaster. Para lograrlo, decidimos utilizar el Modelo C4, ya que nos permite explicar la arquitectura de forma progresiva, desde lo más general hasta los detalles técnicos. A través de estos diagramas mostramos cómo se ve el sistema por fuera y también cómo hemos dividido las responsabilidades internamente para que la solución sea escalable y eficiente.

#### 4.3.1. Software Architecture System Landscape Diagram

En esta sección se presenta el System Landscape Diagram, el cual permite visualizar el sistema dentro de un entorno más amplio, considerando no solo a los usuarios que interactúan con la solución, sino también a otros sistemas externos relevantes. Este diagrama ofrece una perspectiva general del ecosistema en el que se encuentra la aplicación, mostrando cómo se relaciona con actores y servicios externos. De esta manera, se facilita la comprensión del alcance del sistema, sus dependencias y las posibles integraciones con otros sistemas dentro del entorno digital.

![System Landscape Diagram](assets/TB1/system_landscape_diagram.png)

#### 4.3.2. Software Architecture Context Level Diagrams

El diagrama muestra a TaskMaster System en el centro de la interacción. Los usuarios gestionan proyectos y consultan análisis directamente en la plataforma, mientras que el sistema se encarga de orquestar la comunicación con servicios externos. La relación con Mailgun permite que el usuario reciba notificaciones automáticas, y la integración con Google Calendar garantiza que los hitos del proyecto estén siempre sincronizados fuera de la aplicación.

![Context Level Diagram](assets/TB1/context_level_diagram.png)

#### 4.3.3. Software Architecture Container Level Diagrams

En este nivel, se observa cómo el tráfico entra a través de una Landing Page o directamente a las aplicaciones (Angular para web y Flutter para móvil). Todas las peticiones pasan por un API Gateway que las redirige a los servicios correspondientes de Spring Boot. Todos estos servicios comparten una base de datos central en PostgreSQL, asegurando la integridad de la información mientras se mantiene una arquitectura modular y fácil de mantener.

![Container Level Diagram](assets/TB1/container_level_diagram.png)

#### 4.3.4. Software Architecture Deployment Diagrams

Finalmente, presentamos el Diagrama de Despliegue, que ilustra cómo se distribuyen nuestros contenedores en la infraestructura real. Para esta solución, hemos optado por un ecosistema en la nube aprovechando la versatilidad de Vercel para el frontend, GitHub Pages para la landing informativa y Render para alojar tanto nuestros servicios de backend como la base de datos gestionada. Este esquema refleja una configuración de producción pensada en la disponibilidad y facilidad de despliegue continuo.

![Deployment Diagram](assets/TB1/deployment_diagram.png)


## Conclusiones


### Conclusiones y recomendaciones


## Bibliografía


## Anexos

