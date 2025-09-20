<div align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="logo"  width="20%"/>

**Universidad Peruana de Ciencias Aplicadas** <br>
**Ingeniería de Software** <br>
**Ciclo 2025-2** <br>

<h4>Desarrollo de Aplicaciones Open Source</h4>

**Sección:** 7380
**Profesor:** Mori Paiva, Hugo Allan

<h3>INFORME DEL TB1</h3>

**Startup:** InnovaSoft

**Producto:** RentiCar

**Integrantes:**

Huanca Zevallos, Cristhian Joel <br>
Landa Ortiz, Sergio Javier <br>
Sagastegui Rodriguez, Luis Jesus <br>
Solis Campos, Estefano Sebastian <br>
 

**Setiembre, 2024**

</div>

---

## Registro de Versiones del Informe

| Versión | Fecha       | Autor                                            | Descripción de modificación |
|---------|-------------|--------------------------------------------------|-----------------------------|
| 0.1     | 24/04/2025  | Todos los integrantes                            | Primer sprint TB1           |

## Project Report Collaboration Insights
| URL de la organización del proyecto |    URL del repositorio del reporte    |
|:-----------------------------------:|:-------------------------------------:|
|   https://github.com/CodexaTeam      | https://github.com/CodexaTeam/Report  |

## Contenido

- [Student Outcome](#student-outcome)

- [Capítulo I: Introducción](#cap1)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#cap2)
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
        - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
    - [2.5. Ubiquitous Language](#25-ubiquitous-language)



- [Capítulo III: Requirements Specification](#cap3)
    - [3.1. User Stories](#31-user-stories)
    - [3.2. Impact Mapping](#32-impact-mapping)
    - [3.3. Product Backlog](#33-product-backlog)


- [Capítulo IV: Product Design](#cap4)
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
        - [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
        - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
        - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
        - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagram](#481-database-diagram)


- [Capítulo V: Product Implementation, Validation & Deployment](#cap5)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
            - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
            - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**

**Criterio:** : Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.

<table>
  <tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
    <td>Comunica oralmente con efectividad a diferentes rangos de audiencia.</td>
    <td> </td>
    <td></td>
  </tr>
  <tr>
    <td>Comunica por escrito con efectividad a diferentes rangos de audiencia.</td>
    <td></td>
    <td></td>
  </tr>

</table>

---

# Capítulo I: Introducción

## 1.1. Startup Profile

En esta sección presentamos a InnovaSoft, nuestra startup tecnológica, así como el sector en el que buscamos incursionar, la problemática identificada y la solución propuesta. Este apartado tiene como finalidad brindar una visión clara del proyecto y de los objetivos que orientan a nuestro equipo.

### 1.1.1. Descripción de la Startup

InnovaSoft es una startup fundada por estudiantes de la carrera de Ingeniería de Software, orientada al desarrollo de soluciones digitales innovadoras. Para el presente ciclo académico, hemos planteado el desarrollo de una aplicación web denominada RentiCar, una plataforma destinada al alquiler de vehículos en el Perú.

Actualmente, el mercado de alquiler de autos en el país enfrenta limitaciones: procesos poco digitalizados, escasa confianza entre arrendadores y arrendatarios, y la ausencia de un sistema que centralice ofertas de forma segura y sencilla. Frente a esta problemática, RentiCar busca convertirse en un espacio confiable que conecte a propietarios de vehículos con clientes interesados en alquilarlos, garantizando una experiencia rápida, segura y transparente.

### Mision:

Facilitar el acceso al alquiler de vehículos en el Perú mediante una plataforma digital segura, confiable y de fácil uso, que conecte de manera transparente a propietarios y clientes.

### Vision: 

Convertirnos en la plataforma líder de alquiler de vehículos en el Perú y expandirnos hacia Latinoamérica, ofreciendo una experiencia innovadora, eficiente y 100% confiable, que transforme la forma en que las personas acceden a soluciones de movilidad.

### 1.1.2. Perfiles de integrantes del equipo


<table>
    <tr>
        <td>Perfil</td>
        <td>Foto</td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Huanca Zevallos, Cristhian Joel <br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Me considero una persona proactiva, organizada y responsable al momento de desarrollar un nuevo proyecto en mi vida. En un grupo de trabajo siempre trato de respetar las opiniones de los demás, trato de entender los demás puntos de vista y animo a estar en unión frente a un problema.  
        <td><img src="./assets/ChristianHuanca.jpeg" alt="Christian Huanca" width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Landa Ortiz, Sergio Javier <br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy un estudiante de software, cursando actualmente el 5to ciclo, la carrera me interesa mucho ya que siempre aprendo cosas nuevas cada dia, las tecnologias son tantas que nunca te aburres, me considero una persona responsable y me gusta trabajar en equipo. 
        <td><img src="./assets/SergioLanda.jpeg" alt="Sergio Landa"  width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Sagastegui Rodriguez, Luis Jesus <br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> Soy un estudiante de la carrera de ingenieria de Software y me apasiona mucho lo que hago. Siempre estoy interesado en aprender nuevas tecnologias y lenguajes de programacion. Me gusta ver proyectos de las demas personas y poder compartir ideas. Me considero una persona responsable y muy amable que siempre le gusta ayudar a las demas personas. Siempre trato de dar lo mejor de mi para poder destacar. 
        <td><img src="./assets/JesusSagastegui.jpg" alt="Jesus Sagastegui"  width="600"></td>
    </tr>
    <tr>
        <td><b>Nombre:</b> Solis Campos, Estefano Sebastian <br>
            <b>Carrera:</b> Ingenieria de Software <br>
        <b>Descripcion:</b> oy un estudiante apasionado de la carrera de Ingeniería de Software, actualmente en el quinto ciclo. Me entusiasma aplicar mis conocimientos en el desarrollo de soluciones innovadoras y estoy siempre buscando nuevas oportunidades para aprender y crecer en el mundo de la tecnología.
        <td><img src="./assets/EstefanoSolis.jpeg" alt="Estefano Solis" width="600"></td>
    </tr>
   <table>

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

En el Perú, el mercado de alquiler de vehículos se encuentra rezagado frente a otros servicios de movilidad, debido principalmente a la informalidad de las transacciones, la ausencia de plataformas centralizadas confiables y la desconfianza existente entre propietarios y clientes. Actualmente, la mayoría de operaciones se realiza mediante redes sociales, anuncios clasificados o contactos directos, lo que genera serios riesgos de fraude, pérdida de dinero, incumplimiento en los acuerdos y falta de respaldo legal. A esto se suma que, en la mayoría de los casos, los procesos son poco prácticos y requieren múltiples pasos presenciales, dificultando el acceso a un servicio rápido y eficiente.

Si bien existen alternativas en el mercado internacional, su cobertura en el Perú es limitada, costosa o no responde a la realidad del usuario promedio. Esto deja un vacío en el sector, el cual representa una oportunidad para el desarrollo de una solución digital innovadora. Por ello, resulta fundamental plantear una propuesta que brinde seguridad, transparencia y facilidad de uso, y que al mismo tiempo fomente la confianza entre los actores involucrados. Con este proyecto buscamos no solo atender una necesidad inmediata de movilidad, sino también impulsar la digitalización del sector y promover nuevas oportunidades económicas para los propietarios de vehículos.

A continuación, se presenta un análisis detallado de esta problemática empleando la metodología ‘5W2H’.

**Who** <br>

Por un lado, se encuentran los propietarios de vehículos, personas que muchas veces tienen un automóvil que no utilizan de forma constante y buscan una manera práctica y segura de generar ingresos adicionales a través de su alquiler. Por otro lado, están los clientes que requieren un vehículo de manera temporal, ya sea por motivos de viaje, trabajo, emergencias o simplemente por no contar con un automóvil propio. Ambos grupos comparten una necesidad común: acceder a un sistema que les permita conectarse de forma confiable y sencilla, sin tener que recurrir a procesos engorrosos o inseguros.

**What** <br>

Se identifica la urgencia de contar con una plataforma que funcione como un puente seguro y transparente entre propietarios y clientes. Actualmente, la falta de un servicio centralizado hace que el proceso de alquiler sea desordenado y arriesgado, lo cual limita el crecimiento del sector. Una solución digital debe resolver estos problemas principales: la confianza entre ambas partes, la formalización de los acuerdos y la rapidez en el proceso de búsqueda y alquiler.

**Where** <br>

El problema se concentra principalmente en el Perú, especialmente en las grandes ciudades como Lima, Arequipa y Trujillo, donde existe una mayor demanda de movilidad. Sin embargo, la problemática no es exclusiva de estas zonas; en regiones más pequeñas la necesidad es incluso mayor, ya que los servicios de alquiler tradicionales suelen ser escasos o inexistentes. Esto abre la posibilidad de que, una vez consolidada la solución en el ámbito nacional, se pueda escalar hacia otros países de Latinoamérica que presentan contextos similares.

**When** <br>

Con el avance de la digitalización y el creciente uso de plataformas para todo tipo de servicios, los usuarios esperan soluciones inmediatas y seguras. Sin embargo, el alquiler de vehículos aún no se ha adaptado a estas expectativas de forma integral en el Perú. Por lo tanto, el momento de implementar una plataforma como RentiCar es ahora, antes de que la brecha entre lo que el usuario espera y lo que el mercado ofrece se amplíe aún más.

**Why** <br>

Los clientes enfrentan altos niveles de incertidumbre al alquilar un vehículo, ya que no cuentan con garantías ni respaldo en caso de inconvenientes. Los propietarios, por su parte, ven limitado su potencial de generar ingresos debido al miedo al incumplimiento de acuerdos o al mal uso de sus vehículos. Una plataforma digital que brinde confianza, formalidad y simplicidad responde directamente a esta necesidad, ofreciendo beneficios tangibles a ambos actores y contribuyendo a mejorar el ecosistema de movilidad en el país.

**How** <br>

Esta plataforma permitirá a los propietarios registrar sus vehículos, establecer condiciones de alquiler y gestionar solicitudes de forma ordenada. Del mismo modo, los clientes podrán buscar, comparar y reservar autos de manera ágil, contando con herramientas de validación de usuarios, contratos digitales y sistemas de pago seguro. De esta manera, se garantizará una experiencia fluida y confiable para ambas partes.

**How Much** <br>

Es necesario destacar que el modelo de negocio propuesto se basa en un esquema de comisión por cada transacción realizada dentro de la plataforma. Esto implica que tanto la barrera de entrada como los costos iniciales de adopción para los usuarios serán bajos, lo cual favorece la masificación del servicio. La mayor inversión, en esta primera etapa, estará enfocada en el desarrollo tecnológico y en las estrategias de marketing para captar una base sólida de usuarios que permita validar y escalar el proyecto en el corto plazo.

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

El estado actual del alquiler de vehículos en el Perú se caracteriza por procesos informales, inseguros y desorganizados, que dependen principalmente de redes sociales, acuerdos verbales o contactos personales. Esta situación genera falta de confianza, riesgos de fraude, ausencia de respaldo legal y pérdida de tiempo tanto para propietarios como para clientes. Como resultado, los propietarios tienen miedo de arriesgar sus vehículos y los clientes carecen de garantías al momento de alquilar.

Nuestro producto busca cerrar esta brecha mediante el desarrollo de una plataforma digital confiable, diseñada para ofrecer procesos de verificación de identidad, contratos digitales y pagos seguros, con el fin de generar confianza y formalizar el mercado de alquiler de autos en el país.

Nuestro enfoque inicial se dirigirá a propietarios de vehículos interesados en generar ingresos adicionales y a clientes que necesitan movilidad temporal de forma segura y rápida, priorizando a usuarios urbanos familiarizados con servicios digitales.

Sabremos que tenemos éxito cuando logremos una reducción en la informalidad de las transacciones, un incremento en la confianza y satisfacción de propietarios y clientes, y un crecimiento sostenido en la cantidad de vehículos registrados y reservas confirmadas dentro de la plataforma.

#### 1.2.2.2. Lean UX Assumptions

En esta sección se formulan las hipótesis basadas en las suposiciones previas, estableciendo relaciones claras entre las características del producto, los comportamientos esperados de los usuarios y los resultados de negocio deseados.

1. Business Assumptions:

Asumimos que en el Perú existe un mercado con alto potencial para el alquiler de vehículos mediante plataformas digitales, debido a que actualmente predomina la informalidad y los usuarios carecen de una opción confiable que centralice la oferta y la demanda. Los propietarios de autos buscan generar ingresos adicionales y estarán interesados en publicar sus vehículos si se les ofrece un sistema con respaldo legal y garantías de seguridad, mientras que los clientes valorarán la posibilidad de alquilar un auto de forma rápida, segura y sin depender de trámites presenciales.

2. Business Outcome Assumptions:

Asumimos que si implementamos una plataforma segura, intuitiva y accesible, lograremos incrementar la confianza en el proceso de alquiler de vehículos en el país. Esto permitirá aumentar el número de autos registrados en la plataforma y generar un mayor volumen de transacciones. Un esquema de comisiones justo servirá como incentivo para que tanto propietarios como clientes prefieran RentiCar frente a canales informales, garantizando así la sostenibilidad del modelo de negocio.

3. User Assumptions:

Asumimos que los propietarios y clientes cuentan con acceso a internet y a dispositivos que les permiten interactuar con plataformas digitales, tal como ya lo hacen en servicios de transporte o delivery. Los propietarios sienten preocupación por la seguridad y buscan garantías que reduzcan riesgos de fraude o mal uso de sus autos, mientras que los clientes esperan procesos simples, rápidos y transparentes que les permitan alquilar sin depender de contactos personales.

4. User Outcome Assumptions:

Asumimos que si los propietarios perciben que la plataforma ofrece seguridad y respaldo, estarán dispuestos a alquilar sus autos con mayor frecuencia y a obtener ingresos adicionales de forma constante. Por su parte, los clientes, al encontrar un proceso confiable y fácil de usar, recurrirán al servicio de manera recurrente y lo recomendarán a otros. Una experiencia positiva aumentará la satisfacción y fidelización de los usuarios, contribuyendo al crecimiento orgánico de la comunidad.

5. Feature Assumptions:

Asumimos que las funcionalidades esenciales como la verificación de identidad, los contratos digitales, el sistema de reservas, los pagos seguros y las calificaciones entre usuarios serán suficientes para generar confianza en la etapa inicial. Una interfaz sencilla permitirá que incluso usuarios con poca experiencia digital utilicen la plataforma sin dificultad, mientras que el lanzamiento de un MVP con estas características será suficiente para validar el modelo de negocio y escalar posteriormente hacia funcionalidades más avanzadas como aplicaciones móviles, seguros integrados o servicios complementarios.

#### 1.2.2.3. Lean UX Hypothesis Statements

En esta sección se presentan las suposiciones clave que sustentan el diseño y desarrollo del producto. Estas suposiciones se basan en el entendimiento actual de las necesidades y comportamientos de los usuarios, así como en las condiciones del mercado. Identificar y documentar estas suposiciones permite al equipo alinearse en torno a expectativas comunes y establecer una base sólida para el proceso de validación a través de pruebas e iteraciones futuras.

**Hypothesis Statements 1:**

Creemos que en el Perú existe un mercado desatendido para el alquiler de vehículos mediante plataformas digitales, ya que la mayoría de transacciones se realizan de forma informal y sin garantías. Si ofrecemos un servicio confiable, con respaldo legal y mecanismos de seguridad, los propietarios estarán dispuestos a registrar sus autos y los clientes a alquilarlos con confianza.

**Hypothesis Statements 2:**

Creemos que al implementar una plataforma segura, transparente y de fácil uso lograremos aumentar el número de autos registrados y la cantidad de transacciones realizadas. Esto permitirá generar ingresos sostenibles a través de un esquema de comisiones, consolidando a RentiCar como la opción preferida frente a los canales informales y asegurando la viabilidad del negocio.

**Hypothesis Statements 3:**

Creemos que los propietarios de autos con acceso a internet y dispositivos digitales desean nuevas formas de generar ingresos y están preocupados por la seguridad de sus vehículos, mientras que los clientes buscan una experiencia de alquiler rápida y confiable. Una solución que combine facilidad de uso y garantías de seguridad responderá a las necesidades de ambos segmentos.

**Hypothesis Statements 4:**

Creemos que si los propietarios perciben que RentiCar les ofrece seguridad, respaldo legal y un sistema confiable, utilizarán la plataforma de forma recurrente y la recomendarán a otros. Al mismo tiempo, los clientes satisfechos por la simplicidad y confianza del servicio volverán a alquilar vehículos y contribuirán al crecimiento de la comunidad mediante la fidelización y el boca a boca.

**Hypothesis Statements 5:**

Creemos que al integrar funcionalidades clave como verificación de identidad, contratos digitales, pagos seguros, calificaciones y un sistema de reservas intuitivo, lograremos generar confianza en la etapa inicial. Estas características serán suficientes para validar la propuesta de valor en un MVP, y posteriormente podrán ampliarse con funcionalidades más avanzadas como aplicaciones móviles, seguros integrados y servicios complementarios.

#### 1.2.2.4. Lean UX Canvas

<table>
    <tr>
        <th colspan="1" valign="top">
            <p><b>Business Problem</b></p>
            <p>El alquiler de vehículos en el Perú se realiza mayoritariamente de manera informal, lo que genera desconfianza, riesgo de fraudes, falta de garantías legales y pérdida de tiempo para propietarios y clientes. La ausencia de una plataforma confiable centraliza este problema y limita el desarrollo de un mercado digital seguro
            </p>
        </th>
        <th colspan="1" rowspan="2" valign="top">
            <p><b>Solution Ideas</b></p>
            <p>Plataforma web que conecte a propietarios y clientes en un entorno seguro.</p>
            <p>Registro y verificación de identidad de usuarios.</p>
            <p>Publicación de vehículos con fotos, precios y disponibilidad.</p>
            <p>Sistema de reservas en línea con contratos digitales automáticos.</p>
            <p>Pasarela de pagos segura y protegida.</p>
            <p>Calificaciones y reseñas para generar confianza.</p>
        </th>
        <th colspan="1" valign="top">
            <p><b>Business Outcomes</b></p>
            <p>Aumentar el número de vehículos registrados y transacciones mensuales.</p>
            <p>Generar ingresos sostenibles mediante comisiones por alquiler.</p>
            <p>Reducir la informalidad del mercado de alquiler de autos.</p>
            <p>Posicionar a RentiCar como la plataforma más confiable del Perú.</p>
        </th>
    </tr>
    <tr>
        <td colspan="1" valign="top">
            <p><b>User & Customers</b></p>
            <p>Propietarios de vehículos que buscan generar ingresos adicionales.</p>
            <p>Clientes que requieren movilidad temporal de forma rápida y confiable.</p>
        </td>
        <td colspan="1" valign="top">
            <p><b>User Benefits</b></p>
            <p><b>Propietarios:</b> Seguridad en sus transacciones, respaldo legal y una fuente estable de ingresos adicionales.</p>
            <p><b>Clientes:</b> Acceso rápido y confiable a vehículos, con un proceso claro, seguro y transparente.</p>
        </td>
    </tr>
    <tr>
        <td colspan="1" valign="top">
            <p><b>Hypotheses</b></p>
            <p>Creemos que si ofrecemos una plataforma con pagos seguros y contratos digitales, los propietarios estarán dispuestos a registrar sus autos.</p>
            <p>Creemos que si los clientes encuentran un servicio rápido, confiable y con precios competitivos, recurrirán al alquiler de manera recurrente.</p>
            <p>Creemos que un MVP con funcionalidades básicas (registro, publicación, reservas, pagos y calificaciones) será suficiente para validar el modelo de negocio.</p>
        </td>
        <td colspan="1" valign="top">
            <p><b>What’s the most important thing we need to learn first?</b></p>
            <p>Construir un MVP con las funcionalidades esenciales: registro y verificación de usuarios, publicación de vehículos, sistema de reservas y pagos seguros. Esto permitirá validar rápidamente la adopción de la plataforma, medir el interés de propietarios y clientes, y comprobar si el modelo de negocio es viable antes de invertir en características avanzadas.</p>
        </td>
        <td colspan="1" valign="top">
            <p><b>What’s the least amount of work we need to do to learn the most important thing?</b></p>
            <p>Lo más importante que necesitamos aprender primero es si los usuarios (propietarios y clientes) confían lo suficiente en la plataforma para usarla como canal principal de alquiler de vehículos. La confianza es la base del modelo de negocio: si logramos demostrar que los usuarios se sienten seguros, el crecimiento y la adopción podrán escalar de manera sostenible.</p>
        </td>
    </tr>
</table>