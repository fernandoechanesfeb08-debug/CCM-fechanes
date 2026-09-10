# AWS Research

## Brief Overview
Amazon Web Services (AWS) is the cloud computing platform operated by Amazon, launched in 2006. It is the oldest and, by market share, the largest public cloud provider, offering over 200 fully featured services spanning compute, storage, databases, networking, machine learning, analytics, and IoT. AWS is known for its breadth of services and its "pay-as-you-go" pricing model, which lets organizations of any size rent infrastructure instead of buying it.

## Global Infrastructure
AWS infrastructure is organized into **Regions** (geographically separate areas, e.g., `us-east-1`, `ap-southeast-1`) and **Availability Zones (AZs)** — physically isolated data centers within a region, usually 3 or more per region, connected by low-latency links. On top of this, AWS operates a global network of **Edge Locations** used by its CDN (CloudFront) and **Local Zones**/**Wavelength Zones** for ultra-low-latency workloads. This design lets customers build highly available, fault-tolerant applications by spreading resources across AZs and regions.

## Cloud Management Console
The **AWS Management Console** is the web-based dashboard for provisioning and monitoring resources. It groups services by category (Compute, Storage, Database, etc.), provides a global search bar, a resource groups/tag editor, and **AWS CloudShell** for browser-based command-line access. Programmatic access is also available through the **AWS CLI** and SDKs.

## Four (4) Core Services
1. **Amazon EC2 (Elastic Compute Cloud)** – Resizable virtual machines ("instances") for running applications, available in many instance families optimized for compute, memory, storage, or GPU workloads.
2. **Amazon S3 (Simple Storage Service)** – Object storage for any amount of data, with tiered storage classes (Standard, Infrequent Access, Glacier) for cost optimization.
3. **Amazon RDS (Relational Database Service)** – Managed relational databases (MySQL, PostgreSQL, MariaDB, SQL Server, Oracle, Aurora) with automated backups, patching, and scaling.
4. **AWS IAM (Identity and Access Management)** – Fine-grained control over who can access which resources, using users, groups, roles, and policies.

## Three (3) Advantages
1. **Largest service catalog and market maturity** – the widest breadth/depth of services and the largest partner and third-party tooling ecosystem.
2. **Global reach** – the most regions and availability zones of any provider, useful for low-latency, worldwide deployments.
3. **Flexible pricing** – on-demand, reserved, savings plans, and spot instances allow significant cost optimization for varying workloads.

## Typical Enterprise Use Cases
- Large-scale web and mobile application hosting with auto-scaling
- Big data analytics and data lakes (S3 + Athena/EMR/Redshift)
- Enterprise backup, disaster recovery, and archiving
- Media storage, transcoding, and content delivery via CloudFront

## Screenshot
*(<img width="1917" height="1022" alt="image" src="https://github.com/user-attachments/assets/a0f22cf9-1770-4acc-94f3-52f6c17521ac" />
)*
