# ☁️ Module 02: Compute and Networking

## 🔸 Overview

On-demand computing that provides resources and connectivity.

## 🗝️ Key Compute Services

### 🖥️ Virtual Machines (VMs)

- Type: **IaaS**
- **Scale Sets**:
  - To scale resources elastically (based on demand or schedule)
  - Identical VMs that auto-deploy a load balancer
- **Availability Sets**
  - To create redundancies in order to prevent outages or handle updates
  - **Update Domain**: same-time rebooting
  - **Fault Domain**: power source and network switch

### 🌐 Azure Virtual Desktop

- Type: **IaaS**
- User hardware desktops with Entra ID.

### 🐳 Containers

- Type: **PaaS**
- **Azure Container Apps**: incorporates scaling and load balancing
- **Azure Kubernetes Service**: orchestration service

### ⚡ Azure Functions

- Type: **Serverless**
- Event-driven, serverless computing. Billed per invocation

### 🌐 Azure App Service

- Type: **PaaS**
- HTTP-based service to build and host in conjunction with scaling and high availability
- Enables automated deployments

## 🗝️ Key Networking Components

### Azure Virtual Network (VNet)

Enables Azure resources to communicate with each other and with on-prem resources privately using **Network Security Groups (NSG)**, which enforce traffic filtering and access rules.

### Azure Virtual Private Networks

VPNs are deployed to connect two or more trusted private networks to one another over the public Internet.

### Azure VPN Gateway

Instances that are deployed in a dedicated subnet of the VNet. It supports:

- **Site-to-Site** connection: On-prem datacenters to VNets
- **Point-to-Site** connection: Individual devices to VNets
- **Network-to-Network** connection: VNets to other VNets
- **Policy-based** connection: specify statically the IP addresses of the packets that should be encrypted through each tunnel
- **Route-based** connection: modeled as a network interface or virtual tunnel interface. Use it when:
  - Connecting between VNets
  - Connecting point-to-site
  - Connecting multi-site
  - Using Azure ExpressRoute gateway

### Azure ExpressRoute

Allow a private connection between on-prem networks and Azure.

### Azure DNS

Hosting service for DNS domains that provides name resolution.

### AI-Generated Compute and Networking diagram

![AI Generated Compute Networking](../assets/ai_generated_compute_networking_v1.png)
