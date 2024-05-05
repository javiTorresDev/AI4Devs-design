# Backlog de producto ATS (Applicant Tracking System)

## Índice
* [Modelo de datos actualizado](#modelo-de-datos-actualizado)


## Introducción al Backlog del Producto

En respuesta a las necesidades emergentes del mercado y la evolución constante de la tecnología, **hemos actualizado nuestro modelo de datos para el sistema de seguimiento de candidatos (ATS)**. Estos cambios están diseñados para integrar funcionalidades de inteligencia artificial, lo que permitirá una mayor eficiencia y efectividad en el proceso de reclutamiento. Con la inclusión de entidades como **Análisis de CV**, **Matching**, **Chatbot**, **Análisis Predictivo**, y **Análisis de Sentimiento**, nuestro sistema está preparado para ofrecer una experiencia más dinámica, personalizada y predictiva tanto para reclutadores como para candidatos. Este enfoque proactivo en la adopción de IA asegura que nuestro ATS se mantenga a la vanguardia de la innovación en la gestión de talento:

A continuación se observa el modelo de datos actualizado. Todo el desarrollo del Backlog de producto se realizará con base en esta nueva estructura:

![Modelo de datos](./res/modelo-datos-actualizado.jpeg)

## Historias de usuario orientadas a las funcionalidades de IA

### Análisis de CVs Automatizado
> "Como reclutador, quiero que el sistema realice un análisis automático de los CVs recibidos para identificar rápidamente los candidatos más adecuados según su experiencia y habilidades."

* **Descripción**: El sistema debe ser capaz de procesar y analizar los currículos de los candidatos para extraer información clave como experiencia laboral, educación y habilidades técnicas.

* **Criterios de Aceptación**:
  * Dado que un candidato envía su CV, cuando el sistema recibe el archivo, entonces debe extraer la información relevante y almacenarla en la base de datos.
  * Dado que un reclutador busca candidatos, cuando accede a los perfiles, entonces debe ver un resumen de las habilidades y experiencias destacadas.

* **Notas adicionales**: Debe soportar múltiples formatos de CV, incluyendo PDF y Word.

* **Tareas**:
  * Desarrollar un módulo de procesamiento de texto.
  * Crear una base de datos para almacenar la información extraída.
  * Implementar una interfaz para visualizar los resúmenes de los candidatos.

### Matching Inteligente de Candidatos
> "Como reclutador, quiero que el sistema compare las habilidades de los candidatos con los requisitos de las vacantes para encontrar el mejor match y recomendar candidatos para las posiciones abiertas."

* **Descripción**: Utilizar algoritmos de IA para comparar y puntuar la afinidad entre los perfiles de los candidatos y las descripciones de las vacantes.

* **Criterios de Aceptación**:
  * Dado que un candidato aplica a una vacante, cuando el sistema procesa la aplicación, entonces debe asignar una puntuación de matching y sugerir posibles coincidencias.
  * Dado que un reclutador revisa las aplicaciones, cuando accede al sistema, entonces debe recibir recomendaciones de candidatos basadas en la puntuación de matching.

* **Notas adicionales**: La puntuación debe basarse en criterios ponderados y personalizables.

* **Tareas**:
  * Diseñar y entrenar modelos de IA para el matching de habilidades.
  * Integrar el sistema de matching con la base de datos de vacantes y candidatos.
  * Crear reportes y dashboards para visualizar las recomendaciones.

### Chatbot para Pre-entrevistas
> "Como candidato, quiero interactuar con un chatbot durante el proceso de pre-entrevista para responder preguntas básicas y agilizar mi proceso de aplicación."

* **Descripción**: Implementar un chatbot que pueda realizar entrevistas preliminares y recopilar información básica de los candidatos.

* **Criterios de Aceptación**:
  * Dado que un candidato inicia una pre-entrevista, cuando el chatbot realiza preguntas, entonces debe recoger y almacenar las respuestas del candidato.
  * Dado que un reclutador evalúa un candidato, cuando revisa la información recopilada por el chatbot, entonces debe tener acceso a un resumen de la pre-entrevista.

* **Notas adicionales**: El chatbot debe ser capaz de manejar preguntas abiertas y cerradas.

* **Tareas**:
  * Desarrollar el flujo de conversación del chatbot.
  * Integrar el chatbot con el sistema ATS.
  * Probar y entrenar el chatbot con datos reales de candidatos.

### Análisis Predictivo para la Toma de Decisiones de Contratación
> "Como manager de contratación, quiero consultar análisis predictivos para evaluar la probabilidad de éxito de los candidatos en las posiciones abiertas y tomar decisiones informadas."

* **Descripción**: El sistema debe proporcionar análisis predictivos que utilicen datos históricos y tendencias del mercado laboral para predecir el éxito de un candidato en un puesto.

* **Criterios de Aceptación**:
  * Dado que un manager de contratación evalúa candidatos, cuando utiliza el sistema, entonces debe recibir predicciones sobre la probabilidad de éxito de los candidatos.
  * Dado que se generan informes de contratación, cuando se incluyen análisis predictivos, entonces deben ofrecer insights y recomendaciones basadas en datos.

* **Notas adicionales**: Los modelos predictivos deben ser transparentes y explicables.

* **Tareas**:
  * Desarrollar modelos de análisis predictivo.
  * Integrar análisis predictivo en el proceso de toma de decisiones.
  * Crear visualizaciones de datos para interpretar los resultados del análisis predictivo.

### Evaluación del Ajuste Cultural y Entusiasmo a través del Análisis de Sentimiento
> "Como reclutador, quiero utilizar un sistema de análisis de sentimiento para evaluar las respuestas de los candidatos durante las entrevistas y ayudar a determinar su ajuste cultural y nivel de entusiasmo."

* **Descripción**: Implementar un sistema de análisis de sentimiento que evalúe las respuestas de los candidatos durante las entrevistas para proporcionar insights adicionales sobre su personalidad y motivación.

* **Criterios de Aceptación**:
  * Dado que se realiza una entrevista, cuando el sistema analiza las respuestas del candidato, entonces debe proporcionar un análisis de sentimiento.
  * Dado que un reclutador revisa el análisis de sentimiento, cuando accede al sistema, entonces debe ver interpretaciones que ayuden a evaluar el ajuste cultural del candidato.

* **Notas adicionales**: El análisis debe manejar diferentes idiomas y dialectos.

* **Tareas**:
  * Desarrollar un módulo de análisis de sentimiento.
  * Integrar el análisis de sentimiento con el sistema de entrevistas.
  * Validar la precisión del análisis de sentimiento con pruebas de usuario.

## Generación del Backlog del producto

### Priorización del Backlog con base en las historias de usuario
| Historia de Usuario ordenada por nivel de prioridad | Impacto y Valor | Urgencia | Complejidad y Esfuerzo | Riesgos y Dependencias | Madurez Tecnológica |
|---------------------|-----------------|----------|------------------------|------------------------|---------------------|
| 1. Análisis de CVs Automatizado | Alto | Alta | Media | Medio | Alta |
| 2. Matching Inteligente de Candidatos | Alto | Media | Alta | Alto | Media |
| 3. Chatbot para Pre-entrevistas | Medio | Media | Media | Medio | Alta |
| 4. Análisis Predictivo para la Toma de Decisiones de Contratación | Alto | Baja | Alta | Alto | Baja |
| 5. Evaluación del Ajuste Cultural y Entusiasmo a través del Análisis de Sentimiento | Medio | Baja | Alta | Alto | Baja |


**Explicación de las Estimaciones**:

* **Análisis de CVs Automatizado**:
  * **Impacto y Valor**: Alto, ya que puede mejorar significativamente la eficiencia del proceso de selección.
  * **Urgencia**: Alta, debido a la demanda del mercado por procesos de reclutamiento más rápidos.
  * **Complejidad y Esfuerzo**: Media, existen herramientas de procesamiento de lenguaje natural que pueden ser adaptadas.
  * **Riesgos y Dependencias**: Medio, considerando la variabilidad en la calidad de los CVs y la necesidad de ajustar continuamente los algoritmos de procesamiento de texto para diferentes formatos.
  * **Madurez Tecnológica**: Alta, las herramientas de procesamiento de lenguaje natural están bien establecidas y son ampliamente utilizadas.
* **Matching Inteligente de Candidatos**:
  * **Impacto y Valor**: Alto, un buen sistema de matching puede ahorrar tiempo y recursos significativos.
  * **Urgencia**: Media, es una característica deseable pero puede no ser tan crítica como el análisis de CV.
  * **Complejidad y Esfuerzo**: Alta, debido a la necesidad de desarrollar algoritmos de IA robustos y manejar un gran volumen de datos.
  * **Riesgos y Dependencias**: Alto, por la complejidad del desarrollo y la dependencia de la disponibilidad y calidad de los datos de habilidades y vacantes.
  * **Madurez Tecnológica**: Media, los sistemas de recomendación existen pero su aplicación específica para matching de habilidades es menos común.
* **Chatbot para Pre-entrevistas**:
  * **Impacto y Valor**: Medio, es una mejora valiosa pero no esencial.
  * **Urgencia**: Media, mejora la experiencia del usuario pero no es urgente.
  * **Complejidad y Esfuerzo**: Media, los chatbots son bastante comunes.
  * **Riesgos y Dependencias**: Medio, los chatbots pueden enfrentar desafíos con la interpretación de lenguaje natural.
  * **Madurez Tecnológica**: Alta, los chatbots son una tecnología establecida con muchas plataformas disponibles.
* **Análisis Predictivo para la Toma de Decisiones de Contratación**:
  * **Impacto y Valor**: Alto, debido al potencial de mejorar la calidad de las contrataciones.
  * **Urgencia**: Baja, es una funcionalidad avanzada y no esencial en las etapas iniciales.
  * **Complejidad y Esfuerzo**: Alta, requiere modelos predictivos sofisticados y acceso a datos históricos y actualizados.
  * **Riesgos y Dependencias**: Alto, debido a la necesidad de modelos predictivos precisos y la dependencia de datos históricos de calidad.
  * **Madurez Tecnológica**: Baja, la analítica predictiva aplicada a la predicción del éxito de los candidatos es relativamente nueva y compleja.
* **Evaluación del Ajuste Cultural y Entusiasmo a través del Análisis de Sentimiento**:
  * **Impacto y Valor**: Medio, es una característica innovadora pero no crítica.
  * **Urgencia**: Baja, es más un ‘nice-to-have’ que un ‘must-have’.
  * **Complejidad y Esfuerzo**: Alta, debido a la necesidad de entender matices culturales y lingüísticos.
  * **Riesgos y Dependencias**: Alto, por la complejidad de interpretar correctamente el sentimiento y las emociones a través de diferentes culturas e idiomas.
  * **Madurez Tecnológica**: Baja, el análisis de sentimiento aplicado a entrevistas y ajuste cultural es un área emergente que requiere investigación y desarrollo significativos.
