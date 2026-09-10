# Client Recommendations

## Checkpoint 4 – Cloud Platform Recommendation Challenge

### Client A – Startup Company
**Scenario:** A startup wants to launch a new mobile application on a limited budget, expecting rapid growth.

**Recommended Platform:** AWS (or GCP — either is defensible; justify your choice)

**Justification:** A startup benefits most from a pay-as-you-go model with generous free-tier options and services that scale automatically as usage grows, so there is no large upfront infrastructure cost. AWS's mature serverless and managed-service ecosystem lets a small team ship quickly without hiring dedicated infrastructure staff, and its elasticity supports sudden growth spikes without re-architecting.

**Services the client could use:**
- **AWS Lambda** – serverless backend logic without managing servers
- **Amazon DynamoDB** – scalable NoSQL database for mobile app data
- **Amazon S3 + CloudFront** – storing and delivering app assets globally at low cost

---

### Client B – University (Windows Server, Microsoft 365, Active Directory)
**Recommended Platform:** Microsoft Azure

**Justification:** Since the university already runs Windows Server, Microsoft 365, and Active Directory, Azure offers the smoothest migration path because it extends the same identity system (Microsoft Entra ID / Entra Connect) and licensing relationships the university already has. This reduces retraining, avoids re-building authentication systems from scratch, and keeps hybrid on-prem/cloud operation simple during a gradual migration.

**Services the client could use:**
- **Microsoft Entra ID** – extends existing Active Directory to the cloud
- **Azure Virtual Machines** – lift-and-shift existing Windows Server workloads
- **Azure Virtual Desktop** – cloud-hosted desktops for students/staff

---

### Client C – AI Research Company
**Recommended Platform:** Google Cloud Platform (GCP)

**Justification:** GCP is purpose-built for high-performance AI/ML workloads, offering custom-built Tensor Processing Units (TPUs) and the Vertex AI platform for training and deploying models at scale. Its data analytics tools (BigQuery) also make it easy to prepare and query the massive datasets typically needed for research-grade machine learning.

**Services the client could use:**
- **Vertex AI** – end-to-end platform for building, training, and deploying ML models
- **Cloud TPUs** – specialized hardware acceleration for deep learning
- **BigQuery** – fast, serverless analysis of large research datasets

---

### Client D – Global E-Commerce Company
**Recommended Platform:** AWS

**Justification:** A global e-commerce company needs an infrastructure that can automatically scale with unpredictable traffic (e.g., sales events) and remain highly available across regions. AWS's global network of regions/availability zones, combined with mature auto-scaling and load-balancing services, is well suited to handle worldwide, always-on retail traffic.

**Services the client could use:**
- **Amazon EC2 Auto Scaling** – automatically adjusts compute capacity to demand
- **Elastic Load Balancing (ELB)** – distributes traffic across instances/regions
- **Amazon CloudFront** – global content delivery for fast page loads worldwide

---

## Checkpoint 6 – Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | AWS | Pay-as-you-go pricing, free tier, and elastic scaling suit limited budgets and rapid growth. |
| Enterprise Organization | AWS or Azure | Depends on existing vendor relationships; both offer mature enterprise support and compliance. |
| Microsoft Environment | Azure | Native integration with Windows Server, Active Directory/Entra ID, and Microsoft 365. |
| AI / Machine Learning | GCP | Vertex AI and custom TPUs give it an edge for training and deploying ML models. |
| Kubernetes Deployment | GCP | Google originated Kubernetes; GKE is the most mature managed offering. |
| Global Web Application | AWS | Largest global footprint of regions/availability zones plus mature auto-scaling and CDN tools. |
