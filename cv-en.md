# NASR LADIB
## Senior Platform Engineer | DevOps • Cloud • Observability | Kubernetes | GCP • AWS • Azure | IaC | OpenTelemetry

7 years of experience
✉ ladibnasr@gmail.com
📍 Lille, France  
🔗 [LinkedIn](https://www.linkedin.com/in/nasr-ladib)  
📝 [Medium](https://nasrladib.medium.com) 
🖥️ [GitHub](https://github.com/Nasr-Ladib) 

## PROFESSIONAL SUMMARY
Senior Platform Engineer with 7 years of experience building and operating cloud-native platforms at scale. Currently driving platform engineering at Decathlon, designing multi-cloud provisioning systems (GCP, Aiven, Vault, MongoDB Atlas), building observability platforms with OpenTelemetry, and developing custom Terraform providers and internal developer tooling in Go and Python. Deep expertise in Kubernetes, infrastructure as code, CI/CD automation, database reliability engineering, and FinOps. Proven track record of accelerating developer productivity through self-service platforms, GitOps workflows, and robust monitoring solutions across AWS, GCP, and Azure.

## SKILLS

#### Cloud Platforms
**AWS:** EC2, S3, RDS, CloudWatch, EKS, Lambda, CloudFront, Route53, EventBridge, Inspector, Config, Control Tower, Landing Zone  
**GCP:** GKE, Cloud Run, Cloud Functions, Pub/Sub, BigQuery, GCS, IAM, Cloud Scheduler, Cloud Workflows, Alloy DB, Cloud SQL  
**Azure:** AKS, Azure DevOps  
**Managed Services:** Aiven (PostgreSQL, Kafka, Redis, Valkey, OpenSearch), MongoDB Atlas, Cloudflare  

#### Container & Orchestration
**Container Technologies:** Docker, Docker Compose, Podman  
**Kubernetes Ecosystem:** Kubernetes, Helm, Kubeadm, ArgoCD, Kustomize, Cilium CNI  
**Database Containers:** CloudNative PG, PGBouncer  

#### CI/CD & GitOps
**CI Systems:** GitHub Actions, GitLab CI, Jenkins, AWS CodeBuild, Bamboo  
**CD Systems:** ArgoCD, GitOps workflows  
**Workflow Engineering:** Reusable GitHub Actions (composite actions, reusable workflows), release-please  
**Package Management:** Nexus Pro  

#### Infrastructure as Code
**Provisioning:** Terraform, CloudFormation  
**Custom Providers:** Terraform Plugin Framework (Go), custom Terraform provider development  
**Configuration Management:** Ansible, AWX  
**Tools:** tflint, pre-commit, Snyk  

#### Monitoring & Observability
**OpenTelemetry:** OTel Collector, OpAMP, OTLP, auto-instrumentation, custom exporters  
**Metrics & Monitoring:** Prometheus, Grafana, Datadog, CloudWatch  
**Logging:** ELK Stack, Google Cloud Logging  
**Error Tracking:** Sentry  
**Custom Tooling:** Built self-contained observability platform (Go + React)  

#### Security
**Secret Management:** HashiCorp Vault (policies, auth backends, KV, GCP auth)  
**Static Analysis:** SonarQube, SonarCloud  
**Vulnerability Scanning:** Trivy, Checkmarx (DAST & SCA), Snyk  
**Dependency Management:** Dependabot, Renovate  
**Access Control:** RBAC, Keycloak  

#### Data & Storage
**Databases:** PostgreSQL, Redis, Valkey, OpenSearch, MongoDB Atlas, RDS, DuckDB  
**Messaging:** Kafka, RabbitMQ  
**Database Tooling:** Flyway, DBLinter, pgwatch, pgbackup, CloudBeaver  
**DATA Platform:** Snowflake  

#### Web Servers & Proxy
**Web Servers:** Nginx, Apache, Haproxy, Traefik  
**Protocols:** HTTP/HTTPS, SSH, FTP  

#### DevOps & SRE Practices
**Methodologies:** Agile, Scrum, GitOps, DevSecOps  
**Version Control:** Git, GitFlow, Conventional Commits  
**Systems:** Linux, CentOS  
**Testing:** pytest, Allure, Selenium, JUnit, K6 (load testing)  
**Documentation:** MkDocs (Material), Marp  
**Self-Service Platform:** Backstage  

#### Programming & Scripting
**Languages:** Python, Go, Bash  
**Python Ecosystem:** FastAPI, Pydantic, SQLModel, asyncpg, Typer, uv, Poetry  
**Go Ecosystem:** Gin, Terraform Plugin Framework, goreleaser  
**Frontend:** React, TypeScript, Vite  
**ML/AI Tools:** Airflow, MLflow  

## PROFESSIONAL EXPERIENCE

<div style="display: flex; margin-bottom: 20px; page-break-inside: avoid;">
<div style="width: 25%; padding-right: 20px;">

<img src="https://upload.wikimedia.org/wikipedia/commons/b/bc/Decathlon_-_logo_%28France%2C_2024%29.svg" width="100" alt="Decathlon">

**Decathlon Digital**

<!-- TODO: adjust duration -->
6 months

<!-- TODO: adjust start date -->
November 2025 - Present

Lille, France
</div>
<div style="width: 75%;">

### Senior Platform Engineer (CPE / DBRE)

**Platform & IaC:** Building and operating the "3S" internal developer platform for multi-cloud application provisioning

* Contributed to the **internal developer platform** — declarative provisioning of GCP, GKE, Aiven, Vault, MongoDB Atlas, Cloudflare, and Datadog via a single YAML stack definition, serving 1000+ product teams
* Built **reusable CI/CD workflows** (GitHub Actions) standardizing Terraform plan/apply/destroy across 50+ stack repositories
* Developed a **custom Terraform provider in Go** for Aiven project management, published to the internal registry
* Created the **Aiven Projects Manager API** (FastAPI, Cloud Run, OpenTelemetry) and **FinOps tooling** (BigQuery, GCS) for database governance and cost control

**Observability & Reliability:**

* Implemented **DBLinter pipeline** for automated database quality scanning with SARIF report ingestion and Flyway migrations
* Managed **Vault infrastructure**, **Kubernetes DBA workloads** (GKE/EKS), and database lifecycle automation (dump/restore/refresh)
</div>
</div>

<div style="display: flex; margin-bottom: 20px; page-break-inside: avoid;">
<div style="width: 25%; padding-right: 20px;">

<img src="https://upload.wikimedia.org/wikipedia/fr/a/a6/Cr%C3%A9dit_Agricole.svg" width="100" alt="Credit Agricole">

**Crédit Agricole Personal Finance & Mobility**

10 months

February 2025 - October 2025

Roubaix, France
</div>
<div style="width: 75%;">

### Cloud Engineer

**STAR Project:** Centralized Data Platform with AI and Data Science capabilities for 3000+ employees
* Led technical workshops to design a compliant, reusable data platform with decoupled architecture across business units
* Refactored code to Python and implemented application observability components
* Partnered with Data & Security Architects to deliver a production Snowflake lakehouse on AWS: built a dedicated landing-zone account, set up PrivateLink networking, and enforced KMS encryption on all S3 stages.
* Built modular data-ingestion & integration pipelines (Glue / Snowpipe / Data Factory) feeding Snowflake.
* Developed Terraform code for infrastructure components
* Managed compliance with AWS Landing Zone, Control Tower, AWS Config, AWS Inspector
* Implemented event-driven architecture using Lambda functions, AWS Batch for corporate account notifications
* Built CI/CD pipelines for Python component builds and deployments, adding OpenTelemetry as standard for observability applications
* Worked on the project "CEOS AI" as part of STAR implementing Airflow, MLflow, and LLM on EKS for multi-tenancy
</div>
</div>

<div style="display: flex; margin-bottom: 20px; page-break-inside: avoid;">
<div style="width: 25%; padding-right: 20px;">

<img src="https://logo-marque.com/wp-content/uploads/2021/02/Auchan-Logo.png" width="100" alt="Auchan">

**AUCHAN RETAIL INTERNATIONAL**

2 years 8 months
June 2022 - January 2025
Lille, France
</div>
<div style="width: 75%;">

### DevSecOps & Cloud Consultant

**DevOps Team:** Working as center team for all the projects of Auchan, collaborating with 50+ projects across the organization

* Designed and implemented CI/CD pipelines to automate production deployment processes
* Managed compliance, governance, and standardization through Python and Bash scripts across tools (GitHub, GitHub Actions, ArgoCD, AWX)
* Developed Terraform code for technical modules aligned with architectural requirements for Azure and GCP infrastructures
* Implemented CI/CD pipelines via GitHub Actions to automate infrastructure provisioning and deployment
* Integrated SAST with SonarQube for static code analysis across all repositories
* Implemented Dependabot/Renovate for automated dependency updates to strengthen application security
* Integrated Checkmarx for DAST and SCA to secure applications through dynamic analysis
* Centralized ArgoCD management for Kubernetes application deployment across the organization
* Deployed containerized applications on Google Kubernetes Engine (GKE) and AKS
* Used Nexus Pro to centralize package managers with proxies for unified monitoring
* Deployed and managed AWX with Ansible playbooks for virtual machine lifecycle management for 10,000 machines
* Developed Backstage-based DevGate platform for self-service engineering workflows
* Built internal applications using Django, Spring, and Next.js deployed as containers in AKS
* Configured internal GitHub Actions runners with dynamic scaling from 20-200 instances
* Implemented Prometheus and Grafana for application monitoring
* Centralized DORA metrics via Pub/Sub, Cloud Run, and BigQuery for delivery performance visibility
* Integrated Keycloak with proxies for role-based access controls across tools
* Helped iOS team build applications with GitHub Actions and FastLane, migrating to internal macOS runners for cost optimization
</div>
</div>

<div style="display: flex; margin-bottom: 20px; page-break-inside: avoid;">
<div style="width: 25%; padding-right: 20px;">

<img src="https://media.licdn.com/dms/image/v2/D4E0BAQEVA8qVNEAZjQ/company-logo_200_200/company-logo_200_200/0/1723047262516/skillcapinc_logo?e=2147483647&v=beta&t=FFg1aRMRoOi13g-y11QMxaDrs1tSPR5_KXSpSfpTWPw" width="100" alt="Skillcap">

**Skillcap Studio**
2 months
May 2024 - June 2024
Santiago, Chile (Part-Time Remote)
</div>
<div style="width: 75%;">

### Cloud Engineer

**Web3 NFT Blockchain Gaming Project:**
* **CI/CD Implementation:** Set up GitHub Actions workflows, integrated Dependabot, configured GCP registry pipelines
* **Containerization:** Dockerized client/worker/API components, optimized for x86_64, implemented environment management
* **Cloud Infrastructure:** Deployed to GKE, implemented ArgoCD with GitHub integration, established VPC networking
* **Database Solutions:** Optimized PostgreSQL (CNPG) with connection pooling, scaled node infrastructure, implemented Redis persistence
* **Resource Management:** Tuned application resources, implemented monitoring, resolved caching issues, optimized asset delivery
* **Security Implementation:** Managed access controls, secured credentials, implemented network policies for public-facing services
</div>
</div>

<div style="display: flex; margin-bottom: 20px; page-break-inside: avoid;">
<div style="width: 25%; padding-right: 20px;">

<img src="https://upload.wikimedia.org/wikipedia/commons/7/79/Dev_logo_rgb.png" width="100" alt="Devoteam">

**Devoteam**

5 months
January 2022 - May 2022
France
</div>
<div style="width: 75%;">

### DevOps & Cloud Engineer

* Initialized and managed Kubernetes clusters using Kubeadm and CRI Docker across multiple environments with Cilium CNI
* Built comprehensive CI/CD pipelines with GitLab CI including compilation, unit testing, end-to-end testing, and code review with SonarQube
* Implemented artifact management in Nexus for Docker images and Java artifacts with proper versioning
* Configured continuous delivery with ArgoCD for Kubernetes applications with Slack notification integration
* Automated daily tasks and increased system reliability through HELM implementation for Kubernetes chart management
* Secured pipelines by integrating Trivy for security scanning and implemented HashiCorp Vault for secrets management with githooks
* Configured Prometheus alerting with email notifications for proactive monitoring
</div>
</div>

<div style="display: flex; margin-bottom: 20px; page-break-inside: avoid;">
<div style="width: 25%; padding-right: 20px;">

<img src="https://play-lh.googleusercontent.com/1Sxo8b_WErvgb9iHO35UaUEWKU79B88Z9avAls79_CHbHF8tSTzIzYmo3MZWArG4cg=w480-h960-rw" width="100" alt="KooL Delivery">

**KooL Delivery**

2 months
December 2021 - January 2022
Tunisia
</div>
<div style="width: 75%;">

### Cloud & SRE Engineer

**Context:** Kool Delivery, a delivery startup that launched a mobile application in 2021 and experienced significant growth throughout the year, requiring scalable cloud infrastructure to support its expansion.

* Developed architectural diagrams and detailed documentation including bills of materials for necessary Cloud services
* Designed and implemented high-availability cloud architecture to support peak workloads for optimal performance
* Implemented AWS CloudFormation templates to automate static website configuration including Amazon S3, CloudFront, and Route53
* Configured and optimized cloud services including VPC, EC2, EBS, RDS, S3, CloudWatch, and Elastic Load Balancing
* Implemented resource optimization strategies to ensure scalability and cost efficiency
</div>
</div>

<div style="display: flex; margin-bottom: 20px; page-break-inside: avoid;">
<div style="width: 25%; padding-right: 20px;">

<img src="https://yaiglobal.com/static/media/logo.bd3372e3dc948eae5df8.png" width="100" alt="YaiGlobal">

**YaiGlobal**

3 years 1 month
January 2019 - January 2022
Tunisia
</div>
<div style="width: 75%;">

### DevOps & Cloud Engineer

**Project Focus:** Working on solutions for data labeling applications to facilitate the labeling of various data types (audio, video, text) for AI/ML workflows

* Applied Agile methodologies (Scrum, Sprints, Iterations) to improve team performance and deliverable quality
* Designed and implemented Git-Flow strategy integrated with continuous integration pipelines
* Architected optimal AWS cloud solutions for company software, ensuring efficiency and scalability
* Collaborated with development and testing teams to identify and resolve integration issues
* Managed versioning with Git including branching, merging, tagging across environments in Bitbucket Cloud
* Created Dockerfiles and Docker Compose configurations for containerized applications
* Built and deployed artifacts with npm, Maven, and Composer to different environments via Bitbucket Cloud pipelines
* Configured Bamboo as a continuous integration server for automated release management and delivery pipelines
* Managed Docker images on Docker Hub with proper tagging for version control
* Implemented Kubernetes for container orchestration, including on-premises cluster setup with Kubeadm
* Migrated on-premises Kubernetes cluster to AWS EKS
* Integrated automated testing with Selenium and JUnit with email reporting capabilities
* Configured CentOS servers with required services (Apache, Nginx, SSH, FTP, HTTPS)
* Generated code coverage reports with SonarQube and implemented Quality Gates for Pull Requests
* Created Ansible playbooks, inventories, and roles to automate repetitive infrastructure tasks
</div>
</div>


## EDUCATION

**Ecole Supérieure Privée d'Ingénierie et de Technologies - ESPRIT**  
*Software Engineering Degree (2016 - 2019)*

**National Institute of Applied Science and Technology**  
*Higher Technical Diploma (2014 - 2017)*

## CERTIFICATIONS
* CKS: Certified Kubernetes Security Specialist (2024)
* AWS Certified Solutions Architect – Associate (SAA-C03)
* HashiCorp Certified: Terraform Associate
* Certified Kubernetes Administrator (CKA) - The Linux Foundation
* Cisco Certified Network Associate Routing and Switching (CCNA)
* Cilium Cluster Mesh
* Machine Learning with Python - IBM


## LANGUAGES
* English (Professional)
* French (Native)
* Arabic (Native)

## PUBLICATIONS & OPEN SOURCE
* [Enforcing Secure and Cost-Effective Infrastructure as Code with Terraform, OPA, and Infracost](https://medium.nasrladib.com/enforcing-secure-and-cost-effective-infrastructure-as-code-with-terraform-opa-and-infracost-22b4b4c880c2)
* [Kubernetes Operator - k8s-secret-expiry-controller](https://github.com/devops-360-online/k8s-secret-expiry-controller) - Created a custom Kubernetes operator to manage secret expiration
* [TALQ AI VOICE](https://www.youtube.com/watch?v=6TgvjRT1kvQ)





CONVERT TO PDF: https://apitemplate.io/pdf-tools/convert-markdown-to-pdf/
