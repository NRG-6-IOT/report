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
