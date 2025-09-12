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

Epicas:

| **ID**   | **Título**                                              | **Descripción** |
|----------|----------------------------------------------------------|-----------------|
| **EP-001** | Monitoreo inteligente del estado de la moto | Desarrollar una aplicación móvil que permita a los motociclistas monitorear en tiempo real las métricas clave de su motocicleta, tales como el estado de la batería, kilometraje, consumo de combustible, temperatura del motor, presión de neumáticos y niveles de vibración. Esta funcionalidad busca empoderar al usuario con datos claros, visuales y accesibles desde el celular, mejorando su capacidad para tomar decisiones informadas y prevenir fallas inesperadas durante el uso diario. |
| **EP-002** | Sistema de alertas preventivas y recordatorios automatizados | Implementar un sistema automatizado de alertas y recordatorios tanto para motociclistas como para talleres, que notifique sobre mantenimientos próximos, condiciones críticas detectadas por el sistema de telemetría, o fallas recurrentes. Estas alertas deben llegar a través de canales integrados y habituales, como notificaciones en la app para los mecánicos, con el objetivo de mejorar la prevención de fallos, reducir el riesgo de accidentes y mantener una agenda clara de servicios futuros. Esta épica responde directamente a la necesidad de anticiparse a problemas y evitar gastos innecesarios. |
| **EP-003** | Gestión del historial de mantenimiento y gastos | Desarrollar funcionalidades que permitan al usuario y al taller llevar un registro estructurado del historial de mantenimiento de cada motocicleta, así como los costos asociados a reparaciones, repuestos y servicios realizados. Esta información debe visualizarse mediante reportes claros y simples (mensuales o por evento), y estar disponible tanto para el dueño de la moto como para el mecánico, fomentando la transparencia, planificación y fidelización del cliente. La funcionalidad busca reemplazar métodos manuales (como libretas o la memoria) por una solución digital accesible y confiable. |
| **EP-004** | Desarrollo e integración del dispositivo embebido de telemetría | Diseñar, fabricar e integrar un dispositivo IoT embebido que recolecte en tiempo real los datos críticos del funcionamiento de la motocicleta —como batería, consumo, temperatura, vibración y kilometraje— y los transmita de forma segura a la plataforma digital. Esta épica implica el desarrollo de firmware, pruebas de sensores, aseguramiento de la compatibilidad con distintos modelos de motos (principalmente eléctricas y urbanas), y validación de la estabilidad de conexión con la app mediante protocolos eficientes (BLE, WiFi o LoRa según la arquitectura definida). Es el componente técnico clave que conecta el mundo físico de la motocicleta con la experiencia digital del usuario. |
| **EP-005** | Gestión de relación entre motociclista y mecánico | Funcionalidades que involucren la creación y administración de una relación entre un usuario y su mecánico de preferencia. Permitiendo al usuario otorgarle acceso a un mecánico para visualizar las métricas de su motocicleta en tiempo real, y recibir notificaciones de este. Así mismo estas relaciones pueden romperse o cambiarse según las necesidades del usuario y/o del mecánico. |

User Stories:

| User Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| US-001 | Visualización del consumo de combustible en tiempo real | Como motociclista, quiero visualizar en tiempo real el consumo de combustible de mi moto, para poder optimizar mi forma de conducir y ahorrar gastos. | Escenario 1: Dado que el motociclista está usando la aplicación en la moto en marcha, cuando consulte el panel de métricas, entonces el sistema mostrará el consumo de combustible actual (L/100km o km/L). <br> Escenario 2: Dado que el motociclista ha realizado un recorrido, cuando revise el resumen del viaje, entonces el sistema mostrará el consumo promedio de combustible durante ese trayecto. | EP-001 |
| US-002 | Registro de gastos de mantenimiento y repuestos | Como motociclista, quiero registrar los gastos de mantenimiento y repuestos que realizo, para llevar un control acumulado mensual o por kilometraje. | Escenario 1: Dado que el motociclista accede a la sección de gastos, cuando registre un gasto con monto, descripción y fecha, entonces el sistema lo guardará y actualizará el acumulado mensual y por kilometraje. <br> Escenario 2: Dado que el motociclista revisa sus métricas, cuando consulte el historial de gastos, entonces podrá ver el total invertido filtrado por mes, tipo de gasto o kilometraje. | EP-001 |
| US-003 | Acceso al historial de servicios realizados | Como motociclista, quiero acceder fácilmente al historial de servicios realizados en mi moto, para saber cuándo fue la última vez que hice mantenimiento y qué se reparó. | Escenario 1: Dado que el motociclista entra al historial de mantenimiento, cuando seleccione una entrada, entonces podrá ver la fecha, tipo de servicio, taller y repuestos utilizados. <br> Escenario 2: Dado que el motociclista visualiza el historial, cuando busque por fecha o tipo de servicio, entonces el sistema filtrará y mostrará los resultados correspondientes. | EP-001 |
| US-004 | Comparación de métricas entre motos similares | Como mecánico, quiero comparar las métricas de dos motos similares, para detectar posibles problemas o desviaciones en el rendimiento que requieran revisión. | Escenario 1: Dado que el mecánico accede a la herramienta de comparación, cuando seleccione dos motos del mismo modelo, entonces el sistema mostrará una comparación lado a lado de consumo, temperatura, kilometraje y alertas. <br> Escenario 2: Dado que una diferencia significativa sea detectada, cuando la comparación finalice, entonces el sistema sugerirá una posible causa o una recomendación de diagnóstico. | EP-001 |
| US-005 | Notificación de alerta por consumo excesivo. | Como motociclista, quiero que el aplicativo móvil me notifique en caso de que el sistema detecte un consumo anormalmente alto de combustible por kilómetro. | Escenario 1: <br>Dado que el sistema detecta que el consumo de combustible durante un trayecto es anormalmente alto, cuando este se mantenga en este estado por un tiempo medianamente prolongado, entonces el sistema deberá emitir una notificación de alerta para avisar al usuario. <br> <br> Escenario 2: <br>Dado que el sistema detecta que el consumo de combustible ha vuelto a niveles normales después de una alerta previa, <br> cuando el consumo se mantenga estable en ese rango durante un tiempo prudente, <br> entonces el sistema deberá notificar al usuario que el consumo se ha normalizado y la alerta ya no está activa. | EP-002 |
| US-006 | Notificación de alerta por presión de llantas. | Como motociclista, <br>quiero que el aplicativo móvil me notifique cuando la presión de las llantas sea anormal, <br>para poder tomar acciones preventivas que garanticen mi seguridad y el buen estado de la motocicleta. | Escenario 1: <br>Dado que el sistema detecta que la presión de una o más llantas es más baja de lo recomendado, <br>cuando esta condición se mantenga durante un tiempo determinado, <br>entonces el sistema deberá emitir una notificación de alerta al usuario indicando cuál llanta requiere revisión. <br> <br> Escenario 2: <br>Dado que el sistema detecta que la presión de una o más llantas regresa a un nivel normal después de una alerta, <br>cuando esta condición se mantenga estable durante un tiempo prudente, <br>entonces el sistema deberá notificar al usuario que la presión de las llantas ha vuelto a su rango recomendado. | EP-002 |
| US-007 | Recomendación de mantenimiento. | Como mecánico, quiero poder agendar citas con mis clientes en caso de detectar alguna medida anómala en sus motocicletas desde mi interfaz, para brindar un servicio oportuno y mantener la seguridad de sus vehículos. | Escenario 1: <br>Dado que el sistema detecta una medida anómala en la motocicleta de un cliente, <br>cuando el mecánico acceda a la interfaz de gestión y seleccione al cliente correspondiente, <br>entonces podrá generar una recomendación de mantenimiento y proponer una cita en el calendario. <br> <br> Escenario 2: <br>Dado que un mecánico ha propuesto una cita de mantenimiento a un cliente, cuando el cliente confirme la cita desde su aplicación, entonces el sistema deberá registrar la cita en la agenda del mecánico y notificar la confirmación a ambas partes. <br> <br> Escenario 3: <br>Dado que un mecánico ha propuesto una cita de mantenimiento a un cliente, <br>cuando el cliente rechace o solicite reprogramar la cita desde su aplicación, <br>entonces el sistema deberá notificar al mecánico la respuesta del cliente y permitirle proponer una nueva fecha u hora. | EP-002 |
| US-008 | Notificación de sobrecalentamiento del motor | Como motociclista, <br>quiero que el aplicativo móvil me notifique cuando el motor de mi motocicleta esté presentando un sobrecalentamiento, <br>para poder detenerme a tiempo y evitar daños mayores al vehículo o accidentes. | Escenario 1: <br>Dado que el sistema detecta que la temperatura del motor ha superado el rango seguro, <br>cuando esta condición se mantenga durante un tiempo determinado, <br>entonces el sistema deberá emitir una notificación de alerta al usuario indicando el riesgo de sobrecalentamiento. <br> <br> Escenario 2: <br>Dado que el motor de la motocicleta regresa a su temperatura normal después de una alerta, <br>cuando esta condición se mantenga estable durante un tiempo prudente, <br>entonces el sistema deberá notificar al usuario que la temperatura del motor ha vuelto a la normalidad. <br> <br>Escenario 3: <br>Dado que el sistema detecta múltiples episodios de sobrecalentamiento en un período corto de tiempo, <br>cuando esta recurrencia sea considerada anómala, <br>entonces el sistema deberá recomendar al usuario agendar una revisión de mantenimiento para prevenir posibles fallas graves. | EP-002 |
| US-009 | Sugerencias personalizadas para próximos mantenimientos | Como motociclista, quiero recibir sugerencias personalizadas sobre el próximo mantenimiento que debo hacer, basadas en el historial y uso de mi moto. | Escenario 1: Dado que el sistema tiene acceso al historial de servicios, cuando detecte que se ha cumplido el intervalo de mantenimiento de un componente, entonces sugerirá su revisión o cambio. <br> Escenario 2: Dado que el motociclista revisa el panel de mantenimiento, cuando entre a la sección de sugerencias, entonces verá las recomendaciones específicas para su moto. | EP-003 |
| US-010 | Generación de reporte de salud del vehículo | Como mecánico, quiero generar un reporte de salud del vehículo que incluya estado de batería, temperatura, consumo y alertas recientes, para entregarlo al cliente al final del servicio. | Escenario 1: Dado que el mecánico finaliza un servicio, cuando seleccione la opción de generar reporte, entonces el sistema mostrará un resumen con métricas clave y alertas detectadas. <br> Escenario 2: Dado que el cliente desee conservar el reporte, cuando el mecánico finalice el servicio, entonces podrá imprimirlo o enviarlo por correo. | EP-003 |
| US-011 | Consulta del historial de servicios por parte del mecánico | Como mecánico, quiero consultar el historial de servicios realizados en una moto específica, para tomar decisiones informadas al momento del diagnóstico. | Escenario 1: Dado que el mecánico tenga una moto registrada en el sistema, cuando busque por placa o cliente, entonces podrá acceder al historial completo de servicios, fechas, repuestos y talleres. | EP-003 |
| US-012 | Resumen mensual de servicios, alertas y gastos | Como motociclista, quiero ver un resumen mensual de los servicios, alertas y gastos de mi moto, para tener una visión clara de su estado y del dinero invertido. | Escenario 1: Dado que el motociclista accede a la sección de reportes, cuando seleccione el mes deseado, entonces el sistema mostrará un resumen con los eventos ocurridos, gastos totales y estado general de la moto. | EP-003 |
| US-013 | Subscripción con mecánico. | Como motociclista, quiero poder establecer una relación con mi mecánico de confianza dentro de la aplicación para darle acceso a los datos recopilados, así como permitirle enviarme mensajes o agendar citas. | Escenario 1: <br>Dado que el motociclista desea vincularse con un mecánico de confianza, <br>cuando seleccione al mecánico desde la lista de disponibles o ingrese un código de invitación, <br>entonces el sistema deberá enviar una solicitud de relación al mecánico elegido. <br> <br> Escenario 2: <br>Dado que un motociclista ha enviado una solicitud de relación a un mecánico, <br>cuando el mecánico acepte la solicitud, <br>entonces el sistema deberá confirmar la relación establecida y otorgar al mecánico acceso autorizado a los datos del motociclista. | EP-005 |
| US-014 | Visualización de subscripciones activas con clientes. | Como mecánico, quiero poder visualizar las subscripciones activas de todos mis clientes, para tener claridad sobre qué motociclistas me han otorgado acceso a sus datos y poder gestionar mejor la relación. | Escenario 1: <br>Dado que el mecánico accede a su interfaz de gestión, <br>cuando consulte la sección de subscripciones activas, <br>entonces el sistema deberá mostrarle un listado con todos los motociclistas que han aceptado la relación. <br> <br> Escenario 2: <br>Dado que un cliente ha revocado su subscripción con el mecánico, <br>cuando el mecánico consulte nuevamente la lista de subscripciones activas, <br>entonces el sistema ya no deberá mostrar a dicho cliente en la lista. | EP-005 |
| US-015 | Terminación de la subscripcion con el mecanico | Como motociclista , quiero poder terminar o cambiar la relación de vinculación en cualquier momento, para asegurar mi privacidad y poder elegir un nuevo mecánico si lo deseo. | Escenario 1: Dado que el usuario (motociclista ) desea terminar la relación, cuando confirme la acción, entonces el acceso del mecánico a los datos se revocará inmediatamente. <br> Escenario 2: Dado que la subscripcion se ha cancelado, cuando cualquiera de las partes busque datos compartidos, entonces no podrá acceder a ellos hasta que se cree una nueva vinculación. | EP-005 |
| US-016 | Terminación de la subscripción con el cliente. | Como mecánico, <br>quiero poder terminar la relación de vinculación con un motociclista en cualquier momento, <br>para asegurar que no tenga acceso a mis servicios si ya no deseo mantener la relación. | Escenario 1: <br>Dado que el mecánico desea terminar la relación con un cliente, <br>cuando confirme la acción, <br>entonces el acceso del mecánico a los datos del cliente se revocará inmediatamente y se notificará al motociclista. <br> <br> Escenario 2: <br>Dado que la subscripción se ha cancelado por decisión del mecánico, <br>cuando cualquiera de las partes busque datos compartidos, <br>entonces no podrá acceder a ellos hasta que se cree una nueva vinculación. | EP-005 |
| US-017 | Gestión de múltiples suscripciones con diferentes mecánicos | Como motociclista, quiero poder tener y administrar suscripciones con más de un mecánico a la vez, para consultar métricas y recibir soporte especializado en diferentes áreas o ubicaciones. | Escenario 1: Dado que el motociclista tiene más de un mecánico suscrito, cuando acceda a la lista de suscripciones, entonces podrá seleccionar y administrar cada una por separado. <br> Escenario 2: Dado que el motociclista gestiona varias suscripciones, cuando reciba notificaciones, entonces podrá identificar de cuál mecánico provienen. | EP-005 |
| TS-001 | Uso de polling para detección. | Como desarrollador, quiero implementar un mecanismo de sondeo periódico (polling) para leer los valores de los sensores de la motocicleta (ej. presión de llantas, temperatura del motor, consumo de combustible), <br>para garantizar que la aplicación obtenga datos actualizados constantemente, y estos se vean registrados a lo largo del tiempo. | Escenario 1: <br>Dado que el sistema cuenta con sensores conectados, <br>cuando el proceso de polling se ejecute cada N milisegundos (configurable), <br>entonces se deberán leer los valores de todos los sensores y almacenarlos en la base de datos interna de la app o dispositivo. <br> <br> Escenario 2: <br>Dado que un valor leído supere los umbrales definidos (ej. sobrecalentamiento, baja presión), <br>cuando el sistema procese el dato en el ciclo de polling, <br>entonces se generará un evento de alerta que pueda ser notificado al usuario. <br> <br> Escenario 3: <br>Dado que no se produzca ninguna condición anómala, <br>cuando el polling lea los datos, <br>entonces se actualizarán los registros sin generar alertas adicionales. | EP-004 |
| TS-002 | Monitoreo del estado de las métricas. | Como desarrollador, quiero que las métricas recopiladas actuales del vehículo aparezcan en el monitor serial del dispositivo, para comprobar que estas coincidan con los valores reales. | Escenario 1: <br>Dado que los sensores de la motocicleta están enviando datos, <br>cuando el sistema ejecute la rutina de monitoreo, <br>entonces los valores actuales (ej. presión de llantas, temperatura del motor, consumo de combustible) deberán imprimirse en el monitor serial en tiempo real. <br> <br> Escenario 2: <br>Dado que un sensor específico reporta un valor anómalo, <br>cuando el dato sea mostrado en el monitor serial, <br>entonces el sistema deberá indicar claramente la métrica fuera de rango para facilitar su verificación. <br> <br> Escenario 3: <br>Dado que no hay cambios significativos en los valores de los sensores, <br>cuando el sistema muestre los datos en el monitor serial, <br>entonces estos deberán aparecer de forma estable y consistente, reflejando las lecturas reales sin alteraciones falsas. | EP-004 |
| TS-003 | Lectura de sensor de presión de llantas | Como desarrollador, quiero implementar la lectura periódica de los sensores de presión de llantas, para disponer de datos confiables en el sistema. | Escenario 1 : <br>Dado que los sensores estén conectados, cuando el sistema ejecute la rutina de lectura, entonces deberá obtener el valor actual en PSI de cada llanta. <br> <br> Escenario 2 : <br>Dado que la lectura se realice, cuando el valor esté fuera del rango definido, entonces el sistema deberá marcar el dato como anómalo. | EP-004 |
| TS-004 | Lectura de sensor de temperatura del motor | Como desarrollador, quiero integrar la lectura del sensor de temperatura del motor, para detectar condiciones de sobrecalentamiento. | Escenario 1: <br>Dado que el sensor esté instalado, cuando se ejecute la rutina de monitoreo, entonces el valor de la temperatura en °C deberá registrarse en memoria. <br> <br> Escenario 2: <br>Dado que la temperatura supere el rango seguro, cuando se procese el dato, entonces se deberá marcar como alerta interna para el sistema. <br> <br> Escenario 3: <br>Dado que la temperatura esté dentro de lo normal, cuando se registre en el log, entonces se mostrará sin alertas activas. | EP-004 |
| TS-005 | Lectura de sensor de consumo de combustible | Como desarrollador, quiero implementar la medición de flujo de combustible en tiempo real, para calcular consumo instantáneo y promedio. | Escenario 1: <br>Dado que el motor esté en marcha, cuando el sensor registre flujo, entonces el sistema calculará el consumo instantáneo en L/100km o km/L. <br> <br> Escenario 2: <br>Dado que se complete un trayecto, cuando el sistema procese los datos acumulados, entonces se calculará el consumo promedio. <br> <br> Escenario 3: <br>Dado que no haya flujo de combustible (motor apagado), cuando se ejecute la lectura, entonces el valor reportado será cero. | EP-004 |
| TS-006 | Registro de métricas en memoria local | Como desarrollador, quiero que todas las métricas capturadas se almacenen en memoria local del dispositivo, para permitir la persistencia de datos incluso sin conexión a la app. | Escenario 1: <br>Dado que se ejecute una lectura de sensor, cuando se obtenga el valor, entonces este se guardará con fecha y hora en la memoria local. <br> <br> Escenario 2: <br>Dado que la memoria alcance un límite, cuando se supere el máximo, entonces los registros más antiguos se reemplazarán por los más nuevos. <br> <br> Escenario 3: <br>Dado que la app se sincronice, cuando solicite datos, entonces la memoria local deberá enviar todos los registros pendientes. | EP-004 |
| TS-007 | Sincronización de datos con la aplicación móvil | Como desarrollador, quiero sincronizar los datos de métricas almacenados en el dispositivo con la app móvil, para asegurar que el usuario siempre tenga la información más reciente. | Escenario 1: <br>Dado que el dispositivo tenga registros locales, cuando la app se conecte, entonces se recepcionara todo el lote de datos pendientes. <br> <br> Escenario 2: <br>Dado que la transmisión se complete, cuando los datos estén confirmados en la app, entonces se marcarán como sincronizados en el dispositivo. <br> <br> Escenario 3: <br>Dado que la sincronización falle, cuando se reintente, entonces se enviarán solo los datos que falten. | EP-004 |
| TS-008 | Integración con framework de comunicación IoT | Como desarrollador, quiero integrar el framework IoT del proyecto para enviar los datos recopilados a la nube, para habilitar reportes remotos y análisis avanzados. | Escenario 1: <br>Dado que el dispositivo esté conectado a internet, cuando se complete un ciclo de lectura, entonces los datos deberán enviarse a la nube mediante el framework. <br> <br> Escenario 2: <br>Dado que la transmisión falle, cuando no haya conexión, entonces los datos quedarán en cola local hasta poder reenviarse. <br> <br> Escenario 3: <br>Dado que el envío se complete con éxito, cuando la nube reciba los datos, entonces el sistema deberá confirmar la entrega en el log serial. | EP-004 |

### 3.2 Impact Mapping

<img src="./images/chapter-3/impact_mapping_1.png" alt="impact_mapping_1" width="400"/>
<img src="./images/chapter-3/impact_mapping_2.png" alt="impact_mapping_2" width="400"/>
<img src="./images/chapter-3/impact_mapping_3.png" alt="impact_mapping_3" width="400"/>
<img src="./images/chapter-3/impact_mapping_4.png" alt="impact_mapping_4" width="400"/>

### 3.3 Product Backlog

## Capítulo IV: Solution Software Design

### 4.1 Strategic-Level Attribute-Driven Design

#### 4.1.1 Design-Level EventStorming

##### 4.1.1.1 Candidate Context Discovery

##### 4.1.1.2 Domain Message Flows Modeling

##### 4.1.1.3 Bounded Context Canvases

#### 4.1.2 Context Mapping

#### 4.1.3 Software Architecture

##### 4.1.3.1 Software Architecture System Landscape Diagram

##### 4.1.3.2 Software Architecture Context Level Diagrams

##### 4.1.3.3 Software Architecture Container Level Diagrams

##### 4.1.3.4 Software Architecture Deployment Diagrams

### 4.2 Tactical-Level Domain-Driven Design

#### 4.2.1 Bounded Context: unnamed

##### 4.2.1.1 Domain Layer

##### 4.2.1.2 Interface Layer

##### 4.2.1.3 Application Layer

##### 4.2.1.4 Infrastructure Layer

##### 4.2.1.5 Bounded Context Software Architecture Component Level Diagrams

##### 4.2.1.6 Bounded Context Software Architecture Code Level Diagrams

###### 4.2.1.6.1 Bounded Context Domain Layer Class Diagrams

###### 4.2.1.6.2 Bounded Context Database Design Diagram

## Conclusiones

## Bibliografía

## Anexos
