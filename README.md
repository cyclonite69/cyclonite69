# 🧠 Richard "Chip" Dougherty  
**Systems Architect • SIGINT-Inspired Geospatial & Wireless Intelligence Systems**

---

### 🔍 Overview
I design and maintain **ShadowCheck**, a layered geospatial signal intelligence ecosystem. My work focuses on the intersection of wireless RF analysis, forensic-grade data processing, and hardened AWS infrastructure. I prioritize system reproducibility, data integrity, and modular architecture over monolithic design.

---

## 🏷️ Stack Badges

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-2E8B57?style=flat)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-000000?style=flat&logo=linux&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=flat&logo=mapbox&logoColor=white)

---

## 🚀 ShadowCheck System Architecture

The ecosystem is structured as a unidirectional data flow pipeline, ensuring strict separation of concerns from field collection to analytical visualization.

### 🛰️ Collection Layer (Data Sources)
*   **WiGLE Integration:** Strategic utilization of external bootstrap datasets for system cold-start and validation.
*   **ShadowCheckMobile:** Developing a first-party Android signal collection suite for high-fidelity, sovereign data capture.

### 📥 Ingestion / Transport Layer
*   **AWS S3 Pipeline (dbcoopers-briefcase):** A dedicated ingestion infrastructure for staging, validating, and moving field telemetry into processing environments.

### ⚙️ Processing Layer (Core Engine)
*   **ShadowCheck:** The primary analytical engine responsible for signal enrichment, emitter classification (transient vs. persistent), and normalization into geospatial datasets.

### 🗺️ Visualization / Control Layer
*   **ShadowCheckWeb:** The primary system interface. A React and Mapbox-driven geospatial intelligence dashboard for real-time analysis and operational interaction.

---

## 🧠 Engineering Philosophy
*   **Structure first, then scale:** Prevent technical debt through rigorous architectural foundations.
*   **Modularity over monoliths:** Distributed, decoupled, and observable components.
*   **Forensic mindset:** Data is evidence; ensure it is traceable and untampered.
*   **Signal over noise:** Aggressive filtering to surface high-value intelligence.
*   **Automation with intent:** Purpose-driven orchestration of system lifecycles.

---

## 📡 Specialized Domains
*   **Wireless / RF Analysis:** SIGINT-inspired signal characterization and tracking.
*   **Geospatial Systems:** PostGIS optimization and coordinate system integrity.
*   **AWS Cloud Infrastructure:** Hardened environments (IAM, S3, EC2 Graviton/ARM64).
*   **Android Systems:** Sideloading, telemetry control, and edge ingestion.
*   **Energetics & Propulsion:** Research into APCP burn dynamics and propulsion patents.

---

## 🛡️ Security & Infrastructure
*   **DNS Hardening:** Privacy-first resolution via Unbound and dnscrypt-proxy.
*   **Enforcement:** Strict DNSSEC validation and UFW-managed security policies.
*   **Least Privilege:** Mandatory non-root execution environments and minimal attack surfaces.

---

## ⌨️ Workflow Style
*   **Multi-agent AI:** Leveraging Claude, GPT, and Gemini for accelerated R&D and logic auditing.
*   **CLI-First:** Terminal-driven engineering and systems administration.
*   **Execution Framework:** Modular Python structures for repeatable research tasks.
*   **Versioned Iteration:** Strict version control and CI/CD for system reproducibility.

---

## 📍 Operating Context
*   **Location:** Flint, Michigan
*   **Experience:** 30+ years in systems engineering and architecture.
*   **Background:** Management Information Systems (MIS).

---

## 🎯 Current Focus
*   **Modular Refactoring:** Transitioning ShadowCheck into a clean, componentized architecture.
*   **Pipeline Reliability:** Hardening the ingestion transport layer for increased field data volume.
*   **Signal Classification:** Enhancing algorithms for precision geospatial enrichment.
*   **Sovereign Collection:** Accelerating the migration from WiGLE dependencies to ShadowCheckMobile.

---

> "Build systems that explain themselves. Trust data you can trace. Eliminate noise until only signal remains."