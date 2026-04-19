# 3.1. User Stories
En esta sección se verán las historias de usuario que ayudarán en el desarrollo de la plataforma **DeepEnergy**, el consumo energético que se ve mediante tecnología IoT, bajo la visión de **Voltia**.

## 
| **Epic / Story ID** | **EP01 / US01** |
| :--- | :--- |
| **Título** | **Vinculación de inicio** |
| **Descripción** | **Como** Usuario (Hogar/SME), **quiero** registrar mi inicio en la plataforma **para** establecer el puente de comunicación entre mis dispositivos físicos y la nube de **DeepEnergy**. |
| **Relacionado con** | **EP01: Gateway Management** |
| **Criterios de Aceptación** | **Scenario 1: Registro exitoso del Gateway**<br> **Dado que** el usuario tiene un inicio de **Voltia** conectado a la red<br> **Cuando** ingresa el código de identificación único (MAC/ID) y presiona "Vincular"<br> **Entonces** el sistema valida la conexión y muestra el estado como "Online".<br><br> **Scenario 2: Error de conexión**<br> **Dado que** el Gateway no tiene acceso a internet<br> **Cuando** el usuario intenta realizar la vinculación<br> **Entonces** el sistema muestra un mensaje de error "Dispositivo no detectado, verifique su conexión". |
###

| **Epic / Story ID** | **EP01 / US02** |
| :--- | :--- |
| **Título** | **Registro y sincronización de nodos** |
| **Descripción** | **Como** Usuario, **quiero** añadir nuevos enchufes o focos inteligentes **para** ampliar mi red de control a través de **DeepEnergy**. |
| **Relacionado con** | **EP01: Gateway Management** |
| **Criterios de Aceptación** | **Scenario 1: Sincronización de nuevo dispositivo**<br> **Dado que** el usuario pone un nodo en "Modo Emparejamiento"<br> **Cuando** hace clic en "Escanear Dispositivos" en la app<br> **Entonces** el sistema detecta el nodo, lo registra en la base de datos de **Voltia** y lo añade a la lista de dispositivos disponibles. |
###

| **Epic / Story ID** | **EP02 / US03** |
| :--- | :--- |
| **Título** | **Control remoto de dispositivos** |
| **Descripción** | **Como** Usuario, **quiero** encender o apagar mis dispositivos desde el dashboard **para** gestionar mi hogar o negocio de forma remota sin intervención manual. |
| **Relacionado con** | **EP02: Device Control** |
| **Criterios de Aceptación** | **Scenario 1: Acción de encendido/apagado**<br> **Dado que** el usuario visualiza el switch de un dispositivo en el dashboard de **DeepEnergy**<br> **Cuando** presiona el botón de acción (Toggle)<br> **Entonces** el sistema envía la señal al Gateway y cambia el estado físico del dispositivo en tiempo real. |

## 
| **Epic / Story ID** | **EP03 / US04** |
| :--- | :--- |
| **Título** | **Programación de horarios** |
| **Descripción** | **Como** Usuario de Hogar, **quiero** programar horas específicas de apagado automático **para** reducir el desperdicio energético durante la noche. |
| **Relacionado con** | **EP03: Automation** |
| **Criterios de Aceptación** | **Scenario 1: Configuración de horario semanal**<br> **Dado que** el usuario accede a la sección "Automations"<br> **Cuando** selecciona un dispositivo y define el horario (ej. 23:00) y los días de la semana<br> **Entonces** **DeepEnergy** guarda la regla y ejecuta el apagado automáticamente. |
###

| **Epic / Story ID** | **EP03 / US05** |
| :--- | :--- |
| **Título** | **Creación de escenas grupales** |
| **Descripción** | **Como** Dueño de Negocio, **quiero** activar una escena de "Cierre" **para** apagar todos los equipos no críticos con un solo comando al finalizar la jornada. |
| **Relacionado con** | **EP03: Automation** |
| **Criterios de Aceptación** | **Scenario 1: Ejecución de escena multidevice**<br> **Dado que** el usuario ha configurado un grupo de dispositivos en **DeepEnergy**<br> **Cuando** presiona el botón "Scene: Business Closing"<br> **Entonces** el sistema envía comandos de apagado simultáneos a todos los nodos vinculados. |

## 
| **Epic / Story ID** | **EP04 / US06** |
| :--- | :--- |
| **Título** | **Monitoreo en tiempo real** |
| **Descripción** | **Como** Usuario, **quiero** visualizar el consumo actual en Watts de cada dispositivo **para** entender mi gasto energético al instante. |
| **Relacionado con** | **EP04: Energy Monitoring** |
| **Criterios de Aceptación** | **Scenario 1: Visualización de datos de consumo**<br> **Dado que** un dispositivo está encendido y consumiendo energía<br> **Cuando** el usuario ingresa a los detalles del dispositivo en **DeepEnergy**<br> **Entonces** el sistema muestra una gráfica dinámica con los Watts consumidos en tiempo real. |
###

| **Epic / Story ID** | **EP04 / US07** |
| :--- | :--- |
| **Título** | **Reporte de ahorro mensual proyectado** |
| **Descripción** | **Como** Administrador de Negocio, **quiero** ver un reporte de ahorro comparativo **para** validar la reducción de costos operativos lograda con **DeepEnergy**. |
| **Relacionado con** | **EP04: Energy Monitoring** |
| **Criterios de Aceptación** | **Scenario 1: Generación de reporte de eficiencia**<br> **Dado que** el sistema ha recolectado datos por al menos 30 días<br> **Cuando** el usuario selecciona "Generar Reporte Mensual"<br> **Entonces** el sistema muestra una comparación del consumo actual vs. el histórico y calcula el ahorro estimado. |

## 
| **Epic / Story ID** | **EP05 / US08** |
| :--- | :--- |
| **Título** | **Alerta de consumo inusual** |
| **Descripción** | **Como** Usuario, **quiero** recibir una alerta si un dispositivo supera un umbral de consumo **para** detectar fallas o descuidos costosos. |
| **Relacionado con** | **EP05: Notifications** |
| **Criterios de Aceptación** | **Scenario 1: Envío de alerta preventiva**<br> **Dado que** el usuario definió un límite de consumo para un nodo<br> **Cuando** **DeepEnergy** detecta que el consumo supera dicho umbral<br> **Entonces** envía una notificación push inmediata al smartphone del usuario. |
###

| **Epic / Story ID** | **EP05 / US09** |
| :--- | :--- |
| **Título** | **Notificación de olvido en horario crítico** |
| **Descripción** | **Como** Usuario, **quiero** ser notificado si un equipo sigue encendido después de la hora de cierre configurada. |
| **Relacionado con** | **EP05: Notifications** |
| **Criterios de Aceptación** | **Scenario 1: Detección de equipo encendido fuera de horario**<br> **Dado que** el sistema detecta consumo en un horario de inactividad programado<br> **Cuando** se valida que el nodo reporta > 0W<br> **Entonces** envía una alerta: "¿Olvidaste apagar este equipo?". |
###

| **Epic / Story ID** | **EP06 / US10** |
| :--- | :--- |
| **Título** | **Logeo de eventos y auditoría** |
| **Descripción** | **Como** Administrador de **Voltia**, **quiero** ver un historial de acciones sobre los dispositivos **para** mantener el control de seguridad del sistema. |
| **Relacionado con** | **EP06: Security & Logs** |
| **Criterios de Aceptación** | **Scenario 1: Revisión de historial de acciones**<br> **Dado que** se han realizado cambios en los dispositivos<br> **Cuando** el administrador navega a "Activity Logs"<br> **Entonces** el sistema muestra una tabla con la marca de tiempo, el usuario y la acción ejecutada en **DeepEnergy**. |