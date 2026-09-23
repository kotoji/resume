# Hi there, I'm Kenichiro Kadowaki (@kotoji) 👋

<p align="left">
  <strong>Senior Backend & Data Infrastructure Engineer</strong> | Tokyo, Japan<br/>
  <em>Building resilient data platforms, modular backend systems, and AI workflows with a focus on "Simple Made Easy" and "Correctness First".</em>
</p>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kotoji)
[![Email](https://img.shields.io/badge/Email-kenichiro.kadowaki%40ithnote.blue-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kenichiro.kadowaki@ithnote.blue)
[![Resume-EN](https://img.shields.io/badge/Resume-English-blue?style=flat-square&logo=read-the-docs&logoColor=white)](https://github.com/kotoji/resume/blob/main/resume-en.md)
[![Resume-JA](https://img.shields.io/badge/職務経歴書-Japanese-green?style=flat-square&logo=read-the-docs&logoColor=white)](https://github.com/kotoji/resume/blob/main/resume.md)

---

## 🚀 About Me

I am a Software Engineer with over 8.5 years of experience designing and scaling web backends, modern data infrastructure, and cloud systems.

- 🔭 **Current Focus**: Modern Data Lakehouse architectures (**Apache Iceberg**, **Apache Spark**), distributed observability (**OpenTelemetry**), and AI agent workflows (**Mastra**, **Dify**).
- 🛠️ **Core Expertise**: Designing high-throughput Go backends (modular monoliths, gRPC), enterprise identity federation (Keycloak / OIDC), and declarative infrastructure as code (Terraform on AWS).
- 🧠 **Roots**: Background in computational mathematics (M.S.) and scientific computing. Experience engineering numerical simulation software in **Haskell** (`mtl-style`) and building type-safe backend services in **Scala**.

---

## 🛠️ Tech Stack & Skills

<table>
  <tr>
    <td width="20%"><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
      <img src="https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white" alt="Scala"/>
      <img src="https://img.shields.io/badge/Haskell-5D4F85?style=flat-square&logo=haskell&logoColor=white" alt="Haskell"/>
      <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP"/>
      <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
    </td>
  </tr>
  <tr>
    <td><strong>Data & Storage</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Apache_Iceberg-3B82F6?style=flat-square&logo=apache&logoColor=white" alt="Apache Iceberg"/>
      <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Apache Spark"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <img src="https://img.shields.io/badge/AWS_EMR-FF9900?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS EMR"/>
      <img src="https://img.shields.io/badge/Amazon_S3-569A31?style=flat-square&logo=amazons3&logoColor=white" alt="Amazon S3"/>
    </td>
  </tr>
  <tr>
    <td><strong>Cloud & DevOps</strong></td>
    <td>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS"/>
      <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
      <img src="https://img.shields.io/badge/OpenTelemetry-F5A800?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry"/>
    </td>
  </tr>
  <tr>
    <td><strong>Auth & Protocols</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Keycloak-005696?style=flat-square&logo=redhat&logoColor=white" alt="Keycloak"/>
      <img src="https://img.shields.io/badge/OpenID_Connect-F78C40?style=flat-square&logo=openid&logoColor=white" alt="OIDC"/>
      <img src="https://img.shields.io/badge/OAuth_2.0-EB5424?style=flat-square&logo=auth0&logoColor=white" alt="OAuth 2.0"/>
      <img src="https://img.shields.io/badge/gRPC-244F5D?style=flat-square&logo=grpc&logoColor=white" alt="gRPC"/>
    </td>
  </tr>
  <tr>
    <td><strong>AI & Prototyping</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Mastra-000000?style=flat-square&logo=typescript&logoColor=white" alt="Mastra"/>
      <img src="https://img.shields.io/badge/Dify-1677FF?style=flat-square&logo=openai&logoColor=white" alt="Dify"/>
      <img src="https://img.shields.io/badge/RAG_&_Vector_DB-412991?style=flat-square" alt="RAG"/>
      <img src="https://img.shields.io/badge/Prompt_Engineering-10A37F?style=flat-square" alt="Prompt Engineering"/>
    </td>
  </tr>
</table>

---

## 💡 Engineering Philosophies

### 1. "Simple Made Easy"
I prioritize architectures that dismantle entanglement over superficial shortcuts. By giving users direct query capabilities over clean data models rather than layering fragile query-builder abstractions, we delivered value exponentially faster and eliminated long-term maintenance debt.

### 2. "Correctness First, Performance Second"
Drawing from functional programming and systems design, I ensure domain boundaries and data models accurately reflect problem space requirements before optimizing. When tuning is necessary, it is guided strictly by production telemetry (**OpenTelemetry**), never premature assumptions.

### 3. Pragmatic Modular Monoliths
Inspired by production codebases like `containerd`, I favor high cohesion, explicit interfaces, and tag/attribute-based metadata over rigid hierarchies and dogma.

---

## 🏆 Key Achievements & Career Highlights

- **Next-Gen CDP & DWH Architecture (E-Grant, Inc.)**:
  - Architected a greenfield Go modular monolith backend with gRPC and async job workers.
  - Designed the transition to an open data lakehouse stack using **Apache Iceberg**, **Apache Spark on AWS EMR**, and **Aurora PostgreSQL**.
  - Awarded **Company MVP** for replacing complex legacy analytical layers with a simple, high-performance querying architecture.
- **Enterprise Identity & SSO Modernization (E-Grant, Inc.)**:
  - Solely architected and delivered an enterprise-wide identity and access management system based on **Keycloak (OIDC/OAuth 2.0)**, unifying authentication across multi-product SaaS suites.
- **Generative AI Prototyping (E-Grant, Inc.)**:
  - Led AI enablement for automated customer segmentation and copywriting. Bridged business and technical requirements by evolving prototypes from Dify to **Mastra** (TypeScript).
- **Computational Fluid Dynamics R&D (Deepflow, Inc.)**:
  - Engineered aerodynamic simulation engines with unstructured mesh support in **Haskell** (`mtl-style`) and **Python**, benchmarked against **OpenFOAM**.

---

## 📄 Resumes & Detailed Career History

- 🇺🇸 **[English Resume (Markdown)](https://github.com/kotoji/resume/blob/main/resume-en.md)** — Comprehensive career breakdown, impact, and skill details.
- 🇯🇵 **[職務経歴書 / Japanese Resume (Markdown)](https://github.com/kotoji/resume/blob/main/resume.md)** — 日本語版の職務経歴書・自己PR・詳細プロジェクト履歴。

---

## 📬 Contact & Links

- **GitHub**: [@kotoji](https://github.com/kotoji)
- **Email**: [kenichiro.kadowaki@ithnote.blue](mailto:kenichiro.kadowaki@ithnote.blue)
- **Location**: Tokyo, Japan
