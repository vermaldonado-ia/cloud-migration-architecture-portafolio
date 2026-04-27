## 📌 Contexto

En el modelo anterior no existía monitoreo estructurado, lo que dificultaba la detección temprana de incidentes y aumentaba el impacto en clientes.

La nueva arquitectura incorpora una capa de observabilidad basada en CloudWatch.

---

# 📊 Observabilidad, Monitoreo y Métricas de Éxito

Como parte de la arquitectura objetivo, se definió una capa de observabilidad orientada a asegurar la estabilidad operativa post-migración.

Se propone el uso de Amazon CloudWatch como herramienta central de monitoreo.

---

## 🎯 Objetivo

* Detectar incidentes de forma temprana
* Asegurar continuidad operacional
* Monitorear performance de la plataforma
* Reducir impacto en clientes

---

## ☁️ Monitoreo con CloudWatch

Se definieron métricas clave para el seguimiento de la infraestructura y servicios:

### 🔧 Métricas técnicas

* CPUUtilization
* NetworkIn / NetworkOut
* DiskReadOps / DiskWriteOps
* StatusCheckFailed
* Latencia de aplicación
* Errores de base de datos

---

## 🚨 Alertas (Alarmas)

Se proponen alarmas automáticas para detectar eventos críticos:

* CPU > 80% por más de 10 minutos
* Caída de instancia
* Incremento de latencia
* Pérdida de conectividad
* Errores repetitivos en base de datos

Estas alertas permiten una respuesta proactiva ante incidentes.

---

## 📊 Dashboard Operativo

Se define un dashboard para monitoreo ejecutivo:

* Disponibilidad del sistema
* Estado de servicios
* Clientes afectados
* Incidentes activos vs resueltos
* Tendencia de uso de recursos

---

## 💰 Gestión de Costos y Control Financiero

Como parte del proceso de migración, se incorporó un enfoque de control de costos orientado a evitar desviaciones y asegurar la sostenibilidad de la operación en cloud.

---

### 🔹 Estimación previa de costos

Antes de la migración, se realizó una evaluación de costos utilizando herramientas de estimación (AWS Pricing Calculator), permitiendo:

* Proyectar costos de infraestructura en cloud
* Comparar con costos actuales del datacenter
* Definir un modelo financiero más eficiente
* Apoyar la toma de decisiones estratégicas

---

### 🔹 Control y monitoreo de costos

Durante la operación, se definieron mecanismos de control para evitar sobrecostos:

* Uso de etiquetas (tags) para segmentar recursos por cliente y entorno
* Seguimiento del consumo de recursos en función de la demanda
* Monitoreo del comportamiento de la infraestructura

---

### 🔹 Alertas y gestión de escalabilidad

Se establecieron mecanismos de alerta asociados al crecimiento de la plataforma:

* Notificaciones ante incremento de consumo de recursos
* Seguimiento de escalamiento horizontal y vertical
* Identificación temprana de posibles desviaciones de costos

---

### 🎯 Objetivo

Asegurar un uso eficiente de los recursos en cloud, manteniendo el control financiero de la operación y evitando incrementos inesperados de costos.

---

Este enfoque permitió complementar la migración tecnológica con un control económico adecuado, alineando la operación cloud con los objetivos de eficiencia del negocio.


---

## 📈 Métricas Operativas

* Número de incidentes post-migración
* Tiempo medio de recuperación (MTTR)
* Tiempo de disponibilidad
* Ventanas de indisponibilidad

---

## 💼 Métricas de Negocio

* Reducción de multas por incidentes
* Continuidad del servicio
* Estabilidad para clientes VIP
* Capacidad de crecimiento

---

## 🧠 Enfoque

La incorporación de monitoreo y alertamiento permite:

* Transitar de un modelo reactivo a uno proactivo
* Mejorar la experiencia del cliente
* Asegurar estabilidad en el proceso de expansión

---

## 📊 Dashboards de Monitoreo (Referencia)

Los siguientes dashboards representan una vista referencial de la capa de observabilidad definida para la arquitectura objetivo.

### Dashboard Ejecutivo

![Dashboard Ejecutivo](../diagrams/dashboard_ejecutivo.png)

Vista orientada a negocio para monitorear disponibilidad, incidentes, clientes migrados y estabilidad general del servicio.

---

### Dashboard Técnico

![Dashboard Técnico](../diagrams/dashboard_tecnico.png)

Vista orientada a operación para supervisar performance de infraestructura, red, latencia y estado de instancias.

---

### Alarmas Críticas

![Alarmas Críticas](../diagrams/alarmas_criticas.png)

Vista de alertamiento operacional para la detección temprana de incidentes críticos post-migración.
