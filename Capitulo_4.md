# Capítulo IV: Product Design

## 4.1 Style Guidelines

El diseño de la plataforma se enfoca en ofrecer una interfaz intuitiva que facilite la exploración, selección y contribución de manera visual en DomotiCore. Se busca garantizar una experiencia fluida para desarrolladores de distintos niveles.

La plataforma está pensada para manejar múltiples proyectos, usuarios y contribuciones de forma organizada, manteniendo un entorno accesible, escalable y centrado en la colaboración.

### 4.1.1 General Style Guidelines

En este apartado se detallan las decisiones de estilo que definen la identidad visual de la plataforma, orientada a conectar desarrolladores con proyectos y facilitar su participación en tareas reales. Las decisiones relacionadas con branding, tipografía, colores, espaciado y lenguaje buscan transmitir accesibilidad, colaboración, claridad y dinamismo, elementos clave dentro de comunidades tecnológicas.

***Colores***

<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/color-palette.png" 
       alt="texto">
</div>

La paleta de colores fue seleccionada con un enfoque en la claridad visual, dinamismo y jerarquía de información. Cada color cumple un rol específico dentro de la plataforma:

**Paleta de Colores**

- **Azul primario – #1E40AF:**  
  Representa tecnología, confianza y comunidad. Se utiliza en botones principales, enlaces y elementos interactivos clave como “Contribuir” o “Explorar proyectos”.

- **Gris oscuro – #475569:**  
  Transmite estabilidad y estructura. Se emplea en textos principales, fondos de navegación y componentes base del sistema.

- **Verde acento – #882D00:**  
  Representa éxito y progreso. Se utiliza en indicadores de contribución, confirmaciones y estados positivos dentro del sistema.

- **Gris claro – #64748B:**  
  Simboliza neutralidad. Se utiliza en textos secundarios, bordes y elementos de soporte para mantener equilibrio visual.

**Escalas de color:**  
Cada color cuenta con variaciones de intensidad que permiten diferenciar estados (hover, activo, deshabilitado), jerarquías y organización visual dentro de dashboards y listados de proyectos.

***Tipografía***

<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/inter-font.png"
       alt="texto">
</div>

Se selecciona una tipografía sans-serif moderna como **Inter o Roboto**, debido a su alta legibilidad en entornos digitales.

Esta tipografía permite una lectura clara en interfaces con alta densidad de información, como listados de proyectos, issues y dashboards de contribución.

En cuanto al tamaño:

- Títulos: mayor tamaño y peso (negrita)  
- Subtítulos: tamaño intermedio  
- Texto: tamaño estándar para facilitar la lectura  

Esto permite resaltar información clave y mejorar la comprensión del usuario.

***Branding***

<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/logo-DomotiCore.png"
       alt="texto">
</div>

El branding de la plataforma está orientado a reflejar **colaboración, accesibilidad y comunidad tecnológica**.

Se adopta un enfoque minimalista con:

- Íconos simples relacionados al desarrollo (código, repositorios, bugs)
- Uso moderado de colores
- Diseño limpio y ordenado

Esto permite transmitir una imagen moderna y alineada con el ecosistema Open Source.

***Espaciado***

El diseño se centra en el uso estratégico de espacios en blanco para mejorar la legibilidad y organización.

El contenido se organiza en:

- Tarjetas (cards) para proyectos  
- Listas estructuradas para issues  
- Secciones bien separadas  

Los márgenes y rellenos permiten evitar la saturación visual y facilitan la navegación, especialmente en pantallas con mucha información.

***Dimensiones para el tono de comunicación y lenguaje aplicado***

El tono de comunicación de la plataforma es **claro, directo y accesible**, orientado a desarrolladores de distintos niveles, incluyendo principiantes.

Se busca:

- Evitar lenguaje excesivamente técnico  
- Facilitar la comprensión rápida  
- Motivar la participación  

El sistema utiliza mensajes como:

- “Empieza a contribuir”  
- “Encuentra tu primer issue”  
- “Explora proyectos”  

Esto genera una experiencia amigable y fomenta la interacción.

*****Aspectos clave del diseño*****

**Consistencia:**  
Todos los elementos mantienen una línea gráfica uniforme, permitiendo que el usuario se familiarice rápidamente con la plataforma.

**Navegación:**  
Se estructura de forma intuitiva, permitiendo acceder fácilmente a proyectos, issues y perfil de usuario.

**Accesibilidad:**  
Se prioriza una interfaz clara, con buen contraste, adaptable a distintos dispositivos.

***Elementos de Diseño***

El diseño visual considera elementos fundamentales:

- **Línea:** separa secciones y organiza contenido  
- **Color:** comunica estados y acciones  
- **Tamaño:** establece jerarquía visual  
- **Espacio:** evita saturación y mejora la lectura  
- **Formas:** botones redondeados, tarjetas organizadas  

Estos elementos contribuyen a una experiencia clara y eficiente.

### 4.1.2 Web Style Guidelines

La plataforma será desarrollada como una aplicación web adaptable (Responsive Web Design), permitiendo su uso en distintos dispositivos como laptops, tablets y smartphones.

Esto garantiza que los usuarios puedan explorar proyectos y contribuir desde cualquier entorno.

Se implementarán:

- Layouts basados en grid  
- Componentes reutilizables  
- Diseño adaptable  

Además, se prioriza el uso de dashboards y vistas estructuradas para mostrar:

- Proyectos recomendados  
- Issues disponibles  
- Actividad del usuario  

El diseño dirige la atención del usuario hacia acciones clave como explorar, seleccionar y contribuir.

## 4.2. Information Architecture

La arquitectura de la información de la plataforma se centra en facilitar la exploración eficiente de proyectos y identificar las oportunidades de contribución. Se prioriza que el usuario pueda comprender el ecosistema de proyectos, evaluar su nivel de dificultad y acceder a tareas concretas sin fricción.

El diseño de la información está orientado a guiar al usuario desde la exploración inicial hasta la contribución, manteniendo una estructura clara, escalable y alineada con las dinámicas reales del desarrollo colaborativo.

### 4.2.1 Organization Systems

En la plataforma se emplea principalmente una **organización jerárquica**, en la cual los elementos más relevantes para el usuario, como proyectos recomendados, issues destacados y oportunidades de contribución inmediata, se presentan con mayor prioridad visual dentro de la interfaz. Esta jerarquía permite que los desarrolladores identifiquen rápidamente dónde pueden participar, especialmente en el caso de usuarios principiantes que buscan su primera experiencia en Open Source.

Asimismo, se aplica una **organización por categorización temática**, estructurando los proyectos según criterios como lenguaje de programación, tipo de tecnología, nivel de dificultad y tipo de contribución (bug, feature, documentación). Esta clasificación facilita la navegación y permite que los usuarios filtren contenido de acuerdo con sus intereses, habilidades y objetivos de aprendizaje.

De igual manera, se incorpora una **organización secuencial** en ciertos flujos clave del sistema, como el proceso de contribución. Este proceso guía al usuario paso a paso desde la selección de un proyecto, revisión de issues, comprensión de la tarea, hasta la ejecución de la contribución. Esta estructura reduce la complejidad del proceso y mejora la experiencia, especialmente para desarrolladores con poca experiencia en entornos colaborativos.

En cuanto a la organización temporal, la plataforma utiliza un enfoque **cronológico** para mostrar la actividad reciente, incluyendo nuevas issues, contribuciones recientes y actualizaciones de proyectos. Esto permite a los usuarios mantenerse informados sobre la evolución del ecosistema y detectar oportunidades activas de participación.

Finalmente, la información también se organiza considerando el **perfil del usuario**, adaptando recomendaciones y contenido según su nivel (principiante, intermedio o avanzado), historial de contribuciones e intereses tecnológicos. Esto permite una experiencia más personalizada y eficiente.

### 4.2.2 Labeling Systems

Se prioriza el uso de etiquetas cortas, precisas y comprensibles, con el objetivo de reducir la carga cognitiva del usuario y facilitar la navegación dentro del sistema.

***Landing Page***

- **Inicio:** Sección principal que presenta la plataforma y su propuesta de valor, orientada a motivar la participación en proyectos Open Source.
- **Explorar Proyectos:** Acceso directo al catálogo de proyectos disponibles para contribuir.
- **Cómo Contribuir:** Guía paso a paso para nuevos usuarios que desean iniciarse en el mundo Open Source.
- **Beneficios:** Explicación de las ventajas de participar en proyectos colaborativos (aprendizaje, experiencia, networking).
- **Contacto:** Canal de comunicación para soporte o consultas.

***Aplicación Web – Desarrolladores***

- **Dashboard:** Vista general con recomendaciones personalizadas, actividad reciente y progreso del usuario.
- **Proyectos:** Listado de proyectos disponibles, con filtros por tecnología, dificultad y tipo de contribución.
- **Issues:** Visualización de tareas disponibles dentro de los proyectos, clasificadas por tipo y nivel.
- **Mis Contribuciones:** Historial de participación del usuario en proyectos Open Source.
- **Perfil:** Información personal, habilidades y estadísticas de contribución.
- **Configuración:** Ajustes de cuenta y preferencias.

***Etiquetas comunes dentro del sistema***

- **Beginner-friendly:** Issues adecuados para principiantes  
- **Bug:** Problemas o errores a resolver  
- **Feature:** Nuevas funcionalidades  
- **Documentation:** Tareas relacionadas con documentación  
- **High Priority:** Issues prioritarios  

Estas etiquetas permiten clasificar la información de manera eficiente y facilitar la toma de decisiones del usuario.

### 4.2.3 SEO Tags and Meta Tags

Para asegurar que la plataforma *DomotiCore*, sea funcional, se han configurado los siguientes meta tags técnicos. Estos permiten posicionar la solución como una plataforma de domótica orientada al control inteligente de dispositivos electrónicos en hogares y pequeñas empresas.

* **Title Tag:** en html:  
    `<title>DomotiCore | Plataforma de Domótica para Control Inteligente de Dispositivos IoT</title>`

* **Description:** en html:  
    `<meta name="description" content="Gestiona, monitorea y automatiza tus dispositivos electrónicos con DomotiCore. Plataforma web IoT que permite control en tiempo real, ahorro energético y mayor seguridad para hogares y pequeñas empresas.">`

* **Keywords:** en html:  
    `<meta name="keywords" content="Domótica, IoT, Control de dispositivos, Automatización del hogar, Smart Home, Veltrix, Plataforma web, Energía inteligente, Seguridad doméstica">`

* **Open Graph (Optimización para redes sociales):**
    * `<meta property="og:title" content="DomotiCore: Control inteligente y automatización de tu hogar o negocio">`

    * `<meta property="og:description" content="Centraliza y automatiza tus dispositivos electrónicos con tecnología IoT. Mejora la eficiencia energética, seguridad y comodidad con DomotiCore.">`

    * `<meta property="og:image" content="https://veltrix.com/assets/domoticore-preview.png">`

    * `<meta property="og:url" content="https://veltrix.com/domoticore">`

* **Robots:** en html:  
    `<meta name="robots" content="index, follow">`

### 4.2.4 Searching Systems

Dado que la plataforma puede manejar múltiples dispositivos electrónicos, sensores y reglas automatizadas, se han implementado mecanismos de búsqueda y filtrado que permiten acceder de manera directa a la información crítica.

**Barra de Búsqueda Global:**  
Ubicada en la parte superior del dashboard, permite realizar búsquedas rápidas por:

- Nombre del dispositivo (“Luz Sala”, “Sensor Puerta”)  
- Tipo de dispositivo (luces, cámaras, enchufes inteligentes, sensores)  
- Ubicación (sala, cocina, oficina, etc.)  
- Nombre de automatizaciones configuradas  

Esto permite al usuario ubicar rápidamente cualquier elemento dentro de su red de dispositivos.

**Filtros Inteligentes:**  
En los módulos de dispositivos y automatización, los usuarios pueden segmentar la información mediante:
- Estado del dispositivo (Encendido, Apagado, Desconectado)  
- Tipo de dispositivo (sensor, actuador, cámara, etc.)  
- Nivel de consumo energético  
- Estado de automatización (activa o inactiva)  

Estos filtros permiten visualizar únicamente la información relevante según el contexto del usuario.

**Búsqueda por eventos y actividad:**  
El sistema permite consultar registros históricos como:
- Activaciones de dispositivos  
- Ejecución de automatizaciones  
- Alertas generadas por sensores  

Esto facilita el monitoreo y análisis del comportamiento del sistema.

**Búsqueda contextual:**  
Dentro de cada módulo (dispositivos, automatización, historial), el usuario puede realizar búsquedas específicas relacionadas únicamente con ese entorno, mejorando la precisión y reduciendo la complejidad.

### 4.2.5 Navigation Systems

Se busca que el usuario nunca esté a más de tres interacciones de realizar una acción clave, como encender un dispositivo, configurar una automatización o revisar una alerta.

**Navegación Global (Menú principal):**  
Se implementa mediante un menú lateral o superior persistente que permite acceso directo a los módulos principales del sistema:

- Dashboard: Vista general del estado de los dispositivos, consumo energético y alertas  
- Dispositivos: Gestión y control de todos los dispositivos conectados  
- Automatización: Configuración de reglas, horarios y acciones automáticas  
- Historial: Registro de eventos y actividad del sistema  
- Perfil / Configuración: Gestión de usuario, preferencias y seguridad  

Esta estructura permite una navegación clara y consistente en toda la plataforma.

**Navegación de Contexto:**  
Permite al usuario ubicarse dentro de la plataforma mediante rutas como:

Dispositivos > Sala > Luz Principal  

Automatización > Rutina Nocturna > Configuración  

Esto facilita la orientación y comprensión de la ubicación actual dentro del sistema.

**Navegación Local:**  
Dentro de cada módulo se utilizan pestañas o secciones para acceder a funcionalidades específicas, por ejemplo:

- Información del dispositivo  
- Estado en tiempo real  
- Configuración  
- Consumo energético  

Esto permite organizar la información sin sobrecargar la interfaz.

**Acciones Rápidas:**  
Se incorporan botones visibles y accesos directos para acciones frecuentes como:

- Encender / apagar dispositivos  
- Activar automatizaciones  
- Crear nueva regla  
- Configurar horarios  

Estas acciones están diseñadas para minimizar el número de pasos y mejorar la experiencia del usuario.

**Navegación adaptativa (Responsive):**  
La interfaz se adapta a distintos dispositivos (desktop, tablet, móvil), reorganizando los elementos de navegación para mantener la usabilidad en cualquier entorno, permitiendo el control remoto en tiempo real desde cualquier lugar.

## 4.3 Landing Page UI Design

### 4.3.1 Landing Page Wireframe.

La landing page de DomotiCore presenta una estructura clara y orientada a la conversión, iniciando con una sección principal que introduce la solución como una plataforma IoT capaz de centralizar y automatizar el control de dispositivos eléctricos, resaltando beneficios como el monitoreo en tiempo real, el ahorro energético y la facilidad de uso sin conocimientos técnicos. A continuación, la sección “Nosotros” contextualiza el proyecto, destacando su origen como iniciativa de estudiantes peruanos y su enfoque en brindar soluciones accesibles y sostenibles para hogares y pequeñas empresas.

Seguidamente, la sección de “Funciones” describe las capacidades clave del sistema, incluyendo el control remoto de dispositivos, la programación automatizada, el monitoreo del consumo energético, las alertas inteligentes y la gestión de usuarios, evidenciando un enfoque integral en eficiencia y seguridad. Posteriormente, en “Plataforma”, se muestra una representación del dashboard, donde se visualiza la organización de dispositivos, métricas de consumo y estados en tiempo real, reforzando la idea de una interfaz intuitiva y fácil de utilizar.

Más adelante, la sección “¿Cómo funciona?” explica de manera secuencial el proceso de uso del sistema, desde la conexión inicial del gateway hasta la automatización completa del entorno, simplificando la adopción tecnológica para el usuario. Asimismo, se incluyen testimonios que respaldan la propuesta de valor mediante experiencias reales enfocadas en el ahorro energético y la practicidad del sistema.

Finalmente, la landing concluye con una sección de contacto que integra un formulario y canales directos de comunicación, permitiendo a los usuarios solicitar información o una demostración del producto, reforzando el enfoque comercial y de acompañamiento al cliente.

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-landing/wireframe-1.png" alt="texto"></div>
<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-landing/wireframe-2.png" alt="texto"></div>
<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-landing/wireframe-3.png" alt="texto"></div>
<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-landing/wireframe-4.png" alt="texto"></div>
<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-landing/wireframe-5.png" alt="texto"></div>

### 4.3.2 Landing Page Mock-up.

El wireframe de la landing page en su versión de escritorio ha permitido organizar de forma clara y jerárquica los elementos principales de DomotiCore, facilitando la presentación de la propuesta de valor centrada en el control y automatización de dispositivos eléctricos. A partir de esta estructura inicial, se desarrolló el mockup de la interfaz, manteniendo coherencia con las funcionalidades definidas, como el monitoreo en tiempo real, la gestión remota, las alertas inteligentes y la visualización del consumo energético.

En la implementación final se puede apreciar el uso consistente de la paleta de colores basada en tonos azules y neutros, así como la tipografía moderna seleccionada, lo que contribuye a una estética limpia y tecnológica. Además, la distribución de secciones como el dashboard de vista previa, las funcionalidades y el flujo de uso refuerzan la claridad y usabilidad del producto. En conjunto, el diseño refleja una identidad visual alineada con los valores de accesibilidad, eficiencia e innovación, transmitiendo confianza y facilidad de uso tanto para hogares como para pequeñas empresas.

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/mockup-landing/mockup-1.png" alt="texto"></div>
<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/mockup-landing/mockup-2.png" alt="texto"></div>
<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/mockup-landing/mockup-3.png" alt="texto"></div>
<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/mockup-landing/mockup-4.png" alt="texto"></div>
<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/mockup-landing/mockup-5.png" alt="texto"></div>

## 4.4. Web Applications UX/UI Design

### 4.4.1 Web Applications Wireframes

**Wireframes Versión Desktop - Usuarios de Hogares Inteligentes** 

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-smart-home-users-web/wireframe-devices-control.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-smart-home-users-web/wireframe-dashboard.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-smart-home-users-web/wireframe-energy-monitoring.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-smart-home-users-web/wireframe-device-details-ac.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-smart-home-users-web/wireframe-smart-automations.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-smart-home-users-web/wireframe-history-log.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-smart-home-users-web/wireframe-notifications-center.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-smart-home-users-web/wireframe_security_access.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-smart-home-users-web/wireframe-automation-builder.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-smart-home-users-web/wireframe-settings.png" alt="texto"></div>

**Wireframes Versión Desktop - Pequeños Negocios y Emprendedores**

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-small-business-web/wireframe_device_explorer.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-small-business-web/wireframe_business_integration_settings.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-small-business-web/wireframe_sme_alert_history.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-small-business-web/wireframe_device_explorer.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-small-business-web/wireframe_cost_deep_dive.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-small-business-web/wireframe_team_management.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-small-business-web/wireframe_business_automations.png" alt="texto"></div>

<div style="text-align:center;"><img src="imagenes/imagenes_Cap4/wireframes-small-business-web/wireframe_bulk_device_management.png" alt="texto"></div>

### 4.4.2 Web Applications Wireflow Diagrams

**Wireflow Versión Desktop - Usuarios de Hogares Inteligentes**

**El usuario puede ingresar al home de la aplicación web**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-smart-home-users-web/wireflow-dashboard-web.png"
       alt="Dashboard">

**El usuario puede ingresar a security**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-smart-home-users-web/wireflow-security-web.png"
       alt="Security">

**El usuario puede ingresar a settings**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-smart-home-users-web/wireflow-settings-web.png"
       alt="Settings">

**El usuario puede ingresar a devices**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-smart-home-users-web/wireflow-devices-web.png"
       alt="Devices">

**El usuario puede revisar la habitación que ha seleccionado para monitorear sus dispositivos**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-smart-home-users-web/wireflow-room-selected-web.png"
       alt="Room selected">

**El usuario puede ingresar a Smart Automations**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-smart-home-users-web/wireflow-smart-automations-web.png"
       alt="Smart Automations">

**El usuario puede añadir a new automation**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-smart-home-users-web/wireflow-new-automation-web.png"
       alt="New Automation">

**El usuario puede ingresar a history**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-smart-home-users-web/wireflow-history-web.png"
       alt="History">

**El usuario puede ingresar tanto a la sección de Notifications y a su History Log**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-smart-home-users-web/wireflow-notifications-history-log-web.png"
       alt="Notifications">

**Wireflow Versión Desktop - Pequeños Negocios y Emprendedores**

**El usuario puede ingresar a la pantalla principal**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-small-business-web/wireflow-automation-center-web.png"
       alt="Automatization center">

**El usuario puede dirigirse a Users y gestionar diversas acciones como Business Profile & API Settings**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-small-business-web/wireflow-users-action-web.png"
       alt="Users action">

**El usuario puede dirigirse a Reports y gestionar diversas acciones como Cost Analysis Details**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-small-business-web/wireflow-reports-action-web.png"
       alt="Reports action">

**El usuario puede dirigirse a Devices y gestionar diversas acciones como Device Explorer**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/wireflows-small-business-web/wireflow-devices-action-web.png"
       alt="Devices action">

### 4.4.3 Web Applications Mock-ups

**Versión Desktop Mockups - Usuarios de Hogares Inteligentes** 

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-smart-home-users-web/dashboard-domoticore.png"
       alt="Dashboard "></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-smart-home-users-web/energy-monitoring-domoticore.png"
       alt="Energy Monitoring"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-smart-home-users-web/devices-domoticore.png"
       alt="Devices "></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-smart-home-users-web/automation-domoticore.png"
       alt="Automation"></div>
    
  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-smart-home-users-web/device-details-ac-domoticore.png"
       alt="Device Details"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-smart-home-users-web/security-access-domoticore.png"
       alt="Security & Access"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-smart-home-users-web/history-log-domoticore.png"
       alt="History Log "></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-smart-home-users-web/notifications-domoticore.png"
       alt="Notifications "></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-smart-home-users-web/settings-domoticore.png"
       alt="Settings "></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-smart-home-users-web/automation-builder-domoticore.png"
       alt="Automation Builder"></div>

**Versión Desktop Mockups - Pequeños Negocios y Emprendedores** 

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-small-business-web/sme-dashboard.png"
       alt="Dashboard"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-small-business-web/business-automations.png"
       alt="Business Automations"></div>
  
  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-small-business-web/energy-reports.png"
       alt="Energy Reports"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-small-business-web/bulk-device-management.png"
       alt="Device Management"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-small-business-web/team-management.png"
       alt="Team Management"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-small-business-web/zone-configuration.png"
       alt="Zone Configuration"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-small-business-web/cost-deep-dive.png"
       alt="Cost Deep-Dive"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-small-business-web/sme-alert-history.png"
       alt="Alert History"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-small-business-web/full-device-inventory.png"
       alt="Device Inventory"></div>

  <div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/mockups-small-business-web/business-integration-settings.png"
       alt="Business Integration Settings"></div>
       
### 4.4.4 Web Applications User Flow Diagrams

**User Flow Versión Desktop - Usuarios de Hogares Inteligentes**

**El usuario se encuentra en la pantalla principal, en Dashboard**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-smart-home-users-web/userflow-dashboard-web.png"
       alt="Dashboard">

**El usuario se dirige a la sección de Security**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-smart-home-users-web/userflow-security-web.png"
       alt="Security">

**El usuario se dirige a la sección de Settings**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-smart-home-users-web/userflow-settings-web.png"
       alt="Settings">

**El usuario se dirige a la sección de Devices y puede acceder a revisar sus habitaciones**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-smart-home-users-web/userflow-devices-web.png"
       alt="Devices">

**El usuario se dirige a la sección de Automations y puede darle a New Automation**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-smart-home-users-web/userflow-automations-web.png"
       alt="Automation">

**El usuario se dirige a la sección de History**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-smart-home-users-web/userflow-history-web.png"
       alt="History">

**El usuario puede presionar Notifications Center o puede dirigirse a History Log**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-smart-home-users-web/userflow-notifications-history-log-web.png"
       alt="Notifications">

**User Flow Versión Desktop - Pequeños Negocios y Emprendedores**

**El usuario ingresa a la pantalla principal, Dashboard**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-small-business-web/userflow-dashboard-web.png"
       alt="Dashboard">

**El usuario se dirige a la sección de Automation y con esta sus gestiones**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-small-business-web/userflow-automation-actions-web.png"
       alt="Automations">

**El usuario se dirige a la sección de Reportes y con esta sus gestiones**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-small-business-web/userflow-reports-actions-web.png"
       alt="Reports">

**El usuario se dirige a la sección de Alerts & History**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-small-business-web/userflow-alerts-history-web.png"
       alt="Alerts & History">

**El usuario se dirige a la sección de Devices y con esta sus gestiones**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-small-business-web/userflow-devices-actions-web.png"
       alt="Devices">

**El usuario se dirige a la sección de Users y con esta sus gestiones**
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/userflows-small-business-web/userflow-users-actions-web.png"
       alt="Users">

## 4.5. Web Applications 

**En esta sección se presentan los prototipos de la aplicación web, tanto para navegador de escritorio como para navegador móvil, los cuales permiten simular la interacción y navegación del usuario dentro del sistema. Estos prototipos están directamente basados en los User Flow Diagrams, asegurando que los recorridos diseñados puedan ser experimentados de forma visual y práctica.**

**Las decisiones de interacción se tomaron priorizando la facilidad de uso, la claridad en la navegación y la rapidez para completar tareas clave, como la gestión de pedidos, el control de inventario y la revisión de información relevante. Se buscó que el usuario pueda entender intuitivamente qué hacer en cada pantalla, reduciendo la cantidad de pasos innecesarios y proporcionando retroalimentación visual ante cada acción realizada.**

**Estos prototipos permiten validar la experiencia del usuario antes de la implementación, facilitando la detección temprana de oportunidades de mejora y asegurando que el diseño esté alineado con las necesidades reales de los usuarios y los objetivos del proyecto.**

## 4.6. Domain-Driven Software Architecture

**Se enfoca en la organización de la lógica del software, la delimitación de contextos y el uso de diagramas.**

### 4.6.1 Design-Level EventStorming

**Se presenta a continuación el Event Storming correspondiente a DomotiCore, donde se han identificado los principales eventos del dominio, así como los actores involucrados, acciones, decisiones, reglas de negocio y las interacciones entre los distintos componentes del sistema. Como resultado de este análisis, se definieron 10 bounded contexts:**

Global
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/Global.png"
       alt="Global">

*Leyenda*
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/Leyenda.png"
       alt="Leyenda">

**Gateway Management:**

Gestiona la vinculación, estado y conectividad del gateway Veltrix, permitiendo establecer el puente entre los dispositivos físicos y la nube de DomotiCore.
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/gateway-management.png"
       alt="Gateway Management">

**Device Management:**

Administra el registro, organización y configuración básica de los dispositivos inteligentes asociados a un gateway dentro del hogar o negocio.
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/device-management.png"
       alt="Device Management">

**Device Control:**

Permite el control remoto en tiempo real de los dispositivos, gestionando acciones como encendido, apagado y cambios de estado desde la plataforma.
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/device-control.png"
       alt="Device Control">

**Automation & Scenes:**

Gestiona reglas automáticas y escenas que permiten ejecutar acciones sobre múltiples dispositivos según horarios, condiciones o eventos definidos.
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/automation-scenes.png"
       alt="Automation & Scenes">

**Energy Monitoring:**

Registra, analiza y visualiza el consumo energético de los dispositivos, brindando información en tiempo real e histórica para la toma de decisiones.
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/energy-monitoring.png"
       alt="Energy Monitoring">

**Notifications:**

Administra el envío de alertas y notificaciones automáticas ante eventos relevantes como consumos inusuales, dispositivos desconectados o acciones críticas.
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/notifications.png"
       alt="Notifications">

**IAM (User & Access Management):**

Gestiona usuarios, roles y permisos, asegurando un acceso controlado y seguro a las funcionalidades del sistema según el tipo de usuario.
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/user-access-management.png"
       alt="User & Access Management">

**Smart Integrations:**

Permite la conexión y sincronización con servicios o plataformas externas para ampliar las capacidades del ecosistema DomotiCore.
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/smart-integrations.png"
       alt="Smart Integrations">

**Analytics & Dashboard:**

Consolida información clave del sistema en dashboards y métricas visuales que facilitan la supervisión general del hogar o negocio.

<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/analytics-dashboard.png"
  alt="Analytics & Dashboard">

**History & Audit:**

Registra y conserva el historial de acciones, estados y eventos del sistema para fines de trazabilidad, control y auditoría.
<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/EventStorming/history-audit.png"
       alt="History & Audit">

### 4.6.2 Software Architecture Context Diagram

<a id="4-6-2-software-architecture-context-diagram"></a>

El Diagrama de Contexto representa la vista de más alto nivel de **DomotiCore**, detallando cómo el sistema interactúa con los usuarios y sistemas externos sin profundizar en detalles técnicos.

***Sistema Central***

- **DomotiCore**: Plataforma IoT para la gestión, monitoreo y automatización de dispositivos inteligentes en hogares y pequeños negocios.

****Usuarios****

***Smart Home Users***
- Controlan dispositivos inteligentes del hogar.
- Monitorean consumo energético en tiempo real.
- Configuran automatizaciones del hogar.

***Small Business Owners***
- Gestionan dispositivos IoT en pequeños negocios.
- Supervisan consumo energético para optimización de costos.
- Automatizan procesos eléctricos y de seguridad.

***Sistemas Externos***
- **MQTT Broker (Servicio de Mensajería IoT)**  
  Encargado de la comunicación en tiempo real con dispositivos IoT.

- **Firebase Authentication (Servicio de Identidad)**  
  Responsable de la autenticación y gestión de usuarios.

- **Firebase Firestore (Servicio de Base de Datos)**  
  Almacena información de usuarios, dispositivos y automatizaciones.

- **Firebase Cloud Messaging (Servicio de Notificaciones)**  
  Maneja el envío de notificaciones push.

***Resumen de Interacción***
- Los usuarios (**Smart Home Users** y **Small Business Owners**) interactúan directamente con **DomotiCore**.
- **DomotiCore** delega:
  - Autenticación a Firebase Authentication.
  - Mensajería IoT a MQTT Broker.
  - Persistencia de datos a Firebase Firestore.
  - Notificaciones a Firebase Cloud Messaging.

![Context-Diagram](imagenes/imagenes_Cap4/software-arquitecture-diagrams/context-diagram.png)

### 4.6.3 Software Architecture Container Diagrams

<a id="4-6-3-software-architecture-container-diagrams"></a>

Este nivel desglosa el sistema **DomotiCore** en aplicaciones independientes, especificando las tecnologías de desarrollo empleadas.

***Web Application***

Aplicación desarrollada con **HTML, CSS y JavaScript**, la cual ofrece una interfaz de usuario responsiva y dinámica.  
Se comunica con el backend mediante peticiones asíncronas sobre **HTTPS**.

***API Application***

Construida en **Node.js** utilizando **Express**.  
Este componente actúa como el núcleo del sistema, encargado de:

- Procesar la lógica de negocio IoT  
- Gestionar dispositivos y automatizaciones  
- Exponer endpoints RESTful  
- Integrarse con servicios externos  

***Database***

Motor de base de datos basado en **Firebase Firestore**, responsable de la persistencia de datos.  
Garantiza:

- Integridad de la información  
- Consistencia de datos en tiempo real  
- Escalabilidad del sistema IoT  

![Container-Diagram](imagenes/imagenes_Cap4/software-arquitecture-diagrams/container-diagram.png)

***

### 4.6.4 Software Architecture Components Diagrams

<a id="4-6-4-software-architecture-components-diagrams"></a>

Este nivel descompone el contenedor principal de la **API Application** en componentes internos responsables de la lógica de negocio, monitoreo IoT, automatización y gestión de datos dentro de **DomotiCore**.

***1. Gateway Management***
- Gestiona la vinculación, estado y conectividad del gateway Veltrix en la plataforma.
- Permite establecer de forma segura el puente de comunicación entre los dispositivos físicos locales y la nube de DomotiCore.
- Monitorea la estabilidad de la red y el aprovisionamiento inicial de los Hubs centrales.

***2. Device Management***
- Administra el registro, organización estructural (por ambientes u hogares) y configuración básica de los dispositivos inteligentes asociados a un gateway.
- Controla el inventario lógico de sensores y actuadores vinculados por el usuario dentro de su entorno residencial o comercial.

***3. Device Control***
- Permite el control remoto interactivo y en tiempo real de los dispositivos inteligentes integrados.
- Gestiona la transmisión e interpretación inmediata de comandos operativos críticos como encendido, apagado, regulación y cambios de estado desde la interfaz web.

***4. Automation & Scenes***
- Gestiona las reglas automáticas personalizadas y la creación de escenas complejas en el ecosistema.
- Permite ejecutar acciones concurrentes sobre múltiples dispositivos IoT de forma síncrona basándose en horarios fijos, condiciones lógicas o eventos ambientales definidos.

***5. Energy Monitoring***
- Registra, analiza y procesa métricas de consumo energético provenientes de los nodos de medición eléctrica acoplados.
- Brinda información analítica detallada tanto en tiempo real como histórica para facilitar la toma de decisiones enfocadas en la eficiencia.

***6. Notifications***
- Administra el ciclo completo de envío de alertas automáticas y notificaciones prioritarias del sistema.
- Despacha advertencias inmediatas ante eventos relevantes del entorno como picos de consumo inusuales, dispositivos desconectados de la red o ejecuciones críticas de seguridad.

***7. IAM (User & Access Management)***
- Gestiona las cuentas de usuarios, perfiles operativos, asignación de roles y control de directivas de seguridad.
- Asegura un acceso controlado, cifrado y totalmente restringido a las funcionalidades de administración del sistema según el tipo de usuario (hogar o pyme).

***8. Smart Integrations***
- Maneja la capa de abstracción, conexión y sincronización nativa con servicios, APIs o plataformas domóticas externas.
- Permite expandir el alcance y las capacidades de interoperabilidad del ecosistema global de DomotiCore con terceros.

***9. Analytics & Dashboard***
- Consolida y procesa la información clave recopilada de todo el entorno inteligente para estructurar métricas visuales inteligibles.
- Alimenta los dashboards interactivos facilitando una supervisión gerencial e intuitiva sobre el estado del hogar o negocio.

***10. History & Audit***
- Registra, secuencia y conserva de forma estructurada el historial completo de acciones de usuarios, cambios de estado físicos y eventos del sistema.
- Provee un registro inmutable orientado a fines de trazabilidad operativa, auditoría de seguridad y control retroactivo.


![Components-Diagram](imagenes/imagenes_Cap4/software-arquitecture-diagrams/components-diagram.png)

***

## 4.7 Software Object-Oriented Design

En esta sección se presenta el diseño orientado a la solución, desarrollado a partir de los requerimientos funcionales, User Stories, User Task Matrix, eventos identificados durante el proceso de análisis del dominio. El objetivo de este diseño es representar la estructura lógica del sistema mediante diagramas que describen las principales entidades, relaciones y comportamientos involucrados en la plataforma de automatización y monitoreo energético.

La solución fue modelada considerando un enfoque basado en bounded contexts, permitiendo organizar las responsabilidades del sistema en módulos funcionales relacionados con la gestión de usuarios, administración de dispositivos IoT, automatización, monitoreo energético y notificaciones inteligentes. Cada diagrama incluye clases, atributos, métodos, relaciones, multiplicidades y niveles de acceso. Para la elaboración de los diagramas se utilizará PlantUML.

### 4.7.1 Class Diagrams

<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/Class-diagrams/Domoticore.svg"
       alt="texto">
</div>

- El diseño orientado a objetos fue organizado segunlas relaciones con gestión de usuarios, administración de dispositivos, automatización inteligente, monitoreo energético y notificaciones del sistema. Permite mantener de manera alineada las funcionalidades identificadas durante el proceso de Event Storming y análisis funcional del proyecto.

- Dentro de gestión de usuarios, se definieron las clases Usuario, Administrador y Sesion, encargadas de representar los procesos relacionados con autenticación, supervisión del sistema y control de acceso. La clase Usuario contiene atributos y métodos relacionados con el inicio de sesión, control de dispositivos y visualización del dashboard principal. La clase Administrador hereda funcionalidades de Usuario e incorpora operaciones adicionales relacionadas con validación de dispositivos y supervisión de la infraestructura.

- En administración de dispositivos, las clases Gateway, NodoIoT, Dispositivo y EstadoDispositivo representan la infraestructura encargada de la sincronización y control remoto de equipos electrónicos conectados a la plataforma.

- Para el contexto de automatización, se incorporaron las clases Automatizacion, ReglaAutomatizacion y Horario, las cuales permiten representar reglas inteligentes, acciones automáticas y programaciones horarias ejecutadas por la plataforma.

- En el monitoreo energético, las clases Dashboard, ConsumoEnergetico y ReporteConsumo permiten representar la gestión de métricas eléctricas, visualización de información y generación de reportes históricos de consumo energético.

- El contexto de notificaciones incorpora las clases EventoSistema, Alerta y Notificacion, encargadas de modelar eventos operativos, alertas automáticas y envío de notificaciones relacionadas con consumos anómalos o incidencias detectadas en la plataforma.

## 4.8 Database Design

En esta sección se presenta el diseño de base de datos, desarrollado a partir de los requerimientos funcionales, entidades identificada y funcionalidades relacionadas con monitoreo, control remoto y administración de dispositivos.

El objetivo es garantizar integridad y organización de la información utilizada por la plataforma, permitiendo almacenar datos relacionados con usuarios, dispositivos electrónicos, consumo energético, alertas y eventos del sistema. Se contemplan relaciones entre entidades, restricciones y mecanismos que soporte operaciones de monitoreo en tiempo real y automatización inteligente.

Para la elaboración de los diagramas de base de datos se utilizará Lucidchart y/o Vertabelo, utilizando diagramas entidad-relación para representar tablas, columnas, claves primarias, claves foráneas y relaciones entre entidades.

### 4.8.1 Database Diagrams

<div style="text-align:center;">
  <img src="imagenes/imagenes_Cap4/Database-diagrams/Database Diagrams.svg"
       alt="texto">
</div>

- Se definieron las tablas Usuario, Permiso y UsuarioPermiso, encargadas de almacenar la información relacionada con autenticación, control de acceso y permisos del sistema. La relación entre usuarios y permisos se implementa mediante una tabla intermedia, permitiendo gestionar distintos niveles de autorización dentro de la plataforma.

- En administración de dispositivos, las tablas Gateway, NodoIoT, Dispositivo, Ambiente y EstadoDispositivo permiten representar la infraestructura IoT utilizada. Estas entidades gestionan la sincronización de nodos, control remoto de dispositivos electrónicos y almacenamiento del estado operativo de cada equipo conectado. Asimismo, las relaciones establecidas mediante claves foráneas permiten representar la asociación entre usuarios, nodos y dispositivos dentro del sistema.

- Para el monitoreo energético, se definieron las tablas ConsumoEnergetico, Dashboard y ReporteConsumo, las cuales permiten almacenar mediciones eléctricas, métricas históricas y reportes de consumo energético. Esta estructura soporta las funcionalidades relacionadas con supervisión en tiempo real.

- Las tablas Automatizacion, ReglaAutomatizacion y Programacion permiten almacenar reglas inteligentes, horarios programados y acciones automáticas ejecutadas por la plataforma. Estas entidades responden a las necesidades de automatización identificadas durante el análisis de usuarios y el proceso de Event Storming.

- El contexto de notificaciones incluye las tablas EventoSistema, Alerta y Notificacion, encargadas de registrar eventos operativos, consumos anómalos y alertas generadas automáticamente por la plataforma.

- Las tablas Historial y Exportacion permiten gestionar acciones realizadas dentro del sistema y exportación de reportes energéticos, contribuyendo a mejorar el control operativo y análisis de información.