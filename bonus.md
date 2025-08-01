## 🧠 AZ-900 Bonus Questions & Concepts

These questions were gathered from Microsoft practice exams and AI-assisted study materials. They provide concise summaries and clarifications on frequently tested areas in AZ-900.

### 1️⃣ Business Continuity Across Geography

**Question**: Which Azure component allows you to replicate resources across a geography to ensure business continuity during a natural disaster at the primary site?
**Answer**: Azure Region Pairs

- Azure regions are paired within a geography to support disaster recovery and data residency
- Services like GRS (Geo-Redundant Storage) and Azure Site Recovery depend on region pairing

---

### 2️⃣ Identical Virtual Machines

**Question**: Which Azure compute service can you use to deploy and manage a set of identical virtual machines?  
**Answer**: Azure Virtual Machine Scale Sets (VMSS)

- Supports auto-scaling and uniform VM deployment.
- Integrated load balancing and fault domain spreading.

---

### 3️⃣ VNet-to-VNet Communication

**Question**: You need to allow resources on two different Azure virtual networks to communicate with each other. What should you configure?
**Answer**: VNet Peering

- Enables private communication between VNets without routing through the public Internet.
- Can be intra-region or global.

---

### 4️⃣ Azure Blob Storage Use Cases

**Question**: Which two scenarios are common use cases for Azure Blob storage?
**Answer**:

- ✅ Serving images or documents directly to a browser
- ✅ Storing data for backup and restore

- Designed for unstructured data; integrates with CDN and Archive tiers.

---

### 5️⃣ VM Location Restriction

**Question**: What can you use to restrict the deployment of a virtual machine to a specific location?
**Answer**: Azure Policy

- "Allowed Locations" policy controls geographic deployment zones.

---

### 6️⃣ Azure Cloud Shell Tools

**Question**: Which two tools are accessible via Azure Cloud Shell to manage an Azure environment?
**Answer**:

- ✅ Azure PowerShell
- ✅ Azure CLI

- Both tools come pre-authenticated and pre-installed in Cloud Shell.

---

### 7️⃣ Web-Served Unstructured Files

**Question**: Which Azure Storage service should you use to store unstructured files, such as images, that will be served on webpages?
**Answer**: Azure Blob Storage

- Ideal for image hosting, web app content delivery, and scalable storage.

---

### 8️⃣ Microsoft Purview Governance Feature

**Question**: Which feature in Microsoft Purview should you use to manage access to data sources and datasets?
**Answer**: Data Policy

- 🔹 Data Catalog: for discovery
- 🔹 Data Sharing: for collaboration
- 🔹 Data Estate Insights: for health monitoring

---

### 9️⃣ Multi-Subscription Governance

**Question**: Which Azure service allows you to manage policies across multiple subscriptions and apply compliance rules at scale?
**Answer**: Azure Blueprints

- Bundles policies, role assignments, and ARM templates for consistent deployment.

---

### 🔟 Event-Driven Architecture

**Question**: Which Azure service provides a platform for building event-driven architectures?
**Answer**: Azure Event Grid

- Routes events from sources to handlers (e.g., Azure Functions) with low latency.

---

### 1️⃣1️⃣ Subscription Scalability

**Question**: What is the maximum number of subscriptions that can be managed using Azure Blueprints?
**Answer**: Unlimited

- Blueprints scale horizontally across any number of subscriptions.

---

### 1️⃣2️⃣ Real-Time Event Processing

**Question**: Which Azure service is best suited for real-time event processing?
**Answer**: Azure Stream Analytics

- Performs near real-time data analysis on streaming sources like IoT, logs, and telemetry.

---

### 1️⃣3️⃣ Hybrid Security Monitoring

**Question**: Which Azure service is used to manage and monitor security across hybrid cloud environments?
**Answer**: Azure Security Center

- Provides threat protection, recommendations, and security score insights.

---

### 1️⃣4️⃣ Azure Portal Capabilities

**Question**: Which two actions can be performed by using Azure Portal?
**Answer**:

- ✅ Create new resources
- ✅ Create Microsoft Entra user

- Azure Portal offers GUI-driven resource and identity management.

---

### 🎯 Key Additional Azure Concepts & Notes

| Topic                   | Summary                                                  |
|-------------------------|----------------------------------------------------------|
| Health Advisories       | Proactively review for retirements and breaking changes  |
| Subscription Billing    | Billing data and invoices are generated per subscription |
| Azure SQL Database      | Managed relational database service                      |
| Azure Synapse Analytics | Big data analytics and integrated warehousing            |
| Azure Backup            | Automated backup and restore service                     |
| Microsoft Purview       | Unified compliance and data governance platform          |
| Azure Key Vault         | Manages secrets, keys, certificates securely             |
| Azure Sentinel          | Cloud-native SIEM platform using ML                      |
| Peering                 | Enables private IP communication between Azure VNets     |
| Service Endpoints       | Extend private access to PaaS services                   |
| Bastion                 | Browser-based SSH/RDP access to VMs                      |
| Azure Firewall          | Stateful, scalable firewall service                      |
| Cosmos DB               | NoSQL multi-model database with global distribution      |
