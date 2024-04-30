# Sistema de Gestión de Solicitantes (ATS) - Documento de Diseño
## Descripción del Software
El Sistema de Gestión de Solicitantes (Applicant-Tracking System, ATS) es un sistema utilizado por las empresas para gestionar el proceso de reclutamiento y selección de personal. Este tipo de software ayuda a organizar y automatizar las etapas del proceso de contratación, desde la recepción de aplicaciones hasta la selección final de candidatos. Funciona como una base de datos centralizada que permite a los reclutadores almacenar, filtrar, buscar y gestionar las aplicaciones de los candidatos de manera eficiente. Además, un ATS puede integrarse con otras herramientas de recursos humanos para facilitar una gestión más completa del talento.

## Valor Añadido y Ventajas Competitivas
Las funcionalidades principales de un sistema ATS (Applicant Tracking System) incluyen:
1. Gestión de vacantes: Permite crear y publicar ofertas de empleo en diversas plataformas y medios.
2. Recepción y almacenamiento de aplicaciones: Centraliza las aplicaciones recibidas, ya sea directamente o a través de portales de empleo.
3. Filtrado y clasificación de candidatos: Utiliza palabras clave, habilidades, experiencia, educación, y otros criterios para filtrar y clasificar candidatos automáticamente.
4. Gestión de comunicaciones: Facilita la comunicación con los candidatos a través de correos electrónicos automatizados para actualizaciones de estado, invitaciones a entrevistas, etc.
5. Programación de entrevistas: Integra calendarios para facilitar la programación de entrevistas entre candidatos y reclutadores.
6. Seguimiento del proceso de selección: Permite a los reclutadores seguir el progreso de cada candidato a través de las diferentes etapas del proceso de selección.
7. Informes y análisis: Proporciona herramientas de análisis e informes para evaluar la eficacia del proceso de reclutamiento y tomar decisiones basadas en datos.

##Ventajas competitivas de un ATS:
1. Eficiencia mejorada: Automatiza tareas repetitivas y administra grandes volúmenes de aplicaciones, lo que reduce el tiempo y el esfuerzo en el proceso de selección.
2. Mejora en la calidad de contratación: Al filtrar candidatos basados en criterios específicos, aumenta la probabilidad de encontrar el candidato más adecuado para el puesto.
3. Reducción de costos: Disminuye los costos asociados con el proceso de reclutamiento al reducir la necesidad de recursos humanos adicionales y minimizar el tiempo de contratación.
4. Cumplimiento normativo: Ayuda a asegurar que el proceso de reclutamiento cumpla con las leyes y regulaciones locales e internacionales relacionadas con la contratación.
5. Mejora de la experiencia del candidato: Proporciona una comunicación fluida y constante con los candidatos, mejorando su percepción del proceso y de la empresa.
6. Integración con otras herramientas: Se integra fácilmente con otros sistemas de recursos humanos, lo que permite una gestión más holística del talento.
Estas funcionalidades y ventajas hacen que los sistemas ATS sean herramientas esenciales para las empresas modernas que buscan optimizar sus procesos de reclutamiento y selección de personal.

## Lean Canvas
![lean-canvas](https://www.mermaidchart.com/raw/7625038c-2069-40f1-9490-065847962d47?theme=light&version=v0.1&format=svg)

## Casos de uso
### Caso de Uso 1: Gestión de vacantes
#### Descripción:
Permite a los reclutadores crear, publicar y gestionar ofertas de empleo.

#### Diagrama UML:

![use-case-1](https://www.mermaidchart.com/raw/a3a7d962-f550-41d9-bb37-ddc08eada251?theme=light&version=v0.1&format=svg)

### Caso de Uso 2:  Filtrado y clasificación de candidatos
#### Descripción:
Automatiza el proceso de selección inicial mediante el uso de filtros basados en palabras clave, habilidades, experiencia, etc.


#### Diagrama UML

![use-case-2](https://www.mermaidchart.com/raw/4309fb7f-331e-4fea-a6c7-89472973816f?theme=light&version=v0.1&format=svg)


### Caso de Uso 3:  Programación de entrevistas
#### Descripción:
Facilita la coordinación de entrevistas entre candidatos y reclutadores mediante la integración con calendarios.


#### Diagrama UML

![use-case-3](https://www.mermaidchart.com/raw/f9367d5e-bfae-46b0-8fb5-2c52f0ff67b6?theme=light&version=v0.1&format=svg)

# Entidades del Sistema ATS

## 1. Candidato
### Campos esenciales:
- **ID del candidato**: Identificador único.
- **Nombre**: Nombre completo del candidato.
- **Correo electrónico**: Dirección de correo electrónico.
- **Teléfono**: Número de contacto.
- **Experiencia**: Detalles de la experiencia laboral previa.
- **Educación**: Detalles educativos.
- **Habilidades**: Lista de habilidades técnicas y blandas.

### Relaciones:
- Puede tener múltiples aplicaciones a diferentes vacantes.
- Puede estar asociado a múltiples entrevistas.

## 2. Vacante
### Campos esenciales:
- **ID de la vacante**: Identificador único.
- **Título del puesto**: Nombre del puesto.
- **Descripción**: Descripción detallada del puesto.
- **Ubicación**: Ubicación del trabajo.
- **Requisitos**: Habilidades y experiencia requeridas.

### Relaciones:
- Puede tener múltiples candidatos aplicando.
- Puede tener múltiples entrevistas programadas para diferentes candidatos.

## 3. Entrevista
### Campos esenciales:
- **ID de la entrevista**: Identificador único.
- **Fecha y hora**: Cuándo se programó la entrevista.
- **Modo (Presencial/Online)**: Cómo se llevará a cabo la entrevista.
- **Resultado**: Resultado de la entrevista.

### Relaciones:
- Está asociada a un candidato específico.
- Está asociada a una vacante específica.

## 4. Empresa
### Campos esenciales:
- **ID de la empresa**: Identificador único.
- **Nombre**: Nombre de la empresa.
- **Sector**: Sector industrial al que pertenece.
- **Ubicación**: Ubicación principal de la empresa.

### Relaciones:
- Puede tener múltiples vacantes publicadas.
- Puede tener múltiples reclutadores asociados.

## 5. Reclutador
### Campos esenciales:
- **ID del reclutador**: Identificador único.
- **Nombre**: Nombre completo del reclutador.
- **Correo electrónico**: Dirección de correo electrónico.
- **Teléfono**: Número de contacto.

### Relaciones:
- Está asociado a una empresa.
- Gestiona múltiples vacantes.
- Interactúa con múltiples candidatos.

## 6. Aplicación/Solicitud
### Campos esenciales:
- **ID de la aplicación**: Identificador único.
- **Fecha de aplicación**: Fecha en que el candidato aplicó.
- **Estado**: Estado actual de la aplicación (por ejemplo, pendiente, rechazada, aceptada).

### Relaciones:
- Relaciona a un candidato con una vacante específica.
- Puede tener asociada una o más entrevistas.

## 7. Comentarios/Notas
### Campos esenciales:
- **ID del comentario**: Identificador único.
- **Texto**: Contenido del comentario o nota.
- **Fecha**: Fecha en que se realizó el comentario.

### Relaciones:
- Puede estar asociado a una aplicación, candidato o entrevista, proporcionando información adicional relevante para el proceso de selección.

![data-model](https://www.mermaidchart.com/raw/92ff2b4d-71df-4238-be1b-6e4533e48d64?theme=light&version=v0.1&format=svg)

## Diseño del Sistema a Alto Nivel
El ATS de LTI consta de varios componentes interconectados que trabajan juntos para ofrecer funcionalidades completas de reclutamiento y contratación de personal. A continuación, se detalla el diseño a alto nivel:

# Descripción del Diagrama

- **Portal Frontend**: Interfaz de usuario donde los reclutadores y candidatos interactúan con el sistema.
- **API Gateway**: Actúa como un punto de entrada único para todas las solicitudes, encaminándolas a los microservicios apropiados.
- **Microservicios**: Cada uno maneja una parte específica del proceso de reclutamiento:
  - **Gestión de Candidatos**: Maneja operaciones relacionadas con los candidatos.
  - **Gestión de Vacantes**: Maneja la creación y gestión de vacantes.
  - **Programación de Entrevistas**: Coordina la programación de entrevistas.
  - **Comunicaciones**: Gestiona las comunicaciones automáticas con candidatos.
- **Bus de Eventos**: Facilita la comunicación basada en eventos entre microservicios, permitiendo una arquitectura reactiva y desacoplada.
- **Base de Datos PostgreSQL**: Almacena todos los datos relevantes del sistema, accesible por los microservicios para operaciones CRUD.

Este diseño aprovecha la escalabilidad y flexibilidad de la arquitectura de microservicios y la eficiencia de la arquitectura dirigida por eventos, ideal para sistemas dinámicos y escalables como un ATS en la nube.

## Diagrama de Alto Nivel
[![high-level-design]()

## Componente de Backend

### Diagrama C4


#### Código

Clases del Backend:
# Descripción del Diagrama de Clases

- **Candidato**: Representa a los individuos que aplican a las vacantes. Contiene métodos para agregar aplicaciones y entrevistas a su perfil.
- **Aplicacion**: Representa la aplicación de un candidato a una vacante específica. Puede contener múltiples entrevistas asociadas a esta aplicación.
- **Vacante**: Representa los puestos de trabajo disponibles a los que los candidatos pueden aplicar. Contiene métodos para agregar aplicaciones.
- **Entrevista**: Representa una instancia de entrevista entre un candidato y una vacante.

Este diagrama de clases muestra cómo se estructuran y relacionan las entidades dentro del microservicio de gestión de candidatos, facilitando la implementación y mantenimiento del sistema.

![backend-code]()