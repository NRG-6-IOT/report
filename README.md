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

- [Universidad Peruana de Ciencias Aplicadas](#universidad-peruana-de-ciencias-aplicadas)
    - [**CURSO:** Desarrollo de Soluciones IoT](#curso-desarrollo-de-soluciones-iot)
    - [**NRC**: 3443](#nrc-3443)
    - [**Profesor:** Ángel Augusto Velásquez Núñez](#profesor-ángel-augusto-velásquez-núñez)
    - [**Ingeniería de software**](#ingeniería-de-software)
  - [Informe de -](#informe-de--)
    - [**Nombre del startup:** NRG8](#nombre-del-startup-nrg8)
    - [**Nombre del producto:** -](#nombre-del-producto--)
  - [**Integrantes**](#integrantes)
  - [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [Contenido](#contenido)
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
#### Problema identificado  
En el contexto urbano, los dueños de motos suelen carecer de herramientas digitales que les permitan monitorear el estado de sus vehículos y llevar un control de sus costos de uso y mantenimiento. Esto ocasiona un uso ineficiente del combustible (monetario y rendimiento), fallas mecánicas inesperadas, gastos imprevistos y dificultades para planificar el cuidado preventivo de la moto.  
Por otro lado, los mecánicos y talleres enfrentan la falta de información confiable y actualizada sobre el historial junto a la condición de las motos de sus clientes, lo que en ocasiones limita la precisión de los diagnósticos y la capacidad de generar relaciones de confianza y fidelización.
#### Solución propuesta  
La plataforma IoT para motos urbanas BykerZ ofrece un ecosistema digital compuesto por aplicaciones móviles, web y un dispositivo embebido que recolecta datos de telemetría en tiempo real (kilometraje, consumo de gasolina, estado de batería, vibración y temperatura del motor).  
- Desde el rol de usuario de moto urbana:
    - Consultar métricas de eficiencia de combustible
    - Recibir alertas preventivas
    - Visualizar y registrar costos acumulados de mantenimiento y uso
    - Acceder al historial de servicios realizados.
    - Sugerencias para próximos mantenimientos.
- Desde el rol de mecánico o taller: 
    - Comparación de métricas entre motos similares  
    - Generación de reportes de salud del vehículo  
    - La consulta del historial de servicios  
    - La emisión de recordatorios para próximos mantenimientos.  

Gracias a sus funcionalidades, la plataforma impulsa un uso más seguro, económico y sostenible de las motos, al mismo tiempo que fortalece la relación entre usuarios y mecánicos mediante datos objetivos y accesibles en tiempo real.
#### 1.2.1 Antecedentes y problemática

##### What

- ¿Cuál es el problema?

El problema principal recae en la dificultad de realizar revisiones proactivas, ya que los propietarios carecen por completo de visibilidad en tiempo real sobre la salud de sus vehículos. Esta ceguera operativa conduce inevitablemente a fallas inesperadas y costosas. Por su parte, los talleres mecánicos se ven forzados a operar de manera reactiva; aunque realizan una revisión general al recibir la moto, el proceso de diagnóstico es lento e ineficiente, ya que deben revisar manualmente múltiples partes del vehículo hasta atinar con la fuente del problema, en lugar de poder ofrecer un mantenimiento predictivo y proactivo basado en datos precisos.

- ¿Cuál es la relación con la persona en cuestión?

La relación con el mecánico se transforma gracias a nuestra plataforma. Ya no se limita a interacciones esporádicas y reactivas cuando algo se rompe, sino que se convierte en una relación constante y proactiva. El mecánico utiliza la herramienta para ofrecer un servicio de monitoreo continuo, lo que le permite actuar como un aliado tecnológico y generar un vínculo de confianza mediante un valor añadido constante. Para el usuario, esta relación se traduce en acceso a datos transparentes sobre su vehículo y la recepción de alertas y recomendaciones directas de su mecánico de confianza.

En esencia, la plataforma está enfocada en proporcionar a ambos actores una herramienta integral que satisface sus necesidades específicas: facilita un monitoreo y registro sencillo de las métricas del vehículo para el usuario y, al mismo tiempo, empodera al mecánico con datos precisos para realizar revisiones más efectivas, optimizando significativamente su trabajo y elevando la calidad del servicio.

##### When

- ¿Cuándo sucede el problema?

El problema ocurre durante el uso diario de la motocicleta, cuando el propietario carece de visibilidad sobre el estado interno de su vehículo. Las fallas y el desgaste suceden de manera imprevista, sin alertas tempranas, llevando a averías inesperadas que interrumpen la movilidad y generan costosas reparaciones de emergencia.

- ¿Cuándo utiliza el cliente el producto?

El cliente utiliza la aplicación de BykerZ de forma continua durante sus trayectos para monitorizar en tiempo real el estado de su moto y conocer en qué momento necesita llevar a cabo mantenimiento. Además, accede a ella de manera proactiva al recibir notificaciones del taller, lo que le permite gestionar alertas específicas y agendar citas de mantenimiento con facilidad. Este uso constante no solo le ofrece tranquilidad y control sobre su vehículo, sino que también favorece directamente al mecánico, quien recibe métricas precisas y premeditadas que agilizan y optimizan el proceso de diagnóstico y reparación.

##### Where

- ¿Dónde está el cliente cuando usa el producto?

El cliente utiliza la aplicación de BykerZ principalmente desde su smartphone, accediendo a ella en cualquier lugar y momento. Este acceso ubicuo le permite monitorizar el estado de su moto en tiempo real durante sus desplazamientos, así como revisar de forma remota el historial técnico y las notificaciones proactivas que recibe. Si bien la plataforma se utiliza en talleres durante las interacciones con el mecánico para facilitar el diagnóstico colaborativo, su verdadero poder radica en que todas las métricas y el historial detallado del vehículo pueden visualizarse y compartirse desde cualquier lugar con acceso a internet, garantizando una supervisión continua y una comunicación fluida entre el usuario y su taller de confianza.

- ¿Dónde surge el problema?

El problema surge en la propia motocicleta durante su operación diaria, donde ocurren los eventos críticos. Además, se manifiesta en el taller mecánico, donde la falta de datos en tiempo real impide al mecánico anticiparse a las fallas y ofrece un servicio reactivo.

##### Who

- ¿Quienes se ven involucrados en el problema?

El problema involucra directamente a dos actores clave: los propietarios de motocicletas y los talleres mecánicos. Por un lado, los usuarios enfrentan la dificultad constante de no tener conocimiento preciso del estado interno de sus vehículos, lo que los expone a sufrir fallas imprevistas y reparaciones costosas. Por otro lado, los mecánicos y talleres se ven igualmente afectados, ya que esta falta de información les impide evolucionar hacia un modelo de servicio preventivo y proactivo, lo que no solo genera ineficiencias en sus procesos de diagnóstico, sino que también representa una pérdida de oportunidades de negocio para fidelizar y agregar valor a su cartera de clientes existente.

##### Why

- ¿Por qué sucede el problema?

Las causas del problema se deben en mayor parte a la falta de datos actualizados sobre el estado del vehículo y/o poco conocimiento de algunos usuarios con respecto a identificar señales de una falla en el vehículo. Por otro lado, el diagnóstico se complica ya que carece de un historial del vehículo, dependiendo de lo que el cliente recuerde en base a reparaciones previas y/o incidentes recientes.

##### How 

- ¿En qué condiciones los clientes usan nuestro producto?

Los clientes utilizan nuestro producto en condiciones de movilidad, accediendo a los datos de su moto en tiempo real durante sus trayectos o de manera remota para planificar mantenimientos. La plataforma es utilizada principalmente a través de dispositivos móviles con conectividad a internet, permitiendo interacciones tanto preventivas como reactivas ante alertas generadas por el sistema.

#### 1.2.2 Lean UX Process

##### 1.2.2.1 Lean UX Problem Statements

En el panorama actual de la movilidad urbana, los propietarios de motocicletas operan con una constante incertidumbre respecto al estado de sus vehículos al carecer de visibilidad sobre su condición interna, lo que los expone al riesgo de fallas sorpresivas, reparaciones costosas o incluso accidentes fatales. Paralelamente, los talleres mecánicos se ven limitados por un modelo de servicio reactivo; solo pueden intervenir cuando el problema ya ha ocurrido, lo que se agrava al recibir descripciones vagas e incompletas de los usuarios. Esta falta de datos técnicos específicos complica el diagnóstico, prolonga los tiempos de reparación, reduce la eficiencia del servicio y finalmente erosiona la confianza del cliente.

Para cubrir esta necesidad crítica, surge BykerZ como una herramienta integral que transforma este ecosistema. Se trata de una plataforma digital que monitorea el vehículo en tiempo real y recopila datos históricos de su desempeño de forma automática. Al analizar esta información, BykerZ genera métricas precisas y alertas oportunas sobre anomalías o patrones de desgaste, notificando tanto al motociclista como al mecánico. Esto permite a los usuarios actuar de manera preventiva y empodera a los talleres con información técnica precisa, optimizando sus diagnósticos, permitiendo un mantenimiento proactivo y restaurando así la confianza en los resultados del servicio.

##### 1.2.2.2 Lean UX Assumptions
###### User Assumptions:  
- **¿Quién es el usuario?:** El usuario es un motociclista que busca una manera confiable de conocer el estado actual de su vehículo, así como un mecánico que necesito mayor precisión en la información técnica de la motocicleta para realizar diagnósticos y reparaciones eficientes.  
- **¿Dónde encaja nuestro producto en su trabajo o vida?:** Nuestro producto encaja en el uso cotidiano de la motocicleta para los conductores, así como en el diagnóstico y reparación dentro del taller para los mecánicos.  
- **¿Qué problemas resuelve nuestro producto?:** Nuestro producto resuelve la falta de información confiable sobre el estado de la moto para los conductores. Mientras que, para los mecánicos, resuelve el problema con diagnósticos lentos y/o imprecisos, así como la naturaleza reactiva de su negocio.  
- **¿Cuándo y cómo se usa nuestro producto?:** Se utiliza de forma pasiva durante la conducción del usuario, y de forma activa al recibir las alertas para revisar el estado de su moto. El mecánico lo utiliza diariamente para revisar el estado de las motos de sus clientes suscritos.  
- **¿Qué características son importantes?:** Para el usuario, son importantes las alertas, las métricas sencillas y fáciles de entender, un historial de mantenimiento y una forma de integrar su relación con un taller de confianza. Para el mecánico, es importante tener un dashboard con el estado de las motos de los clientes suscritos, una función de alertas prioritarias, una herramienta de comunicación integrada, y gestión de citas.  
- **¿Cómo debe verse y comportarse nuestro producto?:** Debe tener una interfaz clara y minimalista para el usuario final, priorizando la visualización de datos de salud del vehículo de una manera sencilla (Colores de Semáforo: Verde/Amarillo/Rojo). Para el mecánico, la interfaz debe ser más compleja, pero igualmente intuitiva, priorizando la visualización de problemas críticos y la gestión de clientes.  
###### Business Assumptions:
- **Necesidades y problemas:** Creemos que los motociclistas necesitan una forma confiable de conocer el estado de sus vehículos y así poder anticipar fallas, mientras que los mecánicos requieren datos más técnicos y claros que les faciliten diagnósticos más rápidos y precisos.  
- **Plataforma:** Estas necesidades se pueden resolver a través de un ecosistema que combine un hardware IoT, una aplicación móvil para el usuario y una plataforma web SaaS para los talleres.  
- **Segmentación:** Los usuarios principales serán motociclistas que buscan seguridad y control sobre el estado de su vehículo, y nuestros clientes directos son los talleres o mecánicos interesados en contar con información detallada y quieren adoptar la tecnología necesaria para mejorar su servicio.  
- **Comportamientos:** El valor que los usuarios esperan obtener de nuestro servicio es la tranquilidad de anticipar problemas, evitar gastos inesperados y acceder a reportes confiables que respalden decisiones de mantenimiento.  
- **Beneficios:** Los usuarios obtendrán seguridad y un ahorro en costos de reparación a largo plazo. Los mecánicos se beneficiarán con diagnósticos más eficientes, mayor confianza del cliente y la optimización de su trabajo.
- **Captación de clientes:** Adquiriremos talleres socios a través de ventas directas y referencias del sector, además de realizar campañas digitales enfocadas en las comunidades de motociclistas, atrayendo más clientes potenciales.  
- **Modelo de ingresos:** Generaremos ingresos mediante la venta de los dispositivos IoT, planes de suscripción para el acceso de los mecánicos a los reportes avanzados y acuerdos comerciales con talleres para el uso de la plataforma.
- **Competencia:** Nuestra competencia directa son los scanners OBD2 genéricos y apps como "Bike Scanner". La competencia indirecta son los servicios de mantenimiento tradicionales.  
- **Ventaja competitiva:** Superaremos a la competencia gracias a la integración perfecta taller-cliente, la interpretación automatizada de datos y el enfoque en el mantenimiento predictivo y la experiencia completa, no solo en la lectura de datos.  
###### Technical Assumptions (Suposiciones Técnicas)  
- **Tecnología utilizada:** Podemos desarrollar un dispositivo IoT confiable, de bajo consumo y conectividad estable para instalarse en la moto. La app móvil se puede desarrollar con un framework cross-platform, como Flutter y el backend con tecnologías escalables como Spring Boot o Node.js.  
- **Integraciones:** La plataforma del taller debería integrarse potencialmente con software de gestión de talleres existente y con pasarelas de pago para manejar las suscripciones.  
- **Escalabilidad:** La arquitectura en la nube podrá escalar para soportar el procesamiento de datos en tiempo real de miles de dispositivos y usuarios simultáneos.  
###### Market Assumptions (Suposiciones de Mercado)  
- **Tamaño del mercado:** Existe un mercado significativo y en crecimiento de motociclistas que priorizan la seguridad y el cuidado de su vehículo, y talleres que buscan digitalizarse. Este también es poco explorado, por lo que existe la oportunidad de llenar un nicho con nuestro producto.  
- **Competencia:** El mercado no está saturado con soluciones integrales que conecten directamente al usuario con el taller; la mayoría son herramientas genéricas o desconectadas del servicio profesional.  
- **Tendencias:** Las tendencias de IoT, la movilidad inteligente y la economía de suscripción están en crecimiento, lo que crea un terreno fértil para nuestra solución.  
###### Design Assumptions  
- **Interacción del usuario:** Los usuarios tendrán una mejor interacción con las aplicaciones web y móvil si es que pueden consultar de forma inmediata los indicadores esenciales de su moto y recibir notificaciones oportunas sobre posibles fallas. Mientras que los mecánicos, además de una fácil interacción con las aplicaciones, podrán tener acceso a una mayor cantidad de información técnica y así poder realizar diagnósticos más precisos.  
- **Experiencia del usuario:** Los usuarios tendrán una interfaz intuitiva y confiable que entregue información práctica y transmita tranquilidad, con datos presentados de forma simple y no con términos técnicos crudos, lo que mejorará la percepción de seguridad y control sobre el vehículo.  
- **Colores y la tipografía:** Utilizaremos una paleta de colores que transmita seguridad (azules, verdes) y alerta (rojos, naranjas) cuando sea necesario. La tipografía debe ser marcada y muy legible incluso en movimiento.  
- **Preferencias visuales:** Los usuarios considerarán atractivo un diseño que se asemeje a otros dashboards de vehículos modernos: limpio, con gráficos simples e íconos universalmente reconocibles, y resúmenes visuales fáciles de interpretar.  
- **Prototipos y pruebas:** Las pruebas con motociclistas y mecánicos son necesarias para verificar la facilidad de uso del producto, así como del diseño; todo ello será a través de pruebas de usabilidad. 

##### 1.2.2.3 Lean UX Hypothesis Statements

**Hypothesis Statement 01:**

- Creemos que los motociclistas necesitan una forma sencilla y confiable de monitorear el estado de su moto en tiempo real.
- Sabremos que estamos en lo correcto cuando observemos que los clientes consultan frecuentemente la aplicación para revisar métricas de su vehículo.

**Hypothesis Statement 02:**

- Creemos que los mecánicos requieren información temprana sobre fallos potenciales para brindar un servicio más proactivo.
- Sabremos que estamos en lo correcto cuando los mecánicos reporten menor número de reparaciones de emergencia y mayor número de mantenimientos preventivos.

**Hypothesis Statement 03:**

- Creemos que centralizar la comunicación entre cliente y taller dentro de la plataforma reducirá la fricción y mejorará la coordinación.
- Sabremos que estamos en lo correcto cuando los clientes usen la mensajería o notificaciones de la app en lugar de llamadas o visitas imprevistas.

**Hypothesis Statement 04:**

- Creemos que la creación de un historial de servicios será clave para que los motociclistas planifiquen mantenimientos futuros.
- Sabremos que estamos en lo correcto cuando los usuarios registren y consulten con frecuencia los mantenimientos realizados en su moto.

**Hypothesis Statement 05:**

- Creemos que ofrecer una suscripción con acceso a datos en tiempo real dará valor suficiente para retener clientes.
- Sabremos que estamos en lo correcto cuando observemos baja tasa de cancelación y renovaciones recurrentes de la suscripción.

**Hypothesis Statement 06:**

- Creemos que los usuarios percibirán a BykerZ como una forma de manejar con mayor seguridad y confianza.
- Sabremos que estamos en lo correcto cuando recibamos comentarios positivos en encuestas y reseñas sobre la sensación de seguridad brindada por el uso de la aplicación.

**Hypothesis Statement 07:**

- Creemos que las notificaciones deben ser escuetas y fáciles de entender para que los motociclistas no las ignoren.
- Sabremos que estamos en lo correcto cuando las pruebas de usabilidad muestren que los usuarios entienden y siguen las alertas que reciban.

**Hypothesis Statement 08:**

- Creemos que una interfaz simple con información precisa facilitará la adopción de la aplicación por los motociclistas.
- Sabremos que estamos en lo correcto cuando veamos comentarios positivos sobre la usabilidad de la aplicación.

**Hypothesis Statement 09:**

- Creemos que los talleres que adopten esta plataforma tendrán mayor fidelización de clientes frente a los que no lo hagan.
- Sabremos que estamos en lo correcto cuando los talleres suscritos muestren un aumento en clientes recurrentes.

**Hypothesis Statement 10:**

- Creemos que los usuarios valorarán la posibilidad de acceder al historial de mantenimiento de su motocicleta en un solo lugar.
- Sabremos que estamos en lo correcto cuando los clientes consulten repetidamente el historial en la aplicación.

**Hypothesis Statement 11:**

- Creemos que la plataforma ayudará a los talleres a gestionar de manera más eficiente varias motos de distintos clientes al mismo tiempo.
- Sabremos que estamos en lo correcto cuando los mecánicos reporten menor tiempo de organización y mayor control de su cartera de clientes.

**Hypothesis Statement 12:**

- Creemos que integrar recordatorios automáticos de mantenimientos programados reducirá los olvidos de los clientes.
- Sabremos que estamos en lo correcto cuando los clientes acudan puntualmente a las citas de mantenimiento.

**Hypothesis Statement 13:**

- Creemos que la interfaz intuitiva de la aplicación facilitará la adopción por parte de clientes que no son expertos en tecnología.
- Sabremos que estamos en lo correcto cuando los usuarios aprendan a manejar la app en menos de una semana y la usen sin asistencia.

**Hypothesis Statement 14:**

- Creemos que mostrar gráficas y estadísticas en tiempo real aumentará la percepción de valor tecnológico en la plataforma.
- Sabremos que estamos en lo correcto cuando los usuarios interactúen frecuentemente con los paneles de datos visuales.

**Hypothesis Statement 15:**

- Creemos que el envío de reportes semanales sobre el estado de la moto fortalecerá la relación de confianza entre cliente y taller.
- Sabremos que estamos en lo correcto cuando los clientes valoren positivamente los reportes y continúen la suscripción.

**Hypothesis Statement 16:**

- Creemos que el sistema reducirá costos inesperados al detectar anomalías antes de que se conviertan en averías graves.
- Sabremos que estamos en lo correcto cuando los clientes reporten menos gastos de emergencia y mayor previsión.

**Hypothesis Statement 17:**

- Creemos que ofrecer soporte rápido en caso de fallos críticos en la moto motivará a los usuarios a depender de la aplicación.
- Sabremos que estamos en lo correcto cuando los usuarios utilicen la función de soporte y lo califiquen positivamente.

**Hypothesis Statement 18:**

- Creemos que incluir un sistema de alertas personalizadas para cada cliente aumentará la efectividad del mantenimiento preventivo.
- Sabremos que estamos en lo correcto cuando los talleres reporten mayor precisión en la programación de servicios.

**Hypothesis Statement 19:**

- Creemos que la transparencia en el estado real de la moto mejorará la percepción de honestidad hacia los mecánicos.
- Sabremos que estamos en lo correcto cuando los clientes expresen confianza en las recomendaciones de mantenimiento recibidas a través de la app.

**Hypothesis Statement 20:**

- Creemos que los motociclistas estarán más motivados a usar BykerZ si reciben consejos prácticos de cuidado básico de sus motocicletas.
- Sabremos que estamos en lo correcto cuando identifiquemos que los usuarios revisan de forma constante las secciones de recomendaciones en la aplicación.

##### 1.2.2.4 Lean UX Canvas
![Lean UX Canvas](images/chapter-1/lean-ux-canvas.png)

### 1.3 Segmentos objetivo

#### Segmento Objetivo #1: Usuarios de motos urbanas

Este grupo incluye a personas que utilizan motocicletas como su principal medio de transporte en entornos urbanos, ya sea para movilizarse hacia sus trabajos, estudios, actividades sociales o incluso para labores de reparto. Son usuarios interesados en mantener la eficiencia de su moto, reducir costos imprevistos y contar con mayor seguridad mediante el monitoreo del estado de su vehículo.

- Características clave:
  - Edad: 18 a 45 años
  - Género: Ambos
  - Contexto: Desplazamiento urbano frecuente (trabajo, estudio, servicios de entrega, actividades sociales).
  - Ocupación: Estudiantes universitarios, trabajadores formales/informales, repartidores, jóvenes profesionales.
  - Uso de tecnología: Usuarios activos de smartphones, acostumbrados a apps móviles (redes sociales, movilidad, delivery, fintech).
- Necesidades:
  - Monitorear el consumo de gasolina y la eficiencia del vehículo.
  - Prevenir fallas con alertas de mantenimiento.
  - Conocer costos acumulados de uso y reparaciones.
  - Tener a mano el historial de mantenimiento.

#### Segmento Objetivo #2: Mecánicos y talleres de servicio

Este grupo está conformado por profesionales independientes o pequeños talleres que ofrecen servicios de reparación y mantenimiento de motocicletas. Requieren herramientas que les permitan ofrecer diagnósticos más precisos y gestionar mejor la relación con sus clientes, a fin de mejorar la confianza y fidelización.

- Características clave:
  - Edad: 25 a 55 años
  - Género: Ambos
  - Contexto: Trabajo en talleres de servicio mecánico, tanto formales como independientes.
  - Ocupación: Mecánicos, técnicos de motos, dueños de talleres pequeños o medianos.
  - Uso de tecnología: Nivel intermedio; utilizan smartphones y en algunos casos software de gestión básica. Suelen apoyarse en WhatsApp y redes sociales para coordinar con clientes.
- Necesidades:
  - Acceder a métricas objetivas del estado de la moto.
  - Emitir reportes de salud y diagnósticos comparativos.
  - Consultar el historial de servicios de cada cliente.
  - Recordar y planificar mantenimientos preventivos.


## Capítulo II: Requirements Elicitation & Analysis

### 2.1 Competidores

- Wialon (Gurtam)
  
  <img src="./images/chapter-2/wialon_logo.png" alt="wialon_logo" width="400"/>
  
  Wialon es la plataforma de software insignia de Gurtam, una empresa bielorrusa con más de 20 años en el mercado de telemática e IoT. Está considerada una de las soluciones más versátiles para la gestión de flotas y activos móviles, con más de 4 millones de unidades conectadas en más de 160 países. Wialon funciona bajo un modelo SaaS altamente escalable y soporta más de 3.000 modelos de dispositivos GPS e IoT, lo que permite adaptarse a diferentes necesidades: desde camiones y buses hasta maquinaria pesada o transporte ligero. Entre sus funcionalidades principales destacan el rastreo en tiempo real, generación de informes personalizados, alertas de eventos, gestión de combustible, mantenimiento predictivo y herramientas de integración por API. Su principal fortaleza radica en la gran flexibilidad y ecosistema de partners, lo que lo convierte en una solución preferida para empresas de logística, transporte y operadores de flotas internacionales.

- Fuelio
  
  <img src="./images/chapter-2/fuelio_logo.png" alt="fuelio_logo" width="400"/>
  
  Fuelio es una aplicación móvil enfocada en la gestión del consumo de combustible y el mantenimiento vehicular. Permite a los usuarios registrar de manera sencilla el kilometraje, repostajes, costos asociados y servicios realizados al vehículo, generando estadísticas detalladas sobre rendimiento y gastos. La app ofrece funcionalidades adicionales como localización de estaciones de servicio cercanas, cálculo de consumo por trayecto, y respaldo automático en la nube para mantener los datos seguros y accesibles en múltiples dispositivos. Su propuesta de valor radica en brindar control y transparencia sobre los gastos de movilidad, ayudando tanto a conductores individuales como a pequeños administradores de vehículos a optimizar su presupuesto y hábitos de conducción.
  
- GeoTab

  <img src="./images/chapter-2/geotab_logo.png" alt="geotab_logo" width="400"/>
  
  Geotab, fundada en 2000 en Canadá, es uno de los líderes globales en telemática comercial y gestión de flotas, con más de 3,7 millones de vehículos conectados en más de 150 países. Su propuesta combina el dispositivo IoT Geotab GO9 con la plataforma en la nube MyGeotab, lo que permite a empresas de cualquier tamaño acceder a datos avanzados de sus vehículos. Entre sus principales funcionalidades se incluyen análisis de comportamiento de conducción, diagnóstico de motor, consumo de combustible, planificación de rutas, alertas de mantenimiento, cumplimiento normativo (como ELD en EE.UU.) y reportes personalizados. Además, Geotab cuenta con el Geotab Marketplace, un ecosistema de más de 200 aplicaciones complementarias que amplían las capacidades de la plataforma. Su diferenciador está en la precisión de sus análisis, confiabilidad y enfoque en big data e inteligencia artificial, que permiten a empresas grandes y gobiernos tomar decisiones estratégicas basadas en datos de movilidad.

#### 2.1.1 Análisis competitivo

| **Categoría** | **Byker Z** | **Wialon (Gurtam)** | **Fuelio** | **Geotab** |
|---------------|----------------|----------------------|------------|------------|
| **Perfil - Overview** | Plataforma IoT para motocicletas que conecta mecánicos con clientes, con métricas en tiempo real y alertas preventivas. | SaaS de telemática IoT para gestión de vehículos y activos móviles, con GPS y reportes avanzados. | App para rastrear consumo de combustible, costos, kilometraje y servicios, con búsqueda de estaciones y respaldo en la nube. | Líder global en telemática, con dispositivos IoT y software para análisis de datos vehiculares. |
| **Ventaja competitiva** | Enfoque de nicho: motos + talleres mecánicos. Conexión directa cliente-mecánico mediante suscripción. | Amplia cobertura global y flexibilidad de personalización para distintos tipos de flotas. | Interfaz sencilla, soporte crowdsourced de precios, recordatorios, sincronización y reportes visuales potentes. | Precisión en datos y analítica avanzada, gran reputación en confiabilidad. |
| **Perfil de Marketing - Mercado Objetivo** | Motociclistas individuales y talleres mecánicos pequeños/medianos. | Empresas de logística, transporte y flotas heterogéneas. | Usuarios que buscan ahorro en combustible y seguimiento básico de gastos vehiculares, incluidos conductores particulares y usuarios multi-vehículo. | Flotas comerciales, gobiernos, corporativos globales. |
| **Estrategias de Marketing** | Enfoque B2B2C: atraer talleres como socios y motociclistas vía suscripción. | Estrategia B2B, alianzas con distribuidores y partners locales. | Se promociona como simple y potente; cuenta con integración de precios crowdsourced, historias de usuarios satisfechos y respaldo de Sygic. | Estrategia B2B global, certificaciones y partnerships institucionales. |
| **Perfil de Producto - Productos & Servicios** | Sensores IoT para motos, app móvil/web para clientes, dashboard para mecánicos, alertas proactivas. | Plataforma SaaS con GPS, sensores IoT, informes personalizados. | Fill-ups, gastos, recordatorios, estación de gasolina cercana, gráficos, estadísticas, sincronización. <br> Pro: planificación de ruta, estimación de costo, filtro estaciones, reporte de ruta. | Dispositivos IoT + plataforma de análisis con diagnósticos y mantenimiento predictivo. |
| **Precios & Costos** | Modelo de suscripción mensual accesible (B2C) + paquetes premium para talleres. | Licencias SaaS escalables, costos variables por flota. | Gratuito, Fuelio Pro en Android es suscripción (€7 - €9) sin afectar funciones gratuitas. | Suscripción SaaS + costo de dispositivos IoT (moderado/alto). |
| **Canales de Distribución** | App móvil (Android), web, talleres como canales de adquisición. | Red de partners y distribuidores en más de 150 países. | Android & iOS. | Red global de resellers y partners certificados. |
| **SWOT - Fortalezas** | Nicho diferenciado, cercanía con usuarios finales, foco en motos. | Escalabilidad, robustez y experiencia global. | Interfaz amigable, precios crowdsourced, reportes detallados, muchos features gratuitos. | Precisión en analítica, confiabilidad, amplia red global. |
| **SWOT - Debilidades** | Proyecto nuevo, sin marca consolidada, recursos limitados. | No especializado en motos, alto costo para pequeños talleres. | Entrada manual laboriosa, problemas ocasionales de sincronización. | Altos costos, pensado para grandes flotas, no para usuarios individuales. |
| **SWOT - Oportunidades** | Mercado creciente de motocicletas en LATAM/Asia, tendencia a IoT y mantenimiento predictivo. | Expansión en verticales nuevos como motos y microflotas. | Expandir trip logging, entradas automáticas, soporte ampliado en iOS. | Penetración en mercados emergentes y nuevas integraciones IoT. |
| **SWOT - Amenazas** | Ingreso de grandes players al nicho, barreras de hardware. | Competencia creciente y commoditización de la telemática. | Cambios en licenciamiento por Sygic; apps emergentes con mejor UX o IA predictiva. | Alta competencia y presión por diferenciación. |

#### 2.1.2 Estrategias y tácticas frente a competidores

1. Estrategia de Diferenciación Tecnológica (IoT + Diagnósticos Predictivos)
   
Objetivo: Posicionar a BykerZ como la primera solución que integra hardware IoT y software para ofrecer métricas automáticas en tiempo real y diagnósticos predictivos, superando la limitación de registros manuales en Drivvo, aCar y Fuelio.

Tácticas:

Desarrollar un dispositivo IoT plug & play que se instale fácilmente en motos urbanas.

Integrar algoritmos de mantenimiento predictivo basados en telemetría.

Generar reportes personalizados descargables para usuarios y mecánicos.

Comunicar en marketing el diferencial clave: “No registres datos, deja que tu moto hable por ti”.

2. Estrategia de Enfoque en Nichos Desatendidos (Motos Urbanas + Mecánicos)
   
Objetivo: Atacar un mercado poco atendido: motociclistas urbanos y talleres mecánicos, en contraste con las apps competidoras que se enfocan en autos y flotas.

Tácticas:

Ofrecer funcionalidades específicas para motos (ej. control de gasolina por cilindrada, alertas de aceite, historial de mantenimientos por kilometraje).

Crear una app web exclusiva para mecánicos, con comparativos por modelo y gestión de clientes.

Establecer alianzas con talleres locales y concesionarios de motos para distribución del IoT.

Campañas de marketing dirigidas a delivery riders, mototaxistas y jóvenes motociclistas urbanos.

3. Estrategia de Marca Cercana y Comunitaria
   
Objetivo: Construir confianza mostrando a BykerZ como una solución hecha por y para motociclistas y mecánicos, en lugar de una app genérica de gastos.

Tácticas:

Crear una comunidad digital de motociclistas, con foros y tips de mecánica preventiva.

Usar un lenguaje simple y cercano, evitando tecnicismos innecesarios.

Brindar soporte personalizado (ej. chat directo, FAQs en video, tutoriales cortos en redes).

Generar contenido educativo sobre seguridad, ahorro de combustible y mantenimiento inteligente.

4. Estrategia de Precio Accesible y Transparente
   
Objetivo: Superar la percepción negativa de Drivvo (suscripción costosa) y Fuelio Pro (costo adicional), ofreciendo planes claros y económicos.

Tácticas:

Modelo freemium real: funcionalidades básicas siempre gratuitas (seguimiento de consumo y alertas).

Plan Premium accesible (<$2/mes) con reportes predictivos, diagnósticos avanzados y sincronización completa.

Precio del dispositivo IoT asequible (ej. $30–40) con facilidades de pago en talleres.

Descuentos especiales para mecánicos que adquieran múltiples dispositivos para sus clientes.

5. Estrategia de Diferenciación por Especialización en Motocicletas

Objetivo: Posicionar la solución como un producto diseñado específicamente para motocicletas y talleres mecánicos, en contraste con los competidores que se orientan a flotas grandes y heterogéneas (Wialon, Geotab).

Tácticas:

Desarrollar una interfaz amigable y personalizada para mecánicos y motociclistas.

Ofrecer funcionalidades exclusivas para motos (ej. alertas de mantenimiento de cadena, aceite, frenos).

Construir una narrativa de marca clara: “la telemática de las motos”.

6. Estrategia de Accesibilidad y Flexibilidad en el Modelo de Negocio

Objetivo: Competir contra grandes competidores (Wialon, Samsara, Geotab) ofreciendo un producto más accesible, económico y fácil de implementar, enfocado en usuarios individuales y talleres pequeños.

Tácticas:

Diseñar planes de suscripción escalonados (desde básicos hasta avanzados) que permitan crecer al ritmo del usuario.

Incluir un modelo freemium o demo para captar usuarios rápidamente sin barreras de entrada.

Resaltar la facilidad de instalación de sensores IoT en motos, evitando hardware costoso o complejo.

7. Estrategia de Cercanía y Comunidad con el Usuario Final

Objetivo: Diferenciarse por la relación directa y de confianza entre motociclistas y mecánicos, creando una comunidad alrededor del producto que los competidores globales no priorizan.

Tácticas:

Lanzar campañas de marketing en comunidades locales (Facebook, Instagram, clubes de motociclistas, foros especializados).

Promover talleres mecánicos como socios estratégicos para captar clientes y distribuir el IoT.

Desarrollar integraciones futuras con aseguradoras o talleres certificados, ofreciendo beneficios adicionales (ej. descuentos en seguros, paquetes de mantenimiento).

### 2.2 Entrevistas

#### 2.2.1 Diseño de entrevistas

- Diseño de entrevistas para Motociclistas

Preguntas principales:

1. ¿Podrías contarme un poco sobre ti? (edad, ocupación, lugar de residencia, estado civil)

2. ¿Cómo sueles llevar el control del gasto de combustible y mantenimiento de tu moto?

3. ¿Con qué frecuencia realizas mantenimientos preventivos a tu moto?

4. ¿Has tenido problemas con fallas inesperadas o gastos imprevistos relacionados con tu moto?

5. ¿Cómo te comunicas actualmente con tu mecánico cuando necesitas una revisión o reparación?

Preguntas complementarias:

1. ¿Utilizas actualmente alguna aplicación o herramienta digital para registrar tus gastos o consumo de gasolina?

2. ¿Qué tan cómodo te sentirías si tu moto enviara automáticamente datos de su estado a una aplicación?

3. ¿Qué indicadores del estado de tu moto te gustaría conocer en tiempo real? (ejemplo: presión de neumáticos, combustible, temperatura del motor)

4. ¿Qué tan útil te parecería recibir alertas en tu celular sobre posibles fallas antes de que ocurran?

5. ¿Qué tipo de alertas te serían más útiles? (ejemplo: cambio de aceite, nivel de gasolina, revisión de frenos)

6. ¿Qué dispositivos usas más frecuentemente para organizarte o monitorear cosas? (móvil, laptop, tablet)

7. ¿Qué valoras más en una app para motos? (ejemplo: simplicidad, visualización clara de métricas, recordatorios)

8. ¿Cuánto estarías dispuesto a pagar por un servicio que prevenga fallos y prolongue la vida útil de tu moto?


- Diseño de entrevistas para Mecanicos

Preguntas principales:

1. ¿Podrías contarme un poco sobre ti? (edad, ocupación, experiencia laboral, ubicación del taller)

2. ¿Qué tipo de servicios brindas con mayor frecuencia en tu taller?

3. ¿Cómo registras actualmente el historial de mantenimiento de tus clientes?

4. ¿Cómo realizas actualmente el diagnóstico del estado de una moto cuando llega a tu taller?

5. ¿Te resultaría útil poder monitorear de forma remota el estado de las motos de tus clientes? ¿Por qué?

Preguntas complementarias:

1. ¿Qué tan común es que tus clientes lleguen con problemas que pudieron haberse evitado con un mantenimiento preventivo?

2. ¿Sueles recomendar a tus clientes llevar un control de gastos y mantenimientos? ¿Cómo lo haces?

3. ¿Usas alguna herramienta digital para organizar los diagnósticos o el historial de las motos?

4. ¿Qué tan útil te parecería contar con datos de telemetría en tiempo real (ejemplo: kilometraje, consumo, estado de batería) antes de recibir una moto en tu taller?

5.  ¿Qué métricas (ej. presión de neumáticos, consumo, temperatura) serían más valiosas para tu trabajo?

6.  ¿Qué tipo de reportes serían más valiosos para ti y para tus clientes?

7.  ¿Estarías dispuesto a ofrecer este servicio como un valor agregado a tus clientes? ¿Cómo lo integrarías a tu negocio?

8.  ¿Qué tan dispuesto estarías a recomendar a tus clientes una app vinculada con tu servicio?

9.  ¿Qué modelo de ingresos preferirías: una comisión por cada suscripción de tus clientes, o un plan que te permita supervisar toda tu cartera de clientes a un costo fijo?

10. ¿Qué valoras más en una herramienta digital para tu trabajo? (ejemplo: precisión, facilidad de uso, integración con otros sistemas)

#### 2.2.2 Registro de entrevistas
En esta sección se registran los puntos más relevantes de las entrevistas realizadas a los mecánicos y dueños de motos. Las entrevistas, en formato de video, se encuentran en el siguiente enlace: [Needfinding Interviews - NRG6](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202110291_upc_edu_pe/EUX6HJSrkWFLsupKCjibccgBqipXedXcpryQbgwV-mpKdQ?e=fp4EZr&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

A continuación, se presentan detalles de las entrevistas realizadas a los mecánicos:

| Entrevista 1              | ![Flavio](images/chapter-2/thumbnail-mecanico1-flavio.png) |
|---------------------------|------------------------------------------------------------|
| Nombre del entrevistado   | Flavio Gallardo                                            |
| Edad                      | 21                                                         |
| Distrito                  | San Miguel                                                 |
| Ocupación                 | Ayudante de mecánico                                       |
| Duración de la Entrevista | 4:20                                                       |
| Minuto de Inicio          | 0:00                                                       |

| Entrevista 2              | ![Juan](images/chapter-2/thumbnail-mecanico2-juan.png) |
|---------------------------|--------------------------------------------------------|
| Nombre del entrevistado   | Juan Cuellar                                           |
| Edad                      | 25                                                     |
| Distrito                  | Pueblo Libre                                           |
| Ocupación                 | Mecánico                                               |
| Duración de la Entrevista | 4:15                                                   |
| Minuto de Inicio          | 4:20                                                   |

| Entrevista 3              | ![Aldo](images/chapter-2/thumbnail-mecanico3-aldo.png) |
|---------------------------|--------------------------------------------------------|
| Nombre del entrevistado   | Aldo Vasquez                                           |
| Edad                      | 23                                                     |
| Distrito                  | Breña                                                  |
| Ocupación                 | Ayudante de mecánico                                   |
| Duración de la Entrevista | 3:58                                                   |
| Minuto de Inicio          | 8:18                                                   |

A continuación, se presentan detalles de las entrevistas realizadas a los dueños de motos:

| Entrevista 4              | ![Josue](images/chapter-2/thumbnail-motociclista1-josue.png) |
|---------------------------|--------------------------------------------------------------|
| Nombre del entrevistado   | Josue Paiva                                                  |
| Edad                      | 22                                                           |
| Distrito                  | San Miguel                                                   |
| Ocupación                 | Estudiante                                                   |
| Duración de la Entrevista | 5:40                                                         |
| Minuto de Inicio          | 12:10                                                        |

| Entrevista 5              | ![Mathias](images/chapter-2/thumbnail-motociclista2-mathias.png) |
|---------------------------|------------------------------------------------------------------|
| Nombre del entrevistado   | Mathias Diaz                                                     |
| Edad                      | 23                                                               |
| Distrito                  | Pueblo Libre                                                     |
| Ocupación                 | Profesor                                                         |
| Duración de la Entrevista | 7:34                                                             |
| Minuto de Inicio          | 17:49                                                            |

| Entrevista 6              | ![Jair Huamani](images/chapter-2/thumbnail-motociclista3-jair.png) |
|---------------------------|--------------------------------------------------------------------|
| Nombre del entrevistado   | Jair Huamani                                                       |
| Edad                      | 32                                                                 |
| Distrito                  | Huancavelica                                                       |
| Ocupación                 | Abogado                                                            |
| Duración de la Entrevista | 8:28                                                               |
| Minuto de Inicio          | 25:18                                                              |


#### 2.2.3 Análisis de entrevistas

**Segmento Objetivo: Mecánicos y talleres de servicio**

**Demografía:**  
La edad de los mecánicos entrevistados varía entre 21 y 25 años, con una experiencia laboral de 1 a 3 años. Todos trabajan en talleres urbanos de Lima y atienden principalmente motos de uso diario y delivery, lo que refleja un perfil joven, técnico y cercano a un público que depende de sus vehículos para generar ingresos. El 100 % tiene menos de 3 años de experiencia y el 67 % atiende mayoritariamente a repartidores y transporte urbano.*

**Servicios frecuentes:**  
Los servicios más comunes son cambios de aceite, ajustes de frenos, mantenimiento eléctrico básico, reparación de cadenas y revisión de neumáticos. Esto evidencia un enfoque en mantenimientos preventivos y correctivos rápidos, adaptados a clientes que necesitan volver a la pista en poco tiempo. El 100 % realiza cambios de aceite y revisión de frenos; el 67 % ofrece trabajos eléctricos y de neumáticos.*

**Gestión y diagnóstico:**  
El historial de clientes se maneja con libretas, memoria personal o Excel poco usado. El diagnóstico es manual y basado en experiencia, usando herramientas básicas como multímetro y revisión visual. Esto revela una falta de digitalización en procesos clave del taller. El 67 % gestiona historial en cuadernos/memoria y solo el 33 % usa Excel de manera básica.*

**Necesidades y oportunidades:**  
Los mecánicos ven valor en contar con telemetría remota (kilometraje, batería, combustible, temperatura, neumáticos) y reportes simples como historial, alertas de servicio y resúmenes mensuales. Prefieren un plan fijo para el taller en lugar de comisiones individuales, y valoran herramientas precisas, fáciles de usar y compatibles con WhatsApp, lo que abre una oportunidad para soluciones digitales simples, accesibles y prácticas. El 100 % considera útil la telemetría, el 100 % prefiere un plan fijo y el 100 % valora la facilidad de uso por encima de funciones complejas.*


### 2.3 Needfinding

#### 2.3.1 User Personas

**Segmento Objetivo: Mecánicos y talleres de servicio**

A continuación, se presenta el User Persona de Carlos Quispe. Él representa al mecánico joven y pragmático de Lima, enfocado en el mantenimiento rápido de motos de uso diario y delivery. Este perfil sintetiza las necesidades, frustraciones y motivaciones identificadas en el análisis, sirviendo como arquetipo del usuario objetivo para una solución digital que busca optimizar la gestión y el diagnóstico en talleres de servicio.

![user_persona1.png](images/chapter-2/user_persona1.png)

**Segmento Objetivo: Motociclistas**

A continuación, se presenta el perfil de Daniel Castro, un User Persona desarrollado para representar al segmento clave de motociclistas jóvenes y urbanos en Lima que han adoptado las motocicletas eléctricas como su principal medio de transporte. Este arquetipo sintetiza los hallazgos de la investigación de usuarios, encapsulando sus comportamientos, necesidades y metas.

![user_persona2.png](images/chapter-2/user_persona2.png)

#### 2.3.2 User Task Matrix

**1. Segmento 1: Mecánico de Motocicletas**

| Tarea                                               | Frecuencia | Severidad |
|-----------------------------------------------------|------------|-----------|
| Realizar diagnósticos precisos de fallas            | Alta       | Alta      |
| Optimizar tiempos de servicio                       | Alta       | Alta      |
| Recordar historial de mantenimientos de clientes    | Media      | Alta      |
| Fidelizar clientela mediante recordatorios de citas | Media      | Media     |
| Usar herramientas de diagnóstico manual             | Alta       | Media     |
| Implementar nuevas herramientas tecnológicas        | Baja       | Alta      |
| Anticipar fallas comunes de motos                   | Media      | Alta      |


**2. Segmento 2: Usuario Final de Motocicleta**

| Tarea                                               | Frecuencia | Severidad |
|-----------------------------------------------------|------------|-----------|
| Realizar mantenimientos preventivos                 | Baja       | Alta      |
| Confiar en su mecánico de confianza                 | Alta       | Media     |
| Recordar fechas de último mantenimiento             | Media      | Alta      |
| Detectar fallas solo cuando se presentan            | Alta       | Alta      |
| Buscar información en internet sobre problemas      | Media      | Media     |
| Administrar presupuesto de reparaciones             | Alta       | Alta      |
| Verificar el estado básico de la moto antes de usarla | Alta     | Media     |

#### 2.3.3 User Journey Mapping

En esta sección se presentan los User Journey Maps para los dos segmentos objetivo: mecánicos de motocicletas y usuarios finales de motocicletas. Estos mapas ilustran las etapas clave del viaje del usuario, sus acciones, pensamientos y emociones en cada fase, así como los puntos de contacto con la solución propuesta.

**1. User Journey Map - Mecánico de Motocicletas**

<img src="images/chapter-2/UJOURNEY1.png" alt="User1 Journey" />

**2. User Journey Map - Usuario Final de Motocicleta**

<img src="images/chapter-2/UJOURNEY2.png" alt="User2 Journey" />


#### 2.3.4 Empathy Mapping

En esta sección se presentan los Empathy Mapping por cada segmento objetivo definido.

**1. Empathy Map - Mecánico de Motocicletas**

![Empathy Map Mecánico](images/chapter-2/empathy-mecanico.png)

**2. Empathy Map - Usuario de Motocicleta**
![Empathy Map Dueño](images/chapter-2/empathy-dueno.png)

### 2.4 Big Picture EventStorming

**1. Definir eventos:**

<img src="images/chapter-2/event-storming-1.png" alt="Event Storming 1" />

**2. Definir comandos y agentes**

<img src="images/chapter-2/event-storming-2.png" alt="Event Storming 2" />

**3. Definir políticas**

<img src="images/chapter-2/event-storming-3.png" alt="Event Storming 3" />

**4. Definir vistas**

<img src="images/chapter-2/event-storming-4.png" alt="Event Storming 4" />

**6. Agregados**

<img src="images/chapter-2/event-storming-5.png" alt="Event Storming 5" />

**7. Bounded context**

<img src="images/chapter-2/event-storming-6.png" alt="Event Storming 6" />

### 2.5 Ubiquitous Language

| Término(inglés)      | Término(español)     | Definición(español)                                                                       |
|----------------------|----------------------|-------------------------------------------------------------------------------------------|
| Metric               | Métrica              | Dato cuantitativo sobre el estado o desempeño de la moto.                                 |
| Report               | Report               | Conjunto estructurado de métricas procesadas y visualizadas.                              |
| Comparison           | Comparación          | Análisis de diferencias entre métricas en distintos períodos o vehículos.                 |
| Alert                | Alerta               | Notificación preventiva generada a partir de una métrica crítica o fuera de rango.        |
| Historial            | Historial            | Registro acumulativo de eventos pasados relacionados con vehículos, servicios y clientes. |
| Service              | Servicio             | Intervención realizada por un mecánico.                                                   |
| Repair               | Reparación           | Acción específica para corregir un problema en la moto.                                   |
| Spent                | Gasto                | Desembolso económico relacionado con el vehículo.                                         |
| Client               | Cliente              | Dueño de moto asociado al historial.                                                      |
| Subscription         | Suscripción          | Vínculo activo entre mecánico y dueño de moto.                                            |
| Plan                 | Plan                 | Conjunto de beneficios y limitaciones (ejemplo: básico, premium).                         |
| State                | Estado               | Condición de la suscripción (activa, suspendida, cancelada).                              |
| Renewal              | Renovación           | Acción de extender la suscripción al vencer.                                              |
| Preventive alert     | Alerta preventiva    | Notificación emitida al detectar un valor fuera de rango normal.                          |
| Vehicle status       | Estado del vehículo  | Resumen general del bienestar (óptimo, regular, crítico).                                 |
| Diagnosis            | Diagnóstico          | Interpretación de métricas para indicar posibles fallas o recomendaciones.                |
| Vehicle              | Vehículo             | Moto registrada en la plataforma.                                                         |
| Owner                | Dueño                | Usuario principal que gestiona el vehículo.                                               |
| Authorized Mechanic  | Mecánico autorizado  | Usuario con acceso limitado al vehículo para servicios o diagnósticos.                    |
| Vehicle registration | Registro de vehículo | Proceso de alta inicial en el sistema.                                                    |

## Capítulo III: Requirements Specification

### 3.1 User Stories

### 3.2 Impact Mapping

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
