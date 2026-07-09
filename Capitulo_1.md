# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

Somos una startup peruana denominada **Veltrix**, creada por estudiantes de la carrera de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC), que tiene como objetivo principal optimizar la gestión y control de dispositivos electrónicos en hogares y pequeñas empresas mediante el uso de tecnología IoT.

Nuestra misión es lograr que ninguna persona o negocio gestione sus dispositivos eléctricos de forma manual o desorganizada, promoviendo un control centralizado, automatizado y accesible que permita mejorar la eficiencia energética, la seguridad y la comodidad en el día a día.

Para cumplir con este propósito, hemos desarrollado el proyecto **DomotiCore**, una plataforma web de domótica que permite a los usuarios gestionar, monitorear y automatizar dispositivos electrónicos de manera centralizada. La solución ofrece control en tiempo real, programación de horarios, monitoreo del estado de los dispositivos y una interfaz intuitiva que facilita la interacción del usuario sin necesidad de conocimientos técnicos avanzados.

### 1.1.2 Perfiles de los Miembros del Equipo

docs: update formatting and improve table structure in readme.
| Foto | Apellido y Nombre | 
| --- | --- | 
![oscar](imagenes/imagenes_Cap1/oscar.png) | *Checa Buga Oscar Diego - u20231e492* Soy estudiante de la carrera de ingeniería de software de 5to ciclo, interesado en el desarrollo de soluciones tecnológicas. Destaco por mi trabajo en equipo y comunicación constante. Tengo conocimiento en base de datos, desarrollo de aplicaciones y programación. Me gusta ir adaptándome a las nuevas tecnologías y aprender de estas, para poder desarrollar más en el ámbito profesional.
![diego](imagenes/imagenes_Cap1/diego.jpeg) | *Esquicha Alcántara Diego Alonso - u202411799* Soy un estudiante de la carrera de ingeniería de software de quinto ciclo, me destaco por mis habilidades de comunicación y liderazgo para trabajar en equipo. Una de mis fortalezas es el desarrollo de la documentación necesaria para dar a marcha un proyecto o trabajo grupal y la comodidad de aprender de manera rápida y eficiente alguna herramienta tecnológica.  
![cesar](imagenes/imagenes_Cap1/cesar.jpeg) | *Quispe Llacsahuanga César Agusto - u202417405* Soy estudiante de Ingeniería de Software, interesado en el desarrollo de soluciones tecnológicas y el aprendizaje continuo en herramientas de programación. Cuento con conocimientos en lógica de programación, bases de datos y desarrollo de aplicaciones, lo que me permite contribuir en la construcción de sistemas eficientes. Me caracterizo por ser responsable, proactivo y con buena disposición para el trabajo en equipo, adaptándome a nuevos retos y aportando en el cumplimiento de los objetivos del proyecto. 
![alvaro](imagenes/imagenes_Cap1/alvaro.png) | *Rocha Cotrina Alvaro - u202411243* Soy estudiante de Ingeniería de Software, con enfoque en el desarrollo backend, bases de datos y lógica de programación. Cuento con experiencia en la creación de aplicaciones y resolución de problemas mediante programación, especialmente en lenguajes como C++ y el diseño de sistemas estructurados. Me caracterizo por ser organizado, responsable y comprometido con el trabajo en equipo, aportando en la construcción de soluciones eficientes y en la correcta estructuración de la arquitectura del sistema. Además, tengo una gran capacidad de aprendizaje y adaptación a nuevas tecnologías, lo que me permite contribuir activamente en el desarrollo del proyecto.
![fabrizio](imagenes/imagenes_Cap1/Fabrizio.png) | *Tello Palacios Fabrizio Rafael - u202113310*  Soy estudiante de la carrera de Ingeniería de Software. Considero que soy una persona comprometida en cada trabajo y tarea y siempre trato de dar lo mejor de mi en cada situación. A veces tengo complicaciones con la organización de mi tiempo, pero siempre estoy atento a cualquier problema dentro del equipo para poder pensar en soluciones y llegar a la mejor posible. Me gustan los retos, porque son esos retos los que me motivan a ser mejor como persona y como estudiante. Tengo muchas  cosas en las que mejorar y sé que lo lograré con disciplina y perseverancia.
![DiegoV](imagenes\imagenes_Cap1\DiegoV.PNG) | *Véliz Martínez Diego Alonso - u20211b564*  Soy estudiante de la carrera de Ingeniería de Software. Me considero una persona sumamente dedicada que siempre busca dar su máximo esfuerzo. Aunque la gestión de mi tiempo es un área en la que sigo trabajando, destaco por mi capacidad para resolver problemas y apoyar a mi equipo. Los desafíos me motivan profundamente a crecer en todos los aspectos; reconozco mis oportunidades de mejora y estoy decidido a superarlas con disciplina y constancia.

## 1.2 Solution Profile

### 1.2.1 Antecedentes y Problemática

**What / ¿QUÉ?**  
Se presenta una falta de control centralizado y automatización en la gestión de dispositivos electrónicos, lo que genera ineficiencia en el uso de energía y dependencia de procesos manuales en hogares y pequeñas empresas.  

**When / ¿CUÁNDO?**  
El problema se manifiesta de manera crítica cuando los usuarios olvidan apagar dispositivos, requieren activarlos de forma remota o necesitan programar su funcionamiento en horarios específicos sin intervención manual.  

**Where / ¿DÓNDE?**  
Se observa principalmente en entornos domésticos y pequeños negocios donde múltiples dispositivos eléctricos operan de forma independiente sin integración en un sistema centralizado.  

**Who / ¿QUIÉN?**  
Afecta a propietarios de viviendas, emprendedores y administradores de pequeños negocios que buscan optimizar el control de sus dispositivos eléctricos y reducir costos operativos.  

**Why / ¿POR QUÉ?**  
Sucede debido a la ausencia de soluciones accesibles y centralizadas que integren dispositivos IoT en una sola plataforma, generando procesos manuales, falta de automatización y desperdicio energético.  

**How / ¿CÓMO?**  
A diferencia de un sistema automatizado donde los dispositivos responden a configuraciones inteligentes, el problema se presenta como una gestión manual constante, provocando ineficiencia operativa y pérdida de control.  

**How Much / ¿CUÁNTO?**  
Los usuarios pueden perder entre un 15% y 25% de eficiencia energética debido al uso manual e inadecuado de dispositivos, lo que se traduce en mayores costos de electricidad y menor optimización de recursos.  

### 1.2.2 Lean UX Process

#### 1.2.2.1 Lean UX Problem Statements
DomotiCore fue diseñado para permitir que los usuarios de hogares inteligentes y pequeños negocios gestionen sus dispositivos electrónicos de manera centralizada, automatizada y eficiente.

Sin embargo, hemos observado que muchos usuarios continúan dependiendo de controles manuales o de soluciones aisladas para administrar sus dispositivos, lo que dificulta el monitoreo en tiempo real, incrementa el consumo energético y limita la automatización de las tareas cotidianas.

Esta situación genera pérdida de tiempo, mayores costos de energía y una experiencia de gestión poco eficiente, afectando tanto la comodidad de los usuarios como la eficiencia operativa de sus hogares y negocios.

**¿Cómo podríamos** ofrecer una plataforma web intuitiva que centralice el control, monitoreo y automatización de dispositivos IoT para reducir la intervención manual, optimizar el consumo energético y mejorar la experiencia de los usuarios?

#### 1.2.2.2 Lean UX Assumptions

**A. Business Assumptions**

- Creemos que nuestros clientes necesitan:  
Centralizar el control de sus dispositivos electrónicos, monitorear el consumo energético y automatizar tareas repetitivas para optimizar recursos y reducir errores operativos.

- Creemos que estas necesidades se resolverán mediante:  
Una plataforma web de domótica (DomotiCore) que integre monitoreo energético, control remoto y automatización programada en una única interfaz intuitiva y accesible.

- Creemos que nuestros primeros clientes serán:  
Usuarios de hogares inteligentes y pequeños negocios que buscan reducir el consumo eléctrico, mejorar el control operativo y evitar soluciones complejas o costosas.

- Creemos que el principal valor para nuestros clientes será:  
El control centralizado y el monitoreo energético en tiempo real mediante una plataforma simple y accesible.

- Creemos que los usuarios obtendrán beneficios adicionales como:  
La reducción del consumo energético, el ahorro económico, una mayor tranquilidad, la automatización de tareas y una supervisión remota eficiente.

- Creemos que adquiriremos nuestros primeros usuarios mediante:  
La difusión en redes sociales, demostraciones funcionales, validación académica y pruebas con usuarios reales pertenecientes a los segmentos objetivo.

- Creemos que nuestro modelo de ingresos será:  
Un modelo freemium con funcionalidades básicas gratuitas y herramientas avanzadas bajo suscripción.

- Creemos que nuestros principales competidores serán:  
Soluciones de domótica como Google Nest, Amazon Alexa y plataformas de automatización propietarias.

- Creemos que nuestra principal ventaja competitiva será:  
Una plataforma web accesible, intuitiva y enfocada en usuarios sin experiencia técnica, priorizando el ahorro energético y el control centralizado sin depender de ecosistemas cerrados o hardware costoso.

- Creemos que el mayor riesgo del producto será:  
La complejidad en la integración con distintos dispositivos físicos IoT y la adopción inicial por parte de usuarios no técnicos.

- Creemos que podremos mitigar este riesgo mediante:  
El uso de dispositivos estándar (ESP32/Arduino), la simulación de hardware, una interfaz intuitiva y una arquitectura escalable orientada a la facilidad de uso.

**B. User Assumptions**

- Creemos que los usuarios serán:  
Usuarios domésticos y emprendedores que desean controlar y automatizar dispositivos electrónicos de manera simple, accesible y centralizada.

- Creemos que el producto formará parte de:  
La gestión diaria del hogar o negocio, especialmente en tareas relacionadas con el control remoto, la supervisión y el ahorro energético.

- Creemos que el principal problema que desean resolver es:  
La falta de monitoreo centralizado, la dependencia de procesos manuales y la dificultad para supervisar dispositivos cuando el usuario no está presente.

- Creemos que el uso más frecuente del producto será:  
Encender y apagar dispositivos, programar horarios automáticos, monitorear el consumo energético y verificar estados en tiempo real.

- Creemos que las características más importantes para los usuarios serán:  
Un dashboard centralizado, monitoreo energético por dispositivo, automatización programada, alertas inteligentes y control remoto.

- Creemos que los usuarios esperarán una interfaz:  
Moderna, intuitiva, accesible y fácil de utilizar desde navegadores web y dispositivos móviles.

**C. User Outcome & Benefit Assumptions**

- Creemos que los usuarios podrán visualizar de forma centralizada el estado y consumo de sus dispositivos.

- Creemos que los usuarios reducirán su consumo energético y sus costos operativos.

- Creemos que los usuarios automatizarán tareas repetitivas con mayor frecuencia.

- Creemos que los usuarios experimentarán una mayor tranquilidad gracias al control remoto desde cualquier ubicación.

- Creemos que los usuarios disminuirán los errores humanos relacionados con olvidos o supervisión manual.

**D. Business Outcome Assumptions**

- Creemos que DomotiCore permitirá reducir aproximadamente un 20% el consumo energético durante los primeros meses de uso.

- Creemos que el uso de automatizaciones programadas incrementará aproximadamente un 30%.

- Creemos que alcanzaremos al menos 100 usuarios activos durante el primer año.

- Creemos que lograremos una retención superior al 80% gracias a una experiencia simple e intuitiva.

- Creemos que nos diferenciaremos de soluciones más complejas mediante la accesibilidad y facilidad de uso de la plataforma.

**E. Feature Assumptions**

- Creemos que un Dashboard Centralizado permitirá visualizar dispositivos, estados y consumo energético en una sola interfaz.

- Creemos que la Automatización Programada reducirá la intervención manual y mejorará la eficiencia operativa.

- Creemos que el Monitoreo Energético permitirá identificar los dispositivos con mayor consumo eléctrico.

- Creemos que el Control Remoto aumentará la sensación de control, comodidad y seguridad del usuario.

- Creemos que las Alertas Inteligentes reducirán los errores humanos relacionados con dispositivos encendidos innecesariamente.

#### 1.2.2.3 Lean UX Hypothesis Statements

**Control Centralizado**

Creemos que al ofrecer un dashboard centralizado con información en tiempo real sobre dispositivos y consumo energético **para los usuarios de hogares inteligentes y pequeños negocios**, estos podrán gestionar sus dispositivos desde una única plataforma, **logrando reducir la interacción manual en un 25% y aumentar su capacidad de supervisión y control operativo**. **Sabremos que tenemos razón cuando** observemos comentarios como: *"Ahora puedo controlar y supervisar todos mis dispositivos desde un solo lugar"* y/o cuando los registros del sistema reflejen un uso recurrente del dashboard para el monitoreo diario.

**Automatización de Dispositivos**

Creemos que al permitir automatizaciones programadas y configuraciones inteligentes **para los usuarios de hogares inteligentes y pequeños negocios**, estos optimizarán el uso de sus dispositivos, **logrando reducir el desperdicio energético en un 20% y disminuyendo la necesidad de realizar acciones manuales repetitivas**. **Sabremos que tenemos razón cuando** los usuarios comenten: *"Ya no necesito preocuparme por apagar dispositivos manualmente"* y/o cuando las estadísticas de uso reflejen una alta frecuencia de automatizaciones configuradas.

**Acceso Remoto**

Creemos que al ofrecer acceso remoto desde cualquier ubicación **para los usuarios de hogares inteligentes y pequeños negocios**, estos podrán supervisar y controlar sus dispositivos en tiempo real, **logrando incrementar su satisfacción, tranquilidad y sensación de control sobre su hogar o negocio**. **Sabremos que tenemos razón cuando** observemos comentarios como: *"Puedo supervisar mi hogar o negocio aunque no esté presente"* y/o cuando el sistema registre accesos frecuentes realizados fuera de la red local.

**Optimización Energética**

Creemos que al incorporar monitoreo energético individual por dispositivo y alertas inteligentes **para los usuarios de hogares inteligentes y pequeños negocios**, estos identificarán consumos innecesarios y tomarán mejores decisiones sobre el uso de sus dispositivos, **logrando optimizar sus recursos eléctricos y reducir el consumo energético**. **Sabremos que tenemos razón cuando** observemos comentarios como: *"Ahora sé qué dispositivos consumen más energía y puedo controlarlos mejor"* y/o cuando se evidencien patrones de consumo más eficientes dentro de la plataforma.

#### 1.2.2.4 Lean UX Canvas

| **Business Problem** | **Solutions** | **Business Outcomes** |
| :------------------- | :------------ | :------------------- |
|El estado actual de la gestión de dispositivos electrónicos en hogares y pequeños negocios se caracteriza por una alta dependencia de controles manuales, aplicaciones aisladas y supervisión física constante. Esta situación genera desperdicio energético, dificultad para monitorear dispositivos de forma remota, errores humanos frecuentes y baja capacidad de automatización. Además, muchas soluciones de domótica existentes son costosas, complejas o dependen de ecosistemas cerrados, dificultando su adopción por usuarios sin conocimientos técnicos. DomotiCore busca resolver esta problemática mediante una plataforma web accesible e intuitiva que centraliza el control de dispositivos, automatiza tareas repetitivas y permite monitorear el consumo energético en tiempo real desde cualquier ubicación. Nuestro enfoque inicial está dirigido a usuarios domésticos y pequeños negocios que buscan optimizar recursos, reducir costos operativos y mejorar el control de sus dispositivos de manera simple y eficiente. Sabremos que hemos tenido éxito cuando logremos reducir el consumo energético, aumentar la adopción de automatizaciones y generar un uso recurrente de la plataforma debido a su facilidad de uso y utilidad práctica. | **- Dashboard centralizado:** Visualización en tiempo real del estado, actividad y consumo energético de todos los dispositivos conectados desde una sola interfaz. <br> **- Automatización programada:** Configuración automática de horarios y rutinas para reducir la intervención manual y optimizar el consumo energético. <br> **- Control remoto:** Acceso desde cualquier lugar para gestionar dispositivos sin necesidad de presencia física. <br> **- Monitoreo energético:** Supervisión individual del consumo eléctrico por dispositivo para identificar desperdicios y mejorar la toma de decisiones. <br> **- Alertas inteligentes:** Notificaciones automáticas sobre dispositivos encendidos innecesariamente o actividad inusual. | - Reducción del 20% en el consumo energético durante los primeros meses de uso. <br> - Disminución del uso manual de dispositivos en al menos un 25%. <br> - Incremento del 30% en la adopción de automatizaciones programadas. <br> - Alcanzar 100 usuarios activos en el primer año. <br> - Retención superior al 80% mediante una experiencia intuitiva y accesible. <br> - Diferenciación frente a soluciones complejas mediante simplicidad, accesibilidad y monitoreo energético centralizado. |

| **Users** | **User Outcomes & Benefits** |
| :-------- | :-------------------------- |
| **- Usuarios domésticos:** “Quiero controlar y supervisar todos los dispositivos de mi hogar desde un solo lugar, reduciendo el consumo energético y evitando olvidos o desperdicios innecesarios.” <br> **- Emprendedores / pequeños negocios:** “Necesito monitorear y automatizar los dispositivos de mi negocio para reducir costos operativos, optimizar recursos y mantener control incluso cuando no estoy presente físicamente.” <br> | **- Usuarios domésticos:** Control centralizado de sus dispositivos electrónicos desde cualquier ubicación, permitiendo automatizar tareas repetitivas, monitorear el consumo energético y reducir la dependencia de acciones manuales. Beneficios: ahorro de energía, mayor tranquilidad, prevención de olvidos, comodidad y mejor organización del entorno doméstico. <br> **- Pequeños negocios / emprendedores:** Supervisión remota y automatización eficiente de los dispositivos del negocio mediante una plataforma simple y accesible. Beneficios: reducción de costos operativos, disminución de errores humanos, mayor eficiencia en la gestión diaria, mejor control operativo y optimización del consumo eléctrico. |

| **Hypotheses** | **What’s the most important thing we need to learn first?** | **What’s the least amount of work we need to do to learn the next most important thing?** |
| :------------- | :------------------------ | :----------------------- |
| **- Creemos que** reduciremos el consumo energético en un 20% si los usuarios utilizan automatizaciones programadas y monitoreo energético en tiempo real en lugar de depender únicamente del control manual. <br> **- Creemos que** aumentaremos la frecuencia de uso de la plataforma en un 30% si ofrecemos un dashboard centralizado, intuitivo y fácil de comprender para usuarios sin conocimientos técnicos. <br> **- Creemos que** incrementaremos la satisfacción y tranquilidad de los usuarios si permitimos supervisar y controlar dispositivos remotamente desde cualquier ubicación. <br> **- Creemos que** lograremos una adopción inicial más rápida si la plataforma prioriza simplicidad, accesibilidad y facilidad de configuración frente a soluciones complejas del mercado. <br> **- Creemos que** disminuiremos errores operativos y desperdicio energético si los usuarios reciben alertas inteligentes sobre dispositivos encendidos innecesariamente. <br> **- Creemos que** pequeños negocios percibirán mayor valor en la plataforma si pueden monitorear consumo energético y controlar múltiples dispositivos desde una sola interfaz centralizada. | - ¿El monitoreo energético en tiempo real representa un valor diferencial importante para los usuarios frente a otras soluciones de domótica? <br> - ¿Los usuarios priorizan más la facilidad de uso o las funcionalidades avanzadas de automatización? <br> - ¿Qué dispositivos consideran más importantes para automatizar y supervisar? <br> - ¿Los pequeños negocios perciben el ahorro energético como un beneficio relevante o priorizan más el control operativo remoto? <br> - ¿Los usuarios confiarían en una plataforma web accesible para gestionar dispositivos críticos de su hogar o negocio? | - Realizar entrevistas a usuarios domésticos y emprendedores para validar necesidades relacionadas con ahorro energético, automatización y control remoto. <br> - Desarrollar un prototipo navegable de alta fidelidad (Figma) enfocado en dashboard centralizado, monitoreo energético y automatización programada. <br> - Implementar una simulación básica de dispositivos IoT utilizando ESP32 o entornos virtuales para validar la experiencia de control y monitoreo. <br> - Ejecutar pruebas de usabilidad para evaluar la facilidad de uso de la plataforma en usuarios sin experiencia técnica. <br> - Recoger feedback mediante sesiones de prueba y encuestas para identificar qué funcionalidades generan mayor valor y diferenciación frente a la competencia. |

## 1.3 Segmentos Objetivos

**Segmento 1: Usuarios de Hogares Inteligentes**

Corresponde a los usuarios finales que buscan mejorar su calidad de vida mediante la automatización de su entorno doméstico, conformado por personas entre 20 y 50 años con acceso a tecnología y familiarizadas con el uso de smartphones, aplicaciones móviles y servicios digitales, incluyendo estudiantes, profesionales y familias jóvenes que valoran la comodidad, la seguridad y la eficiencia en su día a día; en su rutina enfrentan problemas como olvidar apagar dispositivos, depender de acciones manuales constantes o no tener visibilidad del estado de sus equipos cuando están fuera de casa, lo que genera pequeñas ineficiencias acumulativas; psicográficamente, priorizan soluciones prácticas, intuitivas y accesibles que no requieran conocimientos técnicos avanzados, buscando herramientas que automaticen tareas repetitivas y optimicen su tiempo; en este contexto, una plataforma como DomotiCore representa una solución integral que no solo mejora la organización del hogar, sino que también contribuye al ahorro energético y brinda mayor tranquilidad mediante el control remoto de los dispositivos.

**Segmento 2: Pequeños Negocios y Emprendedores**

Define a los usuarios a nivel operativo y comercial que gestionan pequeños negocios y requieren optimizar el uso de sus recursos para mantener la rentabilidad, conformado por emprendedores y propietarios de establecimientos como farmacias, tiendas o locales comerciales, generalmente con equipos reducidos de trabajo y recursos limitados; estos negocios utilizan múltiples dispositivos eléctricos en su operación diaria, los cuales suelen ser gestionados de forma manual o sin un sistema centralizado, generando problemas como consumo energético innecesario, falta de control cuando el propietario no está presente y dependencia de terceros para supervisar el funcionamiento; psicográficamente, valoran soluciones confiables, accesibles y que generen un impacto directo en la reducción de costos y mejora operativa, priorizando herramientas fáciles de usar que no impliquen alta complejidad técnica; en el contexto actual, esta falta de automatización puede traducirse en pérdidas económicas y menor eficiencia, por lo que una plataforma como DomotiCore representa no solo una mejora tecnológica, sino una oportunidad estratégica para optimizar procesos, reducir gastos y mejorar el control del negocio desde cualquier lugar.
