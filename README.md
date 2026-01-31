# GHOST-SIGHT: IA Táctica y Conciencia Volumétrica 3D

![GHOST-SIGHT Banner](https://img.shields.io/badge/Status-Project_Live-brightgreen?style=for-the-badge&logo=target)
![NATO DIANA](https://img.shields.io/badge/NATO-DIANA_Accelerator-blue?style=for-the-badge&logo=shield)
![Security](https://img.shields.io/badge/ENS-Nivel_Alto-red?style=for-the-badge&logo=lock)

**GHOST-SIGHT (Global Hostile Operational Surveillance & Tactical AI)** es la plataforma definitiva de digitalización táctica para unidades de élite. Transformamos el adiestramiento CQC (Close Quarters Combat) de una evaluación subjetiva a una ciencia basada en datos objetivos mediante LiDAR de estado sólido e IA en el borde.

---

## 👁️ Visión General
GHOST-SIGHT resuelve el "punto ciego" del análisis táctico, proporcionando una reconstrucción volumétrica milimétrica de cada movimiento, disparo y cobertura, incluso en condiciones de visibilidad cero.

> [!IMPORTANT]
> **Propósito Dual:** Diseñado para la defensa nacional y la seguridad interna, con total interoperabilidad bajo estándares OTAN.

---

## 🏗️ Arquitectura del Sistema

```mermaid
graph TD
    A[Capa Táctica: LiDAR Ouster OS1] -->|Nube de Puntos 3D| B[Capa de Análisis: NVIDIA AGX Orin]
    C[IA Pose Estimation] --> B
    B -->|Métricas en Realidad Aumentada| D[Dashboard Instructor]
    B -->|Digital Twin Inmersivo| E[Servidor de Misión Dell Rugged]
    E -->|After Action Review| F[Debriefing Virtual 3D]
    
    style A fill:#1a1a1a,stroke:#00ff00,color:#fff
    style B fill:#1a1a1a,stroke:#00d2ff,color:#fff
    style E fill:#1a1a1a,stroke:#ff00ea,color:#fff
```

---

## 🎯 Capacidades Críticas
- **🛡️ Disciplina de Cañón (Muzzle Sweep):** Alertas instantáneas (<100ms) si un cañón cruza la silueta de un aliado.
- **⚡ Velocidad de Entrada (Breach Velocity):** Medición de aceleración y fluidez en el asalto.
- **📉 Exposición Volumétrica:** Cálculo exacto de cuánta superficie corporal fue visible desde ángulos enemigos.
- **🌫️ Operación en Humo/0-Lux:** El LiDAR crea un mapa perfecto donde las cámaras convencionales fallan.

---

## 🗺️ Despliegue en Unidades Tier 1 (España)

| Unidad | Sede de Excelencia | Foco Estratégico |
| :--- | :--- | :--- |
| **MOE** | 🇪🇸 Alicante (Rabasa) | Operaciones Especiales de alta intensidad. |
| **GAR** | 🇪🇸 Logroño (PEFE) | Contraterrorismo y combate urbano/híbrido. |
| **GEO** | 🇪🇸 Guadalajara | Protección de altas personalidades y asaltos críticos. |
| **FGNE** | 🇪🇸 Cartagena | Guerra Naval Especial y abordajes (MIO). |
| **EMMOE** | 🇪🇸 Jaca | Investigación biomecánica y formación avanzada. |

---

## 🔄 Ciclo de Vida del Proyecto

```mermaid
sequenceDiagram
    participant S as Sensores (LiDAR)
    participant E as Edge IA (Orin)
    participant D as Digital Twin
    participant I as Instructor (Tablet/AR)

    S->>E: Captura Volumétrica (20Hz)
    E->>E: Análisis de Pose y Trayectoria
    E->>I: Alerta de Peligro (Realidad Aumentada)
    E->>D: Sincronización de Sesión
    D->>I: Visualización AAR 3D Post-Misión
```

---

## 🌍 Alineación Estratégica: NATO DIANA
GHOST-SIGHT participa activamente en el acelerador **NATO DIANA**, promoviendo la estandarización de los "Gemelos Digitales Tácticos" para permitir la interoperabilidad federada (FMN Spiral 4) entre naciones aliadas.

---
**Timestamp:** 2026-01-31
**Nivel de Seguridad:** Confidencial GHOST-SIGHT
**Desarrollado con:** 💻 [Vibecoding](https://github.com/topics/vibecoding) & Antigravity AI
