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
| TB1     | 11/04/2026 | Luciana Sanchez Silva | Desarrollo del capítulo 1 |
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

En el actual paradigma de la transformación digital, las organizaciones se enfrentan a un fenómeno crítico de fragmentación tecnológica. La dependencia sistémica de herramientas heterogéneas e inconexas —como hojas de cálculo de baja escala, protocolos de comunicación asíncronos (correos electrónicos) y plataformas de mensajería instantánea— ha derivado en un “ruido operativo” que limita la escalabilidad, duplica los esfuerzos y reduce la eficiencia de los equipos de trabajo. Esta falta de interoperabilidad compromete la integridad de los datos y la visibilidad transversal del ciclo de vida del proyecto.

Frente a esta problemática, nuestra startup surge como una solución que va más allá de centralizar información. Nuestro objetivo es transformar los datos en inteligencia accionable. A través de la integración de Inteligencia Artificial (IA) y Automatización Robótica de Procesos (RPA), evolucionamos de una gestión reactiva basada en el pasado hacia una gestión predictiva, permitiendo a los equipos anticiparse a los escenarios futuros y mejorar la toma de decisiones en tiempo real.

#### 1.1.1. Descripción de la Startup

Nuestra empresa se dedica a crear herramientas digitales que ayudan a los equipos de trabajo a organizarse mejor y a cuidar sus recursos. Nos enfocamos en pequeñas y medianas empresas (pymes) que necesitan una solución efectiva para gestionar sus proyectos, pero sin la complicación o los altos costos de los programas tradicionales.

Para lograrlo, hemos desarrollado **Nombre STARTUP**, una plataforma de gestión de proyectos que no solo sirve para organizar tareas, sino que utiliza tecnología avanzada para facilitar el trabajo diario:

- Analítica Inteligente: **Nombre STARTUP** incluye una IA que revisa automáticamente cómo va avanzando el equipo. Puede identificar si alguien tiene demasiada carga de trabajo, detectar qué tareas se están retrasando y generar reportes de rendimiento sin que el jefe de proyecto tenga que hacer cálculos manuales.

- Seguimiento y Alertas: La plataforma utiliza indicadores visuales de riesgo basados en IA. Esto funciona como un "semáforo" que avisa cuando un proyecto está en peligro de salirse de las fechas pactadas o del presupuesto, permitiendo reaccionar antes de que ocurra un problema.

- Automatización de Notificaciones: Mediante el uso de RPA (Automatización Robótica de Procesos), el sistema se encarga de las tareas repetitivas. Envía recordatorios automáticos de fechas límite y alertas inteligentes a los miembros del equipo, asegurando que nadie olvide sus compromisos.

**Objetivo:** Brindar a las empresas una solución centralizada que combine la planificación de tareas con el control financiero, mejorando la eficiencia y la comunicación mediante el uso de inteligencia y automatización.

**Misión:** Potenciar la productividad de las organizaciones mediante una plataforma que combine gestión humana y eficiencia tecnológica (IA/RPA) para asegurar la entrega exitosa de proyectos.

**Visión:** Ser el referente latinoamericano en software de gestión inteligente, liderando la adopción de automatización y analítica predictiva en el sector empresarial para 2030.

#### 1.1.2. Perfiles de integrantes del equipo

|  | Miembros del equipo | Codigo de estudiante | Descripción |
|-----------|-----------|-----------|-----------|
|   ![m1](./assets/TB1/m1.jpg)  | Luciana Celeste Sanchez Silva   | U202215979    | Mi nombre es Luciana Celeste Sanchez Silva, tengo 20 años y vivo en Lima. En la actualidad, me encuentro estudiando el 5to ciclo de la carrera de ingeniería de software en la UPC debido a que desde una edad temprana tuve una fascinación relacionada con el uso de la tecnología y la programación. En mi tiempo libre trato de crecer y expandir mi conocimiento en todas las áreas posibles. De igual forma, me gusta nadar, escuchar música y tocar la guitarra. Me comprometo a colaborar en todo momento con la elaboración de esta startup, y llegar a un trabajo sobresaliente. Mis habilidades son: responsabilidad, resolución de problemas, y disciplina.    |
|  ![m2](./assets/TB1/m2.png)   | Omar Luquillas Asto    | U20211G641    | Soy estudiante de la carrera de Ingeniería de Software. Elegí esta carrera porque me apasiona la tecnología, el desarrollo de software y la programación. Tengo conocimientos en lenguajes de programación como C++, Python y Java. Me considero una persona investigadora, ya que me gusta aprender cosas nuevas y siempre estoy en busca de soluciones creativas e innovadoras que generen un impacto positivo en la vida de las personas. Además, valoro el trabajo en equipo, soy responsable y me comprometo a cumplir con mis tareas de manera eficiente.    |
| ![m3](./assets/TB1/m3.png)   |  Valentino Sandoval Paiva   | U20211A962   | Soy Valentino Sandoval, tengo 20 años y soy estudiante de la carrera de Ingeniería de Software. Tengo conocimiento en lenguajes de programación como python y c++, y bases de datos como SQLServer y MongoDB. Desde pequeño me sentí atraído por la tecnología, por lo que me decidí a estudiar la carrera, además disfruto de jugar videojuegos con amigos en mi tiempo libre.   |
| ![m4](./assets/TB1/m4.jpg)    | Maria Fernanda Peña Riofrio   | U202113279   | Mi nombre es Maria Fernanda Peña Riofrio, tengo 21 años, estudio el 6to ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Soy una persona responsable y me gusta ayudar a las demás personas, esto sera evidenciado en el transcuros del proyecto ayudando a mis demás compañeros de equipo. En mis tiempos libres me gusta mucho leer, escuchar música e investigar sobre temas de mi interes.    |
| ![m5](./assets/TB1/m5.jpg)     | Maria Pilares Pocohuanca   | U202215528    | Mi nombre es Maria Pilares Pocohuanca tengo 22 años y estudio la carrera de ingeniería de software en la UPC. Desde niña tuve mucho interés por las matemáticas y la tecnología, motivo por el cual estudio una ingeniería enfocada más a la programación. Me considero una persona perseverante aunque algo impaciente. Sin embargo, como miembro del equipo me comprometo a colaborar con mis compañeros y realizar todas las indicaciones que se dicten, todo con el fin de presentar un buen proyecto.   |

### 1.2. Solution Profile

**NAME** es una solución integral diseñada para eliminar el caos operativo causado por el uso de herramientas desconectadas. A diferencia de un gestor de tareas tradicional, nuestra plataforma actúa como un ecosistema inteligente que centraliza la comunicación, el avance técnico y el control financiero en un solo lugar.

**La solución se basa en tres pilares de innovación:**

- Centralización de la Gestión de Proyectos: Unificamos tareas, cronogramas y comunicación en un solo espacio digital. Esto elimina la necesidad de saltar entre múltiples aplicaciones, permitiendo que toda la información del proyecto esté siempre organizada y disponible.

- Colaboración Activa y en Tiempo Real: Facilitamos que los miembros del equipo actualicen sus avances de forma instantánea. Gracias a la Automatización con RPA, el sistema genera notificaciones inteligentes, recordatorios de vencimiento y alertas automáticas, asegurando que todos estén alineados sin esfuerzo manual.

- Asignación de Responsabilidades y Roles: Estructuramos el trabajo mediante roles definidos (jefes de proyecto y miembros). Esta base permite que nuestra IA de Analítica analice el rendimiento individual, detecte tareas atrasadas y sugiera una distribución justa de la carga de trabajo para evitar el agotamiento del equipo.

- Seguimiento Visual Avanzado: Proporcionamos una visibilidad total mediante tableros visuales y calendarios interactivos. Estos se complementan con Indicadores de Riesgo por IA, que funcionan como alertas inteligentes para identificar visualmente si un proyecto corre el riesgo de retrasarse o exceder su presupuesto.

**Restricciones y Alcance**

- Restricciones técnicas: la plataforma debe ser accesible desde dispositivos móvile, con una interfaz intuitiva y adaptable.
- Alcance inicial: orientada a pequeñas y medianas empresas que requieren optimizar la gestión de proyectos sin recurrir a soluciones costosas y complejas.

#### 1.2.1 Antecedentes y problemática

En el entorno empresarial actual, la dependencia de herramientas dispersas (Excel, correos, mensajería y sistemas aislados) genera una gestión fragmentada que reduce la productividad, desperdicia tiempo y afecta los resultados financieros. Un informe de Quickbase (2023) vincula esta fragmentación con pérdidas significativas de eficiencia, mientras que Atlassian (2024) señala que el 56 % de los trabajadores enfrenta flujos de trabajo desconectados, limitando la visibilidad y la colaboración.

Para comprender mejor esta problemática, la analizamos mediante el modelo 5W2H, incorporando además el impacto de la ausencia de tecnologías predictivas.

1. **What / ¿Qué?**

    -  *¿Cuál es el problema?* La gestión fragmentada en herramientas manuales (Excel, chats) provoca pérdida de datos y falta de previsión. Las empresas no saben que un proyecto fallará hasta que ya es tarde, debido a la ausencia de análisis predictivo.

   - *¿Cuál es la relación con la persona en cuestión?* Los líderes se saturan con tareas administrativas (hacer reportes, enviar recordatorios) y los equipos sufren por cargas de trabajo mal distribuidas.

2. **When / Cuándo?**

    - *¿Cuándo sucede el problema?* Durante todo el ciclo del proyecto, pero se vuelve crítico en las fechas de entrega, donde la falta de alertas automáticas (RPA) genera retrasos acumulados.

    - *¿Cuándo utiliza el cliente el producto?* Diariamente, como panel central para recibir instrucciones de la IA y actualizaciones de los bots de notificación.

3. ***Where / Dónde?***

    - *¿Dónde está el cliente cuando usa el producto?* En entornos de oficina, en modalidad híbrida o trabajo remoto. El producto se usa principalmente desde computadoras y dispositivos móviles.

    -*¿Dónde surge el problema?* En la dispersión digital: cuando la información está repartida en varias aplicaciones no integradas.

4. **Who / Quién?**

    - *¿Quiénes se ven involucrados en el problema?* Jefes de proyecto (PM) que necesitan visibilidad de riesgo y miembros del equipo que requieren claridad en sus prioridades.

    - *¿Cuáles son las causas del problema?* Uso de demasiadas aplicaciones sin integración, dependencia de procesos manuales y falta de una IA que analice el rendimiento en tiempo real.

5. **Why / ¿Por qué?**

    - *¿Por qué sucede el problema?* Porque las soluciones actuales solo registran información pasada y aislada (calendarios, chats, finanzas, gestión de tareas), pero no ayudan a predecir el futuro del proyecto. Esto genera duplicidad de trabajo y decisiones basadas en suposiciones, no en datos.

6. **How / Cómo?**

    - *¿En qué condiciones los clientes usan nuestro producto?* Equipos bajo presión con fechas límite estrictas y presupuestos limitados que no pueden permitirse el lujo de perder tiempo en tareas administrativas manuales.

    - *¿Cómo se diferencia el problema del estado normal (óptimo)?* En un estado óptimo, el sistema debería avisar de un retraso antes de que ocurra. Actualmente, la fricción entre sistemas impide esta proactividad.

7. **How Much / Cuánto?**

    - *¿Cuántos problemas se dan en un día, una semana o un mes?* Según Quickbase (2023), el 70 % de los empleados pierde hasta 20 horas por semana debido a sistemas fragmentados. Esto equivale a medio tiempo laboral desperdiciado por cada trabajador.

    - *¿Cuánto dinero están implicando?* Atlassian (2024) reporta que las organizaciones con ecosistemas desconectados tienen un 37 % menos probabilidad de cumplir sus metas de ingresos. Además, Forrester (2024) encontró que el 76 % de las PMOs usan cinco o más herramientas por proyecto, generando pérdidas de hasta un 23 % del tiempo semanal en tareas redundantes.

#### 1.2.2 Lean UX Process

Según Pragma (2021), el proceso Lean UX es la mezcla de metodologías ágiles y temas de usabilidad, donde se prioriza la experiencia de usuario por la creación de un producto. Teniendo en cuenta ello, hemos elaborado nuestro Lean UX process basándonos en sus cuatro pilares principales: problem statements, assumptions, hypothesis y canvas.

##### 1.2.2.1 Lean UX Problem Statements

**Problem Statement #1 – Líderes de Proyecto (Foco en Predicción) :**
Hemos identificado que los líderes de proyecto en pymes dedican excesivo tiempo al análisis manual de datos para identificar retrasos, lo que impide una reacción oportuna. El problema es que las herramientas actuales son reactivas (muestran lo que ya pasó). ¿Cómo podemos utilizar la IA de analítica predictiva  y los indicadores de riesgo  para que los líderes visualicen amenazas antes de que afecten el cronograma, permitiéndoles tomar decisiones estratégicas basadas en datos en lugar de suposiciones?

**Problem Statement #2 – Miembros de Equipo (Foco en Productividad) :**
Los colaboradores enfrentan confusión y agotamiento debido a cargas de trabajo desequilibradas y al constante "ruido" de mensajes manuales para reportar avances. ¿Cómo podemos implementar un sistema de notificaciones inteligentes mediante RPA que automatice el seguimiento y una IA que equilibre las tareas, para que el equipo se enfoque exclusivamente en la ejecución técnica sin distracciones administrativas?

##### 1.2.2.2 Lean UX Assumptions

**Business Assumptions (Suposiciones de Negocio)**

- Creo que mis clientes tienen la necesidad de: Centralizar la gestión de proyectos en una sola plataforma, evitando el uso disperso de herramientas como Excel, correos y chats, y eliminando la carga administrativa de realizar reportes y seguimientos manuales.

- Estas necesidades se pueden resolver con: Una plataforma digital colaborativa que integre tableros Kanban, calendarios, asignación de tareas, un módulo financiero básico y, fundamentalmente, tecnologías inteligentes (IA y RPA) para la analítica de rendimiento y la automatización de notificaciones.

- Mis clientes iniciales son (o serán): Pequeñas y medianas empresas (pymes) con equipos de desarrollo o áreas de proyectos que buscan mejorar la organización, el control de sus recursos y la previsión de riesgos mediante datos en tiempo real.

- El valor principal que los clientes quieren obtener de mi servicio es: Mayor eficiencia y visibilidad en la planificación y ejecución de proyectos. Beneficios adicionales: Mejor colaboración entre miembros, reducción de errores mediante alertas de riesgo (IA), control preciso de presupuestos y reportes automáticos para decisiones estratégicas.

- Adquiriré a la mayoría de mis clientes a través de: Estrategias de marketing digital (redes sociales, LinkedIn), demostraciones gratuitas de la plataforma enfocadas en la automatización y recomendaciones entre contactos en el sector empresarial tecnológico.

- Ganaré dinero mediante: Un modelo de licenciamiento (SaaS), con una versión gratuita limitada y planes de pago escalables según el tamaño de la empresa, el número de miembros y el nivel de acceso a las herramientas de analítica avanzada.

- Mi principal competencia en el mercado será: Plataformas similares como Trello, Asana o Jira. Los superaremos debido a: Un enfoque en la integración financiera simple, el uso de IA predictiva y RPA nativo para reducir el trabajo operativo, precios más accesibles para pymes y una interfaz móvil intuitiva que no requiere capacitación extensa.

- Mi mayor riesgo de producto es: Que las empresas perciban a **name** como una herramienta redundante frente a soluciones ya conocidas. Lo resolveremos mediante: Una diferenciación clara en la propuesta de valor (finanzas integradas + automatización inteligente) y versiones de prueba gratuitas que demuestren el ahorro real de tiempo.

- Otras suposiciones que, si resultan falsas, harán que nuestro proyecto fracase:

  - Que las pymes estén dispuestas a invertir en una solución digital pagada en lugar de continuar con herramientas gratuitas y procesos manuales.

  - Que los usuarios puedan adoptar rápidamente las funciones de IA y RPA sin percibir complejidad técnica en la plataforma.

**User Assumptions (Suposiciones de Usuario)**

- ¿Quién es el usuario?: Nuestros usuarios son líderes o gerentes de empresas con roles como Product Owners, Scrum Masters o jefes de proyectos, así como los miembros de los equipos de desarrollo y colaboradores que ejecutan las tareas técnicas y operativas.

- ¿Dónde encaja nuestro producto en su trabajo o vida?: Dentro del entorno laboral diario, funcionando no solo como un registro de tareas, sino como un asistente inteligente que ayuda en la planificación, asignación y el seguimiento preventivo de los proyectos.

- ¿Qué problemas resuelve nuestro producto?:

  - La dispersión de información entre múltiples canales (Excel, chats, correos).

  - La falta de visibilidad en tiempo real sobre el progreso y los posibles riesgos de retraso.

  - La carga administrativa de realizar reportes manuales y enviar recordatorios constantes.

  - Las dificultades para controlar presupuestos y plazos de forma integrada.

- ¿Cuándo y cómo se usa nuestro producto?: Se utiliza de forma continua durante la jornada laboral. Los líderes lo consultan para revisar indicadores de riesgo y métricas de rendimiento (IA), mientras que los colaboradores lo usan en dispositivos móviles para recibir notificaciones inteligentes (RPA), registrar avances y gestionar sus tareas pendientes.

- ¿Qué características son importantes?:

  - Seguimiento visual mediante tableros Kanban y calendarios.

  - Analítica predictiva : Reportes automáticos de rendimiento y carga de trabajo.

  - Alertas de riesgo : Indicadores inteligentes que anticipan retrasos.

  - Automatización : Notificaciones y recordatorios autónomos mediante RPA.

- ¿Cómo debería verse y comportarse nuestro producto?: Debe tener una interfaz moderna, intuitiva y fácil de aprender. Su comportamiento debe ser proactivo: en lugar de solo esperar datos, el sistema debe alertar al usuario sobre eventos importantes (como un riesgo de atraso o una sobrecarga de tareas) de manera visual y clara, con un diseño totalmente adaptable a móviles.

##### 1.2.2.3 Lean UX Hypothesis Statements

- **Hypothesis Statement 01 (Centralización e IA):**
Creemos que centralizar tareas, cronogramas y comunicación en una sola plataforma potenciada por IA para pymes aumentará la eficiencia operativa.
Sabremos que estamos en lo correcto cuando veamos que más del 70 % de los usuarios reporten una migración total desde herramientas externas como Excel o chats dispersos hacia la plataforma.

- **Hypothesis Statement 02 (Visibilidad de Riesgo):**
Creemos que implementar tableros Kanban con indicadores de riesgo basados en IA mejorará la capacidad de reacción de los líderes.
Sabremos que estamos en lo correcto cuando recibamos retroalimentación positiva en encuestas de usabilidad y veamos un incremento del 40 % en la interacción con los módulos de alerta temprana.

- **Hypothesis Statement 03 (Control Financiero):**
Creemos que ofrecer un módulo financiero básico integrado con alertas de presupuesto facilitará el control de recursos a los gerentes.
Sabremos que estamos en lo correcto cuando observemos que al menos el 60 % de los clientes activos utilicen semanalmente el módulo de estados de pago y presupuestos.

- **Hypothesis Statement 04 (Adopción de Tecnología):**
Creemos que una interfaz intuitiva permitirá que los usuarios adopten las funciones de IA y RPA sin necesidad de capacitación técnica.
Sabremos que estamos en lo correcto cuando nuevos usuarios completen su primera tarea y configuren su primera alerta automática en menos de 10 minutos.

- **Hypothesis Statement 05 (Conversión):**
Creemos que ofrecer una versión de prueba gratuita que incluya funciones básicas de analítica atraerá a clientes de pago.
Sabremos que estamos en lo correcto cuando al menos el 30 % de los usuarios de prueba realicen el "upgrade" a un plan premium tras probar la automatización.

- **Hypothesis Statement 06 (Toma de Decisiones):**
Creemos que integrar métricas de desempeño generadas por IA mejorará la toma de decisiones estratégicas.
Sabremos que estamos en lo correcto cuando el 80 % de los líderes reporten mayor confianza y rapidez al presentar reportes de avance a sus superiores.

- **Hypothesis Statement 07 (Gestión de Carga):**
Creemos que el análisis de la carga de trabajo por IA  permitirá una asignación de roles y tareas más equitativa.
Sabremos que estamos en lo correcto cuando las métricas internas muestren una reducción del 50 % en tareas duplicadas o miembros de equipo con sobrecarga crítica.

- **Hypothesis Statement 08 (Movilidad):**
Creemos que priorizar el acceso móvil incrementará la frecuencia de actualización de tareas en tiempo real.
Sabremos que estamos en lo correcto cuando veamos que más del 50 % de las interacciones con notificaciones inteligentes provengan de dispositivos móviles.

- **Hypothesis Statement 09 (Competitividad):**
Creemos que un precio escalable junto a funciones de IA nativas atraerá a pymes que hoy ven a Jira o Asana como herramientas costosas o complejas.
Sabremos que estamos en lo correcto cuando los clientes destaquen la relación costo-automatización en entrevistas cualitativas.

- **Hypothesis Statement 10 ( Reducción Administrativa):**
Creemos que brindar reportes automáticos de rendimiento eliminará el trabajo manual de los líderes de proyecto.
Sabremos que estamos en lo correcto cuando los usuarios indiquen que han sustituido por completo la generación manual de reportes en Excel por las exportaciones de nuestra IA.

- **Hypothesis Statement 11 (Retención):**
Creemos que un diseño visual moderno y una experiencia de usuario fluida motivarán un uso constante de la plataforma.
Sabremos que estamos en lo correcto cuando los usuarios activos diarios (DAU) se conecten al menos 3 veces por semana para revisar sus indicadores.

- **Hypothesis Statement 12 (Automatización RPA):**
Creemos que los recordatorios automáticos y alertas por vencimiento  mediante RPA reducirán los retrasos en las entregas.
Sabremos que estamos en lo correcto cuando el porcentaje de tareas finalizadas en la fecha establecida aumente un 15 % mes a mes.

- **Hypothesis Statement 13 (Satisfacción):**
Creemos que un soporte técnico integrado y accesible aumentará la lealtad del cliente hacia la plataforma.
Sabremos que estamos en lo correcto cuando el CSAT (Customer Satisfaction Score) de soporte sea superior a 4.5/5.

- **Hypothesis Statement 14 (Escalabilidad Interna):**
Creemos que la segmentación de proyectos por áreas facilitará la gestión en empresas con múltiples equipos de desarrollo.
Sabremos que estamos en lo correcto cuando las empresas clientes gestionen más de 3 proyectos simultáneos utilizando nuestras funciones de analítica cruzada.

- **Hypothesis Statement 15 (Seguridad de Datos):**
Creemos que la seguridad en el manejo de datos financieros y de rendimiento incrementará la confianza de los niveles gerenciales.
Sabremos que estamos en lo correcto cuando la tasa de abandono por preocupaciones de privacidad sea 0 % y los usuarios den feedback positivo sobre la encriptación de sus presupuestos.

##### 1.2.2.4 Lean UX Canvas

![m1](./assets/TB1/LeanUXCanvas.png)

### 1.3. Segmentos objetivo

**Segmento Objetivo 1: Líder o Gerente de Empresa**

Este segmento corresponde a profesionales que ocupan cargos de liderazgo dentro de organizaciones del sector tecnológico o empresarial, tales como gerentes de proyectos, jefes de innovación o líderes de área. Su rol principal consiste en tomar decisiones estratégicas, gestionar recursos y coordinar equipos en proyectos de desarrollo ágil.

- **Características Demográficas:**
En general, suelen encontrarse en el rango de edad de 30 a 50 años, cuentan con estudios universitarios o de posgrado, y residen principalmente en centros urbanos como Lima, Arequipa o Trujillo, donde se concentra la mayor cantidad de empresas con proyectos tecnológicos.

- **Información Estadística de Sustento:**
Según el Informe del INEI (2023), el 65 % de las empresas medianas y grandes del Perú se ubican en Lima Metropolitana, siendo estas las que mayormente adoptan metodologías de gestión de proyectos ágiles. Asimismo, un estudio de Everis y EY (2022) señala que más del 40 % de las empresas peruanas del sector financiero y tecnológico ya han implementado roles asociados a Scrum Master y Product Owner, lo que refleja la creciente relevancia de este segmento para proyectos de desarrollo ágil.

**Segmento Objetivo 2: Equipo de Desarrollo de Proyectos**

Este segmento está conformado por profesionales que se desempeñan como programadores, diseñadores, analistas de sistemas o testers. Su rol es implementar soluciones técnicas, colaborar en la construcción de software y adaptarse a metodologías ágiles bajo la guía de los líderes de proyecto.

- **Características Demográficas:**
En su mayoría, son profesionales jóvenes entre 22 y 35 años, muchos de ellos egresados recientes o estudiantes de los últimos ciclos de carreras de ingeniería de software, sistemas o afines. Están ubicados principalmente en Lima y en regiones con polos tecnológicos como Cusco, Arequipa y La Libertad. Se caracterizan por un alto nivel de adopción tecnológica y el uso frecuente de herramientas colaborativas.

- **Información Estadística de Sustento:**
De acuerdo con el Banco Interamericano de Desarrollo (BID, 2021), en el Perú se proyecta una demanda de más de 30,000 profesionales de tecnologías de la información hacia el 2025. Asimismo, la Encuesta Nacional de Innovación en la Industria (INEI, 2022) señala que un 37 % de las empresas que desarrollan proyectos de innovación tecnológica han incorporado equipos de desarrollo de software en su estructura, lo cual evidencia la importancia de este grupo como segmento objetivo.

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

#### 4.2.1. EventStorming

#### 4.2.2. Candidate Context Discovery

#### 4.2.3. Domain Message Flows Modeling

#### 4.2.4. Bounded Context Canvases

#### 4.2.5. Context Mapping

### 4.3. Software Architecture

#### 4.3.1. Software Architecture System Landscape Diagram

#### 4.3.2. Software Architecture Context Level Diagrams

#### 4.3.3. Software Architecture Container Level Diagrams

#### 4.3.4. Software Architecture Deployment Diagrams


## Conclusiones


### Conclusiones y recomendaciones


## Bibliografía


## Anexos

