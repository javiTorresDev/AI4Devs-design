# Sistema de Gestión de Solicitantes (ATS) - Documento de Diseño
## Descripción del Software
El Sistema de Gestión de Solicitantes (Applicant-Tracking System, ATS) es una herramienta diseñada para facilitar y optimizar el proceso de contratación de personal en empresas de cualquier tamaño. El ATS de nuestra start-up, llamada LTI (por sus siglas en inglés, "Lead Talent Innovator"), se enfoca en ofrecer una solución completa y fácil de usar para la gestión de candidatos, desde la publicación de ofertas de empleo hasta la contratación final.

## Valor Añadido y Ventajas Competitivas
* Interfaz Intuitiva: LTI se distingue por su interfaz de usuario intuitiva y fácil de navegar, lo que permite a los reclutadores y gerentes de contratación acceder rápidamente a la información que necesitan y realizar sus tareas de manera eficiente.
* Automatización Inteligente: El ATS de LTI utiliza algoritmos avanzados de inteligencia artificial para automatizar tareas repetitivas como la criba curricular, el envío de correos electrónicos a candidatos y la programación de entrevistas, liberando así tiempo para actividades más estratégicas.
* Análisis de Datos: LTI ofrece herramientas robustas de análisis de datos que permiten a los usuarios obtener información valiosa sobre el rendimiento de sus procesos de contratación, identificar tendencias y tomar decisiones informadas para mejorar continuamente sus estrategias de reclutamiento.
* Personalización y Escalabilidad: Nuestro ATS está diseñado para adaptarse a las necesidades específicas de cada empresa, ofreciendo opciones de personalización para flujos de trabajo, informes y configuraciones de usuarios. Además, LTI es escalable y puede crecer junto con la empresa a medida que esta expande su equipo de reclutamiento.
* Soporte y Actualizaciones Continuas: LTI se compromete a brindar un soporte técnico de alta calidad a sus clientes, así como a ofrecer actualizaciones regulares del software para incorporar nuevas funcionalidades y mantenerlo siempre actualizado con las últimas tendencias del mercado de reclutamiento.

## Lean Canvas
![lean-canvas](https://i.postimg.cc/s2nH6LkG/temp-lean-canvas-drawio.png)

## Casos de uso
### Caso de Uso 1: Publicación y Gestión de Ofertas de Empleo
#### Descripción:
En este caso de uso, el usuario (reclutador o gerente de contratación) puede crear y publicar ofertas de empleo en el ATS de LTI. El proceso incluye la definición de detalles como el título del puesto, descripción del trabajo, requisitos y ubicación. Una vez publicada, el usuario puede gestionar las ofertas de empleo, incluyendo la edición, pausa o eliminación de las mismas según sea necesario.

#### Pasos:
1. Iniciar sesión en el ATS de LTI.
2. Acceder al módulo de publicación de ofertas de empleo.
3. Crear una nueva oferta de empleo proporcionando los detalles requeridos.
4. Publicar la oferta de empleo en los canales seleccionados.
5. Gestionar las ofertas publicadas, permitiendo la edición, pausa o eliminación de las mismas.

#### Resultado:
El usuario logra publicar y gestionar eficientemente las ofertas de empleo de la empresa, aumentando la visibilidad de las oportunidades laborales y atrayendo a candidatos cualificados.

#### Diagrama UML:

![use-case-1](https://www.planttext.com/api/plantuml/png/TP71IWCn48RlUOgXPtlGtRrua9PIfE11Q7s0CPckGxF9aaa44P-gZz0NCrdJiXSlIJxo_SCaivA88QR1AcNf625w2Dn_H30SI4VsJic9tOW11nXHdx2dVVoo1EKQNMz9ATJH1tYJX84zeEGZ1NKJOB4-xC4Gl1ns2_XM04b8e-IBdMFD6418-79sYocykPyhQwt9K02qC5pE9bbVIetftR96FKizp5ERGBciI_I9u8yK8fOK3QCbN_rcxh_-rGl_oUrSVYOfFtEpvTgEGQb-ftAWV0Cibq_rIJCilUQrKZDHKwcTgAtKJTHT2HvXQpZFx2vF8qdPoVB0kHdrezIAdCd3_0K0)

### Caso de Uso 2: Criba Curricular y Evaluación de Candidatos
#### Descripción:
En este caso de uso, el usuario utiliza el ATS de LTI para realizar la criba curricular y evaluar a los candidatos que han aplicado a las ofertas de empleo publicadas. El sistema automatiza la revisión de currículums y permite al usuario filtrar y clasificar a los candidatos según criterios predefinidos como experiencia, habilidades y nivel educativo. Además, el usuario puede registrar notas y comentarios sobre cada candidato para facilitar la toma de decisiones.

#### Pasos:
1. Acceder al módulo de gestión de candidatos en el ATS de LTI.
2. Revisar los currículums de los candidatos que han aplicado a las ofertas de empleo.
3. Aplicar filtros y criterios de selección para realizar la criba curricular.
4. Clasificar a los candidatos según su idoneidad para el puesto.
5. Registrar notas y comentarios sobre cada candidato para la evaluación.

#### Resultado:
El usuario logra identificar y evaluar de manera eficiente a los candidatos más adecuados para avanzar en el proceso de contratación, optimizando el tiempo y los recursos del equipo de reclutamiento.

#### Diagrama UML

![use-case-2](https://www.planttext.com/api/plantuml/png/RP71IeCn383lVOgm-q0lRhl8P2V1aviF4DBijzY_7Kag3F6HFEqHzcAsvLSsz5BoaNnDcgxLKAoCqRd8UmFB865uDV11c2pavFGjf0CAZd10UiE1jtQC32sDQOZi799bWHSjA243QWrPt6y1p1vsM_0CJxl76NmuWA9Cg2r1n9u5CC9uFlaISwiRM2sSJwd5XCa7ZvPrrc_Ut5twp_mU50MeY9o_gCGowh_Mughh8GQgrZv4awnm199WN8Vlid9aeZR092ylvKr43Vlk_-cokfvj26fIwr8sx5tooCdQadw4snjNbROkcC_lfzVLSw95fyL4oqxBYLQTLXFLYpwTMtFozI-_0G00)


### Caso de Uso 3: Programación y Seguimiento de Entrevistas
#### Descripción:
En este caso de uso, el usuario utiliza el ATS de LTI para programar y realizar seguimiento de entrevistas con los candidatos preseleccionados. El sistema facilita la coordinación de horarios entre el usuario y los candidatos, envía recordatorios automáticos y permite registrar los resultados de las entrevistas. Además, el usuario puede gestionar múltiples entrevistas simultáneamente y mantener un historial organizado de todas las interacciones con los candidatos.

#### Pasos:

1. Acceder al calendario de entrevistas en el ATS de LTI.
2. Seleccionar candidatos preseleccionados para programar entrevistas.
3. Coordinar horarios y enviar invitaciones de entrevista a los candidatos.
4. Realizar las entrevistas y registrar los resultados y comentarios.
5. Realizar seguimiento de las entrevistas programadas y gestionar los próximos pasos.
#### Resultado:
El usuario logra gestionar eficientemente el proceso de programación y seguimiento de entrevistas, asegurando una comunicación fluida con los candidatos y avanzando en el proceso de contratación de manera efectiva.

#### Diagrama UML

![use-case-3](https://www.planttext.com/api/plantuml/png/TP4nRiCm34LtdOBmdY6sinOfCXNe5AS782JM8I9B1YK7I8lUlLGC6nxQIVmYtoT57LD6oTFWZV7qcI574Ewl6HmBsSmnc7JZCABW02FQ6_RKvOSdA6aClITZqEOey94c58w0IKCIinP0zNhfm16yNzug-3O0KoABgIIi9KS2wC6Yf-2U3bfA8GlTMQTBrTFnjDzlmOuyMQlZeIWP73lCCS4ebDQCYojRRzbJZEAuaDSefM62XpQyizwm7XaBJYlSRE4peUSlhTnCgBXGhw6wQPGcdxVDsp_vHFt40wlDVmy-60NBAc6tUrasK8v5rxEk5ztCkbbqE-jsqGVpOynHjwp__Gi0)

### Modelo de datos

#### Entidades:
* JobPosting representa una oferta de empleo con atributos como id, título, descripción, requisitos y ubicación.
* Candidate representa a un candidato con atributos como id, nombre, correo electrónico, teléfono, experiencia laboral, habilidades y educación.
* Interview representa una entrevista con atributos como id, fecha, hora y notas.
#### Relaciones:
* JobPosting tiene una relación uno a muchos con Candidate, ya que una oferta de empleo puede tener múltiples candidatos aplicando.
* Candidate tiene una relación uno a muchos con Interview, ya que un candidato puede tener múltiples entrevistas asociadas.

![data-model](https://www.planttext.com/api/plantuml/png/TP4z3i8m38Ntd28xoWKwLMA2YIk4nWABn2c9ou-Qtfsq8DgWibZHyvFVPwUEh0DtpWe1nCXFkVV7Wu-CT9Aza78ZqLGIYQTtTbYePEIG-vDY83O1MqPFXHxWsc40bwV6ec5zemlty8tUQZ9eDCDACcbN1eFJQ0kbFNlwyJnQ20ZKb7AyeBKb5PZkBzQE6C8DuRw2DT9MK_tSPwGSwnlQCyJbnCLnKrBAz_FEOjv-y4gbDESAKGEP_4al)

## Diseño del Sistema a Alto Nivel
El ATS de LTI consta de varios componentes interconectados que trabajan juntos para ofrecer funcionalidades completas de reclutamiento y contratación de personal. A continuación, se detalla el diseño a alto nivel:

### Interfaz de Usuario (UI):
* Módulo de Publicación de Ofertas: Permite a los usuarios crear y publicar nuevas ofertas de empleo.
* Módulo de Gestión de Candidatos: Facilita la revisión y gestión de candidatos que han aplicado a las ofertas publicadas.
* Calendario de Entrevistas: Permite programar y gestionar entrevistas con candidatos preseleccionados.
### Backend y Base de Datos:
* Servidor de Aplicaciones: Maneja la lógica de negocio y la interacción con la base de datos.
* Base de Datos: Almacena la información de ofertas de empleo, candidatos, entrevistas y otros datos relevantes.
### Integraciones Externas:
* Integración con Plataformas de Empleo: Permite la conexión con plataformas externas para la difusión de ofertas de empleo.
* Integración con Herramientas de Comunicación: Facilita el envío de correos electrónicos y mensajes a candidatos y entrevistadores.
### Algoritmos de Inteligencia Artificial (IA):
* Criba Curricular Automatizada: Utiliza algoritmos de IA para realizar la criba curricular de manera eficiente.
* Asistente de Programación de Entrevistas: Ayuda a coordinar horarios para entrevistas y envía recordatorios automáticos.
### Seguridad y Acceso:
* Autenticación y Autorización: Garantiza que los usuarios accedan solo a las funciones y datos autorizados.
* Protección de Datos: Cumple con las regulaciones de privacidad y seguridad de datos para proteger la información sensible.

## Diagrama de Alto Nivel
[![high-level-design](https://mermaid.ink/img/pako:eNpVUD1vwjAQ_SuWqygLDECllgyVEsLQmbZDE4aLfQlWHR-yHRUa5b_XTlUJbjq_j3vnG7kgiTzjSTIqo3zGxtSfsMcPsAoajS4NEEvPVvVgrzvSZAOSPmwet8-ySRcsdSjIyDuy3WzFah1Jj9arO26NQjytIteA-OosDUbeOOf6c178TdxcKZumKUlqU5tW07c4gfXsrawNY3n1akJYCz9MInt3Q9ifjmy5fGFFVYQkNJJdWQEOo6AET-4YjcWs2c32zoJQZNCx_SUMM3ArKatcd2SV78nFEdGgVYdGKGB5-GarQqdnRz479tUBu8EqCTE6FwIdBZoveI-2ByXD3ccor_l885pnoZXYwqB9zWszBSkMng5XI3jm7YALPpwleCwVhGV7nrWgXUDPYD6J_t_TL77vmoU?type=png)](https://mermaid.live/edit#pako:eNpVUD1vwjAQ_SuWqygLDECllgyVEsLQmbZDE4aLfQlWHR-yHRUa5b_XTlUJbjq_j3vnG7kgiTzjSTIqo3zGxtSfsMcPsAoajS4NEEvPVvVgrzvSZAOSPmwet8-ySRcsdSjIyDuy3WzFah1Jj9arO26NQjytIteA-OosDUbeOOf6c178TdxcKZumKUlqU5tW07c4gfXsrawNY3n1akJYCz9MInt3Q9ifjmy5fGFFVYQkNJJdWQEOo6AET-4YjcWs2c32zoJQZNCx_SUMM3ArKatcd2SV78nFEdGgVYdGKGB5-GarQqdnRz479tUBu8EqCTE6FwIdBZoveI-2ByXD3ccor_l885pnoZXYwqB9zWszBSkMng5XI3jm7YALPpwleCwVhGV7nrWgXUDPYD6J_t_TL77vmoU)

## Componente de Backend

### Diagrama C4

#### Contexto
El Usuario interactúa a través de la Interfaz de Usuario con el sistema.
La Interfaz de Usuario se comunica con el Backend para gestionar las solicitudes y operaciones del usuario.
El Backend interactúa con la Base de Datos para almacenar y recuperar datos.
El Backend también se comunica con Algoritmos de IA para tareas relacionadas con inteligencia artificial.
Existen Integraciones Externas que el Backend utiliza para conectarse con plataformas externas.
El Backend se encarga de la Seguridad y Acceso para proteger los datos y gestionar el acceso de los usuarios al sistema.

![backend-context](https://www.planttext.com/api/plantuml/png/ROyz3i8m34RtdCBg10DNG0s2eH9RouGOhCH44MrInOd4ZxWxILMMgflbzsn_hZbYY6deXHXHFT0GLB9huTmr5Nm4mFN22OFrDzZjOTEuIE6ERz04CzXcQRK_3HpoKd9walxr39YAVSJeUO4BbxtnmSR1Sx4QkQAKeoQWijuHm-cP8pXSxifUIoO5gr732wHIn3dpLuWw2zFZFm00)

#### Contenedores
* Usuario: Representa a los usuarios que interactúan con el sistema a través de la Interfaz de Usuario.
Contenedores:
* Backend: Es el componente principal del sistema que se encarga de la lógica de negocio y la gestión de datos.
Base de Datos: Almacena y gestiona la persistencia de los datos utilizados por el sistema.

![backend-containers](https://www.planttext.com/api/plantuml/png/SoWkIImgAStDuU8gI4pEJanFLL1o30bMy0dnL5Aevb9GY0ujBaqioioFLT2rKz3mp2j9BKfBh598ILM0IcXorIBfTSu7giXBJSalIYs66k04b4lDIuc5i8jJGNfT4aloYsD1Ek7I8FFHv1Mi51npSXEJK_CI5L908bnS3a2bGDS20000
)


#### Componentes

Contenedor: Backend:
* Controlador API: Gestiona las solicitudes HTTP y las dirige a los servicios correspondientes.
* Servicio de Gestión de Ofertas: Se encarga de la gestión de las ofertas de empleo.
* Servicio de Gestión de Candidatos: Maneja las operaciones relacionadas con los candidatos.
* Servicio de Autenticación: Proporciona funcionalidades de autenticación y autorización de usuarios.
Contenedor: Base de Datos:
* Modelo de Datos: Define la estructura de datos utilizada por el sistema.
* Conexión a la Base de Datos: Gestiona la comunicación y acceso a la base de datos.

![backend-components](https://www.planttext.com/api/plantuml/png/dPD1QiCm44NtEiMGVIwGHKYQGicYfD1byM8ocXPHHrCaEGHAJfKZv6BLs2RKDadSxioVh-Vv7saH4uPKxKfZlf0-yODXiXAVsBELC8E7BBAt4_Ws06yw2L9Y7i7oPLsezifXxyW9M8OdZicTJrw_D-yS4iQRdXLwwomc6TgMLTuXEK9ISs6ELnUChFv7fRHhFelbKYvgqQxEX_g_22LsZzNqGJYOJkVtuy6i8qiZ_vNsguWUa2wJCSnUQvdLLTHJnGg3KzxTR3M_twP2YJXARh9TR4oi_x3wSSOo1fRwuCqha2dhVAi2KbCKYLVJjZKrOBF8Rq4Vomy0)


#### Código

Clases del Backend:
* Application: Clase principal que inicia la aplicación.
* Config: Configuración de la aplicación.
* WebController: Controlador web que recibe las solicitudes HTTP.
* AuthService: Servicio de autenticación y autorización de usuarios.
* OfferService: Servicio para la gestión de ofertas de empleo.
* CandidateService: Servicio para la gestión de candidatos.
* Database: Capa de acceso a datos que interactúa con la base de datos.
* Entity: Clase base para las entidades del dominio (User, Offer, Candidate).
* User, Offer, Candidate: Entidades del dominio.
* OfferData, CandidateData: Clases de datos utilizadas para la creación y actualización de ofertas y candidatos.

![backend-code](https://www.planttext.com/api/plantuml/png/bLJBRiCW4BpxAr1EZbh_W6L5URI7I9LwYAgUYTcagCHOW5EbRVwzF6mCjXkr5mTcPfVT2UnIAYnKSs99KkFo7Hy1pTPw0HMPeQy4eP9XAT6ghXajiQAyyjY6LmTwzDjNs6j42SuOY3wmKMyx46TQWas7q1t26eDAcNpm8a6aZVvK-0GvsYb1g-CzgdNi1nUaG-OvCieW0HVqiuzsj5RjEMU0JP5NNyFpuG1YM4GfG1zlgPIRxmDME7TQivotwrRUr2IMRqbVxH_Y2J3u9LuhpvoILdW4PLNhovPCACESMhfYp28orTmJbQgmsqNK_mPNX9hofptmT5fsAzVB9jpEWttaoKHuwCq_SpgVRkOS-UNLrhFfYE4vpZkFzlvvAFRGbBl7ilTEuZEavXQhIuuUxMzSc7FdfiGrsqfkD6Zxcb2vd557lW_7nKrulTksBofu9ECh4_F6XR76ejSa2OO4oh95Do26S3meeftbWv4nmOQFUO8UtlKa7416qFsHIJGL8cRqNYBMcOYAxonp3eQ0Sp54UYUZ0ujERCqRdLY4aLQIBFL8DdFw1m00)