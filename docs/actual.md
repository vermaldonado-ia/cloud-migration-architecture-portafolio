# Actual

## 🧩 Descripción general

La plataforma ERP se encuentra desplegada en un datacenter local, soportando la operación de múltiples clientes del sector de comercio exterior.

El modelo actual responde a una arquitectura tradicional, con fuerte dependencia de infraestructura física y componentes altamente acoplados.

---

## 🏗️ Características del entorno actual

* Infraestructura on-premise (datacenter local)
* Aplicación centralizada (modelo monolítico o semi-monolítico)
* Base de datos compartida
* Integraciones directas entre componentes
* Procesos de despliegue manuales
* Dependencia de equipos técnicos para operación

---

## ⚠️ Principales limitaciones

### 1. Escalabilidad limitada

El crecimiento de clientes o volumen de transacciones requiere aumentar capacidad física, lo que implica tiempos largos y costos elevados.

---

### 2. Riesgo operativo

La dependencia de un datacenter local expone la operación a riesgos como:

* fallas de infraestructura
* cortes de energía
* eventos físicos
* incidentes sin recuperación inmediata

---

### 3. Despliegues complejos

Los cambios en la plataforma requieren procesos manuales, lo que genera:

* mayor probabilidad de error
* ventanas de mantenimiento
* impacto en usuarios finales

---

### 4. Alto acoplamiento

Los componentes del sistema están fuertemente conectados, lo que provoca que:

* cambios pequeños afecten múltiples módulos
* sea difícil aislar fallas
* se reduzca la velocidad de evolución

---

### 5. Baja flexibilidad

La arquitectura actual dificulta:

* incorporar nuevas funcionalidades
* integrar nuevos servicios
* adaptarse rápidamente a cambios del negocio

---

### 6. Limitada recuperación ante incidentes

No existe un mecanismo robusto de recuperación automática, lo que puede generar tiempos prolongados de indisponibilidad ante fallas críticas.

---

## 📉 Impacto en el negocio

Estas limitaciones generan efectos directos:

* lentitud en la entrega de mejoras
* riesgo en la continuidad del servicio
* dificultad para escalar el negocio
* dependencia de infraestructura rígida
* menor capacidad de respuesta ante clientes

---

## 🧠 Conclusión

La arquitectura actual cumple con la operación existente, pero no está preparada para soportar el crecimiento, la escalabilidad ni la agilidad que el negocio requiere en el mediano y largo plazo.

Esto hace necesaria una estrategia de modernización hacia un modelo más flexible, resiliente y escalable.

