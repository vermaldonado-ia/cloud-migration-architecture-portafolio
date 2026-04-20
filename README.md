# ☁️ Cloud Migration Architecture Portafolio

Proyecto que demuestra un caso real de migración de una plataforma ERP de comercio exterior desde un datacenter local hacia una arquitectura cloud híbrida en AWS.

Este repositorio está diseñado para evidenciar capacidades en:

* Cloud Migration Strategy
* Arquitectura Cloud (AWS)
* Gestión de riesgos y continuidad operativa
* Liderazgo de proyectos de transformación tecnológica

---

## 🎯 Objetivo

Demostrar cómo abordar una migración cloud desde una perspectiva integral:

* Negocio
* Arquitectura
* Riesgos
* Ejecución
* Resultados

---

## 🧩 Contexto del Caso

Se trata de una plataforma ERP logística orientada a la gestión de importaciones y exportaciones, utilizada por agencias de aduana.

El modelo era tipo SaaS (arriendo de plataforma), donde cada cliente operaba sobre una instancia independiente.

---

## ⚠️ Problema

La organización operaba con un datacenter local, generando:

* Altos costos operativos (infraestructura, licencias, personal)
* Pérdida de información de clientes
* Multas por incidentes
* Falta de ambientes (DEV / QA / PROD)
* Cambios en producción sin control

El negocio requería enfocarse en su core: el software, no la infraestructura.

---

## 🏗️ Arquitectura

### AS-IS (Actual)

* Máquinas virtuales por cliente
* Base de datos independiente por cliente
* Alta fragmentación de versiones
* Infraestructura on-premise

### TO-BE (Objetivo)

* Migración a AWS
* Arquitectura híbrida (transición)
* Segmentación de red (VPC)
* Base de datos robusta (Oracle)
* Estandarización de plataformas

---

## 🖼️ Diagrama de Arquitectura

![Arquitectura](./diagrams/arquitectura.png)

---

## 🔄 Estrategia de Migración

* Migración escalonada

* Ventanas controladas (01:00 a 06:00 AM)

* Priorización por riesgo:

  * Bajo
  * Medio
  * Alto (VIP)

* Datacenter como respaldo temporal

---

## ⚡ Gestión de Riesgos

* Pérdida de datos → respaldos + control de migración
* Impacto operativo → ventanas nocturnas
* Clientes críticos → migración individual
* Continuidad → arquitectura híbrida

---

## 👩‍💼 Rol

**Project Manager Senior**

Responsable de:

* Liderar estrategia de migración
* Coordinación de equipos técnicos
* Gestión de stakeholders
* Planificación y ejecución controlada

---

## 📈 Resultados

* Reducción de costos operativos
* Eliminación de dependencia de datacenter
* Mejora en seguridad
* Base para expansión internacional

---

## 📂 Documentación Detallada

* 👉 [Contexto](./docs/contexto.md)
* 👉 [Arquitectura Actual](./docs/actual.md)
* 👉 [Arquitectura Objetivo](./docs/futuro.md)
* 👉 [Estrategia de Migración](./docs/migracion.md)
* 👉 [Roadmap](./docs/roadmap.md)
* 👉 [Riesgos](./docs/riesgos.md)
* 👉 [Seguridad](./docs/seguridad.md)
* 👉 [Métricas](./docs/metricas.md)
* 👉 [Guía de Entrevista](./docs/entrevista.md)

---

## 🧠 Enfoque Profesional

Este repositorio no solo muestra tecnología, sino:

* Toma de decisiones
* Priorización por riesgo
* Estrategia de negocio
* Liderazgo en transformación

---

## 🚀 Próximos pasos

* Evolución a microservicios
* Automatización CI/CD
* Observabilidad
* Integración con IA

---

