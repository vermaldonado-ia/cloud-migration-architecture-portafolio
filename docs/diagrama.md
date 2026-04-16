# Diagrama de Arquitectura

## 🏗️ Arquitectura Actual (AS-IS)

Usuarios / Clientes
↓
ERP (Aplicación central)
↓
Base de Datos
↓
Datacenter Local

---

## 🚀 Arquitectura Futura (TO-BE)

Usuarios / Clientes
↓
ERP en Cloud (entorno principal)
↓
Servicios desacoplados
↓
Base de Datos gestionada
↓
Cloud

⬇️

Datacenter Local (respaldo / contingencia)

---

## 🔄 Modelo de Migración

Datacenter Local
↓
Migración progresiva
↓
Cloud (entorno principal)
↓
Operación híbrida

---

## 💡 Enfoque

* Migración incremental
* Cloud como entorno principal
* Datacenter como respaldo
* Continuidad operativa asegurada
