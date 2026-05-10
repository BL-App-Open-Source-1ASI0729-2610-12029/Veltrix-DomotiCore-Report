## 5.1. Software Configuration Management

La gestión en DomotiCore incluye el código fuente, documentación, prototipos y configuraciones del entorno. El proyecto contempla distintos productos digitales, incluyendo una Landing Page, aplicaciones web y servicios backend orientados a la automatización y monitoreo de dispositivos IoT. El equipo adopta prácticas basadas en GitFlow, Conventional Commits y Semantic Versioning, asegurando un flujo de trabajo colaborativo y organizado.

## 5.1.1. Software Development Environment Configuration
En esta sección se describen las herramientas, tecnologías y plataformas utilizadas por el equipo para el desarrollo colaborativo del proyecto DomotiCore.

| Category | Software / Tool | Purpose in the Project | Access / Download | Preview |
| :--- | :--- | :--- | :--- | :--- |
| **Project Management** | Trello | Gestión de tareas, seguimiento de Sprint Backlog y control del avance del proyecto. | [Trello](https://trello.com) | <img src="imagenes/images_Cap5/Trello .png" width="100"> |
| **Team Communication** | Microsoft Teams | Plataforma principal de comunicación para reuniones y coordinación del equipo. | [Teams](https://www.microsoft.com/microsoft-teams) | <img src="imagenes/images_Cap5/Microsoft Teams.png" width="100"> |
| **Requirements Management** | Miro | Estructuración de ideas, flujos del sistema y análisis de negocio (Event Storming). | [Miro](https://miro.com) | <img src="imagenes/images_Cap5/miro.png" width="100"> |
| **Software Architecture** | Structurizr | Modelado de la arquitectura bajo el modelo C4 (dashboard, gateway, nodos). | [Structurizr](https://structurizr.com) | <img src="imagenes/images_Cap5/structurizr.png" width="100"> |
| **UX/UI Design** | Figma | Diseño de la interfaz, dashboard y visualización de consumo energético. | [Figma](https://www.figma.com) | <img src="imagenes/images_Cap5/figma.png" width="100"> |
| **Diagram Modeling** | Lucidchart | Elaboración de diagramas de flujo, arquitectura y diseño de procesos. | [Lucidchart](https://www.lucidchart.com) | <img src="imagenes/images_Cap5/lucidchart.png" width="100"> |
| **Frontend Development** | HTML5 | Estructura base para el desarrollo de la Landing Page y la plataforma web. | [MDN](https://developer.mozilla.org) | <img src="imagenes/images_Cap5/html.jpg" width="50"> |
| **Frontend Development** | CSS3 | Definición de estilos visuales, diseño responsive y estética. | [MDN](https://developer.mozilla.org) | <img src="imagenes/images_Cap5/css.jpg" width="50"> |
| **Frontend Development** | JavaScript | Funcionalidad interactiva y lógica del sistema web. | [MDN](https://developer.mozilla.org) | <img src="imagenes/images_Cap5/JavaScript.png" width="50"> |
| **IDE** | WebStorm | IDE utilizado para el desarrollo y edición del código fuente frontend. | [WebStorm](https://www.jetbrains.com/webstorm) | <img src="imagenes/images_Cap5/webstorm.jpg" width="100"> |
| **Version Control** | Git & GitHub | Repositorio central para control de versiones, commits y documentación. | [GitHub](https://github.com) | <img src="imagenes/images_Cap5/github.png" width="100"> |
| **Software Testing** | Gherkin | Escenarios de prueba (control remoto, automatización, alertas) por historias de usuario. | [Gherkin](https://cucumber.io/docs/gherkin) | <img src="imagenes/images_Cap5/Gherkin.png" width="100">  |
| **Deployment** | GitHub Pages | Despliegue de la Landing Page para mostrar la propuesta de valor. | [GH Pages](https://pages.github.com) | <img src="imagenes/images_Cap5/github pages.png" width="100"> |

## 5.1.2. Source Code Management

La gestión de código fuente del proyecto **DomotiCore** se realiza mediante la plataforma **GitHub**, permitiendo un control de versiones en entorno de trabajo colaborativo. Se han definido repositorios independientes para cada producto digital.

### 5.1.2.1 Repositories

| Product | Repository URL | Description |
| :--- | :--- | :--- |
| **Organization** | [BL-App-Open-Source-1ASI0729-2610-12029](https://github.com/BL-App-Open-Source-1ASI0729-2610-12029) | Organizacion donde se ubican todos los repositorios del proyecto. |
| **Landing Page** | [Veltrix-DomotiCore-Business-Web-Page](https://github.com/BL-App-Open-Source-1ASI0729-2610-12029/Veltrix-DomotiCore-Business-Web-Page) | Repositorio de la Landing Page institucional del proyecto. |
| **Frontend Web Application** | [Veltrix-DomotiCore-Front-End](https://github.com/BL-App-Open-Source-1ASI0729-2610-12029/Veltrix-DomotiCore-Front-End) | Aplicación web para monitoreo y control de dispositivos. |
| **Backend Web Services** | [Veltrix-DomotiCore-Back-end](https://github.com/BL-App-Open-Source-1ASI0729-2610-12029/Veltrix-DomotiCore-Back-end) | API REST y lógica de automatización IoT. |
| **Documentation Repository** | [Veltrix-DomotiCore-Report](https://github.com/BL-App-Open-Source-1ASI0729-2610-12029/Veltrix-DomotiCore-Report) | Documentación técnica, reportes y entregables del proyecto. |
###
<div style="text-align:center;"><img src="imagenes/images_Cap5/Proyecto-Github-Organizacion.png" width="800" alt="GitHub Repository Structure"></div>

### 5.1.2.2 GitFlow Workflow

El equipo adopta **GitFlow** como estrategia de branching para mantener la estabilidad.

* **Main Branch**: Contiene únicamente versiones estables y aprobadas del proyecto listas para producción.
    * `main`
* **Develop Branch**: Rama principal de integración donde se consolidan las funcionalidades desarrolladas antes de integrarse en producción.
    * `develop`
* **Feature Branches**: Cada nueva funcionalidad se desarrolla en una rama independiente para evitar conflictos en el código base.
    * **Naming Convention**: `feature/<feature-name>`
    * **Examples**: `feature/landing-page-navbar`, `feature/device-monitoring`
* **Hotfix Branches**: Ramas de emergencia para corregir errores críticos detectados directamente en producción.
    * **Naming Convention**: `hotfix/<issue-description>`

### 5.1.2.3 Semantic Versioning

El proyecto utiliza **Semantic Versioning 2.0.0** para controlar las versiones de los productos digitales de Veltrix.

| Version | Description |
| :--- | :--- |
| **v1.0.0** | Primera versión estable y funcional del producto. |
| **v1.1.0** | Incorporación de nuevas funcionalidades menores. |
| **v1.1.1** | Corrección de errores menores. |
| **v2.0.0** | Cambios mayores que incluyen modificaciones estructurales incompatibles. |

### 5.1.2.4 Conventional Commits

Se adopta el estándar de **Conventional Commits** para mantener un historial de cambios limpio y fácil de verificar por el equipo.

| Prefix | Purpose |
| :--- | :--- |
| **feat** | Implementación de nuevas funcionalidades. |
| **fix** | Corrección de errores o bugs. |
| **docs** | Actualizaciones en la documentación del repositorio. |
| **style** | Cambios que no afectan la lógica (espaciados, formatos, CSS). |
| **refactor** | Reestructuración del código existente sin cambiar su funcionalidad. |
| **test** | Corrección de pruebas unitarias o de integración. |

**Examples:**
* `feat: implement responsive landing page`
* `docs: update sprint 1 documentation`
* `fix: correct mobile navigation behavior`
* `style: improve hero section spacing`

## 5.1.3. Source Code Style Guide & Conventions

El equipo adopta convenciones estandarizadas para garantizar legibilidad del código fuente. Como norma general, todos los nombres de variables, clases, funciones y componentes deben ser redactados en idioma **inglés**. 

### 5.1.3.1 HTML Conventions

* **Use Lowercase Element Names**: Todos los elementos y atributos HTML deben escribirse en minúsculas.
    ```html
    <section class="hero-section">
        <input type="email" id="user-email" />
    </section>
    ```
* **Close All HTML Elements**: Todos los elementos deben cerrarse correctamente para evitar errores de renderizado.
    ```html
    <p>DomotiCore centralizes your devices.</p>
    ```
* **Use Semantic HTML Elements**: Se prioriza el uso de etiquetas semánticas para mejorar el SEO y la accesibilidad.
    ```html
    <nav></nav>
    <main></main>
    <footer></footer>
    ```
* **Use Descriptive IDs and Classes**: Los nombres deben ser claros y representar su función.
    ```html
    <div class="contact-form-container">
    ```

### 5.1.3.2 CSS Conventions

* **Use Kebab-Case for Class Names**: Las clases deben escribirse en minúsculas separadas por guiones.
    ```css
    .device-control-panel {
        display: grid;
    }
    ```
* **Use CSS Variables**: Se definen colores y valores reutilizables en el `:root` para facilitar cambios globales.
    ```css
    :root {
        --primary-blue: #1E40AF;
        --dark-navy: #0F172A;
    }
    ```
* **Group Styles by Sections**: El código CSS se organiza mediante bloques de comentarios para identificar claramente las secciones del sistema.
    ```css
    .main-nav { ... }
    .hero-container { ... }
    .control-panel { ... }
    ```
* **Responsive Design**: Uso obligatorio de Media Queries para garantizar una interfaz adaptable.
    ```css
    @media (max-width: 768px) {
        .hero { padding: 2rem; }
    }
    ```

### 5.1.3.3 JavaScript Conventions

* **Use CamelCase**: Las variables y funciones deben seguir la convención camelCase.
    ```javascript
    const deviceStatus = document.getElementById("deviceStatus");
    function updateDeviceStatus() { ... }
    ```
* **Use Meaningful Names**: Los nombres deben representar claramente el propósito del dato o acción.
    ```javascript
    const loginButton = document.querySelector(".btn-login");
    ```
* **Keep Functions Simple**: Las funciones deben realizar una única tarea y ser fáciles de leer.
    ```javascript
    function validateEmail(email) {
        return email.includes("@");
    }
    ```
* **Avoid Inline JavaScript**: La lógica debe estar separada del marcado HTML para mejorar la seguridad y el orden.
    * **Incorrecto**: `<button onclick="sendData()">`
    * **Correcto**: `button.addEventListener("click", sendData);`

## 5.1.4. Software Deployment Configuration

Esta sección describe la configuración, el flujo de trabajo y el proceso de los productos digitales del proyecto.

### 5.1.4.1 Landing Page Deployment

La Landing Page institucional se despliega mediante **GitHub Pages**, utilizando el flujo de integración automática desde la rama `develop`.

**Proceso de Despliegue y Configuración:**

1.  **Configuración del Repositorio:** Se crea el repositorio remoto y se habilitan los permisos para los integrantes del equipo.
    <div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4 (part1).png" width="500"></div>
    <div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(part2).png" width="500"></div>

2.  **Estructura de Ramas:** Se organiza el repositorio siguiendo la estrategia de branching definida anteriormente.
    <div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(part4).png" width="500"></div>

3.  **Commits Automático:** Cada commit realizado en la rama `develop` dispara un proceso de integración que actualiza la versión pública del sitio.
    <div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(part6).png" width="500"></div>

4.  **Habilitación de GitHub Pages:** Se configura el entorno de despliegue para apuntar a la rama de desarrollo.
    <div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(part3).png" width="500"></div>

5.  **Validación:** Se verifica la correcta visualización y funcionamiento responsivo en múltiples navegadores (Chrome, Edge, Safari).
    <div style="text-align:center;"><img src="imagenes/images_Cap5/5.1.4(lading parte3).png" width="500"></div>

**Deployment URL:** [DomotiCore – Landing Page Veltrix](https://oscarcheca.github.io/domoticore-landing/)

---

### 5.1.4.2 Frontend Web Application Deployment

La aplicación web principal (desarrollada con **Vue.js**) será desplegada utilizando **Vercel** para facilitar la integración continua (CI/CD) y previsualizaciones automáticas por cada Pull Request.

* **Repository**: [Veltrix-DomotiCore-Front-End](https://github.com/BL-App-Open-Source-1ASI0729-2610-12029/Veltrix-DomotiCore-Front-End)
* **Platform**: Vercel
* **Deployment URL**: [https://veltrix-domoticore-front-end.vercel.app/](https://veltrix-domoticore-front-end.vercel.app/)

### 5.1.4.3 Backend Web Services Deployment

Los servicios de lógica de negocio y conectividad IoT se despliegan en **Render**, permitiendo la exposición de endpoints seguros bajo el protocolo HTTPS para la comunicación con los dispositivos.

* **Repository**: [Veltrix-DomotiCore-Back-end](https://github.com/BL-App-Open-Source-1ASI0729-2610-12029/Veltrix-DomotiCore-Back-end)
* **Platform**: Render
* **Deployment URL**: [https://veltrix-domoticore-back-end.onrender.com](https://veltrix-domoticore-back-end.onrender.com)

### 5.1.4.4 OpenAPI Documentation

Para facilitar la integración entre el frontend y el backend, la documentación de la API se publica automáticamente mediante **Swagger UI**, permitiendo la visualización y prueba interactiva de los endpoints REST.

* **Documentation URL**: [Veltrix-domoticore-back-end](https://veltrix-domoticore-back-end.onrender.com/swagger-ui.html)

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

| Team Member (Last Name, First Name) | GitHub Username | Infrastructure & Repository | Landing Page Development | Documentation (Chapters 1-5) |
| :--- | :--- | :---: | :---: | :---: |
| Checa, Oscar | OscarCheca | **C** | **C** | **C** |
| Quispe, Cesar | user20-bit | **C** | **L** | **L** |
| Esquich, Diego | DiegoEsquich | **L** | **C** | **C** |
| Tello, Fabrizio | F4bris | **C** | **C** | **C** |
| Rocha , Alvaro | alvarorc24 | **C** | **C** | **C** |

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

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| OscarCheca/domoticore-landing | main | faa7045 | add index.html | Initial commit with index.html for the landing page structure. | 25/04/2026 |
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

Durante el Sprint 1, el enfoque principal del equipo fue el desarrollo e implementación de la Landing Page. Sin embargo, se logró implementar correctamente componentes funcionales en el frontend, como la navegación interactiva, diseño responsive y validación básica del formulario de contacto. La documentación de servicios más complejos se vera en las siguientes sprints, donde se integrarán funcionalidades relacionadas con la gestión de dispositivos IoT, automatización y monitoreo en tiempo real.

## 5.2.1.7. Software Deployment Evidence for Sprint Review

En este sprint, el despliegue del software se limitó a la publicación de la Landing Page de DomotiCore mediante el uso de GitHub Pages. Dado que aún no se ha desarrollado una aplicación web completa ni servicios backend, no se cuenta con evidencia de despliegue de sistemas más complejos en esta fase del proyecto. En futuros sprints, se incluirán evidencias más completas relacionadas con el despliegue de la aplicación, incluyendo integración de servicios, infraestructura y entornos de producción.

## 5.2.1.8. Team Collaboration Insights during Sprint

Los analíticos que nos proporciona Github, en su apartado de Insights, sobre la colaboración del equipo durante el Sprint 1:

<div style="text-align:center;"><img src="imagenes/images_Cap5/5.2.1.8. Team Collaboration.png"


## Bibliografía

- Samuel Greengard, S. (2015). The Internet of Things. MIT Press.
International Telecommunication Union. (2012). Overview of the Internet of Things (Recommendation ITU-T Y.2060). https://www.itu.int

- World Energy Council. (2020). Energy efficiency indicators. https://www.worldenergy.org

## Conclusiones

1. El desarrollo del proyecto permitió integrar de manera coherente herramientas como User Stories, wireframes y control de versiones con Git, logrando una base sólida tanto a nivel de análisis como de implementación.

2. Asimismo, se evidenció la importancia de una comunicación clara, tanto escrita como visual, para transmitir efectivamente las ideas del proyecto a distintos tipos de audiencia, facilitando la comprensión y el trabajo colaborativo.

## Anexos

**Video  de exposición**

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113310_upc_edu_pe/IQBB-A5V0F11So9iWE7DqDgoAcl3ZIcmUBVMwC_-fOgFkK0?e=bgWP1d&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

