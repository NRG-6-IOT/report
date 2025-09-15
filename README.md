<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="150" alt="UPC Logo">

# Universidad Peruana de Ciencias Aplicadas

### **CURSO:** Desarrollo de Soluciones IoT

### **NRC**: 3443

### **Profesor:** Ángel Augusto Velásquez Núñez

### **Ingeniería de software**

## Informe de -

### **Nombre del startup:** NRG8

### **Nombre del producto:** -

## **Integrantes**


| **Nombre**                                | **Codigo** |
|-------------------------------------------|------------|
| **Alejo Cardenas Jose Antonio**           | U202122484 |
| **Astonitas Díaz Juan Diego**             | U202110237 |
| **Casas Sanchez Gabriel Alexander**       | U202220033 |
| **Pacheco Astiguetta Sebastian**          | U202110291 |
| **Paitan Pumachuca Max Anthony**          | U201314454 |
| **Pasquale Barrenechea Gianluca Santino** | U202112078 |
| **Real Calderon Sebatian Omar**           | U20221D964 |


**Agosto 2025**

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
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

## Project Report Collaboration Insights

El enlace a github del reporte del proyecto es el siguiente: [https://github.com/NRG-8-IOT/report](https://github.com/NRG-8-IOT/report).

## Contenido

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1 Startup Profile](#11-startup-profile)
        - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2 Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3 Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1 Competidores](#21-competidores)
        - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2 Entrevistas](#22-entrevistas)
        - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3 Needfinding](#23-needfinding)
        - [2.3.1 User Personas](#231-user-personas)
        - [2.3.2 User Task Matrix](#232-user-task-matrix)
        - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4 Empathy Mapping](#234-empathy-mapping)
    - [2.4 Big Picture EventStorming](#24-big-picture-eventstorming)
    - [2.5 Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1 User Stories](#31-user-stories)
    - [3.2 Impact Mapping](#32-impact-mapping)
    - [3.3 Product Backlog](#33-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
    - [4.1 Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
        - [4.1.1 Design-Level EventStorming](#411-design-level-eventstorming)
            - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
            - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
            - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
        - [4.1.2 Context Mapping](#412-context-mapping)
        - [4.1.3 Software Architecture](#413-software-architecture)
            - [4.1.3.1 Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
            - [4.1.3.2 Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
            - [4.1.3.3 Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
            - [4.1.3.4 Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
    - [4.2 Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
        - [4.2.1 Bounded Context: unnamed](#421-bounded-context-unnamed)
            - [4.2.1.1 Domain Layer](#4211-domain-layer)
            - [4.2.1.2 Interface Layer](#4212-interface-layer)
            - [4.2.1.3 Application Layer](#4213-application-layer)
            - [4.2.1.4 Infrastructure Layer](#4214-infrastructure-layer)
            - [4.2.1.5 Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.1.6 Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.1.6.1 Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
                - [4.2.1.6.2 Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

Criterio: *La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.*
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 5.

<table>
  <thead>
    <tr>
      <th style="text-align: left;">Criterio específico</th>
      <th style="text-align: left;">Acciones realizadas</th>
      <th style="text-align: left;">Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Trabaja en equipo para proporcionar liderazgo en forma conjunta</strong></td>
      <td>
        -
      </td>
      <td>
        -
      </td>
    </tr>
    <tr>
      <td><strong>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</strong></td>
      <td>
        -
      </td>
      <td>
        -
      </td>
    </tr>
  </tbody>
</table>

## Capítulo I: Introducción

### 1.1 Startup Profile

#### 1.1.1 Descripción de la Startup

#### 1.1.2 Perfiles de integrantes del equipo

### 1.2 Solution Profile

#### 1.2.1 Antecedentes y problemática

#### 1.2.2 Lean UX Process

##### 1.2.2.1 Lean UX Problem Statements

##### 1.2.2.2 Lean UX Assumptions

##### 1.2.2.3 Lean UX Hypothesis Statements

##### 1.2.2.4 Lean UX Canvas

### 1.3 Segmentos objetivo

## Capítulo II: Requirements Elicitation & Analysis

### 2.1 Competidores

#### 2.1.1 Análisis competitivo

#### 2.1.2 Estrategias y tácticas frente a competidores

### 2.2 Entrevistas

#### 2.2.1 Diseño de entrevistas

#### 2.2.2 Registro de entrevistas

#### 2.2.3 Análisis de entrevistas

### 2.3 Needfinding

#### 2.3.1 User Personas

#### 2.3.2 User Task Matrix

#### 2.3.3 User Journey Mapping

#### 2.3.4 Empathy Mapping

### 2.4 Big Picture EventStorming

### 2.5 Ubiquitous Language

## Capítulo III: Requirements Specification

### 3.1 User Stories

### 3.2 Impact Mapping

### 3.3 Product Backlog

## Capítulo IV: Solution Software Design

### 4.1 Strategic-Level Attribute-Driven Design

En esta sección se aborda el diseño de la arquitectura desde una perspectiva estratégica, aplicando el enfoque Attribute-Driven Design (ADD). Este método permite vincular los objetivos de negocio con las decisiones arquitectónicas, asegurando que la solución no solo responda a los requerimientos funcionales, sino también a atributos de calidad como escalabilidad, mantenibilidad y desempeño. El propósito es establecer una base conceptual sólida que guíe la definición de contextos, interacciones y responsabilidades dentro del dominio del sistema.

#### 4.1.1 Design-Level EventStorming

Para trasladar la estrategia al plano operativo, se utiliza EventStorming como técnica colaborativa de modelado. Esta metodología, centrada en la identificación de eventos de dominio, facilita la exploración profunda del negocio y la detección de flujos críticos de información. A través de dinámicas visuales y participativas, se descubren los límites naturales del dominio y se modelan las interacciones entre actores, comandos y proyecciones. El objetivo es traducir la visión estratégica en un diseño claro, alineado con el lenguaje ubicuo y la realidad operativa del sistema.

##### 4.1.1.1 Candidate Context Discovery

Tras la sesión de EventStorming, aplicando las técnicas de start-with-value y look-for-pivotal-events, el equipo identificó y agrupó los principales eventos del dominio en bounded contexts candidatos. A continuación, se describen los bounded contexts definidos:

**1. Reportes**

* **Propósito:** Elaboración de reportes de métricas de las motos y análisis comparativo de su desempeño.
* **Responsabilidades:**
  * Generar reportes periódicos de métricas.
  * Comparar métricas históricas y actuales.
  * Producir reportes de métricas actualizadas en tiempo real.
* **Eventos clave:** MetricasGeneradas, ReporteSolicitado, ReporteComparado.
* **Valor para el negocio:** Provee visibilidad y soporte a la toma de decisiones del dueño de la moto y de los talleres.

**2. Historiales**

* **Propósito:** Mantener un registro consolidado de todas las actividades y gastos relacionados con la moto.
* **Responsabilidades:**
  * Historial de servicios de los mecánicos.
  * Historial de gastos asociados.
  * Historial de reparaciones realizadas.
  * Historial de clientes atendidos (para mecánicos).
* **Eventos clave:** ServicioRegistrado, GastoRegistrado, ReparacionFinalizada.
* **Valor para el negocio:** Ofrece trazabilidad y respaldo de la información para usuarios y mecánicos.

**3. Suscripción**

* **Propósito:** Gestionar la relación contractual y de conexión entre dueños de motos y mecánicos.
* **Responsabilidades:**
  * Manejar las suscripciones activas.
  * Administrar vínculos de servicio (mecánico ↔ dueño de moto).
  * Controlar renovaciones o cancelaciones de suscripciones.
* **Eventos clave:** SuscripcionCreada, SuscripcionCancelada, MecanicoAsignado.
* **Valor para el negocio:** Garantiza un flujo de ingresos estable y facilita la conexión entre oferta (mecánicos) y demanda (dueños).

**4. Bienestar de Vehículos**

* **Propósito:** Monitorear y gestionar el estado general de la moto a partir de métricas técnicas.
* **Responsabilidades:**
  * Registrar y controlar métricas en tiempo real.
  * Generar alertas preventivas de mantenimiento.
  * Calcular el estado de salud general del vehículo.
* **Eventos clave:** MetricaRegistrada, AlertaGenerada, EstadoActualizado.
* **Valor para el negocio:** Permite anticipar fallas y garantizar mayor seguridad y durabilidad del vehículo.

**5. Gestión de Vehículos**

* **Propósito:** Administrar la información básica y de registro de cada moto en el sistema.
* **Responsabilidades:**
  * Registro de nuevas motos.
  * Acceso a datos técnicos y de propiedad.
  * Actualización de datos generales del vehículo.
* **Eventos clave:** VehiculoRegistrado, DatosVehiculoActualizados.
* **Valor para el negocio:** Provee la base de datos central sobre la cual interactúan los demás contextos.

##### 4.1.1.2 Domain Message Flows Modeling

**Caso 1: Registro de gastos**
1. El dueño de la moto registra un gasto en la aplicación.
2. El contexto de Gestión de Vehículos recibe el evento GastoRegistrado.
3. El contexto de Historiales actualiza el historial del vehículo con el nuevo gasto.
4. El contexto de Reportes genera un reporte actualizado con el nuevo gasto.

**Caso 2: Conexión entre dueño y mecánico**
1. El dueño de la moto solicita una suscripción a un mecánico.
2. El contexto de Suscripción crea una nueva suscripción y emite el evento SuscripcionCreada.
3. El contexto de Gestión de Vehículos actualiza el estado del vehículo con el nuevo mecánico asignado.
4. El contexto de Bienestar de Vehículos comienza a monitorear el vehículo bajo la nueva suscripción.
5. El Historial registra al nuevo mecánico en la cuenta del dueño.

**Caso 3: Alerta preventiva de mantenimiento**
1. El contexto de Bienestar de Vehículos detecta una métrica crítica y genera el evento AlertaGenerada.
2. El contexto de Gestión de Vehículos recibe la alerta y notifica al dueño de la moto.
3. El contexto de Historiales registra la alerta en el historial del vehículo.
4. El contexto de Reportes actualiza los reportes con la nueva alerta.

**Caso 4: Generar reporte de métricas**
1. El dueño de la moto solicita un reporte de métricas.
2. El contexto de Reportes recibe la solicitud y genera el reporte basado en las métricas actuales.
3. El contexto de Bienestar de Vehículos proporciona las métricas necesarias para el reporte.
4. El reporte es entregado al dueño de la moto.

**Caso 5: Agendar servicio con mecánico**
1. El dueño de la moto agenda un servicio con su mecánico a través de la aplicación.
2. El contexto de Suscripción verifica la suscripción activa y emite el evento ServicioAgendado.
3. El contexto de Historiales registra el servicio agendado en el historial del vehículo.
4. El contexto de Gestión de Vehículos actualiza el estado del vehículo con la información del servicio.
5. El mecánico recibe la notificación del servicio agendado.

**Caso 6: Recomendación de cita**
1. El contexto de Bienestar de Vehículos detecta que una métrica ha alcanzado un umbral crítico y genera el evento RecomendacionCitaGenerada.
2. El contexto de Gestión de Vehículos recibe la recomendación y notifica al dueño de la moto.
3. El contexto de Suscripción sugiere al dueño agendar una cita con su mecánico.
4. El Historial registra la recomendación en el historial del vehículo.
5. El dueño de la moto agenda la cita a través de la aplicación.

**Caso 7: Actualización de datos del vehículo**
1. El dueño de la moto actualiza los datos técnicos o de propiedad del vehículo en la aplicación.
2. El contexto de Gestión de Vehículos recibe la actualización y emite el evento DatosVehiculoActualizados.
3. El contexto de Historiales actualiza el historial del vehículo con los nuevos datos.
4. El contexto de Reportes genera un reporte actualizado con la nueva información del vehículo.
5. El contexto de Bienestar de Vehículos ajusta sus parámetros de monitoreo según los nuevos datos.

##### 4.1.1.3 Bounded Context Canvases

En esta sección se desarrollan los Bounded Context Canvases correspondientes a los contextos delimitados previamente durante el proceso de Candidate Context Discovery. El objetivo principal de este apartado es detallar, para cada contexto, los criterios de diseño que permitan comprender su propósito, límites de responsabilidad, capacidades clave, dependencias y reglas de negocio asociadas.

**Reportes**

<img src="images/chapter-4/reports-bc-canvas.png" alt="Reportes Bounded Context Canvas">

**Historiales**

<img src="images/chapter-4/historial-bc-canvas.png" alt="Historiales Bounded Context Canvas">

**Suscripción**

<img src="images/chapter-4/subscription-bc-canvas.png" alt="Suscripción Bounded Context Canvas">

**Bienestar de Vehículos**

<img src="images/chapter-4/health-bc-canvas.png" alt="Bienestar de Vehículos Bounded Context Canvas">

**Gestión de Vehículos**

<img src="images/chapter-4/vehicle-management-bc-canvas.png" alt="Gestión de Vehículos Bounded Context Canvas">

#### 4.1.2 Context Mapping

En esta sección se presenta el proceso de Context Mapping, cuyo propósito es identificar, analizar y documentar las relaciones estructurales entre los bounded contexts previamente definidos. El objetivo es comprender cómo interactúan, cuáles son sus dependencias y qué patrones de integración de Domain-Driven Design son más adecuados.

<img src="images/chapter-4/context-mapping.png" alt="Context Mapping">

| **Contexto A**       | **Contexto B**         | **Relación (DDD)**          | **Justificación**                                                                                                  |
|----------------------|------------------------|-----------------------------|--------------------------------------------------------------------------------------------------------------------|
| Gestión de Vehículos | Bienestar de Vehículos | Customer/Supplier           | El estado de bienestar depende de la información estructural de los vehículos, como mantenimientos o revisiones.   |
| Gestión de Vehículos | Suscripción            | Customer/Supplier           | Las suscripciones requieren la información base de los vehículos para activar planes y beneficios asociados.       |
| Historiales          | Bienestar de Vehículos | Conformist                  | Historiales se adapta al modelo de Bienestar de Vehículos, siguiendo su esquema para registrar datos consistentes. |
| Historiales          | Gestión de Vehículos   | Customer/Supplier           | Los historiales se construyen a partir de la información de los vehículos, consumiendo sus datos.                  |
| Reportes             | Historiales            | Shared Kernel               | Ambos comparten datos e interpretación de eventos históricos para garantizar consistencia en los reportes.         |
| Reportes             | Suscripción            | Anti-Corruption Layer (ACL) | Se aísla el modelo de Reportes de la complejidad de Suscripción mediante una capa de traducción.                   |

#### 4.1.3 Software Architecture

La arquitectura de software de la solución se ha representado utilizando el modelo C4, el cual permite visualizar la estructura en diferentes niveles de abstracción. Se incluyen los diagramas de System Landscape, System Context y Container Level, con el fin de mostrar desde la visión global del ecosistema hasta la organización interna de la aplicación. Para su elaboración se empleó la herramienta Structurizr, que sigue los lineamientos de C4 Model.

##### 4.1.3.1 Software Architecture System Landscape Diagram

<img src="images/chapter-4/system-landscape-diagram.png" alt="System Landscape Diagram">

##### 4.1.3.2 Software Architecture Context Level Diagrams

<img src="images/chapter-4/system-context-diagram.png" alt="System Context Diagram">

##### 4.1.3.3 Software Architecture Container Level Diagrams

<img src="images/chapter-4/system-container-diagram.png" alt="System Context Diagram">

##### 4.1.3.4 Software Architecture Deployment Diagrams

### 4.2 Tactical-Level Domain-Driven Design

#### 4.2.1 Bounded Context: Gestión de Vehículos

##### 4.2.1.1 Domain Layer

##### 4.2.1.2 Interface Layer

##### 4.2.1.3 Application Layer

##### 4.2.1.4 Infrastructure Layer

##### 4.2.1.5 Bounded Context Software Architecture Component Level Diagrams

##### 4.2.1.6 Bounded Context Software Architecture Code Level Diagrams

###### 4.2.1.6.1 Bounded Context Domain Layer Class Diagrams

###### 4.2.1.6.2 Bounded Context Database Design Diagram

#### 4.2.2 Bounded Context: Historiales

##### 4.2.2.1 Domain Layer

##### 4.2.2.2 Interface Layer

##### 4.2.2.3 Application Layer

##### 4.2.2.4 Infrastructure Layer

##### 4.2.2.5 Bounded Context Software Architecture Component Level Diagrams

##### 4.2.2.6 Bounded Context Software Architecture Code Level Diagrams

###### 4.2.2.6.1 Bounded Context Domain Layer Class Diagrams

###### 4.2.2.6.2 Bounded Context Database Design Diagram

#### 4.2.3 Bounded Context: Suscripción

##### 4.2.3.1 Domain Layer

##### 4.2.3.2 Interface Layer

##### 4.2.3.3 Application Layer

##### 4.2.3.4 Infrastructure Layer

##### 4.2.3.5 Bounded Context Software Architecture Component Level Diagrams

##### 4.2.3.6 Bounded Context Software Architecture Code Level Diagrams

###### 4.2.3.6.1 Bounded Context Domain Layer Class Diagrams

###### 4.2.3.6.2 Bounded Context Database Design Diagram

#### 4.2.4 Bounded Context: Bienestar de Vehículos

##### 4.2.4.1 Domain Layer

<h3>Aggregate: <code>VehicleWellness</code></h3>
<p><strong>Descripción:</strong> Representa el bienestar general de una motocicleta, centralizando las métricas capturadas por el dispositivo IoT, generando alertas preventivas y diagnósticos asociados al estado del vehículo.</p>

<table>
  <thead>
    <tr><th>Atributos</th><th>Tipo de dato</th><th>Visibilidad</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>id</td><td>Long</td><td>Private</td><td>Identificador único del registro de bienestar del vehículo.</td></tr>
    <tr><td>vehicleId</td><td>Long</td><td>Private</td><td>Identificador único de la moto asociada.</td></tr>
    <tr><td>metrics</td><td>List&lt;Metric&gt;</td><td>Private</td><td>Lista de métricas recopiladas en tiempo real por el IoT.</td></tr>
    <tr><td>alerts</td><td>List&lt;PreventiveAlert&gt;</td><td>Private</td><td>Alertas generadas automáticamente a partir de anomalías en las métricas.</td></tr>
    <tr><td>diagnostics</td><td>List&lt;Diagnostic&gt;</td><td>Private</td><td>Diagnósticos calculados con base en la interpretación de métricas.</td></tr>
    <tr><td>status</td><td>VehicleStatus (Enum)</td><td>Private</td><td>Estado general del vehículo (Óptimo, Regular, Crítico).</td></tr>
    <tr><td>createdAt</td><td>Timestamp</td><td>Private</td><td>Fecha de creación del registro.</td></tr>
    <tr><td>updatedAt</td><td>Timestamp</td><td>Private</td><td>Fecha de última actualización del registro.</td></tr>
  </tbody>
</table>

<table>
  <thead>
    <tr><th>Métodos</th><th>Tipo de retorno</th><th>Visibilidad</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>getId()</td><td>Long</td><td>Public</td><td>Devuelve el identificador único del registro de bienestar.</td></tr>
    <tr><td>getVehicleId()</td><td>Long</td><td>Public</td><td>Devuelve el identificador de la moto asociada.</td></tr>
    <tr><td>getMetrics()</td><td>List&lt;Metric&gt;</td><td>Public</td><td>Devuelve la lista de métricas registradas.</td></tr>
    <tr><td>getAlerts()</td><td>List&lt;PreventiveAlert&gt;</td><td>Public</td><td>Devuelve las alertas generadas.</td></tr>
    <tr><td>getDiagnostics()</td><td>List&lt;Diagnostic&gt;</td><td>Public</td><td>Devuelve los diagnósticos calculados.</td></tr>
    <tr><td>getStatus()</td><td>VehicleStatus</td><td>Public</td><td>Devuelve el estado general actual del vehículo.</td></tr>
    <tr><td>updateMetrics(Metric metric)</td><td>void</td><td>Public</td><td>Agrega una nueva métrica al registro y actualiza el estado del vehículo.</td></tr>
    <tr><td>generateAlert(Metric metric)</td><td>PreventiveAlert</td><td>Private</td><td>Genera una alerta preventiva si la métrica sobrepasa un umbral crítico.</td></tr>
    <tr><td>generateDiagnostic()</td><td>Diagnostic</td><td>Private</td><td>Genera un diagnóstico a partir de las métricas actuales.</td></tr>
    <tr><td>updateStatus()</td><td>void</td><td>Private</td><td>Actualiza el estado general del vehículo según las métricas recientes.</td></tr>
  </tbody>
</table>

---

<h3>Entity: <code>Metric</code></h3>
<p><strong>Descripción:</strong> Representa un dato capturado por el dispositivo IoT, asociado al estado de la moto (ejemplo: temperatura, velocidad, kilometraje, nivel de combustible).</p>

<table>
  <thead>
    <tr><th>Atributos</th><th>Tipo de dato</th><th>Visibilidad</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>id</td><td>Long</td><td>Private</td><td>Identificador único de la métrica.</td></tr>
    <tr><td>vehicleId</td><td>Long</td><td>Private</td><td>Identificador de la moto asociada.</td></tr>
    <tr><td>type</td><td>String</td><td>Private</td><td>Tipo de métrica (temperatura, kilometraje, velocidad, combustible, etc.).</td></tr>
    <tr><td>value</td><td>Double</td><td>Private</td><td>Valor registrado de la métrica.</td></tr>
    <tr><td>unit</td><td>String</td><td>Private</td><td>Unidad de medida (°C, km, km/h, L, %).</td></tr>
    <tr><td>capturedAt</td><td>Timestamp</td><td>Private</td><td>Fecha y hora de captura.</td></tr>
  </tbody>
</table>

<table>
  <thead>
    <tr><th>Métodos</th><th>Tipo de retorno</th><th>Visibilidad</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>getType()</td><td>String</td><td>Public</td><td>Devuelve el tipo de métrica.</td></tr>
    <tr><td>getValue()</td><td>Double</td><td>Public</td><td>Devuelve el valor de la métrica.</td></tr>
    <tr><td>getUnit()</td><td>String</td><td>Public</td><td>Devuelve la unidad de medida de la métrica.</td></tr>
    <tr><td>getCapturedAt()</td><td>Timestamp</td><td>Public</td><td>Devuelve la fecha y hora de la captura.</td></tr>
  </tbody>
</table>

---

<h3>Entity: <code>PreventiveAlert</code></h3>
<p><strong>Descripción:</strong> Representa una alerta emitida automáticamente cuando una métrica sobrepasa los valores críticos establecidos.</p>

<table>
  <thead>
    <tr><th>Atributos</th><th>Tipo de dato</th><th>Visibilidad</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>id</td><td>Long</td><td>Private</td><td>Identificador único de la alerta.</td></tr>
    <tr><td>vehicleId</td><td>Long</td><td>Private</td><td>Identificador de la moto asociada.</td></tr>
    <tr><td>metricType</td><td>String</td><td>Private</td><td>Tipo de métrica que generó la alerta.</td></tr>
    <tr><td>message</td><td>String</td><td>Private</td><td>Mensaje descriptivo de la alerta.</td></tr>
    <tr><td>severity</td><td>String</td><td>Private</td><td>Nivel de severidad (Alto, Medio, Bajo).</td></tr>
    <tr><td>createdAt</td><td>Timestamp</td><td>Private</td><td>Fecha y hora de la alerta.</td></tr>
  </tbody>
</table>

---

<h3>Entity: <code>Diagnostic</code></h3>
<p><strong>Descripción:</strong> Representa la interpretación de un conjunto de métricas para indicar posibles fallas, recomendaciones o el estado de la moto.</p>

<table>
  <thead>
    <tr><th>Atributos</th><th>Tipo de dato</th><th>Visibilidad</th><th>Descripción</th></tr>
  </thead>
  <tbody>
    <tr><td>id</td><td>Long</td><td>Private</td><td>Identificador único del diagnóstico.</td></tr>
    <tr><td>vehicleId</td><td>Long</td><td>Private</td><td>Identificador de la moto asociada.</td></tr>
    <tr><td>summary</td><td>String</td><td>Private</td><td>Resumen breve del diagnóstico.</td></tr>
    <tr><td>recommendations</td><td>String</td><td>Private</td><td>Recomendaciones para el usuario o mecánico.</td></tr>
    <tr><td>createdAt</td><td>Timestamp</td><td>Private</td><td>Fecha y hora de generación del diagnóstico.</td></tr>
  </tbody>
</table>

##### 4.2.4.2 Interface Layer

<h3>Controlador: <code>VehicleWellnessController</code></h3>

<table>
  <tr>
    <th>Título</th>
    <td>VehicleWellnessController</td>
  </tr>
  <tr>
    <th>Descripción</th>
    <td>Controlador REST que maneja las operaciones relacionadas con el monitoreo del bienestar del vehículo, incluyendo métricas, alertas y diagnósticos.</td>
  </tr>
</table>

<table>
  <thead>
    <tr>
      <th>Método</th>
      <th>Ruta</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>getVehicleWellnessById</td>
      <td>GET /api/v1/wellness/{vehicleId}</td>
      <td>Obtiene el estado general del bienestar de un vehículo específico por su ID</td>
    </tr>
    <tr>
      <td>getVehicleMetrics</td>
      <td>GET /api/v1/wellness/{vehicleId}/metrics</td>
      <td>Obtiene las métricas en tiempo real de un vehículo</td>
    </tr>
    <tr>
      <td>getVehicleAlerts</td>
      <td>GET /api/v1/wellness/{vehicleId}/alerts</td>
      <td>Obtiene todas las alertas preventivas activas de un vehículo</td>
    </tr>
    <tr>
      <td>generateDiagnosis</td>
      <td>POST /api/v1/wellness/{vehicleId}/diagnosis</td>
      <td>Genera un diagnóstico automático basado en las métricas actuales</td>
    </tr>
    <tr>
      <td>updateMetric</td>
      <td>PUT /api/v1/wellness/{vehicleId}/metrics</td>
      <td>Actualiza las métricas de un vehículo enviadas por el dispositivo IoT</td>
    </tr>
    <tr>
      <td>deleteWellnessData</td>
      <td>DELETE /api/v1/wellness/{vehicleId}</td>
      <td>Elimina los datos históricos de bienestar de un vehículo</td>
    </tr>
  </tbody>
</table>

<h4>Dependencias:</h4>

<table>
  <thead>
    <tr>
      <th>Dependencia</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>VehicleWellnessQueryService</td>
      <td>Servicio para consultas y recuperación de datos sobre métricas, alertas y estado general del vehículo</td>
    </tr>
    <tr>
      <td>VehicleWellnessCommandService</td>
      <td>Servicio para ejecutar comandos de actualización de métricas y generación de diagnósticos</td>
    </tr>
    <tr>
      <td>CreateDiagnosisCommandFromResourceAssembler</td>
      <td>Convierte recursos REST en comandos de generación de diagnósticos</td>
    </tr>
    <tr>
      <td>UpdateMetricCommandFromResourceAssembler</td>
      <td>Convierte recursos REST en comandos de actualización de métricas</td>
    </tr>
    <tr>
      <td>DeleteWellnessCommandFromResourceAssembler</td>
      <td>Convierte recursos REST en comandos de eliminación de registros de bienestar</td>
    </tr>
    <tr>
      <td>VehicleWellnessResourceFromEntityAssembler</td>
      <td>Convierte entidades de bienestar del vehículo en recursos REST para la respuesta</td>
    </tr>
  </tbody>
</table>

##### 4.2.4.3 Application Layer

<hr>
<h3>Clase: <code>VehicleWellnessQueryServiceImpl</code></h3>
<table>
  <tr>
    <th>Título</th>
    <td>VehicleWellnessQueryServiceImpl</td>
  </tr>
  <tr>
    <th>Descripción</th>
    <td>Implementación del servicio de consultas para operaciones de lectura relacionadas con el bienestar del vehículo</td>
  </tr>
</table>
<table>
  <thead>
    <tr>
      <th>Método</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>handle(GetVehicleWellnessByIdQuery)</td>
      <td>Obtiene el estado general del bienestar de un vehículo por su ID</td>
    </tr>
    <tr>
      <td>handle(GetVehicleMetricsQuery)</td>
      <td>Devuelve la lista de métricas asociadas a un vehículo</td>
    </tr>
    <tr>
      <td>handle(GetVehicleAlertsQuery)</td>
      <td>Obtiene todas las alertas preventivas activas de un vehículo</td>
    </tr>
    <tr>
      <td>handle(GetVehicleDiagnosticsQuery)</td>
      <td>Devuelve todos los diagnósticos históricos de un vehículo</td>
    </tr>
  </tbody>
</table>
<h4>Dependencias:</h4>
<table>
  <thead>
    <tr>
      <th>Dependencia</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>VehicleWellnessRepository</td>
      <td>Repositorio para acceso a datos de bienestar de vehículos</td>
    </tr>
    <tr>
      <td>GetVehicleWellnessByIdQuery</td>
      <td>Query para obtener el estado de un vehículo</td>
    </tr>
    <tr>
      <td>GetVehicleMetricsQuery</td>
      <td>Query para recuperar métricas de un vehículo</td>
    </tr>
    <tr>
      <td>GetVehicleAlertsQuery</td>
      <td>Query para recuperar alertas preventivas</td>
    </tr>
    <tr>
      <td>GetVehicleDiagnosticsQuery</td>
      <td>Query para recuperar diagnósticos del vehículo</td>
    </tr>
  </tbody>
</table>
<hr>
<h3>Clase: <code>VehicleWellnessCommandServiceImpl</code></h3>
<table>
  <tr>
    <th>Título</th>
    <td>VehicleWellnessCommandServiceImpl</td>
  </tr>
  <tr>
    <th>Descripción</th>
    <td>Implementación del servicio de comandos para operaciones de escritura relacionadas con el bienestar del vehículo</td>
  </tr>
</table>
<table>
  <thead>
    <tr>
      <th>Método</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>handle(UpdateMetricCommand)</td>
      <td>Agrega o actualiza una métrica en el registro de bienestar del vehículo</td>
    </tr>
    <tr>
      <td>handle(GenerateDiagnosisCommand)</td>
      <td>Genera un diagnóstico basado en las métricas actuales del vehículo</td>
    </tr>
    <tr>
      <td>handle(CreateAlertCommand)</td>
      <td>Genera una alerta preventiva si se detecta una anomalía en las métricas</td>
    </tr>
    <tr>
      <td>handle(DeleteWellnessDataCommand)</td>
      <td>Elimina los datos históricos de bienestar de un vehículo</td>
    </tr>
  </tbody>
</table>
<h4>Dependencias:</h4>
<table>
  <thead>
    <tr>
      <th>Dependencia</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>VehicleWellnessRepository</td>
      <td>Repositorio para acceso y persistencia de bienestar de vehículos</td>
    </tr>
    <tr>
      <td>NotificationService</td>
      <td>Servicio para enviar notificaciones relacionadas con alertas preventivas</td>
    </tr>
    <tr>
      <td>UpdateMetricCommand</td>
      <td>Comando para actualizar o agregar métricas</td>
    </tr>
    <tr>
      <td>GenerateDiagnosisCommand</td>
      <td>Comando para generar diagnósticos</td>
    </tr>
    <tr>
      <td>CreateAlertCommand</td>
      <td>Comando para generar alertas preventivas</td>
    </tr>
    <tr>
      <td>DeleteWellnessDataCommand</td>
      <td>Comando para eliminar registros de bienestar</td>
    </tr>
  </tbody>
</table>

##### 4.2.4.4 Infrastructure Layer

<h3>Clase: <code>VehicleWellnessRepository</code></h3>
<table>
  <tr>
    <th>Título</th>
    <td>VehicleWellnessRepository</td>
  </tr>
  <tr>
    <th>Descripción</th>
    <td>Interfaz de persistencia para operaciones CRUD y consultas específicas relacionadas con el bienestar del vehículo</td>
  </tr>
</table>
<table>
  <thead>
    <tr>
      <th>Método</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>save(VehicleWellness)</td>
      <td>Persiste un nuevo registro de bienestar del vehículo o actualiza uno existente</td>
    </tr>
    <tr>
      <td>deleteByVehicleId(Long vehicleId)</td>
      <td>Elimina los registros de bienestar asociados a un vehículo</td>
    </tr>
    <tr>
      <td>findByVehicleId(Long vehicleId)</td>
      <td>Obtiene el estado general de bienestar de un vehículo específico</td>
    </tr>
    <tr>
      <td>existsByVehicleId(Long vehicleId)</td>
      <td>Verifica si existe un registro de bienestar para un vehículo</td>
    </tr>
    <tr>
      <td>findMetricsByVehicleId(Long vehicleId)</td>
      <td>Obtiene todas las métricas asociadas a un vehículo</td>
    </tr>
    <tr>
      <td>findAlertsByVehicleId(Long vehicleId)</td>
      <td>Obtiene todas las alertas preventivas asociadas a un vehículo</td>
    </tr>
    <tr>
      <td>findDiagnosticsByVehicleId(Long vehicleId)</td>
      <td>Obtiene todos los diagnósticos históricos de un vehículo</td>
    </tr>
  </tbody>
</table>

<h3>Clase: <code>MetricRepository</code></h3>
<table>
  <tr>
    <th>Título</th>
    <td>MetricRepository</td>
  </tr>
  <tr>
    <th>Descripción</th>
    <td>Interfaz de persistencia para operaciones CRUD sobre métricas registradas por el dispositivo IoT</td>
  </tr>
</table>
<table>
  <thead>
    <tr>
      <th>Método</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>save(Metric)</td>
      <td>Persiste una nueva métrica o actualiza una existente</td>
    </tr>
    <tr>
      <td>findById(Long id)</td>
      <td>Recupera una métrica específica por su identificador</td>
    </tr>
    <tr>
      <td>findByVehicleId(Long vehicleId)</td>
      <td>Obtiene todas las métricas asociadas a un vehículo</td>
    </tr>
    <tr>
      <td>findLatestByVehicleId(Long vehicleId)</td>
      <td>Obtiene la última métrica registrada de un vehículo</td>
    </tr>
    <tr>
      <td>deleteByVehicleId(Long vehicleId)</td>
      <td>Elimina todas las métricas asociadas a un vehículo</td>
    </tr>
  </tbody>
</table>

<h3>Clase: <code>PreventiveAlertRepository</code></h3>
<table>
  <tr>
    <th>Título</th>
    <td>PreventiveAlertRepository</td>
  </tr>
  <tr>
    <th>Descripción</th>
    <td>Interfaz de persistencia para gestionar alertas preventivas generadas automáticamente a partir de métricas</td>
  </tr>
</table>
<table>
  <thead>
    <tr>
      <th>Método</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>save(PreventiveAlert)</td>
      <td>Persiste una nueva alerta preventiva</td>
    </tr>
    <tr>
      <td>findByVehicleId(Long vehicleId)</td>
      <td>Obtiene todas las alertas asociadas a un vehículo</td>
    </tr>
    <tr>
      <td>findActiveByVehicleId(Long vehicleId)</td>
      <td>Obtiene únicamente las alertas activas de un vehículo</td>
    </tr>
    <tr>
      <td>deleteByVehicleId(Long vehicleId)</td>
      <td>Elimina todas las alertas asociadas a un vehículo</td>
    </tr>
  </tbody>
</table>

<h3>Clase: <code>DiagnosticRepository</code></h3>
<table>
  <tr>
    <th>Título</th>
    <td>DiagnosticRepository</td>
  </tr>
  <tr>
    <th>Descripción</th>
    <td>Interfaz de persistencia para operaciones CRUD sobre diagnósticos generados a partir de métricas</td>
  </tr>
</table>
<table>
  <thead>
    <tr>
      <th>Método</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>save(Diagnostic)</td>
      <td>Persiste un nuevo diagnóstico</td>
    </tr>
    <tr>
      <td>findById(Long id)</td>
      <td>Recupera un diagnóstico específico</td>
    </tr>
    <tr>
      <td>findByVehicleId(Long vehicleId)</td>
      <td>Obtiene todos los diagnósticos asociados a un vehículo</td>
    </tr>
    <tr>
      <td>findLatestByVehicleId(Long vehicleId)</td>
      <td>Obtiene el diagnóstico más reciente de un vehículo</td>
    </tr>
    <tr>
      <td>deleteByVehicleId(Long vehicleId)</td>
      <td>Elimina todos los diagnósticos asociados a un vehículo</td>
    </tr>
  </tbody>
</table>

##### 4.2.4.5 Bounded Context Software Architecture Component Level Diagrams

##### 4.2.4.6 Bounded Context Software Architecture Code Level Diagrams

###### 4.2.4.6.1 Bounded Context Domain Layer Class Diagrams

###### 4.2.4.6.2 Bounded Context Database Design Diagram

#### 4.2.5 Bounded Context: Reportes

##### 4.2.5.1 Domain Layer

##### 4.2.5.2 Interface Layer

##### 4.2.5.3 Application Layer

##### 4.2.5.4 Infrastructure Layer

##### 4.2.5.5 Bounded Context Software Architecture Component Level Diagrams

##### 4.2.5.6 Bounded Context Software Architecture Code Level Diagrams

###### 4.2.5.6.1 Bounded Context Domain Layer Class Diagrams

###### 4.2.5.6.2 Bounded Context Database Design Diagram

## Conclusiones

## Bibliografía

## Anexos
