# Resume / Curriculum Vitae

> 📄 **Japanese Version**: [resume.md](./resume.md)

## Basic Information

| Key | Value |
| --- | --- |
| **Name** | Kenichiro Kadowaki (門脇 健一郎) |
| **Date of Birth** | April 13, 1991 |
| **Email** | [kenichiro.kadowaki@ithnote.blue](mailto:kenichiro.kadowaki@ithnote.blue) |
| **GitHub** | [github.com/kotoji](https://github.com/kotoji) |
| **Location** | Tokyo, Japan |

---

## Professional Summary

Accomplished Software Engineer with over 8.5 years of experience architecting and developing web backends, data platforms, and cloud infrastructure.

At E-Grant, Inc., spearheaded the architectural design and implementation of core CRM products and next-generation infrastructure. Led the greenfield development of a Customer Data Platform (CDP) / Data Warehouse (DWH) backend using a Go modular monolith architecture and gRPC, and advanced the next-generation modern data stack with Apache Iceberg and Apache Spark. Solely led an enterprise-wide Single Sign-On (SSO) unification based on Keycloak (OIDC/OAuth 2.0), and drove generative AI / LLM prototyping initiatives using Mastra and Dify. Previously contributed to computational fluid dynamics (CFD) simulation software using Haskell and Python at Deepflow, Inc., and engineered critical backend dispatch engines for disaster safety confirmation services at YMIRLINK, Inc.

Distinguished by a design philosophy centered on **"Simple Made Easy"**—deconstructing complex problems into simple, durable architectures—and **"Correctness First, Performance Second"**. Recognized for strong technical leadership, rapid mental model acquisition, and a proven track record of elevating organizational engineering capabilities through hands-on mentoring and technical workshops.

---

## Career Summary

| Period | Company | Role |
| --- | --- | --- |
| Jan 2021 – Oct 2026 | **E-Grant, Inc.** | Tech Lead / Senior Software Engineer |
| Jul 2019 – Mar 2020 | **Deepflow, Inc.** | Software Engineer (R&D Contractor) |
| Apr 2018 – Jun 2019 | **YMIRLINK, Inc.** | Software Engineer |

---

## Work Experience

### E-Grant, Inc. (Jan 2021 – Oct 2026)

*Provider of marketing automation and CRM SaaS platforms for enterprise clients.*

<table>
<tr>
<th width="14%">Period</th>
<th width="46%">Project & Responsibilities</th>
<th width="14%">Languages</th>
<th width="14%">Key Technologies</th>
<th width="12%">Role & Team</th>
</tr>
<tr>
<td>Apr 2026 –<br/>Oct 2026</td>
<td>
<strong>LLM Integration & Generative AI Enablement</strong><br/>
Led PoC and prototyping for automated customer segmentation and copywriting using Mastra and Dify. Established collaborative Biz/Dev engineering framework.
</td>
<td>TypeScript<br/>Python</td>
<td>Mastra, Dify<br/>Prompt Engineering<br/>Vector DB, RAG</td>
<td>Lead Engineer<br/>(1-2 members)</td>
</tr>
<tr>
<td>Oct 2023 –<br/>Oct 2026</td>
<td>
<strong>Next-Gen CDP & DWH Platform</strong><br/>
Spearheaded greenfield design and development of Go+gRPC modular monolith backend and async workers. Led next-gen data architecture using Apache Iceberg and Spark.
</td>
<td>Go<br/>Python</td>
<td>gRPC, PostgreSQL<br/>Apache Spark<br/>Apache Iceberg<br/>OpenTelemetry</td>
<td>De-facto Tech Lead<br/>(2 → 6 members)</td>
</tr>
<tr>
<td>Aug 2023 –<br/>Dec 2023</td>
<td>
<strong>Offshore Service Containerization & CI/CD Pipeline</strong><br/>
Overhauled offshore codebases to comply with 12-Factor App principles. Containerized on AWS ECS and established automated CI/CD and IaC standards.
</td>
<td>PHP</td>
<td>Laravel, AWS ECS<br/>CodePipeline<br/>Terraform</td>
<td>Lead Engineer<br/>(2 members)</td>
</tr>
<tr>
<td>Aug 2022 –<br/>Aug 2023</td>
<td>
<strong>Multi-Tenant Analytics Service Modernization</strong><br/>
Led codebase architecture with dynamic DI multi-tenancy. Built stateless ECS infrastructure via Terraform and led team-wide cloud transition.
</td>
<td>PHP<br/>Go</td>
<td>Laravel, AWS ECS<br/>Terraform<br/>PostgreSQL</td>
<td>Sub-Lead<br/>(4 members)</td>
</tr>
<tr>
<td>Oct 2021 –<br/>Oct 2026</td>
<td>
<strong>Enterprise Single Sign-On (SSO) Platform</strong><br/>
Independently architected and implemented company-wide identity and access management using Keycloak (OIDC/OAuth 2.0) across all SaaS products.
</td>
<td>Go<br/>TypeScript<br/>PHP</td>
<td>Keycloak<br/>OIDC, OAuth 2.0<br/>AWS ECS, Lambda</td>
<td>Sole Owner<br/>(1 member)</td>
</tr>
</table>

#### Project Highlights & Details

#### 1. LLM Integration & Generative AI Enablement (Apr 2026 – Oct 2026)
- **Keywords**: TypeScript, Python, Mastra, Dify, Prompt Engineering, RAG, Vector DB
- **Responsibilities & Outcomes**:
  - Drove feasibility exploration and PoC initiatives to integrate LLM capabilities into CRM, focusing on automated customer segmentation and targeted email/LINE copy generation.
  - Accelerated initial PoC velocity using **Dify**, then transitioned to **Mastra** (TypeScript AI agent framework) to ensure software engineering rigor, testability, and seamless integration with existing services.
  - Bridged the expectation gap with business stakeholders by providing interactive sandboxes, fostering a healthy partnership where business proposed use cases while engineering led architectural design and implementation.

#### 2. Next-Gen CDP & DWH Platform (Oct 2023 – Oct 2026)
- **Keywords**: Go, gRPC, Echo, GORM, OpenTelemetry, Aurora PostgreSQL, AWS EMR (Apache Spark), S3 Tables (Apache Iceberg), Jupyter Notebook, Python
- **Responsibilities & Outcomes**:
  - Served as main architect and de-facto Tech Lead, engineering the core gRPC backend and async job workers from scratch.
  - Applied design principles inspired by open-source systems like `containerd`, creating a practical **modular monolith** that balances maintainability and high performance without dogma.
  - Replaced over-engineered, opaque analytical UI layers with an architecture that allows direct SQL querying and table creation, embodying the **"Simple Made Easy"** principle and winning a prestigious **Company MVP Award**.
  - Enforced a **"Correctness First, Performance Second"** philosophy: prioritized domain model precision, implemented end-to-end observability via **OpenTelemetry (OTel)** tracing/metrics, and tuned performance strictly based on production data.
  - Adopted tag/attribute-based metadata management (inspired by Docker labels and Obsidian) rather than rigid hierarchical directory structures, dramatically improving extensibility.
  - Spearheaded PoCs and architectural planning for next-gen big-data workloads using **AWS EMR (Spark) + S3 Tables (Apache Iceberg) + Jupyter Notebook (ECS)**.

#### 3. Enterprise Single Sign-On (SSO) Platform (Oct 2021 – Oct 2026)
- **Keywords**: Keycloak, OpenID Connect (OIDC), OAuth 2.0, Go, TypeScript, AWS Lambda, ALB, ECS, Route 53, Laravel
- **Responsibilities & Outcomes**:
  - Independently took full ownership of designing, building, and rolling out an enterprise-grade IAM/SSO infrastructure to centralize user identity across multi-product suites.
  - Built an industry-standard **Keycloak** identity foundation compliant with OIDC / OAuth 2.0, conducted security risk assessments, and created client SDKs / Lambda authenticators for cross-service integration.
  - Authored tailored technical guides and architectural blueprints, establishing consensus across disparate product teams through clear, opinionated specifications.

#### 4. Offshore Service Containerization & CI/CD Pipeline (Aug 2023 – Dec 2023)
- **Keywords**: PHP, Laravel, AWS ECS, AWS CodeDeploy, AWS CodePipeline, Terraform
- **Responsibilities & Outcomes**:
  - Integrated and refactored multiple services developed by offshore teams; migrated logging and configuration to conform with 12-Factor App standards.
  - Constructed automated CI/CD delivery pipelines on AWS ECS, ensuring consistent, repeatable production deployments.
  - Organized company-wide **Terraform Study Sessions** to eliminate IaC anti-patterns (such as post-manual-setup imports), instilling declarative IaC standards and code review practices.

#### 5. Multi-Tenant Analytics Service Modernization (Aug 2022 – Aug 2023)
- **Keywords**: PHP, Laravel, Go, Aurora PostgreSQL, AWS ECS, Terraform
- **Responsibilities & Outcomes**:
  - Spearheaded codebase redesign to replace a legacy CakePHP / MySQL 5.6 monolith with a modern multi-tenant service.
  - Implemented dynamic dependency injection (DI) tied to the request lifecycle for robust tenant isolation. Introduced Go for high-speed CLI automation tooling.
  - Architected a completely stateless ECS infrastructure managed via Terraform, eliminating legacy anti-patterns (such as shared EFS mounts), and led team hands-on sessions for cloud readiness.

---

### Deepflow, Inc. (Jul 2019 – Mar 2020)

*Specialized research and development firm for numerical simulation software.*

#### Computational Fluid Dynamics (CFD) Simulation Software R&D
- **Role**: Software Engineer (R&D Contractor)
- **Keywords**: Haskell, Python, OpenFOAM, gmsh, Unstructured Mesh
- **Responsibilities & Outcomes**:
  - Researched and developed aerodynamic and thermal-fluid numerical simulation engines capable of processing complex geometric boundaries using multiple **unstructured meshes (Unstructured Mesh)**.
  - Generated mesh models via **gmsh** and cross-verified physical fidelity and simulation correctness against industry-standard **OpenFOAM** benchmarks.
  - Implemented mathematical and physical algorithms in **Haskell** using **`mtl-style`** (Monad Transformer Library) after initial algorithmic prototyping in Python, gaining deep expertise in pure functional architectures and type-level effect management.
  - Grounded foundational engineering philosophies: *“Correctness first, performance second”* and rigorous domain modeling.

---

### YMIRLINK, Inc. (Apr 2018 – Jun 2019)

*Developer of high-volume messaging and emergency notification systems.*

#### Disaster Safety Confirmation Service Development
- **Role**: Software Engineer
- **Keywords**: Perl, MySQL, In-house Framework
- **Responsibilities & Outcomes**:
  - Joined from requirements definition through design and development for the launch of a mission-critical disaster safety confirmation service.
  - Architected high-throughput backend dispatch systems capable of parsing Japan Meteorological Agency disaster alerts, instantly pinpointing affected geographic regions, and reliably distributing emergency mass alerts.

---

## Technical Skills

### Programming Languages
- **Go**: Deepest proficiency in production. Designed greenfield modular monoliths, gRPC microservices, and asynchronous background workers inspired by open-source codebases like `containerd`.
- **Python**: Extensive use for data analysis, algorithmic prototyping, and generative AI integrations (Dify, RAG pipelines).
- **TypeScript / JavaScript**: Full-stack capability across frontends, microservices, and modern AI agent frameworks (Mastra).
- **PHP**: Proven expertise in large-scale multi-tenant Web architectures, dynamic DI containers (Laravel), and containerized deployments.
- **Scala**: Solid grasp of functional programming (Cats Effect, FS2, PlayFramework, ScalikeJDBC) with deep respect for strong type systems.
- **Haskell**: Production experience in commercial numerical simulation engines utilizing `mtl-style` monad transformers.
- **Others**: C++, Java, Perl, SQL

### Cloud, Infrastructure & Data Platforms
- **Amazon Web Services (AWS)**: ECS, Lambda, VPC, ALB, Route 53, SQS, Aurora PostgreSQL, S3, CodePipeline. Production infrastructure provisioning via **Terraform**.
- **Data Infrastructure**: Apache Spark, Apache Iceberg (S3 Tables), AWS EMR, DWH Architectural Design, Jupyter Notebook.
- **Generative AI & LLM**: Mastra, Dify, RAG architectures, Vector Databases, Prompt Engineering.
- **Containers & Observability**: Docker, Kubernetes, OpenTelemetry (distributed tracing & metrics), gRPC, Keycloak (OIDC / OAuth 2.0).

---

## Education

| Period | Degree | Institution |
| --- | --- | --- |
| Apr 2016 – Mar 2018 | **Master of Science in Mathematical and Information Sciences** | Tokyo Metropolitan University (formerly Capital University of Tokyo) |
| Apr 2011 – Mar 2016 | **Bachelor of Engineering in Mechanical Engineering** | Kanazawa University |

---

## Certifications

- **Applied Information Technology Engineer Examination (AP)** – Information-technology Promotion Agency (IPA), Japan
- **Fundamental Information Technology Engineer Examination (FE)** – Information-technology Promotion Agency (IPA), Japan

---

## Core Strengths & Engineering Philosophy

### 1. Deconstructing Complexity into Simplicity ("Simple Made Easy")
I continuously seek solutions that solve problems at their root rather than adding layers of complexity. When developing our DWH service, rather than introducing an opaque, fragile GUI query builder that would delay delivery, I championed an approach enabling users to write direct SQL against well-structured tables. By distinguishing "Simple" (unentangled) from "Easy" (familiar shortcuts), we delivered high business value on an aggressive timeline and won an internal company award.

### 2. Rapid Mental Model Acquisition & Organizational Knowledge Transfer
When adopting new paradigms or technologies, I swiftly master core mental models and distill them into actionable knowledge for the wider organization:
- **LLM / AI**: Rapidly evaluated Dify and Mastra to bridge knowledge gaps between business teams and engineering through tangible PoCs.
- **Modern Data Platforms**: Proactively researched Apache Iceberg and Spark, conducting internal workshops that guided our next-generation architecture.
- **Infrastructure & Identity**: Led study sessions on Terraform, Docker/ECS, and OIDC/OAuth 2.0 (Keycloak), conveying not just syntax, but the architectural principles and design history behind them.

### 3. Constructive Collaboration & Engineering Mentorship
Drawing from open-source contributions and cross-functional team leadership, I prioritize constructive problem-solving over dogma. Instead of asking "Why isn't it done this way?", I focus on proposing positive, actionable alternatives: "How about we explore this approach?". As a technical mentor, I adapt my coaching to each engineer’s existing mental model, empowering junior team members to grow while helping foster an empathetic, high-velocity engineering culture.
