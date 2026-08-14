# Laboratory 03 – Multi-Cloud Explorer

## Student Information

- **Name:** Nash Khane E. Perez
- **Course/Section:** BSIT 4I
- **Instructor:** MS.JENKIELYN TORRES
- **School Year:** 2026–2027

---

# Part 1 – Multi-Cloud Platform Research

## AWS

Amazon Web Services (AWS) is a cloud computing platform that provides a wide range of services for computing, storage, networking, databases, security, and application development.

### AWS Services

- **Amazon EC2** – Virtual servers for running applications.
- **Amazon S3** – Object storage for files and data.
- **Amazon RDS** – Managed relational database service.
- **AWS IAM** – Identity and access management.
- **Amazon VPC** – Virtual networking environment.

---

## Microsoft Azure

Microsoft Azure is a cloud computing platform developed by Microsoft. It provides services for computing, storage, networking, databases, identity management, and enterprise applications.

### Azure Services

- **Azure Virtual Machines** – Virtual machines for running applications and operating systems.
- **Azure Blob Storage** – Object storage for unstructured data.
- **Azure SQL Database** – Managed relational database service.
- **Microsoft Entra ID** – Identity and access management.
- **Azure Virtual Network** – Private networking for Azure resources.

---

## Google Cloud Platform

Google Cloud Platform (GCP) is a cloud computing platform that provides infrastructure, storage, networking, databases, artificial intelligence, machine learning, and container services.

### GCP Services

- **Compute Engine** – Virtual machines for running workloads.
- **Cloud Storage** – Object storage for data and files.
- **Cloud SQL** – Managed relational database service.
- **Cloud IAM** – Identity and access management.
- **Google Kubernetes Engine (GKE)** – Managed Kubernetes service.
- **Vertex AI** – Platform for developing and deploying AI and machine learning applications.

---

# Part 2 – Cloud Platform Comparison

| Category | AWS | Microsoft Azure | Google Cloud Platform |
|---|---|---|---|
| Compute | Amazon EC2 | Azure Virtual Machines | Compute Engine |
| Storage | Amazon S3 | Azure Blob Storage | Cloud Storage |
| Database | Amazon RDS | Azure SQL Database | Cloud SQL |
| Identity | AWS IAM | Microsoft Entra ID | Cloud IAM |
| Networking | Amazon VPC | Azure Virtual Network | Google Cloud VPC |
| Kubernetes | Amazon EKS | Azure Kubernetes Service | Google Kubernetes Engine |
| AI/ML | AWS AI/ML Services | Azure AI Services | Vertex AI |

## Questions and Answers

### 1. Which cloud provider offers the broadest range of services?

AWS offers one of the broadest ranges of cloud services. It provides services for computing, storage, databases, networking, security, analytics, artificial intelligence, and many other workloads.

### 2. Which provider best integrates with Microsoft technologies?

Microsoft Azure provides the strongest integration with Microsoft technologies. It works well with Windows Server, Microsoft 365, and Microsoft identity technologies.

### 3. Which provider is strongest in Artificial Intelligence and Kubernetes?

Google Cloud Platform is particularly strong in Artificial Intelligence, Machine Learning, and Kubernetes. GCP provides services such as Vertex AI and Google Kubernetes Engine.

### 4. Which cloud platform would you personally choose and why?

I would personally choose Microsoft Azure because it provides strong enterprise capabilities and integrates well with Microsoft technologies. It would be a practical choice for organizations that already use Windows-based systems and Microsoft services.

---

# Part 3 – Client Recommendations

## Client A – Startup Company

### Recommended Platform: AWS

AWS is recommended for the startup because it provides a broad selection of cloud services that can support a mobile application from development to deployment. Its scalable infrastructure allows the startup to increase resources as the application gains more users. The startup could use **Amazon EC2** for computing, **Amazon S3** for object storage, and **Amazon RDS** for relational databases.

---

## Client B – University

### Recommended Platform: Microsoft Azure

Microsoft Azure is recommended because the university already uses Windows Server, Microsoft 365, and Active Directory. Azure provides strong integration with Microsoft's existing technologies, making migration and management more practical. The university could use **Azure Virtual Machines** for Windows-based workloads, **Microsoft Entra ID** for identity and access management, and **Azure Blob Storage** for storing data and files.

---

## Client C – AI Research Company

### Recommended Platform: Google Cloud Platform

Google Cloud Platform is recommended because the company develops Artificial Intelligence and Machine Learning applications. GCP provides services for AI, machine learning, data processing, and scalable computing workloads. The company could use **Compute Engine** for virtual machines, **Google Kubernetes Engine (GKE)** for containerized applications, and **Vertex AI** for developing and deploying AI and machine learning solutions.

---

## Client D – Global E-Commerce Company

### Recommended Platform: AWS

AWS is recommended for the global e-commerce company because it provides scalable infrastructure and services suitable for applications serving customers around the world. The company needs high availability and automatic scaling to handle changes in customer traffic and demand. It could use **Amazon EC2** for application computing, **Amazon S3** for object storage, and **Amazon EC2 Auto Scaling** to automatically adjust computing capacity.

---

# Part 4 – Linux Environment Exploration

## Linux Environment

The Linux environment was explored using the KillerCoda Ubuntu 24.04 Playground.

### Operating System

The operating system is:

- **Ubuntu 24.04.4 LTS**
- **Codename:** Noble Numbat
- **Architecture:** x86_64

The operating system was identified using:

```bash
cat /etc/os-release
```

### CPU Information

The CPU information was obtained using:

```bash
lscpu
```

The environment has:

- **CPU:** Intel Xeon E312xx (Sandy Bridge, IBRS update)
- **CPU(s):** 1
- **Architecture:** x86_64
- **Core(s) per socket:** 1
- **Thread(s) per core:** 1
- **CPU frequency:** 2.0 GHz
- **Virtualization:** KVM

### Memory Information

The memory was checked using:

```bash
free -h
```

Results:

- **Total Memory:** 1.9 GiB
- **Used Memory:** 410 MiB
- **Free Memory:** 873 MiB
- **Available Memory:** 1.5 GiB
- **Swap:** 1.0 GiB

### Disk Space

Disk space was checked using:

```bash
df -h
```

The main filesystem `/dev/vda1` has:

- **Total:** 19 GB
- **Used:** 5.4 GB
- **Available:** 13 GB
- **Usage:** 30%

---

# Part 5 – Cloud Hosting Options for Linux

A Linux server can be hosted on all three major cloud platforms.

| Cloud Provider | Cloud Service | Linux Hosting Example |
|---|---|---|
| AWS | Amazon EC2 | Ubuntu Linux virtual machine |
| Microsoft Azure | Azure Virtual Machines | Ubuntu Server virtual machine |
| Google Cloud Platform | Compute Engine | Ubuntu Linux virtual machine |

### AWS

Amazon EC2 can host a Linux virtual machine such as Ubuntu Server. It provides scalable computing resources for applications and workloads.

### Microsoft Azure

Azure Virtual Machines can host Linux operating systems such as Ubuntu Server. It is suitable for organizations that already use Microsoft Azure services.

### Google Cloud Platform

Google Compute Engine can create and run Linux virtual machines. It provides scalable computing resources for Linux-based applications.

---

# Part 6 – Key Findings

The Linux environment used in this laboratory is running **Ubuntu 24.04.4 LTS** on an x86_64 architecture. It has one virtual CPU based on an Intel Xeon E312xx processor, approximately 1.9 GiB of memory, and a 19 GB main filesystem. The environment uses KVM virtualization.

AWS, Microsoft Azure, and Google Cloud Platform can all host Linux servers through their virtual machine services. The appropriate platform depends on the organization's requirements, existing technologies, application workload, and preferred cloud services.

---

# Evidence

The Linux system information was collected using the following commands:

```bash
cat /etc/os-release
lscpu
free -h
df -h
```

Screenshots of the KillerCoda terminal output should be included as evidence for the laboratory activity.
