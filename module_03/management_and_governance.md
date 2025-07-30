# 🏛️ Module 03: Management and Governance

## 💰 Cost Management in Azure

There are six factors that affect cost:

1. Resource Type
2. Consumption
3. Maintenance
4. Geography
5. Network traffic and data costs
6. Type of consumer

### Pricing Calculator

Estimates cost for provisioning resources in Azure **with an existing subscription**.

### TCO Calculator

Estimates cost for migrating **from on-prem to Azure**.

### Azure Cost Management

Check resource costs, set budgets, create alerts and get recommendations to save money.

- **Cost Analysis**: explore and analyze organizational costs.
- **Cost Alerts**:
  - *Budget* alerts
  - *Credit* alerts
  - *Department spending quota* alerts
- **Budgets**: for subscriptions, resource group, service type, etc

### Resource Tags

A way to organize resources. It creates metadata useful for:

- Resource management
- Cost management and optimization
- Operations management
- Security
- Governance and regulatory compliance
- Workload optimization and automation

Add, modify or delete *resource tags* using: PowerShell, Azure CLI, Resource Management templates, REST API, or the Azure Portal.

### 🛡️ Azure Policy

- Creates, assigns, and manages policies to align with **corporate** standards. It helps to enforce tagging rules and conventions.
- Defined individually or bundled into **initiatives** (group of policies) for broader compliance coverage.
- Applied at the:
  - Management group
    - Subscription
      - Resource Group
        - **Or** individual resource level.

#### Use Cases

- Restrict the deployment of a virtual machine to a specific location
- Only create virtual machines of a certain size

### Microsoft Purview

- A family of data governance, risk, and compliance solutions that helps you get a single, unified view into your data
- Two main solution areas comprise it: risk and compliance (**protection of data**), and unified data governance (**data policy**)

### 🔒 Resource Locks

- Prevent resources from being accidentally deleted or modified
- They're applied regardless of **RBAC** permissions

### Microsoft Service Trust Portal

Details and controls of processes.

### Azure Arc

Manages multi-cloud and hybrid environments by projecting existing non-Azure resources into **Azure Resource Manager (ARM)** for consistent governance.

Resource Types:

- Servers
- Kubernetes clusters
- Azure data services
- SQL Server
- VMs (on preview)

### 🗂️ Azure Resource Manager (ARM)

Deployment and management service for Azure. It uses **ARM templates**, which are IaC in JSON format.

*Bicep*: language that uses declarative syntax (more readable than JSON) to deploy Azure resources (as it can be converted to **ARM templates**).

### Azure Advisor

Evaluates Azure resources and makes recommendations to help improve:

- Reliability
- Security
- Performance
- Operational Excellence
- Cost Efficiency

### Azure Service Health

Keeps track of resources and the overall status of Azure.

| Tool            | Focus    |
|-----------------|----------|
| Azure Status    | Broad    |
| Service Health  | Narrow   |
| Resource Health | Tailored |

### Azure Monitor

Platform for collecting, analyzing, visualizing, alerting, and even acting on resources' metrics.

| Tool                  | Focus                                                       |
|-----------------------|-------------------------------------------------------------|
| Azure Log Analytics   | **Write and run queries** on data gathered by Azure Monitor |
| Azure Monitor Alerts  | Monitor **logs and metrics**                                |
| Application Insights  | Monitor performance of **web apps**                         |
