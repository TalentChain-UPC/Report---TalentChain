## **TB1-Report**

### **Universidad Peruana de Ciencias Aplicadas**<img src="./media/image20.png" style="width:1.95313in;height:1.95313in" />

## 

#### **Ingeniería de Software**

# Arquitecturas De Software Emergentes

#### **Sección : 4281**

#### **Docente: Royer Edelwer Rojas Malasquez** 

#### **Informe TB1**

#### **Startup: TalentChain**

#### **Producto: SkillLedger**

### **Team Members**

\- Brayan Stiven Gamboa Delgado

\- Luiggi Jeremy Jouvenel Antonio Loayza

\- Rony Piero Ticona Luque

\- Luis Enrique Aquije Quiroga

\- Jorge Gerardo Quilla Luyo

2025

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|----|----|----|----|
| 0.1 | 21/04/2025 | Rony Ticona | Diseño de Entrevista |
| 0.2 | 22/04/2025 | Rony Ticona | Registro de Entrevista segmento Empresa |
| 0.3 | 23/04/2025 | Jorge Quilla | Registro de entrevistas Segmento Trabajador |
| 0.4 | 23/04/2025 | Jorge Quilla | Strategic-Level: Attribute-Driven Design y Domain-Driven Design |
| 0.5 | 23/04/2025 | Rony Ticona | User Persona y User Task Matrix |
| 0.6 | 23/04/2025 | Rony Ticona | Empathy mapping |
| 0.7 | 23/04/2025 | Brayan Gamboa | Software Architecture |
| 0.8 | 23/04/2025 | Jeremy Antonio | Capítulo 1, As Is, To be y revisión del informe |
| 0.9 | 23/04/2025 | Luis Aquije | User Stories y Product Backlog |
| 1.0 | 25/04/2025 | Rony Ticona | Conclusiones |

# Project Report Collaboration Insights

# Contenido

[**Student Outcome 5**](#student-outcome)

[**Capítulo I: Introducción 7**](#capítulo-i-introducción)

> [1.1. Startup Profile 7](#startup-profile)
>
> [1.1.1. Descripción de la Startup 7](#descripción-de-la-startup)
>
> [1.2.1 Antecedentes y problemática 10](#antecedentes-y-problemática)
>
> [1.2.2 Lean UX Process 12](#lean-ux-process)
>
> [1.3. Segmentos objetivos 16](#segmentos-objetivos)

[**Capítulo II: Requirements Elicitation & Analysis
16**](#capítulo-ii-requirements-elicitation-analysis)

> [2.1. Competidores 16](#competidores)
>
> [2.1.1. Análisis competitivo 16](#análisis-competitivo)
>
> [2.1.2. Estrategias y tácticas frente a competidores
> 20](#estrategias-y-tácticas-frente-a-competidores)
>
> [2.2. Entrevistas 21](#entrevistas)
>
> [2.2.1. Diseño de entrevistas 21](#diseño-de-entrevistas)
>
> [2.2.2. Registro de entrevistas 23](#registro-de-entrevistas)
>
> [2.2.3. Análisis de entrevistas 26](#análisis-de-entrevistas)
>
> [2.3. Needfinding 28](#needfinding)
>
> [2.3.1. User Personas 28](#user-personas)
>
> [2.3.2. User Task Matrix 30](#user-task-matrix)
>
> [2.3.3. Empathy Mapping 31](#empathy-mapping)
>
> [2.3.4. As-is Scenario Mapping 33](#as-is-scenario-mapping)
>
> [2.4. Ubiquitous Language 34](#ubiquitous-language)

[**Capítulo III: Requirements Specification
36**](#capítulo-iii-requirements-specification)

> [3.1. To-Be Scenario Mapping 36](#to-be-scenario-mapping)
>
> [3.2. User Stories 37](#user-stories)
>
> [3.3. Impact Mapping 39](#impact-mapping)
>
> [3.4. Product Backlog 39](#product-backlog)

[**Capítulo IV: Strategic-Level Software Design
42**](#capítulo-iv-strategic-level-software-design)

> [4.1. Strategic-Level Attribute-Driven Design
> 42](#strategic-level-attribute-driven-design)
>
> [4.1.1. Design Purpose 42](#design-purpose)
>
> [4.1.2. Attribute-Driven Design Inputs
> 43](#attribute-driven-design-inputs)
>
> [4.1.2.1. Primary Functionality (Primary User Stories)
> 43](#primary-functionality-primary-user-stories)
>
> [4.1.2.2. Quality attribute Scenarios
> 45](#quality-attribute-scenarios)
>
> [4.1.2.3. Constraints 47](#constraints)
>
> [4.1.3. Architectural Drivers Backlog
> 49](#architectural-drivers-backlog)
>
> [4.1.4. Architectural Design Decisions
> 50](#architectural-design-decisions)
>
> [4.1.5. Quality Attribute Scenario Refinements
> 53](#quality-attribute-scenario-refinements)
>
> [4.2. Strategic-Level Domain-Driven Design
> 58](#strategic-level-domain-driven-design)
>
> [4.2.1. EventStorming 58](#eventstorming)
>
> [4.2.2. Candidate Context Discovery 61](#candidate-context-discovery)
>
> [4.2.3. Domain Message Flows Modeling
> 63](#domain-message-flows-modeling)
>
> [4.2.4. Bounded Context Canvases 64](#bounded-context-canvases)
>
> [4.2.5. Context Mapping 67](#context-mapping)
>
> [4.3. Software Architecture 68](#software-architecture)
>
> [4.3.1. Software Architecture System Landscape Diagram
> 68](#software-architecture-system-landscape-diagram)
>
> [4.3.1. Software Architecture Context Level Diagrams
> 70](#software-architecture-context-level-diagrams)
>
> [4.3.2. Software Architecture Container Level Diagrams
> 70](#software-architecture-container-level-diagrams)
>
> [4.3.3. Software Architecture Deployment Diagrams
> 72](#software-architecture-deployment-diagrams)
>
> [Conclusiones 72](#conclusiones)
>
> [Bibliografía 73](#bibliografía)
>
> [Anexos 73](#anexos)

#  

# Student Outcome

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">Criterios específicos</th>
<th style="text-align: left;">Acciones realizadas</th>
<th style="text-align: left;">Conclusiones</th>
</tr>
<tr>
<th style="text-align: left;">Comunica oralmente sus ideas y/o
resultados con objetividad a público de diferentes especialidades y
niveles jerárquicos, en el marco del desarrollo de un proyecto en
ingeniería.</th>
<th style="text-align: left;"><p>Brayan Stiven Gamboa Delgado</p>
<p>TB1:</p>
<p>Se comunicó al equipo que realizar con plazos de tiempos y ayuda
constante en caso de errores.</p>
<p>Jeremy Antonio Loayza</p>
<p>TB1: Se realizó un brainstorming para plantear soluciones a la
problemática, se organizó todo en diagramas y se validó constantemente
con el equipo.</p>
<p>Luis Enrique Aquije Quiroga</p>
<p>TB1: Pude comunicar mis opiniones e ideas de forma clara y concisa en
el trabajo de modo que pueda darme a entender sin ambigüedades.</p>
<p>Jorge Gerardo Quilla Luyo</p>
<p>TB1: Se realizó análisis de historias de usuario para definir drivers
arquitectónicos de nuestra aplicación. También, se realizó event
storming para definir los dominios-</p>
<p>Rony Piero Ticona Luque</p>
<p>TB1: Se realizó funciones como user persona, empathy map y task
matrix. Además, se llevó a cabo una entrevista enfocada en el segmento
empresa.</p></th>
<th style="text-align: left;">Durante el desarrollo del proyecto, se
demostró una comunicación clara y efectiva, adaptada a distintos niveles
y especialidades. El equipo coordinó tareas con plazos definidos,
resolvió errores colaborativamente y utilizó técnicas como
brainstorming, event storming y herramientas centradas en el usuario.
Estas acciones permitieron organizar y validar ideas de forma objetiva,
favoreciendo el entendimiento mutuo y el avance eficiente del
proyecto.</th>
</tr>
<tr>
<th style="text-align: left;">Comunica en forma escrita ideas y/o
resultados con objetividad a público de diferentes especialidades y
niveles jerárquicos, en el marco del desarrollo de un proyecto en
ingeniería.</th>
<th style="text-align: left;"><p>Brayan Stiven Gamboa Delgado</p>
<p>TB1:</p>
<p>En base a lo que pide el proyecto se establecieron definiciones y
límites en el proyecto para realizarlo de forma efectiva.</p>
<p>Jeremy Antonio Loayza</p>
<p>TB1: En base a todo lo recopilado se plantearon las bases del
producto, escalabilidad y requerimientos.</p>
<p>Luis Enrique Aquije Quiroga</p>
<p>TB1: Redacte solo la información y el contenido solicitado para esta
entrega siendo muy breve pero lo suficiente</p>
<p>Jorge Gerardo Quilla Luyo</p>
<p>TB1: Se realizaron escenarios en base a historias de usuario para
definir los principales atributos de calidad. Se realizaron flujos y
conexiones para cada contexto o dominio identificado de nuestra
aplicación.</p>
<p>Rony Piero Ticona Luque</p>
<p>TB1: En base al proyecto se estableció un formato de entrevista para
cada segmento objetivo para identificar las historias de usuario,
empathy map y task matrix.</p></th>
<th style="text-align: left;">Durante el desarrollo del proyecto, se
logró una comunicación clara y objetiva. Se establecieron definiciones,
límites y bases del producto, considerando su escalabilidad y
requerimientos. La redacción fue precisa y enfocada en los contenidos
solicitados, asegurando claridad y concisión. Además, se estructuraron
escenarios, flujos y conexiones a partir de historias de usuario, así
como formatos de entrevista para los segmentos objetivo, lo que permitió
documentar eficazmente los avances del proyecto.</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

#  

# **Capítulo I: Introducción**

## **1.1. Startup Profile**

### **1.1.1. Descripción de la Startup**

SkillLedger es una plataforma web que moderniza la forma en que las
empresas reconocen y premian a sus trabajadores, usando la tecnología
blockchain para asegurar transparencia y trazabilidad en cada logro.

Cada vez que una persona cumple objetivos, desarrolla nuevas habilidades
o demuestra actitudes alineadas con los valores de la empresa, puede
ganar monedas digitales. Estas monedas se canjean fácilmente por *ítems*
del catálogo interno: desde días libres y productos hasta experiencias o
reconocimientos especiales.

Todo el sistema funciona con contratos inteligentes, lo que automatiza
el proceso de forma segura. Además, incorporamos elementos de
gamificación y analítica para mejorar la participación y fortalecer la
cultura de reconocimiento en la organización.

Con SkillLedger, las empresas pueden crear un entorno donde se valora el
esfuerzo, se refuerzan los buenos hábitos y se construye una conexión
más fuerte entre trabajadores y compañía.

**Visión:  
**Diseñar una plataforma web accesible y efectiva que permita a las
empresas reconocer el esfuerzo de sus colaboradores mediante el registro
de logros, la entrega de recompensas y la gamificación del
reconocimiento, promoviendo así la motivación, el desarrollo profesional
y la retención del talento.

**Misión:  
**Transformar la forma en que las organizaciones valoran y fortalecen a
su talento, a través de una solución digital transparente, automatizada
y centrada en el crecimiento continuo, el reconocimiento significativo y
el compromiso sostenible.

**1.1.2. Perfiles de integrantes del equipo**

<img src="./media/image36.jpg"
style="width:6.26772in;height:3.52778in" /><img src="./media/image47.jpg"
style="width:6.26772in;height:3.52778in" /><img src="./media/image48.jpg"
style="width:6.26772in;height:3.52778in" /><img src="./media/image46.jpg"
style="width:6.26772in;height:3.52778in" /><img src="./media/image42.jpg"
style="width:6.26772in;height:3.52778in" />  
**1.2. Solution Profile**

Nuestra solución frente a la problemática de la pérdida de talento, la
falta de motivación, la alta rotación de personal y el escaso impulso al
aprendizaje autónomo en las organizaciones, la solución será el
desarrollo de una plataforma web llamada **SkillLedger**, que promueve
una cultura de reconocimiento constante, transparente y automatizada,
usando tecnología blockchain y smart contracts.

### **1.2.1 Antecedentes y problemática**

**What? – ¿Qué?  
¿Cuál es el problema?  
**Muchas empresas pierden talento valioso por no contar con un sistema
claro para reconocer logros o fomentar el aprendizaje. A esto se suma la
falta de motivación entre los trabajadores y la ausencia de incentivos
que impulsen a ser autodidactas.

**When? – ¿Cuándo?  
¿Cuándo ocurre el problema?  
**Este problema aparece todos los días: cuando el trabajador se
esfuerza, cumple objetivos o aprende por su cuenta, pero no recibe
ningún tipo de reconocimiento. Esto afecta el ánimo, el compromiso y la
permanencia del colaborador en la empresa.

**Where? – ¿Dónde?  
¿Dónde se tomarán las medidas?  
**La plataforma se implementará en empresas de Lima Metropolitana,
aunque está pensada para escalar a nivel nacional. Es útil para
cualquier organización que quiera fortalecer su cultura interna y
mejorar cómo retiene y motiva a su equipo.

**Who? – ¿Quién?  
¿Quién lo usará? ¿Quién es el cliente de este producto?  
**El principal usuario será el trabajador, que podrá acumular logros y
canjearlos por recompensas. El cliente directo serán las áreas de
Recursos Humanos o las gerencias que estén buscando nuevas formas de
mejorar el clima laboral y el rendimiento de sus equipos.

**Why? – ¿Por qué?  
¿Por qué es necesario resolver esto?  
**Porque cuando el esfuerzo no se reconoce, las personas pierden el
interés y/o se desmotivan por ende buscan mejores oportunidades que sí
reconozcan su valor. Un sistema claro de reconocimiento ayuda a retener
talento y mantener a los equipos motivados.

**How? – ¿Cómo?  
¿Cómo se resolverá el problema?  
**Con SkillLedger, los logros de cada colaborador se registran y
recompensan automáticamente. Al completar objetivos, aprender nuevas
cosas o actuar según los valores de la empresa, ganan **monedas
digitales** que se canjean por beneficios del catálogo de la empresa.
Todo se gestiona con **smart contracts**, y el sistema incluye
gamificación y analítica para mantener el interés y facilitar la
gestión.

**How much? – ¿Cuánto?  
¿Cuánto costará resolver el problema?  
**El desarrollo e implementación de SkillLedger requiere una inversión
inicial en tecnología y diseño. El modelo se sostendrá con planes
mensuales para empresas interesadas. A futuro, se espera que la
plataforma crezca gracias a su impacto real en retención y clima
laboral.

**¿A cuántas personas beneficiará?  
**En una primera fase, beneficiará a trabajadores de empresas medianas
en Lima. Según la acogida se planea escalar y llegar a miles de
trabajadores en diferentes sectores.

### **1.2.2 Lean UX Process**

**1.2.2.1. Lean UX Problem Statements**

**Problem Statement:  
**En SkillLedger entendemos que muchas empresas pierden talento valioso
por no contar con un sistema claro y constante de reconocimiento, lo que
a su vez desmotiva a los trabajadores y desalienta el aprendizaje
autodidacta.

**Problema:  
**Hoy en día, muchas organizaciones dependen de métodos informales o
poco consistentes para reconocer los logros de sus trabajadores. Esto
genera desinterés, baja motivación y fuga de talento, especialmente en
equipos donde no se valora el constante esfuerzo ni el crecimiento
personal.

**Impacto:  
**La falta de reconocimiento impacta directamente en el clima laboral,
disminuye el compromiso de los equipos y limita el desarrollo continuo.
Además, obliga a las empresas a invertir más en procesos de reemplazo y
capacitación por alta rotación de personal

**1.2.2.2. Lean UX Assumptions**

**Business Assumptions:**

- Las empresas enfrentan una necesidad creciente de contar con
  soluciones más dinámicas, automatizadas y efectivas para reconocer los
  logros de sus trabajadores.

- Esta necesidad puede resolverse mediante una plataforma digital que
  permita registrar metas cumplidas, recompensar de forma personalizada
  y visualizar el desempeño de manera clara y motivadora.

- Nuestros clientes objetivo son las áreas de Recursos Humanos, así como
  líderes de equipos en empresas medianas y grandes, interesadas en
  fortalecer el compromiso y reducir la rotación de talento.

- El principal valor que ofreceremos será un sistema de reconocimiento
  transparente, constante y alineado con los valores corporativos, que
  impacte positivamente en el clima laboral.

- El modelo de ingresos estará basado en suscripciones mensuales,
  ajustadas a la cantidad de usuarios y el nivel de personalización
  requerido.

- Nuestra competencia directa incluye sistemas internos tradicionales y
  soluciones genéricas de gestión de recursos humanos que no están
  diseñadas específicamente para el reconocimiento de trabajadores.

- SkillLedger se diferenciará por ser una plataforma intuitiva, fácil de
  implementar, con experiencia de usuario amigable y respaldada por
  tecnología blockchain y smart contracts para asegurar trazabilidad y
  confianza..

- Para mitigar ese riesgo, nos enfocaremos en mostrar resultados
  tangibles de mejora en la motivación, retención y participación del
  talento, además de ofrecer funcionalidades visuales atractivas y
  personalizables que reflejen la cultura de cada empresa.

**User Assumptions:**

- ¿Quién es el usuario?  
  Trabajadores que buscan reconocimiento justo por su desempeño y áreas
  de RR.HH. de empresas medianas-grandes que requieren una herramienta
  para identificar logros y seguir el desarrollo personal de su equipo.

- ¿Qué problema tiene nuestro producto que queremos resolver?  
  El poco reconocimiento al esfuerzo de los trabajadores, la fuga de
  talento y la falta de herramientas que promuevan el autodesarrollo
  dentro de las empresas.

- ¿Qué características son importantes?  
  Recompensas canjeables, claridad en los criterios de reconocimiento,
  visualización de logros y gamificación.

- ¿Dónde encaja nuestro producto en su trabajo o vida?  
  En el día a día laboral, como parte del sistema de gestión del
  desempeño y bienestar interno.

- ¿Cuándo y cómo es usado nuestro producto?  
  Al cumplir objetivos, completar retos, adquirir habilidades y ser
  reconocido por los líderes. Usado desde la aplicación web.

- ¿Cómo debe verse y comportarse nuestro producto?  
  Con un diseño intuitivo, accesible, visualmente agradable, que cargue
  rápido, sea fácil de usar y que refuerce positivamente las acciones
  del usuario.

**Feature Assumptions:**

1.  **Recompensas canjeables con catálogo personalizado  
    **

    - *Hipótesis:* Creemos que un catálogo con beneficios reales y
      personalizables incentivará el compromiso y mejorará la motivación
      de los trabajadores.

    - *Experimento:* Probar dos versiones de catálogo (genérico vs.
      personalizado) y medir la tasa de canje y satisfacción percibida
      por los trabajadores.

2.  **Sistema de logros y gamificación  
    **

    - *Hipótesis:* Creemos que mostrar niveles, medallas y progreso
      motivará a los usuarios a participar más.

    - *Experimento:* Medir el impacto del sistema de logros en el tiempo
      de uso, la frecuencia de interacción y la percepción de motivación
      a través de encuestas.

3.  **Dashboard de desempeño visible para trabajadores y líderes  
    **

    - *Hipótesis:* Creemos que visualizar el progreso individual y de
      equipo aumentará la transparencia y sentido de avance.

    - *Experimento:* Implementar dashboards simples y medir percepción
      de utilidad mediante encuestas post-uso.

4.  **Reconocimiento entre pares  
    **

    - *Hipótesis:* Creemos que permitir que los trabajadores se
      reconozcan entre sí refuerza la cultura de equipo.

    - *Experimento:* Activar esta función y monitorear la cantidad de
      reconocimientos generados por mes.

**1.2.2.3. Lean UX Hypothesis Statements**

**Hypothesis Statement 01:  
**Creemos que SkillLedger será el canal principal de reconocimiento
dentro de las empresas.  
**Sabremos que hemos tenido éxito cuando:  
**Al menos el 40% de los reconocimientos mensuales sean realizados a
través de la plataforma durante tres meses, reflejando una buena acogida
por parte de los equipos.

**Hypothesis Statement 02:  
**Creemos que el sistema de recompensas canjeables mejorará la
motivación y retención.  
**Sabremos que hemos tenido éxito cuando:  
**El 70% de los trabajadores activos canjeen recompensas al menos una
vez por trimestre y reporten mayor satisfacción laboral.

**Hypothesis Statement 03:  
**Creemos que la gamificación aumentará la participación en actividades
de desarrollo y cumplimiento de metas.  
**Sabremos que hemos tenido éxito cuando:  
**Más del 50% de los usuarios completen retos internos o acumulen
insignias dentro del primer mes de uso.

**Hypothesis Statement 04:  
**Creemos que los líderes encontrarán útil el dashboard para tomar
decisiones sobre su equipo.  
**Sabremos que hemos tenido éxito cuando:  
**El 80% de los líderes que accedan al dashboard lo usen frecuentemente
y lo califiquen como herramienta valiosa en encuestas internas.

**1.2.2.4. Lean UX Canvas**

<img src="./media/image37.png"
style="width:6.26772in;height:3.23611in" />

## **1.3. Segmentos objetivos**

**Segmento Empresas:**

Organizaciones que buscan mejorar la gestión del talento a través de
herramientas que les permitan reconocer, motivar y fidelizar a sus
trabajadores de manera eficiente y estructurada. La implementación y uso
de estas soluciones está a cargo, principalmente, del área de Recursos
Humanos, la cual busca facilitar la toma de decisiones basada en datos y
promover una cultura de reconocimiento y desarrollo continuo dentro de
la empresa.

**Segmento Empleados:**

Trabajadores que valoran el reconocimiento por su esfuerzo, desean hacer
visible su crecimiento profesional y acceder a incentivos que refuercen
su motivación. Están interesados en contar con medios que les permitan
registrar sus logros, recibir retroalimentación y tener mayor
visibilidad dentro de su entorno laboral.

# **Capítulo II: Requirements Elicitation & Analysis**

## **2.1. Competidores**

### **2.1.1. Análisis competitivo**

<table>
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 19%" />
<col style="width: 17%" />
<col style="width: 17%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr>
<th colspan="6" style="text-align: left;">Competitive Analysis
Landscape</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">¿Por qué llevar a cabo este
análisis?</th>
<th colspan="4" style="text-align: left;">Para conocer el valor que
ofrece cada uno de nuestros competidores en este sector</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Nuestro Producto /
Competidores</th>
<th style="text-align: left;">SkillLedger</th>
<th style="text-align: left;">Opolis</th>
<th style="text-align: left;">BitDegree</th>
<th style="text-align: left;">HiFives</th>
</tr>
<tr>
<th rowspan="2" style="text-align: left;">Perfil</th>
<th style="text-align: left;">Overview</th>
<th style="text-align: left;">Plataforma web que usa blockchain para
ayudar a las empresas a reconocer, recompensar y retener talento.</th>
<th style="text-align: left;">Cooperativa digital para trabajadores
independientes. Ofrece beneficios laborales y control sobre la identidad
y datos laborales.</th>
<th style="text-align: left;">Plataforma educativa blockchain con cursos
en línea, recompensas gamificadas y certificados NFT.</th>
<th style="text-align: left;"><p>Plataforma</p>
<p>que permite a las organizaciones digitalizar, automatizar y
transformar la experiencia de sus empleados mediante programas de
recompensas y reconocimiento. Incorpora inteligencia artificial para
ofrecer insights y gamificación en el proceso de
reconocimiento.</p></th>
</tr>
<tr>
<th style="text-align: left;">Ventaja competitiva ¿Qué valor ofrece a
los clientes?</th>
<th style="text-align: left;"><p>-Sistema gamificado de recompensas
interno personalizado para cada empresa.</p>
<p>-Smart contracts automatizan los acuerdos de aprendizaje y
premios.</p>
<p>-Historial de logros portable y transparente.</p>
<p>-Recompensas alineadas con los valores de la empresa (productos, días
libres, etc).</p></th>
<th style="text-align: left;">-Permite portabilidad de beneficios y
datos laborales entre trabajos. -Incentiva la autonomía laboral.</th>
<th style="text-align: left;"><p>-Recompensas reales (criptomonedas)</p>
<p>- Aprendizaje gamificado y validación pública de habilidades en
blockchain.</p></th>
<th style="text-align: left;"><p>-Integración de IA para análisis y
personalización de reconocimientos</p>
<p>-Plataforma altamente configurable que se adapta a las necesidades
específicas de cada organización</p></th>
</tr>
<tr>
<th rowspan="2" style="text-align: left;">Perfil de marketing</th>
<th style="text-align: left;">Mercado Objetivo</th>
<th style="text-align: left;">Empresas medianas y grandes con enfoque en
innovación en RRHH, bienestar del talento y transformación digital.</th>
<th style="text-align: left;"><p>-Freelancers</p>
<p>-Trabajadores remotos</p></th>
<th style="text-align: left;">Estudiantes, profesionales jóvenes,
aprendices Web3 y empresas tecnológicas</th>
<th style="text-align: left;">Empresas medianas y grandes que buscan
modernizar sus programas de reconocimiento y recompensas</th>
</tr>
<tr>
<th style="text-align: left;">Estrategia de Marketing</th>
<th style="text-align: left;"><p>– Contacto directo con departamentos de
RRHH.</p>
<p>–Participación en ferias de tecnología y Web3.</p></th>
<th style="text-align: left;"><p>-Marketing comunitario (DAO-style)</p>
<p>-Conferencias Web3</p></th>
<th style="text-align: left;">Alianzas con plataformas de educación y
campañas en redes Web3. Participación en hackathons y eventos de cripto
educación.</th>
<th style="text-align: left;">Marketing B2B enfocado en demostrar el
retorno de inversión de los programas de reconocimiento.</th>
</tr>
<tr>
<th rowspan="3" style="text-align: left;">Perfil del producto</th>
<th style="text-align: left;">Productos y servicios</th>
<th style="text-align: left;"><p>-Plataforma web para gestionar
recompensas y logros.</p>
<p>-Marketplace personalizable de recompensas.</p></th>
<th style="text-align: left;"><p>-gestión de identidad profesional</p>
<p>-comunidad de soporte laboral</p></th>
<th style="text-align: left;">Cursos interactivos, recompensas en
tokens, certificados NFT, rutas de aprendizaje personalizadas.</th>
<th style="text-align: left;"><p>-Plataforma web y aplicaciones móviles
para gestión de recompensas y reconocimiento.</p>
<p>-Panel administrativo para recursos humanos.</p></th>
</tr>
<tr>
<th style="text-align: left;">Precios y costos</th>
<th style="text-align: left;">Subscripciones mensuales ajustadas a la
cantidad de trabajadores y el nivel de personalización requerido.</th>
<th style="text-align: left;">Subscripción mensual para miembros. Costos
asociados al uso de servicios administrativos y beneficios.</th>
<th style="text-align: left;">Muchos cursos gratuitos, otros pagos en
tokens.</th>
<th style="text-align: left;">Ofrece demostraciones gratuitas y opciones
de personalización según los requerimientos del cliente.</th>
</tr>
<tr>
<th style="text-align: left;">Canales de distribución</th>
<th style="text-align: left;">Web App (SaaS)</th>
<th style="text-align: left;">-Web (dashboard) -Integración con
wallets</th>
<th style="text-align: left;">Web y plataforma de cursos propia.
Integración con blockchain (wallet)</th>
<th style="text-align: left;">Plataforma web accesible globalmente y
aplicaciones móviles para Android e iOS.</th>
</tr>
<tr>
<th rowspan="4" style="text-align: left;">Análisis SWOT</th>
<th style="text-align: left;">Fortalezas</th>
<th style="text-align: left;"><p>-Historial de logros portable y
confiable</p>
<p>-Incentivos personalizables según cultura empresarial</p></th>
<th style="text-align: left;">-Transparencia -Descentralización
-Portabilidad de identidad profesional</th>
<th style="text-align: left;"><p>-Interfaz gamificada</p>
<p>-comunidad activa</p>
<p>-Certificaciones NFT reconocidas.</p></th>
<th style="text-align: left;"><p>-Plataforma escalable y
personalizable.</p>
<p>-Enfoque en la gamificación y reconocimiento social.</p></th>
</tr>
<tr>
<th style="text-align: left;">Debilidades</th>
<th style="text-align: left;"><p>-Empresas tradicionales podrían dudar
en implementar tecnologías Blockchain.</p>
<p>-Conocimientos necesarios para implementación</p></th>
<th style="text-align: left;">Enfocado principalmente en freelancers, no
en empleados tradicionales.</th>
<th style="text-align: left;"><p>-Foco limitado en el ámbito
educativo</p>
<p>-No incluye incentivos empresariales directos ni conexión con
empresas como empleadores</p></th>
<th style="text-align: left;"><p>-No utiliza tecnología blockchain, lo
que podría limitar la transparencia y portabilidad de los logros.</p>
<p>-Dependencia de integraciones con sistemas existentes.</p></th>
</tr>
<tr>
<th style="text-align: left;">Oportunidades</th>
<th style="text-align: left;"><p>-Creciente interés en bienestar laboral
y retención</p>
<p>-Empresas buscan formas de engagement no salariales</p></th>
<th style="text-align: left;">Aprovechar el crecimiento del trabajo
remoto.</th>
<th style="text-align: left;">-Expandirse a certificaciones corporativas
o integraciones con empresas</th>
<th style="text-align: left;"><p>-Expansión a mercados emergentes que
buscan modernizar sus programas de reconocimiento.</p>
<p>-Incorporación de tecnologías emergentes como blockchain para mejorar
la transparencia y portabilidad de los logros.</p></th>
</tr>
<tr>
<th style="text-align: left;">Amenazas</th>
<th style="text-align: left;"><p>-Competidores grandes podrían
desarrollar soluciones similares</p>
<p>-Rechazo a modelos de gamificación en entornos laborales
tradicionales</p></th>
<th style="text-align: left;">Competencia de plataformas tradicionales
de payroll/beneficios.</th>
<th style="text-align: left;">-Competencia creciente de plataformas
educativas blockchain</th>
<th style="text-align: left;">-Competencia creciente de nuevas
plataformas que integran tecnologías emergentes.</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### **2.1.2. Estrategias y tácticas frente a competidores**

<table>
<colgroup>
<col style="width: 30%" />
<col style="width: 69%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">Competidores</th>
<th style="text-align: left;">¿Qué se puede hacer para ganarle a la
competencia?</th>
</tr>
<tr>
<th style="text-align: left;">Competidor 1:BitDegree</th>
<th style="text-align: left;"><p>Enfocar el producto al sector
empresarial.</p>
<p>Ofrecer recompensas personalizadas internas.</p>
<p>Portabilidad del historial profesional.</p></th>
</tr>
<tr>
<th style="text-align: left;">Competidor 2:Opolis</th>
<th style="text-align: left;"><p>Orientar la solución a empleados
internos.</p>
<p>Usar smart contracts en objetivos y recompensas.</p>
<p>Integración directa con la cultura empresarial.</p></th>
</tr>
<tr>
<th style="text-align: left;">Competidor 3:HiFives</th>
<th style="text-align: left;"><p>Añadir transparencia y trazabilidad con
blockchain.</p>
<p>Logros portables entre empresas.</p>
<p>Crear economía de recompensas personalizada.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## **2.2. Entrevistas**

### **2.2.1. Diseño de entrevistas**

**Segmento Empresa:**

Introducción

Gracias por tu tiempo. Estamos desarrollando una plataforma que permite
a los trabajadores subir evidencias de sus logros, como cursos o
puntualidad, para que las empresas puedan reconocer y recompensar su
esfuerzo. Queremos conocer tu experiencia y tu opinión para construir
una solución que se adapte a las necesidades reales de las empresas.

1.  ¿Nos puede brindar sus nombres, cuál es el nombre de su empresa y a
    qué rubro pertenece?

2.  ¿Cuántos trabajadores tienen actualmente?

3.  ¿Cuál es su cargo dentro de la organización?

4.  ¿La empresa cuenta con un área de Recursos Humanos o Gestión del
    Talento?

5.  Actualmente su empresa utiliza algún tipo de sistema de
    reconocimiento o recompensas para los trabajadores ?

6.  ¿Por qué razones han decidido (o no) implementar un sistema de
    recompensas?

7.  ¿Qué tipos de logros o comportamientos consideran valiosos en sus
    trabajadores ?

8.  ¿Qué formas de recompensa cree que podrían motivar más al personal?

9.  ¿Cómo validan actualmente el desempeño o el desarrollo profesional
    de sus trabajadores ?

10. ¿Qué tan importante consideran el desarrollo profesional continuo de
    sus trabajadores ?

11. ¿Han considerado usar herramientas tecnológicas para facilitar la
    gestión del talento y el reconocimiento?

12. ¿Qué funcionalidades consideran necesarias o útiles en una
    plataforma que les permita visualizar logros y recompensar
    directamente a sus trabajadores?

13. ¿Qué tan dispuestos estarían a invertir en una solución que motive y
    ayude a desarrollar el potencial de sus equipos?

14. ¿Hay algo más que les gustaría compartir sobre cómo gestionan el
    talento o cómo visualizan el futuro del desarrollo profesional
    dentro de su empresa?

**Segmento Trabajador:**

Introducción

Gracias por participar. Estamos desarrollando una plataforma donde
podrás registrar tus logros, como cursos completados o puntualidad, para
que tu empresa pueda ver tu esfuerzo y reconocerlo con recompensas. Tu
opinión nos ayudará a crear una solución útil para ti y tus compañeros.

1.  ¿Nos puede brindar sus nombres y qué cargo desempeñas actualmente?

2.  ¿En qué tipo de empresa trabajas y cuántos años llevas ahí?

3.  ¿Tu empresa tiene un área de Recursos Humanos o algo parecido?

4.  ¿Has recibido alguna vez una recompensa o reconocimiento por tu
    trabajo o por mejorar tus habilidades?

5.  ¿Qué importancia le das al desarrollo profesional o capacitarte
    constantemente?

6.  ¿Qué tipo de acciones crees que deberían reconocerse en un
    trabajador?(Ej. puntualidad, desempeño, formación, iniciativa, etc.)

7.  ¿Qué tipo de recompensas te motivarían a seguir mejorando como
    profesional?(Económicas, días libres, reconocimiento, vales, etc.)

8.  ¿Cómo sueles demostrarle a tu empresa que estás progresando o
    aprendiendo cosas nuevas?

9.  ¿Has tenido dificultades para que tu esfuerzo o logros sean
    reconocidos dentro de la empresa?

10. ¿Te gustaría que existiera una herramienta donde puedas subir
    certificados, logros o datos sobre tu desempeño para que la empresa
    lo vea directamente?

11. ¿Qué cosas te gustaría que tenga esa herramienta para que sea útil
    para ti?

12. ¿Qué tan dispuesto estarías a usar una plataforma que te ayude a
    recibir recompensas o reconocimientos de manera más clara y directa?

13. ¿Hay algo más que te gustaría compartir sobre cómo se valora el
    esfuerzo en tu trabajo o cómo te gustaría que fuera?

### **2.2.2. Registro de entrevistas**

**Segmento Trabajador**

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">Entrevista 1</th>
<th style="text-align: left;">Jair Velasquez Pizarro</th>
</tr>
<tr>
<th style="text-align: left;">Edad</th>
<th style="text-align: left;">22 años</th>
</tr>
<tr>
<th style="text-align: left;">Distrito</th>
<th style="text-align: left;">Comas</th>
</tr>
<tr>
<th style="text-align: left;"><img src="./media/image35.png"
style="width:2.97917in;height:1.125in" /></th>
<th style="text-align: left;"><p>Jair, un estudiante de séptimo ciclo de
Ingeniería de Software, trabaja y estudia al mismo tiempo. Aunque no ha
recibido recompensas formales en su trabajo actual, valora el
reconocimiento por aspectos como la puntualidad y el cumplimiento de
metas. Considera esencial el desarrollo profesional constante,
complementando su educación con cursos adicionales. Entre las
recompensas que más lo motivarían a seguir mejorando están los aumentos
salariales y los días libres.</p>
<p>A pesar de ser relativamente nuevo en su trabajo, Jair ha tenido la
oportunidad de demostrar sus avances y conocimientos a través de
reuniones con su superior. Aunque no ha tenido grandes logros, ha
recibido comentarios positivos. Está interesado en una aplicación que
permita gestionar y mostrar sus logros dentro de la empresa, lo cual
considera útil tanto para recibir reconocimiento como para mejorar sus
oportunidades laborales.</p></th>
</tr>
<tr>
<th style="text-align: left;">URL de la grabación</th>
<th style="text-align: left;"><a
href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211b197_upc_edu_pe/EeQ1IF9HGQFLtsfzLRhW3ecBTMeL3V_FecqQwp-fSE42mg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&amp;e=k0Yidr"><u>Link
a la entrevista</u></a></th>
</tr>
<tr>
<th style="text-align: left;">Timing</th>
<th style="text-align: left;">00:40 - 4:19</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">Entrevista 2</th>
<th style="text-align: left;">Miguel Angel Ybañez Esquerre</th>
</tr>
<tr>
<th style="text-align: left;">Edad</th>
<th style="text-align: left;">22 años</th>
</tr>
<tr>
<th style="text-align: left;">Distrito</th>
<th style="text-align: left;">Rimac</th>
</tr>
<tr>
<th style="text-align: left;"><img src="./media/image13.png"
style="width:2.97917in;height:1.15278in" /></th>
<th style="text-align: left;"><p>Miguel Ángel, estudiante de Ingeniería
de Software, trabaja y estudia simultáneamente. Ha recibido un pequeño
aumento económico en su trabajo debido a su eficiencia, y considera que
el desarrollo profesional continuo es crucial, especialmente en un campo
tan cambiante como el software. Valora el reconocimiento por iniciativas
y el desempeño eficiente, y le motivarían recompensas como aumentos
salariales y días libres. Además, aplica constantemente sus nuevos
conocimientos en los proyectos en los que trabaja.</p>
<p>Aunque ha enfrentado dificultades para que se reconozcan sus logros,
especialmente al unirse a proyectos ya retrasados, Miguel Ángel cree que
una aplicación para gestionar logros y desempeño podría ayudar a mejorar
las oportunidades dentro de la empresa, como acceder a un nuevo puesto o
aumentar su salario. Está interesado en una plataforma que le permita
mostrar habilidades, logros y certificaciones, y le gustaría usarla para
recibir reconocimientos claros y directos por su trabajo.</p></th>
</tr>
<tr>
<th style="text-align: left;">URL de la grabación</th>
<th style="text-align: left;"><a
href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211b197_upc_edu_pe/EZ1xfeU6w6tDs8AXYhl71iMB-EFpJlacCVHIL63ztkN3Rg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&amp;e=kzZtyH"><u>Link
a la entrevista</u></a></th>
</tr>
<tr>
<th style="text-align: left;">Timing</th>
<th style="text-align: left;">00:37 - 5:29</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

| Entrevista 3 | Mario Eugenio Roncallo Machare |
|----|----|
| Edad | 22 años |
| Distrito | Breña |
| <img src="./media/image29.png" style="width:2.97917in;height:1.66667in" /> | Mario Eugenio Roncallo Machare, practicante pre profesional en una empresa comercializadora de materiales de construcción, valora mucho el desarrollo profesional y considera clave reconocer el desempeño, la iniciativa y las ganas de aprender. Aunque ha recibido un reconocimiento simbólico, señala que a veces su esfuerzo no es visible por ser practicante. Le motivan recompensas económicas, vales o capacitaciones, y suele demostrar su progreso aplicando lo aprendido y proponiendo mejoras. Estaría muy dispuesto a usar una herramienta como SkillLedger, siempre que sea fácil de usar, permita subir certificados, recibir feedback y visibilizar su crecimiento de forma clara. |

**  
Segmento Empresa**

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">Entrevista 1</th>
<th style="text-align: left;">Rosmel Gomez Benancio</th>
</tr>
<tr>
<th style="text-align: left;">Edad</th>
<th style="text-align: left;">22</th>
</tr>
<tr>
<th style="text-align: left;">Distrito</th>
<th style="text-align: left;">Lima</th>
</tr>
<tr>
<th style="text-align: left;"><img src="./media/image31.png"
style="width:2.97917in;height:1.58333in" /></th>
<th style="text-align: left;"><p>Rosmel Gomez Benancio, trabajador del
área de recursos humanos en su empresa. Tienen un programa interno donde
los líderes asignan puntos mensuales que luego podrán canjear por gift
cards para fomentar la cultura de reconocimiento. En su empresa creen
que la mejor forma de motivar a su personal son recompensas en forma de
días libres adicionales, cursos pagados o acceso a conferencias
internacionales.</p>
<p>Consideran utilizar herramientas tecnológicas para facilitar la
gestión del talento y el reconocimiento como SaaS (Software as a
Service). Funcionalidades útiles para visualizar los logros y
recompensar directamente a sus colaboradores son, dashboard en tiempo
real, los catálogos de recompensas y smarts contracts para beneficios.
Se muestra interesado en la inversión de esta iniciativa si demuestra
reducción de rotación y la mejora de productividad.</p></th>
</tr>
<tr>
<th style="text-align: left;">URL de la grabación</th>
<th style="text-align: left;"><a
href="https://youtu.be/JtG7V8uwZuA"><u>Link a la entrevista</u></a></th>
</tr>
<tr>
<th style="text-align: left;">Timing</th>
<th style="text-align: left;">4:51</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">Entrevista 2</th>
<th style="text-align: left;">Alexandra Mariella Cabezas</th>
</tr>
<tr>
<th style="text-align: left;">Edad</th>
<th style="text-align: left;">29 años</th>
</tr>
<tr>
<th style="text-align: left;">Distrito</th>
<th style="text-align: left;">Breña</th>
</tr>
<tr>
<th style="text-align: left;"><img src="./media/image45.png"
style="width:2.97917in;height:0.86111in" /></th>
<th style="text-align: left;"><p>Alexandra Cabezas, Supervisora en el
sector educativo, trabaja en Learning SAC, una empresa que gestiona
matrículas y fomenta el desarrollo profesional de sus trabajadores. Con
más de 200 empleados, la compañía utiliza Moodle para capacitar a su
equipo, centrando los incentivos en la productividad y ofreciendo la
oportunidad de estudiar carreras online sin costo, salvo el título
profesional.</p>
<p>Alexandra considera que el desarrollo profesional continuo es vital,
especialmente en un entorno orientado a ventas educativas, donde la
persuasión y el conocimiento sólido son esenciales. Valora la
puntualidad, el cumplimiento de metas ambiciosas y el progreso constante
como indicadores clave del desempeño. Piensa que una plataforma que
permita a los trabajadores registrar sus logros y certificaciones, y que
visibilice su curva de aprendizaje, podría motivar al equipo y mejorar
su rendimiento.</p>
<p>A pesar de ciertos retos como el ausentismo, la empresa está
interesada en explorar herramientas tecnológicas para gestionar el
talento y recompensar logros de forma más efectiva. Alexandra ve estas
soluciones como una oportunidad para fortalecer tanto el desempeño
individual como colectivo, y para consolidar el compromiso hacia el
aprendizaje continuo y la excelencia operativa.</p></th>
</tr>
<tr>
<th style="text-align: left;">URL de la grabación</th>
<th style="text-align: left;"><a
href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u201420422_upc_edu_pe/ER8S-jzjq89Cuwo3GHRfVbwBA_95_OidWtqzMGT5k6Qi0Q?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&amp;e=1ARCmV"><u>Link
a la entrevista</u></a></th>
</tr>
<tr>
<th style="text-align: left;">Timing</th>
<th style="text-align: left;">12:53</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### **2.2.3. Análisis de entrevistas**

- **Segmento Trabajador:**

Jair, Miguel Ángel y Mario valoran el desarrollo profesional constante y
consideran fundamental el reconocimiento por su desempeño. Las
recompensas más motivadoras para ellos incluyen aumentos salariales,
días libres y beneficios como vales o capacitaciones. Aunque han
recibido algunos reconocimientos, enfrentan dificultades para que su
esfuerzo sea visibilizado de forma adecuada.

Todos muestran interés en una plataforma como SkillLedger para gestionar
logros, certificaciones y recibir feedback. Subrayan la importancia de
que la herramienta sea intuitiva, promueva el reconocimiento directo y
facilite mejores oportunidades laborales dentro de sus empresas.

Datos estadísticos de las entrevistas

<img src="./media/image10.png"
style="width:6.26772in;height:3.76389in" />

- **Segmento Empresa:**

Alexandra y Rosmel trabajan en empresas que valoran el desarrollo
profesional y el reconocimiento del desempeño como pilares fundamentales
para motivar a sus equipos. Ambas organizaciones cuentan con programas
de incentivos: una utiliza plataformas como Moodle y carreras online,
mientras que la otra implementa sistemas de puntos canjeables por
recompensas.

Coinciden en que herramientas tecnológicas, como plataformas para
registrar logros y ofrecer recompensas mediante dashboards o catálogos,
podrían optimizar la gestión del talento. Ven estas soluciones como
oportunidades para fortalecer la motivación, reducir la rotación de
personal y mejorar la productividad organizacional.

Datos estadísticos de las entrevistas

<img src="./media/image2.png"
style="width:6.26772in;height:3.76389in" />

## **2.3. Needfinding**

### **2.3.1. User Personas**

Los user personas nos ayudan a reunir las características más relevantes
de cada segmento objetivo, representadas a través de una persona
ficticia. En este caso, los datos se obtuvieron a partir de las
entrevistas realizadas en las etapas anteriores.

- Segmento Trabajador

> <img src="./media/image27.png" style="width:4.875in;height:7.07292in" />

- Segmento Empresa

> <img src="./media/image40.png" style="width:5.24479in;height:6.813in" />

### **2.3.2. User Task Matrix**

Los User Task Matrix identifican las tareas que los usuarios realizarán
en la aplicación y, para cada segmento objetivo, especifica la
frecuencia y relevancia asociadas a estas tareas. Esto facilita la
validación de la prioridad de cada funcionalidad dentro de la
aplicación.

<img src="./media/image39.png"
style="width:6.26772in;height:2.90278in" />

### **2.3.3. Empathy Mapping**

Lo siguiente a evaluar como parte del proceso de needfinding en
TalentChain es analizar nuestros segmentos objetivos mediante empathy
mapping. Este enfoque busca profundizar en el entendimiento de nuestros
usuarios para identificar oportunidades de mejora, plantear nuevos
enfoques y definir herramientas adecuadas que respondan a sus
necesidades específicas dentro del ecosistema del proyecto.

- Segmento Trabajador

> <img src="./media/image26.png"
> style="width:6.27083in;height:6.92708in" />

- Segmento Empresa

> <img src="./media/image33.png"
> style="width:6.27083in;height:7.20833in" />

### **2.3.4. As-is Scenario Mapping**

**Segmento Trabajador:**

<img src="./media/image14.png"
style="width:6.26772in;height:3.26389in" />

**Segmento Empresas:**

<img src="./media/image25.png"
style="width:6.26772in;height:3.30556in" />

## **2.4. Ubiquitous Language**

- Blockchain

> Definición: Tecnología de registro distribuido utilizada para
> garantizar la transparencia y trazabilidad de los logros y
> recompensas.

- Contrato Inteligente (Smart Contract)

> Definición: Automatización programable que regula y ejecuta los
> acuerdos dentro de la plataforma, como la asignación de monedas
> digitales al completar logros.

- Gamificación

> Definición: Aplicación de mecánicas de juego, como niveles, medallas y
> retos, para incentivar la participación y el aprendizaje.

- Monedas Digitales

> Definición: Unidades virtuales emitidas como recompensa por logros y
> acciones específicas; pueden canjearse por beneficios en el catálogo.

- Catálogo de Recompensas

> Definición: Lista personalizada de beneficios que los trabajadores
> pueden obtener, incluyendo productos, días libres, experiencias y
> reconocimientos especiales.

- Dashboard de Desempeño

> Definición: Interfaz visual que permite a trabajadores y líderes
> monitorear progreso, logros y métricas clave de rendimiento.

- Reconocimiento entre Pares

> Definición: Función que permite a los trabajadores otorgar
> reconocimientos a sus compañeros, promoviendo una cultura de equipo.

- Logro

> Definición: Resultado obtenido por un colaborador tras cumplir un
> objetivo, adquirir una nueva habilidad o demostrar valores alineados
> con la empresa.

- Retención de Talento

> Definición: Capacidad de una empresa para mantener a sus trabajadores
> a través de motivación, recompensas y una cultura positiva.

- Motivación Laboral

> Definición: Nivel de compromiso y entusiasmo de los trabajadores,
> influido por el reconocimiento constante y significativo.

- Achievement Wallet

> Definición: Un repositorio digital personal donde los trabajadores
> almacenan sus logros, habilidades y recompensas adquiridas, todo
> respaldado por tecnología blockchain.

- Recognition Framework

> Definición: El conjunto de reglas y métricas definidas por la empresa
> para determinar cómo se asignan los logros y recompensas en la
> plataforma.

# **Capítulo III: Requirements Specification**

## **3.1. To-Be Scenario Mapping**

**Segmento Trabajador:**

<img src="./media/image30.png"
style="width:6.26772in;height:3.26389in" />

**Segmento Empresas:**

<img src="./media/image17.png"
style="width:6.26772in;height:3.31944in" />

## **3.2. User Stories**

<table>
<colgroup>
<col style="width: 14%" />
<col style="width: 21%" />
<col style="width: 23%" />
<col style="width: 40%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;">Epic / Story ID</th>
<th style="text-align: center;">Título</th>
<th style="text-align: center;">Descripción</th>
<th style="text-align: center;">Criterio de aceptación</th>
</tr>
<tr>
<th colspan="4">Epic 1: Gestión de Usuarios y Perfiles</th>
</tr>
<tr>
<th>E1-US001</th>
<th>Registro de empleados</th>
<th><strong>Como</strong> administrador, <strong>quiero</strong>
registrar nuevos empleados en la plataforma <strong>para</strong> que
puedan empezar a usar el sistema de recompensas.</th>
<th><p><strong>Escenario N°1:</strong> Administrador registra nuevos
empleados</p>
<p><strong>Dado</strong> que el formulario de registro debe permitir
ingresar datos básicos como nombre, correo, cargo y área.</p>
<p><strong>Entonces</strong> el sistema debe enviar un correo de
bienvenida con instrucciones de acceso.</p>
<p><strong>Y</strong> el nuevo empleado debe aparecer en la lista de
usuarios activos.</p></th>
</tr>
<tr>
<th>E1-US002</th>
<th style="text-align: left;">Completar perfil profesional</th>
<th style="text-align: left;"><strong>Como</strong> empleado,
<strong>quiero</strong> completar mi perfil profesional
<strong>para</strong> que la empresa pueda reconocer mis logros y
formación.</th>
<th style="text-align: left;"><p><strong>Escenario N°1:</strong> El
empleado quiere completar su perfil profesional</p>
<p><strong>Dado que</strong> el usuario debe poder ingresar y actualizar
datos como habilidades, cursos completados y certificaciones.</p>
<p><strong>Cuando</strong> el sistema guarda los cambios
automáticamente.</p>
<p><strong>Entonces</strong> el perfil debe poder visualizarse desde el
panel del administrador.</p></th>
</tr>
<tr>
<th>E1-US003</th>
<th style="text-align: left;">Asignación de roles</th>
<th style="text-align: left;"><strong>Como</strong> administrador,
<strong>quiero</strong> asignar roles a los usuarios
<strong>para</strong> controlar el acceso a las diferentes
funcionalidades de la plataforma.</th>
<th style="text-align: left;"><p><strong>Escenario N°1:</strong> El
administrador quiere asignar roles a los usuarios</p>
<p><strong>Dado que</strong> debe existir al menos dos roles:
"administrador" y "empleado".</p>
<p><strong>Cuando</strong> los administradores modifiquen roles desde el
panel de usuarios.</p>
<p><strong>Entonces</strong> los empleados no podrán acceder a funciones
administrativas.</p></th>
</tr>
<tr>
<th colspan="4">Epic 2: Logros y trayectorias</th>
</tr>
<tr>
<th>E2-US004</th>
<th>Registro de cumplimiento de metas</th>
<th style="text-align: left;"><strong>Como</strong> empleado,
<strong>quiero</strong> registrar el cumplimiento de una meta o
actividad <strong>para</strong> recibir recompensas si corresponde.</th>
<th style="text-align: left;"><p><strong>Escenario 1:</strong> El
empleado quiere registrar el cumplimiento de una meta y recibir
recompensas</p>
<p><strong>Dado que</strong> el usuario puede seleccionar una meta de su
ruta y marcarla como completada.</p>
<p><strong>Entonces</strong> el sistema debe solicitar evidencia
(archivo, enlace o comentario).</p>
<p><strong>Y</strong> el administrador debe validar el cumplimiento
antes de aprobar la recompensa.</p></th>
</tr>
<tr>
<th>E2-US005</th>
<th>Definicion de rutas de desarrollo</th>
<th style="text-align: left;"><strong>Como</strong> administrador,
<strong>quiero</strong> definir rutas de desarrollo o aprendizaje
<strong>para</strong> que los empleados sepan qué logros alcanzar.</th>
<th style="text-align: left;"><p><strong>Escenario N°1:</strong> El
administrador quiere definir el camino a seguir en el desarrollo.</p>
<p><strong>Dado que</strong> el administrador puede crear, editar o
eliminar rutas.</p>
<p><strong>Cuando</strong> cada ruta incluye una serie de metas u
objetivos claros.</p>
<p><strong>Entonces</strong> las rutas pueden ser asignadas a uno o más
empleados.</p></th>
</tr>
<tr>
<th>E2-US006</th>
<th>Visualización de logros</th>
<th style="text-align: left;"><strong>Como</strong> empleado,
<strong>quiero</strong> visualizar mis logros alcanzados y los
pendientes <strong>para</strong> motivarme a avanzar.</th>
<th style="text-align: left;"><p><strong>Escenario N°1:</strong> El
empleado desea ver sus logros y pendientes</p>
<p><strong>Dado que</strong> el usuario puede ver un panel con sus
logros completados y los que tiene en progreso.</p>
<p><strong>Entonces</strong> cada logro debe mostrar su descripción,
estado, y fecha de validación.</p>
<p><strong>Y</strong> el panel debe actualizarse automáticamente tras la
validación de un logro.</p></th>
</tr>
<tr>
<th colspan="4">Epic 3: Integración con blockchain y smart
contracts</th>
</tr>
<tr>
<th>E3-US007</th>
<th>Registro de logros en blockchain</th>
<th style="text-align: left;"><strong>Como</strong> sistema,
<strong>quiero</strong> registrar los logros validados en la blockchain
<strong>para</strong> garantizar transparencia e inmutabilidad.</th>
<th style="text-align: left;"><p><strong>Escenario N°1:</strong> El
sistema debe poder registrar en la blockchain exitosamente.</p>
<p><strong>Dado que</strong> cada logro validado debe generar una
transacción en la blockchain.</p>
<p><strong>Y</strong> el registro incluye información del empleado, tipo
de logro y fecha.</p>
<p><strong>Entonces</strong> los datos serán visibles desde un visor de
logros con trazabilidad blockchain.</p></th>
</tr>
<tr>
<th>E3-US008</th>
<th>Automatización con smart contracts</th>
<th style="text-align: left;"><strong>Como</strong> administrador,
<strong>quiero</strong> establecer reglas en smart contracts
<strong>para</strong> automatizar la entrega de recompensas.</th>
<th style="text-align: left;"><p><strong>Escenario N°1:</strong> El
administrador quiere establecer ciertas normas en los contratos
inteligentes.</p>
<p><strong>Dado que</strong> el administrador puede definir condiciones
específicas (por ejemplo: “si completa la ruta A, recibe 100
tokens”).</p>
<p><strong>Cuando</strong> el sistema deba desplegar automáticamente un
smart contract con esas reglas.</p>
<p><strong>Entonces</strong> la recompensa se otorga sin intervención
manual.</p></th>
</tr>
<tr>
<th>E3-US009</th>
<th>Consulta de trazabilidad de logros</th>
<th style="text-align: left;"><strong>Como</strong> empleado,
<strong>quiero</strong> consultar la trazabilidad de mis logros en la
blockchain <strong>para</strong> asegurar su autenticidad.</th>
<th style="text-align: left;"><p><strong>Escenario N°1:</strong> Ya que
el empleado quiere consultar la trazabilidad de sus logros en la
blockchain.</p>
<p><strong>Dado que</strong> el usuario puede acceder a un historial de
logros registrado en la blockchain.</p>
<p><strong>Entonces</strong> debe mostrarse un enlace o hash verificable
para cada registro.</p>
<p><strong>Y</strong> la interfaz debe ser clara y comprensible incluso
para usuarios sin experiencia técnica.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## **3.3. Impact Mapping**

**Segmento Trabajador**

<img src="./media/image44.png"
style="width:6.26772in;height:4.56944in" />

**Segmento Empresa**

<img src="./media/image21.png"
style="width:6.26772in;height:4.76389in" />

## **3.4. Product Backlog**

| **\#Orden** | **User Story ID** | **Título** | **Descripción** | **Story Points** |
|----|----|----|----|----|
| 1 | HU001 | Registro de empleados | **Como** administrador, **quiero** registrar nuevos empleados en la plataforma **para** que puedan empezar a usar el sistema de recompensas. | 5 |
| 2 | HU002 | Completar perfil profesional | **Como** empleado, **quiero** completar mi perfil profesional **para** que la empresa pueda reconocer mis logros y formación. | 3 |
| 3 | HU003 | Asignación de roles | **Como** administrador, **quiero** asignar roles a los usuarios **para** controlar el acceso a las diferentes funcionalidades de la plataforma. | 5 |
| 4 | HU004 | Registro de cumplimiento de metas | **Como** empleado, **quiero** registrar el cumplimiento de una meta o actividad **para** recibir recompensas si corresponde. | 5 |
| 5 | HU005 | Definición de rutas de desarrollo | **Como** administrador, **quiero** definir rutas de desarrollo o aprendizaje **para** que los empleados sepan qué logros alcanzar. | 5 |
| 6 | HU006 | Visualización de logros | **Como** empleado, **quiero** visualizar mis logros alcanzados y los pendientes **para** motivarme a avanzar. | 8 |
| 7 | HU007 | Registro de logros en blockchain | **Como** sistema, **quiero** registrar los logros validados en la blockchain **para** garantizar transparencia e inmutabilidad. |  |
| 8 | HU008 | Automatización con smart contracts | **Como** administrador, **quiero** establecer reglas en smart contracts **para** automatizar la entrega de recompensas. | 8 |
| 9 | HU009 | Consulta de trazabilidad de logros | **Como** empleado, **quiero** consultar la trazabilidad de mis logros en la blockchain **para** asegurar su autenticidad. | 5 |

#  

# **Capítulo IV: Strategic-Level Software Design**

## **4.1. Strategic-Level Attribute-Driven Design**

En esta sección, se describe el proceso de diseño arquitectónico basado
en atributos de calidad que hemos identificado de acuerdo a la solución
propuesta, estos deben garantizar transparencia, seguridad,
escalabilidad, entre otros, dentro de nuestra aplicación.

### **4.1.1. Design Purpose**

La aplicación web propuesta aborda una problemática centrada en el
reconocimiento y retención del talento mediante un sistema gamificado
basado en blockchain. A partir del análisis funcional, se han
identificado diversos requerimientos agrupados en épicas, lo que ha
permitido definir con claridad los módulos del sistema.

Para el desarrollo del backend, se ha optado por una arquitectura de
microservicios, dado que la solución involucra dominios funcionales
complejos y bien delimitados, como el sistema de logros y recompensas,
la gestión de usuarios, el catálogo de incentivos, y la integración con
blockchain mediante smart contracts. Esta separación por dominios no
solo favorece la escalabilidad y mantenibilidad, sino que también
permite que los equipos de desarrollo trabajen de manera independiente,
reduciendo el acoplamiento entre frontend y backend.

Además, se está tomando en cuenta la interacción con servicios externos,
lo cual exige una arquitectura resiliente ante posibles fallos o
latencias en esos sistemas. En consecuencia, cada microservicio deberá
cumplir con sus respectivas reglas de negocio, establecer mecanismos de
comunicación adecuados (como APIs REST o eventos), y garantizar los
atributos de calidad requeridos mediante el uso de herramientas,
patrones y buenas prácticas arquitectónicas.

### **4.1.2. Attribute-Driven Design Inputs**

En esta sección, tomaremos decisiones arquitectónicas en base a
elementos recolectados, es decir, nuestras historias de usuario.
Tomaremos en cuenta distintos criterios de calidad, como la
escalabilidad, disponibilidad y rendimiento.

#### **4.1.2.1. Primary Functionality (Primary User Stories)**

A continuación, presentamos historias de usuario que tienen mayor
relevancia y complejidad a nivel de desarrollo. Estas presentan
características que requieren nuestra atención para asegurar su correcto
funcionamiento.

<table>
<colgroup>
<col style="width: 15%" />
<col style="width: 17%" />
<col style="width: 27%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;"><p>Epic /</p>
<p>User Story ID</p></th>
<th style="text-align: left;">Título</th>
<th style="text-align: left;">Descripción</th>
<th style="text-align: left;">Criterios de aceptación</th>
<th style="text-align: left;">Relacionado con (Epic ID)</th>
</tr>
<tr>
<th style="text-align: left;">HU004</th>
<th style="text-align: left;">Registro de cumplimiento de metas</th>
<th style="text-align: left;"><strong>Como</strong> empleado,
<strong>quiero</strong> registrar el cumplimiento de una meta o
actividad <strong>para</strong> recibir recompensas si corresponde</th>
<th style="text-align: left;"><p><strong>Escenario 1:</strong> El
empleado quiere registrar el cumplimiento de una meta y recibir
recompensas</p>
<p><strong>Dado que</strong> el usuario puede seleccionar una meta de su
ruta y marcarla como completada.</p>
<p><strong>Entonces</strong> el sistema debe solicitar evidencia
(archivo, enlace o comentario).</p>
<p><strong>Y</strong> el administrador debe validar el cumplimiento
antes de aprobar la recompensa.</p></th>
<th style="text-align: left;">2</th>
</tr>
<tr>
<th style="text-align: left;">HU007</th>
<th style="text-align: left;">Registro de logros en blockchain</th>
<th style="text-align: left;"><strong>Como</strong> sistema,
<strong>quiero</strong> registrar los logros validados en la blockchain
<strong>para</strong> garantizar transparencia e inmutabilidad.</th>
<th style="text-align: left;"><p><strong>Escenario N°1:</strong> El
sistema debe poder registrar en la blockchain exitosamente.</p>
<p><strong>Dado que</strong> cada logro validado debe generar una
transacción en la blockchain.</p>
<p><strong>Y</strong> el registro incluye información del empleado, tipo
de logro y fecha.</p>
<p><strong>Entonces</strong> los datos serán visibles desde un visor de
logros con trazabilidad blockchain</p></th>
<th style="text-align: left;">3</th>
</tr>
<tr>
<th style="text-align: left;">HU008</th>
<th style="text-align: left;">Automatización con smart contracts</th>
<th style="text-align: left;"><strong>Como</strong> administrador,
<strong>quiero</strong> establecer reglas en smart contracts
<strong>para</strong> automatizar la entrega de recompensas.</th>
<th style="text-align: left;"><p><strong>Escenario N°1:</strong> El
administrador quiere establecer ciertas normas en los contratos
inteligentes.</p>
<p><strong>Dado que</strong> el administrador puede definir condiciones
específicas (por ejemplo: “si completa la ruta A, recibe 100
tokens”).</p>
<p><strong>Cuando</strong> el sistema deba desplegar automáticamente un
smart contract con esas reglas.</p>
<p><strong>Entonces</strong> la recompensa se otorga sin intervención
manual.</p></th>
<th style="text-align: left;">3</th>
</tr>
<tr>
<th style="text-align: left;">HU009</th>
<th style="text-align: left;">Consulta de trazabilidad de logros</th>
<th style="text-align: left;"><strong>Como</strong> empleado,
<strong>quiero</strong> consultar la trazabilidad de mis logros en la
blockchain <strong>para</strong> asegurar su autenticidad.</th>
<th style="text-align: left;"><p><strong>Escenario N°1:</strong> Ya que
el empleado quiere consultar la trazabilidad de sus logros en la
blockchain.</p>
<p><strong>Dado que</strong> el usuario puede acceder a un historial de
logros registrado en la blockchain.</p>
<p><strong>Entonces</strong> debe mostrarse un enlace o hash verificable
para cada registro.</p>
<p><strong>Y</strong> la interfaz debe ser clara y comprensible incluso
para usuarios sin experiencia técnica.</p></th>
<th style="text-align: left;">3</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

#### **4.1.2.2. Quality attribute Scenarios**

Las historias de usuario seleccionadas necesitan, en su mayoría, del uso
de Blockchain y Smart Contracts, los cuales, al ser sistemas externos,
debemos asegurar el correcto acceso a estos y cumplir con la
implementación en nuestra solución. También, tenemos historias de
usuario en donde el módulo de Catálogo de recompensas es imprescindible
para ejecutar los principales beneficios de usar nuestra aplicación para
el usuario empleado.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">Atributo</th>
<th style="text-align: left;">Fuente</th>
<th style="text-align: left;">Estímulo</th>
<th style="text-align: left;">Artefacto</th>
<th style="text-align: left;">Entorno</th>
<th style="text-align: left;">Respuesta</th>
<th style="text-align: left;">Medida</th>
</tr>
<tr>
<th style="text-align: left;">Usabilidad</th>
<th style="text-align: left;">Usuario Empleado</th>
<th style="text-align: left;">Registrar el cumplimiento de un
certificado, meta, objetivos, etc., y recibir una recompensa</th>
<th style="text-align: left;">Apartado de registro de metas, objetivos,
certificados, etc.</th>
<th style="text-align: left;">Aplicación web</th>
<th style="text-align: left;"><p>La interfaz es intuitiva.</p>
<p>El sistema cuenta con una guía para subir evidencia de sus
logros</p></th>
<th style="text-align: left;"><p>Evaluar la eficiencia, es decir que
tanto demora el usuario empleado en subir la evidencia de sus
logros.</p>
<p>El usuario registra sus logros y sube su evidencia en menos de 90
segundos.</p></th>
</tr>
<tr>
<th colspan="7" style="text-align: left;">Scenario: Registro eficiente
de cumplimiento de metas</th>
</tr>
<tr>
<th style="text-align: left;">Confiabilidad</th>
<th style="text-align: left;">Sistema</th>
<th style="text-align: left;">Validación de la meta, objetivos,
certificado de un empleado</th>
<th style="text-align: left;">Smart Contract desplegado</th>
<th style="text-align: left;">Conexión activa con el sistema de
blockchain</th>
<th style="text-align: left;">Transacción es guardada en la cadena de
bloques y se vuelve inmutable</th>
<th style="text-align: left;"><p>El 100% de los certificados, metas,
logros, etc. son veraces.</p>
<p>La confirmación de la transacción se realiza en menos de 5
segundos</p></th>
</tr>
<tr>
<th colspan="7" style="text-align: left;">Scenario: Transacción de
puntos es confiable y trazable</th>
</tr>
<tr>
<th style="text-align: left;">Seguridad</th>
<th style="text-align: left;">Usuario no autorizado o atacante</th>
<th style="text-align: left;">Intento registrar metas, certificados,
etc. sin que haya sido validado por el sistema</th>
<th style="text-align: left;">Validación y registro en blockchain</th>
<th style="text-align: left;">Operación manual por el usuario
Empresa</th>
<th style="text-align: left;">Bloqueo del registro y transacción
detenida.</th>
<th style="text-align: left;">El 100% de las evidencias son registradas
y han sido validadas de manera oficial.</th>
</tr>
<tr>
<th colspan="7" style="text-align: left;">Scenario: Prevención de
certificados o evidencias fraudulentas en blockchain</th>
</tr>
<tr>
<th style="text-align: left;">Modificabilidad</th>
<th style="text-align: left;">Usuario Empresa (Administrador)</th>
<th style="text-align: left;">Definir reglas y condiciones para ejecutar
la transacción de un Smart Contract</th>
<th style="text-align: left;">Módulo de creación de Smart Contract</th>
<th style="text-align: left;">Usuario empresa con los permisos
necesarios para la creación de contratos</th>
<th style="text-align: left;">El sistema permite definir las reglas o
condiciones del contrato sin afectar el funcionamiento de otros
módulos</th>
<th style="text-align: left;">El proceso de creación de Smart Contracts
debe estar 100% libre de errores tras realizar esa operación</th>
</tr>
<tr>
<th colspan="7" style="text-align: left;">Scenario: Modificabilidad en
la definición de reglas de Smart Contract</th>
</tr>
<tr>
<th style="text-align: left;">Seguridad</th>
<th style="text-align: left;">Usuario no autorizado</th>
<th style="text-align: left;">Intenta crear un smart contract</th>
<th style="text-align: left;">Módulo de creación de Smart Contract</th>
<th style="text-align: left;">Acceso restringido a usuarios sin
credenciales de administrador</th>
<th style="text-align: left;">El sistema bloquea el intento no
autorizado de creación de contratos</th>
<th style="text-align: left;">El 100% de los intentos deben ser
bloqueados.</th>
</tr>
<tr>
<th colspan="7" style="text-align: left;">Scenario: Creación segura de
Smart Contracts</th>
</tr>
<tr>
<th style="text-align: left;">Usabilidad</th>
<th style="text-align: left;">Empleado</th>
<th style="text-align: left;">Verificar la trazabilidad de sus logros en
los registros del blockchain</th>
<th style="text-align: left;">Historial de transacciones, filtrado por
el usuario correspondiente</th>
<th style="text-align: left;">Consulta de registros</th>
<th style="text-align: left;">Historial de transacciones con un enlace
verificables a cada registro</th>
<th style="text-align: left;"><p>Tasa de éxito de consulta mayor a
90%.</p>
<p>Satisfacción del cliente indicando claridad y facilidad de
uso.</p></th>
</tr>
<tr>
<th colspan="7" style="text-align: left;">Scenario: Consulta de
transacciones clara y verificable</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

#### **4.1.2.3. Constraints**

En esta sección vamos definir restricciones, las cuales nos ayudarán a
identificar y minimizar riesgos, costos, etc. Entre las principales
restricciones tenemos:

- El contexto Blockchain debe asegurar rendimiento ante la demanda de
  creación de contratos

- Los empleados autorizados pueden visualizar el historial de sus logros

- Visualización en tiempo real de las transacciones

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">Technical Story ID</th>
<th style="text-align: left;">Título</th>
<th style="text-align: left;">Descripción</th>
<th style="text-align: left;">Criterios de aceptación</th>
<th style="text-align: left;">Relacionado con (Epic ID)</th>
</tr>
<tr>
<th style="text-align: left;">TS001</th>
<th style="text-align: left;">Capacidad de la red blockchain</th>
<th style="text-align: left;">La red blockchain debe poder manejar de
manera eficiente las transacciones de logros, sin afectación del
rendimiento general.</th>
<th style="text-align: left;"><p>- La red debe soportar al menos 1,000
transacciones simultáneas.</p>
<p>- El tiempo de respuesta de transacciones no debe superar los 3
segundos.</p></th>
<th style="text-align: left;">3</th>
</tr>
<tr>
<th style="text-align: left;">TS002</th>
<th style="text-align: left;">Autenticación y control de acceso</th>
<th style="text-align: left;">Solo los empleados autenticados deben
tener acceso a su trazabilidad de logros.</th>
<th style="text-align: left;"><p>- Todos los empleados deben
autenticarse antes de consultar su historial.</p>
<p>- Los permisos deben ser verificados antes de permitir el
acceso.</p></th>
<th style="text-align: left;">1</th>
</tr>
<tr>
<th style="text-align: left;">TS003</th>
<th style="text-align: left;">Tiempo de validación de logros</th>
<th style="text-align: left;">El sistema debe validar rápidamente los
logros para asegurar recompensas oportunas.</th>
<th style="text-align: left;"><p>- El tiempo de validación no debe
exceder los 5 segundos.</p>
<p>- El sistema debe confirmar el cumplimiento antes de aprobar la
recompensa.</p></th>
<th style="text-align: left;">2</th>
</tr>
<tr>
<th style="text-align: left;">TS004</th>
<th style="text-align: left;">Escalabilidad del sistema</th>
<th style="text-align: left;">El sistema debe ser capaz de manejar un
creciente número de contratos inteligentes sin afectar el
rendimiento.</th>
<th style="text-align: left;">- El sistema debe ser capaz de manejar al
menos 1,000 contratos inteligentes por minuto sin degradación del
rendimiento.</th>
<th style="text-align: left;">3</th>
</tr>
<tr>
<th style="text-align: left;">TS005</th>
<th style="text-align: left;">Monitoreo en tiempo real de la
blockchain</th>
<th style="text-align: left;">El sistema debe permitir la visualización
en tiempo real de los logros registrados en la blockchain.</th>
<th style="text-align: left;"><p>- La interfaz de monitoreo debe mostrar
los logros en tiempo real con un retraso máximo de 5 segundos.</p>
<p>- Los logros deben ser accesibles desde la interfaz de consulta en
todo momento.</p></th>
<th style="text-align: left;">3</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### **4.1.3. Architectural Drivers Backlog**

| Driver ID | Título de Driver | Descripción | Importancia para Stakeholders (High, Medium, Low) | Impacto en Architecture Technical Complexity (High, Medium, Low) |
|----|----|----|----|----|
| 1 | Registro inmutable y confiable en Blockchain | Las transacciones deben registrarse de forma confiable y verificable en blockchain para asegurar su autenticidad | High | High |
| 2 | Prevención de registros fraudulentos | El sistema debe evitar que usuarios no autorizados registren metas o logros sin validación previa. | High | Medium |
| 3 | Modificabilidad de reglas en smart contracts | El sistema debe permitir definir y actualizar reglas o condiciones para smart contracts sin afectar otras funciones | Medium | High |
| 4 | Seguridad en creación de smart contracts | Solo usuarios autorizados pueden crear o modificar contratos inteligentes | High | Medium |
| 5 | Interfaz intuitiva para subir y evidenciar logros | La interfaz de registro debe ser clara y eficiente para que los empleados suban evidencia de logros facilmente | High | Medium |
| 6 | Consulta clara y verificable de transacciones | Los empleados deben poder ver las transacciones en el apartado correspondiente | High | Medium |
| 7 | Rendimiento de la red Blockchain | La red blockchain debe soportar una alta demanda de transacciones sin afectar el rendimiento del sistema | High | High |
| 8 | Escalabilidad del sistema | El sistema debe escalar a medida que aumente el número de usuarios, logros y contratos registrados. | High | High |
| 9 | Visualización en tiempo real de transacciones | Los usuarios deben ver las transacciones en la red blockchain de inmediato | High | High |

### **4.1.4. Architectural Design Decisions**

| Driver ID | Título de Driver | Pattern 1: Blockchain pública |  | Pattern 2: Blockchain privada |  | Pattern 3: Blockchain híbrida |  |
|----|----|----|----|----|----|----|----|
|  |  | Pro | Con | Pro | Con | Pro | Con |
| 1 | Registro inmutable y confiable en Blockchain | Alta transparencia e inmutabilidad garantizada por una red descentralizada | Costos por transacción (gas fees) y menor control sobre la red | Mayor control sobre los datos y sin tarifas por transacción. | Confianza limitada fuera de la organización, menos descentralizada. | Combina trazabilidad pública con control privado y rendimiento. | Mayor complejidad técnica en sincronización y gestión de nodos. |
| 7 | Rendimiento de la red Blockchain | Infraestructura robusta y probada a escala global. | Latencias variables y saturación de red en horas pico. | Alta velocidad de transacción y bajo tiempo de respuesta. | Escala limitada a la infraestructura local o de la empresa. | Permite optimizar el rendimiento en red privada con respaldo público. | Requiere lógica adicional de sincronización y validación cruzada. |
| 9 | Visualización en tiempo real de transacciones | Herramientas ya existentes como exploradores (etherscan, polygonscan). | Dependencia de nodos externos o APIs públicas, posibles demoras. | Control total de los eventos y visualización interna en tiempo real. | Se necesita construir desde cero la interfaz de consulta. | Puedes tener visualización interna rápida y pruebas de integridad pública. | La sincronización entre capas puede generar inconsistencias temporales. |

| Driver ID | Título de Driver | Pattern 1: Validación de roles y lógica en el backend |  | Pattern 2: Validación embebida en Smart Contracts |  | Pattern 3: Autenticación externa (OAuth2 + JWT) |  |
|----|----|----|----|----|----|----|----|
|  |  | Pro | Con | Pro | Con | Pro | Con |
| 2 | Prevención de registros fraudulentos | Permite lógica flexible, actualizable sin redeploy. | Si el backend es comprometido, la seguridad se ve afectada. | Regla inmutable directamente en la blockchain, imposible de eludir. | Difícil de modificar; requiere redeploy si cambia la lógica. | Seguridad escalable y estándar de la industria. | Requiere gestión robusta de tokens y expiración; agrega complejidad externa. |
| 4 | Seguridad en creación de smart contracts | Control total de permisos desde el sistema central. | Puede ser menos confiable si se produce una brecha de seguridad. | Solo usuarios específicos pueden ejecutar funciones críticas (ej. requiere(owner) en Solidity). | Difícil de actualizar permisos sin redeploy | Permite integrar servicios corporativos (Google, Azure AD). | Introduce dependencia en un sistema externo para crear contratos. |

| Driver ID | Título de Driver | Pattern 1: Contratos parametrizables |  | Pattern 2: Versionado con re-deploy por reglas |  | Pattern 3: Oráculos externos |  |
|----|----|----|----|----|----|----|----|
|  |  | Pro | Con | Pro | Con | Pro | Con |
| 3 | Modificabilidad de reglas en smart contracts | Permite cambiar reglas sin necesidad de re-deployar el contrato completo. | Mayor complejidad lógica dentro del contrato, puede haber errores al manejar parámetros. | Claridad y trazabilidad de versiones del contrato, fácil de auditar. | Implica reescribir y migrar contratos antiguos, lo que puede ser costoso y lento. | Permite integrar datos del mundo real, mayor flexibilidad. | Dependiendo de un servicio externo, puede generar puntos de fallo si el oráculo no está disponible. |

| Driver ID | Título de Driver | Pattern 1: Interfaz con pasos guiados |  | Pattern 2: Drag & Drop con validación inmediata |  | Pattern 3: Historial con enlaces de trazabilidad directa |  |
|----|----|----|----|----|----|----|----|
|  |  | Pro | Con | Pro | Con | Pro | Con |
| 5 | Interfaz intuitiva para subir y evidenciar logros | Muy fácil de usar, guía paso a paso al usuario, adecuado para novatos. | Puede ser tedioso si no está bien diseñado, mayor número de clics. | Muy rápida y visual, mejora la experiencia de usuario. | Requiere mayor complejidad en frontend y posibles limitaciones de navegador. | Total transparencia, el usuario puede verificar todo de forma directa. | Puede ser complicado para usuarios sin experiencia, requiere educación. |
| 6 | Consulta clara y verificable de transacciones | Facilidad de uso, el usuario tiene clara la navegación. | Menos flexible si el usuario sabe lo que busca (un click para acceder). | Rápido, más moderno y familiar para los usuarios. | No es ideal para la consulta de información, más útil para cargar evidencia. | Total transparencia, fácil para el usuario verificar la autenticidad. | Requiere educación, puede ser técnico para usuarios sin experiencia. |

| Driver ID | Título de Driver | Pattern 1: Microservicios con orquestación |  | Pattern 2: Arquitectura monolítica |  | Pattern 3: Serverless |  |
|----|----|----|----|----|----|----|----|
|  |  | Pro | Con | Pro | Con | Pro | Con |
| 8 | Escalabilidad del sistema | Escala horizontal de cada servicio de forma independiente; facilita despliegue continuo. | Mayor complejidad operativa (DevOps intensivo), overhead de red entre servicios. | Arquitectura más simple inicialmente; las colas absorben picos de carga sin cambiar código. | Difícil de escalar por componente; el monolito se vuelve un cuello de botella a gran escala. | Escalado automático sin gestión de servidores; pago por uso real. | Límites de ejecución / cold starts; puede resultar costoso bajo carga constante alta. |

### **4.1.5. Quality Attribute Scenario Refinements**

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 24%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th colspan="3" style="text-align: left;">Scenario Refinement for
Scenario 1</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Scenario(s):</th>
<th style="text-align: left;">Registro eficiente de cumplimiento de
metas</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Business Goals:</th>
<th style="text-align: left;">Agilizar la entrega de recompensas al
validar metas cumplidas, mejorar la experiencia del usuario.</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Relevant Quality
Attributes:</th>
<th style="text-align: left;">Usabilidad</th>
</tr>
<tr>
<th rowspan="6" style="text-align: left;">Scenario Components</th>
<th style="text-align: left;">Stimulus:</th>
<th style="text-align: left;">Registrar el cumplimiento de metas,
objetivos o certificados y subir evidencia.</th>
</tr>
<tr>
<th style="text-align: left;">Stimulus Source:</th>
<th style="text-align: left;">Usuario empleado</th>
</tr>
<tr>
<th style="text-align: left;">Environment:</th>
<th style="text-align: left;">Aplicación web</th>
</tr>
<tr>
<th style="text-align: left;">Artifact (if known):</th>
<th style="text-align: left;">Módulo de registro de metas, objetivos o
certificados</th>
</tr>
<tr>
<th style="text-align: left;">Response:</th>
<th style="text-align: left;">La interfaz guía al usuario con claridad,
permitiéndole subir la evidencia de manera intuitiva.</th>
</tr>
<tr>
<th style="text-align: left;">Response Measure:</th>
<th style="text-align: left;">El proceso debe completarse en menos de 90
segundos por el usuario.</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Questions:</th>
<th style="text-align: left;"><p>¿La interfaz es lo suficientemente
clara para nuevos usuarios?</p>
<p>¿El proceso tiene validaciones efectivas de campos?</p></th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Issues:</th>
<th style="text-align: left;">Posible abandono por procesos largos o
confusos. Dificultad en la carga de evidencia desde el móvil.</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 24%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th colspan="3" style="text-align: left;">Scenario Refinement for
Scenario 2</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Scenario(s):</th>
<th style="text-align: left;">Transacción de puntos es confiable y
trazable</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Business Goals:</th>
<th style="text-align: left;">Garantizar que los logros validados se
registren de forma inmutable y verificable para mantener la confianza en
el sistema</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Relevant Quality
Attributes:</th>
<th style="text-align: left;">Confiabilidad</th>
</tr>
<tr>
<th rowspan="6" style="text-align: left;">Scenario Components</th>
<th style="text-align: left;">Stimulus:</th>
<th style="text-align: left;">Validación de una meta, objetivo o
certificado de un empleado</th>
</tr>
<tr>
<th style="text-align: left;">Stimulus Source:</th>
<th style="text-align: left;">Sistema</th>
</tr>
<tr>
<th style="text-align: left;">Environment:</th>
<th style="text-align: left;">Conexión activa con el sistema
Blockchain</th>
</tr>
<tr>
<th style="text-align: left;">Artifact (if known):</th>
<th style="text-align: left;">Smart contract desplegado que registra el
logro</th>
</tr>
<tr>
<th style="text-align: left;">Response:</th>
<th style="text-align: left;">La transacción es correctamente procesada,
almacenada en blockchain y disponible para trazabilidad</th>
</tr>
<tr>
<th style="text-align: left;">Response Measure:</th>
<th style="text-align: left;">El 100% de los logros registrados deben
ser válidos y la transacción debe confirmarse en menos de 5
segundos</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Questions:</th>
<th style="text-align: left;"><p>¿Qué pasa si la red blockchain tiene
latencia?</p>
<p>¿Cómo se maneja una transacción fallida o pendiente?</p></th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Issues:</th>
<th style="text-align: left;">Posibles fallos en el tiempo de
confirmación o problemas de conectividad con la red blockchain</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 24%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th colspan="3" style="text-align: left;">Scenario Refinement for
Scenario 3</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Scenario(s):</th>
<th style="text-align: left;">Prevención de certificados o evidencias
fraudulentas en blockchain</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Business Goals:</th>
<th style="text-align: left;">Proteger la integridad del sistema,
garantizando que solo logros validados y verificados sean
registrados.</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Relevant Quality
Attributes:</th>
<th style="text-align: left;">Seguridad</th>
</tr>
<tr>
<th rowspan="6" style="text-align: left;">Scenario Components</th>
<th style="text-align: left;">Stimulus:</th>
<th style="text-align: left;">Intento de registrar metas, certificados o
evidencias sin validación oficial</th>
</tr>
<tr>
<th style="text-align: left;">Stimulus Source:</th>
<th style="text-align: left;">Usuario no autorizado o atacante</th>
</tr>
<tr>
<th style="text-align: left;">Environment:</th>
<th style="text-align: left;">Operación manual dentro del sistema por
parte del usuario (empresa o externo)</th>
</tr>
<tr>
<th style="text-align: left;">Artifact (if known):</th>
<th style="text-align: left;">Módulo de validación y registro en
blockchain</th>
</tr>
<tr>
<th style="text-align: left;">Response:</th>
<th style="text-align: left;">El sistema bloquea el intento y no genera
ninguna transacción en la blockchain</th>
</tr>
<tr>
<th style="text-align: left;">Response Measure:</th>
<th style="text-align: left;">El 100% de los registros deben ser
validados oficialmente antes de ser aceptados y registrados</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Questions:</th>
<th style="text-align: left;"><p>¿Cómo se valida que un usuario tenga
permisos adecuados?</p>
<p>¿Se registran los intentos fallidos en logs?</p></th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Issues:</th>
<th style="text-align: left;">Posibles brechas de seguridad si hay
errores en la lógica de validación o configuración de roles.</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 24%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th colspan="3" style="text-align: left;">Scenario Refinement for
Scenario 4</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Scenario(s):</th>
<th style="text-align: left;">Modificabilidad en la definición de reglas
de Smart Contract</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Business Goals:</th>
<th style="text-align: left;">Permitir al administrador adaptar las
reglas del sistema de recompensas de forma flexible, sin interrumpir el
servicio.</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Relevant Quality
Attributes:</th>
<th style="text-align: left;">Modificabilidad</th>
</tr>
<tr>
<th rowspan="6" style="text-align: left;">Scenario Components</th>
<th style="text-align: left;">Stimulus:</th>
<th style="text-align: left;">Necesidad de definir o actualizar las
reglas y condiciones de ejecución de un contrato inteligente</th>
</tr>
<tr>
<th style="text-align: left;">Stimulus Source:</th>
<th style="text-align: left;">Usuario empresa (Administrador)</th>
</tr>
<tr>
<th style="text-align: left;">Environment:</th>
<th style="text-align: left;">Acceso administrativo al sistema y
permisos habilitados para modificación de contratos</th>
</tr>
<tr>
<th style="text-align: left;">Artifact (if known):</th>
<th style="text-align: left;">Módulo de creación y edición de Smart
Contracts</th>
</tr>
<tr>
<th style="text-align: left;">Response:</th>
<th style="text-align: left;">El sistema permite modificar las
condiciones sin afectar el funcionamiento general del sistema</th>
</tr>
<tr>
<th style="text-align: left;">Response Measure:</th>
<th style="text-align: left;">El proceso de modificación debe estar 100%
libre de errores y no requerir reinicio del sistema</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Questions:</th>
<th style="text-align: left;"><p>¿Las reglas pueden actualizarse sin
re-deployar el contrato?</p>
<p>¿Existe control de versiones y validaciones?</p></th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Issues:</th>
<th style="text-align: left;">Riesgo de errores en lógica contractual o
pérdida de trazabilidad si no hay control de versiones adecuado</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 24%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th colspan="3" style="text-align: left;">Scenario Refinement for
Scenario 5</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Scenario(s):</th>
<th style="text-align: left;">Creación segura de Smart Contracts</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Business Goals:</th>
<th style="text-align: left;">Asegurar que solo administradores
autorizados puedan crear o modificar contratos inteligentes, evitando
accesos maliciosos.</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Relevant Quality
Attributes:</th>
<th style="text-align: left;">Seguridad</th>
</tr>
<tr>
<th rowspan="6" style="text-align: left;">Scenario Components</th>
<th style="text-align: left;">Stimulus:</th>
<th style="text-align: left;">Intento de creación de un Smart
Contract</th>
</tr>
<tr>
<th style="text-align: left;">Stimulus Source:</th>
<th style="text-align: left;">Usuario no autorizado</th>
</tr>
<tr>
<th style="text-align: left;">Environment:</th>
<th style="text-align: left;">Acceso restringido a usuarios sin
credenciales administrativas</th>
</tr>
<tr>
<th style="text-align: left;">Artifact (if known):</th>
<th style="text-align: left;">Módulo de creación de Smart Contracts</th>
</tr>
<tr>
<th style="text-align: left;">Response:</th>
<th style="text-align: left;">El sistema detecta el intento, lo bloquea
y registra el evento</th>
</tr>
<tr>
<th style="text-align: left;">Response Measure:</th>
<th style="text-align: left;">El 100% de los intentos no autorizados
deben ser bloqueados y registrados en un log de auditoría</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Questions:</th>
<th style="text-align: left;"><p>¿Qué nivel de autenticación se usa?</p>
<p>¿El sistema tiene mecanismos de auditoría y alertas activas?</p></th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Issues:</th>
<th style="text-align: left;">Fallos en la gestión de roles o en el
sistema de autenticación podrían permitir accesos indebidos</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 24%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th colspan="3" style="text-align: left;">Scenario Refinement for
Scenario 6</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Scenario(s):</th>
<th style="text-align: left;">Consulta de transacciones clara y
verificable</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Business Goals:</th>
<th style="text-align: left;">Asegurar que los empleados puedan
verificar sus logros registrados en blockchain de forma comprensible y
transparente</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Relevant Quality
Attributes:</th>
<th style="text-align: left;">Usabilidad</th>
</tr>
<tr>
<th rowspan="6" style="text-align: left;">Scenario Components</th>
<th style="text-align: left;">Stimulus:</th>
<th style="text-align: left;">El empleado desea consultar la
trazabilidad de sus logros</th>
</tr>
<tr>
<th style="text-align: left;">Stimulus Source:</th>
<th style="text-align: left;">Usuario empleado</th>
</tr>
<tr>
<th style="text-align: left;">Environment:</th>
<th style="text-align: left;">Interfaz de consulta desde web o
móvil</th>
</tr>
<tr>
<th style="text-align: left;">Artifact (if known):</th>
<th style="text-align: left;">Historial de transacciones filtrado por
usuario</th>
</tr>
<tr>
<th style="text-align: left;">Response:</th>
<th style="text-align: left;">El sistema muestra una lista clara de
logros con enlaces o hashes verificables por cada registro</th>
</tr>
<tr>
<th style="text-align: left;">Response Measure:</th>
<th style="text-align: left;">Tasa de éxito de consulta ≥ 90% y
satisfacción del usuario ≥ 4.5/5 en claridad de uso</th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Questions:</th>
<th style="text-align: left;"><p>¿La interfaz explica qué es un hash o
enlace de verificación?</p>
<p>¿Se puede acceder desde cualquier dispositivo?</p></th>
</tr>
<tr>
<th colspan="2" style="text-align: left;">Issues:</th>
<th style="text-align: left;">Confusión del usuario si el lenguaje es
técnico; riesgo de abandono si la interfaz no es intuitiva</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## **4.2. Strategic-Level Domain-Driven Design**

En esta sección, vamos a definir los dominios de nuestra solución,
tomaremos en cuenta eventos, actores, acciones, políticas, etc. para
dividir las responsabilidades de cada módulo y lograr un diseño
escalable, fácil de entender y desacoplado.

### **4.2.1. EventStorming**

Para simplificar el esfuerzo que conlleva elaborar distintos diagramas y
lograr obtener los requisitos funcionales de una solución de software,
se utilizará EventStorming. Según Bagocius (2022): “Es una técnica para
descubrir el comportamiento de un negocio o los requerimientos del
mismo. Es decir, permite recopilar eventos que se producen, los actores
involucrados, servicios de terceros implicados y comandos o acciones
para ejecutar las reglas de negocio” (párr. 3).

<img src="./media/image7.png"
style="width:6.26772in;height:1.16667in" />

Step 1: Domain Events

<img src="./media/image8.png"
style="width:6.26772in;height:2.58333in" />

Step 2: Add Actors and Commands

<img src="./media/image4.png"
style="width:6.26772in;height:3.29167in" />

Step 3: Policies and External Systems

<img src="./media/image23.png"
style="width:6.26772in;height:4.09722in" />

Step 4: Aggregates

<img src="./media/image5.png"
style="width:6.26772in;height:4.22222in" />

Step 5: Bounded Context

<img src="./media/image11.png"
style="width:6.26772in;height:3.94444in" />

Link al Miro:
[<u>EventStorming</u>](https://miro.com/app/board/uXjVIA4OirY=/?moveToWidget=3458764625401649245&cot=14)

### **4.2.2. Candidate Context Discovery**

Certificados: Este Bounded Context se encargará de la revisión de
certificados de cursos y metas que el empleado quiere lograr de acuerdo
al puesto de trabajo en el que se encuentre. La opción de trayectoria
que elija tendrá que ser completada por el mismo empleado, y la empresa
será la encargada de validar el certificado. Esta etapa del flujo
principal de nuestra aplicación es importante para cumplir las
condiciones necesarias y así el empleado pueda demostrar su valía,
compromiso y esfuerzo dentro de la empresa.

<img src="./media/image32.png" style="width:6.26772in;height:3.75in" />

Smart Contract: Este Bounded Context es el encargado de crear y
desplegar los Smart Contracts, el cual forma parte de la tecnología
Blockchain, además de ser el desencadenante de transacciones automáticas
si es que se cumplen ciertas condiciones. Se realizarán las respectivas
notificaciones al empleado.

<img src="./media/image6.png"
style="width:6.27083in;height:2.80208in" />

Transacciones: Este Bounded Context se encarga de cumplir con uno de los
objetivos de la aplicación, el cual es la transparencia entre sus
empleados. A través de la tecnología blockchain se podrá visualizar los
registros inmutables de cada transacción, la cual fue ejecutada por el
Smart Contract con anterioridad, fomentando así la competencia a nivel
interno.

<img src="./media/image9.png"
style="width:6.26772in;height:4.47222in" />

Catálogo de recompensas: Este Bounded Context se centra en las
recompensas que puede obtener el empleado cuando realiza sus
actividades, completa cursos, alcanza sus metas, etc. Podrá canjear sus
puntos obtenidos con productos, beneficios y otras cosas que la empresa
ofrezca.

<img src="./media/image38.png"
style="width:6.26772in;height:2.26389in" />

### **4.2.3. Domain Message Flows Modeling**

Evento: Transacción de puntos a empleado

Este evento se ejecuta cuando el empleado finaliza un curso pertinente
para su puesto de trabajo actual. Este curso debe ser completado en
alguna plataforma web de cursos, y el certificado debe ser revisado por
el equipo correspondiente de la empresa. Una vez validado se ejecuta
automáticamente el smart contract, el cual contiene requisitos para que
se realice la transacción de puntos al empleado. Finalmente, por medio
de la aplicación web se podrá visualizar en tiempo real la transacción
realizada a ese empleado.

<img src="./media/image22.png"
style="width:6.26772in;height:2.93056in" />

Link al Miro: [<u>Domain Message Flow Modelling Scenario
1</u>](https://miro.com/app/board/uXjVIA4OirY=/?moveToWidget=3458764625558054083&cot=14)

Evento: Canje de puntos en catálogo de recompensas

Este evento ocurre cuando el usuario empleado desea canjear sus puntos
obtenidos en el catálogo de recompensas que tiene integrado nuestra
aplicación. Este catálogo necesita ser actualizado con productos,
beneficios, entre otros, los cuales deben ser ingresados por el usuario
empresa.

<img src="./media/image18.png"
style="width:6.26772in;height:3.13889in" />

Link al Miro: [<u>Domain Message Flow Modelling Scenario
2</u>](https://miro.com/app/board/uXjVIA4OirY=/?moveToWidget=3458764625562354338&cot=14)

### **4.2.4. Bounded Context Canvases**

Certificados Context

<img src="./media/image12.png"
style="width:6.26772in;height:3.23611in" />

Smart Contracts Context

<img src="./media/image16.png"
style="width:6.26772in;height:3.23611in" />

Transacciones Context

<img src="./media/image34.png"
style="width:6.26772in;height:3.23611in" />

Usuarios Context

<img src="./media/image3.png"
style="width:6.26772in;height:3.83333in" />

Catálogo de recompensas Context

<img src="./media/image28.png"
style="width:6.26772in;height:3.23611in" />

Premios Context

<img src="./media/image41.png"
style="width:6.26772in;height:3.23611in" />

### **4.2.5. Context Mapping**

- Todos los bounded context cuentan con una interfaz gráfica en la
  aplicación web, por tal motivo es que se agregan íconos de usuarios,
  ya que será un sistema centrado en interacción humana.

- El bounded context Certificados tiene una coordinación del tipo débil
  con el bounded context Smart Contracts, ya que smart contracts solo
  necesita un resultado de Certificados. Además, se establece una capa
  de anticorrupción (ACL) para proteger las reglas de negocio de Smart
  Contracts.

- El bounded context Smart Contracts tiene una fuerte relación con el
  bounded context Transacciones. Ambos pueden compartir algunos modelos
  o reglas de negocio para realizar sus debidas operaciones.

- La relación entre Usuarios y Smart Contracts nos indica que Smart
  Contracts necesita datos del usuario para definir los respectivos
  contratos. Además, se usa una capa ACL para evitar contaminar el
  contexto.

- El bounded context de Catálogo ofrece APIs o servicios para que el
  bounded context de Usuarios pueda consumirlos. El contexto de Usuarios
  tiene una capa ACL para que las reglas de negocio del mismo contexto
  no sean expuestas al Catálogo.

- La relación entre el contexto Premios y Usuarios indica que el
  contexto Premios está en constante colaboración con el usuario y se
  adapta según las necesidades.

<img src="./media/image43.png"
style="width:6.26772in;height:3.01389in" />

Link al Miro: [<u>Context
Mapping</u>](https://miro.com/app/board/uXjVIA4OirY=/?moveToWidget=3458764625826801771&cot=14)

## **4.3. Software Architecture**

### **4.3.1. Software Architecture System Landscape Diagram**

SkillLedger es una plataforma que permite a empresas reconocer el
talento de sus empleados a través de recompensas en blockchain. El
sistema interactúa con tres tipos de usuarios: empleados, recursos
humanos, y administradores.

<img src="./media/image15.png"
style="width:6.13542in;height:5.63542in" />

### **4.3.1. Software Architecture Context Level Diagrams**

<img src="./media/image24.png"
style="width:6.26772in;height:5.69444in" />

### **4.3.2. Software Architecture Container Level Diagrams**

Los empleados y el HR acceden por la web, ambos se comunican con el
sistema a través del API Gateway, que enruta las solicitudes según el
contexto (autenticación, recompensas, perfiles).

<img src="./media/image19.png"
style="width:6.16667in;height:5.19792in" />

### **4.3.3. Software Architecture Deployment Diagrams**

<img src="./media/image1.png"
style="width:6.26772in;height:4.34722in" />

## Conclusiones

- El desarrollo del capítulo introductorio permitió definir claramente
  el propósito, misión y visión de la plataforma, así como detallar la
  problemática central y su impacto en el entorno laboral. Se
  establecieron supuestos de negocio, hipótesis y estrategias Lean UX,
  aportando una base conceptual sólida. Este trabajo permitió al equipo
  comprender el valor de la propuesta desde una perspectiva estratégica
  y orientar correctamente el diseño funcional del producto.

- El análisis de los segmentos objetivos y de la competencia permitió
  enfocar la solución hacia usuarios bien definidos y diferenciar la
  propuesta frente a otras plataformas del mercado. Asimismo, el diseño
  de la arquitectura del sistema integró esos hallazgos para construir
  una solución técnica escalable, segura y orientada a la experiencia
  del usuario. Este trabajo fue clave para alinear los aspectos técnicos
  con las necesidades del mercado y usuarios.

- La etapa de needfinding permitió identificar necesidades reales de los
  usuarios a través de herramientas como user personas, empathy maps y
  task matrix. Estos insumos facilitaron una comprensión empática del
  comportamiento y motivaciones de cada segmento, lo cual fue
  fundamental para priorizar funcionalidades relevantes y definir una
  experiencia de usuario coherente con los objetivos del producto. La
  información obtenida enriqueció la perspectiva del diseño centrado en
  el usuario.

- La especificación de requisitos mediante historias de usuario y
  backlog permitió definir con precisión las funcionalidades clave del
  sistema. Se organizaron en épicas coherentes, considerando criterios
  técnicos y necesidades del negocio. Este trabajo fue esencial para
  establecer un marco estructurado de desarrollo, facilitar la
  estimación del esfuerzo y asegurar que cada funcionalidad responda a
  un objetivo concreto dentro del flujo de la aplicación.

- El diseño estratégico basado en atributos de calidad permitió tomar
  decisiones arquitectónicas fundamentadas en drivers relevantes como
  seguridad, escalabilidad y trazabilidad. A través del uso de
  microservicios y principios de Domain-Driven Design, se lograron
  separar responsabilidades y modelar bounded contexts específicos. Esta
  etapa aportó una base robusta para garantizar la mantenibilidad del
  sistema y responder de manera efectiva a los requerimientos técnicos y
  funcionales del producto.

## Bibliografía

Bagocius T. (2022, 27 de septiembre). *Event storming.* Adictos al
trabajo. Recuperado el 18 de abril del 2025, de
[<u>https://adictosaltrabajo.com/2022/09/27/event-storming/</u>](https://adictosaltrabajo.com/2022/09/27/event-storming/)

ddd-crew. (2023, 27 de diciembre). *Context mapping*. GitHub. Recuperado
el 23 de abril del 2025, de
[<u>https://github.com/ddd-crew/context-mapping</u>](https://github.com/ddd-crew/context-mapping)

ddd-crew. (2024, 20 de octubre). *Bounded context canvas*. GitHub.
Recuperado el 23 de abril del 2025, de
[<u>https://github.com/ddd-crew/bounded-context-canvas</u>](https://github.com/ddd-crew/bounded-context-canvas)

## Anexos

Github:[<u>https://github.com/TalentChain-UPC/Report---TalentChain</u>](https://github.com/TalentChain-UPC/Report---TalentChain)

Video entrevistas completo:
[<u>https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112655_upc_edu_pe/EZ4eIwIzfSxBsZGsE3bONl0BcwuNRcYbwnkuKwkjp-OU_Q?e=o96iQu</u>](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112655_upc_edu_pe/EZ4eIwIzfSxBsZGsE3bONl0BcwuNRcYbwnkuKwkjp-OU_Q?e=o96iQu)

Video expo:

[<u>https://upcedupemy.sharepoint.com/:v:/g/personal/u202112655_upc_edu_pe/EaHMFyC9WjRAqhMMpwjiIi4BFz3wdJ4lQ9cfKdfza_WtdA?e=fPClXy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D</u>](https://upcedupemy.sharepoint.com/:v:/g/personal/u202112655_upc_edu_pe/EaHMFyC9WjRAqhMMpwjiIi4BFz3wdJ4lQ9cfKdfza_WtdA?e=fPClXy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

