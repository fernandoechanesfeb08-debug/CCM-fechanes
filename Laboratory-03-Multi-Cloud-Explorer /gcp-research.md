# Google Cloud Platform (GCP) Research

## Brief Overview
Google Cloud Platform is Google's public cloud offering, launched in 2008 (App Engine) and expanded significantly through the 2010s. GCP leverages the same global infrastructure that powers Google Search, YouTube, and Gmail, and is particularly known for its strengths in data analytics, artificial intelligence/machine learning, and container orchestration — Google created and open-sourced **Kubernetes**, which remains central to its container strategy.

## Global Infrastructure
GCP infrastructure is organized into **Regions** and **Zones** (isolated locations within a region), connected by Google's private global fiber network rather than the public internet, which reduces latency between regions. GCP also operates **Edge Points of Presence (PoPs)** for its CDN and networking services, and offers **Multi-region** and **Dual-region** configurations for storage resilience.

## Cloud Management Console
The **Google Cloud Console** is the web-based interface for managing resources, organized around **Projects** (the basic unit of resource organization and billing). It includes **Cloud Shell**, a free browser-based terminal with the `gcloud` CLI pre-installed, plus built-in code editor and monitoring dashboards.

## Four (4) Core Services
1. **Compute Engine** – Customizable virtual machines with per-second billing and live migration during host maintenance.
2. **Cloud Storage** – Unified object storage with Standard, Nearline, Coldline, and Archive classes for different access frequencies.
3. **Cloud SQL** – Managed relational database service supporting MySQL, PostgreSQL, and SQL Server.
4. **Identity and Access Management (IAM)** – Google Cloud's role-based access control system, tightly integrated with Google accounts and Workspace.

## Three (3) Advantages
1. **Leading AI/ML capabilities** – Vertex AI, TPUs (Tensor Processing Units), and pretrained models give GCP an edge for machine learning workloads.
2. **Best-in-class Kubernetes support** – Google Kubernetes Engine (GKE) is widely regarded as the most mature managed Kubernetes offering, since Google originated the technology.
3. **Strong data analytics tools** – BigQuery enables fast, serverless analysis of massive datasets without managing infrastructure.

## Typical Enterprise Use Cases
- Large-scale data analytics and business intelligence (BigQuery)
- AI/ML model training and deployment (Vertex AI, TPUs)
- Containerized and microservices architectures orchestrated with Kubernetes (GKE)
- High-performance computing and scientific workloads

## Screenshot
*(Insert screenshot of the GCP homepage or Cloud Console here: `screenshots/gcp-homepage.png`)*
