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

La presente sección describe la especificación de requisitos del sistema propuesto, elaborada a partir del análisis de la información obtenida durante la etapa de investigación. Su objetivo es definir de manera clara las funcionalidades y características que deberá cumplir el producto digital, considerando las necesidades de los usuarios y el contexto del problema identificado.

Esta sección incluye el desarrollo de distintos artefactos que permiten estructurar la solución, tales como el To-Be Scenario Mapping, las User Stories, el Impact Map y el Product Backlog. Estos elementos facilitan la comprensión del comportamiento esperado del sistema, así como la priorización y organización de los requerimientos, permitiendo orientar el desarrollo bajo un enfoque ágil y centrado en el usuario.

### 3.1. To-Be Scenario Mapping

En esta sección se presenta el To-Be Scenario Mapping, el cual describe el escenario futuro de interacción de los usuarios con el sistema propuesto. Para su elaboración, el equipo siguió un proceso estructurado que incluyó la preparación del análisis, la generación de ideas mediante lluvia de ideas individual, la revisión y consolidación de actividades, así como la identificación y definición de las fases principales del proceso, organizadas como columnas.

Asimismo, se consideraron las dimensiones de Doing, Thinking y Feeling para cada User Persona, permitiendo comprender no solo las acciones que realizan, sino también sus percepciones y emociones durante la interacción con el sistema. Finalmente, el mapa To-Be fue contrastado conceptualmente con el escenario actual (As-Is), identificando mejoras significativas como la incorporación de analítica inteligente y automatización de procesos, las cuales optimizan la gestión de proyectos y la toma de decisiones.

**Segmento 1: Líder o gerente de proyectos de software**

![texto alternativo](assets/TB1/TOBE1.jpg)

**Segmento 2: Miembro de un equipo de desarrollo de software**

![texto alternativo](assets/TB1/tobe2.jpg)

### 3.2. User Stories

| **EPIC(ID)** | **Título**                              | **Descripción**                                                                                                                                                        |
| ------------ | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **EP01**     | **Landing Page**                        | Como visitante, quiero acceder a una página de inicio clara que explique los beneficios de TaskMaster, para evaluar si es adecuado para mis necesidades.               |
| **EP02**     | **Registro y autentificacion de usuario** | Como trabajador, quiero registrarme y verificar mi identidad para acceder a TaskMaster, garantizando que solo personal autorizado pueda acceder a las funcionalidades. |
| **EP03**     | **Gestión de Proyectos y Tareas**       | Como líder de equipo, quiero gestionar proyectos y asignar tareas a los miembros del equipo para distribuir el trabajo de manera organizada.                           |
| **EP04**     | **Visualización y Seguimiento**         | Como miembro del equipo, quiero ver el progreso de mis tareas en tiempo real con indicadores inteligentes de riesgo y alertas, para anticipar retrasos y gestionar mejor mis responsabilidades.                                       |
| **EP05**     | **Analítica y Reportes**                | Como líder de equipo, quiero generar reportes inteligentes mediante inteligencia artificial para analizar el desempeño, predecir riesgos y mejorar la toma de decisiones.                  |
| **EP06**     | **Notificaciones**                      | Como miembro del equipo, quiero recibir notificaciones automatizadas basadas en eventos del sistema, para mantenerme informado y priorizar mi trabajo de manera eficiente.      |
| **EP07**     | **Integraciones Técnicas**              | Como desarrollador, quiero implementar un backend con servicios CRUD (crear, leer, actualizar y eliminar) para proyectos, tareas, usuarios y reportes, de modo que la lógica central de TaskMaster esté estructurada y mantenible  |
| **EP08**     | **Investigación y Validación Técnica**  | Como miembro del equipo de desarrollo, quiero validar la seguridad de TaskMaster mediante pruebas técnicas para garantizar la protección de los datos de los usuarios. |

| **Story ID** | **User**  | **Priority** | **Epic** | **Title**                                        | **Description**                                                                                                                                                           | **Acceptance Criteria**                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------ | --------- | ------------ | -------- | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **US01**     | Visitante | High         | EP01     | Información general sobre TaskMaster             | Como visitante, quiero entender rápidamente los beneficios y características de TaskMaster, para evaluar si se ajusta a mis necesidades.                                  | **ESCENARIO 01:** **DADO** que el visitante accede a la página principal, **CUANDO** hace scroll hacia la sección **Características clave**, **Y** el sistema carga la información correspondiente, **Y** las animaciones se activan al entrar en pantalla, **ENTONCES** el sistema muestra una lista visual destacada con las funciones principales de la aplicación, **Y** el visitante puede identificar fácilmente los beneficios del producto. |
| **US02**     | Visitante | High         | EP01     | Llamado a la acción para descargar la aplicación | Como visitante, quiero tener un botón de registro claro y accesible para descargar la aplicación.                                                                         | **ESCENARIO 01:** **DADO** que el visitante accede a la landing page, **CUANDO** visualiza el botón de registro ubicado en la parte superior o inferior, **Y** el botón está resaltado visualmente, **Y** hace clic sobre él, **ENTONCES** el sistema redirige al visitante a la tienda de aplicaciones correspondiente, **Y** se abre la página de descarga de TaskMaster.                                                                         |
| **US03**     | Visitante | Medium       | EP01     | Testimonios de usuarios                          | Como visitante, quiero ver testimonios de usuarios reales de TaskMaster para confiar en su efectividad.                                                                   | **ESCENARIO 01:** **DADO** que el visitante se encuentra en la página de inicio, **CUANDO** baja hasta la sección de **Testimonios**, **Y** el sistema carga las reseñas de usuarios, **Y** las imágenes y textos se muestran correctamente, **ENTONCES** el sistema presenta los testimonios con texto y fotos de usuarios reales, **Y** genera confianza en la efectividad de la aplicación.                                                      |
| **US04**     | Visitante | Medium       | EP01     | Muestra de planes y precios                      | Como visitante, quiero ver las opciones de planes y precios de TaskMaster para poder elegir el más adecuado.                                                              | **ESCENARIO 01:** **DADO** que el visitante accede a la página principal, **CUANDO** navega hasta la sección de **Planes de suscripción**, **Y** los datos de los planes están disponibles, **Y** el usuario visualiza la comparación entre ellos, **ENTONCES** el sistema muestra los distintos planes con sus características, **Y** cada plan incluye un botón para comparar o seleccionar.                                                      |
| **US05**     | Visitante | Low          | EP01     | Adaptabilidad móvil                              | Como usuario móvil, quiero navegar la landing page sin problemas, para acceder a la información desde cualquier dispositivo.                                              | **ESCENARIO 01:** **DADO** que el usuario accede desde un dispositivo móvil, **CUANDO** hace clic en el ícono del menú principal, **Y** el sistema detecta el tamaño de pantalla reducido, **Y** activa la versión responsive, **ENTONCES** se despliegan las opciones principales en un panel lateral, **Y** el fondo se oscurece para mejorar el contraste.                                                                                       |
| **US06**     | Visitante | Low          | EP01     | Navegación mediante encabezado                   | Como usuario, quiero un menú de navegación claro en el encabezado, para acceder fácilmente a las diferentes secciones de la página.                                       | **ESCENARIO 01:** **DADO** que el visitante explora la plataforma informativa, **CUANDO** utiliza las opciones de navegación del encabezado, **Y** selecciona una sección, **Y** el encabezado permanece visible durante el desplazamiento, **ENTONCES** el sistema redirige al usuario a la sección seleccionada, **Y** mantiene accesible el menú para navegación continua.                                                                       |
| **US07**     | Visitante | Medium       | EP01     | Misión y visión                                  | Como visitante interesado, quiero conocer la visión y misión de la empresa, para entender sus objetivos a largo plazo y su proyección de futuro.                          | **ESCENARIO 01:** **DADO** que el visitante navega por la sección **Sobre la empresa**, **CUANDO** busca información sobre las metas futuras y actuales, **Y** la sección se despliega correctamente, **Y** el contenido es legible, **ENTONCES** el sistema muestra claramente la declaración de **Misión y Visión**, **Y** permite al visitante comprender los objetivos de la empresa.                                                           |
| **US08**     | Visitante | High         | EP01     | About the Team                                   | Como visitante quiero acceder a la sección About the Team para conocer quiénes son los integrantes y su rol en el proyecto.                                               | **ESCENARIO 01:** **DADO** que el visitante accede a la landing page, **CUANDO** hace scroll o selecciona el enlace **About the Team**, **Y** el sistema carga la información del equipo, **Y** las imágenes y textos se renderizan correctamente, **ENTONCES** se muestra una sección con nombres, fotos, roles y una breve descripción de cada integrante, **Y** el visitante puede conocer quiénes conforman el equipo.                          |
| **US09**     | Visitante | Low          | EP01     | Pie de página                                    | Como visitante quiero visualizar un pie de página con enlaces a secciones clave para encontrar fácilmente información adicional y mantenerme conectado con la plataforma. | **ESCENARIO 01:** **DADO** que el visitante llega al final de la landing page, **CUANDO** visualiza el pie de página, **Y** el sistema carga los enlaces de contacto, políticas y redes sociales, **Y** el visitante hace clic sobre uno de ellos, **ENTONCES** el sistema redirige a la sección o recurso correspondiente, **Y** mantiene visible el pie de página en futuras visitas.                                                             |
| **US10**     | Visitante                 | High         | EP02     | Registro de usuario                         | Como visitante quiero registrarme en la plataforma proporcionando mis datos básicos para crear una cuenta y acceder a las funcionalidades de TaskMaster.                                                                            | **ESCENARIO 01:** **DADO** que un visitante proporciona datos válidos en el formulario de registro, **CUANDO** completa todos los campos requeridos, **Y** presiona el botón de registro, **Y** el sistema valida que la información sea correcta, **ENTONCES** se crea una nueva cuenta en la plataforma, **Y** el usuario obtiene acceso a las funcionalidades básicas. <br><br> **ESCENARIO 02:** **DADO** que un visitante intenta registrarse con un correo ya existente, **CUANDO** completa el formulario de registro, **Y** el sistema detecta la duplicidad del correo, **Y** valida los datos ingresados, **ENTONCES** el sistema rechaza la acción, **Y** muestra un mensaje informando que el correo ya está en uso.                                                                                                                                                                                                                                                             |
| **US11**     | Team Member / Team Leader | High         | EP02     | Inicio de sesión                            | Como usuario registrado quiero autenticarme con mis credenciales para acceder a mi cuenta y gestionar mis proyectos.                                                                                                                | **ESCENARIO 01:** **DADO** que un usuario proporciona credenciales válidas, **CUANDO** solicita autenticación, **Y** el sistema valida correctamente los datos, **Y** verifica que la cuenta esté activa, **ENTONCES** se concede el acceso al sistema, **Y** el usuario puede gestionar sus proyectos. <br><br> **ESCENARIO 02:** **DADO** que un usuario proporciona credenciales inválidas, **CUANDO** solicita autenticación, **Y** el sistema verifica los datos, **Y** detecta inconsistencias, **ENTONCES** el sistema rechaza la acción, **Y** muestra un mensaje informando que los datos no son correctos.                                                                                                                                                                                                                                                                                                                                                                         |
| **US12**     | Team Member / Team Leader | Medium       | EP02     | Recuperación de contraseña                  | Como usuario registrado quiero restablecer mi contraseña en caso de olvido para poder acceder nuevamente a la plataforma.                                                                                                           | **ESCENARIO 01:** **DADO** que un usuario solicita restablecer su contraseña con un correo válido, **CUANDO** ingresa su correo electrónico en la sección de recuperación, **Y** el sistema valida que esté registrado, **Y** genera un enlace o código de recuperación, **ENTONCES** el sistema envía el método de restablecimiento, **Y** el usuario puede actualizar su contraseña. <br><br> **ESCENARIO 02:** **DADO** que un usuario solicita restablecer su contraseña con un correo no registrado, **CUANDO** el sistema valida la información ingresada, **Y** no encuentra coincidencias, **Y** verifica la inexistencia de la cuenta, **ENTONCES** el sistema rechaza la acción, **Y** muestra un mensaje informando que no existe cuenta asociada.                                                                                                                                                                                                                                |
| **US13**     | Team Member / Team Leader | Low          | EP02     | Cierre de sesión                            | Como usuario registrado quiero finalizar mi sesión para garantizar la seguridad de mi cuenta en cualquier dispositivo.                                                                                                              | **ESCENARIO 01:** **DADO** que un usuario tiene una sesión activa, **CUANDO** solicita cerrar sesión, **Y** el sistema recibe la solicitud, **Y** verifica las credenciales activas, **ENTONCES** invalida el token de autenticación, **Y** finaliza la sesión correctamente. <br><br> **ESCENARIO 02:** **DADO** que un usuario no tiene una sesión activa, **CUANDO** solicita cerrar sesión, **Y** el sistema valida el estado de autenticación, **Y** detecta la ausencia de sesión, **ENTONCES** el sistema rechaza la acción, **Y** muestra un mensaje indicando que no hay sesión activa.                                                                                                                                                                                                                                                                                                                                                                                             |
| **US14**     | Team Leader               | High         | EP02     | Invitación de usuarios con código de acceso | Como Team Leader, quiero invitar a los usuarios a través de un código de acceso para que se registren y luego puedan ser asignados a tareas dentro de los proyectos, asegurando que solo los usuarios autorizados puedan colaborar. | **ESCENARIO 01:** **DADO** que el Team Leader genera un código de acceso único, **CUANDO** el usuario recibe el código, **Y** ingresa a la plataforma, **Y** lo introduce durante el registro, **ENTONCES** el sistema valida el código, **Y** permite que el usuario se una al proyecto. <br><br> **ESCENARIO 02:** **DADO** que el usuario se ha unido al proyecto mediante el código, **CUANDO** el Team Leader desea asignar tareas, **Y** selecciona participantes del proyecto, **Y** revisa la lista de usuarios válidos, **ENTONCES** el sistema solo muestra a los usuarios que ingresaron con un código de invitación, **Y** permite asignarles tareas. <br><br> **ESCENARIO 03:** **DADO** que el Team Leader intenta invitar a un usuario mediante un código, **CUANDO** el código es inválido o ha caducado, **Y** el sistema verifica su estado, **Y** detecta la invalidez, **ENTONCES** el sistema notifica que el código no es válido, **Y** evita el registro del usuario. |
| **US015**    | Team Leader | High         | EP03     | Registro de nuevos proyectos            | Como líder de equipo quiero crear un nuevo proyecto para organizar las tareas y asignar responsables de manera estructurada.                        | **ESCENARIO 01:** **DADO** que el líder accede a la opción *Crear Proyecto*, **CUANDO** completa los campos requeridos (nombre, descripción y fechas), **Y** revisa que toda la información esté correcta, **Y** presiona el botón *Guardar*, **ENTONCES** el sistema registra el nuevo proyecto en la base de datos, **Y** lo muestra automáticamente en el tablero del líder. <br><br> **ESCENARIO 02:** **DADO** que el líder intenta crear un proyecto sin nombre, **CUANDO** hace clic en *Guardar*, **Y** el sistema valida los campos obligatorios, **Y** detecta que el campo nombre está vacío, **ENTONCES** el sistema muestra un mensaje de error, **Y** no permite continuar con el registro. |
| **US016**    | Team Leader | High         | EP03     | Asignación de usuarios a proyectos      | Como líder de equipo quiero asignar usuarios a un proyecto para que puedan colaborar en sus tareas y actividades.                                   | **ESCENARIO 01:** **DADO** que el líder abre la opción *Asignar Usuarios*, **CUANDO** selecciona varios usuarios del listado, **Y** confirma la acción, **Y** guarda los cambios, **ENTONCES** el sistema asocia a los usuarios seleccionados con el proyecto, **Y** les envía una notificación de incorporación. <br><br> **ESCENARIO 02:** **DADO** que el líder intenta asignar a un usuario que ya pertenece al proyecto, **CUANDO** guarda los cambios, **Y** el sistema valida duplicados, **Y** detecta coincidencia, **ENTONCES** el sistema evita la duplicación, **Y** mantiene la lista correcta de participantes.                                                                             |
| **US017**    | Team Leader | High         | EP03     | Asignar tareas para los usuarios        | Como líder de equipo quiero asignar tareas específicas a los miembros para distribuir la carga de trabajo de forma clara.                           | **ESCENARIO 01:** **DADO** que el líder selecciona una tarea en el tablero, **CUANDO** asigna un usuario responsable, **Y** guarda los cambios, **Y** el sistema valida la existencia del usuario, **ENTONCES** el sistema registra la asignación, **Y** muestra el nombre del responsable en el tablero. <br><br> **ESCENARIO 02:** **DADO** que el líder intenta asignar una tarea a un usuario inexistente, **CUANDO** confirma la acción, **Y** el sistema busca el usuario, **Y** no encuentra coincidencias, **ENTONCES** el sistema muestra un mensaje de error, **Y** no guarda la asignación.                                                                                                    |
| **US018**    | Team Leader | Medium       | EP03     | Establecer prioridad de tareas          | Como líder de equipo quiero asignar prioridades a las tareas dentro de un proyecto para garantizar que las tareas más importantes se hagan primero. | **ESCENARIO 01:** **DADO** que el usuario agrega una nueva tarea, **CUANDO** selecciona una prioridad entre alta, media o baja, **Y** guarda la tarea, **Y** el sistema valida la selección, **ENTONCES** el sistema ordena las tareas del tablero según su nivel de prioridad, **Y** mantiene la organización visual según el valor asignado.                                                                                                                                                                                                                                                                                                                                                            |
| **US019**    | Team Member | High         | EP03     | Notificaciones de tareas asignadas      | Como miembro del equipo, quiero recibir una notificación cuando se me asigna una nueva tarea, para estar al tanto de mis responsabilidades.         | **ESCENARIO 01:** **DADO** que el líder asigna una tarea a un miembro del equipo, **CUANDO** la asignación se confirma, **Y** el sistema registra la tarea, **Y** asocia al responsable, **ENTONCES** el sistema envía una notificación dentro de la aplicación, **Y** también un correo electrónico informando la nueva asignación.                                                                                                                                                                                                                                                                                                                                                                      |
| **US020**    | Team Leader | Medium       | EP03     | Modificación de fechas límite de tareas | Como líder de equipo quiero modificar la fecha límite de las tareas para ajustar los plazos según las necesidades del proyecto.                     | **ESCENARIO 01:** **DADO** que el líder accede a una tarea existente, **CUANDO** modifica la fecha límite, **Y** guarda los cambios, **Y** el sistema valida que la nueva fecha sea posterior a la actual, **ENTONCES** el sistema actualiza la fecha límite de la tarea, **Y** notifica al usuario asignado. <br><br> **ESCENARIO 02:** **DADO** que el líder intenta establecer una fecha límite anterior a la fecha actual, **CUANDO** confirma el cambio, **Y** el sistema compara ambas fechas, **Y** detecta que la nueva es inválida, **ENTONCES** el sistema muestra un mensaje de error, **Y** mantiene la fecha original sin cambios.                                                           |
| **US021**    | Team Leader | Medium       | EP03     | Modificación de la prioridad de tareas  | Como Lider del equipo quiero modificar la prioridad de una tarea para organizar mejor el trabajo según su urgencia e importancia.                 | **ESCENARIO 01:** **DADO** que el usuario accede a la configuración de una tarea, **CUANDO** cambia la prioridad a alta, media o baja, **Y** confirma la acción, **Y** el sistema valida la modificación, **ENTONCES** el sistema actualiza la prioridad de la tarea, **Y** reordena el tablero según el nuevo criterio. <br><br> **ESCENARIO 02:** **DADO** que el usuario intenta guardar una tarea sin seleccionar prioridad, **CUANDO** confirma la acción, **Y** el sistema valida los campos, **Y** detecta ausencia de selección, **ENTONCES** el sistema asigna por defecto la prioridad “Media”, **Y** guarda la tarea exitosamente.                                                             |
| **US022**    | Team Member | Medium       | EP03     | Actualización de estado de tareas       | Como miembro del equipo quiero actualizar el estado de una tarea a completada o pendiente para reflejar con precisión su progreso.                  | **ESCENARIO 01:** **DADO** que un miembro del equipo accede a una tarea asignada, **CUANDO** marca la tarea como completada, **Y** el sistema guarda el cambio, **Y** actualiza el estado, **ENTONCES** el sistema cambia el estado de la tarea a “Completada”, **Y** refleja el cambio visualmente en el tablero. <br><br> **ESCENARIO 02:** **DADO** que un miembro del equipo accede a una tarea, **CUANDO** la desmarca como completada, **Y** el sistema procesa la acción, **Y** actualiza el registro, **ENTONCES** el sistema cambia su estado a “Pendiente”, **Y** lo muestra actualizado en el tablero.                                                                                         |
| **US023**    | Team Member | High         | EP04     | Ver progreso de tareas en tiempo real con indicadores inteligentes | Como miembro del equipo, quiero ver el progreso de las tareas en tiempo real con indicadores inteligentes, para identificar posibles retrasos y actuar a tiempo. | **ESCENARIO 01:** DADO que el usuario accede al tablero de tareas, **CUANDO** consulta las tareas listadas, **Y** visualiza sus estados actuales, **Y** hay cambios en tiempo real, Y el sistema analiza el estado de las tareas mediante lógica inteligente, **ENTONCES** el sistema muestra los indicadores de estado (Pendiente, En progreso, Completada) Y resalta tareas con riesgo de retraso o próximas a vencer **Y** actualiza los avances automáticamente.<br><br>**ESCENARIO 02:** DADO que un miembro del equipo cambia el estado de una tarea (por ejemplo, de “En progreso” a “Completada”), **CUANDO** guarda el cambio, **Y** el sistema procesa la actualización, **Y** recalcula el riesgo de la tarea, **ENTONCES** el progreso se refleja en tiempo real **Y** se actualizan los indicadores de riesgo para todos los usuarios. |
| **US024**    | Team Leader | High         | EP04     | Ver métricas de rendimiento con indicadores de riesgo           | Como líder de equipo, quiero ver métricas de rendimiento con indicadores de riesgo, para identificar posibles problemas en el progreso del proyecto.                   | **ESCENARIO 01:** DADO que el líder accede a la sección de métricas, **CUANDO** solicita un reporte de desempeño, **Y** selecciona un proyecto, **Y** el sistema recopila los datos Y evalúa el comportamiento de las tareas, , **ENTONCES** se genera un gráfico o reporte con tareas completadas, retrasadas y porcentaje de avance Y se muestran indicadores de riesgo (alto, medio, bajo)  **Y** los resultados en pantalla.<br><br>**ESCENARIO 02:** DADO que el líder selecciona un periodo específico (por ejemplo, mensual), **CUANDO** el sistema filtra los datos, **Y** recalcula las métricas, **Y** reanaliza el nivel de riesgo, **ENTONCES** se muestran las métricas actualizadas **Y** los indicadores de riesgo ajustados al periodo.                   |
| **US025**    | Team Member | Medium       | EP04     | Visualizar calendario de tareas con alertas inteligentes       | Como miembro del equipo, quiero ver un calendario con mis tareas y alertas inteligentes, para anticipar entregas y evitar retrasos.                        | **ESCENARIO 01:** DADO que el miembro tiene tareas con fechas límite, **CUANDO** consulta el calendario, **Y** el sistema carga las tareas, **Y** evalúa la proximidad de los plazos, **ENTONCES** se muestran las tareas distribuidas en el calendario **Y** se resaltan aquellas próximas a vencer o en riesgo.<br><br>**ESCENARIO 02:** DADO que el usuario consulta el calendario, **CUANDO** pasa el cursor sobre una tarea, **Y** el sistema detecta la interacción, **Y**analiza el estado de la tarea, **ENTONCES** se muestra un resumen **Y** se incluye una alerta si la tarea presenta riesgo de retraso.                      |
| **US026**    | Team Leader | High         | EP05     | Generar reporte inteligente de desempeño por miembro | Como líder de equipo, quiero generar un reporte inteligente de desempeño por cada miembro del equipo, para identificar áreas de mejora, riesgos y recibir recomendaciones basadas en el análisis de datos.                    | **ESCENARIO 01:** DADO que el líder selecciona la opción **“Generar reporte de desempeño”**, **CUANDO** el sistema procesa la solicitud, **Y** recopila las métricas de cada miembro, **Y** calcula el estado de sus tareas (completadas, en progreso y retrasadas) Y analiza los patrones de desempeño utilizando inteligencia artificial, **ENTONCES** el sistema muestra un reporte detallado **Y** destaca riesgos, nivel de productividad y recomendaciones por integrante.<br><br>**ESCENARIO 02:** DADO que el líder solicita el reporte de desempeño, **CUANDO** el sistema finaliza la generación, **Y** genera insights automáticos, **ENTONCES** el sistema permite exportar el reporte en formato **PDF o Excel** **Y** mantiene las recomendaciones generadas por IA.                                   |
| **US027**    | Team Leader | High         | EP05     | Reporte inteligente de tareas cumplidas y retrasadas | Como líder de equipo, quiero recibir un reporte inteligente de tareas cumplidas y retrasadas, para identificar problemas críticos y anticipar retrasos en el proyecto. | **ESCENARIO 01:** DADO que el líder accede a la sección de reportes, **CUANDO** selecciona “Reporte inteligente de tareas”, **Y** el sistema filtra la información, Y organiza los datos por estado, Y analiza tendencias de retraso utilizando inteligencia artificial, **ENTONCES** se genera un reporte **Y** se muestra el nivel de riesgo del proyecto y predicción de cumplimiento.<br><br>**ESCENARIO 02:** DADO que el reporte se encuentra generado, **CUANDO** el líder selecciona la opción de exportar, **Y** el sistema prepara el archivo, **ENTONCES** el sistema permite exportar el reporte en **PDF o Excel** **Y** conserva los indicadores de riesgo y predicciones generadas por IA.                                         |
| **US028**    | Team Member | Medium       | EP05     | Visualizar resumen semanal inteligente de avances    | Como miembro del equipo, quiero ver un resumen semanal inteligente de mis avances, para entender mi rendimiento y recibir sugerencias de mejora.                    | **ESCENARIO 01:** DADO que el usuario accede a la **sección de reportes**, **CUANDO** selecciona la opción **“Resumen semanal”**, **Y** el sistema obtiene las tareas  **Y** calcula los resultados, Y analiza el progreso mediante inteligencia artificial, **ENTONCES** el sistema muestra un resumen  **Y** proporciona recomendaciones personalizadas para mejorar el desempeño.<br><br>**ESCENARIO 02:** DADO que el usuario selecciona un periodo específico (por ejemplo, de lunes a viernes), **CUANDO** el sistema ajusta el rango de fechas, **Y** filtra las tareas, **Y** recalcula las métricas, Y reanaliza los datos con IA, **ENTONCES** el sistema actualiza el reporte con los datos del periodo elegido **Y** muestra insights adaptados al periodo seleccionado. |
| **US029**    | Team Member | High         | EP06     | Notificación automatizada de tarea asignada            | Como miembro del equipo, quiero recibir una notificación automatizada cuando se me asigne una nueva tarea, para estar al tanto de mis responsabilidades sin intervención manual.                                    | **ESCENARIO 01:** DADO que un **Team Leader asigna una nueva tarea**, **CUANDO** la asignación se confirma, **Y** el sistema valida al usuario destinatario, **Y** la tarea se registra correctamente, Y se ejecuta el flujo automatizado de notificaciones,  **ENTONCES** el sistema envía una **notificación dentro de la app y por correo electrónico** al miembro asignado **Y** actualiza su bandeja de notificaciones.<br><br>**ESCENARIO 02:** DADO que un **Team Leader asigna una tarea**, **CUANDO** revisa la **bandeja de notificaciones**, **Y** el sistema sincroniza la información, **ENTONCES** se muestra la tarea asignada **Y** se prioriza como notificación reciente.                                                                |
| **US030**    | Team Member | High         | EP06     | Notificación automatizada de fecha límite cercana      | Como miembro del equipo, quiero recibir notificaciones automatizadas cuando una tarea esté próxima a vencer, para priorizar mis actividades.                                               | **ESCENARIO 01:** DADO que una **tarea tiene una fecha límite próxima**, **CUANDO** la fecha límite esté a **menos de 24 horas**, **Y** el sistema ejecuta un proceso automático programado, **Y** detecte la proximidad, **ENTONCES** el sistema envía una **notificación dentro de la app y por correo electrónico** **Y** marca la tarea como prioritaria automáticamente.<br><br>**ESCENARIO 02:** DADO que una **tarea está cerca de su fecha límite**, **CUANDO** el sistema analiza los plazos, **Y** detecta tareas críticas automáticamente, **ENTONCES** el sistema **resalta las tareas** **Y** envía una notificación de recordatorio sin intervención del usuario.                           |
| **US031**    | Team Leader | High         | EP06     | Notificación automatizada de tarea completada          | Como líder de equipo, quiero recibir notificaciones automatizadas cuando una tarea se complete, para hacer seguimiento del progreso en tiempo real.                                   | **ESCENARIO 01:** DADO que un **Team Member marca una tarea como completada**, **CUANDO** el sistema procesa el cambio, **Y** actualiza la base de datos, **Y** dispara automáticamente el evento de notificación, **ENTONCES** el sistema **envía una notificación dentro de la app y por correo electrónico** al **Team Leader** **Y** registra el progreso.<br><br>**ESCENARIO 02:** DADO que una tarea ha sido completada, **CUANDO** el sistema sincroniza el tablero, **Y** actualiza el estado automáticamente, **ENTONCES** el líder visualiza el cambio **Y** recibe una notificación en tiempo real.                                |
| **US032**    | Team Member | Medium       | EP06     | Notificación automatizada de mensajes en proyecto | Como miembro del equipo, quiero recibir notificaciones automáticas cuando haya nuevos mensajes, para mantenerme actualizado sin revisar constantemente.                                         | **ESCENARIO 01:** DADO que **un nuevo mensaje es agregado en el proyecto**, **CUANDO** el sistema procesa la comunicación, **Y** guarda el mensaje, **Y** ejecuta el flujo automático de notificación, **ENTONCES** se envía una notificación **Y** actualiza el historial.<br><br>**ESCENARIO 02:** DADO que existen mensajes nuevos, **CUANDO** el **usuario ingresa a la plataforma**, **Y** el sistema carga las notificaciones, **ENTONCES** muestra “nuevo mensaje” **Y** gestiona automáticamente el estado leído/no leído.                   |
| **US033**    | Team Member | Medium       | EP06     | Notificación automatizada de actualización de tareas   | Como miembro del equipo, quiero recibir notificaciones automatizadas cuando una tarea cambie, para estar informado sin necesidad de revisiones manuales. | **ESCENARIO 01:** DADO que el **Team Leader actualiza una tarea**, **CUANDO** el sistema registra el cambio, **Y** detecta automáticamente la modificación, **ENTONCES** el sistema **envía una notificación** **Y** resalta los cambios en la interfaz.<br><br>**ESCENARIO 02:** DADO que una tarea es modificada, **CUANDO** el sistema sincroniza el tablero, **Y** genera indicadores automáticos, **ENTONCES** las tareas se resaltan **Y** se notifica al usuario en tiempo real. |
| **TS01** | Developer | High      | EP08  | Validación de seguridad en la API                | Como desarrollador, quiero verificar que la API de TaskMaster esté segura para proteger los datos de los usuarios.                                         | **DADO** que el equipo de desarrollo realiza pruebas de seguridad sobre la API, **CUANDO** se envían solicitudes con credenciales y datos sensibles, **Y** el sistema procesa dichas solicitudes, **Y** aplica protocolos de encriptación, **ENTONCES** las credenciales deben mantenerse protegidas, **Y** no debe haber filtraciones de información. |
| **TS02** | Developer | High      | EP08  | Optimización del rendimiento de la base de datos | Como desarrollador, quiero mejorar el rendimiento de las consultas en la base de datos para que TaskMaster funcione más rápido.                            | **DADO** que el sistema tiene múltiples consultas activas, **CUANDO** se ejecutan pruebas de carga, **Y** se aplican optimizaciones en los índices y consultas SQL, **Y** se eliminan cuellos de botella, **ENTONCES** el tiempo de respuesta de la base de datos disminuye, **Y** la aplicación responde de manera más eficiente.                     |
| **TS03** | Developer | Alta      | EP08  | Gestión de Proyectos                             | Como desarrollador, quiero implementar la creación, modificación y eliminación de proyectos, para mantener la información organizada y coherente.          | **DADO** que un usuario envía una solicitud válida para crear un proyecto, **CUANDO** la API procesa la petición, **Y** valida los datos, **Y** registra el proyecto en la base de datos, **ENTONCES** el sistema devuelve la información del nuevo proyecto, **Y** confirma su creación exitosa.                                                      |
| **TS04** | Developer | Alta      | EP08  | Gestión de Tareas                                | Como desarrollador, quiero implementar operaciones para registrar, actualizar estados o prioridades, y eliminar tareas, para reflejar el flujo de trabajo. | **DADO** que un usuario modifica el estado o prioridad de una tarea, **CUANDO** la API recibe y procesa la solicitud, **Y** actualiza la información en la base de datos, **Y** mantiene la integridad de los datos, **ENTONCES** el sistema refleja el nuevo estado en la interfaz, **Y** confirma la actualización al usuario.                       |
| **TS05** | Developer | Media     | EP08  | Administración de Usuarios                       | Como desarrollador, quiero implementar el manejo de alta, edición y baja de usuarios, para que roles y permisos se mantengan alineados con los proyectos.  | **DADO** que un administrador solicita eliminar un usuario, **CUANDO** la API procesa la petición, **Y** verifica que el usuario no tenga proyectos activos, **Y** actualiza su estado a inactivo, **ENTONCES** el usuario pierde acceso al sistema, **Y** sus permisos quedan deshabilitados.                                                         |
| **TS06** | Developer | Media     | EP08  | Manejo de Reportes                               | Como desarrollador, quiero implementar la generación, actualización y almacenamiento de reportes, para que los líderes accedan a información consistente.  | **DADO** que un líder solicita un reporte de desempeño, **CUANDO** la API procesa la petición, **Y** consulta las métricas más recientes, **Y** genera el archivo en formato descargable, **ENTONCES** el sistema devuelve el reporte actualizado, **Y** lo almacena para futuras referencias.                                                         |
| **SS1** | Team Member | High      | EP09  | Integración con herramientas de comunicación | Como miembro del equipo, quiero que TaskMaster se integre con Slack para recibir actualizaciones sobre mis tareas, para mantenerme al tanto de los cambios importantes sin tener que acceder continuamente a la plataforma. | **DADO** que el usuario vincula su cuenta de Slack con TaskMaster, **CUANDO** una tarea es asignada o actualizada, **Y** el sistema detecta el cambio, **Y** envía la notificación correspondiente, **ENTONCES** Slack muestra la alerta en el canal indicado, **Y** el usuario se mantiene informado sin ingresar al sistema.             |
| **SS2** | Team Member | High      | EP09  | Integración con Google Calendar              | Como miembro del equipo, quiero que TaskMaster sincronice mis tareas con Google Calendar para no olvidar mis plazos.                                                                                                        | **DADO** que el usuario conecta su cuenta de Google Calendar con TaskMaster, **CUANDO** se crean o modifican tareas con fechas límite, **Y** el sistema valida la autenticación con Google, **Y** ejecuta la sincronización, **ENTONCES** las tareas aparecen en su calendario, **Y** se actualizan automáticamente ante cualquier cambioo. |



### 3.3. Impact Mapping

### 3.4. Product Backlog

| Orden | Código US | Título                                               | Story Points |
|-------|-----------|------------------------------------------------------|--------------|
| 1     | US014     | Invitación de usuarios con código de acceso           | 8 |
| 2     | US015     | Registro de nuevos proyectos                          | 8 |
| 3     | US016     | Asignación de usuarios a proyectos                    | 8 |
| 4     | US017     | Asignar Tareas para los usuarios                      | 8 |
| 5     | US019     | Notificaciones de tareas asignadas                    | 8 |
| 6     | US023     | Ver progreso de tareas en tiempo real con indicadores inteligentes | 8 |
| 7     | US024     | Ver métricas de rendimiento con indicadores de riesgo | 8 |
| 8     | US026     | Generar reporte inteligente de desempeño por miembro  | 8 |
| 9     | US027     | Reporte inteligente de tareas cumplidas y retrasadas  | 8 |
| 10    | US029     | Notificación automatizada de tarea asignada           | 8 |
| 11    | US030     | Notificación automatizada de fecha límite cercana     | 8 |
| 12    | US031     | Notificación automatizada de tarea completada         | 8 |
| 13    | TS01      | Validación de seguridad en la API                     | 8 |
| 14    | TS02      | Optimización del rendimiento de la base de datos      | 8 |
| 15    | TS03      | Gestión de Proyectos (implementación en backend)      | 8 |
| 16    | TS04      | Gestión de Tareas (implementación en backend)         | 8 |
| 17    | SS1       | Integración con herramientas de comunicación (Slack)  | 8 |
| 18    | SS2       | Integración con Google Calendar                       | 8 |
| 19    | US010     | Registro de usuario                                   | 8 |
| 20    | US011     | Inicio de sesión                                      | 8 |
| 21    | US012     | Recuperación de contraseña                            | 5 |
| 22    | US018     | Establecer prioridad de tareas                        | 5 |
| 23    | US020     | Modificación de fechas límite de tareas               | 5 |
| 24    | US021     | Modificación de la prioridad de tareas                | 5 |
| 25    | US022     | Actualización de estado de tareas                     | 5 |
| 26    | US025     | Visualizar calendario de tareas con alertas inteligentes | 5 |
| 27    | US028     | Visualizar resumen semanal inteligente de avances     | 5 |
| 28    | US032     | Notificación automatizada de mensajes en proyecto     | 5 |
| 29    | US033     | Notificación automatizada de actualización de tareas  | 5 |
| 30    | TS05      | Administración de Usuarios (backend)                  | 5 |
| 31    | TS06      | Manejo de Reportes (backend)                          | 5 |
| 32    | US013     | Cierre de sesión                                      | 3 |
| 33    | US05      | Adaptabilidad móvil                                   | 3 |
| 34    | US06      | Navegación mediante Encabezado                        | 3 |
| 35    | US09      | Pie de página                                         | 3 |
| 36    | US01      | Información general sobre TaskMaster                  | 8 |
| 37    | US02      | Llamado a la acción para descargar la aplicación      | 8 |
| 38    | US08      | About the team                                        | 8 |
| 39    | US03      | Testimonios de usuarios                               | 5 |
| 40    | US04      | Muestra de planes y precios                           | 5 |
| 41    | US07      | Misión y visión                                       | 5 |



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

