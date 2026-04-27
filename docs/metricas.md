## 📊 Observabilidad, Monitoreo y Métricas de Éxito

Como parte de la arquitectura objetivo, se definió una capa de observabilidad orientada a asegurar la estabilidad operativa post-migración.

Se propone el uso de Amazon CloudWatch como herramienta central de monitoreo.

---

### 🎯 Objetivo

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

### 🚨 Alertas (Alarmas)

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

## 💰 Gestión de Costos y Control Financiero

Como parte del proceso de migración, se incorporó un enfoque de control de costos orientado a evitar desviaciones y asegurar la sostenibilidad de la operación en cloud.

### 🔹 Estimación previa de costos

Antes de la migración, se realizó una evaluación utilizando AWS Pricing Calculator, permitiendo:

* Proyectar costos de infraestructura
* Comparar con el modelo de datacenter
* Definir un modelo financiero eficiente
* Apoyar decisiones estratégicas

---

### 🔹 Control y monitoreo de costos

* Uso de etiquetas (tags) por cliente y entorno
* Seguimiento del consumo de recursos
* Monitoreo del comportamiento de la infraestructura

---

### 🔹 Alertas y gestión de escalabilidad

* Notificaciones ante incremento de consumo
* Seguimiento de escalamiento horizontal y vertical
* Identificación temprana de desviaciones

---

### 🎯 Objetivo de Control de Costos

Asegurar un uso eficiente de los recursos en cloud, evitando incrementos inesperados y manteniendo la sostenibilidad financiera de la operación.

---

## 🧠 Enfoque

La incorporación de monitoreo y control financiero permite:

* Transitar de un modelo reactivo a uno proactivo
* Mejorar la experiencia del cliente
* Asegurar estabilidad en el proceso de expansión

---

## 📊 Dashboards de Monitoreo (Referencia)

## 📊 Dashboards de Monitoreo

Los dashboards fueron diseñados para cubrir distintos niveles de visibilidad:

### 📌 Dashboard Ejecutivo
Vista orientada a negocio, enfocada en disponibilidad, incidentes y estado general del servicio.

### 🔧 Dashboard Técnico
Monitoreo detallado de performance:
- CPU
- Memoria
- Latencia
- Uso de red

### 🚨 Dashboard de Alarmas
Gestión de eventos críticos:
- Alertas automáticas
- Umbrales definidos
- Notificación de incidentes

📸 Referencia visual disponible en el README principal del repositorio.

