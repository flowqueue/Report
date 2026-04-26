<div align = "center">
  <img style="height: 150px" src=/assets/assets/chapter-1/UPC_logo_transparente.png alt="">
  <h1>Universidad Peruana de Ciencias Aplicadas</h1>
<h1>Facultad de Ingeniería</h1>
  <h2>Carrera de Ingeniería de Software</h2>
  <h2>Periodo 2610</h2>
  <h2>1ASI0730 - Aplicaciones Web </h2>
  <h2>NRC- 0730</h2>
  <br>
  <h2>Profesor - Jose Miguel Flores Ingaruca </h2>
  <h2>Informe de Trabajo TB1</h2>
  <br>
  <h2 >Startup - flowqueue </h2>
  <h2 >Producto - </h2>
  <br>
  <h2 >Integrantes</h2>
  <ul style="list-style: none; padding: 0;">
      <li><h3>U202315654 - Pillaca Vidal, Luis Angel</h3></li>
      <li><h3>U202417693 - Alexander Auden Aliaga Ocampo</h3></li>
      <li><h3>u202210764 - Daniel Elias Ruiz Huisa</h3></li>
      <li><h3> -  </h3></li>
  </ul>
  <br>
  <h4>abril del 2026</h4>
<br>
</div>
<div style="page-break-after: always;"></div>

## Contenido

- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo 1: Introducción](#capítulo-1-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
  - [Segmento — Ciudadanos usuarios de servicios públicos en Lima](#segmento--ciudadanos-usuarios-de-servicios-públicos-en-lima)
  - [Segmento — Personal administrativo de atención](#segmento--personal-administrativo-de-atención)
  - [Segmento — Supervisores o responsables de sede](#segmento--supervisores-o-responsables-de-sede)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
    - [Segmento objetivo 1: Ciudadanos usuarios de servicios públicos](#segmento-objetivo-1-ciudadanos-usuarios-de-servicios-públicos)
    - [Segmento objetivo 2: Personal administrativo de atención](#segmento-objetivo-2-personal-administrativo-de-atención)
    - [Segmento objetivo 3: Responsables o administradores de sede](#segmento-objetivo-3-responsables-o-administradores-de-sede)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [Debilidades](#debilidades)
  - [Oportunidades](#oportunidades)
  - [Amenazas](#amenazas)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
- [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [Segmentos a entrevistar](#segmentos-a-entrevistar)
  - [Datos generales a recolectar](#datos-generales-a-recolectar)
  - [Ciudadanos usuarios de servicios públicos (Segmento 1)](#ciudadanos-usuarios-de-servicios-públicos-segmento-1)
  - [Preguntas para personal administrativo (Segmento 2)](#preguntas-para-personal-administrativo-segmento-2)
  - [Preguntas para supervisores o responsables de sede (Segmento 3)](#preguntas-para-supervisores-o-responsables-de-sede-segmento-3)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. NeedFinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
- [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [User Task Matrix – Citizen](#user-task-matrix--citizen)
  - [User Task Matrix – Counter Operator](#user-task-matrix--counter-operator)
  - [User Task Matrix – Supervisor](#user-task-matrix--supervisor)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
- [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Domain-Level EventStorming](#461-domain-level-eventstorming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

**Criterio:** : La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.

<table>
  <tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>
  </table>



  ## Capítulo 1: Introducción
### 1.1. Startup Profile
Como peruanos y como equipo hemos creado FlowQueue, tiene como objetivo principal abordar la ineficiencia en la gestión de atención al público en instituciones del Perú, caracterizada por largas filas, tiempos de espera impredecibles y falta de transparencia en el orden de atención.
En entidades como RENIEC, EsSalud y Banco de la Nación, los usuarios enfrentan diariamente problemas relacionados con la organización de colas, lo que genera pérdida de tiempo, estrés y una mala experiencia de servicio.
En respuesta a esta problemática, hemos desarrollado la plataforma FlowQueue, un sistema web de gestión de colas virtuales que permite a las instituciones administrar turnos de atención de manera digital. La solución permite a los usuarios obtener tickets en línea, visualizar su posición en la cola en tiempo real y conocer el tiempo estimado de atención, reduciendo significativamente la necesidad de filas físicas.
#### 1.1.1. Descripción de la Startup
FlowQueue es una startup tecnológica enfocada en la digitalización y optimización de procesos de atención al cliente en instituciones públicas y privadas.
Nuestra plataforma funciona como un sistema centralizado de gestión de colas que permite:
Crear y administrar turnos virtuales por sede y tipo de servicio
Asignar tickets digitales a los usuarios
Visualizar el estado de atención en tiempo real
Estimar tiempos de espera dinámicamente
Gestionar múltiples sedes desde un único sistema
El sistema está diseñado con una arquitectura web moderna que integra un frontend interactivo con un backend robusto, permitiendo manejar múltiples usuarios concurrentes y actualizaciones en tiempo real.
A diferencia de soluciones tradicionales, FlowQueue no solo digitaliza el proceso de filas, sino que introduce herramientas de monitoreo, control y análisis que mejoran la eficiencia operativa de las instituciones y la experiencia del usuario.
La plataforma ofrece diferentes niveles de acceso, incluyendo usuarios finales (clientes) y administradores (personal de atención), garantizando una gestión estructurada y escalable del servicio.


#### 1.1.2. Perfiles de integrantes del equipo
<table>
  <tr>
    <th colspan="2"> Alexander Auden Aliaga Ocampo </th>
  </tr>
  <tr>
    <td> <img src="assets/assets/chapter-1/Alex.jpg" width=300px> </td>
    <td> Soy estudiante de ingeniería de software en la UPC, con conocimientos básicos en los lenguajes de programación como c++, python , css, html, javascript también conocimientos básicos en base de datos viendo Mongo DB y creando diagramas relaciones como no relacionales. Además poseo habilidades de empatía y buena comunicación con el equipo esto me permite ser productivo en el ámbito de grupos y en general. </td>
  </tr>
</table>

### 1.2. Solution Profile
#### 1.2.1. Antecedentes y problemática
En el Perú, miles de ciudadanos realizan diariamente trámites y solicitudes en entidades públicas del Estado, como registros de identidad, servicios de salud, bancos estatales y otras instituciones de atención masiva. Sin embargo, gran parte de estos procesos continúa desarrollándose mediante colas presenciales, tiempos de espera prolongados y poca visibilidad sobre el orden de atención. Esta situación genera incomodidad, pérdida de tiempo y una experiencia negativa para los usuarios, especialmente cuando deben reorganizar sus actividades personales, académicas o laborales para poder ser atendidos.
Aplicando la técnica de las 5W + 2H, se identifica lo siguiente:
 Who: ciudadanos que acuden a servicios públicos del Estado, así como personal administrativo encargado de organizar la atención.
 What: largas colas de espera, desorden en el flujo de atención y falta de información en tiempo real sobre los turnos.
 Where: entidades públicas de atención presencial en el Perú, especialmente aquellas con alta afluencia de usuarios.
 When: durante los horarios de atención en los que se concentran trámites, consultas o pagos.
 Why: porque muchos servicios todavía dependen de sistemas manuales o poco digitalizados para gestionar turnos y priorizar la atención.
 How: los usuarios deben acudir físicamente, esperar por largos periodos y depender de información limitada o poco clara.
 How much: esto se traduce en tiempo perdido, estrés, congestión en los establecimientos y menor eficiencia operativa para las instituciones.
A partir de ello, la problemática principal del proyecto se define como la ineficiencia en la gestión de colas de espera en servicios públicos del Estado, la cual afecta tanto a los ciudadanos como al personal que administra la atención. Por un lado, los usuarios enfrentan esperas extensas, incertidumbre y una experiencia poco satisfactoria. Por otro lado, las instituciones tienen dificultades para ordenar el flujo de personas, distribuir adecuadamente sus recursos y ofrecer una atención más transparente y predecible.
Frente a este contexto, la propuesta del equipo consiste en desarrollar una solución digital que permita gestionar colas de manera virtual, brindando a los usuarios la posibilidad de obtener un turno, visualizar su posición en la fila y estimar su tiempo de espera, mientras que el personal administrativo podrá monitorear y organizar la atención de forma más eficiente. El objetivo principal es reducir tiempos muertos, mejorar la experiencia del ciudadano y optimizar la gestión operativa de los servicios públicos.
Como delimitación inicial del proyecto, la solución se enfocará en instituciones públicas con alta demanda de atención presencial, y se implementará como una plataforma web accesible desde distintos dispositivos. Además, el alcance estará orientado a resolver el problema de organización y seguimiento de turnos, no a reemplazar el trámite en sí ni los procesos internos propios de cada entidad.

#### 1.2.2. Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements

### Segmento — Ciudadanos usuarios de servicios públicos en Lima

**Contexto:**  
Los ciudadanos que acuden a entidades públicas de atención al público, como RENIEC, EsSalud y Banco de la Nación, necesitan realizar trámites, consultas o pagos de forma rápida y ordenada. Buscan reducir tiempos de espera, evitar largas filas presenciales y contar con mayor visibilidad sobre su turno de atención.

**Observación:**  
Actualmente, los usuarios suelen enfrentarse a colas físicas extensas, tiempos de espera impredecibles y poca información sobre el estado real de la atención. En muchos casos, deben llegar con anticipación y permanecer largos periodos en el establecimiento sin certeza de cuándo serán atendidos, lo que genera pérdida de tiempo, incomodidad y estrés.

**Problema:**  
No existe una solución digital accesible y centralizada que permita a los ciudadanos obtener un turno de atención de manera remota, visualizar su posición en la cola en tiempo real y estimar con mayor precisión cuánto falta para ser atendidos.

**Pregunta clave:**  
¿Cómo diseñar una plataforma web que permita a los ciudadanos obtener turnos virtuales, monitorear en tiempo real el avance de la cola y optimizar su tiempo de espera en instituciones públicas de alta demanda?


### Segmento — Personal administrativo de atención

**Contexto:**  
El personal administrativo de instituciones públicas debe gestionar diariamente grandes volúmenes de usuarios, organizar el flujo de atención y procurar que el servicio sea lo más ordenado y eficiente posible. Sus funciones suelen estar relacionadas con la recepción, orientación, asignación de turnos y control del flujo de personas durante la atención.

**Observación:**  
En muchos casos, la gestión de colas todavía se realiza manualmente o mediante procesos poco eficientes, lo que ocasiona desorden, dificultades para controlar prioridades, retrasos en la atención y ausencia de métricas claras para evaluar el desempeño del servicio.

**Problema:**  
Las instituciones no cuentan con una herramienta digital centralizada que permita al personal administrativo gestionar turnos de manera eficiente, supervisar el flujo de atención en tiempo real y mejorar la organización del servicio.

**Pregunta clave:**  
¿Cómo implementar una plataforma web que permita al personal administrativo gestionar colas, controlar el estado de los turnos en tiempo real y optimizar la eficiencia operativa de la atención al público?

### Segmento — Supervisores o responsables de sede

**Contexto:**  
Los supervisores o responsables de sede tienen a su cargo el monitoreo del servicio de atención al ciudadano dentro de una oficina o en varias sedes de una misma institución. Necesitan conocer indicadores de tiempo de espera, volumen de usuarios y desempeño general de la atención para tomar decisiones que mejoren la operación.

**Observación:**  
La falta de un sistema centralizado dificulta la supervisión unificada del servicio, limita la comparación del rendimiento entre horarios o sedes y reduce la capacidad de tomar decisiones oportunas sobre redistribución de recursos y personal.

**Problema:**  
No existe una solución que permita a los responsables de sede monitorear la atención en tiempo real, visualizar indicadores clave y tomar decisiones basadas en datos para optimizar el servicio brindado al ciudadano.

**Pregunta clave:**  
¿Cómo diseñar una plataforma web que permita a los supervisores o responsables de sede monitorear el flujo de atención, identificar oportunidades de mejora y optimizar la distribución de recursos de manera eficiente?

##### 1.2.2.2. Lean UX Assumptions

  Assumptions Worksheet

En esta sección declaramos las suposiciones fundamentales sobre nuestro modelo de negocio y el comportamiento de los usuarios.

- **¿Quién es el usuario?**  
  Ciudadanos peruanos que realizan trámites en instituciones con alta demanda y personal administrativo de dichas entidades.

- **¿Dónde encaja nuestro producto?**  
  En el proceso de espera y gestión de turnos, sustituyendo la fila física por una virtual.

- **¿Qué problemas resolvemos?**  
  Pérdida de tiempo del usuario, falta de información en tiempo real, desorden administrativo y falta de métricas operativas en las instituciones.

- **¿Cuándo y cómo se usa nuestro producto?**  
  Se usa desde el dispositivo móvil del usuario antes de llegar o al llegar a la sede, y por el personal administrativo a través de una interfaz de gestión durante su jornada laboral.

- **¿Qué valor ofrecemos?**  
  Predictibilidad y ahorro de tiempo para el ciudadano; eficiencia y control de datos para la institución.

 Business Outcomes

Estos son los resultados medibles que FlowQueue espera lograr para las instituciones que adopten el sistema:

- **Reducción del tiempo promedio de espera:**  
  Lograr una disminución del 30% en el tiempo que los usuarios pasan físicamente en las instalaciones.

- **Aumento en la satisfacción del cliente:**  
  Incrementar el puntaje de satisfacción (NPS) del servicio de atención al público en un 25%.

- **Optimización de recursos:**  
  Reducción del 15% en costos operativos relacionados con la gestión manual de colas y personal de seguridad para control de filas.

- **Toma de decisiones basada en datos:**  
  Generación de reportes semanales de afluencia por sede que permitan ajustar el personal según la demanda real.

 Users

Identificamos los segmentos específicos que interactúan con la plataforma:

- **Usuarios Finales (Ciudadanos):**  
  Personas de entre 18 y 65 años que necesitan realizar trámites en RENIEC, EsSalud o Banco de la Nación y buscan optimizar su tiempo.

- **Personal de Atención (Operadores):**  
  Trabajadores de las instituciones que gestionan el llamado de turnos y la atención directa.

- **Administradores de Sede:**  
  Encargados de monitorear el flujo general de una o varias oficinas y generar reportes de rendimiento.

 User Outcomes

Lo que los usuarios esperan lograr o sentir al usar FlowQueue:

- **Sentido de Control:**  
  El usuario siente que tiene el control de su tiempo al saber exactamente cuántas personas hay delante de él.

- **Reducción del estrés:**  
  Menor ansiedad al no tener que estar físicamente de pie en una fila larga e incierta.

- **Eficiencia Laboral (Administrativos):**  
  El personal siente que su trabajo es más organizado y menos caótico, permitiéndoles enfocarse en la atención y no en el orden de la fila.

- **Transparencia:**  
  El usuario confía en que el sistema de turnos es justo y no existen saltos en el orden de llegada.

 Features

Funcionalidades clave que implementaremos para cumplir con los resultados anteriores:

- **Generación de Ticket Virtual:**  
  Los usuarios pueden obtener un turno digital desde el Landing Page o Web App sin estar presentes.

- **Monitor en Tiempo Real:**  
  Visualización dinámica de la posición actual y el tiempo estimado para ser atendido.

- **Sistema de Notificaciones:**  
  Alertas automáticas cuando el turno del usuario esté próximo a ser llamado.

- **Dashboard Administrativo:**  
  Interfaz para que el personal gestione la cola, asigne prioridades y marque turnos como completados.

- **Módulo de Analítica:**  
  Herramientas de reporte para visualizar tiempos de espera históricos y picos de demanda por sede.

- **Gestión Multi-Sede:**  
  Capacidad de administrar diferentes ubicaciones geográficas desde una única cuenta de administrador corporativo.

##### 1.2.2.3. Lean UX Hypothesis Statements

Estas validan si FlowQueue funciona como negocio y aporta valor a las instituciones.

 Hypothesis de negocio

- **Hipótesis 1 – Reducción de tiempos:**  
  Creemos que implementar un sistema de turnos virtuales en instituciones públicas reducirá el tiempo promedio de espera presencial de los usuarios. Sabremos que esto es cierto si el tiempo de permanencia en sede disminuye al menos en un 30% dentro de los primeros 3 meses.

- **Hipótesis 2 – Satisfacción del cliente:**  
  Creemos que brindar información en tiempo real sobre el estado de la cola aumentará la satisfacción del usuario. Sabremos que esto es cierto si el NPS aumenta en un 25% tras la implementación.

- **Hipótesis 3 – Reducción de costos operativos:**  
  Creemos que digitalizar la gestión de colas reducirá la necesidad de personal dedicado al control físico de filas. Sabremos que esto es cierto si los costos operativos asociados disminuyen en al menos un 15%.

- **Hipótesis 4 – Toma de decisiones basada en datos:**  
  Creemos que proporcionar reportes de analítica permitirá a las instituciones optimizar la asignación de personal. Sabremos que esto es cierto si los administradores utilizan los reportes semanalmente y logran ajustar horarios o recursos en al menos 1 decisión operativa por semana.

- **Hipótesis 5 – Adopción del sistema:**  
  Creemos que las instituciones con alta demanda adoptarán un sistema digital de colas si mejora su eficiencia operativa. Sabremos que esto es cierto si al menos el 60% de las sedes piloto continúan usando el sistema después de 2 meses.

 Hypothesis de usuarios

- **Hipótesis 1 – Uso antes de llegar:**  
  Creemos que los ciudadanos preferirán obtener su turno antes de llegar a la sede usando su celular. Sabremos que esto es cierto si al menos el 70% de los tickets se generan de forma remota.

- **Hipótesis 2 – Reducción de estrés:**  
  Creemos que visualizar su posición en la cola reducirá la ansiedad del usuario. Sabremos que esto es cierto si el 80% de los usuarios reporta menor estrés en encuestas post-servicio.

- **Hipótesis 3 – Confianza en el sistema:**  
  Creemos que un sistema transparente de turnos aumentará la confianza del usuario en el proceso. Sabremos que esto es cierto si menos del 5% de los usuarios reporta quejas por desorden o injusticia en la fila.

- **Hipótesis 4 – Uso de notificaciones:**  
  Creemos que los usuarios dependen de notificaciones para acercarse a tiempo a su turno. Sabremos que esto es cierto si al menos el 65% de los usuarios llega justo antes de ser llamado, en lugar de esperar físicamente.
  

- **Hipótesis 5 – Eficiencia del personal:**  
  Creemos que los operadores podrán gestionar turnos más eficientemente con un dashboard digital. Sabremos que esto es cierto si el tiempo promedio de atención por usuario se reduce o se mantiene estable con mayor volumen.


##### 1.2.2.4. Lean UX Canvas

| **Sección** | **Descripción** |
|------------|-----------------|
| **1. Problema / Oportunidad** | En instituciones públicas del Perú, como RENIEC, EsSalud y Banco de la Nación, los usuarios enfrentan largas filas, tiempos de espera impredecibles y poca transparencia en el orden de atención. Esto genera pérdida de tiempo, estrés y una mala experiencia de servicio. FlowQueue busca digitalizar y optimizar la gestión de colas mediante una plataforma web de turnos virtuales y monitoreo en tiempo real. |
| **2. Usuarios y Clientes** | **Usuarios:** Ciudadanos que realizan trámites en instituciones públicas, personal administrativo de atención y supervisores o responsables de sede. <br> **Clientes:** Instituciones públicas que necesitan optimizar su atención al ciudadano, reducir tiempos de espera y mejorar el control operativo de sus sedes. |
| **3. Supuestos** | Los ciudadanos adoptarán una solución digital si les permite ahorrar tiempo y conocer el estado de su turno en tiempo real; el personal administrativo utilizará la plataforma si simplifica la gestión de colas y mejora la organización de la atención; los supervisores o responsables de sede valorarán la solución si les proporciona métricas útiles para monitorear el servicio y tomar decisiones; las instituciones estarán dispuestas a implementar la solución si reduce tiempos de espera, mejora la satisfacción del usuario y optimiza la operación. |
| **4. Necesidades del Usuario** | Obtener turnos sin hacer filas físicas, conocer la posición en la cola, recibir información clara sobre el tiempo estimado de atención, gestionar turnos en tiempo real, priorizar casos cuando sea necesario, monitorear el flujo de atención, acceder a reportes, identificar horas pico y optimizar recursos en la sede. |
| **5. Solución Propuesta** | Plataforma web orientada a la gestión de colas virtuales en instituciones públicas, desarrollada para permitir a los ciudadanos generar tickets digitales, visualizar su posición en la cola y recibir notificaciones sobre su turno, mientras que el personal administrativo podrá gestionar la atención y los supervisores accederán a reportes e indicadores para el monitoreo del servicio. |
| **6. Resultados (Outcomes)** | **Resultados esperados:** Reducción del tiempo de espera presencial, mejora en la experiencia del ciudadano, mayor organización del flujo de atención y mejor capacidad de supervisión institucional. <br> **KPIs:** Tiempo promedio de espera, cantidad de tickets generados, porcentaje de usuarios atendidos a tiempo, nivel de satisfacción del usuario, frecuencia de uso del sistema y número de sedes activas. |
| **7. Experimentos** | Pruebas de usabilidad con usuarios potenciales, validación del flujo de generación de ticket virtual, simulación del monitoreo de cola en tiempo real, pruebas del dashboard administrativo, evaluación del módulo de métricas y encuestas para comprobar que el MVP cubre las necesidades esenciales de ciudadanos, personal administrativo y supervisores. |
| **8. MVP (Producto Mínimo Viable)** | Registro e inicio de sesión, selección de entidad o sede, selección de trámite, generación de ticket virtual, visualización de posición en la cola, tiempo estimado de atención, notificaciones previas, dashboard administrativo para gestionar turnos y panel básico de métricas para supervisión. |

### 1.3. Segmentos objetivo

#### Segmento objetivo 1: Ciudadanos usuarios de servicios públicos
Este segmento está conformado por personas que acuden a entidades públicas del Estado para realizar trámites, consultas, pagos o solicitudes. Incluye jóvenes, adultos y adultos mayores, generalmente entre los 18 y 65 años, residentes en zonas urbanas, que valoran la rapidez, el orden y la previsibilidad en la atención. Muchos de ellos utilizan teléfonos móviles y servicios digitales básicos, por lo que podrían adaptarse a una solución web que les permita gestionar su turno sin permanecer físicamente en una cola por largos periodos.

**Sus principales necesidades son:**
- reducir el tiempo de espera,
- evitar aglomeraciones,
- conocer con claridad cuándo serán atendidos,
- y tener una experiencia más ordenada y menos estresante.

#### Segmento objetivo 2: Personal administrativo de atención
Este segmento incluye a los trabajadores responsables de organizar la atención al público dentro de las instituciones estatales. Suelen desempeñar funciones vinculadas con recepción, orientación, asignación de turnos y control del flujo de usuarios. Requieren herramientas que les permitan visualizar la cola en tiempo real, priorizar casos cuando corresponda y mantener un mayor control operativo.

**Sus necesidades principales son:**
- organizar de forma eficiente el flujo de usuarios,
- reducir el desorden en la atención,
- mejorar la distribución de turnos,
- y contar con información útil para tomar decisiones operativas.

#### Segmento objetivo 3: Responsables o administradores de sede
Este segmento agrupa a supervisores o encargados de una sede o área de atención. Tienen interés en monitorear indicadores de tiempo de espera, volumen de usuarios y desempeño del servicio. Buscan soluciones que no solo ayuden a ordenar la atención, sino que también generen datos para evaluar mejoras en la operación.

**Sus principales necesidades son:**
- supervisar la atención de forma centralizada,
- identificar horas pico,
- optimizar recursos,
- y mejorar la calidad del servicio brindado al ciudadano.

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

En el mercado existen diversas soluciones que abordan la gestión de colas y atención al cliente, tanto a nivel local como internacional. Los principales competidores identificados son:
<b>Competidores directos:</b>
- <b>Qmatic</b>
  Plataforma global especializada en sistemas de gestión de colas y experiencia del cliente en instituciones públicas y privadas.
- Turnero (sistemas de turnos digitales locales)
 Soluciones implementadas por algunas entidades en Perú o LATAM que permiten asignación básica de turnos, generalmente sin monitoreo en tiempo real avanzado.
- <b>Queue-it</b>
 Sistema enfocado en la gestión de colas virtuales principalmente para tráfico web (ej. alta demanda en sitios), pero aplicable a gestión de acceso.
<b>Competidores indirectos:</b>
- <b>Sistemas manuales o semi-digitales</b>
 (tickets físicos, Excel, atención por orden de llegada).
- **Aplicaciones internas de instituciones**
 Algunas entidades desarrollan sistemas propios limitados a una sola sede o servicio.
- **Plataformas de citas previas**
 Sistemas que permiten agendar citas, pero no gestionan colas dinámicas en tiempo real.

#### 2.1.1. Análisis competitivo
Competitive Analysis Landscape

 ¿Por qué llevar a cabo este análisis?

- Identificar las brechas existentes en el mercado peruano.
- Evaluar las fortalezas y limitaciones de los competidores directos e indirectos.
- Definir estrategias de diferenciación para SafeHome, enfocadas en accesibilidad, integración IoT y una plataforma web responsive.
- Validar que la solución propuesta responde a necesidades reales no cubiertas de manera integral.

---

**Competidores**

**Overview**
| Overview | FlowQueue | Qminder | QLess | Inalto |
|----------|----------|---------|-------|--------|
| | FlowQueue es una startup peruana que ofrece una plataforma web de gestión de colas virtuales orientada a instituciones públicas y privadas. | Qminder es una plataforma SaaS global especializada en la gestión de colas y experiencia del cliente. | QLess es un sistema de colas virtuales basado en la nube con registro remoto. | Inalto es una empresa peruana con sistema híbrido que integra web/app con hardware. |

---

**Perfil**

**Ventaja competitiva**

| Ventaja competitiva | FlowQueue | Qminder | QLess | Inalto |
|---------------------|----------|---------|-------|--------|
| | - Plataforma 100% web<br>- Sin instalación ni hardware<br>- Adaptado al contexto peruano<br>- Reducción de tiempos de espera<br>- Escalabilidad multi-sede | - Plataforma madura internacional<br>- Notificaciones automatizadas<br>- Analítica avanzada<br>- Integraciones empresariales | - Eliminación total de filas físicas<br>- Plataforma cloud escalable<br>- Enfoque UX<br>- Implementación multisector | - Presencia local<br>- Solución hardware + software<br>- Adaptabilidad sectorial<br>- Soporte técnico local |

---

**Perfil de marketing**

**Mercado objetivo**

| Mercado Objetivo | FlowQueue | Qminder | QLess | Inalto |
|-----------------|----------|---------|-------|--------|
| | Instituciones públicas y privadas peruanas | Empresas globales, hospitales, bancos, universidades | Empresas globales, hospitales, bancos, universidades | Empresas peruanas con infraestructura física |

**Estrategias de marketing**

| Estrategias | FlowQueue | Qminder | QLess | Inalto |
|------------|----------|---------|-------|--------|
| | - Alianzas con el Estado<br>- Pilotos institucionales<br>- Enfoque GovTech | - Marketing digital global<br>- SaaS B2B<br>- Casos de éxito | - Marketing digital global<br>- SaaS B2B<br>- Casos de éxito | - Ventas directas<br>- Implementaciones personalizadas<br>- Relación comercial local |

---

**Perfil de producto**

**Productos & Servicios**

| Productos & Servicios | FlowQueue | Qminder | QLess | Inalto |
|----------------------|----------|---------|-------|--------|
| | Plataforma web + monitoreo en tiempo real | SaaS de gestión de filas + analítica + notificaciones | SaaS de gestión de filas + analítica + notificaciones | Sistema híbrido (software + kioscos + pantallas) |

**Precios y costos**

| Precios y Costos | FlowQueue | Qminder | QLess | Inalto |
|------------------|----------|---------|-------|--------|
| | SaaS accesible (suscripción) | Suscripción SaaS (costo medio-alto) | Suscripción SaaS (costo medio-alto) | Costos altos por implementación + hardware |

**Canales**

| Canales | FlowQueue | Qminder | QLess | Inalto |
|---------|----------|---------|-------|--------|
| | Web responsive | Web + móvil | Web + móvil | Web + app + hardware físico |

---

**Análisis SWOT**

**Fortalezas**

| Fortalezas | FlowQueue | Qminder | QLess | Inalto |
|-----------|----------|---------|-------|--------|
| | - Adaptado a Perú<br>- 100% web<br>- Bajo costo<br>- Enfoque UX | - SaaS consolidado<br>- Presencia internacional<br>- Analítica avanzada<br>- Alta confiabilidad | - Eliminación de filas<br>- Cloud escalable<br>- UX optimizada<br>- Experiencia multisector | - Presencia local<br>- Solución completa<br>- Soporte técnico<br>- Experiencia implementación |

---

### Debilidades

| Debilidades | FlowQueue | Qminder | QLess | Inalto |
|------------|----------|---------|-------|--------|
| | - Bajo reconocimiento<br>- Recursos limitados<br>- Dependencia institucional<br>- Menor desarrollo tecnológico | - Costos elevados<br>- No adaptado a Perú<br>- Dependencia técnica | - Costos altos<br>- Enfoque global<br>- Dependencia conectividad | - Dependencia hardware<br>- Implementación compleja<br>- Menor flexibilidad<br>- Escalabilidad limitada |

---

### Oportunidades

| Oportunidades | FlowQueue | Qminder | QLess | Inalto |
|--------------|----------|---------|-------|--------|
| | - Digitalización del sector público<br>- Alta demanda<br>- Falta de soluciones locales<br>- Expansión LATAM | - Expansión LATAM<br>- Adopción cloud<br>- Integraciones empresariales | - Crecimiento GovTech<br>- Sector público<br>- Digitalización | - Digitalización empresas<br>- Proyectos institucionales<br>- Modernización |

---

### Amenazas

| Amenazas | FlowQueue | Qminder | QLess | Inalto |
|----------|----------|---------|-------|--------|
| | - Competidores globales<br>- Soluciones híbridas<br>- Resistencia al cambio<br>- Presupuesto estatal | - Competidores económicos<br>- Barreras culturales<br>- Regulaciones | - Nuevos SaaS<br>- Limitación local<br>- Competencia híbrida | - SaaS simples<br>- Competidores internacionales<br>- Cambio a web |

#### 2.1.2. Estrategias y tácticas frente a competidores

### 2.2. Entrevistas
## 2.2.1. Diseño de entrevistas

Las entrevistas tienen como propósito comprender cómo viven actualmente los ciudadanos y el personal administrativo el proceso de atención presencial en servicios públicos del Estado, identificar frustraciones, necesidades y oportunidades de mejora, y recopilar información suficiente para construir user personas y definir requerimientos funcionales del producto.

### Segmentos a entrevistar

- **Segmento 1:** Ciudadanos usuarios de servicios públicos
- **Segmento 2:** Personal administrativo de atención
- **Segmento 3:** Responsables o supervisores de sede

### Datos generales a recolectar

Para cada entrevistado se recogerá:

- Nombres y Apellidos
- Edad
- Distrito
- Ocupación
- Frecuencia con la que utiliza o gestiona servicios públicos
- Dispositivo que usa con mayor frecuencia
- Canales digitales que suele utilizar

### Ciudadanos usuarios de servicios públicos (Segmento 1)

**Preguntas principales:**

1. ¿Con qué frecuencia acudes a entidades públicas para realizar trámites?
2. ¿Qué tipo de problemas sueles enfrentar cuando haces cola?
3. ¿Cuánto tiempo sueles esperar antes de ser atendido?
4. ¿Qué es lo que más te molesta: el tiempo de espera o la falta de información?
5. Si pudieras ver información en tiempo real mientras esperas, ¿qué te gustaría saber?
6. ¿Usarías una plataforma web para sacar turno y monitorear tu lugar en la cola? ¿Por qué?

### Preguntas para personal administrativo (Segmento 2)

**Preguntas principales:**

1. ¿Cómo se organiza actualmente la atención al público en su institución?
2. ¿Cuáles son los principales problemas en la gestión de colas?
3. ¿Qué dificultades enfrenta el personal para controlar el flujo de usuarios?
4. ¿En qué momentos del día hay mayor congestión de usuarios?
5. ¿Qué información o herramientas le ayudarían a mejorar la atención?
6. ¿Considera útil una plataforma que gestione turnos en tiempo real? ¿Por qué?

### Preguntas para supervisores o responsables de sede (Segmento 3)

**Preguntas principales:**

1. ¿Cuáles son los mayores retos al gestionar la atención al público?
2. ¿Cómo evalúan actualmente la eficiencia del servicio?
3. ¿Qué indicadores consideran más importantes (tiempo de espera, cantidad de usuarios, etc.)?
4. ¿Qué problemas se repiten con más frecuencia en la atención?
5. ¿Qué beneficios esperaría de una plataforma de colas virtuales?
6. ¿La institución estaría dispuesta a adoptar una solución digital si mejora la eficiencia?
#### 2.2.2. Registro de entrevistas
#### 2.2.3. Análisis de entrevistas

### 2.3. NeedFinding
#### 2.3.1. User Personas
## 2.3.2. User Task Matrix

### User Task Matrix – Citizen

| Tarea del usuario | Frecuencia | Importancia |
|-------------------|-----------|-------------|
| Consultar disponibilidad de atención | Alta | Alta |
| Obtener un turno | Alta | Alta |
| Ver posición en la cola | Alta | Alta |
| Recibir notificaciones de atención | Media | Alta |
| Reprogramar o cancelar turno | Media | Media |
| Estimar tiempo de espera | Alta | Alta |
| Evitar desplazamiento innecesario | Alta | Alta |
| Validar requisitos del trámite | Media | Alta |
| Acceder a información del trámite | Media | Alta |

### User Task Matrix – Counter Operator

| Tarea del usuario | Frecuencia | Importancia |
|-------------------|-----------|-------------|
| Registrar usuarios en cola | Alta | Alta |
| Visualizar cola en tiempo real | Alta | Alta |
| Llamar al siguiente usuario | Alta | Alta |
| Priorizar casos especiales | Media | Alta |
| Reorganizar turnos | Media | Alta |
| Controlar flujo de atención | Alta | Alta |
| Comunicar incidencias | Media | Media |
| Gestionar usuarios ausentes | Media | Media |
| Validar asistencia del usuario | Alta | Alta |

### User Task Matrix – Supervisor

| Tarea del usuario | Frecuencia | Importancia |
|-------------------|-----------|-------------|
| Monitorear tiempos de espera | Alta | Alta |
| Identificar horas pico | Media | Alta |
| Evaluar desempeño del personal | Media | Alta |
| Tomar decisiones operativas | Media | Alta |
| Supervisar múltiples colas | Alta | Alta |
| Generar reportes | Media | Media |
| Detectar cuellos de botella | Media | Alta |
| Optimizar asignación de recursos | Media | Alta |
| Analizar satisfacción del usuario | Baja | Media |#### 2.3.3. User Journey Mapping
#### 2.3.4. Empathy Mapping

### 2.4. Big Picture EventStorming

## 2.5. Ubiquitous Language

En esta sección se definen los términos clave del dominio de **FlowQueue**. Estos términos son de uso obligatorio para el equipo de desarrollo, los interesados y los usuarios finales, garantizando una comunicación sin ambigüedades.

---

**Administrative Dashboard**  
Interfaz de gestión centralizada donde el *Headquarters Supervisor* visualiza indicadores de rendimiento, métricas de atención y supervisa el estado operativo de las sedes.

**Citizen**  
Usuario final que accede a la plataforma para buscar instituciones, emitir un *Digital Ticket* y realizar el seguimiento de su turno de forma remota.

**Counter Operator**  
Personal de la institución encargado de gestionar el flujo de la *Virtual Queue* desde un *Service Counter*, realizando llamados y finalizando atenciones.

**Digital Ticket**  
Identificador único generado por el sistema que representa el turno del *Citizen*. Incluye código de turno, hora de emisión y un código QR para validación.

**Headquarters Supervisor**  
Rol administrativo responsable de monitorear la eficiencia de la sede y tomar decisiones basadas en analítica de datos.

**Queue Status**  
Información dinámica que indica la posición del usuario en la fila, el número de turnos restantes y el estado actual de la atención en sala.

**Real-Time Update**  
Mecanismo de sincronización que asegura que los cambios en la *Virtual Queue* se reflejen instantáneamente en todos los dispositivos conectados.

**Service Counter**  
Punto de atención físico (ventanilla) asignado a un *Counter Operator* para realizar el trámite solicitado por el *Citizen*.

**Service Type**  
Categorización de trámites que define a qué flujo o *Virtual Queue* específico ingresará el usuario.

**Virtual Queue**  
Estructura lógica y digital que organiza el orden de llegada de los usuarios, eliminando la necesidad de una fila física en la sede.

**Waiting Time Estimate**  
Tiempo aproximado de espera calculado mediante algoritmos que consideran el ritmo de atención actual de los *Counter Operators*.

## Capítulo III: Requirements Specification

### 3.1. User Stories
### 3.2. Impact Mapping
### 3.3. Product Backlog

## Capítulo IV: Product Design

### 4.1. Style Guidelines
#### 4.1.1. General Style Guidelines
#### 4.1.2. Web Style Guidelines

### 4.2. Information Architecture
#### 4.2.1. Organization Systems
#### 4.2.2. Labeling Systems
#### 4.2.3. SEO Tags and Meta Tags
#### 4.2.4. Searching Systems
#### 4.2.5. Navigation Systems

### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe
#### 4.3.2. Landing Page Mock-up

### 4.4. Web Applications UX/UI Design
#### 4.4.1. Web Applications Wireframes
#### 4.4.2. Web Applications Wireflow Diagrams
#### 4.4.3. Web Applications Mock-ups
#### 4.4.4. Web Applications User Flow Diagrams

### 4.5. Web Applications Prototyping

### 4.6. Domain-Driven Software Architecture
#### 4.6.1. Domain-Level EventStorming
#### 4.6.2. Software Architecture Context Diagram
#### 4.6.3. Software Architecture Container Diagrams
#### 4.6.4. Software Architecture Components Diagrams

### 4.7. Software Object-Oriented Design
#### 4.7.1. Class Diagrams

### 4.8. Database Design
#### 4.8.1. Database Diagrams

## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
#### 5.1.2. Source Code Management
#### 5.1.3. Source Code Style Guide & Conventions
#### 5.1.4. Software Deployment Configuration

### 5.2. Landing Page, Services & Applications Implementation
#### 5.2.1. Sprint 1
