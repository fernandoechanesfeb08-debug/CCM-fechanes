# Microsoft Azure Research

## Brief Overview
Microsoft Azure is Microsoft's public cloud platform, launched in 2010. Azure is distinguished by its deep integration with Microsoft's existing enterprise software ecosystem — Windows Server, Active Directory, Microsoft 365, and .NET — which makes it a natural fit for organizations already invested in Microsoft technology. Like AWS, it offers a broad catalog of compute, storage, database, AI, and networking services under a pay-as-you-go model.

## Global Infrastructure
Azure infrastructure is organized into **Regions**, grouped into **Geographies** (e.g., "United States", "Europe") that satisfy data residency and compliance requirements. Regions can be paired into **Region Pairs** for disaster recovery, and larger regions contain **Availability Zones** — physically separate locations within a region with independent power, cooling, and networking. Azure also runs a global content delivery and edge network for low-latency access.

## Cloud Management Console
The **Azure Portal** is the primary web-based console, offering a customizable dashboard, resource groups for organizing related resources, and **Azure Cloud Shell** for browser-based CLI/PowerShell access. Azure is also managed through **Azure CLI**, PowerShell modules, and **Azure Resource Manager (ARM)** templates or Bicep for infrastructure-as-code.

## Four (4) Core Services
1. **Azure Virtual Machines** – On-demand, scalable virtual machines supporting both Windows and Linux.
2. **Azure Blob Storage** – Massively scalable object storage for unstructured data, with hot, cool, and archive access tiers.
3. **Azure SQL Database** – A fully managed relational database service built on Microsoft SQL Server, with automatic tuning, scaling, and patching.
4. **Microsoft Entra ID (formerly Azure Active Directory)** – Identity and access management service that integrates directly with on-premises Active Directory and Microsoft 365.

## Three (3) Advantages
1. **Seamless integration with Microsoft products** – Windows Server, Active Directory, Microsoft 365, and .NET workloads migrate and interoperate smoothly.
2. **Strong hybrid cloud support** – tools like Azure Arc and Azure Stack let organizations manage on-premises and cloud resources together.
3. **Enterprise trust and compliance** – widely adopted in government, healthcare, and finance due to strong compliance certifications and long-standing enterprise relationships.

## Typical Enterprise Use Cases
- Migrating on-premises Windows Server/Active Directory environments to the cloud
- Hybrid cloud deployments that span on-prem data centers and Azure
- Enterprise productivity workloads integrated with Microsoft 365
- .NET application hosting and modernization

## Screenshot
*(Insert screenshot of the Azure homepage or Azure Portal here: `screenshots/azure-homepage.png`)*
