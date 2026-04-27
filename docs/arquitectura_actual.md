## 🏗️ Arquitectura Actual (AS-IS)

La plataforma operaba sobre un modelo basado en infraestructura local (datacenter propio), con una arquitectura altamente fragmentada y con bajo nivel de estandarización.

### 🔹 Componentes principales

* Máquina virtual independiente por cliente
* Base de datos de código abierto por instancia
* Plataforma web personalizada por cliente

---

### ⚠️ Problemáticas técnicas identificadas

* **Inestabilidad en la base de datos:**
  Uso de motor de base de datos de código abierto que, ante crecimiento significativo de datos (GB), presentaba fallas críticas, incluyendo pérdida o eliminación de información.

* **Alta fragmentación de versiones:**
  Existencia de múltiples versiones de la plataforma en producción, generando inconsistencias entre clientes y dificultad para mantener actualizaciones homogéneas.

* **Falta de estandarización:**
  Cada cliente operaba con configuraciones distintas, aumentando la complejidad operativa y los tiempos de soporte.

---

### ⚙️ Problemáticas operacionales

* Cambios en producción sin control formal
* Ausencia de ambientes separados (Desarrollo / QA / Producción)
* Falta de procesos de validación antes de despliegues
* Dependencia de intervenciones manuales

---

### 🚨 Impacto en el negocio

* Alto riesgo de pérdida de datos
* Baja confiabilidad del servicio
* Reclamos de clientes por desalineación de versiones
* Dificultad para escalar la plataforma
* Incremento en costos operativos por mantenimiento reactivo

---

### 📉 Limitaciones de la arquitectura

* Baja escalabilidad
* Baja resiliencia ante fallas
* Dificultad para crecimiento internacional
* Dependencia total del datacenter local

---

Esta arquitectura representaba un riesgo crítico para la continuidad operacional y limitaba directamente la capacidad de crecimiento del negocio.

