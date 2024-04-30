# LTI-ODG - Diseño de sistema ATS
## Generado con:
* Claude 3 Haiku con GPT-3.5
* Microsoft Copilot con GPT-4

## Conversación con Claude 3 Haiku
> Ver conversación completa: [click aquí](https://claude.ai/chat/f8a2068a-3964-496d-ab9e-e05b068b9a90)

### Prompt 1:
Confírmame qué sabes acerca de un Applicant-Tracking System

### Prompt 2:
Genial, quiero diseñar un sistema de ATS y tu me vas a ayudar en el proceso. Vamos a ir paso a paso. No continues con el siguiete paso hasta que no te lo indique. Confírmame que entendiste la forma en que vamos a trabajar

### Prompt 3:
Bien, el sistema ATS debe diferenciarse de las soluciones actuales teniendo en cuenta, entre otras, las siguientes características:

Aumentar la eficiencia para los departamentos de HR
Mejorar la colaboración en tiempo real entre reclutadores y managers
Automatizaciones
Asistencia de IA en diversas tareas
Etc.

La primera fase es de lluvia de ideas. Quiero que analices la información dada y me ayudes a identificar qué otras claves de éxito debo tener en cuenta para diseñar un sistema que se destaque por encima de los competidores actuales del mercado. Dame los resultados en forma de lista

### Prompt 4:
Dame un listado de todas las características del sistema ATS, incluyendo las que yo te di anteriormente en el prompt y las que me acabas de dar tu como respuesta. El objetivo inicial es tener un compilado de todas las características

### Prompt 5:
Vamos a crear el primer artefacto del diseño del sistema ATS. Para esto, dame la siguiente información en formato markdown agregando un índice al inicio del documento:

Descripción breve del software LTI
El valor añadido y las ventajas competitivas con base en el listado de características que me acabas de suministrar. Revisa si hay alguna que se repita y utiliza la información sin duplicados
Explicación de las funciones principales.

### Prompt 6:
Conoces el modelo de negocio "Lean Canvas"?

### Prompt 7:
Perfecto, quiero que me generes el contenido detallado para un diagrama de Lean Canvas relacionado con nuestro ATS. Toma como base la información que tienes hasta el momento y agrega por tu cuenta la que falte. Dame la información en formato xml y luego aparte la descripción detallada del contenido en texto y lista de items para tener un mayor detalle

<details>
  <summary>Respuesta de ChatGPT</summary>

  1. Problema:

      Los procesos de reclutamiento y contratación en las empresas suelen ser lentos, ineficientes y con poca colaboración entre los diferentes actores involucrados.


  2. Segmento de clientes:

  * Departamentos de Recursos Humanos y reclutamiento de empresas de todos los tamaños y sectores.
  * Empresas con altos volúmenes de contratación.
  * Empresas que buscan optimizar y agilizar sus procesos de reclutamiento.


  3. Propuesta de valor única:

      Un sistema ATS innovador que aprovecha la automatización y la inteligencia artificial para optimizar todo el proceso de reclutamiento, mejorando la eficiencia, colaboración y experiencia de usuario.


  4. Solución:

      **Nombre**: Sistema ATS (Applicant Tracking System).
      **Descripción**: Software integral de gestión del proceso de reclutamiento y contratación, con funciones de automatización, IA, análisis de datos, colaboración en tiempo real y capacidades multimedia.


  5. Métricas clave:

  * Tiempo de contratación promedio.
  * Costos de reclutamiento por contratación.
  * Tasa de abandono de candidatos.
  * Satisfacción de clientes y candidatos.


  6. Ventaja especial:

  * Asistencia de Inteligencia Artificial en diversas tareas.
  * Experiencia de usuario mejorada e intuitiva.
  * Automatización de procesos y tareas repetitivas.
  * Análisis de datos avanzados y generación de informes personalizados.


  7. Canales:

  * Equipo de ventas directas.
  * Sitio web y marketing en línea.
  * Alianzas con proveedores de software de RRHH.
  * Asistencia a ferias y eventos de la industria.


  8. Estructura de costos:

  * Desarrollo y mantenimiento del software.
  * Recursos humanos (equipo de ingeniería, ventas, soporte).
  * Infraestructura de TI y hosting.
  * Marketing y adquisición de clientes.


  9. Fuentes de ingresos:

  * Suscripciones mensuales/anuales según planes de pago.
  * Cargos por implementación y configuración personalizada.
  * Servicios adicionales de consultoría y soporte.
</details>

## Conversación con Microsoft Copilot
> Ver conversación completa: [click aquí](https://sl.bing.net/iQ1HFA1V6vQ)

### Prompt 1:
Te voy a pasar un archivo makdown con el diseño de un ATS que se encuentra incompleto. Necesito que lo tomes como base para lo que vamos a realizar de aquí en adelante

### Prompt 2:
Confírmame que entendiste el contexto del sistema ATS que estoy desarrollando

### Prompt 3:
Identifica los tres casos de uso principales y dame una descripción detallada teniendo en cuenta lo siguiente:
"
- Identificar los diferentes roles del usuario que interactúan con el producto
- Identificar las acciones que cada uno de ellos realizará en el sistema
- Las dependencias de unas acciones con otras:
    - Comprar requiere registrarse
    - Acceder al perfil requiere autenticarse
    - Etc."

<details>
  <summary>Respuesta de Microsoft Copilot</summary>

  **Caso de Uso 1: Publicación de Vacantes**
  * Roles de Usuario:
    * Reclutador: Publica nuevas ofertas de trabajo.
    * Manager de Contratación: Aprueba las vacantes antes de su publicación.
  * Acciones:
    * El Reclutador crea una nueva oferta de trabajo en el sistema.
    * El Manager de Contratación revisa y aprueba la oferta de trabajo.
    * Una vez aprobada, la vacante se publica automáticamente en los canales seleccionados.
  * Dependencias:
    * La aprobación de la vacante por parte del Manager de Contratación es necesaria antes de la publicación.
    * El Reclutador debe estar autenticado en el sistema para crear y enviar la oferta de trabajo.

  **Caso de Uso 2: Proceso de Selección de Candidatos**
  * Roles de Usuario:
    * Candidato: Aplica a las ofertas de trabajo y completa las evaluaciones requeridas.
    * Reclutador: Revisa las aplicaciones y selecciona candidatos para entrevistas.
  * Acciones:
    * El Candidato se registra en el sistema, completa su perfil y aplica a las vacantes.
    * El Reclutador utiliza la IA para filtrar y clasificar las aplicaciones.
    * Los candidatos seleccionados son notificados y programados para entrevistas.
  * Dependencias:
    * Los Candidatos deben registrarse y completar su perfil para aplicar a las vacantes.
    * El Reclutador necesita autenticarse para acceder a las aplicaciones y gestionar el proceso de selección.

  **Caso de Uso 3: Integración con Herramientas de RRHH**
  * Roles de Usuario:
    * Administrador de Sistemas: Configura y mantiene la integración con otras herramientas de RRHH.
    * Reclutador: Utiliza las herramientas integradas para mejorar el proceso de reclutamiento.
  * Acciones:
    * El Administrador de Sistemas establece conexiones con plataformas de RRHH externas.
    * El Reclutador accede a las herramientas integradas para realizar tareas como la evaluación de competencias o la verificación de antecedentes.
  * Dependencias:
    * La configuración por parte del Administrador de Sistemas es necesaria para la integración funcional.
    * El Reclutador debe tener permisos adecuados para utilizar las herramientas integradas.

Estos casos de uso reflejan interacciones clave dentro del sistema ATS y cómo diferentes roles de usuario dependen de ciertas acciones y permisos para llevar a cabo sus tareas eficientemente. Si necesitas más detalles o casos de uso adicionales, no dudes en pedirlo.
</details>

### Prompt 4:
Representa estos casos de uso en el tipo de diagrama más adecuado usando el formato plantUML. Diferencia entre usuarios visitantes y usuarios logueados. Acorde a la sintaxis y buenas prácticas UML, define y describe lo que sea necesario.

### Prompt 5:
Separa el diagrama en los tres casos de uso principales sin quitar detalle de la información

<details>
  <summary>Caso de Uso 1: Publicación de Vacantes</summary>

  ```
    @startuml
    left to right direction
    skinparam packageStyle rectangle

    actor "Usuario Logueado" as Authenticated
    actor "Reclutador" as Recruiter
    actor "Manager de Contratación" as HiringManager

    rectangle "Publicación de Vacantes" {
      usecase "Crear Vacantes" as UC1
      usecase "Revisar y Aprobar Vacantes" as UC2
      usecase "Publicar Vacantes Aprobadas" as UC3

      Authenticated --> UC1 : Crea vacantes
      Recruiter <|-- Authenticated : Especialización
      Recruiter --> UC1 : Inicia
      HiringManager <|-- Authenticated : Especialización
      HiringManager --> UC2 : Aprueba
      Recruiter --> UC3 : Publica
    }
    @enduml
  ```
</details>
<details>
  <summary>Caso de Uso 2: Proceso de Selección de Candidatos</summary>

  ```
    @startuml
    left to right direction
    skinparam packageStyle rectangle

    actor "Usuario Visitante" as Visitor
    actor "Usuario Logueado" as Authenticated
    actor "Reclutador" as Recruiter
    actor "Candidato" as Candidate

    rectangle "Selección de Candidatos" {
      usecase "Registrarse y Completar Perfil" as UC1
      usecase "Aplicar a Vacantes" as UC2
      usecase "Filtrar y Clasificar Aplicaciones" as UC3
      usecase "Programar Entrevistas" as UC4

      Visitor --> UC1 : Registra y\ncompleta perfil
      Candidate <|-- Visitor : Especialización
      Candidate --> UC1 : Inicia
      Candidate --> UC2 : Aplica
      Authenticated --> UC3 : Filtra aplicaciones
      Recruiter <|-- Authenticated : Especialización
      Recruiter --> UC3 : Inicia
      Recruiter --> UC4 : Programa entrevistas
    }
    @enduml

  ```
</details>
<details>
  <summary>Caso de Uso 3: Integración con Herramientas de RRHH</summary>

  ```
    @startuml
    left to right direction
    skinparam packageStyle rectangle

    actor "Usuario Logueado" as Authenticated
    actor "Reclutador" as Recruiter
    actor "Administrador de Sistemas" as SysAdmin

    rectangle "Integración con RRHH" {
      usecase "Configurar Integraciones" as UC1
      usecase "Usar Herramientas Integradas" as UC2

      Authenticated --> UC1 : Configura integraciones
      SysAdmin <|-- Authenticated : Especialización
      SysAdmin --> UC1 : Inicia
      Authenticated --> UC2 : Usa herramientas
      Recruiter <|-- Authenticated : Especialización
      Recruiter --> UC2 : Inicia
    }
    @enduml

  ```
</details>

### Prompt 6:
Identifica todas las entidades del modelo de datos para nuestro sistema ATS y listalas a continuación

### Prompt 7:
Identifica todas las entidades del modelo de datos para nuestro sistema ATS y listalas a continuación

### Prompt 8:
Generame el diagrama del modelo de datos para todas las entidades listadas anteriormente. Utiliza el formato Mermaid

<details>
  <summary>Repuesta de Microsoft Copilot</summary>

  ```
  erDiagram
    CANDIDATO ||--o{ APLICACION : aplica
    CANDIDATO {
        string id PK "Identificador único"
        string nombre "Nombre completo"
        string contacto "Información de contacto"
        string curriculum "URL o datos del currículum"
        string historial_laboral "Historial de trabajos anteriores"
        string educacion "Educación y certificaciones"
        string habilidades "Habilidades relevantes"
    }

    RECLUTADOR ||--o{ VACANTE : publica
    RECLUTADOR ||--o{ ENTREVISTA : coordina
    RECLUTADOR ||--o{ APLICACION : revisa
    RECLUTADOR {
        string id PK "Identificador único"
        string nombre "Nombre completo"
        string contacto "Información de contacto"
        string departamento "Departamento al que pertenece"
        string rol "Rol dentro del departamento"
    }

    MANAGER_DE_CONTRATACION ||--o{ VACANTE : aprueba
    MANAGER_DE_CONTRATACION {
        string id PK "Identificador único"
        string nombre "Nombre completo"
        string contacto "Información de contacto"
        string departamento "Departamento al que pertenece"
        string rol "Rol dentro del departamento"
    }

    VACANTE ||--o{ APLICACION : recibe
    VACANTE ||--o{ OFERTA_DE_TRABAJO : genera
    VACANTE {
        string id PK "Identificador único"
        string titulo "Título de la vacante"
        string descripcion "Descripción detallada"
        string requisitos "Requisitos necesarios"
        string ubicacion "Ubicación geográfica"
        string tipo_contrato "Tipo de contrato ofrecido"
        float salario "Rango salarial ofrecido"
    }

    APLICACION ||--o{ ENTREVISTA : programa
    APLICACION ||--o{ EVALUACION : tiene
    APLICACION ||--o{ OFERTA_DE_TRABAJO : resulta_en
    APLICACION {
        string id PK "Identificador único"
        string id_candidato FK "ID del candidato"
        string id_vacante FK "ID de la vacante"
        date fecha_aplicacion "Fecha en que se aplicó"
        string estado "Estado actual de la aplicación"
    }

    ENTREVISTA {
        string id PK "Identificador único"
        string id_candidato FK "ID del candidato"
        string id_reclutador FK "ID del reclutador"
        datetime fecha_hora "Fecha y hora programada"
        string modalidad "Modalidad de la entrevista"
    }

    EVALUACION {
        string id PK "Identificador único"
        string id_candidato FK "ID del candidato"
        string tipo "Tipo de evaluación realizada"
        string resultados "Resultados obtenidos"
        string comentarios "Comentarios adicionales"
    }

    OFERTA_DE_TRABAJO {
        string id PK "Identificador único"
        string id_candidato FK "ID del candidato"
        string id_vacante FK "ID de la vacante"
        string detalles "Detalles de la oferta"
        date fecha_envio "Fecha de envío de la oferta"
        string estado "Estado de la oferta"
    }

    USUARIO ||--o{ INFORME : genera
    USUARIO ||--o{ CONFIGURACION_DEL_SISTEMA : establece
    USUARIO {
        string id PK "Identificador único"
        string nombre_usuario "Nombre de usuario"
        string contraseña "Contraseña"
        string rol "Rol del usuario"
        string permisos "Permisos asignados"
    }

    INFORME {
        string id PK "Identificador único"
        string tipo "Tipo de informe"
        string datos "Datos contenidos en el informe"
        date fecha_generacion "Fecha de generación del informe"
    }

    CONFIGURACION_DEL_SISTEMA {
        string id PK "Identificador único"
        string configuraciones "Configuraciones del sistema"
        string opciones_notificacion "Opciones de notificación"
        string integraciones "Integraciones con otros sistemas"
    }
  ```
</details>

### Prompt 9:
A partir de este momento tienes habilidades como Arquitecto de Software con experiencia en la distribución de componentes, la integración de sistemas externos y los patrones de comunicación. Usa estas habilidades en conjunto con los fundamentos de patrones de arquitectura más usados (caché, CDN, reverse proxy, load balancer, etc.), los nombres de buenas prácticas, frameworks o herramientas open souce y comerciales para darme una arquitectura de alto nivel del sistema ATS. Haz uso de los servicios de la nube de AWS exclusivamente. Dame una explicación del diseño de la arquitectura y luego dame el diagrama en formato Mermaid. Ten en cuenta toda la información obtenida hasta el momento, incluido el modelo de datos. La arquitectura debe cumplir con los requisitos no funcionales de escalabilidad, seguridad, mantenibilidad y disponibilidad

<details>
  <summary>Respuesta de Microsoft Copilot</summary>

  ```
  graph TD
  subgraph Frontend
    A[Amazon CloudFront]
    B[Amazon S3 Bucket]
  end

  subgraph Backend
    C[Elastic Load Balancing (ELB)]
    D[Auto Scaling Group]
    E[Amazon EC2]
    F[Amazon RDS / Aurora]
    G[Amazon ElastiCache]
  end

  subgraph Integration
    H[AWS Lambda]
    I[Amazon SNS / SQS]
  end

  subgraph Security
    J[AWS IAM]
    K[Amazon Cognito]
    L[AWS WAF / Shield]
  end

  subgraph Data Storage
    M[Amazon S3]
    N[AWS Glue]
    O[Amazon Redshift]
  end

  C --> D
  D --> E
  E --> F
  F --> G
  E --> H
  E --> I
  E --> J
  E --> K
  E --> L
  E --> M
  E --> N
  E --> O
  A --> B
  B --> C
  B --> E
  B --> F
  B --> G
  B --> H
  B --> I
  B --> J
  B --> K
  B --> L
  B --> M
  B --> N
  B --> O
  ```
</details>

### Prompt 10:
Conoces el concepto de diagramas C4 de Simon Brown?

### Prompt 11:
Genial, necesito crear los diagramas C4 para el sistema ATS que estamos diseñando. Concéntrate en el sistema ATS como tal para dar el nivel de profundidad en los diagramas. Haz uso de la referencia oficial (https://c4model.com/) y del lenguaje plantUML para darme el código necesario (https://github.com/plantuml-stdlib/C4-PlantUML)

<details>
  <summary>Diagrama de contexto</summary>

  ```
  @startuml C4_Elements
  !include https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Context.puml

  Person(alias1, "Candidato", "Una persona que busca empleo y utiliza el ATS para aplicar a ofertas de trabajo.")
  Person(alias2, "Reclutador", "Usuario que gestiona el proceso de reclutamiento dentro de la empresa.")
  Person(alias3, "Manager de Contratación", "Responsable de tomar las decisiones finales de contratación.")
  System(alias4, "Sistema ATS", "Permite la gestión y seguimiento de candidatos, vacantes y procesos de selección.")

  System_Ext(alias5, "Sistemas de RRHH", "Sistemas externos de gestión de recursos humanos.")
  System_Ext(alias6, "Plataformas de Empleo", "Plataformas externas donde se publican las ofertas de trabajo.")
  System_Ext(alias7, "Servicios de Email", "Servicios externos para enviar notificaciones y comunicaciones.")

  Rel(alias1, alias4, "Usa")
  Rel(alias2, alias4, "Usa")
  Rel(alias3, alias4, "Usa")
  Rel(alias4, alias5, "Integra con")
  Rel(alias4, alias6, "Publica vacantes en")
  Rel(alias4, alias7, "Envía emails a través de")

  @enduml
  ```
</details>

### Prompt 11:
Necesito crear los diagramas de los otros niveles concentrándonos en el contexto "Sistema ATS". Qué información necesitamos definir para poder generarlos?. Especifícame la información para cada nivel por separado y uno a uno, no procedas al siguiente diagrama hasta no haber definido el anterior y hasta que yo no te lo confirme

### Prompt 12:
Dame sugerencias de cada uno de estos aspectos teniendo en cuenta toda la información recopilada hasta el momento para nuestro sistema ATS y los requerimientos no funcionales plasmados en el diseño de alto nivel

<details>
  <summary>Diagrama de contenedores</summary>

  ```
  @startuml C4_Containers
  !include https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Container.puml

  LAYOUT_WITH_LEGEND()

  Person(alias1, "Candidato", "Una persona que busca empleo y utiliza el ATS para aplicar a ofertas de trabajo.")
  Person(alias2, "Reclutador", "Usuario que gestiona el proceso de reclutamiento dentro de la empresa.")
  Person(alias3, "Manager de Contratación", "Responsable de tomar las decisiones finales de contratación.")

  Container(alias4, "Aplicación Web ATS", "React", "Interfaz principal para candidatos y reclutadores.")
  Container(alias5, "Servicio de Backend ATS", "Node.js, Express", "Maneja la lógica de negocio y la comunicación con la base de datos.")
  Container(alias6, "Servicio de Autenticación", "Amazon Cognito", "Gestiona el registro de usuarios y la seguridad de la sesión.")
  Container(alias7, "API de Integración", "GraphQL", "Permite la comunicación con sistemas externos de RRHH y plataformas de empleo.")

  System_Ext(alias8, "Sistemas de RRHH", "Sistemas externos de gestión de recursos humanos.")
  System_Ext(alias9, "Plataformas de Empleo", "Plataformas externas donde se publican las ofertas de trabajo.")
  System_Ext(alias10, "Servicios de Email", "Servicios externos para enviar notificaciones y comunicaciones.")

  Rel(alias1, alias4, "Usa")
  Rel(alias2, alias4, "Usa")
  Rel(alias3, alias4, "Usa")
  Rel(alias4, alias5, "Envía y recibe datos a través de", "JSON/HTTPS")
  Rel(alias5, alias6, "Valida credenciales con")
  Rel(alias5, alias7, "Se comunica con")
  Rel(alias7, alias8, "Integra con")
  Rel(alias7, alias9, "Publica vacantes en")
  Rel(alias5, alias10, "Envía emails a través de")

  @enduml
  ```
</details>
<details>
  <summary>Diagrama de componentes</summary>

  ```
  @startuml C4_Containers
  !include https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Container.puml

  LAYOUT_WITH_LEGEND()

  Person(alias1, "Candidato", "Una persona que busca empleo y utiliza el ATS para aplicar a ofertas de trabajo.")
  Person(alias2, "Reclutador", "Usuario que gestiona el proceso de reclutamiento dentro de la empresa.")
  Person(alias3, "Manager de Contratación", "Responsable de tomar las decisiones finales de contratación.")

  Container(alias4, "Aplicación Web ATS", "React", "Interfaz principal para candidatos y reclutadores.")
  Container(alias5, "Servicio de Backend ATS", "Node.js, Express", "Maneja la lógica de negocio y la comunicación con la base de datos.")
  Container(alias6, "Servicio de Autenticación", "Amazon Cognito", "Gestiona el registro de usuarios y la seguridad de la sesión.")
  Container(alias7, "API de Integración", "GraphQL", "Permite la comunicación con sistemas externos de RRHH y plataformas de empleo.")

  System_Ext(alias8, "Sistemas de RRHH", "Sistemas externos de gestión de recursos humanos.")
  System_Ext(alias9, "Plataformas de Empleo", "Plataformas externas donde se publican las ofertas de trabajo.")
  System_Ext(alias10, "Servicios de Email", "Servicios externos para enviar notificaciones y comunicaciones.")

  Rel(alias1, alias4, "Usa")
  Rel(alias2, alias4, "Usa")
  Rel(alias3, alias4, "Usa")
  Rel(alias4, alias5, "Envía y recibe datos a través de", "JSON/HTTPS")
  Rel(alias5, alias6, "Valida credenciales con")
  Rel(alias5, alias7, "Se comunica con")
  Rel(alias7, alias8, "Integra con")
  Rel(alias7, alias9, "Publica vacantes en")
  Rel(alias5, alias10, "Envía emails a través de")

  @enduml
  ```
</details>
<details>
  <summary>Diagrama de código</summary>

  ```
  @startuml C4_Code
  !include https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Component.puml

  Container(alias5, "Servicio de Backend ATS", "Node.js, Express", "Maneja la lógica de negocio y la comunicación con la base de datos.")

  Component(alias5_3, "Controlador de Aplicaciones", "Node.js, Express", "Maneja las solicitudes relacionadas con las aplicaciones de los candidatos.")
  Component(alias5_3_1, "Modelo de Aplicación", "Mongoose Schema", "Define la estructura de datos para una aplicación de candidato.")
  Component(alias5_3_2, "Servicio de Aplicación", "Clase de Servicio", "Provee lógica de negocio para operaciones de aplicaciones.")
  Component(alias5_3_3, "Repositorio de Aplicaciones", "Clase de Repositorio", "Abstrae la capa de acceso a datos para las aplicaciones.")
  Component(alias5_3_4, "Validador de Aplicaciones", "Clase de Validación", "Valida la información de las aplicaciones antes de procesarlas.")

  Rel(alias5_3, alias5_3_1, "Usa")
  Rel(alias5_3, alias5_3_2, "Llama métodos de")
  Rel(alias5_3_2, alias5_3_3, "Usa para CRUD de aplicaciones")
  Rel(alias5_3_2, alias5_3_4, "Valida con antes de guardar")

  @enduml
  ```
</details>