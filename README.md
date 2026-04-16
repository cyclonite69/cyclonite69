<div align="center">

# 🧠 Richard "Chip" Dougherty
**Systems Architect • SIGINT-Inspired Geospatial & Wireless Intelligence Systems**

[![Email](https://img.shields.io/badge/Email-cyclonite01%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:cyclonite01@gmail.com)

<br>

[![GitHub Streak](https://streak-stats.demolab.com?user=cyclonite69&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=cyclonite69&theme=tokyonight&show_icons=true&hide_border=true&count_private=true)](https://github.com/anuraghazra/github-readme-stats)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=cyclonite69&theme=tokyonight&show_icons=true&hide_border=true&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

[![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=cyclonite69&theme=tokyo-night&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

### 🔍 Overview
I design and maintain the **ShadowCheck Geospatial Signal Intelligence Platform**. My work focuses on the intersection of wireless RF analysis, forensic-grade data processing, and hardened AWS infrastructure. I prioritize system reproducibility, data integrity, and modular architecture over monolithic design.

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

ShadowCheck is not a collection of isolated projects; it is a unified, layered system designed with strict unidirectional data flow. It ensures forensic-grade data integrity from field capture through to analytical visualization.

### 🛰️ Collection Layer
*   **WiGLE:** External bootstrap dataset utilized strictly for cold-start validation, not a system dependency.
*   **ShadowCheckMobile:** First-party Android RF collection system designed for sovereign, high-fidelity signal capture.

### 📥 Ingestion Layer (AWS S3)
*   **dbcoopers-briefcase:** AWS S3-based infrastructure pipeline handling the staging, validation, and secure transport of raw field telemetry into processing environments.

### ⚙️ Processing Layer
*   **ShadowCheck Core Engine:** The primary analytical engine responsible for signal ingestion, enrichment, emitter classification (differentiating transient vs. persistent), and geospatial normalization into PostGIS.

### 🗺️ Visualization Layer
*   **ShadowCheckWeb:** The primary operational control plane. A React and Mapbox-driven interface providing real-time and historical geospatial intelligence visualization.

---

## 🧠 Engineering Philosophy
*   **Structure first, then scale:** Prevent technical debt through rigorous architectural foundations.
*   **Modularity over monoliths:** Distributed, decoupled, and observable components.
*   **Forensic mindset:** Data is evidence; ensure it is traceable and untampered.
*   **Signal over noise:** Aggressive filtering to surface high-value intelligence.
*   **Automation with intent:** Purpose-driven orchestration of system lifecycles.

---

<details>
<summary><strong>📡 Specialized Domains</strong> (Click to expand)</summary>
<br>

*   **Wireless / RF Analysis:** Wi-Fi, BLE, and spectrum behavior characterization.
*   **Geospatial Systems:** PostGIS optimization and strict coordinate integrity.
*   **AWS Cloud Infrastructure:** Hardened IAM, S3 pipelines, and EC2 Graviton deployment.
*   **Android Systems:** Sideloading, telemetry control, and edge-capture optimization.
*   **Energetics & Propulsion:** Research into APCP burn dynamics and propulsion patents.

</details>

---

<details>
<summary><strong>🛡️ Security & Infrastructure</strong> (Click to expand)</summary>
<br>

*   **DNS Hardening:** Privacy-first resolution via Unbound and dnscrypt-proxy.
*   **Enforcement:** Strict DNSSEC validation and UFW-managed firewall policies.
*   **Least Privilege:** Mandatory non-root execution environments and minimal attack surfaces.

</details>

---

## ⌨️ Workflow Style
*   **Multi-agent AI:** Leveraging Claude, GPT, and Gemini for accelerated logic auditing.
*   **CLI-First:** Terminal-driven engineering and operational administration.
*   **Execution Framework:** Modular Python structures for reproducible research.
*   **Versioned Iteration:** Strict, version-controlled reproducibility across all pipelines.

---

## 📍 Operating Context
*   **Location:** Flint, Michigan
*   **Experience:** 30+ years in systems engineering and architecture.
*   **Background:** Management Information Systems (MIS).

---

## 🎯 Current Focus
*   **ShadowCheck modular refactoring:** Transitioning into a highly componentized architecture.
*   **AWS ingestion pipeline hardening:** Securing the data transport layer for increased volume.
*   **Signal classification improvements:** Enhancing algorithms for precision geospatial enrichment.
*   **Sovereign Collection:** Accelerating the migration from WiGLE dependencies to ShadowCheckMobile.

---

> "Build systems that explain themselves. Trust data you can trace. Eliminate noise until only signal remains."

<br>
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=cyclonite69&style=flat&color=1a1b26&label=PROFILE+VIEWS" alt="Profile Views Counter" />
</div>
