# ☁️ Module 02: Storage

## 🔸 Overview

Scalable, durable, and secure storage services in Azure. Optimized for different data types and redundancy.

## 📦 Redundancy

- In the **primary region**: data is always replicated three times
  - LRS
  - ZRS
- In the **secondary region**: based on region-pairs, and it can't be changed
  - GRS
  - GZRS

Data in the **secondary region** may not be up-to-date due to RPO (usually 15 mins).

## 🗃️ Storage Types

### Azure Blobs

Storage for unstructured data; such as text, images or binary files.

#### Tiers

| Tier     | Optimized For         | Minimum Storage Duration | Scope             |
|----------|-----------------------|-------------------------|--------------------|
| Hot      | Frequent access       | None                    | Blob or Account    |
| Cool     | Infrequent access     | 30 days                 | Blob or Account    |
| Cold     | Rare access           | 90 days                 | Blob or Account    |
| Archive  | Long-term retention   | 180 days                | Blob only          |

### Azure Files

Fully managed file shares that are accessible via **SMB** or **NFS**.

### Azure Queues

Service for storing large number of messages.

### Azure Disks

Storage volumes to be mounted on VMs.

### Azure Tables

Structured, non-relational data (NoSQL).

### Data Migration options

- **Azure Migrate**: hub to migrate from on-prem to the cloud
- **Azure Data Box**: physical device with storage capacity of up to 80 terabytes

### File Movement options

- **AzCopy**: command-line utility to copy blobs and files
- **Azure Storage Explorer**: application with a GUI to manage blobs and files
- **Azure File Sync**: tool that acts as a Windows Server
