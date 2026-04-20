# ☁️ Cloud Migration Architecture Portafolio

Caso real de migración de una plataforma ERP de comercio exterior desde un datacenter local hacia una arquitectura cloud en AWS, con foco en reducción de riesgo operativo, optimización de costos y habilitación de crecimiento internacional.

---

## 🎯 Executive Summary

La organización operaba sobre un datacenter local con altos costos operativos y riesgos críticos de pérdida de información, afectando directamente la continuidad del negocio.

Se diseñó y ejecutó una estrategia de migración cloud escalonada, priorizada por criticidad de clientes, incorporando mejoras en arquitectura, seguridad y gobierno operativo.

El resultado fue una plataforma más estable, escalable y alineada al core del negocio.

---

## 🧩 Contexto del Negocio

* Industria: Comercio exterior
* Plataforma: ERP logístico (SaaS)
* Modelo: Instancias independientes por cliente

El negocio requería:

* Escalar a nuevos mercados
* Reducir costos operativos
* Aumentar confiabilidad del servicio

---

## ⚠️ Problema Estratégico

* Infraestructura fuera del core del negocio
* Pérdida de información de clientes
* Multas por incidentes operativos
* Falta de ambientes controlados
* Cambios en producción sin gobierno

Esto generaba un riesgo directo sobre:

* continuidad operacional
* reputación
* crecimiento internacional

---

## 🏗️ Arquitectura

### AS-IS

* Datacenter local
* Máquina virtual por cliente
* Base de datos independiente
* Alta fragmentación

### TO-BE

* Migración a AWS
* Arquitectura híbrida (transición)
* Segmentación de red (VPC)
* Base de datos robusta
* Estandarización de plataformas

---

## 🖼️ Arquitectura Objetivo

![Arquitectura](./diagrams/arquitectura.png)

---

## 🔄 Estrategia de Migración

* Migración escalonada
* Ventanas controladas (01:00 – 06:00 AM)
* Priorización por criticidad

Secuencia:

1. Clientes bajo riesgo
2. Clientes intermedios
3. Clientes críticos (VIP)

Se mantuvo el datacenter como respaldo para asegurar continuidad.

---

## ⚡ Gestión de Riesgos

* Pérdida de datos → respaldos + validación
* Impacto operativo → ventanas controladas
* Clientes críticos → migración individual
* Continuidad → arquitectura híbrida

---

## 📊 Observabilidad y Monitoreo

Como parte de la arquitectura objetivo, se definió una capa de monitoreo utilizando Amazon CloudWatch, orientada a asegurar la estabilidad post-migración.

Incluye:

* Monitoreo de infraestructura
* Seguimiento de disponibilidad
* Alertas automáticas
* Dashboards operativos

👉 Ver detalle: [Métricas y monitoreo](./docs/metricas.md)

---

## 👩‍💼 Rol

**Project Manager Senior**

Responsable de:

* Definición de estrategia de migración
* Coordinación de equipos técnicos
* Gestión de stakeholders
* Ejecución controlada del plan

---

## 📈 Resultados de Negocio

* Reducción significativa de costos operativos
* Eliminación de dependencia de datacenter
* Mejora en estabilidad y seguridad
* Disminución de incidentes críticos
* Base habilitada para expansión internacional

---

## 📂 Documentación

* 👉 [Contexto](./docs/contexto.md)
* 👉 [Arquitectura Actual](./docs/actual.md)
* 👉 [Arquitectura Objetivo](./docs/futuro.md)
* 👉 [Migración](./docs/migracion.md)
* 👉 [Roadmap](./docs/roadmap.md)
* 👉 [Riesgos](./docs/riesgos.md)
* 👉 [Seguridad](./docs/seguridad.md)
* 👉 [Métricas y Monitoreo](./docs/metricas.md)
* 👉 [Guía de Entrevista](./docs/entrevista.md)

---

## 🧠 Enfoque Consultivo

Este proyecto refleja un enfoque integral:

* Alineación negocio-tecnología
* Gestión de riesgo
* Toma de decisiones basada en impacto
* Estrategia de migración progresiva
* Diseño orientado a operación

---

## 🚀 Evolución

* Automatización CI/CD
* Observabilidad avanzada
* Microservicios
* Integración con IA

---

