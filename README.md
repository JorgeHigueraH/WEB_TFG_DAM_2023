# MasterBills: Enterprise & User Billing Ecosystem (2023)

### Technical Maturity and Security Audit
**Note for technical evaluators:** This repository contains the Final Degree Project for my Associate Degree in Multi-platform Applications Development (DAM) from May 2023. 

As a Software Engineer now focused on AI and MLOps, I maintain this project as a public archive of my foundational skills in systems architecture. However, I must state that this codebase contains several legacy practices that do not align with my current professional standards:
* **Security:** Sensitive configuration files (.env) were committed to the history. This is a critical security error that I now strictly avoid through proper secret management.
* **Version Control:** Commit messages are non-standard and lack descriptive quality. I currently utilize Semantic Commits (Conventional Commits) for all professional work.
* **Integrity:** This project is for archival purposes only and is no longer functional or maintained.

---

## Project Overview
MasterBills is a full-stack digital ecosystem designed to centralize service-based business management and user billing. It facilitates a direct connection between merchants (POS) and customers (Management Dashboard).

### Functional Scope
* **Client Side:** Geolocation of nearby services, integrated mobile payments, and automated invoice storage via QR code ingestion.
* **Merchant Side:** Administrative HUB for service rate management, employee task distribution, and automated customer communication.
* **AI Implementation:** Initial integration of OpenAI's API for the generation of automated marketing and transactional emails.

## Technical Architecture
This repository hosts the Web Infrastructure of the ecosystem, implemented with a modular approach:

* **Backend:** PHP 8+ utilizing the Symfony Framework (MVC Pattern).
* **Database Management:** Relational MySQL managed via Doctrine ORM and automated migrations.
* **Security Layer:** Implementation of Argon2 for password hashing and managed session control.
* **Frontend:** Twig template engine for server-side rendering, Bootstrap for responsive design, and Chart.js for financial data analytics.
* **External APIs:** Stripe API for payment processing and OpenAI for LLM-assisted features.

**Note:** The ecosystem included a desktop Point of Sale (POS) component developed in Java and JavaFX, which is currently stored in a private repository.

## Directory Structure
* `/src`: Core business logic (Controllers, Entities, Repositories).
* `/migrations`: Version control for database schema.
* `/templates`: UI components and view logic.
* `/public`: Entry point and static asset management.
* `docker-compose.yml`: Initial containerization setup for development environments.

---

## Strategic Evolution
Managing the lifecycle of this full-stack application provided the engineering foundations necessary for my current specialization in MLOps, specifically regarding:
1. Orchestration of production-ready APIs.
2. Automation of data pipelines and ETL processes.
3. System monitoring and infrastructure security.

**Author:** Jorge Higuera Herrero - May 2023
