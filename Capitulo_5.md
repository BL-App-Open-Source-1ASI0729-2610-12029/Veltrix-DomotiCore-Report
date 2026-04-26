## 5.1. Software Configuration Management

La gestión en DomotiCore es fundamental para asegurar el control de todos los componentes del sistema, incluyendo el código fuente, documentación, prototipos y configuraciones del entorno IoT. Dado que el proyecto involucra múltiples elementos como interfaz web, simulación de dispositivos y lógica de automatización, es necesario mantener un control riguroso que permita el trabajo colaborativo.

## 5.1.1. Software Development Environment Configuration

**Project Management**

- **Trello**: Se utiliza para gestionar las tareas del proyecto, permitiendo visualizar el progreso del desarrollo mediante tableros organizados por estados (To-do, In progress, Done). Esto fue clave durante el Sprint 1, donde se gestionó la finalización del reporte y la landing page.

<div style="text-align:center;"><img src="imagenes/images_Cap5/Trello .png" alt="texto"></div>

- **Microsoft Teams**: Se emplea como plataforma principal de comunicación para reuniones, planificación de sprints y coordinación del equipo, facilitando la colaboración remota.

<div style="text-align:center;"><img src="imagenes/images_Cap5/Microsoft Teams.png" alt="texto"></div>

**Requirement Management**

- **Miro**: Se utiliza para estructurar ideas, flujos del sistema y análisis del negocio, incluyendo el Event Storming del sistema IoT.

<div style="text-align:center;"><img src="imagenes/Impact map 1.png" alt="texto"></div>

- **Structurizr**: Permite modelar la arquitectura del sistema DomotiCore bajo el modelo C4, representando componentes como:
dashboard, gateway, nodos IoT, servicios de monitoreo y product UX/UI design.

<div style="text-align:center;"><img src="imagenes/images_Cap5/structurizr.png" alt="texto"></div>

- **Figma**: Herramienta utilizada para diseñar la interfaz del sistema, incluyendo: dashboard centralizado, control de dispositivos, visualización de consumo energético.

<div style="text-align:center;"><img src="imagenes/images_Cap5/figma.png" alt="texto"></div>

- **Lucidchart**: Se emplea para diagramas de flujo, arquitectura y diseño de procesos del sistema.

<div style="text-align:center;"><img src="imagenes/images_Cap5/lucidchart.png" alt="texto"></div>

**Software Development**: Tecnologías utilizadas para el desarrollo de la Landing Page y la base del sistema web.

- **HTML**

<div style="text-align:center;"><img src="imagenes/images_Cap5/html.jpg" alt="texto"></div>

- **CSS**

<div style="text-align:center;"><img src="imagenes/images_Cap5/css.jpg" alt="texto"></div>

- **JavaScript**

<div style="text-align:center;"><img src="imagenes/images_Cap5/JavaScript.png" alt="texto"></div>

**WebStorm**: IDE utilizado para el desarrollo del frontend del sistema.

<div style="text-align:center;"><img src="imagenes/images_Cap5/webstorm.jpg" alt="texto"></div>

**Software Testing**: Gherkin se utiliza para definir escenarios de prueba basados en historias de usuario: Para el control remoto de dispositivos, automatización por horarios, alertas de consumo energético.

**Software Documentation**

- **GitHub**: Se utiliza como repositorio central del proyecto, permitiendo el control de versiones, trabajo colaborativo, registro de commits, documentación del sistema, software Deployment.

<div style="text-align:center;"><img src="imagenes/images_Cap5/github.png" alt="texto"></div>

**GitHub Pages**: Se emplea para desplegar la Landing Page del producto, permitiendo mostrar la propuesta de valor de DomotiCore a los usuarios.

<div style="text-align:center;"><img src="imagenes/images_Cap5/github pages.png"

## 5.1.2. Source Code Management

La gestión del código fuente del proyecto DomotiCore se realiza mediante la plataforma GitHub, la cual permite mantener un control de versiones eficiente. El repositorio principal del proyecto, denominado “Open_Source_”, centraliza tanto la documentación del proyecto como los avances de la Landing Page y los diseños iniciales de la aplicación web.

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.2 github.png"

**Estructura de ramas**: Se uso de múltiples ramas organizadas por capítulos y funcionalidades, lo cual refleja una adaptación práctica del modelo GitFlow.

- **Main**: Rama principal del repositorio. Contiene la versión estable del proyecto. Se utiliza para almacenar la documentación final y entregables.
- **Develop**: Rama de integración principal. Aquí se consolidan los cambios provenientes de otras ramas. Es la rama donde se concentran los commits más recientes del equipo y donde sera visibles todos los commits de las ramas en uno solo.

**Ramas por funcionalidades / capítulos**

- **1.1/Startup-Profile**
- **1.2/Solution-Profile**
- **1.3/Segmentos-Objetivos**
- **2.2/Entrevistas**
- **2.4/Big-Picture-EventStorming**
- **3.1/User-Stories**
- **4.1/Style-Guidelines**
- **4.3.1/Landing-Page-Wireframe**
- **5.1/Software-Configuration-Management**

Se trabaja de forma paralela, separando responsabilidades por módulo o capítulo, facilitar la integración progresiva en develop y la evidencia de integración (Commits y Merges).

Despues de completar todas las ramas se uniran todos en **Develop**, que servira para que todo sea visible en una misma rama.

**Gestión de commits**: El equipo utiliza commits descriptivos que permiten identificar claramente los cambios realizados.

- "add landing page mockup"
- "add web applications wireframes"
- "docs: update README with project details"
- "Update startup and product names in README"

Los Commits:
- feat → nuevas funcionalidades
- docs → documentación
- Colaboración del equipo

Cada miembro contribuye con commits específicos que se integran cambios de diferentes ramas, lo que mantiene un flujo continuo de desarrollo y el control de versiones y trazabilidad.

## 5.1.3. Source Code Style Guide & Conventions

El código desarrollado por los miembros del equipo esté completamente redactado en inglés.

## **HTML**

**Use Lowercase Element Names**: Se recomienda utilizar minúsculas para todos los elementos HTML.

    <section class="hero">
      <h1>Controla tu hogar</h1>
    </section>

**Close All HTML Elements**: Todos los elementos deben cerrarse correctamente para evitar errores de renderizado.

 < p >DomotiCore centraliza tus dispositivos.</ p >

< a href="#contacto">Solicitar demo</a >

**Use Lowercase Attribute Names**: Los atributos deben escribirse en minúsculas.

< input type="email" placeholder="tu@correo.com" id="fe" />

**Use Semantic HTML Elements**: Se deben utilizar etiquetas semánticas para mejorar la estructura y accesibilidad.

< nav>...</ nav>
< section id="funciones">...</ section>
< footer>...</ footer>

**Use Descriptive IDs and Classes**: Los nombres deben ser claros y representar su función.

< section id="contacto">
  < div class="contact-form">

## **CSS**

**Use Kebab-Case for Class Names**: Las clases deben escribirse en minúsculas separadas por guiones.

.contact-form {
  display: flex;
}


**Use CSS Variables for Colors**: Se deben definir colores reutilizables en :root.

:root {
  --blue: #1E40AF;
  --navy: #0F172A;
}

**Group Styles by Sections**: El código CSS debe organizarse por secciones del sitio.

/* NAV */
nav { ... }

/* HERO */
.hero { ... }

/* FOOTER */
footer { ... }


**Use Consistent Spacing**: Se debe mantener consistencia en márgenes, padding y alineación.

.section {
  padding: 6rem 2rem;
}

**Responsive Design with Media Queries**: Se deben usar breakpoints para adaptar la interfaz.

@media (max-width: 600px) {
  .hero {
    padding: 4rem 1rem;
  }
}


## **JavaScript**

**Use CamelCase for Variables and Functions**: Las variables y funciones deben usar camelCase.

function sendForm() {
  const userName = document.getElementById('fn').value;
}

**Keep Functions Simple and Clear**: Las funciones deben ser cortas y fáciles de entender.

if (!n || !e) {
  alert('Por favor completa tu nombre y correo.');
  return;
}


**Use Meaningful Variable Names**: Los nombres deben representar su propósito.

const navLinks = document.getElementById('navLinks');
const hamburger = document.getElementById('hamburger');

**Avoid Inline JavaScript**: Se recomienda mantener la lógica separada del HTML.

< button onclick="sendForm()">Enviar</ button>

## 5.1.4. Software Deployment Configuration

Este apartado describe la configuración y el proceso de despliegue del sistema DomotiCore.

**Configuracion del proyecto**
Se crea un repositorio remoto en GitHub para la Landing Page del proyecto DomotiCore.

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4 (part1).png"

Se agregan los integrantes del equipo como colaboradores del repositorio.

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(part2).png"

Se organiza la estructura base del proyecto (Brenches)

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(part4).png"

Se ve lo visual en del documento.

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(part5).png"

Se habilita GitHub Pages para las ramas.

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(part6).png"

**Creación Landing Page:**

Se desarrolla la interfaz del sistema basada en la Landing Page del codigo.

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(lading parte1).png"

Se realizan commits organizados según funcionalidades implementadas.

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(lading parte2).png"

**Despliegue:**

Se configura GitHub Pages para desplegar automáticamente desde la rama develop.

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(part3).png"

Se valida el funcionamiento en distintos navegadores (Chrome, Edge, etc.) para la lading page.
<div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(lading parte3).png"

## 5.2. Landing Page, Services & Applications Implementation

La implementación de la Landing Page, los servicios y la aplicación web de DomotiCore se desarrolló la página de presentación del sistema, enfocada en comunicar los beneficios y la vista preliminar del dashboard del sistema. Además, se implementaron estructuras base para los servicios de gestión de dispositivos, monitoreo energético y automatización. El proceso permitió traducir los requisitos definidos previamente (User Stories, entrevistas y Event Storming) en código funcional utilizando tecnologías como HTML, CSS y JavaScript.

## 5.2.1. Sprint 1

El Sprint 1 representa el primer ciclo de desarrollo ágil del proyecto DomotiCore, donde se priorizó la construcción de la Landing Page y la organización inicial del repositorio en GitHub.

Durante este sprint, el equipo se enfocó en:
- Implementar la estructura visual de la Landing Page.
- Definir la identidad visual basada en los Style Guidelines.
- Subir avances al repositorio.
- Organizar ramas y commits.
- Documentar el proyecto.

## 5.2.1.1. Sprint Planning 1

### Sprint Information

| Campo | Detalle |
| :--- | :--- |
| **Sprint #** | Sprint 1 |
| **Date** | 2026-04-25 |
| **Time** | 11:00 PM |
| **Location** | Microsoft Teams (Reunión virtual) |
| **Prepared By** | Equipo Veltrix |

### Attendees (Planning Meeting)

| Participantes |
| :--- |
| Cesar Quispe |
| Oscar Checa |
| Diego Esquich |
| Fabrizio Rafael|
| Alvaro Rocha |
### Sprint 1 – Review Summary

| Descripción |
| :--- |
| Durante el Sprint 1 se lograron avances importantes como la implementación completa de la Landing Page de DomotiCore, incluyendo secciones como Hero, Features, About y Contacto. Además, se organizó el repositorio en GitHub, se realizaron commits relacionados a wireframes, mockups y documentación, y se implementó una vista simulada del dashboard. Sin embargo, quedaron pendientes aspectos como la integración con backend, automatización real de dispositivos y despliegue final en producción. |

### Sprint 1 – Retrospective Summary

| Descripción |
| :--- |
| El Sprint 1 evidenció problemas en la organización del equipo, como falta de comunicación, distribución ineficiente de tareas y dependencia de entregas de último momento. Como mejoras, se propuso realizar reuniones más frecuentes, utilizar herramientas como Trello para seguimiento, definir responsabilidades claras y mejorar la gestión del tiempo. |

### Sprint Goal & User Stories

| Campo | Detalle |
| :--- | :--- |
| **Sprint 1 Goal** | Desarrollar y desplegar la Landing Page funcional de DomotiCore, estructurar el repositorio en GitHub y reflejar el avance en el tablero de tareas. |
| **Sprint 1 Velocity** | 5 User Stories |
| **Story Points por historia** | 5 puntos |
| **Sum of Story Points** | 25 |

## 5.2.1.2. Aspect Leaders and Collaborators

## 5.2.1.3. Sprint Backlog 1

En este primer sprint, el equipo se enfocó en la implementación de las funcionalidades base de la Landing Page de DomotiCore, incluyendo la estructura HTML, estilos CSS, navegación interactiva y diseño responsive. Asimismo, se desarrolló el reporte del proyecto que documenta el ciclo de vida del software, desde la concepción hasta la implementación inicial.

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.2.1.3. Sprint Backlog 1.png"

### Sprint Backlog
| Sprint # | ID | Title | Description | Estimation (Hours) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Sprint 1** | TSK001 | GitHub repository setup | Creación de repositorios, configuración de ramas y organización del proyecto | 2 | All team members | Done |
| **Sprint 1** | TSK002 | Landing Page HTML structure | Desarrollo de la estructura base HTML (navbar, hero, sections) | 5 | Frontend team | Done |
| **Sprint 1** | TSK003 | Landing Page CSS styling | Implementación de estilos siguiendo la guía visual (colores, tipografía) | 6 | Frontend team | Done |
| **Sprint 1** | TSK004 | Responsive design | Adaptación de la Landing Page a dispositivos móviles y tablets | 4 | Frontend team | Done |
| **Sprint 1** | TSK005 | Navigation and interactivity | Implementación de navegación, menú hamburguesa y scroll dinámico | 3 | Frontend team | Done |
| **Sprint 1** | TSK006 | Platform preview section | Creación del dashboard preview simulado dentro de la Landing Page | 4 | Frontend team | Done |
| **Sprint 1** | TSK007 | Contact form functionality | Implementación del formulario de contacto con validaciones básicas | 3 | Frontend team | Done |
| **Sprint 1** | TSK008 | Report documentation (Chapters 1–5) | Desarrollo del documento del proyecto con toda la información requerida | 10 | All team members | Done |

## 5.2.1.4. Development Evidence for Sprint Review

## 5.2.1.5. Execution Evidence for Sprint Review

En esta entrega, el equipo ha completado con éxito la implementación y el lanzamiento de la página de la Landing Page. Esta página presenta diferentes secciones que brindan información detallada sobre nuestro producto.

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.2.1.5. Execution Evidence(1).png"

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.2.1.5. Execution Evidence(2).png"

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.2.1.5. Execution Evidence(3).png"

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.2.1.5. Execution Evidence(4).png"

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.2.1.5. Execution Evidence(5).png"

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.2.1.5. Execution Evidence(6).png"

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.2.1.5. Execution Evidence(7).png"

##

## 5.2.1.6. Services Documentation Evidence for Sprint Review

## 5.2.1.7. Software Deployment Evidence for Sprint Review

## 5.2.1.8. Team Collaboration Insights during Sprint

Los analíticos que nos proporciona Github, en su apartado de Insights, sobre la colaboración del equipo durante el Sprint 1:

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.2.1.8. Team Collaboration.png"


##