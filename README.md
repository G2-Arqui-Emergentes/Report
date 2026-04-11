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

