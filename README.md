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

## 1.3. Segmentos objetivo

<b>Segmento 1 (Arrendador de vehículo):</b>

Dueños de autos que no usan su vehículo con frecuencia y desean generar ingresos extras, estos serían personas de edad entre 25 a 45 años que residen en Lima Metropolitana.

<b>Segmento 2 (Arrendatario de vehículo):</b>

Personas que necesitan un vehículo de manera temporal que tengan edad entre 25 a 45 años con residencia en Lima Metropolitana y estos no tendrían un auto propio o profieran no usarlo todo el tiempo, así buscando una alternativa más económica y flexible frente a taxis o apps de transporte.

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

| Nombre del Competidor | Descripción |
| :-------------------: | :---------- |
| Peru Rent a Car <img src="./assets/PeruRentCar.jpg" alt="PeruRentCar" width="600"> https://www.perurentacar.com/ | Life Alert es una de las marcas más reconocidas en sistemas de alerta médica, famosa por su eslogan “¡He caído y no puedo levantarme!”. Ofrece sistemas de emergencia diseñados para ayudar a personas mayores a solicitar asistencia rápidamente. Su principal dispositivo es un botón de emergencia que puede usarse en el hogar o fuera de él, enviando alertas a un centro de monitoreo disponible las 24 horas del día. |
| Clase A Rent a Car <img src="./assets/ClaseARentCar.png" alt="ClaseARentCar" width="600"> https://www.alquilerautoslima.net/  | MobileHelp es un proveedor líder de sistemas de alerta médica que ofrece dispositivos portátiles y basados en el hogar para personas mayores. Sus dispositivos están diseñados para alertar a los servicios de emergencia en caso de una caída u otro incidente. Además de las soluciones de emergencia en el hogar, MobileHelp destaca por su cobertura fuera de casa gracias a su integración con redes móviles, lo que ofrece a los usuarios mayor independencia y movilidad. |
| Rento <img src="./assets/RentoRent.jpg" alt="RentoRent" width="600"> https://rento.pe/  | CarePredict es una empresa tecnológica que se enfoca en el monitoreo preventivo para adultos mayores. Utiliza dispositivos portátiles equipados con sensores para rastrear patrones de comportamiento y signos vitales. A través de la inteligencia artificial, CarePredict predice posibles problemas de salud antes de que ocurran, como caídas o infecciones, y permite la intervención proactiva de cuidadores y familiares. |


### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
  </tr>
  <tr>
    <td colspan="5">Comparar las características y funcionalidades clave de nuestra solución con las de la competencia para identificar ventajas competitivas y posibles áreas de mejora.</td>
  </tr>
  <tr>
    <td colspan="3">Competidores</td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center">
        RentiCar 
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center">
        Peru Rent a Car 
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center" >
        Clase A Rent a Car 
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;text-align: center" >
        Rento
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Plataforma web P2P para conectar dueños de autos con clientes de alquiler. Busca ser rápida, segura y fácil de usar, apostando por digitalización total y confianza.
    </td>
    <td colspan="1" valign="top">Empresa tradicional con más de 20 años en el mercado peruano. Ofrece autos, camionetas y vans con seguro, asistencia y soporte para turistas y empresas.
    </td>
    <td colspan="1" valign="top">Empresa local de alquiler con sede en Lima, enfocada en brindar vehículos modernos, en buen estado y con contratos flexibles. Reconocida por su trato personalizado.
    </td>
    <td colspan="1" valign="top">Primera app P2P de alquiler de autos particulares en Perú. Incluye seguro RIMAC, GPS, monitoreo 24/7 y verificación de usuarios. Opera solo en Lima pero con visión de crecer a nivel nacional.
    </td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">Modelo 100% colaborativo y escalable, con costos más bajos y posibilidad de crecer en número de autos sin necesidad de flota propia.
    </td>
    <td colspan="1" valign="top">Reputación consolidada, flota amplia y experiencia. Fiabilidad percibida por clientes corporativos y turistas.
    </td>
    <td colspan="1" valign="top">Atención cercana y personalizada. Ideal para clientes que priorizan confianza y flexibilidad de trato.
    </td>
    <td colspan="1" valign="top">Innovación tecnológica y respaldo asegurador fuerte. Modelo digital pionero en Perú.
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top"> Jóvenes profesionales, turistas digitales, empresas pequeñas que buscan movilidad flexible y propietarios de autos que quieren generar ingresos extra.
    </td>
    <td colspan="1" valign="top">Turistas extranjeros y nacionales, empresas que requieren autos para personal o ejecutivos, familias que buscan viajes seguros.
    </td>
    <td colspan="1" valign="top">Residentes de Lima y clientes que buscan un servicio confiable y directo con atención humana.
    </td>
    <td colspan="1" valign="top">Dueños de autos que buscan monetizar su vehículo, arrendatarios jóvenes urbanos, millennials y usuarios tecnológicos.
    </td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">Campañas digitales (redes, SEO/SEM), promociones de lanzamiento, alianzas con aseguradoras y fintechs, programas de referidos.
    </td>
    <td colspan="1" valign="top">Presencia en buscadores, alianzas con agencias de viajes, ferias de turismo y marketing tradicional.
    </td>
    <td colspan="1" valign="top">Publicidad local, confianza por reputación y marketing boca a boca.
    </td>
    <td colspan="1" valign="top">Estrategia digital intensiva en redes sociales, marketing de confianza basado en seguridad y respaldo legal.
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Alquiler P2P, validación digital de usuarios, registro de autos particulares, seguros, sistema de alertas y soporte técnico.
    </td>
    <td colspan="1" valign="top">Alquiler de autos, camionetas, vans y pickups. Incluye seguros, GPS opcional, servicios corporativos y entrega en aeropuertos.
    </td>
    <td colspan="1" valign="top">Alquiler de autos modernos, seguros incluidos, contratos adaptables según el cliente, soporte continuo.
    </td>
    <td colspan="1" valign="top">Alquiler peer-to-peer, seguro todo riesgo, GPS obligatorio, verificación de identidad y central de monitoreo 24/7.
    </td>
  </tr>
  <tr>
    <td colspan="2">Precios y Costos</td>
    <td colspan="1" valign="top">Precios competitivos, definidos por los propietarios pero regulados por la plataforma. Comisiones más bajas que empresas tradicionales.
    </td>
    <td colspan="1" valign="top">Tarifas medias-altas. Reflejan el costo de mantener una flota propia, seguros completos y servicios adicionales.
    </td>
    <td colspan="1" valign="top">Tarifas medias. Ajustadas a la atención personalizada y al buen estado de la flota.
    </td>
    <td colspan="1" valign="top">Tarifas dinámicas, generalmente más bajas que rent a car tradicionales gracias al modelo P2P.
    </td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución</td>
    <td colspan="1" valign="top">Pagina Web. Alianzas con aseguradoras y canales digitales.
    </td>
    <td colspan="1" valign="top">Oficinas físicas en Lima + página web y contacto telefónico.
    </td>
    <td colspan="1" valign="top">Oficina física, reservas por teléfono y página web.
    </td>
    <td colspan="1" valign="top">Aplicación móvil y web con reservas 100% digitales.
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Modelo escalable sin necesidad de flota propia, digitalización completa, costos más bajos, foco en experiencia de usuario.
    </td>
    <td colspan="1" valign="top">Reputación, infraestructura establecida, atención corporativa, variedad de flota.
    </td>
    <td colspan="1" valign="top">Atención personalizada, trato humano, autos modernos y cuidados.
    </td>
    <td colspan="1" valign="top">Innovación tecnológica, confianza gracias a seguro RIMAC y GPS, pioneros en P2P.
    </td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Startup nueva sin reputación consolidada, confianza inicial a construir.
    </td>
    <td colspan="1" valign="top">Modelo rígido y menos flexible, procesos más burocráticos.
    </td>
    <td colspan="1" valign="top">Escala limitada y menos variedad de flota frente a grandes competidores.
    </td>
    <td colspan="1" valign="top">Flota aún limitada, dependencia del crecimiento de usuarios particulares.
    </td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">Crecimiento de la economía colaborativa, demanda de digitalización, aumento de turismo y movilidad urbana.
    </td>
    <td colspan="1" valign="top">Aumento del turismo post-pandemia, expansión del mercado corporativo.
    </td>
    <td colspan="1" valign="top">Crecimiento de clientes que buscan atención diferenciada.
    </td>
    <td colspan="1" valign="top">Expansión nacional, crecimiento de usuarios P2P en Perú.
    </td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Competencia consolidada, regulaciones del sector transporte, desconfianza inicial.
    </td>
    <td colspan="1" valign="top">Ingreso de apps digitales y startups más ágiles.
    </td>
    <td colspan="1" valign="top">Pérdida de clientes frente a plataformas digitales con mayor alcance.
    </td>
    <td colspan="1" valign="top">Aparición de nuevos competidores internacionales o nacionales con más capital.
    </td>
  </tr>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

<table>
  <tr>
    <th colspan="3" valign="top"></th>
    <th colspan="4" valign="top"><b>OPORTUNIDADES</b></th>
    <th colspan="4" valign="top"><b>AMENAZAS</b></th>
  </tr>
  <tr>
    <th colspan="3" valign="top"></th>
    <td colspan="4" valign="top">
      <li> Crecimiento del turismo interno y extranjero en Perú.
      <li> Tendencia a la digitalización de servicios de movilidad.
      <li> Aumento de la demanda de opciones económicas y flexibles en transporte.
      <li> Interés de PYMEs y startups por servicios de movilidad alternativos.
    </td>
    <td colspan="4" valign="top">
      <li> Alta competencia de empresas consolidadas (Peru Rent a Car, Clase A).
      <li> Competidores emergentes con modelo digital similar (Rento).
      <li> Riesgo de guerra de precios.
      <li> Desconfianza cultural hacia plataformas nuevas.
    </td>
  </tr>

  <tr>
    <th colspan="3" valign="top"><b>FORTALEZAS</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS FO (Ofensivas)</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS FA (Defensiva)</b></th>
  </tr>
  <tr>
    <td colspan="3" valign="top">
      <li> Plataforma 100% digital con reservas rápidas y seguras.
      <li> Flexibilidad en planes de alquiler (por horas, días o suscripción mensual).
      <li> Uso de tecnología IoT (GPS, monitoreo en tiempo real).
      <li> Enfoque en experiencia del usuario y atención 24/7.
    </td>
    <td colspan="4" valign="top">
      <li> Posicionar a RentiCar como la plataforma de alquiler más ágil y flexible para turistas y jóvenes en Lima. 
      <li> Usar la tecnología IoT como diferenciador innovador, mostrando seguridad y control en tiempo real.
      <li> Generar alianzas con hoteles, agencias de turismo y startups para integrar RentiCar en experiencias de viaje y negocios.
    </td>
    <td colspan="4" valign="top">
      <li> Diferenciarse de grandes competidores mediante la rapidez y simplicidad digital.
      <li> Competir con Rento ofreciendo mayor cobertura y disponibilidad de vehículos.
      <li> Evitar la guerra de precios destacando valor agregado: seguridad, flexibilidad y soporte 24/7.
    </td>
  </tr>

  <tr>
    <th colspan="3" valign="top"><b>DEBILIDADES</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS DO (Reorientación)</b></th>
    <th colspan="4" valign="top"><b>ESTRATEGIAS DA (Supervivencia)</b></th>
  </tr>
  <tr>
    <td colspan="3" valign="top">
      <li> Marca nueva sin historial ni reputación consolidada.
      <li> Flota inicial limitada frente a grandes competidores.
      <li> Recursos financieros más reducidos que empresas consolidadas.
      <li> Dependencia de la confianza digital en un mercado aún en transición.
    </td>
    <td colspan="4" valign="top">
      <li> Reforzar la confianza en la marca mediante certificaciones, seguros y políticas transparentes.
      <li> Expandir la flota progresivamente a través de convenios con propietarios particulares y PYMEs.
      <li> Aprovechar la digitalización para compensar la falta de trayectoria, mostrando procesos claros, seguros y amigables.
    </td>
    <td colspan="4" valign="top">
      <li> Lanzar campañas de marketing educativo sobre la seguridad y beneficios de alquilar en plataformas digitales.
      <li> Implementar un programa de fidelización para generar usuarios recurrentes desde el inicio.
      <li> Diversificar fuentes de ingreso (planes corporativos, suscripciones, alquiler por horas) para reducir vulnerabilidad frente a la competencia.
    </td>

  </tr>

</table>

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
## 2.4. Big Picture EventStorming
## 2.5. Ubiquitous Language

# Capítulo III: Requirements Specification
## 3.1. User Stories

| **Epic / Story ID** | **Título**                            | **Descripción**                                                                                                     | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                                     | **Relacionado con (Epic ID)** |
|---------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| US-01               | Registro de Usuario                   | Como visitante, quiero registrarme en la aplicación para poder publicar vehículos o consultar opciones de alquiler. | Escenario 1: Given que un visitante accede al formulario de registro, when ingresa datos válidos y selecciona “Registrar”, then el sistema crea la cuenta y muestra un mensaje de confirmación. Escenario 2: Given que el visitante ingresa datos inválidos, when intenta registrarse, then el sistema muestra un error solicitando corrección. | EP-01                         |
| US-02               | Log In                                | Como usuario, quiero iniciar sesión con mis credenciales para acceder a mis publicaciones o realizar reservas.      | Escenario 1: Given que el usuario ya está registrado, when ingresa credenciales válidas, then accede al sistema. Escenario 2: Given que el usuario ingresa credenciales incorrectas, when intenta acceder, then el sistema muestra un aviso para reintentar.                                                                                    | EP-01                         |
| US-03               | Recuperación de Contraseña            | Como usuario, quiero restablecer mi contraseña en caso de pérdida de acceso a la cuenta.                            | Escenario 1: Given que el usuario olvidó su contraseña, when ingresa su correo válido, then se envía un link de recuperación. Escenario 2: Given que el usuario ingresa datos erróneos, when solicita recuperación, then el sistema muestra un error de validación.                                                                             | EP-01                         |
| US-04               | Dashboard del usuario                 | Como usuario, quiero contar con un Dashboard donde pueda consultar información de mis reservas.                     | Escenario 1: Given que el usuario accede al sistema, when selecciona “Log-In”, then se carga la pestaña “Dashboard”. Escenario 2: Given que está en otra pestaña, when selecciona “Dashboard”, then se redirige al panel principal.                                                                                                             | EP-02                         |
| US-05               | Sección Destacados del Dashboard      | Como usuario, quiero ver una sección de destacados con vehículos recomendados.                                      | Escenario 1: Given que el usuario accede al Dashboard, when está en la sección “Destacados”, then se muestran autos sugeridos. Escenario 2: Given que selecciona “Ver más”, when lo hace, then se redirige al catálogo de autos.                                                                                                                | EP-02                         |
| US-06               | Sección Publicados del Dashboard      | Como usuario, quiero visualizar mis vehículos publicados desde el Dashboard.                                        | Escenario 1: Given que accede al Dashboard, when se sitúa en la sección “Mis Publicaciones”, then se muestran sus autos publicados. Escenario 2: Given que selecciona “Nueva Publicación”, when lo hace, then se redirige al formulario de publicación.                                                                                         | EP-02                         |
| US-07               | Cancelar reserva de vehículo          | Como usuario, quiero cancelar una reserva de un vehículo.                                                           | Escenario 1: Given que está en su Dashboard, when selecciona una reserva, then puede cancelarla. Escenario 2: Given que selecciona varias reservas, when elige cancelación múltiple, then puede eliminarlas en lote.                                                                                                                            | EP-02                         |
| US-08               | Pestaña de Publicación                | Como usuario, quiero acceder a una pestaña de publicación para crear y gestionar mis vehículos en alquiler.         | Escenario 1: Given que desea publicar un vehículo, when selecciona “Nueva Publicación”, then se muestra el formulario. Escenario 2: Given que está en otra pestaña, when selecciona “Publicación”, then se redirige.                                                                                                                            | EP-03                         |
| US-09               | Creación de publicaciones             | Como usuario, quiero registrar publicaciones para ofrecer mis autos en alquiler.                                    | Escenario 1: Given que selecciona crear, when ingresa la información, then se guarda la publicación. Escenario 2: Given que selecciona una publicación, when la edita, then puede actualizar su información.                                                                                                                                    | EP-03                         |
| US-10               | Visualizar una publicación            | Como usuario, quiero consultar la información de una publicación creada.                                            | Escenario 1: Given que está en publicaciones, when selecciona una, then se muestran los datos. Escenario 2: Given que selecciona “Modificar”, when lo hace, then puede actualizar los datos registrados.                                                                                                                                        | EP-03                         |
| US-11               | Eliminar una publicación              | Como usuario, quiero eliminar una publicación ya creada.                                                            | Escenario 1: Given que selecciona una publicación, when hace clic en “Eliminar”, then se borra. Escenario 2: Given que selecciona varias publicaciones, when elige “Eliminar múltiples”, then puede eliminarlas en lote.                                                                                                                        | EP-03                         |
| US-12               | Pestaña de Navegación                 | Como usuario, quiero recorrer las publicaciones de autos disponibles en alquiler.                                   | Escenario 1: Given que desea explorar, when accede a “Navegación”, then se muestran los autos disponibles. Escenario 2: Given que está en otra pestaña, when selecciona “Navegación”, then se redirige a la sección.                                                                                                                            | EP-04                         |
| US-13               | Ordenar el precio de los alquileres   | Como usuario, quiero ordenar los alquileres según precio.                                                           | Escenario 1: Given que está en Navegación, when selecciona el ícono de ordenar, then los precios se listan de menor a mayor. Escenario 2: Given que ya ordenó, when vuelve a hacer clic, then se ordenan de mayor a menor.                                                                                                                      | EP-04                         |
| US-14               | Filtrado de marcas                    | Como usuario, quiero filtrar los vehículos en base a su marca.                                                      | Escenario 1: Given que escribe una marca en el campo, when confirma, then se muestran autos de esa marca. Escenario 2: Given que restablece filtros, when hace clic en “Borrar Filtros”, then se muestran todos nuevamente.                                                                                                                     | EP-04                         |
| US-15               | Reseñar publicaciones de alquiler     | Como usuario, quiero dejar reseñas sobre los autos que alquilé.                                                     | Escenario 1: Given que completó una reserva, when selecciona “Dejar Reseña”, then puede puntuar del 1 al 5. Escenario 2: Given que añade comentario, when lo guarda, then queda visible en la publicación.                                                                                                                                      | EP-04                         |
| US-16               | Reserva de vehículo                   | Como usuario, quiero reservar un auto en línea para asegurar su disponibilidad.                                     | Escenario 1: Given que está en una publicación, when selecciona “Reservar”, then elige fecha y horario. Escenario 2: Given que confirma reserva, when finaliza, then se registra en el sistema.                                                                                                                                                 | EP-04                         |
| US-17               | Ver estado IoT del auto               | Como usuario, quiero visualizar un indicador de ubicación y estado del vehículo durante la reserva.                 | Escenario 1: Given que tengo una reserva activa, when consulto la ficha del vehículo, then se muestra un widget con estado (Disponible/En uso) y ubicación general. Escenario 2: Given que el auto no tiene IoT activo, when consulto la ficha, then el widget no se muestra.                                                                   | EP-04                         |
| US-18               | Pestaña de Perfil                     | Como usuario, quiero acceder a mi perfil con mis datos personales y documentos.                                     | Escenario 1: Given que accedo a “Perfil”, when lo selecciono, then puedo ver o editar mi información. Escenario 2: Given que estoy en otra pestaña, when selecciono “Mi Perfil”, then se me redirige a la pestaña.                                                                                                                              | EP-05                         |
| US-19               | Crear Perfil                          | Como usuario, quiero crear un perfil con mis datos personales.                                                      | Escenario 1: Given que accedo a “Nuevo Perfil”, when ingreso datos, then se guarda mi información. Escenario 2: Given que dejo campos vacíos, when finalizo, then se me pide completarlos correctamente.                                                                                                                                        | EP-05                         |
| US-20               | Modificar Perfil                      | Como usuario, quiero editar la información ya registrada en mi perfil.                                              | Escenario 1: Given que accedo a mi perfil existente, when selecciono “Modificar”, then puedo cambiar información. Escenario 2: Given que ingreso datos inválidos, then el sistema me muestra un mensaje de corrección.                                                                                                                          | EP-05                         |
| US-21               | Cargar documentos de garantía         | Como usuario, quiero subir documentos personales para validar mi identidad y poder alquilar autos.                  | Escenario 1: Given que estoy en mi perfil, when selecciono “Cargar Documentos”, then puedo subir archivos. Escenario 2: Given que selecciono un archivo ya existente, when lo reemplazo, then se guarda la nueva versión.                                                                                                                       | EP-05                         |
| US-22               | Acceso a la Landing Page              | Como visitante, quiero acceder a la landing page de Renticar y conocer el servicio.                                 | Given que accedo a la landing page, when navego por sus secciones, then debo visualizar beneficios y características del producto.                                                                                                                                                                                                              | EP-06                         |
| US-23               | Ver Información del Producto          | Como visitante, quiero leer información clara sobre el producto.                                                    | Given que estoy en la landing, when accedo a “Why Choose Us”, then debo ver las características principales.                                                                                                                                                                                                                                    | EP-06                         |
| US-24               | Consultar los modelos disponibles     | Como visitante, quiero revisar una muestra de vehículos disponibles en la página principal.                         | Given que estoy en la landing, when accedo a “Popular Cars”, then debo visualizar opciones destacadas.                                                                                                                                                                                                                                          | EP-06                         |
| US-25               | Leer Testimonios de Clientes y Dueños | Como visitante, quiero leer testimonios de clientes y dueños para confiar en el servicio.                           | Given que estoy en la landing, when accedo a “Testimonials”, then debo ver reseñas verificadas.                                                                                                                                                                                                                                                 | EP-06                         |
| TS-26               | Traducción de la Landing Page         | Como visitante, quiero cambiar el idioma de la landing page.                                                        | Given que estoy en la landing, when selecciono idioma “Español/Inglés”, then el contenido se actualiza.                                                                                                                                                                                                                                         | EP-06                         |
| TS-27               | Call To Action                        | Como visitante, quiero suscribirme dejando mi correo para recibir novedades.                                        | Given que estoy en la landing, when selecciono “Know More” y completo el formulario, then mi correo queda registrado para recibir noticias.                                                                                                                                                                                                     | EP-06                         |

### **Epic 01: Creación y Gestión de Cuenta**
| **Story ID** | **Título**                |
|--------------|---------------------------|
| US-01        | Registro de Usuario       |
| US-02        | Inicio de Sesión          |
| US-03        | Recuperar Contraseña      |

### **Epic 02: Dashboard del Usuario**
| **Story ID** | **Título**                    |
|--------------|-------------------------------|
| US-04        | Dashboard del usuario         |
| US-05        | Destacados en el Dashboard    |
| US-06        | Publicaciones en el Dashboard |
| US-07        | Cancelar Reserva de Vehículo  |

### **Epic 03: Creación y Visualización de Publicaciones**
| **Story ID** | **Título**             |
|--------------|------------------------|
| US-08        | Pestaña de Publicación |
| US-09        | Crear Publicación      |
| US-10        | Visualizar Publicación |
| US-11        | Eliminar Publicación   |

### **Epic 04: Navegación de Alquileres Disponibles**
| **Story ID** | **Título**                  |
|--------------|-----------------------------|
| US-12        | Navegación de Publicaciones |
| US-13        | Ordenar por Precio          |
| US-14        | Filtrar por Marca           |
| US-15        | Reseñar Publicaciones       |
| US-16        | Reservar Vehículo           |
| US-17        | Ver estado IoT del auto     |

### **Epic 05: Perfil de Usuario**
| **Story ID** | **Título**                    |
|--------------|-------------------------------|
| US-18        | Pestaña de Perfil             |
| US-19        | Crear Perfil                  |
| US-20        | Modificar Perfil              |
| US-21        | Cargar documentos de garantía |

### **Epic 06: Interacción con la Landing Page**
| **Story ID** | **Título**                    |
|--------------|-------------------------------|
| US-22        | Acceso a Landing Page         |
| US-23        | Información del Producto      |
| TS-24        | Catálogo Popular              |
| TS-25        | Testimonios                   |
| TS-26        | Traducción de la Landing Page |
| TS-27        | Call To Action                |

## 3.2. Impact Mapping
## 3.3. Product Backlog

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level EventStorming
### 4.6.2. Software Architecture Context Diagram
### 4.6.3. Software Architecture Container Diagrams
### 4.6.4. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
## 4.8. Database Design
### 4.8.1. Database Diagram


# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog 1
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

# Conclusiones
# Bibliografía
# Anexos